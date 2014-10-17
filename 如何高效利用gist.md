# 如何充分利用Gist？
Github作为代码分享平台在开发者中非常流行。此平台托管了包括游戏、书籍以至于字体在内的一千两百多万个项目，这使其成为互联网上最大的代码库。  

Github还提供另一个非常有用的功能，这就是Gist。  

开发人员常常使用Gist记录他们的代码片段，但是Gist不仅仅是为极客和码农开发的，每个人都可以用到它。 如果你听说过类似Pastebin或者Pastie这样的网页应用的话，那我们就可以看出它们和Gist很像，但是Gist比它们要更优雅。因为这些免费应用一般含有广告，而且带有很多其他杂七杂八的功能。  

**Gist - 任何人都能用得着**  

在以下几个方面你不是极客也可以用到Gist。  

### 1. 匿名张贴  
你不需要拥有Github账号就可以使用Gist。用浏览器打开gist.github.com，在窗口中写下你想说的就可以创建一个Gist。你可以发布一个私密的Gist，也就是说这个Gist将不会被他人搜索到而只对直接在浏览器中输入URL的人可见。    

### 2. 能像wiki一样记录历史  
如果你修改已经发布了的Gist的话之前的所有版本都将被保存。你可以点击Revisions按钮按时间浏览，而且你可以通过内置的diff引擎查看任意两个版本间的差异。 这也可以用于比较文本文件。  

### 3. 发布富文本内容  
虽然Gist只能用纯文本来写，但是你可以用markdown来发布html格式的Gist。你可以添加列表、图片（已有图床上的）和表格。当你用markdown的时候不要忘了文件名要以.md为后缀。  

### 4. 把Gist当作一个写作平台  
虽然现在有很多写作引擎，比如Blogger、Medium、Tumblr，但你还可以用Gist来快速发布你的文字。你可以用纯文本或者markdown等文档标记语言些一个Gist然后用roughdraft.io来把它作为一个独立的网页发布。

### 5. 托管gist上的单个页面
Bl.ocks 是一个非常有趣的专为Gist开发的应用。  

你可以用纯文本把HTML、CSS、JavaScript代码写下来以index.html为文件名保存为Gist，然后用bl.ocks.org把渲染好的结果在浏览器中展示出来。比如，这个[gist](https://gist.github.com/labnol/122d4de95c6a127b1c9b)展示出来就是[这样](http://bl.ocks.org/labnol/raw/122d4de95c6a127b1c9b/)。  

显然宽带限制是一个问题，但是bl.ock.org作为一个通过Gist托管HTML的工具仍然是相当不错的。 当然你也可以用[Google Drive](http://www.labnol.org/internet/host-website-on-google-drive/28178/)。    

### 6. 制作任务列表
你可以用Gist跟踪待处理任务（[举个栗子](https://gist.github.com/labnol/8e1cdf64cd7b0c1a811e)）。这是用纯文本的特殊语法写的但是你可以任意勾选。  
```
- [x] Pick the flowers
- [ ] Call John 9303032332
- [x] Cancel cable subscription
- [ ] Book the flight tickets  
```
你可以勾选或者勾去任意选项，源文本将会自动变更。如果你的Gist是共有的的话，任何人都可以看到你的列表，但是只有你（拥有者）可以改变其勾选状态。  

### 7. 把Gist作为一个网页收藏夹  
在Chrome浏览器你可以找到一个叫GistBox的插件，通过这个插件你可以在浏览网页时选择保存网页内容为Gist。你甚至可以添加标注或者话题标签以易于以后更容易找到它。  

### 8. 把Gist嵌入网页中  
你可以用一行js代码就可以把任何一条Gist嵌入到网页中。嵌入的Gist格式不发生任何变化，而且访问者可以非常方便的把它们fork到他们的Github中。要嵌入wordpress的话有这个[插件](http://wordpress.org/plugins/oembed-gist/)和[短代码](http://en.support.wordpress.com/gist/)可以使用。  
` <script src="https://gist.github.com/username/gist-id.js"></script> `   
 
### 9. 测量访问量  
你可以使用Google Analytics查看你的Gist的访问量。因为Gist纯文本中不允许运行js代码，所以我们可以用[GA Beacon](https://github.com/igrigorik/ga-beacon)来记录实时访问Gist的情况。  
把如下代码添加到Gist中，用markdown格式保存，这样就在这个Gist中添加了一个透明追踪图像。  
 `![Analytics](https://ga-beacon.appspot.com/UA-XXXXX-X/gist-id?pixel) `   

### 10. 在桌面端管理Gist
Gisto是一个能让您在浏览器之外管理Gist的桌面应用。您可以对Gist进行搜索、编辑、查看历史和分享。 此应用可运行于苹果、微软和linux系统。 当然您也可以用GistBox这个web应用替代它。  

- - - - - - 
[翻译原文](https://github.com/eduOSS/Translations/edit/master/%E5%A6%82%E4%BD%95%E9%AB%98%E6%95%88%E5%88%A9%E7%94%A8gist.md)/[英文原文](http://www.labnol.org/internet/github-gist-tutorial/28499/)
