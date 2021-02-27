## ポートフォリオ
コンペへ取り組むにあたり作成したモデルのコード（GitHub）や分析レポート（PDF）をポートフォリオとさせていただきます。

## 目標
コンペで良い予測精度のモデルを作成し上位に入ること

## 結果
【SOTA】マイナビ × SIGNATE Student Cup 2019: 賃貸物件の家賃予測で**5８位**/575人

## 構造
**data**-- train.csv / test.csv　２つのデータセット  
**feature**--  
creat.ipynb (データから作った特徴量) / used_feature.ipynb　（最終的にモデルに学習させた特徴量）  
**model**--lgbm.ipynb (LightGBMを用いたモデルのコード)  
**graphic**--  
**importance**--feature_importance  
