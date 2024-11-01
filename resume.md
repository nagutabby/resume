---
pdf_options:
  format: A4
  margin: 10mm 10mm
body_class: markdown-body
stylesheet:
  - https://cdnjs.cloudflare.com/ajax/libs/picocss/2.0.6/pico.classless.indigo.min.css
  - main.css
---

<main class='container-fluid'>

# 履歴書
## 名前・連絡先
|||
|---|---|
|名前|笹川 尋翔 (ささがわ ひろと)|
|連絡先|nagutabby@nagutabby.uk|

## 学歴
|年|月|学校|学部・学科・専攻|備考|
|---|---|---|---|---|
|2017|4|新潟県立柏崎高等学校|普通科|入学|
|2020|3|新潟県立柏崎高等学校|普通科|卒業|
|2020|4|金沢工業大学|工学部 情報工学科|入学|
|2024|3|金沢工業大学|工学部 情報工学科|卒業|
|2024|4|北陸先端科学技術大学院大学|先端科学技術研究科 <br> 先端科学技術専攻|入学|
|2026|3|北陸先端科学技術大学院大学|先端科学技術研究科 <br> 先端科学技術専攻|卒業見込み|

## 保有資格
|年|月|名称|
|---|---|---|
|2020|7|ITパスポート試験|
|2020|10|Python 3 エンジニア認定基礎試験|
|2021|2|基本情報技術者試験|
|2021|3|Ruby Association Certified Ruby Programmer Silver version 2.1|
|2021|8|LE-1: Linux Essentials|
|2022|6|AWS Certified Cloud Practitioner|
|2022|8|AWS Certified Solutions Architect – Associate|
|2023|2|Microsoft Certified: Azure Fundamentals|
|2023|3|LPIC-1|
|2023|5|TOEIC L&R 770点|

<div class="page-break"></div>

## プログラミング言語の使用経験
|言語|使用した期間|
|---|---|
|Python|5年|
|Ruby|4年|
|JavaScript|3年|
|Java|3年|
|PHP|2年|
|TypeScript|2年|

## インターンシップ
### 株式会社CirKit
#### 参加期間
- 開始日: 2021年3月1日
- 終了日: 2024年3月31日

#### 概要
SAKITOの開発における貢献を述べる。1つ目は、引換券のペーパーレス化である。これまではSAKITOで入手した引換券をレジで紙の引換券に交換し、さらにその紙の引換券を商品と交換する必要があったが、SAKITOの引換券と商品を直接交換できる機能を追加することでアプリの利便性を向上させた。2つ目は、特典コードの作成・入力機能である。大学近くの自動車学校への入校特典として提供するための特典コードの作成・入力機能を実装し、SAKITOのマネタイズを推進した。3つ目は、システムの保守性向上である。初めにRails 5.0からRails 7.0、Ruby 2.6からRuby 3.2、MySQL 5.7からMySQL 8.0にアップデートした。続いて、ホスティングサービスからIaaS、IaaSからPaaSに段階的に移行することでサービスの運用費を削減した。

###　株式会社Speee
#### 参加期間
- 開始日: 2024年8月15日
- 終了日: 2024年8月30日

#### 概要
チームを作り、与えられたテーマに沿ったWebアプリを開発した。朝会や夕会では「良かったこと」と「悪かったこと」を整理し、サービスの価値を向上させるための方法を考えて問題に対処した。1スプリント目では、チーム全体が同じ方向を向いて作業できるようにするためにチームの目的を言語化し、実際のユーザーが求めている機能や体験を把握するためにユーザーストーリーを分析し、技術選定を行った。2スプリント目では、サービスが必要とする具体的なデータ項目を特定して開発の焦点を絞るために、サービスで利用されるデータを整理し、アプリのデータ構造を定義した。3スプリント目では、データの一貫性を確保するためにデータソースをデータベースに投入し、バックエンドとフロントエンドを実装した。4スプリント目では、実装段階でのエラーや潜在的な問題を特定して修正するために、コードレビューを行った。

<div class="page-break"></div>

### Sansan株式会社
#### 参加期間
- 開始日: 2024年9月2日
- 終了日: 2024年9月20日

#### 概要
単独で開発チームに加わり、技術調査から実装後の性能調査までの工程を通してWebアプリのパフォーマンス改善に取り組んだ。1スプリント目では、問題の原因を調査し、パフォーマンス改善のための設計を考えた。2スプリント目では、改善策を実装し、さらに改善策の効果や新たな課題を早い時期に発見するために、開発環境での性能調査を行った。3スプリント目では実装した改善策が期待通りに動作することを確認するためにテストケースを作成し、本番環境に近い条件下でパフォーマンスを評価するためにステージング環境での性能調査を行い、リリースに向けてデプロイの設定を行った。

## ポートフォリオ
|||
|---|---|
|GitHub|https://github.com/nagutabby|
|Speaker Deck|https://speakerdeck.com/nagutabby|
|ブログ|https://blog.nagutabby.uk/|

## 制作物
### SAKITO
#### 技術スタック
- フロントエンド
  - Ruby, Ruby on Rails, HTML, CSS, SCSS, JavaScript, jQuery, Bootstrap
- バックエンド
  - Ruby, Ruby on Rails
- インフラ
  - Railway, Docker, CircleCI, Google Workspace, MySQL

#### 概要
金沢工業大学の学生や教員をターゲットにしたアプリである。アンケートに回答することでポイントを獲得でき、そのポイントを使用してガチャを回せる。ガチャからは大学の学食やコンビニで使える引換券を入手できる。URL: https://sakito.cirkit.jp/

<div class="page-break"></div>

### @連絡網
#### 技術スタック
- フロントエンド
  - Ruby, Ruby on Rails, HTML, CSS, SCSS, JavaScript, Bulma
- バックエンド
  - Ruby, Ruby on Rails
- インフラ
  - Amazon EC2, Amazon S3, Amazon SES, ELB, AWS Certificate Manager, Docker, GitHub Actions, MySQL

#### 概要
石川県内の学校をターゲットにしたアプリである。教員はメーリングリストを管理したり、メールの予約送信機能などを利用して生徒にメールを送信したりできる。URL: https://atren.jp/

### nagutabbyの考え事
#### 技術スタック
- フロントエンド
  - Svelte, SvelteKit, HTML, CSS, SCSS, TypeScript, Pico CSS
- バックエンド
  - TypeScript, microCMS
- インフラ
  - Fly.io, Mailtrap, Docker

#### 概要
個人ブログである。余計なデザインを省き、シンプルに仕上げることで記事の読みやすさとアプリの使いやすさを改善した。ビューポートの大きさに応じて取得する画像の大きさを変えたり、アプリの依存関係を減らしたりすることでパフォーマンスを改善した。CDNやService Workerを使うことでレスポンスタイムを削減した。お問い合わせページではSSRを、それ以外のページではCSRを用いることでセキュリティの確保とスムーズな画面遷移を両立した。URL: https://blog.nagutabby.uk/

## 自己PR
私の強みは、幅広い技術への探究心と実践的な問題解決力、チームの技術力向上を推進できる行動力、そして新しい課題への柔軟な適応力である。

まず、Webアプリケーション開発における、幅広い技術理解と実践力について述べる。3年間の課外活動を通じて、インフラ、バックエンド、フロントエンドのそれぞれの領域でチームに貢献した。例えば、Linuxサーバーの運用を通じたCI/CD環境の整備、データ出力機能を含むAPIの開発、テンプレートエンジンとCSSフレームワークの刷新による開発効率とデザインの柔軟性の向上がある。現代のWeb開発では、それぞれの技術領域の相互関係を理解し、適切に統合できる人材が求められており、この経験は大きな強みになると考える。

次に、チーム全体の技術力向上を推進できる行動力について述べる。インフラの知識が不足している状況を改善するために、AWS勉強会やLinuxハンズオンを企画・開催した。また、新人の技術的な疑問を迅速に解決するためにペアプログラミングを導入し、さらにドキュメント管理をNotionに移行することで運用コストを削減し、より質の高いドキュメンテーションを実現した。これらの取り組みを通じて、個人の技術力向上だけでなく、チーム全体の生産性向上にも貢献した。

最後に、新しい課題への柔軟な適応力について述べる。個人としては、インプット中心の学習に限界を感じた際に、課外活動やコミュニティーへの参加を通じてインプットした知識を他者に分かりやすく伝える取り組みを行い、インプットとアウトプットを結びつける学習スタイルに転換した。また、組織の課題に対しても、1年目はインフラ基盤を刷新してシステムの安定性を向上させ、2年目以降はWebアプリケーションの開発を通じてユーザー体験の向上や収益化を実現するなど、状況に応じた価値提供を行ってきた。

このように、幅広い技術への理解があるからこそチームへの効果的な共有ができ、また新しい課題への対応力があるからこそチームが直面する様々な課題を解決できている。今後は、これまでの経験で培った強みを活かしながら、特定の技術領域での専門性も高めることで、より大きな価値を提供できるエンジニアを目指していきたいと考えている。

</main>
