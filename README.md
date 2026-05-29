# 亚克力小五金外贸买家画像报告

全球亚克力小五金外贸买家画像可视化报告 | Global Acrylic Hardware Export Buyer Personas

## 📊 项目概述

本项目是一个交互式的市场分析仪表板，呈现全球亚克力小五金采购商的详细画像，分为四大市场类别：

- **高端定制市场** (20%) - 奢华品牌与设计师
- **大众性价比市场** (45%) - 零售连锁与电商平台
- **新兴增长市场** (25%) - 本地品牌与DTC企业
- **专业机构市场** (10%) - 实验室与工业应用

## 🚀 快速开始

### 本地预览
直接在浏览器中打开 `index.html` 文件即可预览。

### 在线访问
通过 GitHub Pages 访问：[https://kimiqian11.github.io/ki-mi](https://kimiqian11.github.io/ki-mi)

## 📋 主要特性

✅ 响应式设计 - 完全适配桌面、平板和手机设备  
✅ 彩色分类 - 四色系统清晰区分市场类别  
✅ 交互效果 - 卡片悬停动画提升用户体验  
✅ 中文本地化 - 全中文界面展示  
✅ 无依赖 - 纯HTML/CSS实现，无需额外库

## 📁 文件结构

```
ki-mi/
├── index.html          # 主要报告页面
├── README.md           # 项目说明文档
└── .github/
    └── workflows/
        └── deploy.yml  # GitHub Pages 自动部署配置
```

## 🔧 技术栈

- HTML5
- CSS3 (Grid & Flexbox 布局)
- 响应式设计
- 无外部依赖

## 📝 内容说明

### 产品核心优势
- 92% 高透光 - 水晶质感
- 轻量化 50% - 相比金属/玻璃
- 低成本替代 - 奢华感方案
- 耐候抗腐蚀 - 不生锈、不变黄

### 四大市场类别详情

每个市场卡片包含：
- 市场份额预估与进度条
- 重点国家列表
- 目标客户类型
- 核心采购偏好标签
- 服务重点说明

## 🌐 部署方式

### GitHub Pages (推荐)

**部署步骤：**

1. 进入仓库的 **Settings** (设置)
2. 左侧菜单找到 **Pages**
3. 在 "Build and deployment" 部分：
   - **Source** 选择 "GitHub Actions"
4. 自动部署配置已启用
5. 每次推送到 `main` 分支都会自动部署
6. 网站将在 **https://kimiqian11.github.io/ki-mi** 发布

### 自定义部署

可部署到任何静态网站托管服务：

**Netlify:**
- 连接 GitHub 仓库 → 自动部署
- 访问: https://app.netlify.com/

**Vercel:**
- 导入项目 → 自动部署
- 访问: https://vercel.com/

**AWS S3 + CloudFront:**
- 上传 `index.html` 到 S3 桶
- 配置 CloudFront 分发

**阿里云 OSS:**
- 手动上传文件或使用 ossutil 工具

## 🔄 更新流程

1. 修改 `index.html` 或其他文件
2. 提交并推送到 `main` 分支
3. GitHub Actions 自动触发
4. 网站自动更新（通常 < 1 分钟）

## 📞 故障排查

**GitHub Pages 未显示？**
- 确认仓库设置中 Pages 已启用
- 检查 Actions 标签页看是否有构建错误
- 清除浏览器缓存后重新访问

**需要自定义域名？**
- 在 Pages 设置中添加 "Custom domain"
- 配置 DNS 记录

## 📄 许可证

此项目可自由使用和修改。

---

**最后更新**: 2026-05-29  
**作者**: 外贸战略研究小组
