# スプラ掛け声

スプラトゥーン3のプレー中に、スマホが**ランダムな間隔（既定60〜120秒）で「今の課題」を読み上げる**練習アプリ。試合が終わったら ○△× と勝敗を3タップで記録し、直近10試合で○が7つになったら卒業して次の課題へ進む。

**使い方ページ**：`help.html`（ホーム画面への追加手順・音が出ない時・データの扱い）

**使い方**：①画面をつけたまま置く ②試合開始で「開始」・終わったら「終了」 ③○△×だけでいい

- 画面が消えると音が止まるので、画面をつけたまま置いてください（対応機種は自動で点けたままにします）
- **「ホーム画面に追加」して使ってください**。Safariのタブのまま使うと、7日間開かないとデータが消えることがあります（iOSの仕様）
- データはすべて端末内（localStorage）。サーバー・アカウント・通信なし。機種変更は設定の「書き出し／読み込み」で
- ローカル確認：`python3 -m http.server 8787` → http://localhost:8787/

**公開手順（GitHub Pages）**：GitHubに空リポジトリ `splat-kakegoe` を作る → `git remote add origin git@github.com:mukuzun/splat-kakegoe.git && git push -u origin main` → リポジトリの Settings › Pages で Branch=main / Folder=/(root) を選んで保存 → 数分後に `https://mukuzun.github.io/splat-kakegoe/` で開ける（スマホのSafari/Chromeで「ホーム画面に追加」）。
