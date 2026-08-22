# 講義資料ポータル — iU 志村ゼミ

学部ゼミ（財務・経済の基礎／ソクラテス式）の講義資料・復習ページ・ニュース速報。
グループの夏期集中講座と、個別指導2名の計3トラックに分かれている。
各ページは外部依存のない単一HTMLファイル。

## トラック

講義は3つに分かれている。それぞれ独立したポータルページを持ち、受講者にはそのURLだけを渡せばよい。

| トラック | 対象 | ポータル |
|---|---|---|
| 夏期集中講座（グループ） | 田村・廻・山本・河野・秋山・中村 | [seminar.html](seminar.html) ・ [Pages](https://katsuagezzz.github.io/summer_lecture/seminar.html) |
| 個別指導 — 佐々木さん | 佐々木 | [sasaki.html](sasaki.html) ・ [Pages](https://katsuagezzz.github.io/summer_lecture/sasaki.html) |
| 個別指導 — 豊長さん | 豊長 | [toyonaga.html](toyonaga.html) ・ [Pages](https://katsuagezzz.github.io/summer_lecture/toyonaga.html) |

`index.html` は3トラックへの振り分けだけを行うハブ。各資料の「一覧へ」は、所属するトラックのポータルに戻る。

## 夏期集中講座

### 講義資料（事前課題）

| 回 | 講義日 | テーマ | ファイル |
|---|---|---|---|
| 夏期 第4回 | 2026-08-25 | バリュー投資（シケモク投資家とリンチ・チャート）と金利と為替（橘玲『プアジャパン』） | [HTML](lectures/lecture_20260825.html) ・ [Pages](https://katsuagezzz.github.io/summer_lecture/lectures/lecture_20260825.html) |
| 夏期 第3回 | 2026-08-18 | 上場が答え合わせをする夏 ― SpaceX、Anthropic、そして「電力」という首 | [HTML](lectures/lecture_20260818.html) ・ [Pages](https://katsuagezzz.github.io/summer_lecture/lectures/lecture_20260818.html) |

### 復習ページ

| 回 | 講義日 | テーマ | ファイル |
|---|---|---|---|
| 夏期 第2回 | 2026-08-11 | 介入は「流れ」を変えられるか ― 為替・金利・減価償却・原価率 | [HTML](reviews/lecture_review_20260811.html) ・ [Pages](https://katsuagezzz.github.io/summer_lecture/reviews/lecture_review_20260811.html) |
| 夏期 第1回 | 2026-08-04 | 登場人物を並べる ― 政府・日銀・市場・アメリカ | [HTML](reviews/lecture_review_20260804.html) ・ [Pages](https://katsuagezzz.github.io/summer_lecture/reviews/lecture_review_20260804.html) |

### 講義ネタ速報

| Vol. | 配信日 | 対象期間 | トピック | ファイル |
|---|---|---|---|---|
| 1 | 2026-08-09 | 2026-08-05 〜 08-09 | 日米協調介入のその後／同じ円安が正反対に効いた4〜6月期決算 | [HTML](news_briefs/lecture_news_20260809.html) ・ [Pages](https://katsuagezzz.github.io/summer_lecture/news_briefs/lecture_news_20260809.html) |

## 個別指導 — 佐々木さん

決算ケーススタディ。各資料の上部のタブで前後の回に行き来できる。

| 回 | 講義日 | テーマ | ファイル |
|---|---|---|---|
| 第3回 | 2026-08-20 | 金利・為替・インフレの関係性 ― 輸入物価+29.1%は、どこで+1.6%になったのか | [HTML](lectures/lecture_sasaki_20260820.html) ・ [Pages](https://katsuagezzz.github.io/summer_lecture/lectures/lecture_sasaki_20260820.html) |
| 第2回 | 2026-08-17 | ZOZOの決算を読む ― 受託販売とテイクレート | [HTML](lectures/lecture_sasaki_20260817.html) ・ [Pages](https://katsuagezzz.github.io/summer_lecture/lectures/lecture_sasaki_20260817.html) |

## 個別指導 — 豊長さん

**答えは載せず、空欄と問いだけを配る**方針で作っている。

| 講義日 | テーマ | ファイル |
|---|---|---|
| 2026-08-28 | 「儲かっている」は、4回に分けて言われる ― ところが、メルカリのPLには、そのうち1つが無い（PL・段階損益・会計基準） | [HTML](lectures/lecture_toyonaga_20260828.html) ・ [Pages](https://katsuagezzz.github.io/summer_lecture/lectures/lecture_toyonaga_20260828.html) |
| 2026-08-21 | 在庫を持たない会社が、世界でいちばん重い買い物を始めた（為替・金利・BS・固定資産・減価償却） | [HTML](lectures/lecture_toyonaga_20260821.html) ・ [Pages](https://katsuagezzz.github.io/summer_lecture/lectures/lecture_toyonaga_20260821.html) |

## 構成

- `news_briefs/lecture_news_YYYYMMDD.html` — 速報 各号の本体（単一HTML・CSSインライン・ダークモード対応・印刷可）
- `reviews/lecture_review_YYYYMMDD.html` — 各回の復習ページ（同上）
- `lectures/lecture_YYYYMMDD.html` — 各回の講義資料（同上）。個別指導回は `lecture_<名字ローマ字>_YYYYMMDD.html`
- `index.html` — トラック振り分けのハブ。`seminar.html` / `sasaki.html` / `toyonaga.html` — トラック別ポータル

## 注記

- 数字は決算短信・官庁発表などの一次情報で裏取りし、推計値・未確定値は各ページのフッターに明記しています。復習ページのうち講義中に口頭で示された概算・例示には、その旨をタグで明示しています。
- 復習ページには、ゼミ参加者個人のポートフォリオ・保有銘柄は収録していません。
- ブラウザストレージ（localStorage 等）は使用していません。

## GitHub Pages

公開URL： https://katsuagezzz.github.io/summer_lecture/

`index.html` が3トラックへの振り分けページです。授業では各トラックのURLを直接開けば、そのトラックの資料だけが並びます。

有効化：リポジトリの **Settings → Pages → Build and deployment** で Source を `Deploy from a branch`、Branch を `main` / `/ (root)` に設定して Save。反映まで1〜2分かかります。
