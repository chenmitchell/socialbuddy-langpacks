# SocialBuddy 語言包 / Language Packs

<p align="center">
  <strong>🌐 社群小幫手多語言翻譯</strong><br>
  讓 <a href="https://github.com/chenmitchell/social-buddy-release">SocialBuddy</a> 說你的語言。
</p>

---

> **還沒裝 SocialBuddy？** 👉 [先到這裡下載擴充功能](https://github.com/chenmitchell/social-buddy-release)，裝好再回來拿語言包。

## 目前有的語言

| 資料夾 | 語言 | Language |
|--------|------|----------|
| `zh_CN` | 簡體中文 | Simplified Chinese |
| `ja` | 日本語 | Japanese |
| `ko` | 한국어 | Korean |
| `es` | Español | Spanish |
| `pt_BR` | Português (Brasil) | Brazilian Portuguese |

> 繁體中文和英文已經內建在擴充功能裡，不用另外裝。

## 怎麼裝？

### 介面翻譯（_locales）

1. 在上面的表格找到你要的語言資料夾
2. 點進 `locales/` → 下載整個語言資料夾（例如 `ja/`）
3. 找到你電腦上 SocialBuddy 擴充功能的安裝資料夾
4. 把下載的資料夾丟進 `_locales/` 裡面
5. 到 `chrome://extensions/` 重新載入擴充功能

### 快速回覆範本

1. 到 `canned-templates/` 下載你要的語言 JSON（例如 `ja.json`）
2. 打開 SocialBuddy 設定頁 → 快速回覆 → 匯入 JSON
3. 選剛下載的檔案就好了

## 想幫忙翻譯？

歡迎貢獻新語言或改善現有翻譯！

1. **Fork** 這個 repo
2. 在 `locales/` 底下新增一個資料夾，用 Chrome 的語系代碼命名（例如 `fr`、`de`、`th`）
3. 複製 `locales/ja/messages.json` 當範本
4. 翻譯裡面所有的 `"message"` 欄位（`"description"` 是說明，留著參考就好）
5. 想順便做快速回覆範本的話，在 `canned-templates/` 加一個 JSON
6. 送 **Pull Request**

### 語系代碼參考

常見的：`fr`（法文）、`de`（德文）、`it`（義大利文）、`th`（泰文）、`vi`（越南文）、`id`（印尼文）、`ar`（阿拉伯文）、`ru`（俄文）、`tr`（土耳其文）、`hi`（印地文）

完整清單：https://developer.chrome.com/docs/extensions/reference/api/i18n#locales

### 快速回覆範本格式

```json
[
  {
    "title": "範本標題（簡短描述）",
    "body": "完整的回覆文字內容...",
    "category": "分類名稱（例如：感謝回饋、澄清事實）",
    "persona": "語氣風格（例如：專業穩重、溫暖親切）"
  }
]
```

## 相關連結

- [SocialBuddy 擴充功能下載](https://github.com/chenmitchell/social-buddy-release)
- [SocialBuddy 官網](https://socialbuddy-verify.mitch.tw)

---

<p align="center">
  <strong>米球®</strong> — SocialBuddy 社群小幫手<br>
  <sub>MIT License — 自由使用、自由貢獻。</sub>
</p>
