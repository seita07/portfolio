## ポートフォリオ
コンペへ取り組むにあたり作成したモデルのコード（GitHub）や分析レポート（PDF）をポートフォリオとさせていただきます。

## 目標
コンペで良い予測精度のモデルを作成し上位に入ること

## 結果
【SOTA】マイナビ × SIGNATE Student Cup 2019: 賃貸物件の家賃予測で**58位**/575人  


<img width="1440" alt="signate_junni" src="https://user-images.githubusercontent.com/61231053/109386337-5e7abc80-793d-11eb-9e87-751daa81e934.png">


## 構造
**data**-- train.csv / test.csv　２つのデータセット  
**feature**--creat.ipynb (作った特徴量) / used_feature.ipynb（最終的に用いた特徴量）  
**model**--lgbm.ipynb (LightGBMを用いたモデルのコード)  
**importance**--feature_importance  
