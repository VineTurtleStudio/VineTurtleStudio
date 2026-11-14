<div align="center">

# 藤栖龟舍 · VineTurtleStudio 官网

**工作室官方网站（纯静态，无构建步骤）**

<a href="#-简体中文">简体中文</a> ·
<a href="#-繁體中文">繁體中文</a> ·
<a href="#-english">English</a> ·
<a href="#-日本語">日本語</a>

</div>

---

## 🇨🇳 简体中文

藤栖龟舍的官方网站。整站是纯 **HTML + CSS + 原生 JavaScript**，没有构建步骤、没有依赖，改完直接刷新即可看到效果。

> 状态：建设中。当前为首页骨架（「藤栖之域」「龟舍时光」两个板块）。

### 目录结构

```
index.html                  首页
CSS/style.css               全站样式
JS/script.js                交互脚本
Resources/images/           图片资源（含 logo）
```

### 本地预览

直接双击 `index.html` 即可。若需要更接近线上的行为（相对路径、跨域限制），起一个静态服务器：

```bash
python -m http.server 8000
# 然后访问 http://127.0.0.1:8000/
```

或用 Node：

```bash
npx serve .
```

### 部署

任何静态托管都能直接用，构建产物就是这几份文件本身：

- GitHub Pages：仓库 Settings → Pages → 选择分支根目录
- 任意静态主机：把 `index.html`、`CSS/`、`JS/`、`Resources/` 一起上传

### 修改约定

- 颜色、间距统一走 `CSS/style.css` 顶部的自定义属性，不要在 HTML 里写内联样式
- 图片放 `Resources/images/`，文件名用小写和连字符，避免中文与空格
- 新增板块时同步更新 `JS/script.js` 里的导航高亮逻辑

## 🇹🇼 繁體中文

藤棲龜舍的官方網站。整站是純 **HTML + CSS + 原生 JavaScript**，沒有建置步驟、沒有相依套件，改完重新整理即可看到效果。

> 狀態：建置中。目前為首頁骨架（「藤棲之域」「龜舍時光」兩個區塊）。

### 目錄結構

```
index.html                  首頁
CSS/style.css               全站樣式
JS/script.js                互動腳本
Resources/images/           圖片資源（含 logo）
```

### 本機預覽

直接雙擊 `index.html` 即可。若要更接近線上行為（相對路徑、跨域限制），可啟動靜態伺服器：

```bash
python -m http.server 8000
# 開啟 http://127.0.0.1:8000/
```

### 部署

任何靜態託管都能直接使用，建置產物就是這幾個檔案本身：

- GitHub Pages：Settings → Pages → 選擇分支根目錄
- 任意靜態主機：上傳 `index.html`、`CSS/`、`JS/`、`Resources/`

### 修改約定

- 顏色、間距統一使用 `CSS/style.css` 頂部的自訂屬性，不要在 HTML 寫行內樣式
- 圖片放 `Resources/images/`，檔名用小寫與連字號，避免中文與空白
- 新增區塊時同步更新 `JS/script.js` 的導覽高亮邏輯

## 🇬🇧 English

The official website of VineTurtleStudio. The whole site is plain **HTML + CSS + vanilla JavaScript** — no build step, no dependencies. Edit a file, refresh, done.

> Status: under construction. Currently the home page skeleton ("藤栖之域" and "龟舍时光" sections).

### Structure

```
index.html                  home page
CSS/style.css               global styles
JS/script.js                interaction script
Resources/images/           images (incl. logo)
```

### Preview locally

Just open `index.html`. For behaviour closer to production (relative paths, CORS rules), serve it:

```bash
python -m http.server 8000
# then open http://127.0.0.1:8000/
```

or with Node:

```bash
npx serve .
```

### Deploy

Any static host works — the build output is these files themselves:

- GitHub Pages: repo Settings → Pages → serve from the branch root
- Any static host: upload `index.html`, `CSS/`, `JS/`, `Resources/`

### Conventions

- Put colours and spacing in the custom properties at the top of `CSS/style.css`; avoid inline styles
- Images go in `Resources/images/`, lowercase with hyphens, no CJK characters or spaces
- When adding a section, update the nav-highlight logic in `JS/script.js`

## 🇯🇵 日本語

藤棲亀舎の公式サイトです。**HTML + CSS + 素の JavaScript** のみで、ビルドも依存関係もありません。編集して再読み込みすれば反映されます。

> 状態：制作中。現在はトップページの骨組み（「藤栖之域」「龟舍时光」の 2 セクション）。

### 構成

```
index.html                  トップページ
CSS/style.css               全体のスタイル
JS/script.js                インタラクション
Resources/images/           画像（ロゴ含む）
```

### ローカル確認

`index.html` をそのまま開けます。本番に近い挙動（相対パス・CORS）を確認したい場合：

```bash
python -m http.server 8000
# http://127.0.0.1:8000/ を開く
```

### デプロイ

静的ホスティングならどこでも可。成果物はこのファイル群そのものです。

- GitHub Pages：Settings → Pages → ブランチ直下を指定
- 任意の静的ホスト：`index.html`、`CSS/`、`JS/`、`Resources/` をアップロード

### 編集ルール

- 色・余白は `CSS/style.css` 冒頭のカスタムプロパティで管理（インラインスタイルは使わない）
- 画像は `Resources/images/` に小文字＋ハイフン名で配置
- セクション追加時は `JS/script.js` のナビハイライトも更新
---

## 许可 / License

本项目以 [MIT](./LICENSE) 许可证发布。

Licensed under the [MIT License](./LICENSE).
