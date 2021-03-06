>本文由「@玄学翻译社」企划制作！
>企划：宋雅文、杨雍；翻译：满月、王蛇无毒、Thest、一个兔角鹿、风语时；校对：刘嘉俊、太昊。

![游戏里的那些大咪咪（以及关于大咪咪的错误）](http://img.tairan.com/2016-12-29-s6olhbsxp6j99garwxce.gif)

Duang~~ Duang~~ Duang~~

历年来，许多游戏试图去模拟胸部的摇晃。乃至一个专门的名词的产生「胸部物理」（俗称“乳摇系统”，下文统称“乳摇系统”）。

若你玩过有乳摇系统的游戏，可能会发现很少有游戏中的胸部动起来和现实里一样，是受重力影响的一团脂肪。游戏中这些胸部一般都像是有自我意志的氢气球。

某些游戏对胸部表现太不真实，以至于论者认为这是性别歧视，或者游戏行业物化女性的结果。

我见过人吐槽游戏开发者是否从未接触过真实的胸部。我也见过有人暗示游戏开发者不知道怎么在游戏里去恰当的表现女性特征，以及因为做游戏的女性太少，所以才会有茫茫多奇形怪状的胸部。
*（编者注：游戏人，单身狗，没朋友）*


<!--more-->


我也在想，这些看法有道理吗？很多人对为什么乳摇系统糟糕提出疑问，却少见讲述胸部创造过程的干货。搜索一番之后，我发现了[很多](http://forum.unity3d.com/threads/bouncy-breast-physics-nsfw.105842/)[业余](http://answers.unity3d.com/questions/371578/suggestions-for-breast-physics.html) [开发者](http://blenderartists.org/forum/showthread.php?192897-How-to-apply-bounce-to-breast-bones-in-female-model) 似乎[真的](http://forum.unity3d.com/threads/technique-to-apply-bouncy-breasts-and-hair-physics.62473/) 不知怎样在游戏中处理乳摇系统。各种论坛里竟有不少帖子和教程讨论如何实现优秀的乳摇系统。有人做出了四个章节的幻灯片，名为“[Unity中的乳摇之道](http://www.slideshare.net/MatumitFilmSombunjaroen?utm_campaign=profiletracking&utm_medium=sssite&utm_source=ssslideview)”。还有人开发了专门工具供其他开发者使用，从而一起揭开“乳到底怎么摇”的神秘面纱。

而同时，资深游戏开发者们已经在胸部的合理摇动这条路上探寻了将近二十年之久。

### 1996：一切的开始

1996年一款名为「饿狼传说2」的游戏发布。这款游戏被称为是对「街霸2」的"[公然抄袭](http://www.hardcoregaming101.net/fatalfury/fatalfury2.htm)"。「饿狼传说2」 也确实有自己独树一帜的设计点：在玩家生命值极低的时候可以搓动华丽的“超必杀技”来摆脱困境，一举逆转整个局势。

不过讲真，「饿狼传说2」对游戏有一巨大贡献之：史上[第一个](http://www.giantbomb.com/breast-bounce/3015-96/) 胸部会自己摇动的角色。

![游戏里的那些大咪咪（以及关于大咪咪的错误）](http://img.tairan.com/2016-12-29-onyjbey9ab3frgcaqjoc.gif)

（源：[TheInnocentSinful1](http://youtu.be/BO9cT7JRTnY)）

**不知火舞**，这个角色以一对生动活现的胸部而著称。即使现在「饿狼传说」系列已经过气，它仍然给我们留下了宝贵的遗产：让乳摇成为格斗游戏的标配。

**Street Fighter 4**
**街霸4**

![游戏里的那些大咪咪（以及关于大咪咪的错误）](http://img.tairan.com/2016-12-29-e1hv1wrdnewbutf09tnc.gif)

(Source: [*CeruleanNight*](https://www.youtube.com/channel/UCGRLgaqENNL4olJ5-A34IFQ))
（源：[*CeruleanNight*](https://www.youtube.com/channel/UCGRLgaqENNL4olJ5-A34IFQ)）

**Soul Calibur**
**剑魂**

![游戏里的那些大咪咪（以及关于大咪咪的错误）](http://img.tairan.com/2016-12-29-gystvq5xibfzt1fmt9xu.gif)

（源：[*Thegamerwalkthroughs*](https://www.youtube.com/channel/UCb7ElR0N_nIIu_Ojx56TR_A)）

**Skullgirls**
**骷髅女孩**

![游戏里的那些大咪咪（以及关于大咪咪的错误）](http://img.tairan.com/2016-12-29-dtk2ldf97hoyxoma8klc.gif)

（源：[*Poccola_margherita0141*](https://www.youtube.com/channel/UCglDB87yRIO7druwPcyyqSQ)）

当然，这些年来并不是只有格斗游戏搭载了乳摇系统。

**Tomb Raider**
**古墓丽影**

![游戏里的那些大咪咪（以及关于大咪咪的错误）](http://img.tairan.com/2016-12-29-qll1myu7mhgnvudfeeaw.gif)

（源：[*sys2074*](https://www.youtube.com/channel/UCsdeD9hmbNtwqW57JI7DCrg)）

**Resident Evil**
**生化危机** 

![电子游戏的胸是怎么做的（以及它们为什么会出错）](http://img.tairan.com/2016-12-29-esaoyqhnlz6damxocuyt.gif)

（资料来源:[*Saladtoser69*](https://www.youtube.com/channel/UC4wH23WmLtL20lReS_TZAPg)）

**崛起：罗马之子**

当开发者不给胸部添加物理效果时，不少技术宅玩家就会通过制作mod的方式自己实现。其中典型的就是老滚「天际」的最强乳摇系统mod：

![How Video Game Breasts Are Made (And Why They Can Go Wrong)](http://img.tairan.com/2016-12-29-ccjljwda01jie0mmfggw.gif)

(资料来源: [*Marek Iwanowicz*](https://www.youtube.com/channel/UCa16DLkbM09dzsVJl9mYUhQ))

在2009年，有一个[*第二人生*的mod](http://nwn.blogs.com/nwn/2009/10/emeralds-breasts.html)允许玩家自行给角色添加乳摇系统效果。由于这个mod太受欢迎而被采纳进游戏本体——现如今玩家们纷纷[向他人安利](http://community.secondlife.com/t5/English-Knowledge-Base/Controlling-your-avatar-s-appearance/ta-p/700709#Section_.3.1)如何将自己的角色捏出最好的效果。

![How Video Game Breasts Are Made (And Why They Can Go Wrong)](http://img.tairan.com/2016-12-29-jefijiidaldexsyjjnkz.png)

(资料来源: [*BlakOpalDesigns*](https://www.youtube.com/channel/UC-zcMKtXdvZor4GjZf4rkDw))

甚至「我的世界」的玩家也找出来许多方法添加上乳摇系统效果，毕竟「我的世界」的玩家总是把一切都加进游戏嘛。

### 最有名的乳摇系统系统

历数所有用到乳摇系统效果的游戏中，其中魁首就是「死或生」系列。乳摇系统对于前文所提及的游戏而言或仅是一个小小”特色“，但是对于「死或生」而言，却是深入骨髓的特色。如此过分的强调胸部也许引来了少许恶评，[正如Mike Fahey对于/死或生/的看法](http://www.kotaku.com.au/2015/02/dead-or-alive-is-more-than-breasts)，毕竟很多粉丝喜欢的是这个游戏的玩法而非胸部。但是，乳摇系统确已不能从「死或生」中剥离出去了。

![How Video Game Breasts Are Made (And Why They Can Go Wrong)](http://img.tairan.com/2016-12-29-jz83ql2qdbm7tmvakcdc.gif)

(资料来源: [*Thegamerwalkthroughs*](https://www.youtube.com/channel/UCb7ElR0N_nIIu_Ojx56TR_A))

“在开发「死或生」时，我希望能制作一些吸引玩家注意力的内容，”制作人板垣伴信在 Game Informer/2004年的采访中说。“当然「死或生」是由于它跳跃的乳房而出名的...但当我在3D游戏中制作[乳摇系统效果]时，感觉它还是夸张了一点。”

其中最新作的一大卖点在于，新引擎令玩家可自主调整角色的乳摇系统效果。

“我们将我们所使用的皮肤和乳摇系统仿真技术称为‘Yawaraka Engine’，”Yosuke Hayashi，「死或生：最后一战」的制作人对[Famitsu](http://www.famitsu.com/news/201410/23064123.html)说“你一旦在新主机上看到效果，绝对回不去了。”

他们所说的是：多亏了技术的力量，开发团队可以模拟更为复杂的乳摇系统。高超科技和性文化的结合结果颇奇特……当然，任何人看到「死或生」的视频，必然明白，这个系列并不着重于实现「真实」的物理效果。相反，无论是胸部的效果还是反重力的打斗动作，该作中的物理总是极尽夸张。不管人们对胸部的真实性有着怎样的误解，这种强烈的物理效果应是为实现独特美学的刻意所为。

其他游戏也一样吗？我近几个月都在找开发者们讨论乳摇系统，结果出乎意料地难。——向人刺探未公布大作的细节，比问出胸部设计的理由还要更容易些。我联系了大量开发者，却只有少数人愿意公开接受采访。好彩我还是了解到了乳摇系统的一些基础。

###游戏的乳摇系统如何工作

简单讲，在现代3D游戏中，每个角色都有自己的模型，覆盖着类似于“皮肤”的贴图。这些模型被“骨骼”撑起，而操纵骨骼则令角色移动。骨骼数量是由游戏图像引擎决定的，引擎支持的骨骼数量各有不同。角色骨骼的数量也会被同屏渲染的模型数量所影响--角色越多，就越吃配置，所以减少角色骨骼的数量是开发者乐于见到的。（还好，现实世界不是这样的！）

![How Video Game Breasts Are Made (And Why They Can Go Wrong)](http://img.tairan.com/2016-12-29-fqf758lu1ihxaeycxhba.png)

所有的骨骼在制作动画之前，要进行“rigging（绑定）”处理。绑定令开发者决定一个模型能运动到什么程度，以及如何达成。胸部通常不会自行运动，而是因其他物体运动而产生反应，就像头发和布料一样。如果开发者想要胸部能够移动，他们会“绑定”这个角色的胸腔区域。胸部如何运动取决于胸腔部位的骨骼数量：当胸部左右运动一致时，模型的胸部通常只有一个关节。如果胸部左右独立运动，那么胸腔通常绑定了至少一对骨骼。

![How Video Game Breasts Are Made (And Why They Can Go Wrong)](http://img.tairan.com/2016-12-29-heb491s9jb0t0qoudrue.gif)

(来源: [*Maya Learning Channel*](https://www.youtube.com/channel/UCHmAXsicpLK2EHMZo5_BtDA))

”从结构上看，乳房固定在胸肌上，又向上与肩相连，所以锁骨一移动，就会向后拉动胸部。”Tim Dawson，一名曾参与开发「黑色洛城」的独立开发者对我说。

一旦胸部绑定完成，开发者就有几种方式添加乳摇系统。其中一种控制胸部移动的模拟系统令开发者给胸部加上”弹簧“。例如角色上下跳跃后，弹簧便接受运动信息，并决定物体此后如何移动。弹簧使得胸部能在角色静止下来后继续运动。如果一个角色有两个弹簧组件，一个也许会用来决定胸部骨骼到胸腔的距离，第二个也许用来控制胸部离起始点的距离。除此之外，开发者还可添加一个阻尼效果来决定胸部逐渐停下的时长。

“想象一下这个角色站立起来” Dawson说，“起立的瞬间会使胸部的骨骼向下倾斜。然后当这个角色站直，这个骨骼便会回弹向上，再下坠，反复直到停止。这就是一个胸部运动的流程。“ 剩下的部分就是思考：“[胸部]应该有多重，以及多好的支撑？”

**为什么开发者会误入歧途**

我听说许多游戏都使用了这类系统。其实，若要令游戏物理极尽真实，弹簧系统并不一定有效，但对于乳摇系统是一种便宜又简单的方案。许多引擎甚至内置了它。弹簧系统本来是为了辅助“刚体物理”，然而，乳房并不是刚体。为了造出更真的胸，你需要一种叫“软体物理模拟”的东西，而这对计算机配置要求高得多。

另一种方式则需要手动实现胸部动画。即将胸部与身体的其它主要部分——比如四肢——同等对待。这样，乳摇系统便不交由模拟系统来计算，而由动画师决定每种情形下的动作。我得知，手动实现要比模拟实现罕见得多，因为它十分耗时。简单说，给胸部做动画实在太棘手了（对不起哦。）

尽管这二者之外也有其它方式制作胸部动画，但这仍然解释了一些问题。比如为何在格斗类游戏中常见独特的乳摇系统：如果同屏只需考虑两个角色，开发者当然可以添加像乳摇系统这样的细节。格斗类游戏的角色往往比一般游戏的骨骼更多。乳摇系统的制作难度也解释了为什么许多游戏里的胸部看起来很奇怪：即使开发者愿意加入这些细节，经济上也不允许，只得削减成本。

![How Video Game Breasts Are Made (And Why They Can Go Wrong)](http://img.tairan.com/2016-12-29-rj1ad1bm1hi2ipyuhrrd.gif)

不过，若说乳摇系统不真实纯属技术缺陷所致，也不尽然。毕竟乳摇系统是一种选择，并非个个游戏必备。

一位化名Alex的开发者讲述了乳摇系统出状况的经历——原因并非技术限制。Alex说，工作室当时非常重视胸部的表现，但还是遇到很多问题。

“当时（工作室）制作胸部动态的时候，我首先注意到的就是它们的运动方式根本不自然。”Alex说。

“我记得当时我对美术说，‘胸部摇起来不对啊’，我记得我直接这样问他，‘你看过胸部运动吗？你「亲眼」见过胸部运动吗？’”

这个动画师是很大可能以前是见过胸部的。但要知道，记住胸部具体如何运动实在太难。即使是像笔者这样能持证上岗的巨乳女神，也要仔细检查自己胸部如何运动，才能在游戏中真实地反映出来。当然，这属于动画师的职业范畴。

“我认为（人们）记得的是「幻想」中的胸部，就像我们记忆中嘴唇的颜色更红，还有我们记忆中腰围（总是比实际更纤细）。”Alex解释道。

“如果你见过动画师干活，会发现他们经常站起来，或者询问同事——那是在尝试观察动作，还会录下自己的动作。但很有意思，我根本没和女动画师当过同事。”

“反正，（动画师会）甩甩胳膊，试着找点感觉，他们在研究动画像什么样子。而我觉得……游戏里面经常特别强调乳摇系统，却没有能实现效果的动作。

## 人们希望看到的是的是他们想象中的胸部。

但是，夸张的乳摇系统并不总是无心之失。一些开发者讲述了故意把乳摇系统做得很夸张的情形。因为在实现胸部运动中花费了工夫，开发者大概很想让大家注意到胸部。这种现象不光出现在胸部。若一个开发者在游戏的细节上花时间，都会很想要玩家注意到。所以我们才看到开发视频中讲述游戏怎么表现风、角色斗篷怎么摆动等等——这一类东西对游戏品质不起决定性作用，却是人们常花许多时间去实现的。

“如果开发者特意去让胸部动起来，说明有人很想看它动。”Dawson对我说，“假如说你一个不小心，设置胸部以最小的幅度来摇摆反弹。想象一下工作是老大进来问你，怎么角色讲话的时候看不到乳摇？于是效果就增强到说话的时候胸部也会起伏，但现在角色如果跑动或者做其他动作，甩胸幅度就夸张得荒谬了。但这时候实现功能的人就必须照办，因为有人认为这样比较好。”

“总而言之我有点怀疑，如果乳摇系统调得不自然，一定是因为有别人为了种种原因，故意要他们这样做的。”Dawson说。

虽然很显然，Dawson所说的仅代表他自己项目组的决策情况，但他的话是有一定道理的。例如「刀魂」开发组，[公开发表](http:www.ifc.com_fix/2011/05_how-soul-calibur-keeps-its-boo) 说他们的游戏中有围绕胸部表现的全套系统。

![How Video Game Breasts Are Made (And Why They Can Go Wrong)](http://img.tairan.com/2016-12-29-x7r9hicddsyq7maeunoy.jpg)

不用说，他们一定想要胸部的外观和运动与设计相同。只是即便意图如此，玩家不一定接受。

“世界上所有女人看到这玩意儿之后都会望而却步，哼，‘奶子才不会这样甩来甩去，根本不自然！’”Alex说。他自然知道。他所在的项目组中，游戏模型都都经过玩家测试。开发者们收到了女性看过游戏后的真实反馈。大部分项目组不会这样做，但这一次开发组内没有足够女性来提供意见，因而进行了调查。

“从整体上看，（女性的反应）不是中立的，而是负面的。”Alex说。奇怪的是，无论物理效果不真实，还是物理效果关掉时，都会得到负面评价。似乎制作乳摇系统像是走钢丝，既不能太夸张，也不能太压抑，不然总会有人觉得有问题。你可以把这想作“乳摇恐怖谷”。

### 就爱这样的胸部

Alex的工作室通过玩家测试、利用参考材质，以及对解剖结构的诚恳探讨，最终改进了乳摇系统的表现。但是我说的“改进”，当然不是“更加真实”的意思。

“很多游戏里充斥着夸张的（男性）形象”，Alex说。“但我们并不会说‘靠，这做的太假了！’那些角色当然不真实！但是他们看起来超级强壮，而且我们喜欢那种强壮。这种道理同样适用于胸部”

Tim Dawson似乎也同意这种观点。他觉得开发者倾向于不真实的胸部，是因为夸张的身体表现已经成为一种行业标配。

“开发人员可能会对解剖结构很马虎，比如做出的胸部过大或者身体根本无法支撑，或者整个形状不自然，”Dawson说，“有一次我发现一个女性敌人模型的胸部像气球一样从身体里凸出来，但是没法说服美术总监修改。”

“但就算建模很好，如果一个拥有西瓜般大小乳房的角色，身着比基尼用大侧手翻攻击敌人，这种乳摇系统表现也非常难以拟真，因为整个场面就不真实。”他说。

“人们喜欢看胸部的动态，这是我们大脑的本能”，Alex说，“因此，对有的人来说，把胸部做夸张稳赚不亏。我觉得游戏里有（乳摇系统）就是因为这原因。”

### 给游戏开发者的建议

不管工作室追求真实性还是艺术美感，总是既有胸部运动看上去不错的游戏，也有胸部运动夸张的游戏。对于游戏开发者，应该有办法让乳摇得更好看。

“出来走两步！也就是把动画播给人看”，Alex说。他还强调在工作室女性员工不足时，对外演示尤为重要。

还有一点值得考虑，那就是游戏要展示什么样的胸部。Alex指出，自然的胸部和夸张的胸部截然不同。

一个人的独特体态会影响胸部运动。有些人生来胸围傲人，也影响胸部的运动。而乳房位于胸部的高低和其挺翘程度也不尽相同。诸如此类的差别还有很多。

“即使是绝赞的自然胸型也是会有一定程度的下垂”，Alex表示，如果开发者们意图做出更好的乳摇系统，认真考虑这些事情很重要。

Alex给的另一点建议是利用色情片或色情杂志，特别是那种老版的裸女杂志。真的，这些都是绝佳的参考素材。

“（这些素材能提供）绝佳的观察机会，乳头在哪里？胸部的线条是怎么动的？乳房下部的曲线是如何的？”。

“我认为在游戏中的胸部不需要过于真实，除非这就是（开发者的）本意……当然，如果动起来很诡异，那还是要注意，那会让姑娘们有“恐怖谷效应”一样的不适感受的。”

牢记这些，也许今后的游戏中会有更好看的胸部。到那时，游戏业就可以改为解决下一个难题……钉钉物理了。

“如果你让我做一个裸男走路的动画，我肯定懵逼的，蛋蛋到底怎么动啊，”Alex开玩笑道，“真不知道！”

## 何去何从

原文地址：「How Video Game Breasts Are Made (And Why They Can Go Wrong)」http://www.kotaku.com.au/2016/12/how-video-game-breasts-are-made-and-why-they-can-go-wrong/

