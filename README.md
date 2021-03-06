# ことりカフェとは

<li>・鳥飼育者に向けに作成しました。</li>
<li>・おすすめの鳥に関する商品を紹介、共有するWEBアプリケーションです。</li>
<li>・AmazonのURL等情報を投稿時に入力する事で、自動的に商品の画像を表示します。</li>
<li>・購入ボタンをクリックすることで、自動的にAmazonの該当商品購入ページ遷移します。</li>

## 🌐 App URL 
### https://

## 💬 Usage
`$ git clone https://github.com/shuyamurai/bird-cafe` 

## 機能概要
<ul>
    <li>・ユーザー新規登録機能、ログイン機能、ログアウト機能（devise）</li>
    <li>・トップページ（商品一覧機能）</li>
    <li>・おすすめ商品投稿機能（投稿時、Amazonの商品画像を自動的に取得し表示する）</li>
    <li>・商品詳細表示機能（購入ボタンをクリックするとAmazonの該当商品購入画面に遷移）</li>
    <li>・商品編集機能</li>
    <li>・商品削除機能</li>
    <li>・いいね機能</li>
    <li>・いいね数ランキング機能</li>
    <li>・サイト内検索機能</li>
    <li>・コメント投稿機能</li>
    <li>・コメント削除機能</li>
    <li>・マイページ機能</li>
    <li>・ダイレクトメッセージ機能</li>
</ul>

## 使用技術(本番環境)

### フロントエンド
<ul>
    <li>HTML/CSS・Sass</li>
    <li>JavaScript</li>
    <li>jQuery</li>
</ul>

### バックエンド
<ul>
    <li>rails6.0.3.2</li>
</ul>

### インフラストラクチャー
<ul>
    <li>Mysql</li>
</ul>

### AWS
<ul>
    <li>AWS EC2</li>
    <li>AWS RDS</li>
    <li>AWS Route53</li>
</ul>

### その他
<ul>
    <li>SSL証明書 Let’s Encrypt</li>
</ul>



<form class="search-form" action="#">
        <input class='input-box' placeholder='キーワードから探す'>
        <button class="search-button">
          <%= image_tag "search.png", class:"search-icon" %>
        </button>
      </form>