# Claude Code Skills Catalog

Claude Codeのスキル・プラグイン環境を一覧化し、ユーザープロフィールに基づくパーソナライズ推薦を表示するGitHub Pagesサイト。

## Features

- **41スキル / 12カテゴリ** をカード形式で表示
- **4層のスキルソース**: Bundled / Installed Plugin / Skills Repo / Official Marketplace + Recommended
- **4軸の選定基準**: 業務関連度(40%) / コミュニティ人気度(25%) / 活用頻度(20%) / シナジー(15%)
- **人気度スコア**: [anthropics/skills](https://github.com/anthropics/skills), [claude-plugins-official](https://github.com/anthropics/claude-plugins-official), [SkillsMP](https://skillsmp.com), [SkillHub](https://www.skillhub.club/) に基づく相対評価
- **パーソナライズ推薦 TOP 7**: 金融・暗号資産 / プロダクトマネジメント / 学術論文 / データ可視化 / AI・MCP / ドキュメント / コード品質
- カテゴリフィルター・関連度/人気度/名前/カテゴリ ソート
- ダークテーマ・レスポンシブデザイン

## Data Sources

| ソース | 内容 |
|--------|------|
| [anthropics/skills](https://github.com/anthropics/skills) (93.8k stars) | 公式スキルリポジトリ（16スキル） |
| [anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official) | 公式プラグインマーケットプレイス（32+プラグイン） |
| Claude Code Bundled | 本体組み込みスキル（5個） |
| [SkillsMP](https://skillsmp.com) / [SkillHub](https://www.skillhub.club/) | コミュニティマーケットプレイス |

> Note: Anthropicは個別スキルのDL数を公開していません。人気度はGitHub活動量・マーケットプレイス掲載状況に基づく相対評価です。

## Structure

```
docs/
└── index.html    ← 単一HTML（CSS/JS埋め込み）
```

## Deploy

GitHub Pages設定で `docs/` フォルダを Source に指定してください。
