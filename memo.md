# 備忘録
## goの実行までの流れ
`mkdir`でディレクトリを作る -> go.modファイルを作る -> ....
### 外部(もしくは自分で作った)moduleを持ってくるとき
まずはmoduleのpathを編集する  
`go mod edit -replace example.com/greetings=../greetings`  

moduleを適用する  
`go mod tidy`
### 実行するとき
`go run [file name or.]`  

`go build [file name]`で実行ファイル`.exe`だけが作成される  
## 疑問に思った点とその答え
Q1. なぜgoではモジュールの名前を`example.com/なんとかかんとか`と書くか？  
A1. ドメインを仮で置きたいから







