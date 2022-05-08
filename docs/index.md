# 白泽史料库-冷战

本文件夹下保存的是1945-1999的历史时期的大事件。

本文件夹的主题是“意识形态冲突下的世界”，包括1945-1991年的冷战冲突，1991-1999的20世纪最后十年的历史大事。

本文件夹的定位是【工具类】，仅供学术参考以及了解历史使用，对任意历史事件评价的视角详见下面的【研究视角】

**本文件夹首先是笔记，这就不可避免造成了叙事时候带有很强的主观色彩；写这个笔记的时候又是以【公开的笔记】来写的，因此又有一点可读性，但总体上还是比较混乱的**

### 简介

二战结束之后，以美国为首的西方资本主义世界和以苏联为首的社会主义阵营开始逐渐走向对立。

随着核武器的强大威力展现，双方在冲突之中尽量避免了直接的热武器冲突，采用以政治宣传、经济作战、文化渗透等一系列“冷冲突”手段进行对抗，因此这段时期称之为冷战。

冷战的主导思维是“零和博弈”，双方的大部分行动出发点都是置对方于不利的目的展开的。为此“地缘政治”、“谍报战”、“代理人战争”以及“颜色革命”等开始成为各国外交、情报的手段受到空前重视。

冷战的结束标志一般认为是苏联解体事件，但之后造成的大量战争和政治动荡我们认为有必要一并介绍。

### 研究视角

西方学者研究冷战视角大部分是根据地缘政治和上层建筑叙事来进行研究。

本文件夹分为两个部分

1. 第一部分将会**单纯**讲述冷战期间的大事件，所有的大事件只会给予尽可能少的评价。评价的角度将会从中文互联网主流视角给出，以此作为参考。
2. 第二部分将会通过政治经济学来阐述部分重大事件背后各方势力行动的经济上动机。

## Material color palette 颜色主题

### Primary colors 主色

> 默认为 `white`

点击色块可更换主题的主色

<center>
<div id="color-button">
<button data-md-color-primary="red">Red</button>
<button data-md-color-primary="pink">Pink</button>
<button data-md-color-primary="purple">Purple</button>
<button data-md-color-primary="deep-purple">Deep Purple</button>
<button data-md-color-primary="indigo">Indigo</button>
<button data-md-color-primary="blue">Blue</button>
<button data-md-color-primary="light-blue">Light Blue</button>
<button data-md-color-primary="cyan">Cyan</button>
<button data-md-color-primary="teal">Teal</button>
<button data-md-color-primary="green">Green</button>
<button data-md-color-primary="light-green">Light Green</button>
<button data-md-color-primary="lime">Lime</button>
<button data-md-color-primary="yellow">Yellow</button>
<button data-md-color-primary="amber">Amber</button>
<button data-md-color-primary="orange">Orange</button>
<button data-md-color-primary="deep-orange">Deep Orange</button>
<button data-md-color-primary="brown">Brown</button>
<button data-md-color-primary="grey">Grey</button>
<button data-md-color-primary="blue-grey">Blue Grey</button>
<button data-md-color-primary="white">White</button>
</div>
</center>

<script>
  var buttons = document.querySelectorAll("button[data-md-color-primary]");
  Array.prototype.forEach.call(buttons, function(button) {
    button.addEventListener("click", function() {
      document.body.dataset.mdColorPrimary = this.dataset.mdColorPrimary;
      localStorage.setItem("data-md-color-primary",this.dataset.mdColorPrimary);
    })
  })
</script>

### Accent colors 辅助色

> 默认为 `red`

点击色块更换主题的辅助色

<center>
<div id="color-button">
<button data-md-color-accent="red">Red</button>
<button data-md-color-accent="pink">Pink</button>
<button data-md-color-accent="purple">Purple</button>
<button data-md-color-accent="deep-purple">Deep Purple</button>
<button data-md-color-accent="indigo">Indigo</button>
<button data-md-color-accent="blue">Blue</button>
<button data-md-color-accent="light-blue">Light Blue</button>
<button data-md-color-accent="cyan">Cyan</button>
<button data-md-color-accent="teal">Teal</button>
<button data-md-color-accent="green">Green</button>
<button data-md-color-accent="light-green">Light Green</button>
<button data-md-color-accent="lime">Lime</button>
<button data-md-color-accent="yellow">Yellow</button>
<button data-md-color-accent="amber">Amber</button>
<button data-md-color-accent="orange">Orange</button>
<button data-md-color-accent="deep-orange">Deep Orange</button>
</div>
</center>

<script>
  var buttons = document.querySelectorAll("button[data-md-color-accent]");
  Array.prototype.forEach.call(buttons, function(button) {
    button.addEventListener("click", function() {
      document.body.dataset.mdColorAccent = this.dataset.mdColorAccent;
      localStorage.setItem("data-md-color-accent",this.dataset.mdColorAccent);
    })
  })

  // #758
  document.getElementsByClassName('md-nav__title')[1].click()
</script>