# 新中文編程語言

吾編程語言基中文文言，一字以達意。

[彼](https://github.com/wenyan-lang/wiki/blob/master/Syntax-Cheatsheet.md)云：`吾有一數。曰三。名之曰「甲」。`\
我作：`整甲置三。`

彼云：`吾嘗觀「「算經」」之書。方悟「正弦」「餘弦」「圓周率」之義。`\
我作：`引《算經》得「正弦」「餘弦」「圓周率」。`\
註曰：`引《算經》得一`，《算經》諸法盡可用也。

彼云：`吾有一物。名之曰「甲」。其物如是。物之「「乙」」者。數曰三。物之「「丙」」者。言曰「「丁」」。是謂「甲」之物也。`\
我作：`物〈如是〉有數乙、文丙。〈如是〉甲置「乙」三、「丙」『丁』。`

彼之法，蓋譯歐洲計製協會之編碼也，非中國人之法也。

## 關鍵字
右八十八字不可以定名。
```
數字：〇一二三四五六七八九十百千万亿兆升降
（大寫）零壹貳叁肆伍陸柒捌玖拾佰仟萬億
品類：陰陽有無爻數整實複文列物類術入成引得
控制：若則否也恆爲是云凡中至止次歸
運算：置用之進退正負乘除模加減不大小等於在與抑或非
調試：書
```

## 符號

「單引號」注名，『雙引號』注文，《雙書名號》注模組，〈單書名號〉注品類，（括號）注式以先其算。
句點（。）終語句。

## 文件約定
半型爲文法符號，全型爲代碼文字。文法推導依`<尖括號>:表達式`。\
`[方括號]`：可選。\
`{大括號}`：組合。\
`竪|綫`：多選一。\
`(甲,乙)`：前一文`甲`至`乙`遍。\
`(甲)`：前一文`甲`遍。\
`(甲,)`：前一文`甲`遍以上。\
`(,甲)`：前一文〇遍以上，`甲`遍以下。\
`文...`：依`文`一遍以上，限於所在括號之内

## [品類](./types.md)
## [名數](./expressions.md)
## [指令](./statements.md)
