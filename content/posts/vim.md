---
title: "Vim"
date: 2024-04-04T11:08:11+08:00
lastmod: 2024-04-04T11:08:11+08:00
author: ["Sulv"]
keywords: 
- 
categories: # 没有分类界面可以不填写
- 
tags: # 标签
- 
description: ""
weight:
slug: ""
draft: false # 是否为草稿
comments: true # 本页面是否显示评论
reward: true # 打赏
mermaid: true #是否开启mermaid
showToc: true # 显示目录
TocOpen: true # 自动展开目录
disableShare: true # 底部不显示分享栏
showbreadcrumbs: true #顶部显示路径
---


## Vim-Adventures简介

Vim作为一款神级编辑器，却有非常陡峭的学习曲线。网上大部分的教程很多仍然以背指令为基础，很容易让人望而却步。之前我也多次想要学习Vim但是最终都放弃了。直到使用Vim-Adventures才发现要入门Vim其实一点也不难，而且只要熟悉了一些基本命令以后，Vim的使用体验就绝对超过市面上大部分的编辑器了。

就我个人的体验来说，理解Vim的指令并不难，难点在于掌握Vim需要大量的重复练习。初学Vim的人很难有大量使用Vim操作的环境，或没有安全的可以进行编辑的文本，或无法忍受初学Vim时相对下降的编辑效率，从而很快就放弃了Vim。

Vim-Adventures是一款基于Vim操作的网页版游戏，通过一些游戏行为能潜移默化地熟练Vim的基本操作，最终形成肌肉记忆。同时Vim-Adventure给予了玩家一个安全的、可大量重复练习的环境，从而在短时间内获得使用Vim的快感，最终能够体会到Vim的强大。

Vim-Adventures的难度梯度还是比较平缓的，前几关都能够很简单的完成。但是随着游戏的进行，挑战难度会逐渐增大。鉴于网上没有看到比较全面的中文版的攻略，在全部通关Vim-Adventures后，我把每一关的流程攻略写在这里，给有兴趣学习Vim的朋友参考。

Level 14部分参考了github:

> https://github.com/pepers/vim-adventures

需要特别说明的是，整个攻略基于我自己的尝试，很有可能不是最优解，需要其他玩家共同发掘。同时强烈建议除非卡关很久否则尽量不要看这个攻略，自己实践的训练效果是最好的。

全文最后有一个小彩蛋，关于学习git的使用。

#### Vim-Adventures全攻略

-   [Vim-Adventures简介](https://blog.csdn.net/weixin_45107866/article/details/93711288#VimAdventures_0)
-   [游戏内常用命令](https://blog.csdn.net/weixin_45107866/article/details/93711288#_19)
-   [Level 1](https://blog.csdn.net/weixin_45107866/article/details/93711288#Level_1_33)
-   [Level 2](https://blog.csdn.net/weixin_45107866/article/details/93711288#Level_2_46)
-   [Level 3](https://blog.csdn.net/weixin_45107866/article/details/93711288#Level_3_55)
-   [Level 4](https://blog.csdn.net/weixin_45107866/article/details/93711288#Level_4_70)
-   [Level 5](https://blog.csdn.net/weixin_45107866/article/details/93711288#Level_5_75)
-   -   [Deleting段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#Deleting_78)
    -   [Before段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#Before_89)
    -   [These段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#These_104)
-   [Level 6](https://blog.csdn.net/weixin_45107866/article/details/93711288#Level_6_123)
-   -   [Some段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#Some_128)
    -   [~段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#_142)
    -   [begin段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#begin_148)
    -   [There段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#There_156)
    -   [With段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#With_162)
    -   [function段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#function_168)
    -   [I段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#I_174)
-   [Level 7](https://blog.csdn.net/weixin_45107866/article/details/93711288#Level_7_181)
-   -   [The段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#The_184)
    -   [emptyStr段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#emptyStr_195)
    -   [if段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#if_202)
    -   [fx段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#fx_210)
    -   [What's段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#Whats_217)
-   [Level 8](https://blog.csdn.net/weixin_45107866/article/details/93711288#Level_8_222)
-   -   [That's段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#Thats_229)
    -   [Shoot段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#Shoot_232)
    -   [Here's段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#Heres_242)
    -   [You段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#You_263)
    -   [Today段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#Today_268)
    -   [Eeny段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#Eeny_277)
-   [Level 9](https://blog.csdn.net/weixin_45107866/article/details/93711288#Level_9_286)
-   -   [Numbers段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#Numbers_287)
    -   [I段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#I_293)
    -   [Var段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#Var_304)
    -   [HAWAIi段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#HAWAIi_317)
    -   [You段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#You_333)
    -   [3.1415926535段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#31415926535_338)
    -   [Deleting段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#Deleting_351)
-   [Level 10](https://blog.csdn.net/weixin_45107866/article/details/93711288#Level_10_364)
-   -   [Bey段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#Bey_377)
    -   [Round段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#Round_386)
    -   [Delete段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#Delete_394)
    -   [on段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#on_403)
    -   [If段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#If_420)
    -   [When段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#When_430)
    -   [rule段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#rule_443)
    -   [Let's段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#Lets_450)
    -   [the段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#the_459)
-   [Level 11](https://blog.csdn.net/weixin_45107866/article/details/93711288#Level_11_471)
-   -   [rush段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#rush_474)
    -   [press段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#press_480)
    -   [Made段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#Made_488)
    -   [Grey段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#Grey_500)
    -   [What？段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#What_505)
    -   [Mahatma段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#Mahatma_513)
    -   [4 8段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#4_8_522)
    -   [entary段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#entary_533)
    -   [You've段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#Youve_538)
    -   [Hakuna Matata段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#Hakuna_Matata_548)
    -   [D'oh段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#Doh_563)
    -   [Formally段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#Formally_568)
    -   [this段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#this_575)
    -   [No段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#No_584)
    -   [Arrow Island：](https://blog.csdn.net/weixin_45107866/article/details/93711288#Arrow_Island_590)
    -   [YOU段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#YOU_598)
-   [Level 12](https://blog.csdn.net/weixin_45107866/article/details/93711288#Level_12_605)
-   -   [It's good段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#Its_good_608)
    -   [In every generation段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#In_every_generation_614)
    -   [May the 4th段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#May_the_4th_621)
    -   [You can measure段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#You_can_measure_627)
    -   [for (i='a';段](https://blog.csdn.net/weixin_45107866/article/details/93711288#for_ia_636)
    -   [These are not段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#These_are_not_643)
    -   [\\\* \\{ margin段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#__margin_650)
    -   [for (int i=0;段](https://blog.csdn.net/weixin_45107866/article/details/93711288#for_int_i0_662)
    -   [\\段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#DOCTYPE_html_672)
    -   [yoda段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#yoda_680)
    -   [In the段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#In_the_688)
    -   [LeChuck?段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#LeChuck_703)
    -   [function段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#function_709)
    -   [1 2 3 4 5段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#1_2_3_4_5_717)
    -   [One little段：](https://blog.csdn.net/weixin_45107866/article/details/93711288#One_little_728)
-   [Level 13](https://blog.csdn.net/weixin_45107866/article/details/93711288#Level_13_740)
-   [Level 14](https://blog.csdn.net/weixin_45107866/article/details/93711288#Level_14_742)
-   -   [W Mark：](https://blog.csdn.net/weixin_45107866/article/details/93711288#W_Mark_762)
    -   [H Mark：](https://blog.csdn.net/weixin_45107866/article/details/93711288#H_Mark_768)
    -   [A Mark：](https://blog.csdn.net/weixin_45107866/article/details/93711288#A_Mark_774)
    -   [D Mark：](https://blog.csdn.net/weixin_45107866/article/details/93711288#D_Mark_780)
    -   [Underground Buffer：](https://blog.csdn.net/weixin_45107866/article/details/93711288#Underground_Buffer_798)
-   [总结](https://blog.csdn.net/weixin_45107866/article/details/93711288#_809)
-   [彩蛋](https://blog.csdn.net/weixin_45107866/article/details/93711288#_812)
-   -   [本地git仓库题目](https://blog.csdn.net/weixin_45107866/article/details/93711288#git_828)
    -   [远程git仓库题目](https://blog.csdn.net/weixin_45107866/article/details/93711288#git_830)
    -   [完成](https://blog.csdn.net/weixin_45107866/article/details/93711288#_832)

## 游戏内常用命令

在学习Vim的基础命令前，有一些游戏命令需要了解。

```c
:login # 登录命令。必须登录才能继续Level 3以后的游戏内容 :stats # 显示统计数据，主要显示每关的按键，用时等 :keyboard # 显示当前可以使用的指令。可用指令随着游戏进程逐步增加 :w <'filename'> # 储存游戏进度，最多可以储存3个游戏进度。如果已有同名进度，需要使用:w!覆盖。此命令本身也是Vim命令 :e <'filename'> # 读取游戏进度。此命令本身也是Vim命令 :!ls # 列出当前储存的游戏进度。注意和':ls'区分 :!rm <'filename'> # 删除游戏存档 :q # 退出游戏。此命令本身也是Vim命令 :level <'n'> # 一旦通过某关，则可以使用:level命令直接跳转至该关开头
```

## Level 1

第一关主要是熟悉Vim的移动。Vim中移动光标可以用hjkl也可以用上下左右，但是既然都用来学Vim了，那就尽量不要用上下左右。实际上习惯了hjkl的移动方法以后，手不用离开主键盘区就能实现光标移动命令实在是方便的不行。在Vim Adventures里，如果你想用上下左右移动的话，游戏也会提示你使用hjkl的，所以就老老实实学习这个使用方法吧。

游戏中的小人主要是讲解游戏剧情和一些使用技巧，除了最后一关和中间一些涉及游戏进程的对话以外都可以不用太在意。

首先先移动到钥匙位置取得第一个钥匙，注意上方的Remember里的箱子现在暂时是打不开也过不去的，不要过多纠结，一路穿越迷宫向右，消耗刚刚得到的钥匙打开拦在路上的箱子（门？Whatever。。。）进入草地。

现在发现如果想直接过去会有一个反向台阶阻拦，这里需要用到一个技巧：在较长的一行向较短的一行移动时，如果光标超出较短一行的长度，光标会进入较短的一行的最后。但如果继续从较短的一行向较长的一行移动，则光标会回到一开始光标位置的同一列。

因此，只需要将光标移动到草地的第一行最后，然后按j向下即可越过台阶。第二和第三个台阶同理。

越过三个台阶，和皇冠紫发小人对话，按Esc进入第二关。

## Level 2

在第一行获得指令`w`。w使光标跳转至下一个单词的开头处。

使用w和hjkl进入石块中间获得第一个钥匙和指令`e`。e使光标跳转至当前单词的结尾处，如果已经在当前单词的结尾，则跳转至下一个单词的结尾。

进入最后一行获得指令`b`。b使光标跳转至当前单词的开头处，如果已经在当前单词的开头，则跳转至前一个单词的开头。

使用e进入石块中间获取第二把钥匙，向上混合使用w, e, b获取第三把钥匙后打开三个箱子，和皇冠紫发小人对话，按Esc进入第三关。

## Level 3

在第二行Blue处获得指令B。B和b的区别在于b将标点及空格视为单词间分隔而B只将空格（包括tab）视为单词间的分隔。

标红框的暂时无法处理，先将光标移动至草丛边带帽子小人，接下来屏幕右上角会有30秒倒计时。玩家需要在30秒内到达整段文字的最后。

先按j进入文字，按Esc跳过屏幕滚动。17个w到达第三行on，4个e到达my，不断尝试重复使用we之后到达最后一行拿到指令x，等30秒时间到后就会被传送会文字开头。

x可以删除当前光标所在的字符。使用x将Roses段落内标记红框的字符删除后可以获取棕色钥匙。混合使用hjkl, wbB按照原路返回第一关游戏最开始处Remember段落。光标移动至“！”处，使用B进入段落，打开棕色宝箱，获得蜡烛。

如果要继续下面的游戏需要注册付费，费用是25美刀，有效期半年，可以使用信用卡进行支付。

注册付费后就可以使用注册的账号登录。使用全文开头给出的命令可以实现登录，保存游戏进度，读取游戏进度，选择关卡等功能。

拿到蜡烛以后，只能看到附近一点范围的地图，返回之前获得棕色钥匙的小岛，和皇冠紫发小人对话，按Esc进入第四关。

## Level 4

向下走几步后黑暗状态会解除，用x删除所有标红框字符后获得指令W和指令E。W E对应w e的效果和B对应b的效果非常接近，可以类比理解。

在script段落，从<开始，按E跳至>，向下到第三行按B到达句首，移动获得指令r。指令r的作用是替换，按r后输入正确的字符就可以替换当前的字符。将红框内红色的字符用r替换为黑色字符，分别为r0 r< rl rm ra rr rr即可完成本段。和皇冠紫发小人对话，按Esc进入第五关。

## Level 5

从第五关开始游戏难度逐渐提升，各个puzzle的路径也变得不是特别直观。在接下来的攻略中，将用每个puzzle的开头单词作为puzzle的标识。

### Deleting段：

回顾之前的x和r指令，注意有变化红框的就是需要用r替换的，否则就是用x删除的。

-   第1行删除x,e
-   第4行删除l
-   第5行rd，删除ool ool
-   第6行删除s，rr
-   第7行删除c，rw
-   第8行rm rs rn

完成后获得指令d。d和x都起删除的作用，但是x一次只删除一个字符，d可以删除多个字符/行/段落。这里需要说明的是，单独的d并不起作用，d需要配合一个定位符来使用，原因很好理解，因为x就是删除当前光标所在的字符，但是d删除的是一个范围，需要根据光标的定位删除当前光标和指定光标之间所有的字符。dd可以直接删除当前一整行，这是vim中的一种快捷方式，以后也会有很多指令有类似的效果。

### Before段：

注意从这里开始，需要删除的红框就不止一个字符了。如果红框框住多个字符，说明需要在一个指令内删除。比如"gone"中的"ne"就不能用两次x删除，必须一次清除。

-   第1行a处dw，n处de
-   第2行空格处de，rarw，删除d
-   第3行rx
-   第4行rs
-   第5行删除r，a处de
-   第6行删除r，删除s，删除s，rd
-   第7行rl
-   第8行n处dw

完成后获得金色钥匙。

在第4行的affair处按e进入路中间。向上回到右侧，进入These段。

### These段：

-   第1行n处dw，t处dw
-   第2行y处dw
-   第3行o处dW，n处dw
-   第4行删除u，ry，s处dw，删除感叹号
-   第6行删除两个空格，rabbit的i处db
-   第7行n处dE，rn
-   第9行re，删除t
-   第12行rt，删除u，keyboard的b处de
-   第13行kIdder的第二个d处de，rh
-   第16行需要一次删除两行。在第16行任一处dj即可

注意明面上看似乎都处理完毕，但是最后有一句"BTW, X does mark the spot"提示还有一个小puzzle未解决。  
在X处按x，会出现提示：当向前删除时，光标所在位置的字符不会被删除。因此，在.处db，可以删除X和后面的空格，从而完成这个puzzle。

完成后获得金色钥匙。

使用获得的金色钥匙打开两道门后和皇冠紫发小人对话，按Esc进入第六关。

## Level 6

从第六关开始，整体难度再次提升，大部分的puzzle有了按键次数的限制，这要求玩家用精简的方式对字符进行处理，这也符合Vim操作的核心宗旨。一旦puzzle内按键次数超过限制，则会直接跳出puzzle，puzzle内的所有已经处理的内容全部清空。

在限制按键次数的puzzle中，puzzle的按键次数上限是比较严苛的，有不少puzzle我反复试了很多次，都只能在上限按键次数完成。但是就是在这样反复思考的过程中，Vim的水平可以得到进一步的提高。

### Some段：

"Some"的m处开始。

进入Some段后就可以看见右上角的"8 key presses to go"，说明这个puzzle需要在8个按键内完成。

小技巧：

1.  进入puzzle后如果发现出现失误，按两次Esc可以直接跳出puzzle。
2.  进入puzzle后在次数限制内可以任意移动，如果没有超过上限就离开puzzle，可以在离开的位置重新进入puzzle。

-   jjjjjjjj（8次j到最后一行Back的下方）
-   h（到Back的c处），b b db即可

完成后获得金色钥匙。

### ~段：

第2行"beard"的b处开始。

-   rh e rt j w rf

完成后获得指令~。 指令~的作用是大小写的互相转换。

### begin段：

"begin"的b处开始。

-   ~ w e x j j h x W w l rt e x

完成后获得指令$。 指令$的作用是跳转到行最后。

"Shaken"的S处$跳转至感叹号，进入下一部分。

### There段：

第4行"Understand"的U处开始。

-   ~ k k k $ rs j j j de

完成后获得指令0。 指令0的作用是跳转到行开头。

### With段：

第1行"With"的W处开始。

-   $ ~ j 0 r0 j $ x j 0 w r1 w ~

完成后获得指令^。 指令^的作用是跳转到行的非空首字符。

### function段：

第4行开始。

-   E l D j j j d^ j dd j w w x $ j h h rI W l D

完成后获得金色钥匙。

### I段：

本段不限指令次数，结合之前的操作可以简单通过。

完成后获得金色钥匙。

使用获得的金色钥匙打开两道门后和皇冠紫发小人对话，按Esc进入第七关。

## Level 7

第七关开始出现可以进入的小草丛，而且里面会有NPC和指令藏在其中。

### The段：

puzzle前有一个门被锁住，目前没有钥匙可以打开。

-   进入puzzle后$跳转至最后，进入第4行"with"前的草丛，获得指令,。 指令,的作用是反向重复f t F T四个指令的操作。
-   第7行b到"timidly"，向下草丛获得指令;。 指令;的作用是重复f t F T四个指令的操作。0回到开头。
-   在草丛里b到"grinned"，向下草丛获得指令t。 指令t可以向后跳转到指定字符的前一个位置，而大写的T则向前查找。有了t以后，就可以跨越之前用web无法解决的跳转问题。
-   探索草丛，在第4行"felt"前的草丛里获得指令f。 指令f和指令t类似，向后跳转到指定字符。但是f是直接到达指定字符，t是到达指定字符的前一个字符。大写F方式类似于大写T，是向前查找指定字符。
-   倒数第5行的"Alice"前的草丛中藏有一个戴帽子的小人，对话后会在5秒后将玩家传送到第11行"way"前的小人处。目前没有什么作用。
-   在倒数第2行的"the"前的草丛里获得指令z。指令z搭配ztb三个位置，可以在不移动光标的状态下调整页面的位置。zb是将当前光标所在行变为最底端（bottom），zt是将当前光标所在行变为最顶端（top），zz是居中。

通过puzzle后向下，进入下一个puzzle。

### emptyStr段：

-   fx dt" 删除5个x

完成后获得金色钥匙。

使用钥匙打开边上的大门，获得指令%。 %可以方便的在()\[\]{}等符号间做跳转。

### if段：

-   $ % j d%

完成后获得金色钥匙。

向上回到海岛puzzle，和Alice前的小人对话，搭配0可以迅速返回puzzle一开始的大门，使用钥匙解锁后获得指令g。g是一种更加迅速的跳转方式。gg可以直接到达全文开头，G可以直接到达全文结尾。if段的puzzle也可以用dG替代d%处理。

有了指令g以后可以迅速跳转至海岛下方。

### fx段：

-   这个puzzle需要用到一个新的技巧。先进入段落，使用Fx到达第1段的x的位置，然后按两次Esc退出puzzle。但是此时Fx的指令已经被系统记录在寄存器中，此时就可以使用之前获得的指令,和;迅速重复Fx这个指令。
-   再次进入puzzle
-   ; x j , x j ; x j x , x

完成后获得金色钥匙。

### What’s段：

-   gg tm k通过What’s段
-   % k通过(2段

使用钥匙解锁，和皇冠紫发小人对话，按Esc进入第八关。

## Level 8

开始后需要重新回到之前的区域，因此需要原路返回。注意返回时同样有限制指令次数的要求。

-   t2后退出puzzle，重新进入，; j
-   G h

即可回到主路线。

### That’s段：

-   移动到有裂痕的字符处即可修复裂痕，全部修复完毕后获得金色钥匙。

### Shoot段：

本段不限指令次数。

-   第1行"honeymoon"m处db
-   第2行rm
-   第3行"have"h处dtl
-   第4行"stone"o处dta
-   第5行dG

完成后获得指令\*。 指令\*是查找光标（光标后）最近的字符，同时跳转过去。

### Here’s段：

本段之前的海洋不同，黑色区域一旦进入就会传送回之前的位置。

-   $ b
-   \* \* j

由于没有足够的指令，这个puzzle暂时无法完成。先暂时离开puzzle，向下移动。

-   获得指令#后继续，在最后一段的r处开始
-   \# e #
-   \* 0 \* \*
-   k j # # #
-   gg $ b \* \*
-   \* Fh #
-   gg $ b \* 获得蓝色钥匙
-   \* j \* Fh # e
-   使用蓝色钥匙打开蓝色大门，获得指令n。

指令n类似于, ;，是对\*和#的重复。同样，大写N是对\* #的反向重复。

-   回到段落中 gg $ b \* \*完成puzzle，进入左侧Today段

### You段：

-   使用f和t打开草丛，在倒数第4行的草丛中获得指令#

指令#作用和\*类似，但是查找方向相反。有了#指令就可以回到Here’s段

### Today段：

当使用\* #进行搜索时，整个段落中的匹配是内容都会出现，也就是说，这种搜索是全局的，因此，搜索出的结果和记录也是全局的。所以要解决这个puzzle，首先到You段第5行"You"处。

-   \* 可以看到所有的you都被标记，这时再回到Today段
-   注意这里不能使用\* 或者#，因为一旦使用这两个指令，就会覆盖之前对you的搜索。
-   N
-   到达上方You处后使用金色钥匙打开大门

和房间内小人对话后，小人会在10秒后将你传送到他的第一个兄弟处。

### Eeny段：

传送后和小人对话，小人会要求你去最后一个兄弟处，如果60秒内不能到达，就会被传送回之前的位置。这时发现这个puzzle无法跳转。仔细观察发现，出口处是一个.，因此，需要在之前的段落标记好.，然后使用n进行跳转。

-   和小人对话后等60秒，被传送回之前的地方。使用同样的方法回到Today段。
-   和房间内小人对话后立刻回到段落，n跳转至本段结尾的"You."处，在.上按\*对.进行搜索
-   10秒后被重新传送到下方
-   进入段落后使用两次n指令到达出口
-   和最后一个兄弟对话后完成puzzle

和皇冠紫发小人对话，按Esc进入第九关。

## Level 9

### Numbers段：

-   $ j j j j到达下方草丛，在最左上角的草丛里获得金色钥匙
-   gg回到开头

使用金色钥匙打开大门，获得指令数字。数字指令可以说是Vim中最好用的指令之一，数字可以对后面的指令进行重复，极大地减轻了指令操作次数。

### I段：

注意这个puzzle需要按照指定的顺序到达每个字符。字符右上角的数字表示移动顺序，从1直到7。

-   4j 到达2
-   0 到达3
-   2k 到达4
-   3w 到达5
-   4$ 到达6
-   Tu 到达7
-   5G 4l 4k获得金色钥匙
-   99$ 小技巧：当指令数字过大时，Vim会尽可能多地完成指令。因此在获得钥匙后，可以使用99$直接到最后，然后Tu完成puzzle

### Var段：

-   fi 到达2
-   3\* 到达3
-   Fu 到达4
-   2# 到达5

通过puzzle后向下，进入下一个puzzle。

-   3B j
-   4T-

通过puzzle后向下向右，进入下一个puzzle。

### HAWAIi段：

-   3x ~ j
-   5~ 这里会掉下去，但是没有影响。目前没有想到可以不掉下去的方法
-   5j d4j
-   fC 2rG 注意晃动的字符只能踩一次，踩过后就会消失
-   99k

完成后获得金色钥匙。

原路返回：

-   3e k 3t-
-   2G

回到主路后向左，进入下一个puzzle。

### You段：

-   15B k

通过puzzle后向上，进入下一个puzzle。

### 3.1415926535段：

这段猛看似乎可以使用\*+,;的方法处理，但是实际上在Vim中，\*和#是对整个单词进行识别的，而这个puzzle中，由于没有空格等区分，因此几乎每一行才被视为一个单词，因此\*和#是没有办法使用的。

-   在puzzle外f8
-   2G ; 3j
-   4j ^ 2j 2; 4j ; 获得金色钥匙
-   ,

通过puzzle后向下，回到You段puzzle。

-   3$ l暂时离开puzzle
-   返回puzzle，2Fa j

通过puzzle后向下，使用一把金色钥匙打开门，进入下一个puzzle。

### Deleting段：

-   2w d2w
-   4j b l
-   3x
-   3j 0
-   d3W x j
-   2l d2fX j
-   h d4w x j
-   3l d2tb

完成后获得金色钥匙。

使用三把金色钥匙打开门后，和皇冠紫发小人对话，按Esc进入第十关。

## Level 10

在上一关和皇冠紫发小人对话的边上可以看到灰色的字：“DELETED Is Not Really LOST”。正是这句话引出了第10关的内容。

在通常的文本编辑器中，删除的内容就是删除了，想要恢复就要不断的撤销（其实被删除的内容也是被储存了起来，只是不能显式地调用而已），在Vim中，被x或d删除的内容也是如此，这样的删除并不是真的被删除，而是类似于剪切，统一被保存在寄存器（register）当中。Vim里有多种寄存器，如无名寄存器（unnamed，最常用的寄存器），小删除寄存器（small delete），数字寄存器（numbered，1-9），具名寄存器（named，a-z），黑洞寄存器（black hole）等。寄存器的知识会在后面详细讲到。

首先先获得指令p，指令p就是粘贴，默认粘贴会粘贴最近一次复制或者剪切的内容，在当前，就是删除的内容。p是在光标后粘贴，P则是在光标前粘贴。

在下方使用d和x剪切特定内容后，在提示的对应位置粘贴即可。

完成后获得金色钥匙。

右上角的箱子需要棕色钥匙才能打开，暂时先不用理会。使用金色钥匙打开大门向下，进入下一个puzzle。

### Bey段：

-   向上剪切字符t
-   在"Bey"的e处2p
-   在"bough"的h处p
-   在"bi"的i处p
-   在"buer"的u处2p

完成后向左向下，进入下一个puzzle。

### Round段：

-   j dj
-   p
-   gg
-   P

完成puzzle后获得指令"，使用"就可以显式地指定剪切/复制所使用的寄存器。同时，:reg可以看到当前寄存器的使用情况，即储存的内容。向下进入下一个puzzle。

### Delete段：

-   j dd
-   dd
-   dd

完成后向下进入下一个puzzle。

这里删除的三行，使用:reg打开寄存器，可以看到编号1-3的3个寄存器保留了刚刚删除的三行内容。当我们需要粘贴时，可以在p前使用"加上寄存器代码，显式地复制寄存器内保存的内容。

### on段：

注意进入限制指令的puzzle后，打开寄存器查看也是消耗指令次数的。因此，在进入puzzle前先确认这个puzzle需要粘贴的内容对应所在寄存器的数字编号。我的寄存器内容为：

```c
"" 99 bottles of beer （无名寄存器，保留最近一次剪切的内容） "1 99 bottles of beer "2 on the wall. "3 pass is around,
```

-   P（默认粘贴无名寄存器的内容）
-   j p
-   j "3p
-   j "2p

完成后后一直向上，然后向右向上，进入下一个puzzle。

### If段：

如果直接删除X，那么在第一行粘贴时就无法成功粘贴t，因此，需要先将t保存在指定的寄存器当中。

-   （我将t保存在4号寄存器中）"4x
-   删除X
-   gg $ "4p
-   3j 2Te获得金色钥匙

完成后向右进入下一个puzzle。

### When段：

除了数字寄存器之外，还有具名寄存器，使用a-z进行命名。当某个具名寄存器已经有内容存放时，"\[a-z\]会替换寄存器内的内容，而"\[A-Z\]则会在对应寄存器后进行追加。

-   4G w "adw "bdw
-   5G "Adw "Ade
-   k "Bde
-   "aP
-   j "bP

完成后获得棕色钥匙。回到关卡开始处，打开棕色箱子，获得指令y。指令y即为复制指令，思路与d接近。

返回获得棕色钥匙的地方，向下进入下一个puzzle。

### rule段：

-   第2行开始处y3w
-   k P
-   3G P

完成后获得金色钥匙，向下进入下一个puzzle。

### Let’s段：

-   j dd
-   j dd
-   k yy
-   2P
-   G 3p

完成后获得金色钥匙。回到左侧最下方，进入下一个puzzle。

### the段：

这个puzzle需要的内容为：“Betty rules” “tweetle bettle” “on the wall” “One Ring”，对应内容需要在整关中找到并存入寄存器后粘贴。

我的寄存器内容为：

```c
"a Betty rules "b tweetle bettle "c on the wall "d One Ring
```

全部粘贴后使用3把金色钥匙打开三扇门，和皇冠紫发小人对话，按Esc进入第十一关。

## Level 11

进入11关后会发现跳转到天空图。实际上这是Vim的缓存区，用以同时处理多个文件。使用:ls可以看到所有的工作区，当前所在的工作区前标记%，前一个工作区前标记#。

### rush段：

-   第2行"you"处进入，yw k P b ~
-   3w yw j $ P rs

完成后获得指令c。c也是非常常用的指令，用于替换一段字符内容。相当于删除一段内容后重新输入，这里不要求删除前的内容长度和输入后的内容长度相同，理论来说，c一个字符后重新打一万个字也是没有问题的。

### press段：

-   第1行"Ctrl"处 c3$ Esc <Esc>
-   j C insert mode <Esc>
-   j ce mode <Esc>
-   3b ce return to <Esc>

完成后向下进入下一个puzzle。

### Made段：

-   第1行"terrible"处 dw
-   jb ce editing <Esc>
-   $ r?
-   j b C Delete <Esc>
-   3b ce Backspace <Esc>
-   j cc to fix it. <Esc>

完成后获得指令s。指令s是直接替换当前所在字符，和c需要指定目标位置点有一定的区别。

向上回到关卡开始处，向右进入下一个puzzle。

### Grey段：

-   \* C White <Esc>

完成后向右进入下一个puzzle。

### What？段：

-   第1行删除i和it
-   第2行S local fisherman, <Esc>
-   第4行 2sn <Esc>
-   第6行 S waters… <Esc>

这段完成后需要切换工作区，直接:b#就可以跳转回到地面进入下一个puzzle。

### Mahatma段：

-   第1行删除hat，rs
-   第2行swa <Esc>
-   第3行ce chocolates <Esc>
-   第4行ce never <Esc> rw
-   第5行ce et <Esc>

完成后获得蓝色钥匙，向下进入下一个puzzle。

### 4 8段：

-   "8"处开始，es 15 <Esc>
-   w ce 16 <Esc>
-   2w x
-   w 4C 42 <Esc>

完成后获得棕色钥匙。:b#返回天空，使用蓝色钥匙打开大门，使用棕色钥匙打开宝箱，获得指令i。指令i是在当前字符前插入文字。

其实从这关开始，对Vim的操作就已经从Normal模式加入了Insert模式。i是进入Insert模式最常用的方法，在Insert模式下，一切按键都会变成输入，而不作为指令执行。

获得指令i后就可以回到关卡开始处一直向下，进入下一个puzzle。

### entary段：

-   I Elem <Esc>

完成后向右进入下一个puzzle。

### You’ve段：

-   W i got (注意这里有空格) <Esc>
-   j I yourself (注意这里有空格) <Esc>
-   j b i I (注意这里有空格) <Esc>
-   j I Well <Esc>

完成后获得指令a。指令a和i几乎完全相同，唯一区别就在于i是在光标前插入而a是在光标后插入。

:b#回到地面，进入下一个puzzle。

### Hakuna Matata段：

-   Y
-   2k i It <Esc> A philosophy <Esc>
-   gg P
-   j p
-   w h k a wonderful <Esc>
-   j b h j i no <Esc>
-   l 2j a no <Esc>
-   3j i It <Esc>
-   3$ b h获得蓝色钥匙

:b#回到天空，使用蓝色钥匙打开大门，获得指令o。指令o会在当前光标下新建一行并同时进入Insert模式，O则是在上一行插入。

向左向上返回，进入下一个puzzle。

### D’oh段：

-   5A! <Esc>

完成后向右进入下一个puzzle。

### Formally段：

本段不限指令次数，结合之前的操作可以简单通过。

-   注意如果遇到输入正确但是没有显示通过的情况，请检查是否有空格相关的问题

完成后:b#回到地面进入下一个puzzle。

### this段：

-   第1行开始：O You mean <Esc>
-   j o all I had <Esc>
-   j o click my <Esc>

完成后出现小人，对话给出第一个提示，要进入underground file，箭头岛（arrow island）的第二个词"Sesame"应该为"underground"。

可以看到"Open Sesame"是一个箭头的标记，即所谓的箭头岛（arrow island）。说明这个是通往下一个关的地方。向上进入下一个puzzle。

### No段：

-   第1行开始：4O Beat it <Esc>
-   gg s Just b <Esc>

完成后出现小人，对话给出第二个提示，箭头岛（arrow island）的第一个词"Open"应该为":e"。

### Arrow Island：

-   已知两个提示后，在"Open"的O处 ce:e <Esc>
-   w C underground <Esc>

完成后获得红色钥匙。在全文一开始的指令中也有提到，:e是打开一个文件，在这里输入:e underground进入underground。

使用红色钥匙开门后进入下一个puzzle。

### YOU段：

-   w ce SHALL <Esc>
-   l p
-   fP C ! <Esc>
-   B P

完成后和皇冠紫发小人对话，按Esc进入第十二关。

## Level 12

最后这几关的难度比较大。从12关开始有了会动的“bug"，一旦碰到就会被踢回关卡开始，所以反复重来是不可避免的，同时还要一定的熟练度保证眼疾手快，而且还需要有些耐心。好在被bug踢回关卡开头处并不会导致关卡的重新读档，所以不用太有压力。当然，bug们也是可以被消灭的，根据bug身上标示的指令，只要他们出现在指令的影响范围内，bug就会被消灭。因此，d和y会在面对bug的时候非常有用。

### It’s good段：

-   d j：当d j在下方时d99j
-   5W：在距离5个词时d5W

完成后获得指令==()==。小括号()会在整句话之间进行跳转。整句话的标识为句号.，问号?和感叹号!。向上进入下一个puzzle。

### In every generation段：

-   gg G: dgg dG即可消灭。注意，由于d指令不会跳转，因此消灭bug后会保持原位。
-   ()：距离1句内d( d)
-   \# \*：当# \*在下方时d# d\*

完成后获得指令\[\]。中括号\[\]本身需要搭配()或者{}使用，用来查找未闭合的()或{}。向左进入下一个puzzle。

### May the 4th段：

-   ^： 当^在同行左侧时d^
-   t： 当t在第2行右侧时dt!

完成后获得指令{}。花括号{}会以段落为单位进行跳转。向下进入下一个puzzle。

### You can measure段：

-   )
-   2)
-   (
-   2)
-   )

完成后向下，\])，进入下一个puzzle。

### for (i=‘a’;段

-   3\]：d3\]}
-   2\[：2b d2\[{
-   3k 获得金色钥匙

完成后向上原路返回，进入下一个puzzle。

### These are not段：

-   } $：第1行d} d$
-   {：第2行d{
-   F T：第1行$，dFt dTT

完成后获得棕色钥匙，向下进入下一个puzzle。

### \* { margin段：

-   } }
-   3：3出现在前两行时d3$
-   \]}：d\]}
-   F：F出现在position段的第一行时dFp
-   3}进入下一段
-   k l：dk k d99l
-   \[{：d\[{
-   完成后出现棕色宝箱，使用棕色钥匙打开后获得指令i a。这里的i a不再是insert和append，而是作为d y c操作的一部分，对block或者段落进行定位的定位符。在这种情况下，i代表inner，a代表an object。详细地说，di(指删除(内的所有内容但不包括括号本身，而da(则会删除包括括号在内的括号括起来的所有内容。常见的object有括号（包括() \[\] {} <>），引号（包括单双引号），word，WORD，sentence，paragraph等。

向上使用金色钥匙开门后进入下一个puzzle。

### for (int i=0;段

-   2a}：d2a}
-   ap：dap
-   a( i(：第一行()中da( di(
-   a{：第一行最后da{
-   第3行最后一个)处ci) (I+1)\*(j+1) <Esc>
-   3j ca\[ endl <Esc>

完成后获得红色钥匙。向右进入下一个puzzle。

### <!DOCTYPE html>段：

-   W 2j ci< head <Esc>
-   j c2a\[ <scropt> <Esc>
-   4j ci{ （注意此处开头有两个空格）alert(‘Hello World!’); <Esc>
-   G 4k dap di( di\_ d%

完成后回到开头处，使用蓝色钥匙打开大门进入下一个puzzle。

### yoda段：

-   i"：di"
-   3个a"：gg 每一行da"
-   gg t" ci" No! <Esc>
-   4G ci’ do not. <Esc>

完成后获得第二把红色钥匙。向上右下后找到两个红色大门，使用红色钥匙打开右边大门后进入下一个puzzle。

### In the段：

这段是不能使用i a进入Insert模式的，只能使用复制粘贴完成。

-   fh yaw
-   2j P
-   b j P
-   2k p
-   b 2j 2w 6j yiw
-   j P
-   gg fh 3j 3w j 2yaw
-   6j 6j p j p

完成后获得指令.。指令.会重复最近一次进行的修改，是批量处理字符的好方法。使用红色钥匙打开左侧大门，进入下一个puzzle。

### LeChuck?段：

-   dis
-   dap

完成后向下进入下一个puzzle。

### function段：

-   % di)
-   B 2j ciw isOver <Esc>
-   2j .
-   3j .

完成后获得蓝色钥匙，向下进入下一个puzzle。

### 1 2 3 4 5段：

-   2w cwFizz <Esc>
-   3G .
-   3w .
-   4w .
-   gg $ ciw Buzz <Esc>
-   2j .
-   2j . b iFizz <Esc>

完成后进入下一个puzzle。

### One little段：

-   2w \*
-   c$ Indians <Esc>
-   2n .
-   n .
-   n .
-   2n .
-   n .
-   n ct. Indian boy <Esc>
-   n . as <Esc>

完成后使用蓝色钥匙打开大门，和皇冠紫发小人对话，按Esc进入第十四关。

## Level 13

由于对数字13的迷信。。。这关不存在。。。

## Level 14

进入第14关会发现，所有的移动指令都不能使用了。所有能用的指令只有y c d z等几个。

-   首先zz将视角调整至正中，发现本段开始处有指令H。yap取得指令。H可以在不滚动屏幕的状态下，将光标移动至当前屏幕显示的第1行。
-   再次zz调整视角，发现首行有指令L。H取得指令。指令L则是光标跳转至屏幕显示的最后一行。
-   不断使用zt zz 和L可以到达全文最后，重新获得数字指令。
-   当<count>G不能使用的时候，:<count>可以同样起到跳转至某行的作用。
-   :47跳转至47行，获得设定nu nonu。:set nu可以打开行号显示，在Vim中，行号是默认不显示的，如果需要显示则需要每次进入Vim后:set nu。如果想要默认进入Vim即显示行号，则需要修改~/.vimrc配置文件，在配置文件中写入set nu即可。
-   打开行号后使用冒号+数字跳转至每行的开头，27行获得指令M。M类似于H和L，是跳转至屏幕当中一行。41行获得指令|。|是跳转是每行的第几列。
-   :reg打开寄存器，发现下一步的提示内容：“Directions are in the ground buffer”，使用:ls查看buffer，发现ground对应编号为1，使用:b1跳转至ground buffer。
-   zb调整视角，看到提示1：在41行开始，zt调整视角，看到提示2：查看33行39列，zz调整视角，看到提示3：在两个"brute"正中间的行第47列，提示4：结尾倒数第4个pro。
-   :b4跳转回lorem，由于41行的指令|已经获得，因此直接根据提示2，:33 39|，获得指令/,?。指令/可以对全文进行搜索，相当于常见的Ctrl+F，而？则是从文末开始搜索。
-   /burte <Enter>查找到两个burte一个在第3行一个在第19行，因此需要到达11行47列。:11 47|获得指令\`。\`指令可以跳转至有特定标记的地方，使用:marks可以看到当前所有的标记。marks类似于标签，可以在文中任意标记，使用\`加上标记名可以随时进行快速跳转。
-   :52 4?pro <Enter>到达第37行最后，68|到pro前一个位置，打开传送门。
-   在前面的行动中，可以看到有一些不同颜色闪烁的方块，一个白色，一个蓝色。使用搜索/White /Blue到达。
-   /White <Enter>，发现可以对话，白色的就是Mr.White，使用数字选择回应的内容。和Mr.White对话可以了解到局部标记（local marks）的相关信息，同时Mr.White说如果要了解关于全局标记（global marks）的信息需要找到Mr.Blue。当问到如何使用marks消灭Big Bug时，Mr.White说需要把所有的标记放在对应的位置，具体的细节可以问Mr.Red。
-   /Blue <Enter>和Mr.Blue对话，Mr.Blue提供了更多之前关于消灭Big Bug时的情况，其中说到Mr.Pink无法控制自己时会变化哦那个，这也是导致之前消灭Big Bug失败的原因。同样Mr.Blue也说到需要将marks放在指定的位置才可以消灭Big Bug，剩余的内容需要问Mr.Red。
-   /Pink <Enter>发现Mr.Pink在前一个位置，64|和Mr.Pink对话，了解到:marks可以显示所有的marks，而:delm指令可以删除已存在的marks。和Mr.Pink对话时Mr.Pink会请求原谅，选择对话1不原谅他，Mr.Pink会继续恳求，始终选择No，三次以后会发现Mr.Pink变成了Mr.Red，然后再了解关于Big Bug的事，发现sky buffer有关于如何在underground buffer设置marks从而消灭Big Bug的提示。
-   :b2到达sky buffer，\`W到达W mark。

### W Mark：

-   9| d/clever <Enter>
-   :2 13| d/\\. <Enter>（因为.作为一个正则表达式的成分，在这里需要使用反斜杠\\进行转义）
-   5| 获得指令<Ctrl>-R，这个指令就是用来就是撤销撤销的操作，类似于Ctrl+Z后再取消撤销
-   \`H到达H mark

### H Mark：

-   :delm! 清除所有的局部标记
-   :4 <Enter> 30|到达最后完成puzzle
-   ?’ <Enter> 获得指令’。指令‘可以跳转至指定marks所在行的第一个非空字符。
-   'A到达A mark的首字符

### A Mark：

-   ?! 到达最后
-   d’A 消灭所有的bugs
-   3?m <Enter>获得指令m。使用指令m就可以在指定的位置设置标记。
-   \`D到达D mark

### D Mark：

-   :delm Dthe <Enter>
-   2| mo
-   ?<space>o <Enter> mM
-   ? <Enter> my
-   ? <Enter> me
-   :7 7| 获得星星

:b4 回到lorem buffer，找到之前打开的传送门:37 68|，mB /g <Enter> mg /i <Enter> mi /u <Enter> mu设置4个标记。完成后出现棕色箱子。

-   :reg打开寄存器，发现"y给出第2个提示，在sky buffer的W和Y当中。
-   \`W \`Y，但是不要打断画面滚动过程，可以发现提示"Toadstool (Peach is also interesting…)"。
-   ·P到达P mark
-   :marks 显示所有的marks，再使用:marks Toadstool显示特定的几个marks获得提示：“The power of undo will beat Big Bug”，同时:5 <Enter>在第5行获得棕色钥匙。（:marks Peach可以看到另一个提示：“The cursors are NOT friends!”）
-   \`B 9|打开棕色宝箱，获得指令u。指令u就是常见的撤销命令。同时之前所有的指令都再次可以使用了。
-   \`U <Ctrl>-R恢复修改前的内容，给出新的提示：3个bugs伪装成了光标，需要记住名字"Uganda" “Bram"和"Charity”。（这其实是一个彩蛋，打开原生Vim出现的界面就是这个Charity关于援助乌干达儿童的项目）。
-   :b3到达underground buffer进入Boss战。

### Underground Buffer：

-   先mB /g <Enter> mg /i <Enter> mi /u <Enter> mu设置4个标记，完成后会出现Big Bug和三个小弟，也就是之前遇到的Mr.White Mr.Blue和Mr.Red，对应之前的提示：“The cursors are NOT friends!”。
-   被任何一个碰到就会被弹回lorem buffer，但是之前的状态不会消失。可以先在lorem buffer中搜索"Uganda" “Bram"和"Charity”，然后回到underground buffer重复/<Enter> ?<Enter>消灭"Uganda" "Bram"和"Charity"三个小弟后专心对付Big Bug。
-   要对Big Bug造成伤害需要使用指令u和Ctrl-R，可以用99u 99Ctrl-R造成大量伤害，同时用0 $ gg G {}躲避Big Bug。
-   当Big Bug被消灭以后，使用99Ctrl-R撤销所有修改后通关。

![[99-Attachment/ce1047f58a1e2ba692eaa38fd61f8eea_MD5.png]]  
最后放一个统计图~

![[99-Attachment/98f593ed8b962eec2638c5141649f90d_MD5.png]]

## 总结

Vim Adventures对于入门Vim是非常好的学习工具。非常详尽地讨论了Normal mode和Insert Mode下的操作和使用，也少量地涉及了Command Mode，唯一美中不足是没有涉及关于Visual Mode的部分，不过相信通过了整个关卡的训练，玩家已经对Vim有了手感，剩下的就是自己的摸索和锻炼了。

## 彩蛋

Git是现在最流行的版本管理工具，相关的介绍这里不多提供。在这里给出一个学习git非常好的网站，和Vim Adventures一样，同样是用游戏的方式学习。

网址如下：[Learn Git Branching](https://learngitbranching.js.org/)： https://learngitbranching.js.org/

相比于Vim Adventures，Learn Git Branching全部免费并且有完全的中文翻译，对于新人非常友好。只需要1-2个小时就可以对git的常用指令如：

-   git commit 提交
-   git branch 建立分支
-   git merge/ git rebase 合并分支
-   git clone 复制自远程仓库
-   git fetch 获取远程提交
-   git pull 获取并合并远程提交
-   git push 提交至远程仓库

等能有一个直观的理解和记忆。

### 本地git仓库题目

![[99-Attachment/ea718093c6a4b0f50a7736e5b80193cf_MD5.png]]

### 远程git仓库题目

![[99-Attachment/c5089e7048b2cecb87a6202f6501c7c1_MD5.png]]

### 完成

![[99-Attachment/bc3ab53be35fd55c6ad450d4fd63731f_MD5.png]] 
由于题目难度不大且有官方答案提供，因此就不多做赘述，仅做一个小小的安利。

以上，完结撒花~