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

### Color Scheme 配色方案

根据浏览器与系统设置自动切换明暗主题，也可手动切换
<div class="tx-switch">
<button data-md-color-scheme="default"><code>Default</code></button>
<button data-md-color-scheme="slate"><code>Slate</code></button>
</div>
<script>
  var buttons = document.querySelectorAll("button[data-md-color-scheme]")
  Array.prototype.forEach.call(buttons, function(button) {
    button.addEventListener("click", function() {
      document.body.dataset.mdColorScheme = this.dataset.mdColorScheme;
      localStorage.setItem("data-md-color-scheme",this.dataset.mdColorScheme);
    })
  })
</script>

### Primary colors 主色

点击色块可更换主题的主色，默认为`Pink`
<div class="tx-switch">
<button data-md-color-primary="red"><code>Red</code></button>
<button data-md-color-primary="pink"><code>Pink</code></button>
<button data-md-color-primary="purple"><code>Purple</code></button>
<button data-md-color-primary="deep-purple"><code>Deep Purple</code></button>
<button data-md-color-primary="indigo"><code>Indigo</code></button>
<button data-md-color-primary="blue"><code>Blue</code></button>
<button data-md-color-primary="light-blue"><code>Light Blue</code></button>
<button data-md-color-primary="cyan"><code>Cyan</code></button>
<button data-md-color-primary="teal"><code>Teal</code></button>
<button data-md-color-primary="green"><code>Green</code></button>
<button data-md-color-primary="light-green"><code>Light Green</code></button>
<button data-md-color-primary="lime"><code>Lime</code></button>
<button data-md-color-primary="yellow"><code>Yellow</code></button>
<button data-md-color-primary="amber"><code>Amber</code></button>
<button data-md-color-primary="orange"><code>Orange</code></button>
<button data-md-color-primary="deep-orange"><code>Deep Orange</code></button>
<button data-md-color-primary="brown"><code>Brown</code></button>
<button data-md-color-primary="grey"><code>Grey</code></button>
<button data-md-color-primary="blue-grey"><code>Blue Grey</code></button>
<button data-md-color-primary="white"><code>White</code></button>
</div>
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

点击色块更换主题的辅助色，默认为`red`
<div class="tx-switch">
<button data-md-color-accent="red"><code>Red</code></button>
<button data-md-color-accent="pink"><code>Pink</code></button>
<button data-md-color-accent="purple"><code>Purple</code></button>
<button data-md-color-accent="deep-purple"><code>Deep Purple</code></button>
<button data-md-color-accent="indigo"><code>Indigo</code></button>
<button data-md-color-accent="blue"><code>Blue</code></button>
<button data-md-color-accent="light-blue"><code>Light Blue</code></button>
<button data-md-color-accent="cyan"><code>Cyan</code></button>
<button data-md-color-accent="teal"><code>Teal</code></button>
<button data-md-color-accent="green"><code>Green</code></button>
<button data-md-color-accent="light-green"><code>Light Green</code></button>
<button data-md-color-accent="lime"><code>Lime</code></button>
<button data-md-color-accent="yellow"><code>Yellow</code></button>
<button data-md-color-accent="amber"><code>Amber</code></button>
<button data-md-color-accent="orange"><code>Orange</code></button>
<button data-md-color-accent="deep-orange"><code>Deep Orange</code></button>
</div>
<script>
  var buttons = document.querySelectorAll("button[data-md-color-accent]");
  Array.prototype.forEach.call(buttons, function(button) {
    button.addEventListener("click", function() {
      document.body.dataset.mdColorAccent = this.dataset.mdColorAccent;
      localStorage.setItem("data-md-color-accent",this.dataset.mdColorAccent);
    })
  })
</script>

<style>
button[data-md-color-accent]> code {
    background-color: var(--md-code-bg-color);
    color: var(--md-accent-fg-color);
  }
button[data-md-color-primary] > code {
    background-color: var(--md-code-bg-color);
    color: var(--md-primary-fg-color);
  }
button[data-md-color-primary='white'] > code {
    background-color: var(--md-primary-bg-color);
    color: var(--md-primary-fg-color);
  }
button[data-md-color-accent],button[data-md-color-primary],button[data-md-color-scheme]{
    width: 8.4rem;
    margin-bottom: .4rem;
    padding: 2.4rem .4rem .4rem;
    transition: background-color .25s,opacity .25s;
    border-radius: .2rem;
    color: #fff;
    font-size: .8rem;
    text-align: left;
    cursor: pointer;
}
button[data-md-color-accent]{
  background-color: var(--md-accent-fg-color);
}
button[data-md-color-primary]{
  background-color: var(--md-primary-fg-color);
}
button[data-md-color-scheme='default']{
  background-color: hsla(0, 0%, 100%, 1);
}
button[data-md-color-scheme='slate']{
  background-color: var(--md-default-bg-color);
}
button[data-md-color-accent]:hover, button[data-md-color-primary]:hover {
    opacity: .75;
}
</style>

## 致谢

感谢 [OI Wiki](https://oiwiki.org/) 和 [CTF Wiki](https://ctf-wiki.org/) 给的 Material of Mkdocs 主题更改部分的代码参考。同时感谢笔者之一的几位一起讨论政治历史的高中同学们。对历史上的所有先贤们在人类文明所作出的探索和奉献表达最大的敬意。