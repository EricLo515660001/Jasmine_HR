# 2026 環安／工安招募成效分析（GitHub Pages）

本專案是純靜態網站，**無需安裝套件或建置**，所有 CSS、JavaScript 和彙總統計均包含於 `index.html`。

## 部署到 GitHub Pages

1. 在 GitHub 建立新的 repository（建議使用 **Private**，但請先確認 GitHub Pages 的可見性政策）。
2. 上傳 `index.html`、`.nojekyll` 和此 `README.md` 到 repository 的 `main` 分支根目錄。
3. 開啟 repository 的 **Settings → Pages**。
4. 在 **Build and deployment** 將 Source 設為 **Deploy from a branch**，Branch 設為 `main`，Folder 選 `/ (root)`，按 Save。
5. 部署完成後，GitHub 會在 Pages 設定頁顯示網站網址。

## 注意

- GitHub Pages 網站可能公開可見：即使來源 repository 為 Private，也**不要假設網站只有公司同仁能看**。部署前請依公司資安與個資政策確認是否允許公開這些統計。
- 目前網頁只有彙總統計，沒有放入個別候選人資料或原始 Excel。
- 若要更新數據，需要修改 `index.html` 的 `monthly` 以及 KPI 內容；不會自動連動 Excel。
- 可直接雙擊 `index.html` 在本機瀏覽器預覽；按「列印／另存 PDF」可列印報告。
