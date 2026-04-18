# SocialBuddy Language Packs / 語言包

Community-contributed language packs for [SocialBuddy](https://github.com/chenmitchell/social-buddy-release) Chrome Extension.

## Included Languages / 包含語言

| Folder | Language | 語言 |
|--------|----------|------|
| `zh_CN` | Simplified Chinese | 簡體中文 |
| `ja` | Japanese | 日本語 |
| `ko` | Korean | 한국어 |
| `es` | Spanish | Español |
| `pt_BR` | Brazilian Portuguese | Português (Brasil) |

> **Note:** Traditional Chinese (`zh_TW`) and English (`en`) are built into the extension by default.

## How to Install / 安裝方式

1. Download the language folder you need (e.g. `locales/ja/`)
2. Open the extension's installation folder
3. Copy the folder into `_locales/`
4. Reload the extension in `chrome://extensions`

For canned reply templates:
1. Download the JSON file from `canned-templates/` (e.g. `ja.json`)
2. Open SocialBuddy Settings → Quick Replies → Import JSON
3. Select the downloaded file

## How to Contribute / 如何貢獻

We welcome translations for new languages! Here's how:

1. **Fork** this repository
2. Create a new folder under `locales/` using Chrome's locale code (e.g. `fr`, `de`, `th`)
3. Copy `locales/ja/messages.json` as a template
4. Translate all `"message"` values (keep the `"description"` as reference)
5. (Optional) Create a canned template JSON under `canned-templates/`
6. Submit a **Pull Request**

### Locale Code Reference

Use standard Chrome locale codes: `fr`, `de`, `it`, `th`, `vi`, `id`, `ar`, `ru`, `tr`, `hi`, etc.

Full list: https://developer.chrome.com/docs/extensions/reference/api/i18n#locales

### Canned Template Format

```json
[
  {
    "title": "Short label for the template",
    "body": "The full reply message text...",
    "category": "Category name (e.g. 感謝回饋, 澄清事實)",
    "persona": "Persona style (e.g. 專業穩重, 溫暖親切)"
  }
]
```

## License

MIT — see [LICENSE](LICENSE)
