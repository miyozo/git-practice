# git-practice

## このリポジトリについて
社内のGitミニ勉強会用のハンズオンリポジトリです。

## 注意事項
- このリポジトリは**Public**です（社外の人も閲覧可能）
- **社内情報・個人情報は絶対にpushしないでください！**
- pushするファイルはミニ勉強会用のもののみにしてください。

## ディレクトリ構成
```
git-practice/
├── README.md          # このファイル
├── profile/
│   └── sample.md     # プロフィールのテンプレート
└── conflict/
    └── conflict.md    # コンフリクト体験用ファイル
```

## 当日の流れ

### STEP 1：プロフィール作成でGit基本操作を学ぶ
1. `profile/sample.md`を参考にファイルを作成する。
2. ファイル名は`任意のニックネーム（英語かローマ字）.md`とする。（例：`hoge-king.md`）
3. `git add` → `git commit` → `git push`する。
4. `git pull`で他の人のファイルを確認する。

### STEP 2：コンフリクトの体験
1. `conflict/conflict.md`を編集する。
2. `git push`しようとするとコンフリクトが発生するはず。
3. コンフリクトを解消して`git push`する。