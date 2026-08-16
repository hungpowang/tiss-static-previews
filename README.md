# TISS Static Previews

以 GitHub Pages 發布工作中產生的靜態 HTML，供同事透過公開網址預覽。

## 目前內容

- `/recruiting/project-manager/`
- `/recruiting/product-manager/`
- `/recruiting/qa-engineer/`

## 新增預覽頁

1. 建立語意清楚的英文目錄，例如 `meeting/project-review/`。
2. 將單檔 HTML 命名為該目錄下的 `index.html`。
3. 如有圖片或 CSS 等資源，放在同一目錄並使用相對路徑。
4. 在根目錄 `index.html` 加入入口連結。
5. 提交並推送到 `main`，GitHub Pages 會自動更新。

## 注意事項

這是公開儲存庫與公開網站。`noindex` 只是在頁面中要求搜尋引擎不要收錄，並不是存取控制；請勿上傳機密資料、個人資料或未授權公開的內容。
