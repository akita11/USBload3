# USBload3

<img src="https://github.com/akita11/USBload3/blob/main/USBload3.jpg" width="240px">

<img src="https://github.com/akita11/USBload3/blob/main/USBload3_back.jpg" width="240px">

モバイルバッテリをマイコンボード等で給電するときに、電源が切れてしまう現象を回避するためのものです。定期的に負荷をかける（少し電流を流す）ことで、電源が切れることを回避します。流す電流量と電流を流す周期は設定できます。[USBload](https://github.com/akita11/USBload)と機能は同一で、受電側のUSBコネクタのみ異なります。


## 使い方

- 本機のUSB Aコネクタとマイコンボード等を、市販のUSBケーブルで接続する
- 本機のUSB TypeCコネクタとモバイルバッテリを、市販のUSBケーブルで接続する

モバイルバッテリを接続すると動作がはじまります。負荷がかかっている（電流が流れている）ときには本体LEDが点灯します。

## 設定の変更

[USBload](https://github.com/akita11/USBload)の資料を参照してください。なお負荷時のLEDは、LED横の「LED」と書いてあるパターン（半田ジャンパ）をカットすることでOFFにできます。


## Author

Junichi Akita (@akita11) / akita@ifdl.jp
