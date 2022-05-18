---
layout: default
title: JobControlのセット
nav_order: 4
---

## 03.JobControlのセット
<br>

#### 03.1 ジョブの読み込み
<br>

<img src="assets/03-1.png" width="640" alt="hi" class="inline"/><br>

Adobe Illustratorでジョブに名前をつけ、**“Apply”**をクリックすると、<br>
マシンを操作するためのソフトウェア**「TROTEC JobControl X」**が起動する。<br>
画面右側のジョブリストの中に、先ほど作成したジョブが表示されているかを確認する。<br>
<br>
<br>

<img src="assets/03-2.png" width="640" alt="hi" class="inline"/><br>

ジョブネームをダブルクリックすると、Plateと呼ばれる中央のエリアにジョブが配置される。<br>
加工開始ボタンを押すと、このPlateエリアに表示されているジョブに応じて加工が行なわれる。<br>
<br>
<br>

<img src="assets/03-3.png" width="420" alt="hi" class="inline"/><br>
<br>

画面上部のツールバーに表示されている**“ジョブの透過”**ボタンをクリックすると、<br>
それまで黒く表示されていたジョブ（加工データ）が、元のデータ通りに表示される。<br>
<br><br>

##### ★線や画像が表示されない場合

* Adobe Illustrator上での、線や画像の色設定及びカラーモードがRGBになっているかを確認する。

* 画面左の**"EngraveTimeEstimationBar"**に、データ作成に使用した色が表示されているかどうかを確認する。<br>
（されていない場合、後ほど設定で表示させることができるのでこのままで良い）
<br>
<br>
<br>

#### 03.2 レーザーのパワーや加工速度の設定
<br>

<img src="assets/03-4.png" width="420" alt="hi" class="inline"/><br>

画面上部の**“材料テンプレートの設定”**ボタンを押す。<br>
<br>

<img src="assets/03-5.png" width="640" alt="hi" class="inline"/><br>

材料データベースウィンドウが表示される。<br>
加工データ作成時に設定した色ごとに、加工のプロセスやレーザーのパワー、加工スピードを設定する。<br>
（画面左部から、使用する素材名を選択することでも設定可能。）<br>
設定が完了したら**“OK”**ボタンをクリックする。<br>
<br><br>

##### ★各項目の内容
* **color：**加工データ上での色。カラーボックスの上にカーソルを合わせると、カラー列の下部にRGBの色成分数値が表示される。

* **プロセス：**色ごとの加工内容を設定。
    - **彫刻：**ぬりつぶすように、画像部分が削られる。
    - **カット：**ラインに沿ってレーザーが動き、素材が切断される。
    - **スキップ：**何も加工されない。Plate上でも非表示となる。
    - **配置：**Plate上では表示されるが、加工はされない。

* **パワー：**レーザーのパワー（最大出力に対するパーセンテージ。0〜100%まで設定可能）

* **スピード：**レーザーの加工速度。最速2.8m/秒。（最大スピードに対するパーセンテージ。0〜100%まで設定可能）

* **PPI/Hz：**
    - **PPI（彫刻）：**1インチあたりのレーザーパルス数。基本的に1000PPIでOK。dpiと異なり、PPIが増加しても加工時間に影響はない。
    - **Hz（カット）：**カット時のレーザーパルスの周波数。基本的に1000HzでOK。

* **自動：**PPIまたはHzの設定値が自動的に設定される。

* **Passes：**色ごとの加工の繰り返し数を設定。

* **Air Assist：**空気噴射のON,OFFを切り替えられる。基本的にON。

* **Z-Offset：**ベッドの高さを調整可能だが、トラブルが起こる可能性があるので、必要でない限り0.00に設定する。

* **アドバンス：**より詳細な設定が可能（データの部分的な加速等）だが、必要でない限りデフォルトに設定する。