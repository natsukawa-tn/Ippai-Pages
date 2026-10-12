# Ippai-Pages

一杯（Ippai / 한잔）的产品页、隐私政策、利用规约、免责事项与 FAQ（GitHub Pages）。结构与 NagiNote-Pages / Tallyra-Pages 相同。
本仓库由 Ippai 仓库（`../Ippai`）的 `tools/pages/generate.py` 生成（文字在 `tools/pages/content.py`），**请修改脚本后重新生成，不要直接改 HTML**。

- `index.html`：按浏览器语言跳转到 `ja/`、`en/`、`ko/`、`zh-Hans/`、`zh-Hant/`（默认 `en/`，与 App 内链接的语言规则一致）
- `<lang>/index.html`：产品介绍
- `<lang>/privacy.html`：隐私政策（App 内「設定 › プライバシーポリシー」与付费墙链接到这里）
- `<lang>/terms.html`、`disclaimer.html`、`faq.html`：利用规约、免责事项、常见问题（App 内链接）
- `styles.css`：样式；`assets/`：App 图标、favicon

App 中的地址：`https://natsukawa-tn.github.io/Ippai-Pages/<lang>/<page>.html`（见 `AppConstants`）

上架后：把各语言 `index.html` 中的「App Store で近日公開」按钮换成 App Store 链接（`https://apps.apple.com/app/id<AppID>`）。
App 的功能或数据处理方式变化时，同步更新 5 种语言的隐私政策和「最終更新日」。
