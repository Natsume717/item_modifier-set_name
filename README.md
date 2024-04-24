# item_modifier-set_name
item_modifierの1項目であるset_nameに関するサンプルになります。

詳しくはブログ記事『[【マイクラ】set_nameでアイテム名を変更【item_modifier】](https://natsumake.com/set_name/)』を参考にしてください。

<h3>概要</h3>
アイテムに対して、名前を適用させることが可能です。

<h3>使い方</h3>

データパック導入後、ワールドに入り```/reload```と入力し実行してください。

タラを倒すことで、デフォルトとは異なる名前が付け加えられたダイヤモンドをドロップします。

また、手元のアイテムに対して、以下のコマンドを実行することで名前を変更することが可能です。

```copy
/item modify entity @s weapon.mainhand sample:set_name
```

以下のコマンドの場合は、色付き文字など細かな設定を施したものになります。

```copy
/item modify entity @s weapon.mainhand sample:set_name_advanced
```

説明文と共に指示しているものを適用した場合は、以下のコマンドを実行してください。

```copy
/item modify entity @s weapon.mainhand sample:with_lore
```
