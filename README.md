# 美容面罩产品原型设计

## 项目概述

这是一个美容面罩产品的Web端高保真原型设计，包含商城和社区功能。设计风格参考 [Umitec Beauty](https://umitecbeauty.com/)，功能特性参考 [Govee](https://www.govee.com/)。

## 技术栈

- **HTML5** - 页面结构
- **Tailwind CSS** - 样式框架（CDN）
- **Font Awesome** - 图标库（CDN）
- **Unsplash/Pexels** - 图片资源

## 项目结构

```
web/
├── index.html              # 主入口页面（iframe网格展示）
├── home.html              # 首页
├── shop.html              # 商城页面
├── product-detail.html    # 产品详情页
├── community.html         # 社区页面
├── profile.html           # 个人中心
├── cart.html              # 购物车
├── custom.css             # 自定义样式
└── README.md             # 项目说明
```

## 页面说明

### 1. index.html
主入口页面，使用iframe方式嵌套所有其他页面，以grid网格形式展示所有原型界面。

### 2. home.html
首页，包含：
- Hero区域（产品主推）
- 科学背书（SGS认证、临床验证等）
- 产品特色
- 热门产品展示
- 客户评价
- 社区动态

### 3. shop.html
商城页面，包含：
- 分类筛选
- 产品列表（网格布局）
- 排序功能
- 分页

### 4. product-detail.html
产品详情页，包含：
- 产品图片展示
- 产品信息
- 规格选择
- 用户评价
- 产品详情标签页

### 5. community.html
社区页面，包含：
- 发布区域
- 话题标签
- 帖子列表
- 侧边栏（热门话题、推荐用户）

### 6. profile.html
个人中心，包含：
- 个人信息
- 统计信息
- 我的订单
- 我的收藏

### 7. cart.html
购物车页面，包含：
- 商品列表
- 数量调整
- 订单摘要
- 推荐商品

## 设计特点

1. **现代化UI设计**
   - 简洁清晰的布局
   - 渐变色彩搭配
   - 卡片式设计
   - 悬停动画效果

2. **用户体验优化**
   - 响应式设计
   - 清晰的导航结构
   - 直观的操作流程
   - 友好的交互反馈

3. **产品展示**
   - 突出产品特色
   - 科学背书展示
   - 客户评价展示
   - 促销信息醒目

## 使用方法

1. 直接在浏览器中打开 `index.html` 查看所有页面原型
2. 或单独打开各个HTML文件查看具体页面
3. 所有页面使用CDN引入Tailwind CSS和Font Awesome，无需本地安装

## 注意事项

- 图片资源来自Unsplash，需要网络连接
- 所有页面为静态原型，无后端交互功能
- 代码结构清晰，便于转换为Figma文件进行二次编辑

## 设计规范

- 主色调：粉色（#EC4899）到紫色渐变
- 字体：系统默认字体栈
- 圆角：统一使用rounded-lg/rounded-xl
- 间距：使用Tailwind标准间距系统
- 阴影：统一使用shadow-md/shadow-lg

