日本の上場企業のデータを集め、分析するツールを書いています。

- **[stock_db](https://github.com/expgolemclone/stock_db)** — 日本株の財務・株価データを自動収集し SQLite に集約するツールキット。EDINET・Stooq・Yahoo Finance からデータを取得。XBRL パーサーは Rust (PyO3) で実装。
- **[formula_screening](https://github.com/expgolemclone/formula_screening)** — 財務指標を Python の条件式でスクリーニングするアプリケーション。`stock_db` のデータを使い、`stock_web_ui` で結果を表示。[GitHub Pages](https://expgolemclone.github.io/formula_screening/) で公開中。
- **[stock_web_ui](https://github.com/expgolemclone/stock_web_ui)** — スクリーニングプロジェクト共通の Web UI パッケージ。ローカルサーバー、テンプレート、テーブルランタイム、CSS を提供。
- **[invest_like_legends](https://github.com/expgolemclone/invest_like_legends)** — 投資家・ファンドごとの保有銘柄を、財務指標つきで一覧できる Web アプリ。[GitHub Pages](https://expgolemclone.github.io/invest_like_legends/) で公開中。
- **[land_value_research](https://github.com/expgolemclone/land_value_research)** — 上場企業が所有する東京の土地の含み益を算出するパイプライン。[ランキング結果](https://expgolemclone.github.io/land_value_research/data/ranking/ranking_market_cap_ratio.html)を公開中。
