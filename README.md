# Animation-Generation-project
本プロジェクトは2022/05/03に始めたプロジェクトです。
## 概要
本プロジェクトの目的は、テキストからアニメーションの作成を行うことです。
続編の制作がなくなってしまったアニメやオリジナルアニメの作成などに活用できると予想されます。



## 進行状況
2022/05/03:アニメーションデータの収集を開始\
2022/05/05:ルールベースによるシーン検出プログラムの作成([https://github.com/tsutsui-439f340f/scene_separation](https://github.com/tsutsui-439f340f/Scene-Separation-rule-base)) \
2022/07/07:管理用データベースの構築\
2022/07/10:アノテーションデータの構築を開始\
2022/07/17:シーン数約2500、アノテーション80シーン達成\
2022/08/01:シーン数約3400達成 \
2022/08/03:AEを用いたシーン生成 \
2022/08/10:シーン検出評価タスクの作成(https://github.com/tsutsui-439f340f/Scene-Separation-metrics)

## データセットのシーンの分析
2022/08/01:における約3400個のシーンに対しての1シーン中のフレーム数と秒数\
このデータセットのシーンの定義は場面が一瞬で切り替わるものを指しており、トランジションが使われているシーンは前後まとめて1シーンとしています。\
フレーム数：平均66.1個
![image](https://user-images.githubusercontent.com/55880071/184421152-2e0ec69f-268e-469b-a8c7-32f678697baf.png)
秒数：平均2.54秒
![image](https://user-images.githubusercontent.com/55880071/184421130-2e3d10b7-4917-4e54-a4b8-643a35fc5147.png)

## データ収集状況
![image](https://user-images.githubusercontent.com/55880071/185758496-2774ede8-e99e-4c82-b0b6-300500004e7f.png)



## 備考

