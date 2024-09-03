# じゃね制作のKANGEKI譜面置き場

[KANGEKI](https://www.kangeki.org/start)という音楽ゲーム用の譜面ファイルです。  
鍵盤発狂譜面しかありません。

### ダウンロード

Codeと書かれたボタンをクリックし、Download ZIPを押してください。

## 導入方法

基本的には公式の[wiki](https://www.kangeki.org/select/music)を参照ください。  
ここで配布しているのは譜面ファイルのみです。  
楽曲データは以下の手順で生成していただく必要があります。

### 楽曲データの生成手順

 1. 譜面に対応したBMSファイルを用意します。入手先は[BMS Links](#BMS-Links)を参照。  
 2. BMSファイル(.bms .bmeなど)から[BMX2WAV](https://childs.squares.net/program/bmx2wav/)でWAVファイルを生成します。  
 複数の譜面がある場合、どれを対象に生成しても問題ないはずです。

※リンク先などから直接楽曲データをダウンロードできる場合でも、  
　BMS音源と構成や尺が異なる場合が考えられます。  
　そのためBMSから生成したものを使用いただくのを推奨します。

### Audio Offsetに関して

作者の感覚でそれっぽい値を設定していますが、  
作者自身まだKANGEKIの判定を掴みきれていないので怪しいです。  
違和感を感じたらeditモードから調整してください。  
また、私の環境でBMX2WAVの設定は  
・先頭の無音部分を除去する→チェック  
・先頭に無音を挿入する→チェック  
・挿入する時間(秒)→0.7  
で楽曲データを生成しています。(これらの値はすべてデフォルトです)

## 難易度について

現在、♫1～♫6までの譜面を公開中です。  
ただし、KANGEKIで「♫」が表示できないっぽいので  
譜面ファイルは「♫」を除いた数字のみで定義しています。  
値が大きくなると、難しくなります。  
作者の独断で決定しているので参考程度です。

♫1～♫2ぐらいまでは、14+や15ができれば理不尽な配置はないと思います。  
え、14+とか15って何の数字かって…？  
いや、おぼろげながら浮かんできたんです　14+や15という数字が。それだけです。  
とはいえ、EXやノーツ数稼ぎのロングとかはないので、  
同程度のスコアが出るかは別問題かと思います。  
♫3ぐらいから未知の領域になっていくかもしれません。

## 譜面一覧

| 曲名(曲情報は[BMS Links](#BMS-Links)を参照) | 難易度 | ひとこと |
|--|--|--|
| After Burner | INSANE ♫3 | グリッサンド配置好きです |
| cold planet | INSANE ♫2 | 難しい要素はないのにスコアが出ない。難易度付けが難しい。 |
| Mario Paint (Time Regression Mix) | INSANE ♫2 | レーンがうねうねするのはフリックの予告です |
| How to make 音ゲ～曲! | INSANE ♫4 | 動画のものから一番修正した譜面 |
| Overjoy ★ OVERDOSE!! | INSANE ♫3 | あの配置は　おぼろげながら　浮かんできたんです |
| Papyrus | INSANE ♫1 |  |
| Psalms ～魂の還るばしょ～ | INSANE ♫6 | 正規は二回目のプレイですでに呪われていたので乱常備でやってます |
| 桜華月 | INSANE ♫1 | ONTROLLERを買って、つまりレバーが実装されて、一番最初に作った譜面 |
| Wizdomiot | INSANE ♫2 | 自分で遊ぶために初めて作った譜面。せっかくなのでレバー操作不要のままいじらず。 |
| 俗物フェスティバル | INSANE ♫4 | ♫5でもいいような気がする |


## BMS Links

Artistは敬称略とさせていただきます。

- After Burner (フォルダ：AfterBurner)  
  - Artist: ねこかぶりサイクロン(xi+ねこみりん) feat.えみゅう。
  - Genre: BRAVE
  - URL: https://www.nekomirin.com/music.htm
- cold planet(フォルダ：coldplanet)  
  - Artist: knot
  - Genre: Techno
  - URL: http://web.archive.org/web/20110625181433/http://www.geocities.jp/panda_bms/cold_planet.zip
- Mario Paint (Time Regression Mix)(フォルダ：MarioPaint)  
  - Artist: ueotan
  - Genre: GAMEMUSIC
  - URL: https://dropbox.bms.ms/u/13536802/MarioPaint.zip
- How to make 音ゲ～曲!(フォルダ：OtogeMusic)  
  - Artist: F Rabbeat
  - Genre: OTOGE MUSIC
  - URL: https://manbow.nothing.sh/event/event.cgi?action=More_def&num=89&event=142
- Overjoy ★ OVERDOSE!!(フォルダ：OverjoyOverdoze)  
  - Artist: Luna Fozer
  - Genre: Theme of Luna Fozer ch.
  - URL: https://manbow.nothing.sh/event/event.cgi?action=More_def&num=494&event=142
- Papyrus(フォルダ：Papyrus)  
  - Atrist: papyrus
  - Genre: Grand Finale
  - URL: https://manbow.nothing.sh/event/event.cgi?action=More_def&num=193&event=60
- Psalms ～魂の還るばしょ～(フォルダ：Psalms)  
  - Artist: qfeileadh&レゾナンスもえこ
  - Genre: Requiem
  - URL: https://manbow.nothing.sh/event/event.cgi?action=More_def&event=133&num=128
- 桜華月(フォルダ：SakuraKagetsu)  
  - Artist: AKITO
  - Genre: JP-SPIRITUAL POP
  - URL: https://web.archive.org/web/20050915121030/http://page.freett.com/akito11/bms.html
- Wizdomiot(フォルダ：Wizdomiot)  
  - Artist: LeaF
  - Genre: RATIONAL PUNISHMENT
  - URL: http://leafbms.web.fc2.com/song.html
- 俗物フェスティバル(フォルダ：Zokubutsu)  
  - Artist: Micelle feat.Yshida
  - Genre: Self-introduction
  - URL: https://manbow.nothing.sh/event/event.cgi?action=More_def&num=4&event=137

## TIPS
- ジャケット画像などのファイル名は基本的に任意らしいが、アンダーバーで始まると認識されないようだ
- 低BPMの曲でハイスピを設定上限にしてもなお緑数字が大きいときは、エディタで譜面ファイルを開いて冒頭にSCROLL SPEED定義を入れると良いかもしれない
