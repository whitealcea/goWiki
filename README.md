# goWiki
Go言語で作成した、Web上からテキストの参照・編集ができるプログラム

# ページ
## トップ
- http://localhost:8080/top
- 登録されているページの一覧が表示される画面
- 本画面から登録されているページの参照・編集ができる

## 参照画面
- https://localhost:8080/view/XXX(PageTitle)
- 登録されているテキストを参照する画面
- 「Edit」リンクから編集画面に遷移することができる
- 「XXX」に存在しないページ名を入力した場合、編集画面にリダイレクトする

## 編集画面
- https://localhost:8080/edit/XXX(PageTitle)
- テキスト新規作成・編集画面
- 「XXX」の名称でテキストファイルを保存する
- 「Save」ボタンで保存する

# 制約
- ページ名は半角英数字のみ
