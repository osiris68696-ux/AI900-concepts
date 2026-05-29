# GitHub Pages 部署步驟

## 第一次部署

1. 登入 GitHub：<https://github.com>
2. 點右上角 `+`，選 `New repository`
3. Repository name 建議填：

```text
ai900-concepts
```

4. Visibility 可選 `Public`
5. 不要勾選新增 README，因為資料夾裡已經有 README
6. 建立 repository
7. 在 repository 首頁點 `uploading an existing file`
8. 上傳這些檔案到根目錄：
   - `index.html`
   - `styles.css`
   - `app.js`
   - `robots.txt`
   - `.nojekyll`
   - `README.md`
9. 點 `Commit changes`
10. 到 `Settings` > `Pages`
11. `Build and deployment` 的 Source 選 `Deploy from a branch`
12. Branch 選 `main`，資料夾選 `/root`
13. 點 `Save`

幾分鐘後會得到網址：

```text
https://你的GitHub帳號.github.io/ai900-concepts/
```

## 之後更新網站

如果只是小改：

1. 到 GitHub repository
2. 點要更新的檔案，例如 `app.js`
3. 點鉛筆圖示編輯
4. 貼上新版內容
5. 點 `Commit changes`
6. GitHub Pages 會自動重新部署

如果一次改很多檔：

1. 到 repository 首頁
2. 點 `Add file` > `Upload files`
3. 拖曳新版檔案覆蓋
4. 點 `Commit changes`
5. GitHub Pages 會自動更新

## 搜尋引擎設定

這個網站已經包含：

- `robots.txt`
- `<meta name="robots" content="noindex, nofollow, noarchive" />`

用途是告訴搜尋引擎不要收錄。這不是密碼保護；有網址的人仍然可以開啟。
