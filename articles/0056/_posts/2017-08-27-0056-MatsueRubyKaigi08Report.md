---
layout: post
title: RegionalRubyKaigi レポート (61) 松江 Ruby 会議 08
short_title: RegionalRubyKaigi レポート (61) 松江 Ruby 会議 08
created_on: 2017-08-27
tags: 0056 MatsueRubyKaigi08Report regionalRubyKaigi
---
{% include base.html %}


## RegionalRubyKaigi レポート 松江 Ruby 会議 08

### はじめに

2016年12月17日（土）に松江Ruby会議08が開催されました。今年は合計91名の方々に参加いただきました。

* 日時：2016年12月17日（土）11:00〜17:40（懇親会: 18:00〜）
* 場所：松江テルサ４Ｆ大会議室
* 主催：Matsue.rb（まつえるびー）
* 後援：日本Rubyの会
* 動画による中継(Youtube)：[https://www.youtube.com/playlist?list=PLbJxhePIoIPBU5f0cAn4BceCG48EGSHsA](https://www.youtube.com/playlist?list=PLbJxhePIoIPBU5f0cAn4BceCG48EGSHsA)
* Togetterまとめ： [https://togetter.com/li/1061092](https://togetter.com/li/1061092)
* 公式タグ・Twitter：[#matrk08](https://twitter.com/hashtag/matrk08)

![07_all.jpg]({{base}}{{site.baseurl}}/images/0056-MatsueRubyKaigi08Report/07_all.jpg)

### 許可を得る前にプルリクしよう (ゲスト講演)

* 発表者
  * 越川直人氏([@ppworks](https://twitter.com/ppworks))
* 資料
  * [https://speakerdeck.com/ppworks/matrk08](https://speakerdeck.com/ppworks/matrk08)

![01_guest01_koshikawa.jpg]({{base}}{{site.baseurl}}/images/0056-MatsueRubyKaigi08Report/01_guest01_koshikawa.jpg)

「許可を得る前にプルリクしよう」と題して、株式会社マネーフォワードの Rails エンジニアである越川氏([@ppworks](https://twitter.com/ppworks))に講演をいただきました。
越川氏は初めての来松ということで、貴重なお話を持って松江に来ていただいたことに感謝です。

#### マネーフォワードについて

マネーフォワードといえば、家計簿アプリや会計ソフトを開発・運営している会社というイメージが真っ先に思い浮かびますが、エンジニア目線で見てどんな会社なのかを紹介していただきました。
マネーフォワードではエンジニアドリブンの考え方を取り入れており、各プロジェクトのリーダーはエンジニアが勤めているそうです。
26歳という若さでプロダクトオーナーを務めるメンバーもいるとのことで同い年の筆者としては驚いています。

#### ワークOSSバランス

マネーフォワードではにフルタイムRubyコミッタとして働くメンバーがいます。
ほぼ、プロダクトの開発には関わらず、純粋にRubyの開発を専属で仕事としているとのことでした。これはRubyをはじめとしたOSSはプロダクトの開発には欠かせないものであり、その元となるOSS開発へ貢献することで結局は地続きで、プロダクトに繋がっているという考え方からということです。
仕事とOSS開発を切り離して考えるのではなく、OSS開発そのものも仕事につながっていると考え、実際にOSSのメンテナンスを行いながら仕事を行う「ワークOSSバランス」というワードを発信していただきました。

#### 許可を得る前にプルリク

「許可を求めるな謝罪せよ」という有名なワードがありますが、越川氏本人がもじった「許可を求めるな Pull Request せよ」というワードが今回の
講演でのタイトルとなっていました。「許可を求めるな謝罪せよ」の意味としては許可を得るよりもやってみてダメでも謝る方が簡単だからとにかくやってみようという意味だと解釈しています。
越川氏の今回の講演タイトルに当てはめると、とにかく動くものを作ってみてそれを提案すればいい。許可を求める前にとにかく作れ。ということになるでしょうか。この考えはマネーフォワードのエンジンドリブン＝とにかく自分が主体になってリーダーシップをとるという考えに通じています。

### 意思決定プロセスとPull Request

Pull Request の思想はチームでの意思決定のプロセスの民主化に通じる部分があります。
越川氏が例として示されたチームでの意思決定プロセスは

1. あるひとの意志を案として、提案する
1. 合意形成のための議論を行い、新たな案を取り込む
1. 合意形成され意思決定される


でした。

これがそのままPull Requestの概念である

1. Pull Request を作成して、動くコードで提案する
1. コメントのやりとり、コミットを繰り返す
1. Mergeして取り込まれる


という流れにそっくりそのまま対応するということを教えていただきました。
ここから、「何かを変えようと思えば変えられる手段を、Githubのおかげでプレイヤー全員が手にすることができる」ということを学ぶことができました。

#### CHANGEの提案

何かを変えようと思うときは、誰かがやってくれるのを待つのではなく、とにかく自分が起点となることが大切だとおっしゃっていました。
自分が変わる→自分が変える→周りが変わるという流れを作るためには自分がリーダーシップをとる必要がある。
自分が変わるきっかけとして「アドラー心理学」が非常に参考になるということでした。
心理学と聞くと小難しそうな気がしていましたが、今一度学ぼうと思えるきっかけにを作ることができました。
自分が人生の主人公になるために、どうすれば建設的な判断ができるかどうかを日々考えることが重要だと越川氏は最後におっしゃっていました。

#### さいごに

越川氏の講演には、なにかをするときは誰かがやってくれるのを待つのではなく、どんどん自分発信で自分が主役になろうという想いが込められていました。
もちろんその考えは、越川氏が所属するマネーフォワードのエンジニアドリブンに通づるものがあります。
これからは筆者もそうですが、「許可を得る前にプルリク」を実践していきたいと考えさせられました。

### 昼休憩 (LT)

お昼ごはんを食べながら、きむらしのぶ氏([@mix_dvd](https://github.com/mix_dvd))の司会で以下の5件のLTの発表が行われました。

* 僕とRubyコミュニティ
  * 発表者
    * むらじゅん氏([@murajun1978](https://twitter.com/murajun1978))
  * 資料
    * [https://murajun1978.github.io/slides/matsue_rubykaigi08/slides/](https://murajun1978.github.io/slides/matsue_rubykaigi08/slides/)
* 2006-2016 Ruby, OSS, Thinreports
  * 発表者
    * 日高 克也氏([@hidakatsuya](https://twitter.com/hidakatsuya))
  * 資料
    * [https://speakerdeck.com/hidakatsuya/matsue-rubykaigi08-lt](https://speakerdeck.com/hidakatsuya/matsue-rubykaigi08-lt)
* 俺とMatsue.rb
  * 発表者
    * 橋本 将氏([@sho_hashimoto](https://twitter.com/sho_hashimoto))
* スプラウト.rbとRails Girls Matsue 3rd
  * 発表者
    * 松岡 香里氏


### The Power of Storytelling (基調講演)

* 発表者
  * まつもとゆきひろ氏([@yukihiro_matz](https://twitter.com/yukihiro_matz))

![02_keynote_matz.jpg]({{base}}{{site.baseurl}}/images/0056-MatsueRubyKaigi08Report/02_keynote_matz.jpg)

連日の講演で体調が悪い中、今回も松江Ruby会議でご講演いただきありがとうございます！
愛犬が散歩中に引かれたようでしたが無事退院できたそうで安心しました。

今回のご講演ではいくつかの物語とプログラマーを掛け合わせて、様々な教訓や物語を語る大事さについて、お話をしていただきました。
その中でストーリーの概要と物語からみる教訓についてご紹介したいと思います。

#### 物語

##### 石のスープ

達人プログラマーの中でも紹介されたお話ですが、まつもと氏は本を持参され、朗読されました。

> 戦争が終わってお腹を空かせた兵士が村を見つけたが、村人に食材をわけてもらえなかった。
> そこで兵士は鍋にお湯をわかし石を入れたところ、村人が興味を示し始め、それをきっかけとして兵士の指示の元、村人が様々食材を提供してくれた。


この物語の中での教訓は、石をなべに入れたことで人が集まる「触媒」となり、最初の一歩を踏み出すことによりおいしいスープを作ることができた。
この教訓はオープンソースのRubyとも照らし合わせて、話をされました。
1995年にインターネットへ最初のRubyを公開し、20年以上の時間をかけて多くの人に改善をかけてもらったことによって、基本的な方向性はさほど変わっていないが、はるかによいものとして今のRubyがあるそうです。
Rubyという触媒を受けてここまでの人が集まり、各々でのRuby会議開催を続けてこられたことも、ひとつの物語かもしれないですね。

##### ゆでガエル

２つ目のお話としてゆでガエルをあげられました。

> ゆでガエルは、大きな鍋の中にお湯を沸かしておいて、そこにカエルを放り込むと、暑いのでびっくりして飛び出す。
> 水の中にカエルを入れてだんだんと温めていると、暖かいなぁと思っているうちにゆであがってしまう。


この教訓として、人間は少しずつの変化に弱いようです。
あるとき急に大変なことが起こるとがんばるが、状況が次第に悪くなるとタイミングを逃して手遅れになります。
現実の話として地球温暖化を併せてお話されましたが、普段の仕事の中でもいろいろと応用できるお話だと思います。

##### わらしべ長者

わらしべとはつまらないものを指すが、夢から覚めて最初に掴んだわらから始まり、わら、あぶ、みかん、反物、馬と変えていき、最後には長者の屋敷と取引して終わるお話です。

教訓として、価値の評価軸は一次元ではなく、簡単に入手できるものから価値を得ることができるそうです。

* 反物になった話
  * 普段なんでもないときに公平な取引だとみかんと反物は価値的に割に合わないが、ただ死にそうなときのみかんは価値が異常に高い。
* 馬になった話
  * 最初馬を取引したときは死にそうだったが、手をれることで価値があがった
* 屋敷になった話
  * そんな都合のよい取引はない


最後は冗談交じりでお話されましたが、ひとつの物語でもいろいろな教訓が得られることを実感できました。

#### 物語の力

これらの物語と教訓を一通りお話された後、実際のプログラマーの現場として、物語を語ることの重要性をお話されました。
プログラマーとして設計書を作ったりプログラムを書く中で物語を語ることにより、物事を見たときにいろいろと考えたり、身近に感じれるそうです。
身近に感じることにより、印象に残り忘れないため、その物語がもたらす教訓を何度も振り返れることができ、最終的に身に付けることができるかもしれないようです。

#### さいごに

最後にまつもと氏は、プログラマーとしてありたい自分の反面、ストーリーテラーとしての自分を語られておられました。
年間で数多くの講演をする中で、何かを作るときに物語を込める必要があることを感じたそうです。
プログラムを作る上で設計者、デザイナー、プロダクトオーナー、そしてストーリーテラーと様々な立場の観点から物語のお話を聞くことができました。
実際に仕事の現場で物語の語り部となり、語り続けていくことの重要性を考えさせられる講演となりました。
紙面の都合上すべてをお伝えすることが難しいですが「みなさんによい語り部になってもらえたらと思う」と最後にまつもと氏は物語を語られておられました。

### My Favorite Tools (ゲスト講演)

* 発表者
  * 松田明氏([@a_matsuda](https://twitter.com/a_matsuda))
* 資料
  * [https://speakerdeck.com/a_matsuda/my-favorite-tools](https://speakerdeck.com/a_matsuda/my-favorite-tools)

![03_guest02_amatsuda.jpg]({{base}}{{site.baseurl}}/images/0056-MatsueRubyKaigi08Report/03_guest02_amatsuda.jpg)

株式会社マネーフォワードの松田明氏にご講演いただきました。
「My Favorite Tool」と題して、松田明氏の開発環境の紹介・その他開発に使用するツールについてご紹介いただきました。
会場もご講演の内容を熱心に聞いている様子でした。
以下のツールについてご紹介いただきました。

### [md2key](https://github.com/k0kubun/md2key)

Markdown記法のテキストからKeynoteへ変換してくれるコマンドラインツールで、プレゼン資料を作成する時に使われており、md2keyのソースコードへのコミットも良くされているとのことでした。
松田明氏がどのようにmd2keyを使われているかもご紹介いただき、発表前日の移動時間などの空き時間を使用してiPhoneのNotesで発表で話したいことを箇条書きでまとめておき、発表日にmd2keyで変換してプレゼン資料を仕上げているとのことでした。

### [gem-src](https://github.com/amatsuda/gem-src)

gem install、bundle installをフックして、インストールされたgemのメタデータからソースコードのリポジトリを探してきてgit cloneしてくれるrbenvプラグイン。
松田明氏が使用しているプロダクトにバグを見つけた時に、直ぐにパッチを書いて対処したいので、ソースコードは全て手元に置いておきたいので使用しているとのことでした。
手元にダウンロードしたgemパッケージから検索すれば、使用しているgemのソースコード中からのみ検索することができるとのことでした。

### [gem-repositorizer](https://github.com/amatsuda/gem-repositorizer)

gem installされた時点でバージョン管理を始めておくためのgem plugin。
開発中にbundleしているgemをデバッグする時に、gem側のソースコードを書き換えることがあるが、バージョン管理していないと書き換えた内容が分からなくなってしまうので作成された個人用のツールとのことでした。

### git-*

gitのサブコマンドで自分用に設定されていることについてご紹介いただきました。
git aliasでgit addのaddを「ad」や「a」にされていることや、gitのサブコマンドをrebase、cherry-pick、commitのようなコマンドにされているとのことでした。

特にcommitコマンドについてご紹介いただき、たとえばコマンドライン上にコマンドがある時に「commit &lt;コマンド&gt;」のような形式で使用して、コミットメッセージをダブルクォートで囲む作業を減らしていることができるとのことでした。
また、コミットに関する話で、コードを生成するコマンドを実行した場合、履歴を読む時に生成したコートと区別が付くようにそのままコミットするのが望ましいとのことでした。

### [action_args](https://github.com/asakusarb/action_args)

Rails 3でマージされたMerbプロジェクトで使用されていた機能のgemパッケージ。
action_argsを使用すればコントローラのアクションを、Rubyのメソッドらしく書くことができ、既存のRails式のコードもそのまま動作するので、bundleしておくことをお勧めするとのことでした。
action_argsに関する話で、Railsに取り込みたいと松田明氏がDHHに提案した時の話や、内部実装に関する話をしていただきました。

### [database_rewinder](https://github.com/amatsuda/database_rewinder)

database_cleanerというgemパッケージのオルタナティブ。
松田明氏のご講演の中では、Rails標準のtransactional_testの動きや、database_cleanerとdatabase_rewinderの違いについてお話いただきました。

### [test-unit](https://github.com/test-unit/test-unit)

松田明氏はテストはtest-unitを使用されているとのことでした。
test-unitの2つの機能についてお話していただきました。

* power_assert
* sub_test_case
  * RSpecのdescribeやcontextみたいに階層構造を持ったテストケースが書ける。


### [rfd](https://github.com/amatsuda/rfd)

Rubyで書かれたファイラ。実装についてお話いただきました。
rfdは押されたキーの名前をsendして、対応する名前のメソッドを呼び出して、メソッドに定義された処理が実行されるという実装になっており、プラグインが書きやすいとのことでした。

### まとめ

松田明氏にご紹介いただいたツールは、インターネット上に公開されているものが多く、ツールを使用していた方からPull Requestをいただき、もっとツールを良くしてくれたことをお話いただきました。
また、プログラマには自分が使う道具を作る権利があり、コードを書く道具を作る楽しみをしないのはもったいないので、皆コードを書きましょうと呼びかけました。
最後に松江Ruby会議08が開催された松江市が[Ruby City MATSUEプロジェクト](http://www1.city.matsue.shimane.jp/jigyousha/sangyou/ruby/)をしていることもあり、yet another Ruby Cityとして東京都の谷根千をご紹介いただきました。

### プログラミングコンテスト結果発表

* 発表者
  * 吉岡隆行氏 ([@murateku](https://twitter.com/murateku))、西田 雄也氏 ([@nishidayuya](https://twitter.com/nishidayuya))と受賞者の皆さん、スポンサーの皆さん

![04_procon.jpg]({{base}}{{site.baseurl}}/images/0056-MatsueRubyKaigi08Report/04_procon.jpg)

前回の松江 Ruby 会議 07 では paiza さんとの協賛でオンラインでのプログラミングコンテストが行われました。[昨年度](https://paiza.jp/poh/joshibato/matsue-ruby)はpaizaさん協賛の形でしたが、今年度はスタッフで集まって実行環境を開発してみました。

#### 内容

標準入力で与えられる迷路(以下など)を解く時間(同じならば次にプログラムサイズ)を競う内容でした。なお、迷路は全部で5つあり、そのサイズは問題によって異なります。

{% highlight text %}
{% raw %}
#################
S #     #       #
# # ##### ##### #
#       # #   # #
# ### # # ### # #
# #   # # #   # #
# ##### # # # # #
#     # #   # # #
##### # ##### ###
# #   #     #   #
# # ##### # ### #
# # #   # # #   #
# # # # ### # ###
# #   #   #   # #
# # ##### # ### #
#   #     #     G
#################
{% endraw %}
{% endhighlight %}


#### 受賞者の皆さんと投稿プログラム

松江Ruby会議08での受賞者の皆さんのコードは以下のようなものでした。2位の方までですが簡単にご紹介します。

##### 一般部門

###### shugo氏(1位: 165バイト)

{% highlight text %}
{% raw %}
m=$<.read;v=m.tr($/,?#).unpack"C*";g=/G/=~m;q=[s=/S/=~m];while(i=q.pop)!=g;v[i]=35;[1,-1,s,-s].each{|d|v[j=i+d]!=35&&q<<j&&$:[j]=i}end;m[i]=?:while(i=$:[i])!=s;$><<m
{% endraw %}
{% endhighlight %}


詳しい解説は[こちら](https://shugo.net/jit/20161217.html#p01)にてshugoさんご自身にしていただいています。ダイクストラ法で解かれたようですが、A*法も試された上で更にこのプログラムサイズにまでなっている点がすごいですね。

しかし、出題者としてはもう少し大きい迷路しておけばよかったと思ってしまいました。

###### nari3氏(2位: 658バイト)

{% highlight text %}
{% raw %}
M=$<.read.lines.map(&:chomp)
N=M.size+5
MX=N*N
A=Array
S=A.new(N){A.new(N,-1)}
K=[]
D=[[1,0],[-1,0],[0,1],[0,-1]]

M.each_with_index{|l,y|
  l.chars.each_with_index{|c,x|
 case c
 when ' '
   S[y][x]=MX
 when 'S'
   @s=[x,y,MX]
 when 'G'
   @g=[x,y,1]
 end
}}
K<<@g
while K[0]
  px,py,st = K.pop
  D.each{|dx,dy|
 x=px+dx;y=py+dy
 if S[y][x] > st
   S[y][x]=st
   K<<[x,y,st+1]
 end
  }
end
w=@s
while w
  px,py,st=w
  n=D.map{|dx, dy|
 x=px+dx;y=py+dy
 [x,y,S[y][x]]
  }.select{|s| s[2] > 0 && s[2] < st }.min_by{|s| s[2] }
  M[n[1]][n[0]] = ':' if n
  w = n
end

puts(M)
{% endraw %}
{% endhighlight %}


全ての経路を試すタイプの解き方のようです。ゴールに到達できる経路が2つ(ただし、最短を選択する必要があるので正解は1つ)ある問題で困る可能性があるのですが、無事回避されてしまったようです。

##### 学生部門

###### momiji氏(1位: 269バイト)

{% highlight text %}
{% raw %}
a=STDIN.each_line.map(&:chomp);w=a.size;$b=Array.new;$f=Array.new;def e(n);if$b[n]==nil&&$m[n]==' ';$f.push(n);$b[n]=$c;end;end;$m=a.join;c=$m.index('S');while $m[c+1]!='G';$c=c;e(c+1);e(c+w);e(c-w);e(c-1);c=$f.pop;end;while$m[c]!='S';a[c/w][c%w]=':';c=$b[c];end;puts a
{% endraw %}
{% endhighlight %}


nari3氏と方針としては同じでしたが表現の仕方が違いました。1経路分のデータを配列などではなく文字列にして管理してるのが面白いですね。

###### ミュミャリャツァオビュビュンピピュプリャプピフンドシン氏(2位: 1152バイト)

{% highlight text %}
{% raw %}
maze_ary = STDIN.each_line.map(&:chomp);class Maze;def initialize(inp);@wi = inp[0].length - 1;@he = inp.length;@ma = [];inp.each do |input|;li = [];input.split("").each do |c|;next if c == "\n";@start = {:x => li.length, :y => @ma.length } if c == "S";@goal  = {:x => li.length, :y => @ma.length } if c == "G";c == " " ? li.push(@wi * @he) : li.push(c);end;@ma.push(li);end;end;def tok;his = [];ido(@start[:x], @start[:y], his);@ans.each do |hi|;next if ["S", "G"].include?(@ma[hi[:y]][hi[:x]]);@ma[hi[:y]][hi[:x]] = ":";end;end;def ido(x, y, his);his.push({:x => x, :y => y});return if @ma[y][x] == "#";return if @ma[y][x] == "S" && his.length > 1;if @ma[y][x] == "G" then;if @ans == nil || history.length < @ans.length then;@ans = his.clone;end;return;end;if @ma[y][x].kind_of?(Numeric) then;return if @ma[y][x] <= his.length;@ma[y][x] = his.length;end;ido(x - 1, y, his);his.pop;ido(x + 1, y, his);his.pop;ido(x, y - 1, his);his.pop;ido(x, y + 1, his);his.pop;end;def to_s;str = "";str << @ma.map do |line|;line.map do |c|;c.kind_of?(Numeric) ? " " : c;end.join("");end.join("\n");end;end;maze_ary = Maze.new(maze_ary);maze_ary.tok;puts(maze_ary)
{% endraw %}
{% endhighlight %}


nari3氏と方針としては同じでしたが表現の仕方が違いました。再起のある/なしやデータの持ち方で三者三様のコードになっているのが面白いですね。なお、投稿時は入賞するとは思っていなかったそうで、名前も面白い事になっています。

##### その他

上記以外で挑戦いただいてご自身の解答を公開されてる方々です。simanさんの記事は力作ですので是非どうぞ。yharaさんのプログラムはそれ自身も迷路になっており流石というほかありませんでした。

* [simanさん](http://qiita.com/siman/items/11444f7c0720e994dd01)
* [yharaさん](https://twitter.com/yhara/status/810155346954190848)


#### 実行環境

松江Ruby会議08後しばらくして以下にて今回の実行環境を公開しています。迷路を解くという問題に限った内容ですが、よかったら試してみてください。

* [https://github.com/matsuerb/maze_solver_collector](https://github.com/matsuerb/maze_solver_collector)


### mrubyで携帯回線IoTデバイスを作ってみた (ライブコーディング)

* 発表者
  * 佐藤氏

![05_livecoding_sato.jpg]({{base}}{{site.baseurl}}/images/0056-MatsueRubyKaigi08Report/05_livecoding_sato.jpg)

島根大学ものづくり部 Pimの佐藤氏に「mruby/cで携帯回線のIoTデバイスを作ってみた」と題してライブコーディングをしていただきました。
ライブコーディングは、会場に佐藤氏が持ってきたLEDライトやイルミネーションで飾り付けられたクリスマスツリーを時間内にmruby/cでプログラミングして光らせるという内容でした。
マイコンボードとしてWakayama.rbの山本氏が作成されたGR-CITRUSを使用しているとのことでした。

* [GR-CITRUS](http://gadget.renesas.com/ja/product/citrus.html)


他にも以下のサービスを使用して、LEDを光らせているとのことでした。

* [LINE API](https://developers.line.me/)
* [AWS Lambda](https://aws.amazon.com/jp/lambda/)
* [さくらインターネットが提供するIoTプラットフォームサービス、sakura.io](https://sakura.io/)


まず佐藤氏は、LEDライトを10回点滅させるところから書き始めました。　
直ぐに書き終えてLEDライトが点滅すると、会場からは拍手が起こりました。
次に携帯デバイスからオンにする命令をすることで、クリスマスツリーに飾り付けられたイルミネーションを光らせることができるようにライブコーディングを行い、会場を盛り上げました。

### Ruby Quiz

* 発表者
  * 本多展幸氏([@nobyuki](https://twitter.com/nobyuki))と矢田文香氏
* 資料
  * [https://github.com/matsuerb/matrk/blob/master/08/ruby-quiz.md](https://github.com/matsuerb/matrk/blob/master/08/ruby-quiz.md)

![06_rubyquiz.jpg]({{base}}{{site.baseurl}}/images/0056-MatsueRubyKaigi08Report/06_rubyquiz.jpg)

来場者全員参加型のクイズ大会を行いました。

5問の選択形式のクイズに挙手で解答し、正解者が勝ち残っていく形式のものを2回実施しました。
1回目と2回目でそれぞれ、最後まで勝ち残った2名の方には、スポンサー企業からご提供いただいた賞品がプレゼントされました。（5問終了時点で2名よりも多かった場合はじゃんけんで決着）
1回目と2回目のどちらも、5問が終了した時点で3名ほどに絞り込まれ、なかなか白熱した大会となりました。

5問のうち、前半の2問はRubyに関連する事柄の知識を問う問題（思考時間:10秒）で、後半の3問は提示されたRubyプログラムの実行結果を問う問題（思考時間:60秒）でした。
後者の問題の一例は以下になります。

{% highlight text %}
{% raw %}
Q. 下記のコードの実行結果は？

result = Integer("012") + "012".to_i
p result

(1) 20
(2) 22
(3) 24
{% endraw %}
{% endhighlight %}


上記問題の解答やその他の問題と解答は上記の資料に記載してありますので、興味がわいた方は、ぜひ覗いてみてください。

## 謝辞

### スタッフTシャツスポンサーをしていただきました、株式会社 spice life様

前回に引き続き、スタッフTシャツをご提供いただきました。一枚から発注が可能だそうです。イベントに、プライベートに、ぜひご利用ください。

[株式会社spice life](http://spicelife.jp/index.html) [TMIX](http://tmix.jp/)

### プログラミングコンテストでサーバをご提供いただきました、株式会社イーストバック様

[株式会社イーストバック](http://www.eastback.co.jp/)

### その他、ご協力いただいた企業様

[株式会社 ティーエム21](http://www.tm-21.co.jp/), [株式会社ネットワーク応用通信研究所](http://www.netlab.jp/), [フェンリル株式会社](http://www.fenrir-inc.com/), [株式会社Misoca](https://www.misoca.jp), [株式会社島根情報処理センター](http://www.sjc-inc.co.jp), [ファーエンドテクノロジー株式会社](https://www.farend.co.jp), [株式会社八雲ソフトウェア](http://8clouds.co.jp/), [株式会社日本ハイソフト](http://www.jhsc.co.jp/)

## 著者について

### 西田 雄也 ([@nishidayuya](https://twitter.com/nishidayuya))

プログラマ。
Redmineは職場ではもちろん、結婚式のタスク管理以降、家族でも使っている。
2014-12に [redmine_text_format_converter](https://github.com/nishidayuya/redmine_text_format_converter) というプラグインを開発し、Redmineの書式をTextileからMarkdownに変換して管理下の全てのプロジェクトをMarkdownへ移行させました。

### 佐田 明弘 ([@sada4](https://twitter.com/sada4))

Matsue.rbにひっそりといるプログラマ。

### 井上 裕之 ([@ino_h](https://twitter.com/ino_h))

Rubyといろんなものをまぜるが好き。

### 本多 展幸 ([@nobyuki](https://twitter.com/nobyuki))

プログラミング教育おじさん。

### 木村 友哉([@tomo-k](https://github.com/tomo-k))

Apple 信者な Rubyist。

### 橋本 将 ([@sho_hashimoto](https://twitter.com/sho_hashimoto))

Matsue.rb の雑用係。[定例会](http://matsue.rubyist.net/about_us/#matsuerb)にはだいたい出席してます。


