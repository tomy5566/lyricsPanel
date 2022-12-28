# 歌詞串接API練習專案 Readme
lyricsPanel axios for API

## 主要介紹
使用axios搭配Bootstrap建立經典專輯ADELE 25 歌詞查詢網頁。

## DEMO link
[https://tomy5566.github.io/lyricsPanel/](https://tomy5566.github.io/lyricsPanel/)

## 使用技術
- HTML
- CSS: [flex](https://developer.mozilla.org/zh-CN/docs/Web/CSS/flex)
- JavaScript
- AJAX : [axios](https://github.com/axios/axios)
- [Bootstrap](https://getbootstrap.com/)

## JavaScript 使用技術介紹

1. 使用 AJAX : [axios](https://github.com/axios/axios)串接歌詞的 API，取得經典專輯ADELE 25資料。
2. 使用[Bootstrap](https://getbootstrap.com/)建立版型，包含導覽列，歌曲點選，歌詞顯示區域。
3. 建立動態歌曲選單陣列，並利用 [Element.innerHTML](https://developer.mozilla.org/zh-TW/docs/Web/API/Element/innerHTML) 渲染左側歌曲名稱選單。
4. 使用 [Element.classList](https://developer.mozilla.org/en-US/docs/Web/API/Element/classList) 變動元素標籤，偽元素製造透明背景，創造視覺互動效果。
5. 利用 [CSS position fixed](https://www.w3schools.com/css/css_positioning.asp) 設計表頭與表尾的固定位置。

## 功能介紹
- 左側選單顯示 [Adele 的經典專輯 25 ](https://en.wikipedia.org/wiki/25_(Adele_album))的曲目。
- 點選左側曲目，歌詞內容和曲目名稱，會顯示在右側欄位中。
- 點選左側曲目時，會有色彩變化清楚知道該曲目已被選取。
- 表頭與表尾固定在上下位置，放置背景圖片，美化版面。

## 介面展示
![image](https://github.com/tomy5566/lyricsPanel/blob/main/Lyrics_demo_gif.gif)


## 參考資料
六角學院JavaScrip線上課程
ALPHA Camp 網路資源
