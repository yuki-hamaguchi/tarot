# README

# アプリ名
　生年月日占い（占い師用）

# 概要
　タロットカードの生年月日占いを行い、ソウルカード、パーソナルカード、内容を表示し、クライアント情報を保存管理できる占い師専用のアプリケーションです。
 
# 制作背景
　１）生年月日占いは、計算しその数字からカードを調べて内容を伝える手順が生まれます。
　生年月日は、変わることがないので一度占った結果があれば計算し直す必要がない。
　一度、占ったクライアントは過去のデータを直ぐにみたい。
　限られた時間内でクライアントの悩みに答えないといけないのが占い。少しでも手間を減らしクライアントと話す時間を増やすのが目的です。
 
 ２）誰でも気軽に占いができるアプリケーションの試作品も兼ねています。

# 実装予定内容
・生年月日占い　＝　苗字、名前、西暦の生年月日を入力する。

　苗字、名前はクライアント名として保存。生年月日から「ソウルカード」「パーソナルカード」「星」の番号、カード名、内容を表示し占い結果を保存。
 （追加、相性の良い相手の表示も）
 
・クライアントデータ　＝　クライアント名を入力。

　過去に、占ったクライアントの情報が表示。
　
 
・カルテ機能　＝　タロットカードを使った占い結果を記述できる。カテゴリ分けをして少ない入力で保存。

　「ホロスコープ法（総合運）」配置箇所にカード番号と向きを記入。結果が表示される。
　「ケルト十字法」内容を選択、配置箇所にカード番号と向きを記入。結果が表示される。
 
 
 # 実装予定内容２
 ・クライアントログイン機能　＝　クライアントが自分の名前とパスワードを入力。
　自分のみの生年月日占い結果、過去に占ったデータを見ることができる。
 
 ・ワンカード・スプリット　＝　クライアントがボタンをクリック。
　1日一回限定のその日の占い結果が表示。クライアントデータに保存。

