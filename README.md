# AccountFraud


undesample.csv
アンダーサンプル済みの不正会計データ（2000年から2017年までの上場企業4約000社を対象）

列リスト
Class	dt1	dt2	dt3	dt4	dt5	dt6	dt7	dt8	dt9	dt10	dt11	dt12	dt13	dt14	Acc	LI
Class：目的変数
dt1～dt14：総資産などの前年度からの増減値
Acc：アクルーアル（会計発生高）dt*から計算
Li：


不正会計.ipynb
undesample.csvを用いて、不正会計ありを1、なしを0としてロジスティック回帰を行う。あらかじめ
交差検証法でL2正則化パラメータC=0.01を定めた。

適合率、再現率、混同行列、ROCなどを求める。
