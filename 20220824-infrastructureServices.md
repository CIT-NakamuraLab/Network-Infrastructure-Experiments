# HSRP,QoS,SNMP

## 概要
- 実験日: 2022/07/24
- CCNA第 11章 その他のインフラストラクチャサービスと運用

---
## 1 実験環境と構築

!["実験画像"](./images/20220824-infrastructureServicesImg/20220824-infrastructureServices_1.jpg)
#### 図1:実際に構築の際に用いた図
図１をCiscoパケットトレーサーで再現し以下に示す。
!["Ciscoのパケットトレーサーで再現したospfの設計画像"](./images/20220824-infrastructureServicesImg/20220824-infrastructureServices_2.png)
#### 図2,Ciscoのパケットトレーサーで再現したospfの設計画像

> 簡易的な構築手順を以下に示す。<br>
>   ① すべての端末にIPアドレスを割り当てる｡<br>
>   ② RT1及びRT2には､スタンバイグループを1にする｡<br>
>   ③ RT1､RT2には､プライオリティ値を110､100を割り当てる｡(RT1:アクティブルータ､RT2:スタンバイルータ)<br>
>   ④ RT1､RT2にプリエンプトコマンドを打ち込む｡<br>
---

