# ThesisNoWorries

系統需求


Mathematica 10.0以上

請先在R視窗安裝lavaan及semTools套件

install.packages("lavaan", dependencies = TRUE)

install.packages("semTools", dependencies = TRUE)

install.packages("rJava", dependencies = TRUE)

函數說明：

myfactor[資料, 名目變數, 多群組比較變數("D01", "D02"..), 因素負荷下限, 交叉負荷上限]，量表資料，需含變數名稱。

1. 自動執行項目分析、探索性因素分析、varimax因素旋轉、信度分析，將因素負荷過低或交叉負荷題項刪除，直到因素分析收斂為止。
2. 自動執行驗證性因素分析，包含一階CFA及二階CFA等競爭模型，聚合效度及區隔效度，多群組比較。
