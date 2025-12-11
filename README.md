# Ciel's Discord Themes

## 前置作業
在開始套用主題之前，請先完成以下步驟：

1. 安裝 [Vencord](https://vencord.dev)
2. [下載主題包](https://github.com/ShiroOYuki/Ciel-s-discord-themes/releases/latest/download/ciel_shota.zip)

## 啟用主題
開啟已安裝好 Vencord 的 Discord，並依照下列步驟：

1. 使用者設定 -> Vencord -> Themes
2. Local Themes -> Open Themes Folder
3. 將下載的主題包解壓縮到 `{你的路徑}/Vencord/userdata/themes` 資料夾中
4. 回到 Discord -> 勾選 `Ciel's Shotas`

## 自訂主題
開啟 `ciel_shota.theme.css` 後，你應該可以在檔案的一開始看到：
```
:root {
    /* 背景圖片 */
    --bg: url("./ciel_shota/background/default.png");
    --bg-brightness: 30%;           /* 亮度 */

    /* 左下角 - 個人面板背景圖片 */
    --bg-panel: url("./ciel_shota/panel/default.png");
    --bg-panel-brightness: 30%;     /* 亮度 */

    /* 右側成員列表背景圖片 */
    --bg-sidebar: url("./ciel_shota/sidebar/default.png");
    --bg-sidebar-brightness: 50%;   /* 亮度 */
    
    /* 伺服器 - 身分組標題顏色 */
    --category-color: #68aceb;

    --textbar-decoration-fg: url("./ciel_shota/decoration/textbar_foreground.png");
    --textbar-decoration-bg: url("./ciel_shota/decoration/textbar_background.png");
}
```

這裡可以修改各個位置的圖片以及亮度，例如：
```
--bg: url("./ciel_shota/example.png");
--bg-brightness: 30%;
```

這段的意思是把背景圖片設為 `ciel_shota.theme.css` 所在資料夾中，名為 `ciel_shota` 的資料夾中名為 `example.png` 的圖片，並將亮度設為 `30%`。

## 其他

- 目前此主題包還有部分頁面未設定到，請多多包涵。
- 隨著 Discord 更新，此主題包可能會失效，如果有更新會在 [我的 DC 伺服器](https://discord.gg/4ZhpKYTjFm) 中發佈通知。
- 僅[安裝 css](https://github.com/ShiroOYuki/Ciel-s-discord-themes/releases/latest/download/ciel_shota.css)