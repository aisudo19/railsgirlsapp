アプリ作成コマンド

```
rails new railsgirls
```

アプリの起動コマンド

```
rails server
```

Idea の scaffold を作る

```
rails generate scaffold idea name:string description:text picture:string
```

db の migrate

```
rails db:migrate
```

pages コントローラ、about メソッドの追加・pages/about ページの追加

```
rails generate controller pages about
```
