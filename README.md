# ConvenTec 公司介绍（中英双语）

ConvenTec 会展数字化服务商官网单页，含中 / EN 一键切换。

## 部署

- 入口：`index.html`（单页自包含，含内联 CSS/JS）
- 图片：`assets/` 目录需与 `index.html` 同级上传
- 字体：通过 CDN（miaoda.feishu.cn）加载，线上可用
- 语言选择：localStorage 记忆，刷新保持

### GitHub Pages

1. 将本目录内容推送到 GitHub 仓库（index.html 与 assets/ 放在仓库根目录）
2. 仓库 Settings → Pages → Source 选择分支（main / 根目录）并保存
3. 访问 `https://<用户名>.github.io/<仓库名>/`

无需构建，纯静态托管即可。
