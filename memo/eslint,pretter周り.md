eslint-config-prettier を使うと、eslint の設定のうち prettier とバッティングするものを off にしてくれる
eslint の V9 から設定ファイル周りで破壊的な変更が行われているらしい

https://zenn.dev/keita_hino/articles/798bf62c6db663
ESLint v9 （今年末 ~ 来年の初めにリリース予定）で flat config がデフォルトになり、eslintrc は非推奨になる。
eslint v10 （2024 年末 ~ 2025 年初頭にリリース予定）で eslintrc が削除される

eslint.config.mjs は v9 以降のフラットコンフィグという新しい設定方法になる
