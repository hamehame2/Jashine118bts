# Jashin118bts

## 17 mm key pitch wireless split 35% trackball +70% for windowsPC officeworker
## Who is it recommended for?
  Recommended for those considering their first split keyboard, feeling uncertain about compact keyboards, preferring full-size keyboards, or wanting to try column staggered layouts.
  Recommend to Need to change tenkey pad position from right side to centor or left for phisical pain / CAD operation.
  
  Caution: User need to use this keyboard both hard or right side only. You can not use this one without right hand bluetooth conneting.
  Caution: Case were made by 3DP and it has quality inconsitency, if you need perfect one, Do not get this keyboard. 

## Parts List

|Part|Quantity|
|--|--|
|AKDK wireless controller|1 for one hand. 2 for both hand|
|Conthrough(2.5mm, 9pin)|2 for one hand. 4 for both hand||
|Battery|1 for one hand. 2 for both hand|
|25mm TrackBall, sekigonic PAW3222 sensorkit and cable(6pin 0.5mm pitch 150mm FPC type A)|each 1Qty if you need it|
|USB-C cable|1|
|Tadpole pin D3.0 for left hand|11|
|Choc V2 switch for left hand|72|
|1U less than 16.3mm Keycap for left hand|72|
|Tadpole pin D3.0 for right hand|11|
|Choc V2 switch for right hand|46|
|1U less than 16.3mm Keycap for right hand|46|

## はじめに

17 mmキーピッチ無線分割キーボードです。
テンキーと25mmトラックボール、カラムスタッガード(キーが縦にズレる並びのこと)という特徴を持っています。
118キーありフルキーボード以上のためキー数に困らないと思います。
日本の自作キーボード、および商業製品からするとなかなか見つけられない仕様のために作成しました。
CADなどでテンキーが好きな位置に欲しい人、トラックボールが欲しい人、仕事にも使うのに小さいキーボードでは不安がある人、肩こりなど疲労軽減のため分割にしてかつロウスタッガード以外を探している人、ケーブルを増やしたくない人、レイヤーもあんまり増やしたくない人向けです。
テンキーを左端に改変したり、左手側はテンキーなしの70％に改変など、使いやすいように変更ください。デフォルトでは右手側と通信が必要ですので、左側のみ必要な場合は自己責任で改変してください。
記号類はJIS風味の配置です。右手側の　最上段右上から3番目と2番目でトグルoff/onでJIS風味とzmkデフォルトの出力といじれます。
エンター、BackSpaseなど親指側にあり位置が異なります。無変換と変換が必要な方はキーマップを変更ください。
SandS 長押しでシフト、短いとスペースを実装しています。
ハッピーな人用にCapsLodkの位置を長押しするとCtrlキーとなるようにしています。左下のキーにもCtrlキーは入れていますので抵抗感なく行けると思います。
JISのフルキーボードと異なり、DelとPrintScreenとNumLockと矢印キー以外はほとんど使用しない人もいると思うのでベースレイヤーの単打には割り当てていません。
WindowsPCを想定しており、Macは動作しないコマンドも含んでおり改変が必要です。動作未確認ですので改造ください。

## 注意点
注意！3Dプリンターでは品質にバラつきがありますので、完璧さを求める方はご遠慮ください。このためご理解できる方のみ購入いただきノークレームでお願いします。
　またコードの改変に関しては自己責任でお願いします。
　中古品やバッテリーなどについて尋ねられても回答しかねます。

3DPの部品は射出形成ではないため品質にばらつきがでるため、ご容赦ください。
スイッチプレートの反りはキースイッチをはめれば無視できますのでそのまま進めてください。
トップケースとボトムケースの嵌め合いがきつい、各種の穴がきつい場合は削ってください。
ケースがゆるい場合ボトムケースの爪が内側にそってゆるい場合はゴムやスポンジなどを入れ、爪を伸ばすのに手前側の縁にマスキングテープを貼ったりして隙間を調整してください。
持ち運びでの運用を想定していません。持ち運びをされる方はマグネットや紐などを使用するように各自で改変ください。
はんだ付け不要です。代わりにペンチ、バッテリーの極性を修正用に爪楊枝、固定調整などにテープ類が必要になります。

## キーマップについて
記号のトグル機能を使用しているためgithubからフォークいただき、configのキーマップを直接編集ください。シールドよりもconfigが優先されます。
電源オフの状態でUSBをつなげると、エクスプローラーが開くのでファームウェアを貼り付けて上書きしてください。

ベースレイヤーはレイヤー0となります。レイヤー0からレイヤー8までの9階層分設定できるようにはしています。それだけあれば事足りると思います。
トラックボールを触るとオートマウスレイヤーのレイヤー2に一定時間移行します。一定時間経過後はレイヤー0に戻ります。一定時間は任意でユーザー様が変更できます。
トラックボール操作中にレイヤー3の遷移キーを押していると縦スクロールができます。
トラックボール操作中にレイヤー4の遷移キーを押していると横スクロールができます。
トラックボール操作の速さを変更したい場合はright overlay中のCPIにて調整ください。

レイヤー3と4の遷移キーを押しているとレイヤー5になります。デフォルトではレイヤー5の上部にBluetoothの設定キーをいくつかおいています。
zmkの公式を参照して各自編集ください。
