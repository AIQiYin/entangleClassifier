
### hello



<h1 style="font-size:2.5em; margin:1em 0px 15px; line-height:1.7; padding:0px; position:relative; border-bottom-width:1px; border-bottom-style:solid; border-bottom-color:rgb(221,221,221); color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif">
使用 GitHub, Jekyll 打造自己的免费独立博客</h1>
<p style="margin-top:15px; margin-bottom:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
<a target="_blank" target="_blank" href="https://github.com/" style="color:rgb(65,131,196); text-decoration:none">GitHub</a>是一个代码托管网站，现在很多开源项目都放在GitHub上。 利用GitHub，可以让全球各地的程序员们一起协作开发。GitHub 提供了一种功能，叫&nbsp;<a target="_blank" target="_blank" href="https://help.github.com/categories/20/articles" style="color:rgb(65,131,196); text-decoration:none">GitHub
 Pages</a>, 利用这个功能，我 们可以为项目建立网站，当然，这也意味着我们可以通过 GitHub Pages 建立自己的网站。</p>
<p style="margin-top:15px; margin-bottom:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
<a target="_blank" target="_blank" href="http://jekyllrb.com/" style="color:rgb(65,131,196); text-decoration:none">Jekyll</a>是一个简单的，针对博客设计的静态网站生成器。使用 GitHub 和 Jekyll，我们可以打造自己的独立博客，你可以自由地定制网站的风&#26684;，并且这 一切都是免费的。</p>
<p style="margin-top:15px; margin-bottom:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
这是我在GitHub上自己建立的<a target="_blank" target="_blank" href="http://minixalpha.github.io" style="color:rgb(65,131,196); text-decoration:none">博客</a>&nbsp;及<a target="_blank" target="_blank" href="https://github.com/minixalpha/minixalpha.github.io" style="color:rgb(65,131,196); text-decoration:none">源代码</a>&nbsp;（两个分支），在下文的讲解中，你可以随时查看博客的源代码，以便有直观的认识。</p>
<p style="margin-top:15px; margin-bottom:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
网站截图：</p>
<p style="margin-top:15px; margin-bottom:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
<img src="http://img.blog.csdn.net/20140215230442406?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvb25fMXk=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast" alt=""><br>
</p>
<h2 style="margin:1em 0px 15px; line-height:1.7; font-size:2em; padding:0px; position:relative; border-bottom-width:1px; border-bottom-style:solid; border-bottom-color:rgb(238,238,238); color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif">
<a target="_blank" target="_blank" name="%E5%85%A5%E9%97%A8%E6%8C%87%E5%BC%95" class="anchor" href="https://github.com/minixalpha/StrayBirds/blob/master/_posts/2014-02-15-github-jekyll-markdown.md#%E5%85%A5%E9%97%A8%E6%8C%87%E5%BC%95" style="color:rgb(65,131,196); text-decoration:none; display:block; padding-right:6px; padding-left:30px; margin-left:-30px; position:absolute; top:0px; left:0px; bottom:0px"></a>入门指引</h2>
<p style="margin-top:15px; margin-bottom:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
GitHub Pages 的&nbsp;<a target="_blank" target="_blank" href="http://pages.github.com/" style="color:rgb(65,131,196); text-decoration:none">主页</a>&nbsp;提供了一个简单的入门指引，阅读并 操作一下，会有一个直观简单的认识。</p>
<p style="margin-top:15px; margin-bottom:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
阮一峰的文章《<a target="_blank" target="_blank" href="http://www.ruanyifeng.com/blog/2012/08/blogging_with_jekyll.html" style="color:rgb(65,131,196); text-decoration:none">搭建一个免费的，无限流量的Blog----github Pages和Jekyll入门</a>》是使用 GitHub 和 Jekyll 搭建独立博客非常好的入门文章，<span style="">强烈建议先阅读并操作一遍</span>。</p>
<h2 style="margin:1em 0px 15px; line-height:1.7; font-size:2em; padding:0px; position:relative; border-bottom-width:1px; border-bottom-style:solid; border-bottom-color:rgb(238,238,238); color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif">
<a target="_blank" target="_blank" name="%E5%BB%BA%E7%AB%8B%E8%87%AA%E5%B7%B1%E7%9A%84%E5%8D%9A%E5%AE%A2" class="anchor" href="https://github.com/minixalpha/StrayBirds/blob/master/_posts/2014-02-15-github-jekyll-markdown.md#%E5%BB%BA%E7%AB%8B%E8%87%AA%E5%B7%B1%E7%9A%84%E5%8D%9A%E5%AE%A2" style="color:rgb(65,131,196); text-decoration:none; display:block; padding-right:6px; padding-left:30px; margin-left:-30px; position:absolute; top:0px; left:0px; bottom:0px"></a>建立自己的博客</h2>
<p style="margin-top:15px; margin-bottom:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
在学习完阮一峰同学的文章后，你就已经有能力搭建自己的独立博客了，但是这个博客 只有最基本的功能，并且也不好看。这时候，你面临几个选择:</p>
<ol style="padding:0px 0px 0px 30px; margin:15px 0px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
<li style="">完全自己定制博客</li><li style="">找一份框架，修改后使用</li><li style="">从GitHub上fork别人的博客代码，在其中添加自己的文章</li></ol>
<p style="margin-top:15px; margin-bottom:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
如果选择 2, 那么&nbsp;<a target="_blank" target="_blank" href="http://jekyllbootstrap.com/" style="color:rgb(65,131,196); text-decoration:none">jekyll-bootstrap</a>是一个选择。&nbsp;</p>
<p style="margin-top:15px; margin-bottom:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
如果选择 3, 那么自己Google一下&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">github.io
 博客</code>&nbsp;能找到不少博客,去fork,然后修改一下就好。 最近有一个 <a target="_blank" target="_blank" href="https://github.com/barryclark/jekyll-now">
jekyll-now</a>，在 GitHub 上已经获取了 1000&#43; 的fork，可以关注一下。这个项目的特点是，所有操作都是通过网站进行的，不需要懂命令行。另外， 我自己也有一个非常简洁的项目，也不需要懂命令行，直接通过网页操作，就可以有一个自己的博客了。如果只需要这一个简单的博客，可以直接看最后一节:<a target="_blank" target="_blank" href="#t8">一个极简风&#26684;的博客</a>。</p>
<p style="margin-top:15px; margin-bottom:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
如果选择 1, 那么可以好好看看后文的内容。</p>
<h2 style="margin:1em 0px 15px; line-height:1.7; font-size:2em; padding:0px; position:relative; border-bottom-width:1px; border-bottom-style:solid; border-bottom-color:rgb(238,238,238); color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif">
<a target="_blank" target="_blank" name="github--jekyll-%E5%B7%A5%E4%BD%9C%E6%9C%BA%E5%88%B6" class="anchor" href="https://github.com/minixalpha/StrayBirds/blob/master/_posts/2014-02-15-github-jekyll-markdown.md#github--jekyll-%E5%B7%A5%E4%BD%9C%E6%9C%BA%E5%88%B6" style="color:rgb(65,131,196); text-decoration:none; display:block; padding-right:6px; padding-left:30px; margin-left:-30px; position:absolute; top:0px; left:0px; bottom:0px"></a>GitHub
 &#43; Jekyll 工作机制</h2>
<ul style="padding:0px 0px 0px 30px; margin:15px 0px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
<li style="">机制一&nbsp;</li></ul>
<span style="color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.4545450210571px; line-height:23.1818180084229px"></span>
<ol>
<li><span style="font-size:15.4545450210571px; line-height:23.1818180084229px">&nbsp;</span><span style="font-size:15.4545450210571px; line-height:23.1818180084229px">&nbsp;</span><span style="font-size:15.4545450210571px; line-height:23.1818180084229px">简单地说，你在 GitHub
 上有一个账号，名为</span><code style="font-size:12px; font-family:Consolas,'Liberation Mono',Courier,monospace; margin:0px; border:1px solid rgb(221,221,221); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap; background-color:rgb(248,248,248)">username</code><span style="font-size:15.4545450210571px; line-height:23.1818180084229px">(任意)，
 有一个项目，名为&nbsp;</span><code style="font-size:12px; font-family:Consolas,'Liberation Mono',Courier,monospace; margin:0px; border:1px solid rgb(221,221,221); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap; background-color:rgb(248,248,248)">username.github.io</code><span style="font-size:15.4545450210571px; line-height:23.1818180084229px">(固定&#26684;式，username与账号名一致)，
 项目分支名为&nbsp;</span><code style="font-size:12px; font-family:Consolas,'Liberation Mono',Courier,monospace; margin:0px; border:1px solid rgb(221,221,221); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap; background-color:rgb(248,248,248)">master</code><span style="font-size:15.4545450210571px; line-height:23.1818180084229px">(固定)，这个分支有着类&#20284;下面的
 目录结构:</span></li></ol>
<pre style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:13px; margin-top:15px; margin-bottom:15px; background-color:rgb(248,248,248); border:1px solid rgb(221,221,221); line-height:19px; overflow:auto; padding:6px 10px; word-wrap:normal; color:rgb(51,51,51)"><code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:none; background-color:transparent; display:inline; vertical-align:middle; line-height:inherit; padding:0px; word-wrap:normal">.
├── index.html
├── _config.yml
├── assets
│&nbsp;&nbsp; ├── blog-images
│&nbsp;&nbsp; ├── css
│&nbsp;&nbsp; ├── fonts
│&nbsp;&nbsp; ├── images
│&nbsp;&nbsp; └── javascripts
├── _includes
├── _layouts
├── _plugins
├── _posts
└── _site
</code></pre>
<p style="margin-top:15px; margin-bottom:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
这样，当你访问&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">http://username.github.io/</code>时，GitHub
 会使用 Jekyll 解析 用户&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">username</code>名下的<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">username.github.io</code>项目中，分支为<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">master</code>&nbsp;的源代码，为你构建一个静态网站，并将生成的&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">index.html</code>&nbsp;展示给你。</p>
<p style="margin-top:15px; margin-bottom:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
关于这个目录更多的内容，我们还不需要关心，如果你好奇心比较重，可以先看 后文<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">源代码</code>一节。</p>
<p style="margin-top:15px; margin-bottom:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
看完上面的解释，你可能会有一些疑问，因为按照上面的说法，一个用户只能有一个 网站，那我有很多项目，每个项目都需要一个项目网站，该怎么办呢？另外，在阮一峰 同学的文章中，特别提到，分支名应该为&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">gh-pages</code>，这又是怎么回事呢？</p>
<p style="margin-top:15px; margin-bottom:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
原来，GitHub认为，一个GitHub账号对应一个用户或者一个组织，GitHub会 给这个用户分配一个域名：<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">username.github.io</code>，当用户访问这个域名时，
 GitHub会去解析<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">username</code>用户下，<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">username.github.io</code>项目的<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">master</code>分支，
 这与我们之前的描述一致。</p>
<p style="margin-top:15px; margin-bottom:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
<br style="">
另外，GitHub还为每个项目提供了域名，例如，你有一个项目名为<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">blog</code>，
 GitHub为这个项目提供的域名为<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">username.github.io/blog</code>，
 当你访问这个域名时，GitHub会去解析<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">username</code>用户下，<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">blog</code>项目的<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">gh-pages</code>&nbsp;分支。</p>
<p style="margin-top:15px; margin-bottom:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
所以，要搭建自己的博客，你可以选择建立名为&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">username.github.io</code>的项目，
 在<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">master</code>分支下存放网站源代码，也可以选择建立名为&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">blog</code>&nbsp;的项目，在&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">gh-pages</code>分支下存放网站源代码。</p>
<p style="margin-top:15px; margin-bottom:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
GitHub 的 Help 文档中的&nbsp;<a target="_blank" target="_blank" href="https://help.github.com/articles/user-organization-and-project-pages" style="color:rgb(65,131,196); text-decoration:none">User, Organization and Project Pages</a>对此有 详细的描述。</p>
<ul style="padding:0px 0px 0px 30px; margin:15px 0px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
<li style="">机制二</li></ul>
<p style="margin-top:15px; margin-bottom:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
Jekyll 提供了插件功能，在网站源代码目录下，有一个名为&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">_plugins</code>的目录，
 你可以将一些插件放进去，这样，Jekyll在解析网站源代码时，就会运行你的插件， 这样插件是 Ruby 写成的。可以为Jekyll添加功能，例如，Jekyll默认是不提供分类 页面的，你可以写一个插件，根据文章内容生成分类页面。如果没有插件，你只能每 次写文章，添加分类时，为每个分类手动写 HTML 页面。</p>
<p style="margin-top:15px; margin-bottom:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
在本地运行 Jekyll 时，这些插件会自动被调用，但是GitHub在解析网站源代码时， 出于安全考虑，会开启安全模式，禁用这些插件。我们既想用这些插件，又想用 GitHub，怎么办呢怎么办呢？</p>
<p style="margin-top:15px; margin-bottom:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
GitHub还为我们提供了更一种解析网站的方式，那就是直接上传最终的静态网页， 这样，我们可以在本地使用 Jeklly 把网站解析出来，然后再上传到 GitHub上， 这就使得我们既使用了插件，又使用了 GitHub。在上文的目录结构中，有一个 名为&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">_site</code>&nbsp;的目录，这个就是Jeklly在本地解析时最终生成的静态网站，我们
 把其中的内容上传到 GitHub 的项目中就可以了。例如，我在GitHub上的网站， 既解析后的&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">_site</code>&nbsp;目录，大概是这样的:</p>
<pre style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:13px; margin-top:15px; margin-bottom:15px; background-color:rgb(248,248,248); border:1px solid rgb(221,221,221); line-height:19px; overflow:auto; padding:6px 10px; word-wrap:normal; color:rgb(51,51,51)"><code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:none; background-color:transparent; display:inline; vertical-align:middle; line-height:inherit; padding:0px; word-wrap:normal">.

├── index.html
├── 2013
├── 2014
├── assets
├── categories
├── page2
├── page3
├── page4
├── 工具
├── 思想
├── 技术
└── 源代码阅读
</code></pre>
<p style="margin-top:15px; margin-bottom:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
其中的&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">categories</code>，<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">2013</code>,&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">2014</code>&nbsp;目录就是分类插件和归档插件帮助我生成的，
 我只要把这个目录下的内容上传到 GitHub 相应的项目分支中就可以了。这样，你 访问&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">username.github.io</code>时，GitHub就不解析了，直接把<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">index.html</code>返回给你了。</p>
<h2 style="margin:1em 0px 15px; line-height:1.7; font-size:2em; padding:0px; position:relative; border-bottom-width:1px; border-bottom-style:solid; border-bottom-color:rgb(238,238,238); color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif">
<a target="_blank" target="_blank" name="%E5%B7%A5%E4%BD%9C%E6%B5%81" class="anchor" href="https://github.com/minixalpha/StrayBirds/blob/master/_posts/2014-02-15-github-jekyll-markdown.md#%E5%B7%A5%E4%BD%9C%E6%B5%81" style="color:rgb(65,131,196); text-decoration:none; display:block; padding-right:6px; padding-left:30px; margin-left:-30px; position:absolute; top:0px; left:0px; bottom:0px"></a>工作流</h2>
<p style="margin-top:15px; margin-bottom:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
关于 git 和 jekyll 的安装与基本使用，这里就不多说了。</p>
<ul style="padding:0px 0px 0px 30px; margin:15px 0px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
<li style="">工作流一</li></ul>
<p style="margin-top:15px; margin-bottom:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
如果你不使用插件，那么只需要维护一个分支就好:</p>
<pre style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:13px; margin-top:15px; margin-bottom:15px; background-color:rgb(248,248,248); border:1px solid rgb(221,221,221); line-height:19px; overflow:auto; padding:6px 10px; word-wrap:normal; color:rgb(51,51,51)"><code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:none; background-color:transparent; display:inline; vertical-align:middle; line-height:inherit; padding:0px; word-wrap:normal">- username/username.github.io 的 master 分支
- username/blog 的 gh-pages 分支
</code></pre>
<p style="margin-top:15px; margin-bottom:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
其中&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">username</code>&nbsp;是你的
 GitHub 帐号。</p>
<p style="margin-top:15px; margin-bottom:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
你需要在本地维护一份网站源代码，添加新文章后，使用 jekyll 在本地测试一下， 没有问题后，commit 到 GitHub 上的相应分支中就可以了。</p>
<ul style="padding:0px 0px 0px 30px; margin:15px 0px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
<li style="">工作流二</li></ul>
<p style="margin-top:15px; margin-bottom:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
如果你需要使用插件，那么需要维护两个分支，一个是网站的源代码分支 ，另一个 是 由Jeklly 解析源代码后生成的静态网站。</p>
<p style="margin-top:15px; margin-bottom:15px; color:rgb(51,51,51)"><span style="font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.4545450210571px; line-height:23.1818180084229px">例如，如果项目名为 username.github.io，的源代码分支名为&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">source</code>，静态网站分支名为</span><span style="font-family:Consolas,Liberation Mono,Courier,monospace"><span style="line-height:15.6000003814697px; white-space:nowrap; background-color:rgb(248,248,248)">master</span></span><span style="font-family:Helvetica,arial,freesans,clean,sans-serif"><span style="font-size:15.4545450210571px; line-height:23.1818180084229px">。平时写博客时，
 首先在 source 分支下，添加新文章，然后本地使用 jekyll build 将添加文章后的网站 解析一次，这时&nbsp;</span></span><code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; line-height:1.3; margin:0px; border:1px solid rgb(221,221,221); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; padding:0px; white-space:nowrap; background-color:rgb(248,248,248)">_site</code><span style="font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.4545450210571px; line-height:23.1818180084229px">&nbsp;目录下就有新网站的静态代码了。然后把这个目录下的所有内容
 复制到 </span><span style="font-family:Consolas,Liberation Mono,Courier,monospace"><span style="line-height:15.6000003814697px; white-space:nowrap; background-color:rgb(248,248,248)">master</span></span><span style="font-family:Helvetica,arial,freesans,clean,sans-serif"><span style="font-size:15.4545450210571px; line-height:23.1818180084229px">&nbsp;分支下。这个过程，可以写一个
 Makefile，每次添加文章后 make 一下， 就自动将文章发布到 GitHub 上。</span></span></p>
<p style="margin-top:15px; margin-bottom:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
Makefile 内容如下：</p>
<p style="margin-top:15px; margin-bottom:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
<br>
</p>
<pre style="overflow:auto; font-family:Consolas,'Liberation Mono',Menlo,Courier,monospace; font-size:13.6000003814697px; margin-top:0px; margin-bottom:16px; line-height:1.45; padding:16px; word-wrap:normal; color:rgb(51,51,51); background-color:rgb(247,247,247)"><code style="font-family:Consolas,'Liberation Mono',Menlo,Courier,monospace; font-size:13.6000003814697px; line-height:inherit; padding:0px; margin:0px; word-break:normal; border:0px; display:inline; word-wrap:normal; background:transparent">
deploy:
    git checkout source
    jekyll build
    git add -A
    git commit -m &quot;update source&quot;
    cp -r _site/ /tmp/
    git checkout master
    rm -r ./*
    cp -r /tmp/_site/* ./
    git add -A
    git commit -m &quot;deploy blog&quot;
    git push origin master
    git checkout source
    echo &quot;deploy succeed&quot;
    git push origin source
    echo &quot;push source&quot;</code></pre>
<br>
<p></p>
<p style="margin-top:15px; margin-bottom:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
下面的内容涉及源代码，如果需要进一步学习，或者有问题，可以在&nbsp;<a target="_blank" target="_blank" href="http://jekyllrb.com/" style="color:rgb(65,131,196); text-decoration:none">Jeklly 官网</a>上找到更详细的解释，或者在评论中留言。</p>
<h2 style="margin:1em 0px 15px; line-height:1.7; font-size:2em; padding:0px; position:relative; border-bottom-width:1px; border-bottom-style:solid; border-bottom-color:rgb(238,238,238); color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif">
<a target="_blank" target="_blank" name="%E6%BA%90%E4%BB%A3%E7%A0%81" class="anchor" href="https://github.com/minixalpha/StrayBirds/blob/master/_posts/2014-02-15-github-jekyll-markdown.md#%E6%BA%90%E4%BB%A3%E7%A0%81" style="color:rgb(65,131,196); text-decoration:none; display:block; padding-right:6px; padding-left:30px; margin-left:-30px; position:absolute; top:0px; left:0px; bottom:0px"></a>源代码</h2>
<p style="margin-top:15px; margin-bottom:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
再来看一下这个目录结构：</p>
<pre style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:13px; margin-top:15px; margin-bottom:15px; background-color:rgb(248,248,248); border:1px solid rgb(221,221,221); line-height:19px; overflow:auto; padding:6px 10px; word-wrap:normal; color:rgb(51,51,51)"><code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:none; background-color:transparent; display:inline; vertical-align:middle; line-height:inherit; padding:0px; word-wrap:normal">.
├── _config.yml
├── index.html
├── assets
│&nbsp;&nbsp; ├── blog-images
│&nbsp;&nbsp; ├── css
│&nbsp;&nbsp; ├── fonts
│&nbsp;&nbsp; ├── images
│&nbsp;&nbsp; └── javascripts
├── _includes
├── _layouts
├── _plugins
├── _posts
└── _site
</code></pre>
<ul style="padding:0px 0px 0px 30px; margin:15px 0px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
<li style="">_config.yml</li></ul>
<p style="margin-top:15px; margin-bottom:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
这是针对 Jekyll 的<a target="_blank" target="_blank" href="http://jekyllrb.com/docs/configuration/" style="color:rgb(65,131,196); text-decoration:none">配置文件</a>， 决定了 Jekyll 如何解析网站的源代码,下面是一个示例：</p>
<pre style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:13px; margin-top:15px; margin-bottom:15px; background-color:rgb(248,248,248); border:1px solid rgb(221,221,221); line-height:19px; overflow:auto; padding:6px 10px; word-wrap:normal; color:rgb(51,51,51)"><code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:none; background-color:transparent; display:inline; vertical-align:middle; line-height:inherit; padding:0px; word-wrap:normal">baseurl: /StrayBirds
markdown: redcarpet
safe: false
pygments: true
excerpt_separator: &quot;\n\n\n&quot;
paginate: 5
</code></pre>
<p style="margin-top:15px; margin-bottom:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
我的网站建立在&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">StrayBirds</code>&nbsp;项目中，所以&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">baseurl</code>&nbsp;设置成&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">StrayBirds</code>，
 我的文章采用 Markdown &#26684;式写成，可以指定 Markdown 的解析器&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">redcarpet</code>。
 另外，安全模式需要关闭，以便 Jekyll 解析时会运行插件。&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">pygments</code>&nbsp;可以使得Jekyll解析文章中源代码时加入特殊标记，例如指定代码类型，
 这可以被很多 javascript 代码高度库使用。&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">excerpt_separator</code>&nbsp;指定了一个摘要分割符号，这样
 Jekyll 可以在解析文章时， 将文章的提要提取出来。 paginate 指定了一页有几篇文章，页数太多时，我们可以将文章列表分页，我们在 后文还会提到。</p>
<ul style="padding:0px 0px 0px 30px; margin:15px 0px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
<li style="">_layouts</li></ul>
<p style="margin-top:15px; margin-bottom:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
这个目录存放着一些网页模板文件，为网站所有网页提供一个基本模板，这样 每个网页只需要关心自己的内容就好，其它的都由模板决定。例如，这个目录下的 default.html 文件：</p>
<div class="highlight highlight-html" style="overflow-x:auto; overflow-y:hidden; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
<pre style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:13px; margin-top:15px; margin-bottom:15px; background-color:rgb(248,248,248); border:1px solid rgb(221,221,221); line-height:19px; overflow:auto; padding:6px 10px; word-wrap:normal"><span class="cp" style="color:rgb(153,153,153); font-weight:bold">&lt;!DOCTYPE html&gt;</span>
<span class="nt" style="color:navy">&lt;html&gt;</span>
  <span class="nt" style="color:navy">&lt;head&gt;</span>
    <span class="nt" style="color:navy">&lt;meta</span> <span class="na" style="color:teal">charset=</span><span class="s" style="color:rgb(221,17,68)">'utf-8'</span><span class="nt" style="color:navy">&gt;</span>
    <span class="nt" style="color:navy">&lt;title&gt;</span>{{ page.title }}<span class="nt" style="color:navy">&lt;/title&gt;</span>
  <span class="nt" style="color:navy">&lt;/head&gt;</span>
  <span class="nt" style="color:navy">&lt;body&gt;</span>
    <span class="nt" style="color:navy">&lt;header&gt;</span>
    <span class="nt" style="color:navy">&lt;/header&gt;</span>

    <span class="nt" style="color:navy">&lt;aside&gt;</span>
    <span class="nt" style="color:navy">&lt;/aside&gt;</span>

    <span class="nt" style="color:navy">&lt;article&gt;</span>
{{ content }}
    <span class="nt" style="color:navy">&lt;/article&gt;</span>

    <span class="nt" style="color:navy">&lt;footer&gt;</span>
    <span class="nt" style="color:navy">&lt;/footer&gt;</span>
  <span class="nt" style="color:navy">&lt;/body&gt;</span>
<span class="nt" style="color:navy">&lt;/html&gt;</span>


</pre>
</div>
<p style="margin-top:15px; margin-bottom:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
可以看出，这个文件就是所有页面共有的东西，每个页面的具体内容会被填充在&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">{{
 content }}</code>&nbsp;中，注意这个 content 两边的标记，这是一种叫&nbsp;<a target="_blank" target="_blank" href="https://github.com/Shopify/liquid" style="color:rgb(65,131,196); text-decoration:none">liquid</a>&nbsp;的标记语言。 另外，还有那个&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">{{
 page.title }}</code>&nbsp;，其中&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">page</code>&nbsp;表示引用&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">default.html</code>的
 那个页面，这个页面的&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">title</code>&nbsp;&#20540;会在&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">page</code>&nbsp;相应页面中被设置，例如
 下面的&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">index.html</code>&nbsp;文件，开头部分就设置了&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">title</code>&#20540;。</p>
<ul style="padding:0px 0px 0px 30px; margin:15px 0px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
<li style="">index.html</li></ul>
<p style="margin-top:15px; margin-bottom:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
这是网站的首页，访问&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">http://username.github.io</code>&nbsp;时，会指向&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">http://username.github.io/index.html</code>，我们看一下基本内容：</p>
<div class="highlight highlight-html" style="overflow-x:auto; overflow-y:hidden; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
<pre style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:13px; margin-top:15px; margin-bottom:15px; background-color:rgb(248,248,248); border:1px solid rgb(221,221,221); line-height:19px; overflow:auto; padding:6px 10px; word-wrap:normal">---
layout: default
title: 首页
---

<span class="nt" style="color:navy">&lt;ul</span> <span class="na" style="color:teal">class=</span><span class="s" style="color:rgb(221,17,68)">&quot;post-list&quot;</span><span class="nt" style="color:navy">&gt;</span>
    {% for post in site.posts %}
        <span class="nt" style="color:navy">&lt;a</span> <span class="na" style="color:teal">href=</span><span class="s" style="color:rgb(221,17,68)">&quot;{{site.baseurl}}{{post.url}}&quot;</span><span class="nt" style="color:navy">&gt;</span> {{ post.title }}  <span class="nt" style="color:navy">&lt;/a&gt;</span> <span class="nt" style="color:navy">&lt;br&gt;</span>
        {{ post.date | date: &quot;%F&quot; }} <span class="nt" style="color:navy">&lt;br&gt;</span>
        {{ post.category }} <span class="nt" style="color:navy">&lt;br&gt;</span>
        {{ post.excerpt }} 
    {% endfor %}
<span class="nt" style="color:navy">&lt;/ul&gt;</span>
</pre>
</div>
<p style="margin-top:15px; margin-bottom:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
注意，文件开头的描述，我们称之为&nbsp;<a target="_blank" target="_blank" href="http://jekyllrb.com/docs/frontmatter/" style="color:rgb(65,131,196); text-decoration:none">front-matter</a>， 是对当前文件的一种描述，这里 设置的变量可以在解析时被引用，例如这里的&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">layout</code>就会告诉
 Jekyll, 生成&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">index.html</code>&nbsp;文件时，去&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">_layouts</code>&nbsp;目录下找&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">default.html</code>&nbsp;文件，然后把当前文件解析后，添加到&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">default.html</code>&nbsp;的&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">content</code>&nbsp;部分，组成最终的&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">index.html</code>&nbsp;文件。还有<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">title</code>&nbsp;设置好的
 &#20540;，会在&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">default.html</code>&nbsp;中通过&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">page.title</code>&nbsp;被引用。</p>
<p style="margin-top:15px; margin-bottom:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
文件的主体部分遍历了站点的所有文章，并将他们显示出来，这些语法都是&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">liquid</code>&nbsp;语法，
 其中的变量，例如&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">site</code>,
 由 Jekyll 设置我们只需要引用就可以了。而&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">post</code>&nbsp;中的变量，
 如&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">post.title</code>,&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">post.category</code>&nbsp;是由&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">post</code>&nbsp;文件中的
 front-matter 决定，后面马上就会看到。</p>
<ul style="padding:0px 0px 0px 30px; margin:15px 0px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
<li style="">_posts</li></ul>
<p style="margin-top:15px; margin-bottom:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
这个目录存放我们的所有博客文章，他们的名字有统一的&#26684;式：</p>
<pre style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:13px; margin-top:15px; margin-bottom:15px; background-color:rgb(248,248,248); border:1px solid rgb(221,221,221); line-height:19px; overflow:auto; padding:6px 10px; word-wrap:normal; color:rgb(51,51,51)"><code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:none; background-color:transparent; display:inline; vertical-align:middle; line-height:inherit; padding:0px; word-wrap:normal">YEAR-MONTH-DAY-title.MARKUP
</code></pre>
<p style="margin-top:15px; margin-bottom:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
例如，2014-02-15-github-jeklly.md，这个文件名会被解析，前面的&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">index.html</code>&nbsp;中，&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">post.date</code>&nbsp;的&#20540;就由这里文件名中的日期而来。下面，我们看看一篇文章的内容示例：</p>
<pre style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:13px; margin-top:15px; margin-bottom:15px; background-color:rgb(248,248,248); border:1px solid rgb(221,221,221); line-height:19px; overflow:auto; padding:6px 10px; word-wrap:normal; color:rgb(51,51,51)"><code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:none; background-color:transparent; display:inline; vertical-align:middle; line-height:inherit; padding:0px; word-wrap:normal">---
layout: default
title: 使用 Markdown
category: 工具
comments: true
---

# 为什么使用 Markdown

* 看上去不错  
* 既然看上去不错，为什么不试试呢  


# 如何使用 Markdown
</code></pre>
<p style="margin-top:15px; margin-bottom:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
可以看出，文章的 front-matter 部分设置了多项&#20540;，以后可以通过类&#20284;&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">post.title</code>,&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">post.category</code>&nbsp;的方式引用这些些，另外，<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">layout</code>部分的&#20540;和之前解释的一样，
 文件的内容会被填充到&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">_layouts/default.html</code>&nbsp;文件的&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">content</code>&nbsp;变量中。</p>
<p style="margin-top:15px; margin-bottom:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
另外，文章中&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">为什么不试试呢</code>之后的有三个不可见的&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">\n</code>，它决定了这三个&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">\n</code>&nbsp;之前的内容会被放在&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">post.excerpt</code>&nbsp;变量中，供其它文件使用。</p>
<ul style="padding:0px 0px 0px 30px; margin:15px 0px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
<li style="">_includes</li></ul>
<p style="margin-top:15px; margin-bottom:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
这个文件中，存放着一些模块文件，例如&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">categories.ext</code>，其它文件可以通过</p>
<pre style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:13px; margin-top:15px; margin-bottom:15px; background-color:rgb(248,248,248); border:1px solid rgb(221,221,221); line-height:19px; overflow:auto; padding:6px 10px; word-wrap:normal; color:rgb(51,51,51)"><code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:none; background-color:transparent; display:inline; vertical-align:middle; line-height:inherit; padding:0px; word-wrap:normal">{% raw %}
{% include categories.ext %}
{% endraw %}
</code></pre>
<p style="margin-top:15px; margin-bottom:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
来引用这个文件的内容，方便代码模块化和重用。我的博客&nbsp;<a target="_blank" target="_blank" href="http://minixalpha.github.io/StrayBirds/" style="color:rgb(65,131,196); text-decoration:none">主页</a>上的 分类，归档，这些模块的代码都是通过这种方式引用的。</p>
<ul style="padding:0px 0px 0px 30px; margin:15px 0px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
<li style="">_plugins</li></ul>
<p style="margin-top:15px; margin-bottom:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
这个文件中存放一些Ruby插件, 例如&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">gen_categories.rb</code>，这些文件会在
 Jekyll 解析网站源代码时被执行。下一节讲述的就是插件。</p>
<ul style="padding:0px 0px 0px 30px; margin:15px 0px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
<li style="">_site</li></ul>
<p style="margin-top:15px; margin-bottom:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
Jekyll 解析整个网站源代码后，会将最终的静态网站源代码放在这里</p>
<h2 style="margin:1em 0px 15px; line-height:1.7; font-size:2em; padding:0px; position:relative; border-bottom-width:1px; border-bottom-style:solid; border-bottom-color:rgb(238,238,238); color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif">
<a target="_blank" target="_blank" name="%E6%8F%92%E4%BB%B6" class="anchor" href="https://github.com/minixalpha/StrayBirds/blob/master/_posts/2014-02-15-github-jekyll-markdown.md#%E6%8F%92%E4%BB%B6" style="color:rgb(65,131,196); text-decoration:none; display:block; padding-right:6px; padding-left:30px; margin-left:-30px; position:absolute; top:0px; left:0px; bottom:0px"></a>插件</h2>
<p style="margin-top:15px; margin-bottom:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
插件使用 Ruby 写成，放在 _plugins 目录下，有些 Jekyll 没有的功能，又不能 手动添加，因为页面的内容会随着文章日期类别的不同而不同，例如分类功能和归档功能， 这时，就需要使用插件自动生成一些页面和目录。</p>
<ul style="padding:0px 0px 0px 30px; margin:15px 0px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
<li style="">分类 我的分类插件使用的是&nbsp;<a target="_blank" target="_blank" href="https://github.com/shigeya/jekyll-category-archive-plugin/tree/master/_plugins" style="color:rgb(65,131,196); text-decoration:none">jekyll-category-archive-plugin</a>, 它会根据网站文章的分类信息，为每个类别生成一个页面。</li></ul>
<p style="margin-top:15px; margin-bottom:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
使用方法是，把&nbsp;<span style="">plugins/category</span>archive_plugin.rb 放在&nbsp;<span style="">plugins 目录下， 把 _layouts/category</span>archive.html 放在&nbsp;<span style="">layouts 目录下， 这样，这个插件会在Jekyll解析网站时，生成相应categories目录，目录下是各个分类， 每个分类下都有一个&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">index.html</code>&nbsp;文件，这个文件是根据模板文件
 category</span>archive.html 生成的，例如：</p>
<pre style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:13px; margin-top:15px; margin-bottom:15px; background-color:rgb(248,248,248); border:1px solid rgb(221,221,221); line-height:19px; overflow:auto; padding:6px 10px; word-wrap:normal; color:rgb(51,51,51)"><code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:none; background-color:transparent; display:inline; vertical-align:middle; line-height:inherit; padding:0px; word-wrap:normal">_site/categories/
├── 工具
│&nbsp;&nbsp; └── index.html
├── 思想
│&nbsp;&nbsp; └── index.html
├── 技术
│&nbsp;&nbsp; └── index.html
└── 源代码阅读
    └── index.html
</code></pre>
<p style="margin-top:15px; margin-bottom:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
然后，你就可以通过&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">http://username.github.io/blog/categories/工具/</code>&nbsp;访问&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">工具</code>类下的&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">index.html</code>&nbsp;文件。</p>
<ul style="padding:0px 0px 0px 30px; margin:15px 0px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
<li style="">归档 我的归档插件使用的是&nbsp;<a target="_blank" target="_blank" href="https://github.com/shigeya/jekyll-monthly-archive-plugin" style="color:rgb(65,131,196); text-decoration:none">jekyll-monthly-archive-plugin</a>,它会根据网站 _posts目录下的文章日期，为每个月生成一个页面。</li></ul>
<p style="margin-top:15px; margin-bottom:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
使用方法同上。注意，这个插件在 jekyll-1.4.2 中可能会出错，在 jekyll-1.2.0 中没有错误。</p>
<h2 style="margin:1em 0px 15px; line-height:1.7; font-size:2em; padding:0px; position:relative; border-bottom-width:1px; border-bottom-style:solid; border-bottom-color:rgb(238,238,238); color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif">
<a target="_blank" target="_blank" name="%E7%BB%84%E4%BB%B6" class="anchor" href="https://github.com/minixalpha/StrayBirds/blob/master/_posts/2014-02-15-github-jekyll-markdown.md#%E7%BB%84%E4%BB%B6" style="color:rgb(65,131,196); text-decoration:none; display:block; padding-right:6px; padding-left:8px; margin-left:-30px; position:absolute; top:109.48863220214844px; left:0px; bottom:0px; line-height:1"><span class="octicon octicon-link" style=""></span></a>组件</h2>
<ul style="padding:0px 0px 0px 30px; margin:15px 0px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
<li style="">分页</li></ul>
<p style="margin-top:15px; margin-bottom:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
当文章很多时，就需要使用分页功能，在 Jekyll 官网上提供了一种&nbsp;<a target="_blank" target="_blank" href="http://jekyllrb.com/docs/pagination/" style="color:rgb(65,131,196); text-decoration:none">实现</a>，把相应代码放在 主页上，然后在&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">_config.yml</code>&nbsp;中设置&nbsp;<code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:1px solid rgb(221,221,221); background-color:rgb(248,248,248); max-width:100%; display:inline-block; overflow:auto; vertical-align:middle; line-height:1.3; padding:0px; white-space:nowrap">paginate</code>&nbsp;&#20540;就行了。</p>
<ul style="padding:0px 0px 0px 30px; margin:15px 0px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
<li style="">评论</li></ul>
<p style="margin-top:15px; margin-bottom:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
评论功能需要使用外挂，我使用的是&nbsp;<a target="_blank" target="_blank" href="http://disqus.com/" style="color:rgb(65,131,196); text-decoration:none">DISQUS</a>, 注册 之后，将评论区的一段代码放在你需要使用评论功能的页面上, 然后，通过在页面的 front-matter 部分使用</p>
<pre style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:13px; margin-top:15px; margin-bottom:15px; background-color:rgb(248,248,248); border:1px solid rgb(221,221,221); line-height:19px; overflow:auto; padding:6px 10px; word-wrap:normal; color:rgb(51,51,51)"><code style="font-family:Consolas,'Liberation Mono',Courier,monospace; font-size:12px; margin:0px; border:none; background-color:transparent; display:inline; vertical-align:middle; line-height:inherit; padding:0px; word-wrap:normal">comments: true
</code></pre>
<p style="margin-top:15px; margin-bottom:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
启用评论。<strong>此外，如果你 fork 了我的项目，需要修改 `_inclusds<span class="separator" style="color:rgb(153,153,153); font-family:Helvetica,arial,freesans,clean,sans-serif,'Segoe UI Emoji','Segoe UI Symbol'; font-size:18.3999996185303px; line-height:20.1599998474121px">/</span></strong><span class="final-path" style="font-family:Helvetica,arial,freesans,clean,sans-serif,'Segoe UI Emoji','Segoe UI Symbol'; font-size:18.3999996185303px; line-height:20.1599998474121px"><strong>comments.ext`，把里面的
 `<span style="color:rgb(51,51,51); font-family:Consolas,'Liberation Mono',Menlo,Courier,monospace; line-height:13.4399995803833px; white-space:pre">disqus_shortname ` 修改成你的博客短名，这个在注册的时候会设置。</span></strong></span></p>
<p style="margin-top:15px; margin-bottom:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
评论区截图：</p>
<p style="margin-top:15px; margin-bottom:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px">
<img src="http://img.blog.csdn.net/20140215230506156?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvb25fMXk=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast" alt=""><br>
</p>
<p style="margin-top:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px; margin-bottom:0px!important">
基本的内容就介绍到这里，任何问题，欢迎留言。</p>
<p style="margin-top:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px; margin-bottom:0px!important">
<br>
</p>
<p style="margin-top:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px; margin-bottom:0px!important">
另外，如果这篇文章对你有用的话，在<a target="_blank" target="_blank" href="https://github.com/minixalpha/minixalpha.github.io">GitHub</a>上帮我点个 star 吧，即是对我的肯定，也可以帮助更多的人。</p>
<p style="margin-top:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px; margin-bottom:0px!important">
另外，注意如果你要 fork 我的模板，注意里面有些链接是与我的 GitHub 名 minixalpha 相关的，在使用前最好批量地将这个字符串替换为你的账号名。</p>
<p style="margin-top:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px; margin-bottom:0px!important">
<br>
</p>
<h1 name="clean_blog" style="margin-top:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; line-height:23.1818180084229px; margin-bottom:0px!important">
<strong><span style="font-size:18px">一个极简风&#26684;的博客</span></strong></h1>
<p style="margin-top:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px; margin-bottom:0px!important">
<span style="font-size:15.4545450210571px; line-height:23.1818180084229px">从上面的工作流程可以看出，虽然每次我在本地添加文件后，都只要 make 一下就能发布文章，但我还是觉得麻烦，希望能直接通过浏览器在 GitHub 的网站上添加文章，所以，我又建立了一个非常简洁的博客，没有分类，没有评论，就是一个主页，上面有所有文章链接，添加文章时候，只要在 _post 目录下添加一个 markdown 文件就可以了。</span></p>
<p style="margin-top:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px; margin-bottom:0px!important">
这个博客项目为： <a target="_blank" target="_blank" href="https://github.com/minixalpha/StrayBirds/tree/gh-pages">
StrayBirds</a>&nbsp;, 是通过 GitHub 的&nbsp;<span style="color:rgb(34,34,34); font-family:Consolas,'Lucida Console',monospace; white-space:pre-wrap"> Automatic page generator生成。完全通过浏览器操作就能建成，不用 git啊，make啊。这个项目目前已经有了 158 个 fork，但是只有 35 个 star 呀，拜托点下 star，这也太不平衡了……</span></p>
<p style="margin-top:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px; margin-bottom:0px!important">
<span style="color:rgb(34,34,34); font-family:Consolas,'Lucida Console',monospace; white-space:pre-wrap">博客首页：<a target="_blank" target="_blank" href="http://minixalpha.github.io/StrayBirds/">飞鸟集</a>。</span><br>
</p>
<p style="margin-top:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px; margin-bottom:0px!important">
<span style="color:rgb(34,34,34); font-family:Consolas,'Lucida Console',monospace; white-space:pre-wrap"><img src="http://img.blog.csdn.net/20140920131944468?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvb25fMXk=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast" alt=""><br>
</span></p>
<p style="margin-top:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px; margin-bottom:0px!important">
<br>
</p>
<p style="margin-top:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px; margin-bottom:0px!important">
要使用这个项目，你需要做的是：</p>
<p style="margin-top:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px; margin-bottom:0px!important">
1. 注册 GitHub，例如你的用户名为 minixbeta</p>
<p style="margin-top:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px; margin-bottom:0px!important">
2. 到 <a target="_blank" target="_blank" href="https://github.com/minixalpha/StrayBirds/tree/gh-pages">
StrayBirds</a>&nbsp;点右上角的 fork</p>
<p style="margin-top:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px; margin-bottom:0px!important">
3. 到你 fork 后的项目中，将 _config.yml 中的 username 修改成你的用户名 minixbeta</p>
<p style="margin-top:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px; margin-bottom:0px!important">
4. 得到你自己的博客&nbsp;http://minixbeta.github.io/StrayBirds/</p>
<p style="margin-top:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px; margin-bottom:0px!important">
需要注意的是，第一次使用 GitHub Pages 时，可能会有较长时间的缓冲时间，过15min左右，才能正常访问博客，请耐心等待。可以尝试修改项目名称来加快这一进程，如何修改后面有介绍。</p>
<p style="margin-top:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px; margin-bottom:0px!important">
另外，我又添加了评论系统，让这个简洁的博客更为完整，你需要到 Disqus 上注册，然后添加一个站点，然后将 _confg.yml 中的 disqusname&nbsp;<span style="font-size:18.3999996185303px; font-family:Consolas,'Liberation Mono',Menlo,Courier,monospace; line-height:13.4399995803833px; white-space:pre"><strong>修改成你的博客短名，这个在Disqus
 的 Add Disqus To Site 的时候会设置，注意这里的对应关系。注意这个名字不是你的 Disqus 用户名，是你的站点名。</strong></span></p>
<p style="margin-top:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; line-height:23.1818180084229px; margin-bottom:0px!important">
<span style="font-size:18px">如果你的文章想启用评论，在写文章的风&#26684;定义部分，加上 `comments: true` 即可。像示例文章中那样就行，如果你不想加评论，就不要加这句。</span></p>
<p style="margin-top:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px; margin-bottom:0px!important">
<span style="font-size:15.4545450210571px; line-height:23.1818180084229px">另外，由于这个项目目前已经有 200 个 fork，因此我又将 GitHub Pages 官方的所有主题及<a target="_blank" target="_blank" href="http://www.zhanxin.info/">掌心</a>做的 Jekyll 主题整合到其中，你可以通过修改 _config.yml 中的 theme 字段，轻松切换主题，不过每次切换都需要等待一段时间才能生效。所以，最好在修改主题之后修改项目名称，可能会回快这一进程。修改方法后面会介绍。</span></p>
<p style="margin-top:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px; margin-bottom:0px!important">
主题包括：</p>
<p style="margin-top:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px; margin-bottom:0px!important">
</p>
<ul>
<li>hack<span style="white-space:pre"> </span>&nbsp;<img src="http://img.blog.csdn.net/20150423223940345?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvb25fMXk=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast" alt=""></li><li>leap-day<img src="http://img.blog.csdn.net/20150423224008471?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvb25fMXk=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast" alt=""></li><li>merlot <img src="http://img.blog.csdn.net/20150423223913116?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvb25fMXk=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast" alt=""></li><li>midnight&nbsp;<img src="http://img.blog.csdn.net/20150423224036380?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvb25fMXk=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast" alt=""><br>
</li><li>minimal&nbsp;<img src="http://img.blog.csdn.net/20150423224141347?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvb25fMXk=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast" alt=""><br>
</li><li>modernist<span style="white-space:pre"> </span><img src="http://img.blog.csdn.net/20150423224230338?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvb25fMXk=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast" alt=""><br>
</li><li>slate<span style="white-space:pre"> </span><img src="http://img.blog.csdn.net/20150423224054351?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvb25fMXk=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast" alt=""></li><li>time-machine<img src="http://img.blog.csdn.net/20150423223947467?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvb25fMXk=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast" alt=""><br>
</li></ul>
<span style="white-space:pre"></span>
<p style="margin-top:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px; margin-bottom:0px!important">
<span style="font-size:15.4545450210571px; line-height:23.1818180084229px">kunka</span></p>
<p style="margin-top:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px; margin-bottom:0px!important">
<span style="font-size:15.4545450210571px; line-height:23.1818180084229px"><img src="http://img.blog.csdn.net/20150510214858118?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvb25fMXk=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast" alt=""><br>
</span></p>
<p style="margin-top:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px; margin-bottom:0px!important">
<span style="font-size:15.4545450210571px; line-height:23.1818180084229px"></span></p>
<p style="margin-top:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.4545450210571px; line-height:23.1818180084229px; margin-bottom:0px!important">
如果你想把项目的名字改了，例如，将 StrayBirds 修改为 blog</p>
<p style="margin-top:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.4545450210571px; line-height:23.1818180084229px; margin-bottom:0px!important">
那么，你需要做的是:</p>
<p style="margin-top:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.4545450210571px; line-height:23.1818180084229px; margin-bottom:0px!important">
1. 在项目的 Setting 中将 Repository name 从 StrayBirds 修改为 blog</p>
<p style="margin-top:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.4545450210571px; line-height:23.1818180084229px; margin-bottom:0px!important">
2. 将 _config.yml 中的 baseurl 修改为 /blog</p>
<p style="margin-top:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.4545450210571px; line-height:23.1818180084229px; margin-bottom:0px!important">
3. 通过&nbsp;<span style="font-size:15px; line-height:23.1818180084229px">http://minixbeta.github.io/blog/ 来访问你的新博客。</span></p>
<p style="margin-top:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.4545450210571px; line-height:23.1818180084229px; margin-bottom:0px!important">
<span style="font-size:15px; line-height:23.1818180084229px"></span></p>
<h2 style="margin-top:1em; margin-bottom:16px; line-height:1.225; font-size:1.75em; position:relative; padding-bottom:0.3em; border-bottom-width:1px; border-bottom-style:solid; border-bottom-color:rgb(238,238,238); color:rgb(51,51,51); font-family:'Helvetica Neue',Helvetica,'Segoe UI',Arial,freesans,sans-serif">
感谢</h2>
<p></p>
<p style="margin-top:0px; margin-bottom:16px; color:rgb(51,51,51); font-family:'Helvetica Neue',Helvetica,'Segoe UI',Arial,freesans,sans-serif; font-size:16px; line-height:20.4799995422363px">
Thanks to authors of the themes:</p>
<ul style="padding:0px 0px 0px 2em; margin-top:0px; margin-bottom:16px; color:rgb(51,51,51); font-family:'Helvetica Neue',Helvetica,'Segoe UI',Arial,freesans,sans-serif; font-size:16px; line-height:20.4799995422363px">
<li style=""><a target="_blank" target="_blank" href="https://github.com/sundaykofax/baby-legs" style="color:rgb(65,131,196); text-decoration:none; background-color:transparent">hack</a>, Licence: None</li><li style=""><a target="_blank" target="_blank" href="https://github.com/mattgraham/leapday" style="color:rgb(65,131,196); text-decoration:none; background-color:transparent">leap-day</a>, Licence:&nbsp;<a target="_blank" target="_blank" href="http://creativecommons.org/licenses/by/3.0/" style="color:rgb(65,131,196); text-decoration:none; background-color:transparent">Creative
 Commons Attribution</a></li><li style=""><a target="_blank" target="_blank" href="https://github.com/cameronmcefee/headsmart/tree/gh-pages" style="color:rgb(65,131,196); text-decoration:none; background-color:transparent">merlot</a>, Licence: None</li><li style=""><a target="_blank" target="_blank" href="https://github.com/briandoll/change-inside-surroundings.vim/tree/gh-pages" style="color:rgb(65,131,196); text-decoration:none; background-color:transparent">midnight</a>, Licence: None</li><li style=""><a target="_blank" target="_blank" href="https://github.com/orderedlist/minimal" style="color:rgb(65,131,196); text-decoration:none; background-color:transparent">minimal</a>, Licence:&nbsp;<a target="_blank" target="_blank" href="http://creativecommons.org/licenses/by-sa/3.0/" style="color:rgb(65,131,196); text-decoration:none; background-color:transparent">Creative
 Commons Attribution-ShareAlike 3.0 Unported License</a></li><li style=""><a target="_blank" target="_blank" href="https://github.com/orderedlist/modernist" style="color:rgb(65,131,196); text-decoration:none; background-color:transparent">modernist</a>, Licence:&nbsp;<a target="_blank" target="_blank" href="http://creativecommons.org/licenses/by-sa/3.0/" style="color:rgb(65,131,196); text-decoration:none; background-color:transparent">Creative
 Commons Attribution-ShareAlike 3.0 Unported License</a></li><li style=""><a target="_blank" target="_blank" href="https://github.com/jasoncostello/slate" style="color:rgb(65,131,196); text-decoration:none; background-color:transparent">slate</a>, Licence: MIT</li><li style=""><a target="_blank" target="_blank" href="https://github.com/jonrohan/time-machine-theme" style="color:rgb(65,131,196); text-decoration:none; background-color:transparent">time-machine</a>, Licence: None</li><li style=""><a target="_blank" target="_blank" href="https://github.com/pizn/kunka" style="color:rgb(65,131,196); text-decoration:none; background-color:transparent">kunka</a>, Licence: MIT, author:&nbsp;<a target="_blank" target="_blank" href="http://www.zhanxin.info/" style="color:rgb(65,131,196); text-decoration:none; background-color:transparent">zhanxin.info</a></li></ul>
<p style="margin-top:0px; color:rgb(51,51,51); font-family:'Helvetica Neue',Helvetica,'Segoe UI',Arial,freesans,sans-serif; font-size:16px; line-height:20.4799995422363px; margin-bottom:0px!important">
All the themes are intergrated in the blog template, with some modifies.</p>
<br>
<p style="margin-top:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px; margin-bottom:0px!important">
<span style="font-size:15.4545450210571px; line-height:23.1818180084229px">如果你不太明白，可以看这个</span><a target="_blank" target="_blank" href="https://github.com/minixalpha/StrayBirds/tree/gh-pages" style="line-height:23.1818180084229px; font-size:15.3333330154419px">StrayBirds</a><span style="line-height:23.1818180084229px; font-size:15.3333330154419px">&nbsp;</span><span style="font-size:15.4545450210571px; line-height:23.1818180084229px">&nbsp;项目在
 GitHub 上的 READEME，里面有如何fork项目，修改项目名，添加文章的 GIF 演示。</span></p>
<p style="margin-top:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px; margin-bottom:0px!important">
<span style="font-size:15.4545450210571px; line-height:23.1818180084229px">如果遇到有bug, 麻烦在GitHub 上提交</span><a target="_blank" target="_blank" href="https://github.com/minixalpha/minixalpha.github.io/issues" style="font-size:15.4545450210571px; line-height:23.1818180084229px">Issues</a>，最好不要在
 GitHub 上的博客中评论。</p>
<p style="margin-top:15px; color:rgb(51,51,51); font-family:Helvetica,arial,freesans,clean,sans-serif; font-size:15.454545021057129px; line-height:23.18181800842285px; margin-bottom:0px!important">
另外， 这篇文章从 2014 年 2 月到现在 (2015年4月) 一直在不断更新，如果对大家有用，希望去 GitHub 上点个 star 支持一下。</p>
   
</div>




<!-- Baidu Button BEGIN -->




<div class="bdsharebuttonbox tracking-ad" style="float: right;" data-mod="popu_172">
<a href="#" class="bds_more" data-cmd="more" style="background-position:0 0 !important; background-image: url(http://bdimg.share.baidu.com/static/api/img/share/icons_0_16.png?v=d754dcc0.png) !important"></a>
<a href="#" class="bds_qzone" data-cmd="qzone" title="分享到QQ空间"  style="background-position:0 -52px !important"></a>
<a href="#" class="bds_tsina" data-cmd="tsina" title="分享到新浪微博"style="background-position:0 -104px !important"></a>
<a href="#" class="bds_tqq" data-cmd="tqq" title="分享到腾讯微博"style="background-position:0 -260px !important"></a>
<a href="#" class="bds_renren" data-cmd="renren" title="分享到人人网"style="background-position:0 -208px !important"></a>
<a href="#" class="bds_weixin" data-cmd="weixin" title="分享到微信"style="background-position:0 -1612px !important" ></a>
</div>
<script>window._bd_share_config = { "common": { "bdSnsKey": {}, "bdText": "", "bdMini": "1", "bdMiniList": false, "bdPic": "", "bdStyle": "0", "bdSize": "16" }, "share": {} }; with (document) 0[(getElementsByTagName('head')[0] || body).appendChild(createElement('script')).src = 'http://bdimg.share.baidu.com/static/api/js/share.js?v=89860593.js?cdnversion=' + ~(-new Date() / 36e5)];</script>
<!-- Baidu Button END -->

   

<!--172.16.140.13-->

<!-- Baidu Button BEGIN -->
<script type="text/javascript" id="bdshare_js" data="type=tools&amp;uid=1536434" ></script>
<script type="text/javascript" id="bdshell_js"></script>
<script type="text/javascript">
    document.getElementById("bdshell_js").src = "http://bdimg.share.baidu.com/static/js/shell_v2.js?cdnversion=" + Math.ceil(new Date()/3600000)
</script>
<!-- Baidu Button END -->



 


        <div id="digg" ArticleId="19259435" >
            <dl id="btnDigg" class="digg digg_disable"  onclick="btndigga();">
               
                 <dt>顶</dt>
                <dd>25</dd>
            </dl>
           
              
            <dl id="btnBury" class="digg digg_disable"  onclick="btnburya();">
              
                  <dt>踩</dt>
                <dd>0</dd>               
            </dl>
            
        </div>
     <div class="tracking-ad" data-mod="popu_222"><a href="javascript:void(0);" >&nbsp;</a>   </div>
    <div class="tracking-ad" data-mod="popu_223"> <a href="javascript:void(0);" >&nbsp;</a></div>
    <script type="text/javascript">
        function btndigga() {
            $(".tracking-ad[data-mod='popu_222'] a").click();
        }
        function btnburya() {
            $(".tracking-ad[data-mod='popu_223'] a").click();
        }
            </script>

   <ul class="article_next_prev">
                <li class="prev_article"><span  onclick="_gaq.push(['_trackEvent','function', 'onclick', 'blog_articles_shangyipian']);location.href='http://blog.csdn.net/on_1y/article/details/18818081';">上一篇</span><a href="http://blog.csdn.net/on_1y/article/details/18818081" onclick="_gaq.push(['_trackEvent','function', 'onclick', 'blog_articles_shangyipian'])">wsgiref 源代码分析</a></li>
                <li class="next_article"><span onclick="_gaq.push(['_trackEvent','function', 'onclick', 'blog_articles_xiayipian']);location.href='http://blog.csdn.net/on_1y/article/details/19682875';">下一篇</span><a href="http://blog.csdn.net/on_1y/article/details/19682875" onclick="_gaq.push(['_trackEvent','function', 'onclick', 'blog_articles_xiayipian'])">GCC 简介</a></li>
    </ul>

    <div style="clear:both; height:10px;"></div>


            <div class="similar_article"   >
                    <h4></h4>
                    <div class="similar_c"style="margin:20px 0px 0px 0px">
                        <div class="similar_c_t">
                          &nbsp;&nbsp;相关文章推荐
                        </div>
                   
                        <div class="similar_wrap tracking-ad" data-mod="popu_36"  style="max-height:250px">                       
                            <ul class="similar_list fl">    
                                   <li>
                                       <em>•</em>
                                       <a href="http://blog.csdn.net/zjmdp/article/details/39340413" title="拥抱Mac之码农篇" strategy="BlogCommendFromCsdn_0" target="_blank">拥抱Mac之码农篇</a>
                                   </li>
                                   <li>
                                       <em>•</em>
                                       <a href="http://edu.csdn.net/huiyiCourse/detail/491?utm_source=blog7" title="【直播】70天软考冲刺计划--任铄" strategy="undefined" target="_blank">【直播】70天软考冲刺计划--任铄</a>
                                   </li>
                                   <li>
                                       <em>•</em>
                                       <a href="http://download.csdn.net/download/guanbaisheng/9866959" title="GitHub hexo搭建个人博客" strategy="BlogCommendFromCsdn_1" target="_blank">GitHub hexo搭建个人博客</a>
                                   </li>
                                   <li>
                                       <em>•</em>
                                       <a href="http://edu.csdn.net/huiyiCourse/series_detail/60?utm_source=blog7" title="【直播】打通Linux脉络 进程、线程、调度--宋宝华" strategy="undefined" target="_blank">【直播】打通Linux脉络 进程、线程、调度--宋宝华</a>
                                   </li>
                                   <li>
                                       <em>•</em>
                                       <a href="http://blog.csdn.net/GarfieldEr007/article/details/49992713" title="使用 GitHub, Jekyll 打造自己的免费独立博客" strategy="BlogCommendFromCsdn_2" target="_blank">使用 GitHub, Jekyll 打造自己的免费独立博客</a>
                                   </li>
                                   <li>
                                       <em>•</em>
                                       <a href="http://edu.csdn.net/huiyiCourse/series_detail/48?utm_source=blog7" title="【直播】机器学习之凸优化--马博士" strategy="undefined" target="_blank">【直播】机器学习之凸优化--马博士</a>
                                   </li>
                                   <li>
                                       <em>•</em>
                                       <a href="http://download.csdn.net/download/wenchunhai/505242" title="一套基于php+mysql 数据库平台架构的多用户博客系统，该系统融合了Blog的最新元素，拥有强大的个人主页系统，独立的二级域名功能，灵活的用户模版系统，丰富的朋友圈和个性相册功能。" strategy="BlogCommendFromCsdn_3" target="_blank">一套基于php+mysql 数据库平台架构的多用户博客系统，该系统融合了Blog的最新元素，拥有强大的个人主页系统，独立的二级域名功能，灵活的用户模版系统，丰富的朋友圈和个性相册功能。</a>
                                   </li>
                                   <li>
                                       <em>•</em>
                                       <a href="http://edu.csdn.net/combo/detail/522?utm_source=blog7" title="【套餐】MATLAB基础+MATLAB数据分析与统计--魏伟" strategy="undefined" target="_blank">【套餐】MATLAB基础+MATLAB数据分析与统计--魏伟</a>
                                   </li>
                            </ul>
                              <ul class="similar_list fr">      
                                   <li>
                                       <em>•</em>
                                       <a href="http://download.csdn.net/download/u014485012/7731245" title="OurJS免费开源的博客引擎，论坛系统，网站模板和轻量级的CMS" strategy="BlogCommendFromCsdn_4" target="_blank">OurJS免费开源的博客引擎，论坛系统，网站模板和轻量级的CMS</a>
                                   </li>
                                   <li>
                                       <em>•</em>
                                       <a href="http://edu.csdn.net/course/detail/5662?utm_source=blog7" title="【课程】3小时掌握Docker最佳实战--徐西宁" strategy="undefined" target="_blank">【课程】3小时掌握Docker最佳实战--徐西宁</a>
                                   </li>
                                   <li>
                                       <em>•</em>
                                       <a href="http://download.csdn.net/download/luojiadream/4978355" title="Linux/Unix环境下计算C程序运行时间 我自己博客上copy下来的 免费送给大家" strategy="BlogCommendFromCsdn_5" target="_blank">Linux/Unix环境下计算C程序运行时间 我自己博客上copy下来的 免费送给大家</a>
                                   </li>
                                   <li>
                                       <em>•</em>
                                       <a href="" title="【课程】深度学习基础与TensorFlow实践--AI100" strategy="undefined" target="_blank">【课程】深度学习基础与TensorFlow实践--AI100</a>
                                   </li>
                                   <li>
                                       <em>•</em>
                                       <a href="http://blog.csdn.net/GL771066709/article/details/74278818" title="Github/jekyll搭建博客" strategy="BlogCommendFromCsdn_6" target="_blank">Github/jekyll搭建博客</a>
                                   </li>
                                   <li>
                                       <em>•</em>
                                       <a href="http://download.csdn.net/download/yincheng01/5216582" title="传智博客iOS6免费公开课程源码-APP中使用icloud" strategy="BlogCommendFromCsdn_7" target="_blank">传智博客iOS6免费公开课程源码-APP中使用icloud</a>
                                   </li>
                                   <li>
                                       <em>•</em>
                                       <a href="http://blog.csdn.net/M1mory/article/details/52906033" title="使用github和jekyll打造自己的独立博客及常见问题" strategy="BlogCommendFromCsdn_8" target="_blank">使用github和jekyll打造自己的独立博客及常见问题</a>
                                   </li>
                                   <li>
                                       <em>•</em>
                                       <a href="http://download.csdn.net/download/junmuzi/5056093" title="个人博客系统V1.3 标准免费版.rar" strategy="BlogCommendFromCsdn_9" target="_blank">个人博客系统V1.3 标准免费版.rar</a>
                                   </li>
                            </ul>
                        </div>
                    </div>
                </div>   
      
</div>

    <div>
        

        <script type="text/javascript">
            /*博客内容页下方Banner1-728*90，创建于2016-12-13*/
            var cpro_id = "u2843949";
        </script>
        <script type="text/javascript" src="http://cpro.baidustatic.com/cpro/ui/c.js"></script>

     </div>

<div id="suggest"></div>
         <script  language="javascript" type='text/javascript'>     
             $(function(){
                 $.get("/on_1y/svc/GetSuggestContent/19259435",function(data){
                     $("#suggest").html(data);
                 });     
             });             
         </script>  



            
                                    
            
                                    

        <!-- 广告位开始 -->
        <!-- 广告位结束 -->


<div class="comment_class">
    <div id="comment_title" class="panel_head">
        <span class="see_comment">查看评论</span><a name="comments"></a></div>
    <div id="comment_list">
    </div>
    <div id="comment_bar">
    </div>
    <div id="comment_form">
    </div>
    <div class="announce">
        * 以上用户言论只代表其个人观点，不代表CSDN网站的观点或立场<a name="reply"></a><a name="quote"></a></div>
</div>

<script type="text/javascript">
    var fileName = '19259435';
    var commentscount = 43;
    var islock = false
</script>

    <div id="ad_bot">
    </div>
<div id="report_dialog">
</div>

<div id="d-top"  style="bottom:60px;">

        <a id="quick-reply" class="btn btn-top q-reply" title="快速回复" style="display:none;">
            <img src="http://static.blog.csdn.net/images/blog-icon-reply.png" alt="快速回复">
        </a>    
    <a id="d-top-a" class="btn btn-top backtop"  style="display: none;" title="返回顶部" onclick="_gaq.push(['_trackEvent','function', 'onclick', 'blog_articles_huidaodingbu'])" style="">         
         <img src="http://static.blog.csdn.net/images/top.png" alt="TOP">
    </a>
</div>
<script type="text/javascript">
    $(function ()
    {
        $("#ad_frm_0").height("90px");
        
        setTimeout(function(){
            $("#ad_frm_2").height("200px");
        },1000);    
    });
  
</script>
<style type="text/css">
    .tag_list
    {
        background: none repeat scroll 0 0 #FFFFFF;
        border: 1px solid #D7CBC1;
        color: #000000;
        font-size: 12px;
        line-height: 20px;
        list-style: none outside none;
        margin: 10px 2% 0 1%;
        padding: 1px;
    }
    .tag_list h5
    {
        background: none repeat scroll 0 0 #E0DBD3;
        color: #47381C;
        font-size: 12px;
        height: 24px;
        line-height: 24px;
        padding: 0 5px;
        margin: 0;
    }
    .tag_list h5 a
    {
        color: #47381C;
    }
    .classify
    {
        margin: 10px 0;
        padding: 4px 12px 8px;
    }
    .classify a
    {
        margin-right: 20px;
        white-space: nowrap;
    }
</style>





<div id="pop_win" style="display:none ;position: absolute; z-index: 10000; border: 1px solid rgb(220, 220, 220); top: 222.5px; left: 630px; opacity: 1; background: none 0px 0px repeat scroll rgb(255, 255, 255);">
    
</div>
<div id="popup_mask"></div>
<style>
    #popup_mask
    {
        position: absolute;
        width: 100%;
        height: 100%;
        background: #000;
        z-index: 9999;
        left: 0px;
        top: 0px;
        opacity: 0.3;
        filter: alpha(opacity=30);
        display: none;
    }

</style>




<script type="text/javascript">
    $(function(){        
        
        setTimeout(function(){
            $(".comment_body:contains('回复')").each(function(index,item){
                var u=$(this).text().split('：')[0].toString().replace("回复","")
                var thisComment=$(this);
                if(u)
                {
                    $.getJSON("https://passport.csdn.net/get/nick?callback=?", {users: u}, function(a) {
                        if(a!=null&&a.data!=null&&a.data.length>0)
                        {
                            nick=a.data[0].n; 
                            if(u!=nick)
                            {
                                thisComment.text(thisComment.text().replace(u,nick));  
                            }
                        }       
                    });  
                }
            });         

        },200);  

        setTimeout(function(){
            $(".math").each(function(index,value){$(this).find("span").last().css("color","#fff"); })
        },5000);

        setTimeout(function(){
            $(".math").each(function(index,value){$(this).find("span").last().css("color","#fff"); })
        },10000);

        setTimeout(function(){
            $(".math").each(function(index,value){$(this).find("span").last().css("color","#fff"); })
        },15000);
        
        setTimeout(function(){
            $("a img[src='http://js.tongji.linezing.com/stats.gif']").parent().css({"position":"absolute","left":"50%"});
        },300);
    });

    function loginbox(){
        var $logpop=$("#pop_win");
        $logpop.html('<iframe src="https://passport.csdn.net/account/loginbox?service=http://static.blog.csdn.net/callback.htm" frameborder="0" height="600" width="400" scrolling="no"></iframe>');

        $('#popup_mask').css({
            opacity: 0.5,
            width: $( document ).width() + 'px',
            height:  $( document ).height() + 'px'
        });
        $('#popup_mask').css("display","block");
 
        $logpop.css( {
            top: ($( window ).height() - $logpop.height())/ 2  + $( window 
       ).scrollTop() + 'px',
            left:($( window ).width() - $logpop.width())/ 2
        } );
 
        setTimeout( function () {
            $logpop.show();
            $logpop.css( {
                opacity: 1
            } );
        }, 200 );
 
        $('#popup_mask').unbind("click");
        $('#popup_mask').bind("click", function(){
            $('#popup_mask').hide();
            var $clopop = $("#pop_win");
            $("#common_ask_div_sc").css("display","none");
            $clopop.css( {
                opacity: 0
            } );
            setTimeout( function () {
                $clopop.hide();
            }, 350 );
            return false;
        });
    }   

    var articletitle='使用 GitHub, Jekyll 打造自己的免费独立博客';

</script>










                        <div class="clear">
                        </div>
                    </div>                   
                
            </div>
                   
           <div id="side">
               
    <div class="side">
<div id="panel_Profile" class="panel">
<ul class="panel_head"><span>个人资料</span></ul>
<ul class="panel_body profile">
<div id="blog_userface">
    <a href="http://my.csdn.net/on_1y" target="_blank">
    <img src="http://avatar.csdn.net/1/C/2/1_on_1y.jpg" title="访问我的空间" style="max-width:90%"/>
    </a>
    <br />
    <span><a href="http://my.csdn.net/on_1y" class="user_name" target="_blank">on_1y</a></span>
</div>
<div class="interact">

    <a href="javascript:void(0);" class="attent" id="span_add_follow" title="[加关注]"></a>

 <a href="javascript:void(0);" class="letter"  title="[发私信]" onclick="window.open('http://msg.csdn.net/letters/model?receiver=on_1y','_blank','height=350,width=700');_gaq.push(['_trackEvent','function', 'onclick', 'blog_articles_sixin'])"></a>  
</div>
<div id="blog_medal">
                <div id="bms_box">
                                            <a  target="_blank">
                                                    <img src="http://c.csdnimg.cn/jifen/images/xunzhang/xunzhang/zhuanlandaren.png" onmouseover="m_over_m(this,2)" onmouseout="m_out_m()" alt="1" >
                                            </a>
               </div>
</div>
<ul id="blog_rank">
    <li>访问：<span>502931次</span></li>
    <li>积分：<span>5371</span> </li>    
    <li >等级： <span style="position:relative;display:inline-block;z-index:1" >
            <img src="http://c.csdnimg.cn/jifen/images/xunzhang/jianzhang/blog6.png" alt="" style="vertical-align: middle;" id="leveImg">
            <div id="smallTittle" style=" position: absolute;  left: -24px;  top: 25px;  text-align: center;  width: 101px;  height: 32px;  background-color: #fff;  line-height: 32px;  border: 2px #DDDDDD solid;  box-shadow: 0px 2px 2px rgba (0,0,0,0.1);  display: none;   z-index: 999;">
            <div style="left: 42%;  top: -8px;  position: absolute;  width: 0;  height: 0;  border-left: 10px solid transparent;  border-right: 10px solid transparent;  border-bottom: 8px solid #EAEAEA;"></div>
            积分：5371 </div>
        </span>  </li>
    <li>排名：<span>第5050名</span></li>
</ul>
<ul id="blog_statistics">
    <li>原创：<span>93篇</span></li>
    <li>转载：<span>0篇</span></li>
    <li>译文：<span>11篇</span></li>
    <li>评论：<span>123条</span></li>
</ul>
</ul>
</div>




<div id="custom_column_22773588" class="panel">
<ul class="panel_head"><span>GitHub</span></ul>
<ul class="panel_body">

https://github.com/minixalpha

</ul>
</div><div class="panel" id="panel_Search">
    <ul class="panel_head"><span>文章搜索</span></ul>
    <ul class="panel_body" class="form_search">
        <form id="frmSearch" action="http://so.csdn.net/search" class="form_search csdn-tracking-statistics" target="_blank"  data-mod="popu_306">
        <span><input id="inputSearch" type="text" class="blogsearch" title="请输入关键字" /></span>
        <input id="btnSubmit" type="button" value="搜索" title="search in blog" />
        <input type="hidden" name="q" id="inputQ" />
        <input type="hidden" name="t" value="blog" />
        <a id="btnSearchBlog" target="_blank"></a>
        </form>
    </ul>
</div>

<script type="text/javascript">

   
    $(function () {
        $("#btnSubmit").unbind("click");
        $("#btnSubmit").click(function () {           
            search();
        });

        $("#frmSearch").submit(function () {           
            search();
            return false;
        });

        function search()
        {
            if ($("#inputSearch").val() == "") {               
                alert("请录入搜索关键词！");                         
                return false;
            }
            //var url = "http://so.csdn.net/so/search/s.do?q=" + encodeURIComponent($("#inputSearch").val()) + "&u=" + username + "&t=blog";           
            var url = "https://www.baidu.com/s?wd=" + encodeURIComponent($("#inputSearch").val()) + "%20site%3Ablog.csdn.net"
            window.location.href = url;
        }   
    });
</script><div id="panel_Category" class="panel">
    <ul class="panel_head"><span>博客专栏</span></ul>
    <ul class="panel_body" id="sp_column">
    <table cellpadding="0" cellspacing="0"><tr>
    <td style="padding:10px 10px 0 0;">
    <a href="http://blog.csdn.net/column/details/openjdk-src-reading.html" target="_blank"><img src="http://img.blog.csdn.net/20151123175902739" style="width:75px;height:75px;" /></a>
    </td>
    <td style="padding:10px 0; vertical-align:top;">
    <a href="http://blog.csdn.net/column/details/openjdk-src-reading.html" target="_blank">OpenJDK源代码阅读</a>
    <p>文章：13篇</p>
    <span>阅读：29741</span>
    </td>
    </tr></table>
    </ul>
</div><div id="panel_Category" class="panel">
<ul class="panel_head"><span>文章分类</span></ul>
<ul class="panel_body">    
                 <li>
                    <a href="/on_1y/article/category/1296273" onclick="_gaq.push(['_trackEvent','function', 'onclick', 'blog_articles_wenzhangfenlei']); ">数学</a><span>(3)</span>
                </li>
                 <li>
                    <a href="/on_1y/article/category/1296272" onclick="_gaq.push(['_trackEvent','function', 'onclick', 'blog_articles_wenzhangfenlei']); ">计算机科学</a><span>(7)</span>
                </li>
                 <li>
                    <a href="/on_1y/article/category/1128018" onclick="_gaq.push(['_trackEvent','function', 'onclick', 'blog_articles_wenzhangfenlei']); ">算法</a><span>(4)</span>
                </li>
                 <li>
                    <a href="/on_1y/article/category/1128019" onclick="_gaq.push(['_trackEvent','function', 'onclick', 'blog_articles_wenzhangfenlei']); ">编程语言</a><span>(46)</span>
                </li>
                 <li>
                    <a href="/on_1y/article/category/1128103" onclick="_gaq.push(['_trackEvent','function', 'onclick', 'blog_articles_wenzhangfenlei']); ">工具</a><span>(8)</span>
                </li>
                 <li>
                    <a href="/on_1y/article/category/1128104" onclick="_gaq.push(['_trackEvent','function', 'onclick', 'blog_articles_wenzhangfenlei']); ">生活感悟</a><span>(4)</span>
                </li>
                 <li>
                    <a href="/on_1y/article/category/1241556" onclick="_gaq.push(['_trackEvent','function', 'onclick', 'blog_articles_wenzhangfenlei']); ">Linux</a><span>(19)</span>
                </li>
                 <li>
                    <a href="/on_1y/article/category/1296249" onclick="_gaq.push(['_trackEvent','function', 'onclick', 'blog_articles_wenzhangfenlei']); ">Haskell</a><span>(10)</span>
                </li>
                 <li>
                    <a href="/on_1y/article/category/1349346" onclick="_gaq.push(['_trackEvent','function', 'onclick', 'blog_articles_wenzhangfenlei']); ">Python</a><span>(20)</span>
                </li>
                 <li>
                    <a href="/on_1y/article/category/1370993" onclick="_gaq.push(['_trackEvent','function', 'onclick', 'blog_articles_wenzhangfenlei']); ">自然语言处理</a><span>(2)</span>
                </li>
                 <li>
                    <a href="/on_1y/article/category/1559953" onclick="_gaq.push(['_trackEvent','function', 'onclick', 'blog_articles_wenzhangfenlei']); ">数据结构</a><span>(6)</span>
                </li>
                 <li>
                    <a href="/on_1y/article/category/1633469" onclick="_gaq.push(['_trackEvent','function', 'onclick', 'blog_articles_wenzhangfenlei']); ">Web</a><span>(5)</span>
                </li>
                 <li>
                    <a href="/on_1y/article/category/1643691" onclick="_gaq.push(['_trackEvent','function', 'onclick', 'blog_articles_wenzhangfenlei']); ">深入理解计算机系统</a><span>(4)</span>
                </li>
                 <li>
                    <a href="/on_1y/article/category/1856475" onclick="_gaq.push(['_trackEvent','function', 'onclick', 'blog_articles_wenzhangfenlei']); ">软件工程</a><span>(1)</span>
                </li>
                 <li>
                    <a href="/on_1y/article/category/1912583" onclick="_gaq.push(['_trackEvent','function', 'onclick', 'blog_articles_wenzhangfenlei']); ">计算机网络</a><span>(2)</span>
                </li>
                 <li>
                    <a href="/on_1y/article/category/1919383" onclick="_gaq.push(['_trackEvent','function', 'onclick', 'blog_articles_wenzhangfenlei']); ">C语言</a><span>(5)</span>
                </li>
                 <li>
                    <a href="/on_1y/article/category/2228091" onclick="_gaq.push(['_trackEvent','function', 'onclick', 'blog_articles_wenzhangfenlei']); ">Java</a><span>(23)</span>
                </li>
                 <li>
                    <a href="/on_1y/article/category/2228093" onclick="_gaq.push(['_trackEvent','function', 'onclick', 'blog_articles_wenzhangfenlei']); ">虚拟机</a><span>(7)</span>
                </li>
                 <li>
                    <a href="/on_1y/article/category/2293761" onclick="_gaq.push(['_trackEvent','function', 'onclick', 'blog_articles_wenzhangfenlei']); ">源代码阅读</a><span>(15)</span>
                </li>
                 <li>
                    <a href="/on_1y/article/category/2439839" onclick="_gaq.push(['_trackEvent','function', 'onclick', 'blog_articles_wenzhangfenlei']); ">设计模式</a><span>(3)</span>
                </li>
                 <li>
                    <a href="/on_1y/article/category/2492899" onclick="_gaq.push(['_trackEvent','function', 'onclick', 'blog_articles_wenzhangfenlei']); ">内存模型</a><span>(3)</span>
                </li>
                 <li>
                    <a href="/on_1y/article/category/2843079" onclick="_gaq.push(['_trackEvent','function', 'onclick', 'blog_articles_wenzhangfenlei']); ">SICP</a><span>(3)</span>
                </li>
                 <li>
                    <a href="/on_1y/article/category/6093313" onclick="_gaq.push(['_trackEvent','function', 'onclick', 'blog_articles_wenzhangfenlei']); ">编译原理</a><span>(1)</span>
                </li>
                 <li>
                    <a href="/on_1y/article/category/6766305" onclick="_gaq.push(['_trackEvent','function', 'onclick', 'blog_articles_wenzhangfenlei']); ">架构</a><span>(1)</span>
                </li>
</ul>
</div><div id="panel_Archive" class="panel">
<ul class="panel_head"><span>文章存档</span></ul>
<ul class="panel_body">
<div id="archive_list">
<!--归档统计-->
<li><a href="/on_1y/article/month/2017/03">2017年03月</a><span>(1)</span></li><li><a href="/on_1y/article/month/2016/02">2016年02月</a><span>(2)</span></li><li><a href="/on_1y/article/month/2015/11">2015年11月</a><span>(1)</span></li><li><a href="/on_1y/article/month/2015/04">2015年04月</a><span>(1)</span></li><li><a href="/on_1y/article/month/2015/03">2015年03月</a><span>(1)</span></li><li><a href="/on_1y/article/month/2015/01">2015年01月</a><span>(3)</span></li><li><a href="/on_1y/article/month/2014/12">2014年12月</a><span>(1)</span></li><li><a href="/on_1y/article/month/2014/09">2014年09月</a><span>(2)</span></li><li><a href="/on_1y/article/month/2014/08">2014年08月</a><span>(6)</span></li><li><a href="/on_1y/article/month/2014/07">2014年07月</a><span>(5)</span></li><li><a href="/on_1y/article/month/2014/06">2014年06月</a><span>(5)</span></li><li><a href="/on_1y/article/month/2014/05">2014年05月</a><span>(6)</span></li><li><a href="/on_1y/article/month/2014/04">2014年04月</a><span>(2)</span></li><li><a href="/on_1y/article/month/2014/03">2014年03月</a><span>(2)</span></li><li><a href="/on_1y/article/month/2014/02">2014年02月</a><span>(2)</span></li><li><a href="/on_1y/article/month/2014/01">2014年01月</a><span>(3)</span></li><li><a href="/on_1y/article/month/2013/11">2013年11月</a><span>(1)</span></li><li><a href="/on_1y/article/month/2013/10">2013年10月</a><span>(2)</span></li><li><a href="/on_1y/article/month/2013/09">2013年09月</a><span>(2)</span></li><li><a href="/on_1y/article/month/2013/08">2013年08月</a><span>(1)</span></li><li><a href="/on_1y/article/month/2013/03">2013年03月</a><span>(11)</span></li><li><a href="/on_1y/article/month/2013/02">2013年02月</a><span>(29)</span></li><li><a href="/on_1y/article/month/2013/01">2013年01月</a><span>(1)</span></li><li><a href="/on_1y/article/month/2012/12">2012年12月</a><span>(2)</span></li><li><a href="/on_1y/article/month/2012/10">2012年10月</a><span>(2)</span></li><li><a href="/on_1y/article/month/2012/09">2012年09月</a><span>(1)</span></li><li><a href="/on_1y/article/month/2012/07">2012年07月</a><span>(2)</span></li><li><a href="/on_1y/article/month/2012/05">2012年05月</a><span>(3)</span></li><li><a href="/on_1y/article/month/2012/04">2012年04月</a><span>(4)</span></li>
</div>
</ul>
</div>
<div id="hotarticls" class="panel tracking-ad" data-mod="popu_340">
<ul class="panel_head">
    <span>       
阅读排行    </span>
</ul>

<ul class="panel_body itemlist">
<li>
<a href="/on_1y/article/details/19259435" title="使用 GitHub, Jekyll 打造自己的免费独立博客">使用 GitHub, Jekyll 打造自己的免费独立博客</a><span>(61678)</span>
</li>
<li>
<a href="/on_1y/article/details/8640012" title="「学习笔记——Python」Python中的类(classes)">「学习笔记——Python」Python中的类(classes)</a><span>(43349)</span>
</li>
<li>
<a href="/on_1y/article/details/18803563" title="WSGI 简介">WSGI 简介</a><span>(20663)</span>
</li>
<li>
<a href="/on_1y/article/details/8631204" title="「学习笔记——Python」Python 的错误和异常处理">「学习笔记——Python」Python 的错误和异常处理</a><span>(18814)</span>
</li>
<li>
<a href="/on_1y/article/details/8577913" title="【学习笔记——Linux】Linux下正确关机方法">【学习笔记——Linux】Linux下正确关机方法</a><span>(15240)</span>
</li>
<li>
<a href="/on_1y/article/details/20203963" title="控制台，终端，虚拟终端，tty，shell等概念的区别">控制台，终端，虚拟终端，tty，shell等概念的区别</a><span>(10248)</span>
</li>
<li>
<a href="/on_1y/article/details/13030439" title="字符指针与字符数组真正的区别">字符指针与字符数组真正的区别</a><span>(9960)</span>
</li>
<li>
<a href="/on_1y/article/details/24290985" title="对C语言中的static关键字的深入理解">对C语言中的static关键字的深入理解</a><span>(9661)</span>
</li>
<li>
<a href="/on_1y/article/details/8039298" title="Haskell Platform安装过程">Haskell Platform安装过程</a><span>(8617)</span>
</li>
<li>
<a href="/on_1y/article/details/38761511" title="在Ubuntu 12.04 上编译调试 OpenJDK8">在Ubuntu 12.04 上编译调试 OpenJDK8</a><span>(8172)</span>
</li>
</ul>
</div>
<div id="hotarticls2" class="panel tracking-ad" data-mod="popu_341">
<ul class="panel_head"><span>评论排行</span></ul>
<ul class="panel_body itemlist">
<li>
<a href="/on_1y/article/details/19259435" title="使用 GitHub, Jekyll 打造自己的免费独立博客">使用 GitHub, Jekyll 打造自己的免费独立博客</a><span>(43)</span>
</li>
<li>
<a href="/on_1y/article/details/18818081" title="wsgiref 源代码分析">wsgiref 源代码分析</a><span>(13)</span>
</li>
<li>
<a href="/on_1y/article/details/18803563" title="WSGI 简介">WSGI 简介</a><span>(7)</span>
</li>
<li>
<a href="/on_1y/article/details/30109975" title="OpenJDK 源代码阅读之 TimSort">OpenJDK 源代码阅读之 TimSort</a><span>(7)</span>
</li>
<li>
<a href="/on_1y/article/details/13760403" title="理解数据结构">理解数据结构</a><span>(5)</span>
</li>
<li>
<a href="/on_1y/article/details/8625728" title="从如何解决问题到如何学习算法">从如何解决问题到如何学习算法</a><span>(5)</span>
</li>
<li>
<a href="/on_1y/article/details/7477211" title="开篇：为什么开始写博客">开篇：为什么开始写博客</a><span>(5)</span>
</li>
<li>
<a href="/on_1y/article/details/27699513" title="OpenJDK 源代码阅读之 LinkedList">OpenJDK 源代码阅读之 LinkedList</a><span>(5)</span>
</li>
<li>
<a href="/on_1y/article/details/8561371" title="「学习总结-Haskell-1」Haskell 基础知识">「学习总结-Haskell-1」Haskell 基础知识</a><span>(4)</span>
</li>
<li>
<a href="/on_1y/article/details/13030439" title="字符指针与字符数组真正的区别">字符指针与字符数组真正的区别</a><span>(3)</span>
</li>
</ul>
</div>
<div id="newcomments" class="panel">
<ul class="panel_head"><span>最新评论</span></ul>
<ul class="panel_body itemlist">
    <li>
   
         <a href="/on_1y/article/details/24290985#comments">对C语言中的static关键字的深入理解</a>
    <p style="margin:0px;"><a href="/wenweiming_1" class="user_name">wenweiming_1</a>:
很深入！谢谢！
    </p>
    </li>
    <li>
   
         <a href="/on_1y/article/details/27352321#comments">OpenJDK 源代码阅读之 String</a>
    <p style="margin:0px;"><a href="/on_1y" class="user_name">on_1y</a>:
@qiyue199264:你是指 a, b 两个 String 里的 value[] 是存储在不同的...
    </p>
    </li>
    <li>
   
         <a href="/on_1y/article/details/27352321#comments">OpenJDK 源代码阅读之 String</a>
    <p style="margin:0px;"><a href="/qiyue199264" class="user_name">qiyue199264</a>:
楼主有个错误，如果用String b = new String(a); b是作为a的一个复制品，并不...
    </p>
    </li>
    <li>
   
         <a href="/on_1y/article/details/13030439#comments">字符指针与字符数组真正的区别</a>
    <p style="margin:0px;"><a href="/littesss" class="user_name">littesss</a>:
Mark
    </p>
    </li>
    <li>
   
         <a href="/on_1y/article/details/18818081#comments">wsgiref 源代码分析</a>
    <p style="margin:0px;"><a href="/bestallen" class="user_name">bestallen</a>:
实在是谢谢博主辛苦的梳理解读，对WSGI的理解有非常非常大的帮助！
    </p>
    </li>
    <li>
   
         <a href="/on_1y/article/details/19259435#comments">使用 GitHub, Jekyll 打造自己的免费独立博客</a>
    <p style="margin:0px;"><a href="/zhangwei900808" class="user_name">zhangwei900808</a>:
太好了，谢谢楼主
    </p>
    </li>
    <li>
   
         <a href="/on_1y/article/details/19259435#comments">使用 GitHub, Jekyll 打造自己的免费独立博客</a>
    <p style="margin:0px;"><a href="/u013861109" class="user_name">u013861109</a>:
版主在吗，Makefile怎么使用，win系统如何使用呢！麻烦版主帮帮忙
    </p>
    </li>
    <li>
   
         <a href="/on_1y/article/details/19259435#comments">使用 GitHub, Jekyll 打造自己的免费独立博客</a>
    <p style="margin:0px;"><a href="/u013861109" class="user_name">u013861109</a>:
版主这里的make 如何使用
    </p>
    </li>
    <li>
   
         <a href="/on_1y/article/details/19259435#comments">wsgiref 源代码分析</a>
    <p style="margin:0px;"><a href="/u010136741" class="user_name">u010136741</a>:
大侠，请问你画这些图是用什么工具啊，谢谢
    </p>
    </li>
    <li>
   
         <a href="/on_1y/article/details/8603465#comments">「学习笔记——Python」《The Python Tutorial》学习笔记</a>
    <p style="margin:0px;"><a href="/SuGuolin" class="user_name">SuGuolin</a>:
非常赞，翻译了文档给英文差的人很大帮助
    </p>
    </li>
</ul>
</div>
    </div>
    <div class="clear">
    </div>

                   <!-- 广告位开始 -->                    <!-- 广告位结束 -->
                   <div class="tracking-ad" data-view="true"  data-mtp="63" data-order="40" data-con="ad_content_1260" style="width: 200px; height: 500px;">
                         <div id="nav_show_top_stop" style="width: 200px;height: 500px;z-index:1000"><div id="cpro_u2734128"></div>
                             <div id="cpro_u3031287"></div></div>
                   </div>
                <script type="text/javascript">
                    setTimeout(function () {
                        var naviga_offsetTop = 0;
                        function naviga_stay_top() { var scrollTop = jQuery(document).scrollTop(); if (scrollTop > naviga_offsetTop) { jQuery("#nav_show_top_stop").css({ "position": "fixed" }); jQuery("#nav_show_top_stop").css({ "top": "0px" }); } else { jQuery("#nav_show_top_stop").css({ "position": "fixed" }); jQuery("#nav_show_top_stop").css({ "top": naviga_offsetTop - scrollTop + "px" }); } }
                        function onload_function() { naviga_offsetTop = jQuery("#nav_show_top_stop").position().top; jQuery(window).bind("scroll", naviga_stay_top); jQuery(window).bind("mousewheel", naviga_stay_top); jQuery(document).bind("scroll", naviga_stay_top); jQuery(document).bind("mousewheel", naviga_stay_top); } jQuery(document).ready(onload_function);

                    }, 200);
                </script>                    
<script type="text/javascript">(window.cproArray = window.cproArray || []).push({ id: "u2734128" });  </script> 
                    <script src="http://cpro.baidustatic.com/cpro/ui/c.js" type="text/javascript"></script> 
                   <script type="text/javascript">
                       /*PC端-博客内容页左侧Button2-200*200-2017/7/10*/
                       (window.cproArray = window.cproArray || []).push({ id: "u3031287" });
</script>
<script type="text/javascript" src="http://cpro.baidustatic.com/cpro/ui/c.js"></script>

           </div>   

            <div class="clear">
            </div>
        </div>

        








    <script type="text/javascript" src="http://passport.csdn.net/content/loginbox/login.js"></script>
<script type="text/javascript">
    $(function () {
        function __get_code_toolbar(snippet_id) {
            return $("<span class='tracking-ad' data-mod='popu_167'><a href='https://code.csdn.net/snippets/"
                    + snippet_id
                    + "' target='_blank' title='在CODE上查看代码片'  style='text-indent:0;'><img src='https://code.csdn.net/assets/CODE_ico.png' width=12 height=12 alt='在CODE上查看代码片' style='position:relative;top:1px;left:2px;'/></a></span>"
                    + "<span class='tracking-ad' data-mod='popu_170'><a href='https://code.csdn.net/snippets/"
                    + snippet_id
                    + "/fork' target='_blank' title='派生到我的代码片' style='text-indent:0;'><img src='https://code.csdn.net/assets/ico_fork.svg' width=12 height=12 alt='派生到我的代码片' style='position:relative;top:2px;left:2px;'/></a></span>");
        }
        
        $("[code_snippet_id]").each(function () {
            __s_id = $(this).attr("code_snippet_id");
            if (__s_id != null && __s_id != "" && __s_id != 0 && parseInt(__s_id) > 70020) {
                __code_tool = __get_code_toolbar(__s_id);
                $(this).prev().find(".tools").append(__code_tool);
            }
        });

        $(".bar").show();
    });
</script>





    </div>
      <!--new top-->
    

     

   
   
     <!--new top-->
   
   

    
    
    
   

   


       <script type="text/javascript" src="http://static.blog.csdn.net/public/res/bower-libs/MathJax/MathJax.js?config=TeX-AMS_HTML"></script>
          <script type="text/javascript">
              //$(function () {
              //    setTimeout(function () {
              //        var searchtitletags = articletitle + ',' + $("#tags").html();
              //        searchService({
              //            index: 'blog',
              //            query: searchtitletags,
              //            from: 5,
              //            size: 5,
              //            appendTo: '#res',
              //            url: 'recommend',
              //            his: 2,
              //            client: "blog_cf_enhance",
              //            tmpl: '<dd style="background:url(http://static.blog.csdn.net/skin/default/images/blog-dot-red3.gif) no-repeat 0 10px;"><a href="#{ url }" title="#{ title }" strategy="#{ strategy }">#{ title }</a></dd>'
              //        });
              //    }, 1000);
              //});

         </script>
    
    <script src="http://static.blog.csdn.net/scripts/csdn_blog_detail.min.js" type="text/javascript"></script>
        
    <script type="text/javascript" src="http://c.csdnimg.cn/blog/csdn_public_blog_detail.min.js?20170719001"></script>

    <script type="text/javascript" src="http://medal.blog.csdn.net/showblogmedal.ashx?blogid=1114899"></script>

     
    


  <div id="a52b5334d" style="width: 1px; height: 1px; display: none;">
                    <script id="adJs52b5334"></script>
                    <script>document.getElementById("adJs52b5334").src = "http://ads.csdn.net/js/opt/52b5334.js?t=" + Math.random();</script>
   </div>

    
    
        
     

    
          
    <div class="pop_CA_cover"  style="display:none"></div>
    <div class="pop pop_CA"  style="display:none">
          <div class="CA_header">
            收藏助手
            <span class="cancel_icon"  id="fapancle"  onclick="$('.pop_CA').hide();$('.pop_CA_cover').hide();"></span>
          </div>
          <iframe src="" id="fa" frameborder="0" width="100%" height="360"  scrolling="no" ></iframe>
    </div>


        <script type="text/javascript">

            $(function () {
                var fromjs = $("#fromjs");
                if (fromjs.length > 0) {
                    $("#fromjs .markdown_views pre").addClass("prettyprint");
                    prettyPrint();

                    $('pre.prettyprint code').each(function () {
                        var lines = $(this).text().split('\n').length;
                        var $numbering = $('<ul/>').addClass('pre-numbering').hide();
                        $(this).addClass('has-numbering').parent().append($numbering);
                        for (i = 1; i <= lines; i++) {
                            $numbering.append($('<li/>').text(i));
                        };
                        $numbering.fadeIn(1700);
                    });

                    $('.pre-numbering li').css("color", "#999");
                }
            });

            $(".markdown_views a[target!='_blank']").attr("target", "_blank");

            //$(".toc a[target='_blank']").attr("target", "");

            setTimeout(function () {
                $(".toc a[target='_blank']").attr("target", "");
            }, 500);

        </script>

</body>
</html>   
