# 新中文編程語言

吾編程語言基中文文言，一字以達意。

[彼](https://github.com/wenyan-lang/wiki/blob/master/Syntax-Cheatsheet.md)云：`吾有一數。曰三。名之曰「甲」。`\
吾法：`整甲置三。`

彼云：`吾嘗觀「「算經」」之書。方悟「正弦」「餘弦」「圓周率」之義。`\
吾法：`引《算經》得「正弦」「餘弦」「圓周率」。`\
註曰：`引《算經》得一`，《算經》諸法盡可用也。

彼云：`吾有一物。名之曰「甲」。其物如是。物之「「乙」」者。數曰三。物之「「丙」」者。言曰「「丁」」。是謂「甲」之物也。`\
吾法：`物〈如是〉有數「乙」、文「丙」。〈如是〉甲置｛乙：三、丙：『丁』｝。`

彼之法，蓋譯歐洲計製協會之編碼也，非中國人之法也。

## 符號
用全型。
|符號|含義
|-|-
|「單引號」|家用名
|『雙引號』|公用名
|【實方頭括號】|家用類
|〖空方頭括號〗|公用類
|《雙書名號》|模組
|〈單書名號〉|篇
|（括號）|注式以先其算
|＇單引號＇|字常量
|＂雙引號＂|文常量
|＃注釋|注釋單行
|句點（。）|終語句
|逗點（、）|分隔參數

## 文件約定
半型爲文法符號，全型爲代碼文字。文法推導依`<尖括號>:表達式`。\
`[方括號]`：可選。\
`{大括號}`：組合。\
`竪|綫`：多選一。\
`(甲,乙)`：前一文`甲`至`乙`遍。\
`(甲)`：前一文`甲`遍。\
`(甲,)`：前一文`甲`遍以上。\
`文...`：依`文`一遍以上，限於所在括號之内。

## [品類](./types.md)
本類：陰陽、整數、浮點，可複合。

## [名數](./expressions.md)
如下五十四字名局部變量，不必用引號。清末李善蘭等譯泰西算術之書，以十干、十二支、天地人物對二十六羅馬字母，二十八宿對二十四希臘字母，故吾仍之。
```
甲乙丙丁戊己庚辛壬癸子丑寅卯辰巳午未申酉戌亥物天地人
角亢氐房心尾箕斗牛女虛危室壁奎婁胃昴畢觜參井鬼柳星張翼軫
```
## [指令](./statements.md)
順序、判斷、循環三義。
