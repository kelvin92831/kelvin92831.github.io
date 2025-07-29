# My Hexo Blog

這是一個使用 Hexo 框架建立的個人部落格，部署在 GitHub Pages 上。

## 本地開發

### 安裝依賴
```bash
npm install
```

### 本地預覽
```bash
npm run server
```
然後在瀏覽器中打開 `http://localhost:4000`

### 構建靜態文件
```bash
npm run build
```

## 部署到 GitHub Pages

### 方法一：使用 GitHub Actions（推薦）

1. 在 GitHub 上創建一個名為 `kelvin92831.github.io` 的倉庫
2. 將本地代碼推送到 GitHub：
   ```bash
   git remote add origin https://github.com/kelvin92831/kelvin92831.github.io.git
   git push -u origin main
   ```
3. 在 GitHub 倉庫設置中啟用 GitHub Pages，選擇 `gh-pages` 分支作為源
4. 每次推送代碼到 `main` 分支時，GitHub Actions 會自動構建並部署

### 方法二：手動部署

```bash
npm run deploy
```

## 寫新文章

```bash
hexo new "文章標題"
```

## 主題

目前使用的是 `landscape` 主題。你可以在 `_config.yml` 中修改主題設置。

## 配置

主要配置文件是 `_config.yml`，你可以根據需要修改：

- 網站標題和描述
- 作者信息
- 部署設置
- 主題設置

## 訪問地址

部署完成後，你的部落格將可以通過以下地址訪問：
https://kelvin92831.github.io 