# Python3

## Coding Style

## スコープ

Pythonでは、`if`文によってスコープが切り替わりません。   
そのため、C++などで期待される動作とは異なるnamespaceを持つことがあります。   
混乱の元なので、自分では使わないようにするべきですが、他人のコードでそのような箇所を見つけたら読み込んで理解する必要があります。   
（可能なら書き換えるべきです。）

> Python では if 文などの制御構造でもスコープが変わらないので、 if 文のブロック内で初めて定義された変数は、そのブロックを抜けた後でも参照することができます。
[参考](https://uxmilk.jp/41353)

## Type Annotations

[特殊な型](https://qiita.com/icoxfog417/items/c17eb042f4735b7924a3)
[特定のオブジェクトのみを許すようにするType Annotation](https://future-architect.github.io/articles/20201223/)
