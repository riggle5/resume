# 所属・職種:zap:

はじめまして、岸本涼佑と申します。  
現職は株式会社viviONに在籍しており、フロントエンドチームの一員として、WEBサイトやアプリ開発などを担当しております。
前職は株式会社フォーデジットに在籍しており、サービスデザインチームでフロントエンドエンジニアとして働いておりました。
サービスデザインチームでは、主に企業の DX(デジタルトランスフォーメーション)を推進するチームで、大手通信会社様と協力して様々な案件を進めていました。  

# ヴィジョン:dart:

### テック観点から、サービスをリードしていく

ユーザ目線で常に価値を考え、世界の人々が使って楽しい・便利だと言えるような唯一無二のサービスをテック観点からリードしていく。  
また、サービスの企画・設計から参加して、全体を俯瞰してグロースできるような立場で成果を出し続ける。

### デザイン分野にも強いエンジニアになる

ユーザに最適な価値を提供するという点において、UI/UX 等のデザイン領域について考えることは、エンジニアにとっても必要不可欠な課題となってきている。  
また、エンジニア目線でデザインを考えられる能力というものは、移り変わりの激しい昨今の情勢において、とても強みになると考えている。  
そのため、エンジニアリングという垣根を越えて、デザイン分野でも力を発揮できるようなエンジニアになりたい。  
具体的には、グロース等の企画段階から参加したり、UI・インタラクション等について、デザイナーと協力しながら、エンジニア目線で価値を提供していく。

# 案件歴:clipboard:

## **Unity×モーションキャプチャソフトを使用したゲーム案件:space_invader:**

### 期間・メンバー

2018/10 ~ 2018/11  
コンサル 1 名・UX デザイナー 2 名・デペロッパー 2 名

### プロジェクトの概要

某家電量販店のインバウンド消費を拡大するための施策としてスタートしたプロジェクトで、Gestoos というモーションキャプチャーソフトを使用した`Unity`用ゲームの開発。

### コンセプト

サイネージの前に立ったユーザのハンドモーションを備え付けのカメラ側で検知して、それと同期して画面内のキャラクターが特定のアクションを実行するというもの。  
ゲームのコンセプトは忍者手裏剣的当てゲームのような構想で、ユーザ（忍者）が実際に投げるモーションを行うことで、飛翔体（手裏剣）が発射される。ゲーム内にはいくつか的があり、それらに向かって投げることでスコアを競うことができる。

### 学んだこと等

- Unity でゲームを作成した経験  
  途中でプロジェクト自体が中止され、リリースすることはなかったものの、個人的には面白いプロジェクトで、Unity に関する知識を得ることができた。  
  例えば、update 関数等のフレームレートの概念や、ゲーム内のスコア情報の保持、敵オブジェクトに衝突した際の処理方法、スタート・エンド時の挙動など Unity でゲームを開発する上での基本的な実装方法を経験することができた。

### 力をいれたところ

- ゲームシステム等  
  的に命中した際のエフェクトや、スコアボードの実装など、ユーザ目線からあってほしい機能を提案し、追加した。

## **社内稼働管理ツール:clock3:**

### 期間・メンバー

2018/12  
デザイナー 1 名・デペロッパー４名

### プロジェクトの概要

社内向け案件稼働管理ツールの開発。
一日にどの案件で、何時間稼働したかを登録することができ、バックオフィスの方々が社員の稼働状況を把握する際のデータとなる。

### プロジェクトで使用した技術等

- フロントエンド  
  `React`, `Typescript`, `Redux`で SPA を構築。

- サーバーレス  
  案件データは`CloudSQL`で管理し、view 側から非同期で`Cloud Function`のメソッドを実行し、データを取得・格納。

### 学んだこと等

React/Redux を使用した SPA 開発の手法について広く学んだ。

- State の管理手法  
  flux の基本的な概念、action/reducer をそれぞれどのような流れで構築すれば良いか。

- 非同期通信部分の Middleware の実装  
  ライブラリに redux-thunk を使用していたが、具体的な使用方法。  
  React-Redux を使用して、どのように API 通信を実装すればよいのか、実践することができた。

- Cloud Function の実装方法  
  非同期で Clound Function 経由で、SQL 文を発行して DB 上のデータを取得・格納する実装や、Cloud Function のデプロイ方法などについて知見を得ることができた。

### 力をいれたところ

- react-transition-group でのアニメーション  
  実装中に react-transition-group なる react で state の変化を観測してアニメーションを行うライブラリの存在を知り、当プロジェクトに試験的に導入した。  
  React で状態遷移でなにかアニメーションを発火させたい時などにとても便利で、インタラクション実装を効率的に進めることができた。

- chart.js の導入  
  案件の稼働時間を視覚化したいとの要望があったため、chart.js を導入し、canvas で円グラフの実装を行った。ユーザから前より稼働時間が直感的に見やすくなったとの好評を得たので、導入して正解だった。

## **次世代型サイネージ店舗 POC:dress:**

### 期間・メンバー

2019/1 ~ 2019/3  
コンサル 2 名・デザイナー 1 名・リサーチャー 1 名・デペロッパー 2 名

### プロジェクトの概要

リアルのショッピングモールにデジタルサイネージのみを配置した専用のフロアを設け、販売員が不在のデジタルストアはどの程度ユーザに受け入れられるかを検証した実証実験案件。  
EC サイトと連携しており、サイネージに人気のコーディネートを掲載し、埋め込まれた QR コードを読み込むことで実際の商品サイトに誘導して、購買を促す仕組み。  
サイネージには顔認証を行うカメラが設置されており、実際に操作したユーザの年齢・性別等から、売れそうな商品をレコメンドとして出す機能が追加されている。  
当案件では企画から参画し、デジタルストアを基軸に、どのようなサービスを展開すればユーザの反応を得られるかといった UX 部分にも踏み込んで調査・実装を行った。

### プロジェクトで使用した技術等

- フロントエンド  
  `React`, `Typescript`で store の管理に`Mobx`を使用。

- 顔認証システムの活用  
  SPA アプリケーションに顔認証用の SDK を組み込み、カメラに映った人物の年齢や性別や、サイネージ内で、どの商品を選択し、購入まで至ったかなどのデータをリアルタイムで`Google BigQuery`に保存し、商品のレコメンド機能などのためにデータ解析を行えるようなシステムを構築した。

### 学んだこと等

- React hooks の使い方  
  当時外部の勉強会などで React hooks について広く勉強していたため、実験的にこのプロジェクトで hooks を導入した。  
  結果、クラスコンポーネント独特のライフサイクルメソッドの記法からの解放やパフォーマンス面から見ても、hooks を使うことによるメリットをかなり知れたので、デベロッパーチーム内に共通することができた。

- Mobx の導入  
  案件の規模的に Redux だと過剰で逆に煩雑になりそうだったので、比較的軽量で簡素に記述できる Mobx を導入した。

### 力をいれたところ

- UI インタラクション  
  大画面のサイネージで操作するという特殊なアプリケーションだったので、スムーズで気持ちいいインタラクションに拘った。  
  個人的に CSS や Canvas でのアニメーションに興味があり、デザイナーと協力して、導入時のアニメーションや、スワイプ・ズームなどの挙動をブラッシュアップした。  
  結果、ディレクターやデザイナー、また実際に体験して頂いたユーザの方から、インタラクションについて好意的な意見を多く聞けたので、自信がついたとともに、興味のあるインタラクション部分をもっと伸ばしていこうという気持ちになった。

- React hooks、styled-components の社内での布教  
  率先して hooks や styled-components、emotion などを試しに使ってみて、それぞれのメリットやデメリットを社内で共有した。結果、hooks 知っている人の扱いを受けることができた。

- データのリサーチ  
  どのようなコンテンツを作ればユーザの興味を引けるか、実際に使用してもらえるかを第一に、リサーチャーと協力しながら企画を考案していた。その一例として、テック観点から、ユーザデータを活用したレコメンド機能の追加を提案した。  
  具体的には、BigQuery に保存したデータから、ユーザの性別・年齢・その場の滞在時間・サイネージでタップした商品のブランドや種類などを定量的に調査し、この時間帯は１０、２０代が多いから、A ブランドの商品をレコメンドとしてメインに推し出すといった、データリサーチ起点の実装も行った。

## **医療系プロモーションサイト:pill:**

### 期間・メンバー

2019/4 ~ 2018/7  
コンサル 2 名・PM1 名・デザイナー 2 名・デペロッパー 2 名

### プロジェクトの概要

医療系プロモーションサイトの WordPress 開発案件

### プロジェクトで使用した技術等

- フロントエンド  
  `ejs`, `Sass`, `php`を使用し、CMS として`WordPress`を用意し、記事の投稿などが可能なサイトを構築した。

### 学んだこと等

- `Atomic Design`に倣った中規模での WEB サイトの構築  
  atoms, molecules, organisms といった Atomic Design に倣って、CSS コンポーネントの設計を行った。

- WordPress の構築方法等  
  WordPress でのサイトの更新の仕方や、アセットの管理方法について手を動かしながら学ぶことができた。

### 力をいれたところ

- 汎用性のある CSS コンポーネントの作成  
  実装に入る前に、画面上で必要なコンポーネントの種類や状態などを洗い出し、あらかじめ汎用性を持たせる形でコンポーネントの作成を行った。  
  それにより、後のデザイン実装において、コンポーネントの取り回しが良くなり、全体的な実装時間の短縮に繋がった。

- レスポンシブデザインの担保  
  全体的に破綻のないレスポンシブデザインを組むことを目標として、PC、 タブレット、モバイルのどの端末でも崩れがないように、デザインを組むことができた。

- インタラクションの提案・実装  
  企業のプロモーションサイトであったので、インパクトを与えるようなインタラクションには拘った。
  - 背景アニメーションに particle.js を導入
  - clip-path での画像のアニメーションの実装
  - スクロールに連動して要素をスムーズにレンダリングさせる実装
    結果的に、デザイナーやクライアントからインタラクションかっこいいねといった意見を聞けたので、嬉しくなるとともに、スキルアップに繋がった。

## **シャツ・スーツカスタムオーダーサイト:necktie:**

### 期間・メンバー

2019/8 ~ 2020/3  
コンサル 2 名・PM2 名・デザイナー 2 名・リサーチャー 2 名・デペロッパー 5 名（Max）

### プロジェクトの概要

大手百貨店が新規に企画した`カスタムシャツ/スーツオーダーメイドサイト`のフロントエンド開発案件。
このサイトの魅力として、`自動採寸`という、全身の写真を数枚撮るだけで自動的に採寸が可能となる技術を導入した。  
これにより、採寸・サイズの調整に時間がかかるといったオーダーメイドのデメリットを極力廃止し、スピーディーに商品を注文できるという点から、ユーザの体験価値の向上を実現した。  
API 通信は SFCC というセールスフォースが提供している EC プラットフォームサービスを使用。

### プロジェクトで使用した技術等

- フロントエンド  
  `React`, `Typescript`で、State 管理に`Mobx`を使用。

- Headless CMS  
  ユーザが投稿したレビューやお知らせ等記事の管理に Headless CMS の`Prismic.io`を導入。

### 学んだこと等

- 大規模 Web アプリケーションでの`Mobx`を使用した Store の設計・実装方法  
  具体的には、どの粒度でストアを作成するか、ストアとして保持しておくべき値の範囲など。  
  どの値を Observable として持つか、action での Observable の mutate の仕方、computed での filter の仕方等。

- Typescript での、interface, generics 等の効率的な使い方  
  今まで応用的な Typescript の記述についてあまり手を付けて来なかったが、今回の案件で型制約を生かしたコーディングについて実践的に習得することができた。

- Mobx を使用した非同期処理の実装  
  Async/Await と、Mobx の runInAction とを活用した非同期処理の実装方法。

- React hooks でのカスタムフックの活用  
  複数のコンポーネントで使う汎用的な処理はカスタムフックとして切り出すことで、コードの保守性を担保した。

- Headless CMS  
  Headless CMS である Prismic.io との連携方法。具体的には、非同期で CMS 側の情報を fetch する実装について。また、apiClient 部分の実装方法。

- ルーティング  
  hookrouter というライブラリを活用した React 内部でのルーティングの実装方法について。

- styled-component での実装  
  styled-component & styled system(styled-components の記述を簡素化するライブラリ)を使用した、Atomic Design の設計方法。

### 力をいれたところ

- コンポーネントの保守性担保  
  コンポーネントの数が比較的多かったので、Atomic Design に倣って、チームメンバーが使いやすいコンポーネントの設計・実装を目指した。  
  その結果、他メンバーが実装する際に、あらかじめ用意したコンポーネントを組み合わせて使えば、短時間で実装できるようになり、実装の効率化やスケジュールに余裕を持たすことができた。

- パフォーマンスの向上  
  エンドユーザには SPA 特徴のスムーズな画面遷移やインタラクションを体験して欲しかったので、レンダリングコストの軽量化（一部処理のメモ化や computed プロパティの効率的な使い方等）や画像の lazyload 対応など、比較的軽いサイトになるように最適化を行った。

- 自動採寸  
  自動採寸については、他社製の SDK を組み込む形で実装していた。  
  実装していた当初は、写真を撮った後にエラーが多発する、画角内に人物がいるのに認識してくれないなど、多くの不具合に見舞われた。その度に、SDK の提供会社に解決方法について問い合わせたり、テックリードと相談して検証を行うなど、ブラッシュアップを重ねた。  
  最終的には不具合なく動作するものを実装し、使用したユーザからも自動採寸について好評を頂くことができた。

- デザイナーとのコラボレーション  
  サイトのターゲットとして、モバイルユーザが第一に掲げられていた。そのため、スマホでの操作感や、UI 面での改善点について、直接デザイナーとコミュニケーションを取り、テック観点からどのように実装に落とし込むべきか、ペアプロのような形でデザインの実装を行っていた。  
  結果、クライアント等から UI について肯定的な意見を頂くことができた。

## **タスク管理モジュール開発:date:**

### 期間・メンバー

2020/4  
UX デザイナー 1 名・デザイナー 1 名・デペロッパー 1 名

### プロジェクトの概要

Google カレンダー・スプレッドシートを掛け合わせたようなタスク管理モジュールの開発。

### プロジェクトで使用した技術等

- フロントエンド  
  `React`, `Typescript`で作成し、軽量なモジュールだったため、state 管理に`Context Api`のみで対応。

### 学んだこと等

- タスク管理モジュールの実装  
  今までの React のおさらいとして、Google カレンダーのようなモジュールを一度開発してみたいと思っており、手を挙げて参加した案件。  
  タスクのドラッグ＆ドロップでの移動や追加、行・列の移動・追加、テーブルの移動・追加などシンプルだけど、state の設計・実装力が問われるようなモジュールを一人で実装仕上げた。

### 力をいれたところ

- 操作性の向上  
  シンプルだけど何か付加価値を付けようと思い、Trello のようなドラッグ＆ドロップの操作性や、スプレッドシートのような行列やテーブルの移動やコピーを実現した。

## **航空券予約サイトのリニューアル案件:airplane:**

### 期間・メンバー

2020/4 ~ 現在  
コンサル 2 名・PM 1 名・UX デザイナー 3 名・デザイナー 2 名・デペロッパー 3 名・オフショア/業務委託 6 名

### プロジェクトの概要

旅行代理店向けの航空券予約サイトのフロントエンドリニューアル案件。  
既存のCUIベースの予約サイトを、CUI自体は残しつつも、全体的にモダンなGUIベースのサイトにリニューアルするという内容。  
コマンドでのオペレーションに慣れている社員（CUIメイン）と、デジタルに慣れている若手の社員（GUIメイン）の両者がともに使いやすいサイトを目指してリニューアルを行った。  
サイトの機能として、iframeで埋め込まれたCUI部分との非同期通信連携や、データの取り回し、モーダルウィンドウの複数配置など、仕様が複雑なところが多々あったため、設計・実装する過程で、常にクライアントや他チームメンバーと認識を合わせながら進めていた。  

### プロジェクトで使用した技術等

- フロントエンド  
  `React`, `Typescript`で、State 管理に`Redux`を使用。  
  また、API との非同期通信部分に`rxjs`, `redux-observable`を導入。  
  フォームの validation に関して、view 側との接合に`react-hook-form`とスキーマ定義に`yup`を使用。

- API  
  OpenAPI の定義は yaml で記述したスキーマを`stoplight prism`により生成。

### 学んだこと等

- hook 時代の Redux の実装方法  
  useDispatch, useSelector 等の hooks に対応した後の、redux の実装について実践的に学ぶことができた。

- 大規模アプリケーションでの Redux Store の設計・実装方法  
  主に画面ごとにaction, reducer, selectorを用意し、イミュータブルなstateの変更方法(案件内ではimmerjsというライブラリを使用)や、selector周りのメモ化を利用した効率的なstateの取得の仕方について広く理解することができた。

- yup を使ったバリデーションスキーマの定義  
  個人的な React の特徴として、フォーム周りの実装がなかなか困難という点が上がるが、今回は yup でバリデーション用のスキーマを定義し、react-hook-form で view 側と繋ぎこむという実装を行った。

- rxjs を使用した非同期処理の実装  
  今回初めて rxjs に触れたが、その特有の作法である、Observer パターンや、filter、mergeMap をどのタイミングで使うかなどを実装する中で抽象的に理解することができた。

- iframe との通信部分  
  iframe との非同期通信に window オブジェクトが持つ postMessage メソッドを活用し、イベントの post や非同期によるメッセージ通知などを実装した。

- ユニットテストの実装  
  Jest を導入し、reducer, validator に mock を使用したユニットテストケースを実装した。

- オフショアの活用  
  デザイン実装などを一部海外のメンバー（ベトナム等）にオフショアしており、彼らと英語上でコミュニケーションを取る中で、英語でどう伝えれば理解してもらえるかなどを常に考えて行動していた。

### 力をいれたところ

- D3.js の導入  
  サイト内に一部グラフを表示させる部分があり、その描画に D3.js を導入した。データビジュアライゼーションなどに興味があったので、D3.js を実際に使用してみることで、その利点などに気付くことができた。

- API 定義の強化  
  バックエンドチーム（別会社）との API 設計にも参画し、フロントエンド側の視点から、どのようなパラメータが必要か、JSON の構造的にどう送られてくるのが最適か、型は何を指定すればよいかなど、議論を行った。  
  その結果、実施前と比較して、API 定義全体をブラッシュアップすることに成功し、後の API 通信部分のフロントエンド実装を効率的に進めることができた。

- Notion の活用  
  技術的な面ではないが、Notion を活用し、開発フローや、実装する中で発覚した課題点などをドキュメントとして明文化し、後続のメンバーに伝えることで、メンバー間の認識の相違などが比較的減少した。

- 外部リソースのマネジメント  
  一部機能等をベトナムなどの外部人員にオフショアしていたため、彼らのリソースのマネジメントなどを行っていく過程で、先方に渡すタスクの粒度の妥当性や、英語でのコミュニケーションなどについて、今まで経験できなかったマネジメント系の分野に力を入れた。  
  結果、オフショアしやすい体制を作ったことで、スケジュールにも余裕を持つことができた。
  
## **コミックアプリ 漫画ビューアの開発:books:**
  
### 期間・メンバー

2021/4 ~ 2022/4 (他の案件と並行して実装)   
ディレクター 1 名・デザイナー 1 名・Unityエンジニア 7 名・フロントエンドエンジニア 2 名

### プロジェクトの概要

Unityで作成したコミックアプリに、漫画を閲覧する部分をWebviewとして組み込むといった仕様のアプリ開発。  
自分はフロントエンドエンジニアとして、webviewの実装部分を担当した。  
ビューアの基幹部分は他会社が提供しているシステムを仕様し、一部カスタマイズする形で対応した。  

### プロジェクトで使用した技術等

- フロントエンド  
  `React`, `Typescript`を使用

### 学んだこと等

- Unityアプリにwebviewとして漫画ビューアを乗せるという他に類を見ない仕様のプロジェクトであったが、React<=>Unityのイベントの連携部分など多くの知見を貯めることができた。

## **デジタルコンテンツ配信サイトの改修:loud_sound:**

### 期間・メンバー

2021/4 ~ 2022/4 (他の案件と並行して実装)   
デペロッパー 6 名

### プロジェクトの概要
サイト内で購入したデジタルコンテンツ（電子書籍・音声作品・動画など）を視聴・閲覧できる配信サイトのリニューアル案件。  
vueで構築されていたサイトを、機能はそのままにReactで再構築するという目的で改修を実施した。

### プロジェクトで使用した技術等

- フロントエンド  
  `React`を使用し、状態管理に`Recoil`を導入した。  
  また、API通信部分には`SWR`を入れ、`msw`を用いてモックサーバを構築しながら実装を行っていた。  
  取得したデータは`Indexed DB`で管理するようにし、専用のライブラリである`Dexie.js`を導入し構築を行った。

### 学んだこと等

- Recoil  
  以前から興味のあったRecoilをチームに提案し、共有資料などを作成しながら導入を行なった。  
  案件で初めてRecoilを導入したので、storeの作り方やコンポーネントからの呼び出し方法など基本的な部分を習得することができた。  
  atom, selectorなどの使い分け方も、色々と試しながら最適解を見つけることができた。  

- SWR  
  api fetch部分にswrを導入し、取得したデータのキャッシュを行い、通信部分のパフォーマンスの高速化を図った。

- Indexed DB (Dexie.js)  
  Indexed DBまたは、Dexie.js自体初の試みであったが、率先して導入を行い、スキーマの作成や、コンポーネントから呼び出す用のhookの作成まで担当し、
  広く知見を貯めることができた。

### 力をいれたところ

- プロジェクト内で触れた技術の社内共有
  多くの新しい技術を試したり、実際に導入したりできたので、それによって知り得たナレッジを社内共有という形でチームに還元し、メンバーの技術力向上を目的に動くことができた。

## **音声作品ストリーミングアプリの開発:headphones:**

### 期間・メンバー

2022/5 ~ 現在  
ディレクター 1 名・デザイナー 3 名・エンジニア 1 名

### プロジェクトの概要
サイト内で購入した音声系のコンテンツを聴けるストリーミングアプリの開発。  
自分は要件定義段階から参画し、技術選定・機能実装に至るまでほぼ一人で行なっていた。

### プロジェクトで使用した技術等

- フロントエンド  
  アプリ開発ツールとして`React Native` `Typescript`を使用し、
  モバイルデータベースに`Realm`を導入した。

### 学んだこと等

- React Native  
  以前からアプリ開発に興味があり、まずは知見のある言語からということでReact Nativeを用いて開発を行なった。  
  React Native固有の画面の組み立て方、各画面へのナビゲーションなど広く学ぶことができた。

- React Nativeにおける音声再生周りの構築方法  
  今回は音声周りのライブラリとして`react-native-track-player`を導入し、ストリーミング機能の実装を図った。

- Realm  
  モバイル用のデータベースとしてRealmを導入し、API通信時のデータをアプリ内部のデータベースとして保持することで、全体的なパフォーマンスの向上に貢献することができた。

### 力をいれたところ

- 最高のストリーミングアプリを開発すること  
  以前から興味のあったモバイルアプリ＆ストリーミングアプリ開発に挑戦することができる環境であったので、アプリのUX部分やパフォーマンス部分に関して、
  他のアプリと比較して遜色がなく、またはそれ以上になるように力を入れて開発に臨んでいた。
