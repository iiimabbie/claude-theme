# 🌸 Claude AI 自訂主題包 🌸

![GitHub license](https://img.shields.io/badge/license-MIT-pink.svg)
![Version](https://img.shields.io/badge/version-1.3.0-ff69b4)
![Stylus](https://img.shields.io/badge/stylus-%E2%9C%93-pink.svg)

> 💖 讓你的 Claude AI 介面變得更有個性！提供多種風格主題選擇 💖 

## 🎨 主題選擇

### 🌸 少女心主題 (claude-pink-theme.user.css)
- 🎀 **甜美粉紅色系** - 溫暖的粉紅色調，營造可愛氛圍
- 💕 **少女風字體** - 使用 "New Tegomin" 襯線字體
- 🎐 **漂浮動畫** - 櫻花與小熊裝飾，增添生動感
- 🌞 **明亮模式** - 適合白天使用的明亮配色

### 🌤️ 夏日清新主題 (claude-summer-theme.user.css)
- 🌊 **清爽藍色系** - 夏日海洋般的藍色調
- 🌈 **多彩標題** - 不同層級標題使用不同顏色
- ☁️ **夏日裝飾** - 藍心與雲朵動畫效果
- 🎋 **日系字體** - 使用 "Kiwi Maru" 日系字體

## 📸 截圖展示
*(暫空)*
<!-- 
<p align="center">
  <img src="screenshots/主頁.png" width="600" />
  <br>
  <em>粉紅主題預覽</em>
</p>

<div align="center">
<details>
  <summary>(點擊查看更多截圖)</summary>
  
  ### 聊天界面展示
  <img src="screenshots/聊天室內.png" width="80%" />
  
  ### 區塊展示
  <img src="screenshots/text-block.png" width="80%" />
  
  ### h1~h6+字樣展示
  <img src="screenshots/h1~h6+字樣.png" width="80%" />
</details>
</div> -->

## 🔧 安裝方法

1. 首先安裝 [Stylus](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne) 瀏覽器擴充功能

2. 選擇你喜歡的主題並點擊安裝：

   **少女心主題　：**
   [![安裝粉紅主題](https://img.shields.io/badge/%E5%AE%89%E8%A3%9D%E7%B2%89%E7%B4%85%E4%B8%BB%E9%A1%8C-pink?style=for-the-badge)](https://github.com/iiimabbie/claude-theme/raw/main/claude-pink-theme.user.css)

   **夏日清新主題：**
   [![安裝夏日主題](https://img.shields.io/badge/%E5%AE%89%E8%A3%9D%E5%A4%8F%E6%97%A5%E4%B8%BB%E9%A1%8C-blue?style=for-the-badge)](https://github.com/iiimabbie/claude-theme/raw/main/claude-summer-theme.user.css)

*或者手動安裝：*

1. 在 Stylus 中建立新樣式
2. 複製對應主題 CSS 檔案中的代碼
3. 將其套用於 `claude.ai` 域名

## 🛠️ 自訂修改

每個主題都有清楚的 CSS 變數設定，方便你調整顏色：

```css
:root {
    /* 粉紅主題變數 */
    --bg-color: #FDF0ED;        /* 背景色 */
    --text-color: #945E63;      /* 文字色 */
    --accent: #945E63;          /* 重點色 */
    
    /* 夏日主題變數 */
    --bg-color: #FFF8ED;        /* 背景色 */
    --text-color: #6182B8;      /* 文字色 */
    --accent: #6182B8;          /* 重點色 */
}
```

## 🌈 自訂頭像

想要更換聊天頭像？

1. 準備圖片並轉換為 base64 編碼
2. 在 CSS 中找到這段代碼：
   ```css
   background-image: url('這裡填上你的圖片base64編碼') !important;
   ```
3. 替換成你的 base64 編碼

## ⚠️ 兼容性

- ✅ **Chrome**: 已完整測試
- ❓ **Firefox/Safari**: 未測試但應該可用
- 📱 **模式支援**: 
  - 粉紅主題：明亮模式
  - 夏日主題：明亮模式
- ⚠️ **Claude 版本**: 可能隨介面更新需要調整

## 💌 貢獻與反饋

發現問題或有建議？歡迎：
1. 開一個 [issue](https://github.com/iiimabbie/claude-theme/issues)
2. 提交 PR 貢獻你的主題

## 🙏 致謝

- 字體來源: [Google Fonts](https://fonts.google.com/)
- 靈感來源: 想讓 AI 聊天變得更有趣

---

### 💭 為什麼要用這些主題？

因為預設的介面太無聊了！讓你的 Claude 變得更有個性，每次聊天都像是在跟可愛的朋友對話 (◕‿◕)♡

---

## 📜 許可證

MIT © [iiimabbie](https://github.com/iiimabbie)