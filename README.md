# quotable_otaku_diary

画面遷移図
https://www.figma.com/file/AeJn405Iu5SyKvG7Lmr4NP/Calendar-Generator-(%E3%82%B3%E3%83%9F%E3%83%A5%E3%83%8B%E3%83%86%E3%82%A3)?type=design&node-id=0%3A1&mode=design&t=amKnLzy1GHle5mqF-1

■サービス概要

日記アプリに漫画・アニメの名言を日替わりで表示します。その日の気持ちに合わせて名言が変わります。

■ このサービスへの思い・作りたい理由

- 漫画・アニメが大好きで毎日見ている中で、励まされたり、ワクワクしたり、今日も頑張ろうと思える言葉があります。その名言を詰め込んだアプリを作りたいと思いました！漫画・アニメには素晴らしい名言がたくさんあるので、日常的に行う日記をつける中で、名言を見てほしい。
- 私が以前勤めていた会社で、部署全体がよく見る日めくりカレンダーには、今日の格言が日付の下に印刷されていました。1日の始まりに格言で前向きな気持ちになり、仕事に対する気持ちを律するきっかけになったりしていました。これは私だけではなく、カレンダーを見ていた周りの人も「今日の格言、良いこと言ってる！」と自分の手帳にメモして営業に行ったり、「今日の格言なんだっけ？」と気にしてる人もいました。格言や名言っで日常をほんの少し変えれそう！と思いました。
- 漫画やアニメ文化が普及してきてはいるが、まだアニオタ文化に興味がない人でも、良い言葉には心動きます！知ってもらうきっかけに！
- 1日の終わりに、日記をつけることで、名言がどんなモチベーションに繋がったかを振り返ることができる。

■ ユーザー層について

- 漫画・アニメが好きで、セリフを覚えちゃうくらいの人
- 普段から日記をつけている、日記をつけるのにアプリを利用している人
- 名言や格言が好きで、毎日のちょっとしたモチベーションに繋げたい人

■サービスの利用イメージ

- 会員登録機能
- ログイン機能
- ログアウト機能

名言機能

- 「今日の名言」はトップページのカレンダーと一緒に表示される。
- 名言詳細（名言・気分タグ・作品名・キャラクター名・セリフの詳しい説明：何巻のセリフか、アニメ何話か等）
- 名言お気に入り機能で、見返すことができる。


日記機能

- カレンダー形式で月毎に表示される。
- カレンダーから日付を選んで日記をつける。
- 日付の詳細ページから、日記の登録・修正・削除ができる。
- 日付の詳細ページでも、今日の名言が見れる。
- 日記のキーワード検索で、日記を見つけることができる。

通知機能

- 指定した時間に、LINEから今日の気分で名言を通知
- 指定した時間に、LINEから日記を書いてみようと通知

管理者権限
- 名言登録（名言・気分タグ・作品名・キャラクター名・セリフの詳しい説明：何巻のセリフか、アニメ何話か等）

■ ユーザーの獲得について

SNSなどを通して、アプリを宣伝する

■ サービスの差別化ポイント・推しポイント
- その日の気持ちで名言が変わる。
- 追加して欲しい名言は、要望フォームから依頼できます。
- 日記をつけることで、名言と一緒に1日を振り返ることができる。
- 設定した時間にLINEで「今日の気分」を教えてもらい、気持ちに合わせた名言を通知します。
- 設定した時間にLINEで「今日の名言は〇〇でした、日記をつけてみませんか？」と通知するので日記付け忘れ防止できます。

■ MVP
- 会員登録機能
- ログイン機能
- ログアウト機能
- 名言の詳細
- 月毎のカレンダー
- 日記登録・編集・削除
- 日記詳細ページ
- LINE通知機能
  ・LINEBot
- 今日の名言お知らせ
  ・感情分析APIを使用

■ 今後の実装予定
- 名言お気に入り機能
- 名言お気に入り一覧
- 名言要望フォーム
- 日記のお気に入り一覧
- 日記のお気に入り機能
- 日記のキーワード検索

■ 使用技術
- 感情分析を行うGoogle Cloud Natural Language API
- Rails7系
- Ruby3系
- カレンダーはRailsのgemで実装予定
- LINE通知はlinebotで実装する。
- 日記のキーワード検索に、Stimulus Autocomplete（Rails7 ）で実装予定。
- sorcery
- JavaScript
- MySQL
- 要望中の名言ステータスを管理者が編集でき、申請中はユーザーが見れるようにする。

他利用できそうな技術を検討中です。