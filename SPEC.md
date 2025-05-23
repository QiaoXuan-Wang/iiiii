# 音樂推薦網站專案規格書

## 專案概述
這是一個純前端的音樂推薦網站，預計部署在 GitHub Pages 上。專案採用純前端技術開發，所有外部依賴都使用 CDN 版本以確保部署的便利性。

## 技術規格
- 前端框架：Vue.js (CDN 版本)
- UI 框架：Bootstrap (CDN 版本)
- 圖示庫：Font Awesome (CDN 版本)
- 部署平台：GitHub Pages

## 功能需求
1. 音樂推薦列表顯示
   - [ ] 顯示歌曲基本資訊（歌名、歌手、專輯）
   - [ ] 顯示歌曲類別標籤
   - [ ] 提供播放連結

2. 篩選功能
   - [ ] 依照音樂類型篩選
   - [ ] 依照心情標籤篩選
   - [ ] 依照歌手篩選

3. 使用者介面
   - [ ] 響應式設計，支援手機和桌面裝置
   - [ ] 簡潔直觀的操作介面
   - [ ] 美觀的視覺設計

## 目前進度
- [x] 建立基本專案結構
- [ ] 完成首頁 HTML 結構
- [ ] 加入 CDN 相依套件
- [ ] 實作歌單資料結構
- [ ] 實作篩選功能
- [ ] 完成 UI 設計
- [ ] 測試與優化
- [ ] 部署至 GitHub Pages

## 資料結構
預計的歌曲資料結構：
```javascript
{
  id: String,
  title: String,
  artist: String,
  album: String,
  genres: Array<String>,
  mood: Array<String>,
  link: String,
  coverImage: String
}
```

## 注意事項
1. 所有外部依賴必須使用 CDN 版本
2. 確保程式碼結構清晰，便於維護
3. 注意效能優化
4. 確保跨瀏覽器相容性

## 後續發展方向
1. 加入本地儲存功能，記住使用者的收藏
2. 加入更多互動功能
3. 整合音樂串流服務 API
4. 加入更多篩選條件