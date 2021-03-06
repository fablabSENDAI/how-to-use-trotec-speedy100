---
layout: default
title: 03.JobControlのセット
nav_order: 4
---

# 03.JobControlのセット
<br><br>

## 03.1 ジョブの読み込み
<br>

<img src="assets/03-1.png" width="640" alt="hi" class="inline"/><br>

Adobe Illustratorでジョブに名前をつけ、**“Apply”**をクリックすると、<br>
マシンを操作するためのソフトウェア**「TROTEC JobControl X」**が起動します。<br>
画面右側のジョブリストの中に、先ほど作成したジョブが表示されているかを確認します。<br>
<br>
<br>

<img src="assets/03-2.png" width="640" alt="hi" class="inline"/><br>

ジョブネームをダブルクリックすると、Plateと呼ばれる中央のエリアにジョブが配置されます。<br>
加工開始ボタンを押すと、このPlateエリアに表示されているジョブに応じて加工が行なわれます。<br>
<br>
<br>

<img src="assets/03-3.png" width="420" alt="hi" class="inline"/><br>
<br>

画面上部のツールバーに表示されている**“ジョブの透過”**ボタンをクリックすると、<br>
それまで黒く表示されていたジョブ（加工データ）が、元のデータ通りに表示されます。<br>
<br><br>

### ★線や画像が表示されない場合

* Adobe Illustrator上での線や画像の色設定、及びカラーモードがRGBになっているかを確認します。
* 画面左の**"EngraveTimeEstimationBar"**に、<br>
データ作成に使用した色が表示されているかどうかを確認します。<br>
（されていない場合、後ほど設定で表示させることができるのでこのままでOKです。）<br>
<br>
<br>
<br>

## 03.2 レーザーのパワーや加工速度の設定
<br>

<img src="assets/03-4.png" width="420" alt="hi" class="inline"/><br>

画面上部の**“材料テンプレートの設定”**ボタンを押します。<br>
<br>

<img src="assets/03-5.png" width="640" alt="hi" class="inline"/><br>

材料データベースウィンドウが表示されます。<br>
加工データ作成時に設定した色ごとに、加工のプロセスやレーザーのパワー、加工スピードを設定します。<br>
（画面左部から、使用する素材名を選択することでも設定可能です。）<br>
設定が完了したら**“OK”**ボタンをクリックします。<br>
<br><br>

### ★各項目の内容
* **color：**加工データ上での色。カラーボックスの上にカーソルを合わせると、<br>
カラー列の下部にRGBの色成分数値が表示されます。
* **プロセス：**色ごとの加工内容を設定。
    - **彫刻：**ぬりつぶすように、画像部分が削られます。
    - **カット：**ラインに沿ってレーザーが動き、素材が切断されます。
    - **スキップ：**チェックを入れると何も加工されません。Plate上でも非表示となります。
    - **配置：**Plate上では表示されるが、加工はされません。
* **パワー：**レーザーのパワー（最大出力に対するパーセンテージ。0〜100%まで設定可能です。）
* **スピード：**レーザーの加工速度。最速2.8m/秒。<br>
（最大スピードに対するパーセンテージ。0〜100%まで設定可能です。）
* **PPI/Hz：**
    - **PPI（彫刻）：**1インチあたりのレーザーパルス数。<br>
    基本的に1000PPIでOK。dpiと異なり、PPIが増加しても加工時間に影響はありません。
    - **Hz（カット）：**カット時のレーザーパルスの周波数。基本的に1000HzでOKです。
* **自動：**PPIまたはHzの設定値が自動的に設定されます。
* **Passes：**色ごとの加工の繰り返し数を設定。
* **Air Assist：**空気噴射のON,OFFを切り替えられます。基本的にONに設定しておきます。
* **Z-Offset：**ベッドの高さを調整可能だが、必要でない限り0.00に設定します。
* **アドバンス：**必要でない限りデフォルトに設定します。
