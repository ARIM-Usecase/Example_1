# ARIM-Academy：　機器データ利活用ユースケース
### タイトル：機械学習によるTi合金の疲労・クリープ寿命予測
### 機器：クリープ試験機
### 分析：回帰分析（勾配ブースティング回帰、SHAP評価）


## データセット

<div style="border:1px solid #000; padding:10px;">
    
本編で扱う creep_data.xlsx" は、177種のTi合金にかかるクリープデータセットです。

[1] S. Sucheta, R. Ashish and S. A. Kumar, "Machine learning assisted interpretation of creep and fatigue life in titanium alloys", *APL Machine Learning*, **1**, 016102 (2023)

"creep_data.xlsx" には、合金の組成のほか、クリープの実験条件ならびに熱処理のデータがセットで含まれています。

<br>  
<img src="./img/m_016102_1_f1.jpeg" width="50%"><br> 

---



**Chemical composition** 
1. Titanium (wt %) Ti 
1. Alumunium (wt %) Al 
1. Vanadium (wt %) Vn 
1. Carbon (wt %) C 
1. Nitrogen (wt %) N 
1. Oxygen (wt %) O 
1. Hydrogen (wt %) H 
1. Iron (wt %) Fe 0 
1. Silicon (wt %) Si 
1. Tin (wt %) Sn 
1. Niobium (wt %) Nb 
1. Molybednum (wt %) Mo 
1. Zirconium (wt %) Zr 
1. Boron (wt %) B 
1. Chromium (wt %) Cr 


**Experimental parameters**  
1. Rupture strain (%) ϵr 
1. Temperature of measurement (cel) Tcreep 
1. Steady state strain rate (1/s) ˙ ϵ 
1. Applied stress (MPa) σ 

**Heat treatment conditions**  
1. Aging temperature (cel) Tage 
1. Aging time (hrs) tage 
1. Solution temperature (cel) Tsol
1. Solution time (cel) tsol