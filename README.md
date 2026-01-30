# LeadMeHome - 带你回家 🚀

**现代网页版** - 基于 React + TypeScript + Tailwind CSS 重构的益智类游戏

## 项目简介

这是一个经典的"带你回家"益智游戏的现代化重写版本。玩家需要通过鼠标或触摸控制，将所有的 emoji 小球引导到安全的家中区域，同时避开黑洞的陷阱。

## 快速开始

### 安装依赖
```bash
npm install
```

### 开发模式运行
```bash
npm start
```

### 构建生产版本
```bash
npm run build
```

## 游戏玩法

1. **目标**：将所有的 emoji 小球安全送回家
2. **控制方式**：
   - 鼠标移动控制引力点
   - 触摸屏支持直接拖拽
3. **障碍物**：
   - 黑洞：会吞噬小球
   - Wormhole：传送门
   - 障碍墙：小球会反弹
4. **特殊墙**：
   - 加速墙（红色）：增加小球速度
   - 减速墙（绿色）：降低小球速度

## 技术栈

- **前端框架**: React 18
- **类型系统**: TypeScript
- **样式方案**: Tailwind CSS
- **构建工具**: Vite
- **状态管理**: Redux Toolkit
- **路由管理**: React Router v6
- **游戏引擎**: Canvas API

## 项目结构

```
src/
├── components/     # React 组件
│   ├── gamePage/  # 游戏页面
│   ├── mainPage/  # 主页面
│   └── ...
├── game/          # 游戏核心逻辑
│   ├── game.ts    # 游戏主类
│   └── levelData.ts # 关卡数据
├── store/         # Redux 状态管理
├── router/        # 路由配置
└── styles/        # 全局样式
```

## 开发说明

项目采用现代化的技术栈，具备以下特点：

- 🎯 **响应式设计** - 支持桌面端和移动端
- ⚡ **高性能** - 使用 Canvas 实现流畅的游戏体验
- 🎨 **美观界面** - Tailwind CSS 打造现代化 UI
- 🔧 **易维护** - TypeScript + ESLint 保证代码质量
- 📱 **移动友好** - 触摸控制优化

## 部署

游戏已部署在以下地址：
https://your-game-url.com

## 许可证

MIT License

---

*由 Bobo 工作室重写并维护*