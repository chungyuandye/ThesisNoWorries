# ThesisNoWorries

系統需求

Windows, R-3.0.0

Mac, R-3.6.3

Mathematica 10.0以上

請先在R視窗安裝lavaan及semTools套件

install.packages("lavaan", dependencies = TRUE)

install.packages("semTools", dependencies = TRUE)

函數說明：

myfactor[dataset]，dataset為量表資料，需含變數名稱。

1. 自動執行項目分析、探索性因素分析、varimax因素旋轉、信度分析，將因素負荷過低或交叉負荷題項刪除，直到因素分析收斂為止。
2. 自動執行驗證性因素分析，包含一階CFA，聚合效度及區隔效度（Fornell and Larcker (1981)及Anderson and Gerbing (1988)）。
