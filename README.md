# 講義ネタ速報 — iU 志村ゼミ

学部ゼミ（財務・経済の基礎／ソクラテス式）向けの、政治経済ニュース速報ブリーフ。
火曜・土曜の週2回配信を想定。各号は外部依存のない単一HTMLファイル。

## 一覧

| Vol. | 配信日 | 対象期間 | トピック | ファイル |
|---|---|---|---|---|
| 1 | 2026-08-09 | 2026-08-05 〜 08-09 | 日米協調介入のその後／同じ円安が正反対に効いた4〜6月期決算 | [HTML](news_briefs/lecture_news_20260809.html) ・ [Pages](https://katsuagezzz.github.io/summer_lecture/news_briefs/lecture_news_20260809.html) |

## 講義資料（事前課題）

各回の講義前に配布する資料。**答えは載せず、空欄と問いだけを配る**方針で作っている。

| 回 | 講義日 | テーマ | ファイル |
|---|---|---|---|
| 夏期 第3回 | 2026-08-18 | 上場が答え合わせをする夏 ― SpaceX、Anthropic、そして「電力」という首 | [HTML](lectures/lecture_20260818.html) ・ [Pages](https://katsuagezzz.github.io/summer_lecture/lectures/lecture_20260818.html) |
| 個別 | 2026-08-21 | 在庫を持たない会社が、世界でいちばん重い買い物を始めた（BS・固定資産・減価償却） | [HTML](lectures/lecture_toyonaga_20260821.html) ・ [Pages](https://katsuagezzz.github.io/summer_lecture/lectures/lecture_toyonaga_20260821.html) |
| 個別 | 2026-08-20 | 日本の物価を読む ― 輸入物価+29.1%は、どこで+1.6%になったのか（為替・金利・インフレ） | [HTML](lectures/lecture_sasaki_20260820.html) ・ [Pages](https://katsuagezzz.github.io/summer_lecture/lectures/lecture_sasaki_20260820.html) |

## 復習ページ

各回の講義後に公開する、受講生向けの復習用ページ（要点まとめ＋用語集）。

| 回 | 講義日 | テーマ | ファイル |
|---|---|---|---|
| 夏期 第2回 | 2026-08-11 | 日米為替介入と出前館、ハイパースケーラーの1Q決算 | [HTML](reviews/lecture_review_20260811.html) ・ [Pages](https://katsuagezzz.github.io/summer_lecture/reviews/lecture_review_20260811.html) |

## 構成

- `news_briefs/lecture_news_YYYYMMDD.html` — 速報 各号の本体（単一HTML・CSSインライン・ダークモード対応・印刷可）
- `reviews/lecture_review_YYYYMMDD.html` — 各回の復習ページ（同上）
- `lectures/lecture_YYYYMMDD.html` — 各回の講義資料（同上）。個別指導回は `lecture_<名字ローマ字>_YYYYMMDD.html`

## 注記

- 数字は決算短信・官庁発表などの一次情報で裏取りし、推計値・未確定値は各ページのフッターに明記しています。復習ページのうち講義中に口頭で示された概算・例示には、その旨をタグで明示しています。
- 復習ページには、ゼミ参加者個人のポートフォリオ・保有銘柄は収録していません。
- ブラウザストレージ（localStorage 等）は使用していません。

## GitHub Pages

公開URL： https://katsuagezzz.github.io/summer_lecture/

`index.html` がバックナンバー一覧のトップページになります。授業ではこのURLを開くだけで投影できます。

有効化：リポジトリの **Settings → Pages → Build and deployment** で Source を `Deploy from a branch`、Branch を `main` / `/ (root)` に設定して Save。反映まで1〜2分かかります。
