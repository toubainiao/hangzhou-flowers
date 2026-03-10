# 🌸 杭州赏花日历

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen)](https://你的用户名.github.io/hangzhou-flowers)
[![高德地图](https://img.shields.io/badge/高德地图-API-blue)](https://lbs.amap.com/)

> 2025年杭州地区热门赏花地点花期指南，以日历形式呈现，支持地图定位和导航

![预览图](https://picsum.photos/seed/flowerpreview/800/400)

## ✨ 功能特性

- 📅 **日历视图** - 直观展示每日花期状态，红/橙/灰/蓝点标识
- 🗺️ **高德地图** - 集成高德地图API，精确定位和搜索
- 🔍 **智能搜索** - 输入地点自动匹配杭州地区地址
- 🌸 **花期筛选** - 支持按盛花期/初开期/将谢期/未开放筛选
- 📏 **距离排序** - 根据用户位置自动计算距离并排序
- 🚗 **一键导航** - 点击直接跳转高德地图导航
- 📱 **响应式设计** - 支持手机、平板、电脑访问

## 🚀 在线访问

**GitHub Pages地址**: https://你的用户名.github.io/hangzhou-flowers

## 🗂️ 赏花地点数据

包含杭州12个热门赏花地点：

| 地点 | 花卉 | 花期 | 地址 |
|:---|:---|:---|:---|
| 太子湾公园 | 郁金香 | 3.1-4.15 | 西湖区南山路 |
| 西湖苏堤 | 桃花 | 3.10-4.10 | 西湖区苏堤 |
| 植物园 | 梅花 | 2.1-3.20 | 西湖区桃源岭 |
| 八卦田遗址公园 | 油菜花 | 3.15-4.20 | 上城区八卦田 |
| 曲院风荷 | 樱花 | 3.20-4.15 | 西湖区北山街 |
| 良渚文化艺术中心 | 樱花 | 3.15-4.10 | 余杭区良渚 |
| 皋亭山千桃园 | 桃花 | 3.5-4.15 | 江干区天鹤路 |
| 龙井村 | 茶花 | 3.1-4.30 | 西湖区龙井村 |
| 花港观鱼 | 牡丹 | 4.1-4.25 | 西湖区西山路 |
| 径山花海 | 虞美人 | 4.1-5.15 | 余杭区径山镇 |
| 白塔公园 | 樱花 | 3.18-4.10 | 西湖区老复兴街 |
| 湘湖景区 | 木绣球 | 4.1-5.10 | 萧山区湘湖路 |

## 🛠️ 技术栈

- **前端**: HTML5 + CSS3 + JavaScript (原生)
- **地图**: 高德地图 JS API 2.0
- **部署**: GitHub Pages
- **图标**: Emoji + 系统字体

## 📦 本地运行

```bash
# 克隆仓库
git clone https://github.com/你的用户名/hangzhou-flowers.git

# 进入目录
cd hangzhou-flowers

# 用浏览器打开
open index.html
```

或者使用Live Server：
```bash
npm install -g live-server
live-server
```

## 🔑 高德Key配置

如需使用自己的高德Key，请修改 `index.html` 第538行：

```html
<script src="https://webapi.amap.com/maps?v=2.0&key=你的Key&plugin=AMap.Geocoder,AMap.PlaceSearch,AMap.Driving"></script>
```

申请地址: https://lbs.amap.com/

## 📝 更新日志

### 2025-03-10
- ✅ 完成基础功能开发
- ✅ 集成高德地图API
- ✅ 部署到GitHub Pages

## 🤝 贡献

欢迎提交Issue或PR：
- 添加新的赏花地点
- 修正花期数据
- 优化UI设计
- 修复Bug

## 📄 许可证

MIT License - 自由使用和修改

---

Made with ❤️ in Hangzhou
