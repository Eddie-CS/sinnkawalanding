# Sinnkawa Landing

Sinnkawa Singapore 是一个致力于推广可爱文化的品牌。本仓库包含品牌官网的静态着陆页，使用纯 HTML、CSS 与 JavaScript 编写，可直接在浏览器中打开。

## 特色功能

- **倒计时页面**：进入网站后会看到开站倒计时提示。
- **AI 创意工坊**：输入关键词，由 Gemini API 生成押韵的中文标语（需自行在代码中配置 API key）。
- **主题门店展示**：提供多家新加坡门店的图片与地图链接。
- **双语支持**：点击页面右上角按钮可在中文与英文界面之间切换。

## 本地预览

1. 克隆仓库后直接打开 `index.html` 即可查看效果；或在项目根目录运行
   ```bash
   python3 -m http.server 8000
   ```
   然后访问 [http://localhost:8000](http://localhost:8000)。
2. 若要使用 AI 创意工坊，需要在 `index.html` 中的 `apiKey` 变量处填入有效的 Gemini API 密钥。

## 部署

网站可通过 GitHub Pages 部署。仓库中的 `CNAME` 文件已指向 `www.sinnkawa.com.sg` 域名，直接推送到主分支即可发布。

欢迎提交 issue 或 PR 共同改进页面。
