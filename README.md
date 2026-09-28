# Quant Portfolio Site

这是为漆琪制作的 Quant Research Portfolio 网站，适合用于网申时提交给面试官或招聘方。

## 当前版本特点

- 白底明亮风格，适合正式展示与网申提交
- 每个核心项目都附有对应图片 / 图表 / 系统截图
- 单页静态网页，无需后端即可部署
- 已包含 PDF 简历与站点图标
- 内容已做公开展示版脱敏处理

## 文件结构

```text
quant_portfolio_site/
├── index.html
├── README.md
└── assets/
    ├── favicon.svg
    ├── Qiqi_Resume.pdf
    └── projects/
        ├── aiquantalpha.png
        ├── a_share_factor.png
        ├── factor_combo.png
        ├── tail_alpha.png
        ├── noon_strategy.png
        ├── futures_ls.png
        ├── coin_alert.png
        ├── kronos.png
        ├── multi_agent.png
        └── live_trading.png
```

## 本地打开

直接双击 `index.html` 即可在浏览器打开。

## 推荐部署方式

### 1. GitHub Pages

- 新建一个 GitHub 仓库，例如 `quant-portfolio`
- 上传整个文件夹内容
- 在仓库 `Settings -> Pages` 中选择从 `main` 分支部署
- 部署后即可获得公开链接，例如：

```text
https://yourname.github.io/quant-portfolio/
```

### 2. Vercel / Netlify

- 注册并登录 Vercel 或 Netlify
- 直接上传整个项目文件夹或 ZIP
- 选择静态站点部署即可

## 使用建议

- 网申时填写部署后的公开 URL，不要填写本地路径
- 若想进一步增强展示效果，可以继续加入项目子页面、更多图表、回测净值明细与代码片段（公开可展示版）

