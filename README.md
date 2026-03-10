# 我的作品集 (Jekyll GitHub Pages)

這是一個基於 Jekyll 的自動化作品集網站。

## 如何使用

1. **新增專案**：將你的 HTML 檔案放入 `_posts/` 資料夾。
2. **檔案命名**：檔案名稱必須符合 `YYYY-MM-DD-filename.html` 格式。
3. **Front Matter**：在 HTML 檔案最頂端加入以下資訊：
   ```html
   ---
   layout: post
   title: "專案標題"
   description: "專案簡介"
   thumbnail: "預覽圖網址"
   ---
   ```
4. **自動更新**：推送至 GitHub 後，主頁會自動生成對應的卡片。

## 本地預覽 (選配)

如果你有安裝 Ruby 和 Jekyll，可以執行：
```bash
bundle exec jekyll serve
```
然後在瀏覽器打開 `http://localhost:4000`。
