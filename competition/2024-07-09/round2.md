## 垃圾庄
第二轮最后一副，成为了全场唯一做宕3NT的人。

<div class="board-container">
  <div class="Whand">
    <font color="0000C0">♠</font> 963 <br>
    <font color="E80000">♥</font> J5 <br>
    <font color="FF6000">♦</font> 6542 <br>
    <font color="00A000">♣</font> A982 <br>
  </div>
	<div class="Ehand">
	  <font color="0000C0">♠</font> KQJ <br>
    <font color="E80000">♥</font> AQ432 <br>
    <font color="FF6000">♦</font> AKJ <br>
    <font color="00A000">♣</font> T6 <br>
  </div>
</div>

E-W有局，叫牌进程很简单 
<table>
    <tr><td>WEST</td> <td>NORTH</td> <td>EAST</td> <td>SOUTH</td></tr>
    <tr><td>pass</td> <td>pass</td> <td>1H</td> <td>pass</td></tr>
    <tr><td>1NT</td> <td>pass</td> <td>3NT</td> <td>AP </td></tr>
</table>

北家首攻S4，南家跟ST（大欢迎）。

这个3NT看上去并不是很好打。现在赢墩有1墩H2墩D1墩C1墩S，S还有一墩先算上也就是有6墩。看上去是有两条路，H33或南家KX双张；或者南家H有K加D飞中且33的话也能打成。看上去H33显然是更好的选择，但有兼顾的打法吗？
我在桌上选择了这样一条路线，拔一下DA，看看有没有DQ掉落，两边跟出了3和7。从明手出H，南家很快地跟出H6，暗手出J大了，北家跟H9。
现在如何打牌？

其实这就是一个概率计算的问题。
首先，让我们达成一些共识以便接下来的分析。

① 由于南家飞快地跟H6，看上去他的H不会是K6。<br/>
② S应该不会坏于5-2，而且由于南家已经持有HK，如果他持有SATXXX，以及一张潜在的C大牌（北家没有从CKQJ中首攻顶张），他有可能借着无局方出来争叫1S。又因为北家如果SA4应该首攻SA，所以南家不会持有5张S。

1. 只考虑H，应该是只有H33 36%的机会。
2. 另一种方法——由于暗手仅有CA一个桥，要打D33飞中只有现在出D一个机会。如果这样打，飞中的话，可以先试D33再试H33。概率上有50%*(36%+36%)=36%成功。如果飞脱，则情况变得很复杂。
假设南家的防守还行，<br/>
	2.1 他在吃到D后可能回S，这样的话还能再试H33——最终丢2墩S1墩H1墩D完成3NT。（如果S5-2那么S断桥，S4-3则丢2墩S）<br/>
	2.2 他在吃到D后可能回C，这样的话情况更加复杂，可能也有一些概率能够打成，姑且不在意了。<br/>
	2.3 他在吃到D后可能回D，这表明了他有四张D，这样的话还能再试H33——最终丢2墩D1墩H1墩S完成3NT。<br/>

怎么看都是后者更优。好了，一张D出去，定约已经完蛋。

以下四明手
<div class="board-container">
  <div class="Nhand">
    <font color="0000C0">♠</font> A8542 <br>
    <font color="E80000">♥</font> T97 <br>
    <font color="FF6000">♦</font> 7 <br>
    <font color="00A000">♣</font> QJ75 <br>
  </div>
  <div class="Shand">
    <font color="0000C0">♠</font> T7 <br>
    <font color="E80000">♥</font> K86 <br>
    <font color="FF6000">♦</font> QT983 <br>
    <font color="00A000">♣</font> K43 <br>
  </div>
  <div class="Whand">
    <font color="0000C0">♠</font> 963 <br>
    <font color="E80000">♥</font> J5 <br>
    <font color="FF6000">♦</font> 6542 <br>
    <font color="00A000">♣</font> A982 <br>
  </div>
	<div class="Ehand">
	  <font color="0000C0">♠</font> KQJ <br>
    <font color="E80000">♥</font> AQ432 <br>
    <font color="FF6000">♦</font> AKJ <br>
    <font color="00A000">♣</font> T6 <br>
  </div>
</div>

问题在哪？<br/>
事实上，第二种方法所有的再试H33，都基于对手没回出C，或者说，防守失误，但是分析错误的原因在于S。一开始的计算已经把S计算为了两墩，但实际上为了这两墩，还得再脱手一次（如果防守方不犯错的话）。这也就导致了即使飞中D，然后砸33，一旦D24；就会在试H33的过程中输墩先到位（C2D1H1S1）。D是这牌的陷阱，这牌实际上只能试H33。

http://www.bridgeconex.com/MatchInfo.aspx?type=31&matchid=20503&rsnum=200&num=16