---
marp: true
theme: kessan
paginate: true
style: |
  section {
    /* カスタムCSSに加えて個別のスタイルをここに書けます */
  }
---
<!-- _class: title -->
# AIで『自分』を再発見する
〜日々の記録とマルチモーダルの未来〜

松田 晴史
投資テック同好会

---
<!-- header: プロフィール・現在の取り組み -->

<div class="columns">
<div class="column">
<div class="column-title">今取り組んでいること</div>

* 学内フリマアプリの開発
* 投資テック同好会の大学公認化
* Claudeのアンバサダー
* ニンニク育成中
  <img src="garlic.jpg" height="200" alt="ニンニク育成中" style="display: block; margin-top: 10px;">

</div>
<div class="column">
<div class="column-title">申請中のプロジェクト</div>

* トビタテ！留学JAPAN（申請中）
* 目的：多様な幸福の形を実感するため
* 様々な価値観に触れる狙い

</div>
</div>

---
<!-- header: 本日のテーマ -->

<div class="columns">
<div class="column" style="flex: 2;">
<div class="column-title">皆さんに問いかけたいこと</div>

* **「自分自身を本当に理解していますか？」**
* 「自分」とは何か？ 最も身近で最も難解な対象です。
* 果たして、AIを使えばこの「自分」の解像度を上げることは可能なのか？

</div>
</div>

---
<!-- header: 背景：なぜ「自己理解」が必要なのか？ -->

<div class="columns">
<div class="column">
<div class="column-title">溺れるような苦しみ</div>

* 過去に、もがき苦しむような時期がありました
* 「幸せになりたい」と強く願い、幸福について考えた
* 結論：幸福の形は多様で、万人共通の正解はない

</div>
<div class="column">
<div class="column-title">自分専用の幸福を見つける</div>

* 「自分にカスタマイズされた幸福」を見つける必要がある
* それを見つけるためには、まず**自分自身を深く理解しなければならない**
* → AIを使って、自己理解を極限まで深める試みを始めました。

</div>
</div>

---
<!-- header: 開発したシステム：AI自己理解エンジン -->

<div class="columns">
<div class="column">
<div class="column-title">入力：日々の「遺書」</div>

* 毎日、自分の感情や欲しいものをテキスト化
* （※ポップな意味での「遺書」＝毎日のスナップショットです）
* メモツール「Obsidian」で書き、GitHubにログを蓄積

</div>
<div class="column">
<div class="column-title">処理：Gemini API x RAG</div>

* 溜まった思考データをRAG（検索拡張生成）の仕組みで構築
* 「Google Gemini API」を頭脳として活用
* 何もバイアスのない客観的な目で、自分を分析させる

</div>
</div>

---
<!-- header: AIによる自己分析 -->

<div class="columns">
<div class="column" style="flex: 2;">
<div class="column-title">データとしての思考</div>

* 毎日書き続けたテキストデータ ＝ 思考のログ
* 実際に2ヶ月間、このデータをAIに分析・トラッキングさせた
* 感情の揺れや行動の記録から「自分でも気づかない法則」を抽出

</div>
</div>

---
<!-- header: 洞察①：幸福度が上がる確実な条件 -->

<div class="columns">
<div class="column">
<div class="column-title">満足度が高かった日の記録</div>

* 友人とのランニング＋にんにく栽培
* 高校の友人と会う、一緒に行動する
* 1万7千歩歩く、ただ外を歩く、ネカフェ泊

</div>
<div class="column">
<div class="column-title">共通する3つの絶対条件</div>

1. 「波長の合う人間」と同じ空間にいる
2. 身体を動かして外に出ている
3. 評価と無関係な「小さな行動」（栽培、歩く等）

</div>
</div>

---
<!-- header: 洞察②：幸福を妨げる「3つの慢性的な摩擦」 -->

<div class="columns">
<div class="column" style="flex: 2;">
<div class="column-title">AIが見抜いたボトルネック</div>

* ⚠️ **摩擦①：評価の二重拘束**
  「見られたい」と「見られるのが怖い」が同じ強度で共存している。これが開発の進行を止める根本原因。
* ⚠️ **摩擦②：虚無の慢性化**
  虚無の対義語は幸福ではなく「誰かといる・何かに触れる接続感」。
* ⚠️ **摩擦③：身体の問題（副鼻腔などの体調不良）**
  例外なく自発度をゼロにする。「頑張らない理由」を作り出す最大の要因。

</div>
</div>

---
<!-- header: ネクストアクション：最もコスパが高い行動 -->

<div class="columns">
<div class="column" style="flex: 2;">
<div class="column-title">3ヶ月で最も「幸福に近づける」行動ランキング</div>

* **第1位：副鼻腔の治療を予約する（今週中）**
  * 「頑張れない」日の7割が体調不良と連動。ここがすべての基盤。
* **第2位：「波長が合う人間」と週に1回会う時間を作る**
  * 評価なしで人と会うことが、再現性のある幸福の条件。
* **第3位：ZAX（現状のプロダクト）を「実験ログ」にする**
  * 「自分のプロダクト」と思うと怖くて開けないので、評価対象から外す。

</div>
</div>

---
<!-- header: 今後の展望とまとめ -->

<div class="columns">
<div class="column">
<div class="column-title">マルチモーダル化へ</div>

* ゆくゆくはテキスト以外のデータも
* 睡眠データ・音声・表情など
* あらゆる生体情報を組み合わせた深い解析

</div>
<div class="column">
<div class="column-title">まとめ</div>

* 「自分」という最大のアセット（資産）
* AIを使って正しく理解し投資する
* より良い方向へ自分をアップデート

</div>
</div>

---
<!-- _class: title -->
# ご清聴ありがとうございました

<div style="display: flex; flex-direction: column; align-items: center; justify-content: center; width: 100%; margin-top: 20px;">
  <img src="https://api.qrserver.com/v1/create-qr-code/?size=500x500&data=https://x.com/musashinoinvest" width="300" alt="QR Code" style="margin-bottom: 20px;">
  <p style="font-size: 28px; text-align: center; margin: 0;">投資テック同好会 X(Twitter)<br>@musashinoinvest</p>
</div>
