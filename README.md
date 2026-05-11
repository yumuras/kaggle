# Kaggle

Kaggle コンペの解法をまとめたリポジトリ。

## コンペ一覧

| コンペ | 説明 | モデル | スコア |
|--------|------|--------|--------|
| [Titanic](titanic/) | 生存予測 (二値分類) | Random Forest | CV ~0.83 |

## ディレクトリ構成

```
kaggle/
├── titanic/
│   └── titanic.ipynb
├── data/           # 各コンペのデータ置き場
└── pyproject.toml
```

## セットアップ

```bash
uv sync

# Kaggle API 認証トークンを配置
# ~/.kaggle/kaggle.json
```
