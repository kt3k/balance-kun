# ジャーナルタブ

ジャーナル, Journal = 仕訳帳
取引, Trade

## 概要

- 取引の入力
- ジャーナルの閲覧
- ジャーナルの修正 (取引の修正)

## 表示要素

- 取引入力ボタン
- ジャーナルリスト表示
  - トレード編集ボタン
  - 1000件まではそのまま表示
  - 1000件を超える場合は、1000件を超えるごとに月で分割して表示
  - 1ヶ月ぶんが1000件を超える場合は、1ヶ月ごと表示
  - 1ヶ月表示でまともに表示できないスケールのユースケースはサポートしない (スマホアプリでやる規模じゃない)

## 行動要素

- 取引入力ボタンから取引を新規入力する
  - OK | Cancel ボタンが出る
- 取引入力の仕分け選択ボックスから[追加]を選んで、AccountType 追加モーダルを出す
- AccountType 追加モーダルから AccountType を追加する
  - すでに入力済の名前のアカウントタイプは追加できない
- 取引編集ボタンから取引を編集する。入力欄は新規入力とほぼ同じ
  - OK | Cancel | Delete ボタンが出る
- 下にスクロールすると過去の取引を遡って閲覧可能