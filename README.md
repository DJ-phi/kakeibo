# README
<img width="1271" alt="スクリーンショット 2022-06-18 0 26 20" src="https://user-images.githubusercontent.com/94509379/174329460-1089d97f-05c3-4cb4-bc56-69b4b531c2f4.png">
<h1>家計簿アプリ</h1>
<p>
  ユーザーが使いやすい様に心掛けて作りました🙇‍♂️<br>
  ログイン機能があり, 自分の使ったお金をこまめに記録できます<br>
  データ化する事によって自分の出費がどのぐらいか把握できる様に、、、<br>
  あなたの無駄遣いを救いたい🫶<br>
  特に難しい操作は無く,どの年代でも使えます🫶🫶🫶
</p>

<h1>こだわったところ</h1>

<h2>カテゴリの追加を非同期処理(ajax)にした</h2>
<p>
  非同期は今後通る道だと考え挑戦してアドバイスを貰いながらなんとか実装出来ました!!<br>
  複雑なjsを書いてます<br>
  自分にとって傑作です🥹
</p>

<h2>ログイン機能</h2>
<p>
  ログインの理解力を深めったかったのでdevideじゃない実装をしてみました!!<br>
  deviseだとワンコマンドで出来てしまう為,　中の処理がフワフワだったのですが自分で作る事により,理解力がより一層深まりました<br>
</p>

<h2>検索機能</h2>
<p>
  スコープをガンガン使用して
  データの取り出しをしてみました
  whereがない分,コードがとても見やすくなり,スコープ様様です🥹
</p>

<h2>TDD開発</h2>
<p>
  TDD開発が主流と聞いたので初めはテストから書きました！<br>
  itを書いていく中,あれが足りない、これが足りないなど気づけることが出来たのでかなり恩恵を感じました<br>
</p>
 
<h2>S3に画像を保存</h2>
<p>
  AWSの使用が今後必ず訪れると分かったのでローカル,herokuで画像が保存される設定をしました
</p>

<h2>いいね(ajax)</h2>
　　ついでにいいねもajaxしてみました(ボソッ

<h1>使用環境</h1>
<ul>
  <li>TDD開発</li>
  <li>M1</li>
  <li>Ruby 3.1.0</li>
  <li>Rails 6.1.4</li>
  <li>postgreSQL</li>
  <li>AWS S3</li>
  <li>Rspec</li>
  <li>rubocop</li>
</ul>

<h1>機能一覧</h1>
<ul>
  <li>ログイン機能</li>
  <li>ユーザー登録</li>
  <li>カテゴリ管理機能</li>
  <li>投稿機能</li>
  <li>アクティブストレージ(画像投稿) S3</li>
  <li>いいね機能(ajax)</li>
  <li>post/newにあるcategory追加(ajax)</li>
  <li>検索機能(あいまい, 完全一致, 日付検索)</li>
</ul>

<h1>Rspec</h1>
<li>modelテスト</li>
<li>requestテスト</li>
