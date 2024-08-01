# OpenRule1umPDK_KLayout
OpenRule1umPDK_Xschemと一緒に使う事を想定した自分用KLayout PDKです。

他人が使う事を想定していないので使用は自己責任にて。

# メモ
* LVSルールを改変してOpenRule1umPDK_Xschemに完全対応。
  * 使い方 Make netlistを押して Run KLayout LVS を実施
  * レイアウトファイル名とXschemのファイル名をあわせる必要あり (例: nand.sch, nand.gds)
* PCellやDRCルールはいまのところないのでmineda-supportのものを使用する
   * https://github.com/mineda-support/OpenRule1um
   * https://github.com/mineda-support/AnagixLoader
