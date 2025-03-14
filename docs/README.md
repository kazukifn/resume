# 職務経歴書

## 基本情報

|key|value|
|---|---|
|氏名|大西一輝
|生年月日|2000/01/15|

---

## 保有スキル

- Laravel でのサーバーサイド開発
- Rails での API 開発
- WordPress で Hook やカスタムフィールドを用いたテーマの制作
- WordPress サイトのリニューアル
- TypeScript(Vanilla JS)、Vue.js、LiveWire を利用したフロントエンド開発
- Laravel 環境のバージョンアップグレード


---

## 技術スタック

### 言語

- PHP 5 系から 8.2 まで
- JavaScript
- TypeScript 4 系
- Ruby 3 系

### フレームワーク・その他

- Laravel 5 系から 11 系まで
- CakePHP 2 系
- Wordpress 4 系から 6 系
- Rails 7.0.3
- Vue.js
- jQuery
- Vite
- bootstrap
- axios
---

## 職務経歴詳細
### 株式会社アピリッツ
#### プラント工場の日常保全システムの仕様書作成 (2025/02〜現在）
- プロジェクト規模：
  - 7 人ほど
- プロジェクト詳細：
  - 明確に画面設計書と呼べる資料が存在しないのと顧客との齟齬を減らすため作成することとなった
  - 実際にシステムを触ったり、コードをデバッグして仕様に起こしている
- 使用されていた技術：
  - Rails 7.0.3
  - Vue.js 2 系
  - MySQL 8 系
  - Docker
- 気づき・苦労したところ：
  - 機能が多く資料の作成に時間がかかっている
  - プロジェクトにビギナー層が多く、デバッグの仕方や資料作成などを教育している

#### プラント工場のフランジ締結システム保守 (2024/12〜2025/02)
- プロジェクト規模：
  - 6 人ほど
  - 前述の進捗管理システムの派生システム
- プロジェクト詳細：
  - バックエンドエンジニアとして参画
  - フランジ締結を記録したり管理するシステム
  - API の新規作成、修正、Rspec によるユニットテスト実装、フロントエンド修正を行った
  - タスクとフランジの紐づけ機能および CSV でのインポート API の実装、N+1 改善やモーダルのフロントエンド制御の修正など
  - 前述の進捗システムとのシステム連携
- 使用されていた技術：
  - Rails 7.0.3
  - Vue.js 2 系
  - MySQL 8 系
  - Docker
- 気づき・苦労したところ：
  - オフショアの方が実装されている機能が多かったがバグが多くかなり修正することになった。どうやらコミュニケーションに齟齬があったらしい
  - 参画当初は Git ブランチ運用があまりよくなく新しく作り直し改善した
  - 進捗管理システムの派生システムであったが同居することになりデータやステータスがきちんと連動するように気をつけた

#### プラント工場の進捗管理システム保守 (2024/10〜2024/12)
- プロジェクト規模：
  - 9 人ほど
  - 前述の日常保全システムは某プラント工場専用のシステムだが本システムは汎用版であり様々な工場が使用している
- プロジェクト詳細：
  - バックエンドエンジニアとして参画
  - スケジュールや日報を作成するシステム。前述のシステムよりは承認処理は少ないが日報を細かく設定したり、作業工程の管理が行える
  - API の新規作成、修正、Rspec によるユニットテスト実装を行った
  - ユーザーの一括承認 API の新規実装、ガントチャート API のレスポンス修正など
- 使用されていた技術：
  - Rails 7.0.3
  - Vue.js 2 系
  - MySQL 8 系
  - Docker
- 気づき・苦労したところ：
  - 不具合調査、修正にあたり根拠のあるエビデンスを求められることが多く、それを用意するのに苦労した
  - Rspec でのテスト、Rubocop での lint 修正をきっちり対応することで自分の実装に自身が持てるようになった
  - ユニットテストでも仕様を理解していないと作成することも難しいと感じた


#### プラント工場の日常保全システム保守 (2024/09〜2024/10)
- プロジェクト規模：
  - 16 人ほど
  - 某有名プラント工場が利用するシステムで規模は大きい
- プロジェクト詳細：
  - バックエンドエンジニアとして参画
  - はじめての Rails 案件
  - 日々の工事を管理するシステムの保守。複数ユーザーでの細かい承認システムがある
  - 簡単な API の修正を行った。例えばメール送信対象のユーザー取得クエリの修正や TODO データのサニタイズなど
- 使用されていた技術：
  - Rails 7.0.3
  - Vue.js 2 系
  - MySQL 8 系
  - Docker
- 気づき・苦労したところ：
  - 今までは MPA での開発がほとんどで API のデバッグやフロントエンドとのつなぎこみに苦労した
  - Rails と Laravel とのギャップに苦しんだ。似て非なるものでディレクトリ構成が地味に異なっていたり、バリデーションを実行するファイルが異なったりと慣れるまで苦労した。 


### 株式会社クーシー（2021/04〜2024/08）
#### オフショア採用のコードレビュー ( 2024/03〜2024/08 )
- プロジェクト規模：
  - レビューはエンジニアが 1 人で対応
  - 合否判定は採用担当が行う
- プロジェクト詳細：
  - オフショア志望の方の実装したものをレビューした
  - WordPress と Laravel の実装をそれぞれレビューした
  - レビューの観点は以下の通りにした
    - 用意されたローカル開発環境が起動するか
    - README が充実しているか
    - コードが動作するか
    - 仕様通りに実装されているか
    - アンチパターンで実装されていないか
    - 不要な処理が残っていないか
    - インデントなどが整っているか 
- 使用されていた技術：
  - PHP 8.1
  - WordPress 6 系
  - Laravel 10 系
  - MySQL 8 系
  - Docker
- レビューした気づき：
  - コードは書けるのに仕様通りに実装できていないことが多かった。仕様通りに実装することが一番大事なのだが 1 回目の提出でできた人は 1 人しかおらず難易度の高いことなのかなと思いました
  - いただいた開発環境がそのままでは動かずレビューに至るまでに時間がかかることが多かった。こういうのは私も気をつけないといけないなと思いました
  
#### IRサイトリニューアル（2023/10〜2024/03）
- プロジェクト規模：
  - エンジニア 2 人体制でリニューアル作業
  - 私は実作業担当、もう 1 人はプルリクエストなどコードのチェックと仕様の取りまとめ担当
- プロジェクト詳細：
  - 受託開発
  - 既存のサイトはバグが多く、そして WordPress のバージョンが古い、そしてデザインを一新するため WordPress の DB データはそのままにリニューアルすることになった
  - 既存処理のロジックを参考にしながら IR 資料をダウンロードおよび閲覧するページやニュースページをほぼ新規実装した
  - 他静的なページも実装
  - IR 資料をダウンロードおよび閲覧するページには新たにファイルサイズを表示する機能が追加されており管理画面からファイルを設定したときにファイルサイズを取得する処理を実装した
- 使用した技術：
  - PHP 8.2
  - WordPress 6.0.6
  - MySQL 8
  - jQuery 3.6.0
  - Docker
  - Vagrant(はじめは Docker 環境で作業していたが Docker のファイルシステムが重たいのか PHPStorm と相性が悪いため Vagrant 環境に移行）
- 気づき・苦労したところ
  - リニューアル前のサイトの仕様書がないため既存の実装を確認したり DB データを照らし合わせたりしてリニューアルを進めた
  - 既存処理は使いまわしてほくないとの要望があったのでロジックは踏襲しつつほぼ新規実装のような形になっていった。既存処理が複雑であり可読性が低かったためロジックを読み取るのに苦労した
  - IR 資料をダウンロードおよび閲覧するページには JS での絞り込み機能があるが HTML がリニューアルされるため既存の JS が参考にならなかった。そのため一から JS で処理を組むことになったが年度別にタブが分かれておりそのうえで絞り込みがあるなど複雑であったため正確な検索結果を表示させるのに苦労した
  
#### お菓子のOEMマッチングサイトの新規開発（2023/06〜2024/01)
- プロジェクト規模：
  - エンジニア 4 人体制でウォーターフォール開発
  - 主にページ別に担当分担している
  - 2024/01 以降は私の作業がなくなったため抜けた
- プロジェクト詳細：
  - 受託開発
  - お菓子の購入者とお菓子工場をマッチングする Web サービスを始めたいとのことで新規開発することとなった
  - お菓子の購入者、お菓子の製造者、その間を取り持つコンシェルジュでステークホルダーは構成されている。主に購入者、製造者のページを担当
  - サービスフローは購入者がコンシェルジュを通してお菓子を注文。そしてコンシェルジュが工場に対して確認をとり製造を依頼する
  - ログインページのバリデーション、入力フォーム HTML の組み込み、二段階認証を Laravel で実装
  - 二段階認証は認証コードをユーザーに紐づけて DB に保存。メールで認証コードを送信。そして正しい認証コードをユーザーが入力したらログインできる。セッション ID の整合性チェックであったり認証コードの有効期限も設定している
  - 新規会員登録のバリデーション、入力フォーム HTML の組み込み、登録前のメール認証を Laravel で実装
  - メール認証とは新規登録前にメールを入力、そして有効期限付きの新規登録フォームのリンクを送信する機能。ユーザー認証に利用していた LaravelBreeze にそのような機能はないため自作した
  - 購入者、製造者のモデル、テーブルを実装
  - 商品登録ページのモデルとコントローラ、HTML 組み込みを Laravel で実装
  - 商品登録機能を Livewire で実装
  - 製造者の受注商品一覧ページを Laravel で実装。検索絞り込みは Livewire を使った
- 使用した技術：
  - PHP 8.1
  - Laravel  10.28
  - MySQL    8.0
  - Livewire 2.12.3
  - Vite     4.0.0
  - Docker
- 気づき・苦労したところ：
  - フォームの入力内容くらいしか載っていない仕様書とデザインのワイヤーフレーム、DB 設計書だけが頼りだったためディレクターに都度確認をとりながら実装することになった
  - 課題確認および不明点をスプレッドシートに追記していき週一でミーティングを組んで仕様を確認した。こうすることで認識齟齬を減らしたり仕様のブラッシュアップがはかどった
  - Livewire の使用が本案件で初であり他メンバーも触ったことがないためドキュメントを見たりトライアンドエラーを繰り返しながらフロントエンドの実装をすすめた。Laravel との相性は抜群によくて、データを json 化したり API を実装する必要がないため今後も使っていきたいと思った。モダンなフロントエンドを使えるコーダーがいないためこういうライブラリは大変助かる
  - Livewire はフロントエンドとバックエンドの両方の処理を同じメソッドの中で書けることで API を使わずにすむ。だからこそ必然的にファイルが肥大化してしまう。正当な処理の分け方がなくアンチパターンではあるが可読性を重視して Trait にしてファイル分割した
  - Livewire のネックなところはほかの JavaScript ライブラリに比べて若干処理が遅いと感じたこと。サーバーとの通信で遅くなっているのかもしれない
    
#### 野球セミナー動画サイトのリニューアル（2023/01〜2023/06)
- プロジェクト規模：
  - エンジニア 2 人体制でウォーターフォール開発
  - もともと 1 人での開発体制であったが私が途中から加入
- 使用した技術：
  - PHP 8.1
  - Laravel 9.19
  - MySQL 8.0
  - Filament 2.0 (Laravel の管理画面ライブラリ）
  - Vite 3.0.0
  - jQuery 3.5.1
  - Vagrant
- プロジェクト詳細：
  - 受託開発
  - もとは Vimeo という動画共有サイトでサービスを運営していたがサービスを拡大するうえでできることに限りがあるため Laravel で動画サイトの開発をすることになった。動画はすでにアップロードされている Vimeo の埋め込みコードを埋め込んで再生する仕組み
  - 動画はサブスクリプションでの閲覧、買い切りでの閲覧がある
  - 決済は GMO のサービスを利用。決済周りに関してはもう 1 人のエンジニアが担当
  - 動画以外にもドリルやクーポンのショップ販売機能もある
  - 会員登録、ログイン機能のユーザー認証回りを Laravel で実装
  - 動画の一覧、検索絞り込みを Laravel で実装
  - ユーザーの契約状況のログをとる処理を Laravel で実装。サブスクリプションの更新はスケジュールで実行されるがそのタイミングでログを DB に保存する。ログは管理画面で閲覧でき Excel にエクスポートする機能も実装
- 気づき・苦労したこと：
  - 役員の方がとってきた案件であったが仕様のコンセンサスがとれておらず公開後にたくさん修正が発生した。そして先方の関係が良くなかった。技術的な説明をするために先方との MTG に参加することもあったがかなり不満を持っておられた
  - ただ役員の方がプロジェクトを離れ新たなディレクターが入りプロジェクトの立て直しを図った。先方と密にコミュニケーションをとり仕様のコンセンサスをとることで最終的には関係は改善された
  - 公開前は先方とコミュニケーションをとる機会すらなかったが公開後体制を立て直してからは要望を聞き技術的に可能な機能を提案した。ログの細かい仕様に関しては私が提案したものである
  - 管理画面を実装するにあたり laravel-admin ではなく新しいライブラリを使おうとのことで Filament を使うことになった
  - Filament は用意されたクラスやメソッドを使ってフォームやテーブルを作成するのだが仕様通りに実装するとなると細かくカスタマイズする必要があった。情報がかなり少なく公式サイトのコミュニティとにらめっこしていた
  - Filament は Livewire や Alpine.js を理解していないと使いこなすは難しいと思った
  - テストスケジュールが短く簡単なモンキーテストしかできなかった。ほかの案件でもだが工数や費用を気にしてテストをないがしろにしていることが多い

#### 家事代行サービスサイトの開発と保守運用（2022/07〜2024/01)
- プロジェクト規模：
  - WordPress の開発と保守運用時の改修は私 1 人で対応。サーバーの構築はプロジェクトリーダーが対応
- 使用した技術：
  - WordPress 5.7
  - PHP 8.0
  - MySQL 5.7
  - JavaScript
  - jQuery
- プロジェクト詳細：
  - 受託開発と保守運用
  - WordPress で投稿一覧詳細ページと固定ページ、フォームの実装
  - HTML パーツ組み合わせて投稿する機能をカスタムフィールドで実装
  - 各種数値データ系をカスタムフィールドで実装
- 気づき・苦労したこと：
  - スケジュールがタイトだったので公開前は残業が多くなってしまった
  - カスタムフィールドを多用したためテンプレート上の処理が複雑で冗長的になってしまい保守性の低いコードになってしまった

#### 決済サービスサイトのフォーム改修（2022/07〜2022/08)
- プロジェクト規模：
  - フォームの改修は私 1 人で対応
- 使用した技術：
  - PHP 7.1
  - CakePHP 2
- プロジェクト詳細：
  - 保守運用案件
  - CakePHP 製のフォームの複製と入力項目の改修
- 気づき・苦労したこと：
  - 同じ内容のフォームを 4 つほど複製した後に入力欄の改修が入ったため整合性を保つのが大変だった
  - CakePHP はフォーム関するメソッドが多く用意されておりお手軽に実装できるのが良かった

#### 医薬品ECサイト（2022/07〜2023/4)
- プロジェクト規模：
  - フロントエンドを私 1 人で対応。サーバーサイドは別会社実装
- 使用した技術：
  - TypeScript 4.6.4
  - axios 0.12
- プロジェクト詳細：
  - 受託開発
  - 12 月に公開済み
  - EC サイトのプロジェクトにデザインと HTML を提供するために参加
  - API を叩いて医薬品を検索する機能を TypeScript で実装
  - API を叩いて検索欄のサジェストを表示する機能を TypeScript で実装
  - 商品のお気に入りボタンを押下したら非同期で追加される機能を API を使い TypeScript で実装
  - カートに非同期で商品を追加したり削除したり料金を算出する機能を API を使い TypeScript で実装
  - ユーザー登録画面の住所検索機能を TypeScript で実装
  - その他ほかにも TypeScript でフロントエンド実装した
- 気づき・苦労したこと：
  - TypeScript は完全初見でありドキュメントを見ながら実装を進めた。IDE にはかなり助けられた
  - TypeScript を学んだことで他言語でも型を意識するようになった
  - はじめは検索やお気に入りなどのちょっとした実装であったがシステム会社からの実装依頼がかなり増えたためスケジュール的にかなりきつかった
  - 簡単な実装と想定していたため JS のフレームワークは使っていなかった。スケジュールもタイトでシステム会社との連絡がつきづらいためやむを得ずフレームワークを使わず実装をすすめた。カート周りの実装はかなり苦労した
  - システム会社に仕様の確認や修正依頼をしても反応がかなり遅くスケジュール通りに進められないためやむを得ず自己判断して対応することがあった
  - 苦労したこと全般の原因がクーシー側に裁量権がなかったからだと考えている
  


#### 留学サイトの脆弱性対応および機能の改修 (2022/02〜2022/12)
- プロジェクト規模：
  - 改修や Laravel などのプログラム周りのアップデートは私 1 人で対応。インフラ周りやソースレビューは他エンジニアが対応
- 使用した技術：
  - PHP 5.5.50〜8.1
  - MySQL 5.7
  - Laravel 5〜9
  - Vagrant
  - jQuery
  - Bootstrap
  - larastan
- プロジェクト詳細（バージョンアップ対応）：
  - クーシーで保守していた文科省の留学生向けサイトのミドルウェアバージョンアップ
  - バージョンアップしたサイトは 3 つあり留学のニュースサイト、ユーザーが寄稿した留学体験談を公開しているサイト、留学の奨学金サイトである。すべて Laravel で実装されている
  - 脆弱性診断を受けミドルウェアのアップデートと問題のある処理の修正をすることになった
  - Laravel のバージョンを 5 から 6、さらに 6 から 9 へとアップデートした
  - vendor ディレクトリに格納されているライブラリ以外はドキュメントのアップグレードガイドを確認して対応した
  - バージョンアップにより発生した構文エラーは larastan で洗い出し修正した
  - ユーザーのパスワードが管理画面から閲覧できる状態にあった。Crypt で暗号化されていたため Decrypt で複号できるようになっていた。そのためハッシュ化してさらに生のパスワードを閲覧できないようにした
  - タブナビング対策を行った
  - セッションハイジャックの対策を行った。ログアウト時の処理において regenerate だけではセッションが別ブラウザでは更新されていなかったので flush した後 save してその後 regenerate するという対応をとった
- プロジェクト詳細（留学体験談サイトの改修対応）：
  - 管理画面に管理ユーザーを管理する機能の実装
  - 留学体験談を寄稿したユーザーを管理する機能の実装
  - パスワードをリセットする機能と有効期限付きのパスワードリセットリンクを送信する機能の実装
- 気づき・苦労したこと：
  - Laravel のバージョンアップは当初 6 に上げるだけでよかったが 6 のサポート終了が迫っていたため 9 まで上げることになった。静的解析ライブラリである larastan があったおかげでエラー解消がかなりはかどり予定通りにリリースできた
  - リリース時はインフラ担当が産休に入っており 1 人で公開作業をすることになった。WAF の設定変更が必要だったりかなり手間取ったが無事リリースできた
  - Laravel の Like 検索ではキーワードに含まれるメタ文字を addcslashes でエスケープしないとうまく動作しないことがあるということを知った

#### 園児管理アプリの修正 (2021/11〜2022/07)
- プロジェクト規模：
  - 修正および改修は私 1 人で対応
  - ソースレビューおよびリリースはプロジェクトリーダーが対応
- 使用した技術：
  - PHP 7.2
  - MySQL 5.7
  - Vue.js 1.0.28
  - SQL
  - jQuery
- プロジェクト詳細：
  - 保守・運用で改修対応
  - スクラッチ PHP 製の Web アプリと iOS と Android のアプリがある
  - 新規入園登録フォームで予防接種を入力する欄を改修。もとは固定の入力欄だったが Vue.js で自由に増減する入力欄を実装した。また予防接種を保存する SQL を改修
  - 打刻機能の API のエラーメッセージと表示する条件を追加
  - 生年月日をもとに園児のクラス ID を決める SQL を追加。IF 文と TIMESTAMPDIFF を使った
  - Cookie に保存されている園の ID が DB に存在しているかを判定し、なければユーザーに紐づいている園の ID を Cookie にセットする処理を実装
- 気づき・苦労したこと：
  - Vue.js を初めて触ることになり調べながら修正作業を進めた
  - ダンプデータに文字列の NULL が混じっていた。原因をつかむのに時間がかかってしまった。またサーバーサイドと RDBMS の NULL は異なるので素の SQL を使う実装ではあまり使うべきではないなと思った
  - O/R マッパでなく素の SQL でゴリゴリ実装することになったのでミックさんの SQL の本がかなり役に立った。また Laravel で使っていた Eloquent O/R マッパ のありがたみを知った
  
#### アイコン配布サービスの開発 (2021/05〜2021/08)
- プロジェクト規模：
  - 開発は私 1 人で対応。ソースレビューおよびリリースはプロジェクトリーダーが対応
- 使用した技術：
  - PHP 7.4
  - Laravel 7
  - MySQL 5.7
  - jQuery
  - Laravel admin
- プロジェクト詳細：
  - 自社開発
  - クーシーで制作したアイコンを配布するサイト。2023 年に公開終了している
  - 管理画面で登録したアイコンを一覧で表示し、詳細ページでサイズや拡張子を選択してダウンロードできる
  - 管理画面は Laravel admin というライブラリを使い実装
- 気づき・苦労したこと：
  - システム開発自体がはじめてであったため教えてもらいながら実装した
  - 公式ドキュメントを見ること、ライブラリの中身を見ることの大切さを知った