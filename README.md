# 2024_TeamB

**コーディング規約**
```
・クラス名、メソッド名
　PascalCase

・メンバ名
　頭に"_"をつけたうえでのcamelCase
  public変数は必ずプロパティにしてください。
　例）private int _number
　　　public int Number => _number;
　boolの変数または関数の先頭にはis,can,hasを付けてください。
　例）isFlag
　Action,Funcなどのイベントの先頭にはonを付けてください。
　例）onEvent
　定数名は全て大文字にしてください
　例）const int CONST_NUMBER

・コミット文
　[add] : 何かスクリプト、ファイル等を追加した場合
　[update] : スクリプト、ファイル等に変更をした場合
　[remove] : スクリプト、ファイル等を削除した場合
　[clean] : スクリプト、ファイル等を移動した場合
　[fix] : スクリプト等に発生していたバグを解消した場合
　2行目以降は必ず詳しい説明を書き加えてください。

  プルリクエストは最低誰か一人のレビューを受けてからマージすること

・Unityインスペクタ
　インスペクタに公開する変数Header属性をつけてください。
　公開する必要のない変数はprivateにしてください。
```
