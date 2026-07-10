# DADROCK - Minecraft Bedrock Edition Mods

精選最好用的 Minecraft 基岩版模組合集。

## 部署到 Cloudflare Pages

### 方式 1: 使用 Cloudflare Dashboard（推薦）

1. 進入 Cloudflare Dashboard
2. 找到 **Pages** 部分
3. 點擊 **Create a project**
4. 選擇 **Upload assets** 選項卡
5. 上傳整個 `dadrock` 資料夾的內容
6. 點擊 **Deploy** 即可

### 方式 2: 使用 Wrangler CLI

```bash
npm install -g wrangler
wrangler pages deploy .
```

## 文件結構

```
dadrock/
├── index.html          # 主頁面
├── _redirects          # 路由配置
├── robots.txt          # SEO 配置
├── package.json        # 專案配置
├── wrangler.toml       # Cloudflare Workers 配置
└── README.md          # 本檔案
```

## 功能特色

✨ 響應式設計 - 完美適配桌面和手機
🎮 6+ 精選模組展示
🔗 直接連結到模組詳情頁
📱 移動優先設計
🌙 深色主題 Minecraft 風格

## 修改內容

編輯 `index.html` 可以：
- 修改模組資訊
- 更新連結
- 調整配色

## 部署後

- 將 `dadrock` 的公開連結設定為你的自訂網域
- 例如：`dadrock.illusd.com` 或 `mods.yourdomain.com`

---

由 DADROCK 製作，基於 illusd.com 驅動
