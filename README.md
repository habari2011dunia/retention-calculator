放射性物質を摂取したときの体内残留量を選択した体内動態モデルに基づいて計算し, グラフ表示します。キーボードで数値を入力するときは半角数字を使用してください。

表示が途中で切れてしまう場合は[こちら](http://bl.ocks.org/habari2011dunia/raw/7643845/)でご覧ください。

ICRPモデルを選択した場合, 預託実効線量を計算して表示します。
摂取量から預託実効線量への換算係数には経口摂取条件のものを使用しています。

1日あたり尿排出量の計算ではすべての排出のうち尿による排出が80%であると仮定しています。

なお, 現バージョンでは成長に伴う係数変化は計算に加味されていませんので, 
小児の長期慢性摂取に関しては計算結果が本来の値と異なる可能性があります。

(追記) [@parasite2006](https://twitter.com/parasite2006)さんに様々な検査結果から摂取量や蓄積量を推定する方法を紹介していただきました: [habari2011dunia  さんの「放射性物質の体内残留量グラフ」の使い方 - Togetterまとめ](http://togetter.com/li/646851)

### 参考
* IAEA-TECDOC-1009 ["Dosimetric and Medical Aspects of the Radiological Accident in Goiania in 1997"](http://www-pub.iaea.org/MTCD/publications/PDF/te_1009_prn.pdf)
* ICRP Publication 56 ["Age-dependent Doses to Members of the Public from Intake of Radionuclides - Part 1"](http://www.icrp.org/publication.asp?id=ICRP%20Publication%2056)
* Melo et al. ["A Biokinetic Model for 137Cs"](http://journals.lww.com/health-physics/Abstract/1997/08000/A_Biokinetic_Model_for_137Cs.4.aspx)
* 田崎晴明 [『食品中のセシウムによる内部被ばくについて考えるために（放射線と原子力発電所事故についてのできるだけ短くてわかりやすくて正確な解説）』](http://www.gakushuin.ac.jp/~881791/housha/details/CsInBody.html)
* 早野龍五 [『初期セシウム量，一日の摂取量，年齢区分 → 体内セシウム量変化をグラフに』](http://nucl.phys.s.u-tokyo.ac.jp/hayano/radiocesium/)
* 早野龍五 [『放射性セシウムを時々食べる → 体内セシウム量変化をグラフに』](http://nucl.phys.s.u-tokyo.ac.jp/hayano/radiocesium/intermittent.html)
* ICRP ["ICRP Database of Dose Coefficients: Workers and Members of the Public; Ver. 3.0"](http://www.icrp.org/page.asp?id=145)
* 茨城大学有志の会 [『やっかいな放射線と向き合う資料編』](http://yakkaihousyasen.web.fc2.com/)
* Oak Ridge National Laboratory ["Description of the Mathematical Phantom"](http://ordose.ornl.gov/resources/phantom.html)