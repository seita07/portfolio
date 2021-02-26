## ポートフォリオ
コンペへ取り組むにあたり作成したモデルのコードやダッシュボード（PDF）をポートフォリオとさせていただきます。

## 目標
コンペで良い予測精度のモデルを作成し上位に入ること

## 結果
【SOTA】マイナビ × SIGNATE Student Cup 2019: 賃貸物件の家賃予測で**59位**/575人

## 構造
**data**-- train.csv / test.csv　２つのデータセット  
**feature**--  
creat.ipynb (データから作った特徴量) / used_feature.ipynb　（最終的にモデルに学習させた特徴量）  
**model**--lgbm.ipynb (LightGBMを用いたモデルのコード)  
**graphic**--  
**importance**--feature_importance  

## データの概要
学習用データ（train.csv）/検証用データ（test.csv）  
データ数 ： 31,470行/31,262行  
0	 id	物件ID  
1	 賃料（目的変数）  
2	 所在地	  
3	 アクセス	  
4	 間取り	  
5	 築年数	  
6	 方角	  
7	 面積	  
8	 所在階	物件自体の階数と物件がある建物の総階数  
9	 バス・トイレ	  
10	 キッチン	  
11	 放送・通信	  
12	 室内設備	   
13	 駐車場	  
14	 周辺環境	  
15	 建築構造	  
16	 契約期間	

# 手法とその理由
#　最終的な結果

#こだわったポイント
