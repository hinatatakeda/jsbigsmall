# FigmeやPower Pointで画像を扱う際の拡大縮小機能を実装してみた！


前回：[JavaScriptで画像をドラッグ・拡大縮小・スクロールによる変化を出してみよう！](https://github.com/hinatatakeda/jsmoveobject)

<img width="328" alt="スクリーンショット 2024-11-22 13 14 25" src="https://github.com/user-attachments/assets/50583da6-caeb-4151-adee-8c11b23e9597">
このドラッグ・拡大縮小機能を実装したい！



さめ幽霊画像が表示されるのは実際のブラウザの中で何が起きているのか


div
img
/div

で、imgからdivに操作されていることが伝播しなかった？
imgだけブラウザのドラッグ処理になってしまっていたからdraggable falseで動かなくすることで逆にちゃんと動くようになった？