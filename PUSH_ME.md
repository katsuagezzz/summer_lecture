# push 手順（お手元のPCで）

このzipは **コミット済みのGitリポジトリ** です。解凍して2コマンド流すだけで反映されます。

## A. まだ summer_lecture が空の場合（推奨）

```bash
cd summer_lecture_repo
git remote add origin https://github.com/katsuagezzz/summer_lecture.git
git push -u origin main
```

## B. すでに中身がある場合

既存のクローンに、`index.html` / `.nojekyll` / `README.md` / `news_briefs/` を
コピーして、いつも通り add → commit → push してください。

```bash
cp -r summer_lecture_repo/index.html summer_lecture_repo/.nojekyll summer_lecture_repo/news_briefs /path/to/your/summer_lecture/
cd /path/to/your/summer_lecture
git add -A && git commit -m "Add 講義ネタ速報 Vol.1" && git push
```

（`main` ではなく `master` の場合は `git push -u origin main:master` などに読み替えてください）

## GitHub Pages の有効化

1. https://github.com/katsuagezzz/summer_lecture/settings/pages を開く
2. **Build and deployment** → Source: `Deploy from a branch`
3. Branch: `main` ／ フォルダ: `/ (root)` → **Save**
4. 1〜2分待つ

公開URL：
- トップ（バックナンバー一覧）　https://katsuagezzz.github.io/summer_lecture/
- Vol.1 本体　https://katsuagezzz.github.io/summer_lecture/news_briefs/lecture_news_20260809.html
