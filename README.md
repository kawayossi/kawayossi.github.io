
# 吉川　真由(Mayu Yoshikawa)

## Bio
**<span style="font-size: 200%;">2016-2021</span>**  
東京工業高等専門学校　電子工学科  
**<span style="font-size: 200%;">2021-2023</span>**  
東京工業高等専門学校　電気電子工学専攻  
### 研究内容
- 生体工学　筋電や心理物理実験に関する研究に携わりました
- IoT　Raspberry PiやArduinoを使ったデバイス作りに取り組みました

**<span style="font-size: 200%;">2023-</span>**  
東京大学　新領域創成科学研究科　人間環境学専攻　修士課程在籍中
### 研究内容
- 制御工学　Visual odometoryやIMUセンサなどを用いて自己位置推定と地図形成を行う自律移動車いすの開発を行います
- 心理学　ドライビングシミュレータを用いた効果的な運転教育手法について検討を進めています

-----
## Skills

- Python
- OpneCV
- R
- Raspberry Pi
- Arduino
- M5Stack
- Unity
- Blender
- Fusion 360  

-----

## Projects
### 筋電義指<img src="https://raw.githubusercontent.com/kawayossi/kawayossi.github.io/main/pic/AFicon.PNG" width="10%">  
筋電で制御することのできる義手は存在するのですが，義指は存在せず，どのように実装するかが課題となっています．所属していた研究室では，長年ロボットアームを用いて筋電義指についての検証を行っていましたが，より直感的なものが欲しいと考え，Arduinoでサーボモータを用いて制御する筋電義指を制作しました．土台となる手の模型は粘土で作成し，可動部は3Dプリンターで作成しました．人の手に近い見栄えで，筋電入力に対してしっかり動作するため，オープンキャンパスでの研究室公開では特に注目を集めていました．
(動画を入れる予定)

### RO-bot
臨床工学技士からのお話を聞き，課題を解決するために開発を行うハッカソンに参加した際の作品です．RO機器という人工透析に用いる機会の水漏れの発見が遅れ，処置に影響が出てしまうという課題に対して，光センサにより水漏れを検知しSlackbotでお知らせするシステムを提案しました．2日間という限られた時間の中で検知からお知らせのデモまで実装することができました．実装力とシステムの有用性が評価され，最優秀賞を頂くことができました．(生体医工学サマースクール2022)  
<img src="https://raw.githubusercontent.com/kawayossi/kawayossi.github.io/main/pic/RO-botmemo.JPG" width="50%">
(動画を入れる予定)

### 心拍センサ
医療機器ベンチャーでのアルバイトにて，高齢者施設で瞑想中に，コーチが受講者の心拍を一目で確認できるような心拍計が欲しいという要望の下制作しました．M5Stack Atom Matrixを用いて，使用者の心拍と同じタイミングでLEDのハートが脈動します．その後展示会向けに面白い機能が欲しいとのことで，脈波形から血管年齢を，心拍の揺らぎからストレス度合いを算出する機能を追加しました．簡単に測定でき，結果もすぐに確認できるため展示会でも好評でした．(CEATEC 2022，八王子ものづくりEXPO2022)
<img src="https://raw.githubusercontent.com/kawayossi/kawayossi.github.io/main/pic/HR_expo.JPG" width="40%">
## Research

### 三次元環境デバイスの開発
UWB(Ultra Wide Band)による測位システムを用いた新たなプロダクトの提案に取り組みました．UWBでは高精度の測位が可能となっているため，屋内での温度や照度といった環境要素の分布が測定できるのではないかと考え，環境センサとUWB測位システムを組み合わせた三次元環境測定デバイスを試作しました．得られたデータの可視化にも工夫し，Unityを用いたリアルタイムプロット機能を実装しました．オフィスや工場など，様々な実地測定を行い，測定結果は施設の使用者にフィードバックしました．<a href="https://www.facebook.com/locationmind/posts/pfbid02Vib8nXTKZH3FWx8B32V1386iuXhU4qtHMk85UwnZWqUy2gsPuG4P9UnqQzYPioBel">外部リンク</a>  
<a href="/pic/UWB_poster.pdf"><img src="https://raw.githubusercontent.com/kawayossi/kawayossi.github.io/main/pic/UWB_poster.jpg" width="10%"></a>  
画像クリックでpdfが開きます
(動画を入れる予定)

### ヒトの視覚機能について
豊橋技科大の研究室との共同研究で，視覚機能について解明するためにヒトの心理物理実験を行いました．人の視覚機能において輝度コントラスト感度は日内変動するのではないかという仮説のもと実験を進め，結果としては朝よりも夜の方が視力が良くなるという驚くべき結果が得られました．データ解析のためのPython，統計検定のためのR言語の習得，実験に用いたディスプレイの色校正，ヒトの目と光や色の関わりなど，多くのことを学ぶことができました．  
<a href="https://www.eiiris.tut.ac.jp/blog/research-activities/research-publication/230317-paper/">外部リンク</a>
<a href="/pic/Contrast_poster.pdf"><img src="https://raw.githubusercontent.com/kawayossi/kawayossi.github.io/main/pic/Contrast_poster.jpg" width="10%"></a>  
画像クリックでpdfが開きます

### 競技中の怪我防止システムの提案
体育教員から，指導の際に筋肉の使用バランスについて手軽にフィードバックできるようなモノが欲しいという要望を受け制作しました．モーションキャプチャよりも手軽に動作を取得したいとのことで，カメラ1台で骨格検出が可能なMediapipeと筋電センサを組み合わせ，怪我防止に効果的なフィードバックシステムについて検討しました．Raspberry Piで試作機を作ったところ，体育教員からは手軽で表示がわかりやすく画期的と喜んでもらえました．  
<a href="/pic/EMG_poster.pdf"><img src="https://raw.githubusercontent.com/kawayossi/kawayossi.github.io/main/pic/EMG_poster.jpg" width="10%"></a>  
画像クリックでpdfが開きます

## Awords
- 先進的技術シンポジウム2020　優秀ポスター賞<a href="https://www.kousen.tut.ac.jp/research/project/past_report/r02_report">外部リンク</a>
- 日本生体医工学会サマースクール2022　最優秀賞<a href="https://sites.google.com/view/bh2022jsmbeorg/">外部リンク</a>

## Papers
- IEEE Sensors Jounal　"Indoor spatial-environment measurement using ultra-wideband positioning system"<a href="https://ieeexplore.ieee.org/abstract/document/9967251">外部リンク</a>
- 日本生体医工学会誌　"概日リズムによる輝度コントラスト感度特性の変化"<a href="https://www.jstage.jst.go.jp/article/jsmbe/60/6/60_158/_article/-char/ja/">外部リンク</a>




