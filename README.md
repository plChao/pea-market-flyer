# Python 觀念題猜題

一頁式靜態網站，8 題 Python 觀念單選題，送出答案後顯示每題詳解與得分。純 HTML/CSS/JS，無需任何建置工具或後端。

## 本機預覽

直接用瀏覽器打開 `index.html` 即可，或用簡易伺服器：

```bash
python3 -m http.server 8000
```

再開啟 http://localhost:8000

## 部署到 Netlify Drop

1. 前往 https://app.netlify.com/drop
2. 把整個資料夾（或至少 `index.html`）拖曳到頁面上即可完成部署，會拿到一個線上網址。

## 部署到 Netlify（連結 GitHub，之後可自動更新）

1. 先把這個資料夾推上 GitHub（見下方指令）。
2. 到 Netlify 選 **Add new site → Import an existing project**，選擇 GitHub 並授權。
3. 選取這個 repo，Build command 留空、Publish directory 填 `.`（或 `/`），完成部署。
4. 之後每次 push 到 GitHub，Netlify 會自動重新部署。

### 推上 GitHub

```bash
git remote add origin <你的 GitHub repo 網址>
git branch -M main
git push -u origin main
```
