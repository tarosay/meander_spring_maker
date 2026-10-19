# 手動確認項目

1. 初期表示で「Polyline: True」が選択されている。
2. TXT出力の1行目は `Polyline=True`。
3. Falseに切り替えると、TXT出力の1行目が `Polyline=False`。
4. Falseの状態でJSON保存→読込してもFalseが維持される。
5. 「初期値に戻す」でTrueに戻る。
6. 旧v4 JSONは読み込み時にTrueになり、折り返し方式は維持される。
7. DXF出力・描画・引張変位操作に影響がない。
