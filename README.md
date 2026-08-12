# 講義ネタ速報 — iU 志村ゼミ

学部ゼミ（財務・経済の基礎／ソクラテス式）向けの、政治経済ニュース速報ブリーフ。
火曜・土曜の週2回配信を想定。各号は外部依存のない単一HTMLファイル。

## 一覧

| Vol. | 配信日 | 対象期間 | トピック | ファイル |
|---|---|---|---|---|
| 1 | 2026-08-09 | 2026-08-05 〜 08-09 | 日米協調介入のその後／同じ円安が正反対に効いた4〜6月期決算 | [HTML](news_briefs/lecture_news_20260809.html) ・ [Pages](https://katsuagezzz.github.io/summer_lecture/news_briefs/lecture_news_20260809.html) |

## 復習ページ

各回の講義後に公開する、受講生向けの復習用ページ（要点まとめ＋用語集）。

| 回 | 講義日 | テーマ | ファイル |
|---|---|---|---|
| 夏期 第2回 | 2026-08-11 | 日米為替介入と出前館、ハイパースケーラーの1Q決算 | [HTML](reviews/lecture_review_20260811.html) ・ [Pages](https://katsuagezzz.github.io/summer_lecture/reviews/lecture_review_20260811.html) |

## 構成

- `news_briefs/lecture_news_YYYYMMDD.html` — 速報 各号の本体（単一HTML・CSSインライン・ダークモード対応・印刷可）
- `reviews/lecture_review_YYYYMMDD.html` — 各回の復習ページ（同上）

## 注記

- 数字は決算短信・官庁発表などの一次情報で裏取りし、推計値・未確定値は各ページのフッターに明記しています。復習ページのうち講義中に口頭で示された概算・例示には、その旨をタグで明示しています。
- 復習ページには、ゼミ参加者個人のポートフォリオ・保有銘柄は収録していません。
- ブラウザストレージ（localStorage 等）は使用していません。

## GitHub Pages

公開URL： https://katsuagezzz.github.io/summer_lecture/

`index.html` はトップページで、**講義回ごとのタブ**（例：「夏期 第2回」）＋「講義ネタ速報 バックナンバー」タブの構成になっています。授業ではこのURLを開くだけで投影できます。

有効化：リポジトリの **Settings → Pages → Build and deployment** で Source を `Deploy from a branch`、Branch を `main` / `/ (root)` に設定して Save。反映まで1〜2分かかります。

### 新しい講義回タブを足すとき

`index.html` を直接編集します（ビルド不要・単一ファイル）。

1. `.tabs` 内に新しいタブボタンを1つ追加する（`id="tab-XXX"` / `aria-controls="panel-XXX"`）。
2. その下に対応する `<section id="panel-XXX" role="tabpanel" ...>` を1つ追加し、既存の「夏期 第2回」パネルをコピーして、復習ページのカードと、その回につながった講義ネタ速報のカードを差し替える。
3. 「講義ネタ速報 バックナンバー」パネルにも同じ講義ネタ速報のカードを追記する（回に厳密に紐づかない号もここに並ぶ）。
4. 新しいタブをデフォルト表示にしたい場合は、そのタブの `aria-selected="true"`／`tabindex` 省略、他タブを `aria-selected="false"`／`tabindex="-1"` にする。
5. README冒頭の表にも1行追加しておく。
