# 複数のスポナーを実装するとき出やすいエラー

## 詳細
スポナーを複数にしたときに親要素をヒエラルキーからコピぺするとその親要素が死ぬとエラーでゲームが止まる

## 発生したエラー
```
MissingReferenceException: The object of type 'GameObject' has been destroyed but you are still trying to access it. Your script should either check if it is null or you should not destroy the object.
```

<b>意味</b>
GameObjectがnull(無い状態)だけどアクセスしてるよー的なこと

## 解決策
アセットの方でエネミーをコピペで増やして、変更を加えてから、スポナーにアッタッチメントすると親要素がnullにならなくらるから解決するよ。