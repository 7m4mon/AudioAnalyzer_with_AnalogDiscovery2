# Audio Analyzer with AnalogDiscovery2 and LabVIEW 2020

<img src="https://github.com/7m4mon/AudioAnalyzer_with_AnalogDiscovery2/blob/master/AudioAnalyzer__with__AnalogDiscovery2p_sine.png" alt="" title="">

<img src="https://github.com/7m4mon/AudioAnalyzer_with_AnalogDiscovery2/blob/master/AudioAnalyzer__with__AnalogDiscovery2p_triangle.png" alt="" title="">

<img src="https://github.com/7m4mon/AudioAnalyzer_with_AnalogDiscovery2/blob/master/AudioAnalyzer__with__AnalogDiscovery2d.png" alt="" title="">

Labview 2020 Community Edition 公開を記念して AnalogDiscovery2 を使用したオーディオアナライザーをLabview 2020を使って作ってみました。  
そのまま使った場合、0.1%程度の歪み率は測定可能ですが、AD2のダイナミックレンジの都合で、  
振幅が小さくなると歪み率が悪化します。(100mVp-pで3%程度)  
その場合は、[プリアンプを付けると10mVp-pでも1%まで測定可能となります。](http://nomulabo.com/aa_ad2/)  


<img src="https://github.com/7m4mon/AudioAnalyzer_with_AnalogDiscovery2/blob/master/aa_ad2_out.jpg" alt="" title="">

<img src="https://github.com/7m4mon/AudioAnalyzer_with_AnalogDiscovery2/blob/master/aa_ad2_in.jpg" alt="" title="">

オーディオ機器の測定にはノッチフィルタを使用した方式等を採用する必要がありますが、  
アナログ無線機の12dB SINAD感度くらいは測れるのではないでしょうか。  
