<meta http-equiv="Content-Type" content="text/html; charset=utf-8" /><div id="wenzhangToubu"></div>

   

        <div>
        
        <div>
            2014-02-15 23:07
            61693人阅读
             <a href="#comments" target="_blank">评论</a>(43)
             <a href="javascript:void(0);" title="收藏" target="_blank">收藏</a>
              <a href="#report" title="举报" target="_blank">举报</a>

        </div>
        
    
      
        <div>         
            <p>版权声明：本文为博主原创文章，未经博主允许不得转载。</p>
        </div>

  

  
  
     


<div id="article_content">

<h1>
使用 GitHub, Jekyll 打造自己的免费独立博客</h1>
<p>
<a href="https://github.com/" target="_blank">GitHub</a>是一个代码托管网站，现在很多开源项目都放在GitHub上。 利用GitHub，可以让全球各地的程序员们一起协作开发。GitHub 提供了一种功能，叫 <a href="https://help.github.com/categories/20/articles" target="_blank">GitHub
 Pages</a>, 利用这个功能，我 们可以为项目建立网站，当然，这也意味着我们可以通过 GitHub Pages 建立自己的网站。</p>
<p>
<a href="http://jekyllrb.com/" target="_blank">Jekyll</a>是一个简单的，针对博客设计的静态网站生成器。使用 GitHub 和 Jekyll，我们可以打造自己的独立博客，你可以自由地定制网站的风格，并且这 一切都是免费的。</p>
<p>
这是我在GitHub上自己建立的<a href="http://minixalpha.github.io" target="_blank">博客</a> 及<a href="https://github.com/minixalpha/minixalpha.github.io" target="_blank">源代码</a> （两个分支），在下文的讲解中，你可以随时查看博客的源代码，以便有直观的认识。</p>
<p>
网站截图：</p>
<p>
<div class="soucangLargeImageContainer"><img src="http://img.blog.csdn.net/20140215230442406?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvb25fMXk=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast" /></div></p>

<p>
GitHub Pages 的 <a href="http://pages.github.com/" target="_blank">主页</a> 提供了一个简单的入门指引，阅读并 操作一下，会有一个直观简单的认识。</p>
<p>
阮一峰的文章《<a href="http://www.ruanyifeng.com/blog/2012/08/blogging_with_jekyll.html" target="_blank">搭建一个免费的，无限流量的Blog----github Pages和Jekyll入门</a>》是使用 GitHub 和 Jekyll 搭建独立博客非常好的入门文章，强烈建议先阅读并操作一遍。</p>
<h2>
建立自己的博客</h2>
<p>
在学习完阮一峰同学的文章后，你就已经有能力搭建自己的独立博客了，但是这个博客 只有最基本的功能，并且也不好看。这时候，你面临几个选择:</p>
<ol>
<li>完全自己定制博客</li><li>找一份框架，修改后使用</li><li>从GitHub上fork别人的博客代码，在其中添加自己的文章</li></ol>
<p>
如果选择 2, 那么 <a href="http://jekyllbootstrap.com/" target="_blank">jekyll-bootstrap</a>是一个选择。 </p>
<p>
如果选择 3, 那么自己Google一下 <code>github.io
 博客</code> 能找到不少博客,去fork,然后修改一下就好。 最近有一个 <a href="https://github.com/barryclark/jekyll-now" target="_blank">
jekyll-now</a>，在 GitHub 上已经获取了 1000+ 的fork，可以关注一下。这个项目的特点是，所有操作都是通过网站进行的，不需要懂命令行。另外， 我自己也有一个非常简洁的项目，也不需要懂命令行，直接通过网页操作，就可以有一个自己的博客了。如果只需要这一个简单的博客，可以直接看最后一节:<a href="#t8" target="_blank">一个极简风格的博客</a>。</p>
<p>
如果选择 1, 那么可以好好看看后文的内容。</p>
<h2>
GitHub
 + Jekyll 工作机制</h2>


<ol>
<li>  简单地说，你在 GitHub
 上有一个账号，名为<code>username</code>(任意)，
 有一个项目，名为 <code>username.github.io</code>(固定格式，username与账号名一致)，
 项目分支名为 <code>master</code>(固定)，这个分支有着类似下面的
 目录结构:</li></ol>
<pre><code>.
├── index.html
├── _config.yml
├── assets
│   ├── blog-images
│   ├── css
│   ├── fonts
│   ├── images
│   └── javascripts
├── _includes
├── _layouts
├── _plugins
├── _posts
└── _site
</code></pre>
<p>
这样，当你访问 <code>http://username.github.io/</code>时，GitHub
 会使用 Jekyll 解析 用户 <code>username</code>名下的<code>username.github.io</code>项目中，分支为<code>master</code> 的源代码，为你构建一个静态网站，并将生成的 <code>index.html</code> 展示给你。</p>
<p>
关于这个目录更多的内容，我们还不需要关心，如果你好奇心比较重，可以先看 后文<code>源代码</code>一节。</p>
<p>
看完上面的解释，你可能会有一些疑问，因为按照上面的说法，一个用户只能有一个 网站，那我有很多项目，每个项目都需要一个项目网站，该怎么办呢？另外，在阮一峰 同学的文章中，特别提到，分支名应该为 <code>gh-pages</code>，这又是怎么回事呢？</p>
<p>
原来，GitHub认为，一个GitHub账号对应一个用户或者一个组织，GitHub会 给这个用户分配一个域名：<code>username.github.io</code>，当用户访问这个域名时，
 GitHub会去解析<code>username</code>用户下，<code>username.github.io</code>项目的<code>master</code>分支，
 这与我们之前的描述一致。</p>
<p>
另外，GitHub还为每个项目提供了域名，例如，你有一个项目名为<code>blog</code>，
 GitHub为这个项目提供的域名为<code>username.github.io/blog</code>，
 当你访问这个域名时，GitHub会去解析<code>username</code>用户下，<code>blog</code>项目的<code>gh-pages</code> 分支。</p>
<p>
所以，要搭建自己的博客，你可以选择建立名为 <code>username.github.io</code>的项目，
 在<code>master</code>分支下存放网站源代码，也可以选择建立名为 <code>blog</code> 的项目，在 <code>gh-pages</code>分支下存放网站源代码。</p>
<p>
GitHub 的 Help 文档中的 <a href="https://help.github.com/articles/user-organization-and-project-pages" target="_blank">User, Organization and Project Pages</a>对此有 详细的描述。</p>

<p>
Jekyll 提供了插件功能，在网站源代码目录下，有一个名为 <code>_plugins</code>的目录，
 你可以将一些插件放进去，这样，Jekyll在解析网站源代码时，就会运行你的插件， 这样插件是 Ruby 写成的。可以为Jekyll添加功能，例如，Jekyll默认是不提供分类 页面的，你可以写一个插件，根据文章内容生成分类页面。如果没有插件，你只能每 次写文章，添加分类时，为每个分类手动写 HTML 页面。</p>
<p>
在本地运行 Jekyll 时，这些插件会自动被调用，但是GitHub在解析网站源代码时， 出于安全考虑，会开启安全模式，禁用这些插件。我们既想用这些插件，又想用 GitHub，怎么办呢怎么办呢？</p>
<p>
GitHub还为我们提供了更一种解析网站的方式，那就是直接上传最终的静态网页， 这样，我们可以在本地使用 Jeklly 把网站解析出来，然后再上传到 GitHub上， 这就使得我们既使用了插件，又使用了 GitHub。在上文的目录结构中，有一个 名为 <code>_site</code> 的目录，这个就是Jeklly在本地解析时最终生成的静态网站，我们
 把其中的内容上传到 GitHub 的项目中就可以了。例如，我在GitHub上的网站， 既解析后的 <code>_site</code> 目录，大概是这样的:</p>
<pre><code>.

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
<p>
其中的 <code>categories</code>，<code>2013</code>, <code>2014</code> 目录就是分类插件和归档插件帮助我生成的，
 我只要把这个目录下的内容上传到 GitHub 相应的项目分支中就可以了。这样，你 访问 <code>username.github.io</code>时，GitHub就不解析了，直接把<code>index.html</code>返回给你了。</p>

<p>
关于 <a href="http://lib.csdn.net/base/git" title="Git知识库" target="_blank">Git</a> 和 jekyll 的安装与基本使用，这里就不多说了。</p>

<p>
如果你不使用插件，那么只需要维护一个分支就好:</p>
<pre><code>- username/username.github.io 的 master 分支
- username/blog 的 gh-pages 分支
</code></pre>
<p>
其中 <code>username</code> 是你的
 GitHub 帐号。</p>
<p>
你需要在本地维护一份网站源代码，添加新文章后，使用 jekyll 在本地<a href="http://lib.csdn.net/base/softwaretest" title="软件测试知识库" target="_blank">测试</a>一下， 没有问题后，commit 到 GitHub 上的相应分支中就可以了。</p>

<p>
如果你需要使用插件，那么需要维护两个分支，一个是网站的源代码分支 ，另一个 是 由Jeklly 解析源代码后生成的静态网站。</p>
<p>例如，如果项目名为 username.github.io，的源代码分支名为 <code>source</code>，静态网站分支名为master。平时写博客时，
 首先在 source 分支下，添加新文章，然后本地使用 jekyll build 将添加文章后的网站 解析一次，这时 <code>_site</code> 目录下就有新网站的静态代码了。然后把这个目录下的所有内容
 复制到 master 分支下。这个过程，可以写一个
 Makefile，每次添加文章后 make 一下， 就自动将文章发布到 GitHub 上。</p>
<p>
Makefile 内容如下：</p>
<pre><code>
deploy:
    git checkout source
    jekyll build
    git add -A
    git commit -m "update source"
    cp -r _site/ /tmp/
    git checkout master
    rm -r ./*
    cp -r /tmp/_site/* ./
    git add -A
    git commit -m "deploy blog"
    git push origin master
    git checkout source
    echo "deploy succeed"
    git push origin source
    echo "push source"</code></pre>
<p>
下面的内容涉及源代码，如果需要进一步学习，或者有问题，可以在 <a href="http://jekyllrb.com/" target="_blank">Jeklly 官网</a>上找到更详细的解释，或者在评论中留言。</p>

<p>
再来看一下这个目录结构：</p>
<pre><code>.
├── _config.yml
├── index.html
├── assets
│   ├── blog-images
│   ├── css
│   ├── fonts
│   ├── images
│   └── javascripts
├── _includes
├── _layouts
├── _plugins
├── _posts
└── _site
</code></pre>
<ul>
<li>_config.yml</li></ul>
<p>
这是针对 Jekyll 的<a href="http://jekyllrb.com/docs/configuration/" target="_blank">配置文件</a>， 决定了 Jekyll 如何解析网站的源代码,下面是一个示例：</p>
<pre><code>baseurl: /StrayBirds
markdown: redcarpet
safe: false
pygments: true
excerpt_separator: "\n\n\n"
paginate: 5
</code></pre>
<p>
我的网站建立在 <code>StrayBirds</code> 项目中，所以 <code>baseurl</code> 设置成 <code>StrayBirds</code>，
 我的文章采用 Markdown 格式写成，可以指定 Markdown 的解析器 <code>redcarpet</code>。
 另外，安全模式需要关闭，以便 Jekyll 解析时会运行插件。 <code>pygments</code> 可以使得Jekyll解析文章中源代码时加入特殊标记，例如指定代码类型，
 这可以被很多 <a href="http://lib.csdn.net/base/javascript" title="JavaScript知识库" target="_blank">JavaScript</a> 代码高度库使用。 <code>excerpt_separator</code> 指定了一个摘要分割符号，这样
 Jekyll 可以在解析文章时， 将文章的提要提取出来。 paginate 指定了一页有几篇文章，页数太多时，我们可以将文章列表分页，我们在 后文还会提到。</p>
<ul>
<li>_layouts</li></ul>
<p>
这个目录存放着一些网页模板文件，为网站所有网页提供一个基本模板，这样 每个网页只需要关心自己的内容就好，其它的都由模板决定。例如，这个目录下的 default.html 文件：</p>
<div>
<pre>&lt;!DOCTYPE html&gt;
&lt;html&gt;
  &lt;head&gt;
    &lt;meta charset='utf-8'&gt;
    &lt;title&gt;{{ page.title }}&lt;/title&gt;
  &lt;/head&gt;
  &lt;body&gt;
    &lt;header&gt;
    &lt;/header&gt;

    &lt;aside&gt;
    &lt;/aside&gt;

    &lt;article&gt;
{{ content }}
    &lt;/article&gt;

    &lt;footer&gt;
    &lt;/footer&gt;
  &lt;/body&gt;
&lt;/html&gt;


</pre>
</div>
<p>
可以看出，这个文件就是所有页面共有的东西，每个页面的具体内容会被填充在 <code>{{
 content }}</code> 中，注意这个 content 两边的标记，这是一种叫 <a href="https://github.com/Shopify/liquid" target="_blank">liquid</a> 的标记语言。 另外，还有那个 <code>{{
 page.title }}</code> ，其中 <code>page</code> 表示引用 <code>default.html</code>的
 那个页面，这个页面的 <code>title</code> 值会在 <code>page</code> 相应页面中被设置，例如
 下面的 <code>index.html</code> 文件，开头部分就设置了 <code>title</code>值。</p>
<ul>
<li>index.html</li></ul>
<p>
这是网站的首页，访问 <code>http://username.github.io</code> 时，会指向 <code>http://username.github.io/index.html</code>，我们看一下基本内容：</p>
<div>
<pre>---
layout: default
title: 首页
---

&lt;ul class="post-list"&gt;
    {% for post in site.posts %}
        &lt;a href="{{site.baseurl}}{{post.url}}"&gt; {{ post.title }}  &lt;/a&gt; &lt;br&gt;
        {{ post.date | date: "%F" }} &lt;br&gt;
        {{ post.category }} &lt;br&gt;
        {{ post.excerpt }} 
    {% endfor %}
&lt;/ul&gt;
</pre>
</div>
<p>
注意，文件开头的描述，我们称之为 <a href="http://jekyllrb.com/docs/frontmatter/" target="_blank">front-matter</a>， 是对当前文件的一种描述，这里 设置的变量可以在解析时被引用，例如这里的 <code>layout</code>就会告诉
 Jekyll, 生成 <code>index.html</code> 文件时，去 <code>_layouts</code> 目录下找 <code>default.html</code> 文件，然后把当前文件解析后，添加到 <code>default.html</code> 的 <code>content</code> 部分，组成最终的 <code>index.html</code> 文件。还有<code>title</code> 设置好的
 值，会在 <code>default.html</code> 中通过 <code>page.title</code> 被引用。</p>
<p>
文件的主体部分遍历了站点的所有文章，并将他们显示出来，这些语法都是 <code>liquid</code> 语法，
 其中的变量，例如 <code>site</code>,
 由 Jekyll 设置我们只需要引用就可以了。而 <code>post</code> 中的变量，
 如 <code>post.title</code>, <code>post.category</code> 是由 <code>post</code> 文件中的
 front-matter 决定，后面马上就会看到。</p>
<ul>
<li>_posts</li></ul>
<p>
这个目录存放我们的所有博客文章，他们的名字有统一的格式：</p>
<pre><code>YEAR-MONTH-DAY-title.MARKUP
</code></pre>
<p>
例如，2014-02-15-github-jeklly.md，这个文件名会被解析，前面的 <code>index.html</code> 中， <code>post.date</code> 的值就由这里文件名中的日期而来。下面，我们看看一篇文章的内容示例：</p>
<pre><code>---
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
<p>
可以看出，文章的 front-matter 部分设置了多项值，以后可以通过类似 <code>post.title</code>, <code>post.category</code> 的方式引用这些些，另外，<code>layout</code>部分的值和之前解释的一样，
 文件的内容会被填充到 <code>_layouts/default.html</code> 文件的 <code>content</code> 变量中。</p>
<p>
另外，文章中 <code>为什么不试试呢</code>之后的有三个不可见的 <code>\n</code>，它决定了这三个 <code>\n</code> 之前的内容会被放在 <code>post.excerpt</code> 变量中，供其它文件使用。</p>
<ul>
<li>_includes</li></ul>
<p>
这个文件中，存放着一些模块文件，例如 <code>categories.ext</code>，其它文件可以通过</p>
<pre><code>{% raw %}
{% include categories.ext %}
{% endraw %}
</code></pre>
<p>
来引用这个文件的内容，方便代码模块化和重用。我的博客 <a href="http://minixalpha.github.io/StrayBirds/" target="_blank">主页</a>上的 分类，归档，这些模块的代码都是通过这种方式引用的。</p>
<ul>
<li>_plugins</li></ul>
<p>
这个文件中存放一些Ruby插件, 例如 <code>gen_categories.rb</code>，这些文件会在
 Jekyll 解析网站源代码时被执行。下一节讲述的就是插件。</p>
<ul>
<li>_site</li></ul>
<p>
Jekyll 解析整个网站源代码后，会将最终的静态网站源代码放在这里</p>

<p>
插件使用 Ruby 写成，放在 _plugins 目录下，有些 Jekyll 没有的功能，又不能 手动添加，因为页面的内容会随着文章日期类别的不同而不同，例如分类功能和归档功能， 这时，就需要使用插件自动生成一些页面和目录。</p>
<ul>
<li>分类 我的分类插件使用的是 <a href="https://github.com/shigeya/jekyll-category-archive-plugin/tree/master/_plugins" target="_blank">jekyll-category-archive-plugin</a>, 它会根据网站文章的分类信息，为每个类别生成一个页面。</li></ul>
<p>
使用方法是，把 plugins/categoryarchive_plugin.rb 放在 plugins 目录下， 把 _layouts/categoryarchive.html 放在 layouts 目录下， 这样，这个插件会在Jekyll解析网站时，生成相应categories目录，目录下是各个分类， 每个分类下都有一个 <code>index.html</code> 文件，这个文件是根据模板文件
 categoryarchive.html 生成的，例如：</p>
<pre><code>_site/categories/
├── 工具
│   └── index.html
├── 思想
│   └── index.html
├── 技术
│   └── index.html
└── 源代码阅读
    └── index.html
</code></pre>
<p>
然后，你就可以通过 <code>http://username.github.io/blog/categories/工具/</code> 访问 <code>工具</code>类下的 <code>index.html</code> 文件。</p>
<ul>
<li>归档 我的归档插件使用的是 <a href="https://github.com/shigeya/jekyll-monthly-archive-plugin" target="_blank">jekyll-monthly-archive-plugin</a>,它会根据网站 _posts目录下的文章日期，为每个月生成一个页面。</li></ul>
<p>
使用方法同上。注意，这个插件在 jekyll-1.4.2 中可能会出错，在 jekyll-1.2.0 中没有错误。</p>


<p>
当文章很多时，就需要使用分页功能，在 Jekyll 官网上提供了一种 <a href="http://jekyllrb.com/docs/pagination/" target="_blank">实现</a>，把相应代码放在 主页上，然后在 <code>_config.yml</code> 中设置 <code>paginate</code> 值就行了。</p>

<p>
评论功能需要使用外挂，我使用的是 <a href="http://disqus.com/" target="_blank">DISQUS</a>, 注册 之后，将评论区的一段代码放在你需要使用评论功能的页面上, 然后，通过在页面的 front-matter 部分使用</p>
<pre><code>comments: true
</code></pre>
<p>
启用评论。<strong>此外，如果你 fork 了我的项目，需要修改 `_inclusds/</strong><strong>comments.ext`，把里面的
 `disqus_shortname ` 修改成你的博客短名，这个在注册的时候会设置。</strong></p>
<p>
评论区截图：</p>
<p>
<div class="soucangLargeImageContainer"><img src="http://img.blog.csdn.net/20140215230506156?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvb25fMXk=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast" /></div></p>
<p>
基本的内容就介绍到这里，任何问题，欢迎留言。</p>
<p>
另外，如果这篇文章对你有用的话，在<a href="https://github.com/minixalpha/minixalpha.github.io" target="_blank">GitHub</a>上帮我点个 star 吧，即是对我的肯定，也可以帮助更多的人。</p>
<p>
另外，注意如果你要 fork 我的模板，注意里面有些链接是与我的 GitHub 名 minixalpha 相关的，在使用前最好批量地将这个字符串替换为你的账号名。</p>
<h1>
<strong>一个极简风格的博客</strong></h1>
<p>
从上面的工作流程可以看出，虽然每次我在本地添加文件后，都只要 make 一下就能发布文章，但我还是觉得麻烦，希望能直接通过浏览器在 GitHub 的网站上添加文章，所以，我又建立了一个非常简洁的博客，没有分类，没有评论，就是一个主页，上面有所有文章链接，添加文章时候，只要在 _post 目录下添加一个 markdown 文件就可以了。</p>
<p>
这个博客项目为： <a href="https://github.com/minixalpha/StrayBirds/tree/gh-pages" target="_blank">
StrayBirds</a> , 是通过 GitHub 的  Automatic page generator生成。完全通过浏览器操作就能建成，不用 <a href="http://lib.csdn.net/base/git" title="Git知识库" target="_blank">git</a>啊，make啊。这个项目目前已经有了 158 个 fork，但是只有 35 个 star 呀，拜托点下 star，这也太不平衡了……</p>
<p>
博客首页：<a href="http://minixalpha.github.io/StrayBirds/" target="_blank">飞鸟集</a>。</p>
<p>
<div class="soucangLargeImageContainer"><img src="http://img.blog.csdn.net/20140920131944468?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvb25fMXk=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast" /></div></p>
<p>
要使用这个项目，你需要做的是：</p>
<p>
1. 注册 GitHub，例如你的用户名为 minixbeta</p>
<p>
2. 到 <a href="https://github.com/minixalpha/StrayBirds/tree/gh-pages" target="_blank">
StrayBirds</a> 点右上角的 fork</p>
<p>
3. 到你 fork 后的项目中，将 _config.yml 中的 username 修改成你的用户名 minixbeta</p>
<p>
4. 得到你自己的博客 http://minixbeta.github.io/StrayBirds/</p>
<p>
需要注意的是，第一次使用 GitHub Pages 时，可能会有较长时间的缓冲时间，过15min左右，才能正常访问博客，请耐心等待。可以尝试修改项目名称来加快这一进程，如何修改后面有介绍。</p>
<p>
另外，我又添加了评论系统，让这个简洁的博客更为完整，你需要到 Disqus 上注册，然后添加一个站点，然后将 _confg.yml 中的 disqusname <strong>修改成你的博客短名，这个在Disqus
 的 Add Disqus To Site 的时候会设置，注意这里的对应关系。注意这个名字不是你的 Disqus 用户名，是你的站点名。</strong></p>
<p>
如果你的文章想启用评论，在写文章的风格定义部分，加上 `comments: true` 即可。像示例文章中那样就行，如果你不想加评论，就不要加这句。</p>
<p>
另外，由于这个项目目前已经有 200 个 fork，因此我又将 GitHub Pages 官方的所有主题及<a href="http://www.zhanxin.info/" target="_blank">掌心</a>做的 Jekyll 主题整合到其中，你可以通过修改 _config.yml 中的 theme 字段，轻松切换主题，不过每次切换都需要等待一段时间才能生效。所以，最好在修改主题之后修改项目名称，可能会回快这一进程。修改方法后面会介绍。</p>
<p>
主题包括：</p>
<ul>
<li>hack  <div class="soucangLargeImageContainer"><img src="http://img.blog.csdn.net/20150423223940345?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvb25fMXk=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast" /></div></li><li>leap-day<div class="soucangLargeImageContainer"><img src="http://img.blog.csdn.net/20150423224008471?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvb25fMXk=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast" /></div></li><li>merlot <div class="soucangLargeImageContainer"><img src="http://img.blog.csdn.net/20150423223913116?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvb25fMXk=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast" /></div></li><li>midnight <div class="soucangLargeImageContainer"><img src="http://img.blog.csdn.net/20150423224036380?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvb25fMXk=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast" /></div></li><li>minimal <div class="soucangLargeImageContainer"><img src="http://img.blog.csdn.net/20150423224141347?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvb25fMXk=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast" /></div></li><li>modernist <div class="soucangLargeImageContainer"><img src="http://img.blog.csdn.net/20150423224230338?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvb25fMXk=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast" /></div></li><li>slate <div class="soucangLargeImageContainer"><img src="http://img.blog.csdn.net/20150423224054351?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvb25fMXk=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast" /></div></li><li>time-machine<div class="soucangLargeImageContainer"><img src="http://img.blog.csdn.net/20150423223947467?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvb25fMXk=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast" /></div></li></ul>

<p>
kunka</p>
<p>
<div class="soucangLargeImageContainer"><img src="http://img.blog.csdn.net/20150510214858118?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvb25fMXk=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast" /></div></p>
<p>
如果你想把项目的名字改了，例如，将 StrayBirds 修改为 blog</p>
<p>
那么，你需要做的是:</p>
<p>
1. 在项目的 Setting 中将 Repository name 从 StrayBirds 修改为 blog</p>
<p>
2. 将 _config.yml 中的 baseurl 修改为 /blog</p>
<p>
3. 通过 http://minixbeta.github.io/blog/ 来访问你的新博客。</p>
<p>
Thanks to authors of the themes:</p>

<p>
All the themes are intergrated in the blog template, with some modifies.</p>
<p>
如果你不太明白，可以看这个<a href="https://github.com/minixalpha/StrayBirds/tree/gh-pages" target="_blank">StrayBirds</a>  项目在
 GitHub 上的 READEME，里面有如何fork项目，修改项目名，添加文章的 GIF 演示。</p>
<p>
如果遇到有bug, 麻烦在GitHub 上提交<a href="https://github.com/minixalpha/minixalpha.github.io/issues" target="_blank">Issues</a>，最好不要在
 GitHub 上的博客中评论。</p>
<p>
另外， 这篇文章从 2014 年 2 月到现在 (2015年4月) 一直在不断更新，如果对大家有用，希望去 GitHub 上点个 star 支持一下。</p>
   














   











 


        <div id="digg">
            <dl id="btnDigg">
               
                 <dt>顶</dt>
                
            </dl>
           
              
            <dl id="btnBury">
              
                  <dt>踩</dt>
                               
            </dl>
            
        </div>
     
    
    

   

    


               
      


    


           



            
                                    
            
                                    

        
        


<div>
    
    <div id="comment_list"><dl id="comment_item_6444943"><dt>32楼 <a href="/zhangwei900808" target="_blank">潇莎</a> 2016-11-29 17:44发表  <a href="#reply" title="回复" target="_blank">[回复]</a> </dt><dd>太好了，谢谢楼主</dd></dl><dl id="comment_item_6422179"><dt>31楼 <a href="/u013861109" target="_blank">深沉的简单</a> 2016-11-21 18:04发表  <a href="#reply" title="回复" target="_blank">[回复]</a> </dt><dd>版主在吗，Makefile怎么使用，win系统如何使用呢！麻烦版主帮帮忙</dd></dl><dl id="comment_item_6421647"><dt>30楼 <a href="/u013861109" target="_blank">深沉的简单</a> 2016-11-21 15:14发表  <a href="#reply" title="回复" target="_blank">[回复]</a> </dt><dd>版主这里的make 如何使用</dd></dl><dl id="comment_item_6231783"><dt>29楼 <a href="/happy_horse" target="_blank">快乐的kuai小马</a> 2016-08-26 16:20发表  <a href="#reply" title="回复" target="_blank">[回复]</a> </dt><dd>博主，我按你的修改之后，还是打不开；；；https://beeagle.github.io/StrayBirds/</dd></dl><dl id="comment_item_5843733"><dt>28楼 <a href="/visionfans" target="_blank">visionfans</a> 2016-01-16 00:10发表  <a href="#reply" title="回复" target="_blank">[回复]</a> </dt><dd>请问 jekyllthemes.org 上的主题是用Jekyll直接做的还是基于JekyllBootstrap做的？</dd></dl><dl id="comment_item_5841121"><dt>27楼 <a href="/xbmail2013" target="_blank">薛彬axuebin</a> 2016-01-13 22:26发表  <a href="#reply" title="回复" target="_blank">[回复]</a> </dt><dd>谢谢分享，收藏了</dd></dl><dl id="comment_item_5836497"><dt>26楼 <a href="/qq_25042291" target="_blank">小名同学</a> 2016-01-09 17:42发表  <a href="#reply" title="回复" target="_blank">[回复]</a> </dt><dd>请问一下那个不可见的''\n\n"是什么意思，怎么用？我把博文发出去了，发现在主页会显示博文全部内容，怎么样只显示摘要。新手好苦恼，弄了2天没弄好，求帮助啊。谢谢</dd><dl id="comment_item_5836523"><dt>Re: <a href="/on_1y" target="_blank">on_1y</a> 2016-01-09 18:03发表  <a href="#reply" title="回复" target="_blank">[回复]</a> </dt><dd>回复qq_25042291：那个是换行符号，连续两个换行符号上面的内容，就会作为摘要显示。</dd></dl></dl><dl id="comment_item_5725387"><dt>25楼 <a href="/whg333" target="_blank">whg333</a> 2015-12-16 18:10发表  <a href="#reply" title="回复" target="_blank">[回复]</a> </dt><dd>非常感谢,已经fork并且star了,但是其实博主的kunka主题自己写死了评论系统,还有一些细节没有处理好,但最终在博主代码的前提下自己修改好了,且在Win7上搭建了本地jekyll测试,有需要的了具体参考我的博文——jekyll最新版3.0.1安装与问题解决:<br />http://www.iclojure.com/blog/articles/2015/12/02/make-blog-by-jekyll/</dd></dl><dl id="comment_item_5652305"><dt>24楼 <a href="/fhybj" target="_blank">疏竹影</a> 2015-11-28 17:37发表  <a href="#reply" title="回复" target="_blank">[回复]</a> </dt></dl><dl id="comment_item_5430019"><dt>23楼 <a href="/xidianhuihui" target="_blank">xidianhuihui</a> 2015-09-22 15:53发表  <a href="#reply" title="回复" target="_blank">[回复]</a> </dt></dl><dl id="comment_item_5411319"><dt>22楼 <a href="/hubert_Zheng" target="_blank">hubert_Zheng</a> 2015-09-14 13:25发表  <a href="#reply" title="回复" target="_blank">[回复]</a> </dt><dd>mark 学习</dd></dl><dl id="comment_item_5361269"><dt>21楼 <a href="/CodeCleaner" target="_blank">CodeCleaner</a> 2015-08-30 16:01发表  <a href="#reply" title="回复" target="_blank">[回复]</a> </dt><dd>楼主你那个Makefile脚本有个坑啊，cp -r _site/ /tmp/你直接把整个要发布的文件夹里！的内容洒到系统文件夹下了，系统文件夹tmp下还有其他东西的啊！仓库已被我搞费，只好重新再搞了。建议，<br />1. 这个命令可能是：cp -r _site /tmp/<br />2. 干嘛非临时拷到系统文件夹，cp -r _site/ ../tmp/不好么</dd></dl><dl id="comment_item_5359389"><dt>20楼 <a href="/CodeCleaner" target="_blank">CodeCleaner</a> 2015-08-30 01:15发表  <a href="#reply" title="回复" target="_blank">[回复]</a> </dt><dd>谢谢楼主，太有用了。等我先把jekyll以及相应的样式搭起来马上就来star你的github！！</dd></dl><dl id="comment_item_5282567"><dt>19楼 <a href="/Const_Gong" target="_blank">箭已离弓</a> 2015-08-06 18:01发表  <a href="#reply" title="回复" target="_blank">[回复]</a> </dt><dd>有很多问题，有BUG</dd></dl><dl id="comment_item_5250411"><dt>18楼 <a href="/BaiWfg2" target="_blank">技术菌的blog</a> 2015-07-31 10:22发表  <a href="#reply" title="回复" target="_blank">[回复]</a> </dt><dd>而且我不希望url里面出现中文，那该怎么做呢？</dd></dl><dl id="comment_item_5250395"><dt>17楼 <a href="/BaiWfg2" target="_blank">技术菌的blog</a> 2015-07-31 10:22发表  <a href="#reply" title="回复" target="_blank">[回复]</a> </dt><dd>首先非常感谢博主把这东西简易化了，其实对我而言就是想找个地方写点博文，有现成的模板是最好的了。但目前发现个问题啊，为什么只有kunka主题有导航，其它主题没导航呢？</dd></dl><dl id="comment_item_5250379"><dt>16楼 <a href="/BaiWfg2" target="_blank">技术菌的blog</a> 2015-07-31 10:20发表  <a href="#reply" title="回复" target="_blank">[回复]</a> </dt><dd>首先非常感谢博主把这东西简易化了，其实对我而言就是想找个地方写点博文，有现成的模板是最好的了。但目前发现个问题啊，为什么只有kunka主题有导航，其它主题没导航呢？</dd></dl><dl id="comment_item_5154371"><dt>15楼 <a href="/u011591229" target="_blank">gobraves</a> 2015-06-21 15:36发表  <a href="#reply" title="回复" target="_blank">[回复]</a> </dt><dd>学习了，多谢博主</dd></dl><dl id="comment_item_5148353"><dt>14楼 <a href="/z6491679" target="_blank">z6491679</a> 2015-06-17 16:50发表  <a href="#reply" title="回复" target="_blank">[回复]</a> </dt><dd>博主您好，请问一下设置disqus的时候在_config.yml里面改过还是需要将_include下的comments.ext里面也要改？不是已经有var disqus_shortname = '{{site.disqusname}}';了？</dd><dl id="comment_item_5152119"><dt>Re: <a href="/on_1y" target="_blank">on_1y</a> 2015-06-19 16:22发表  <a href="#reply" title="回复" target="_blank">[回复]</a> </dt><dd>回复z6491679：minixalpha.github.io 这个项目中，comments.ext 里的 disqus_shortname 还是硬编码的，因此需要修改，StrayBirds 项目中 disqus_shortname 的从配置文件中读取，只需要修改配置文件就行。</dd></dl></dl><dl id="comment_item_5127463"><dt>13楼 <a href="/GPing93" target="_blank">梦幻白ye</a> 2015-06-07 08:15发表  <a href="#reply" title="回复" target="_blank">[回复]</a> </dt><dd>只是想来说声谢谢～<br />真的非常棒。</dd></dl><dl id="comment_item_4907373"><dt>12楼 <a href="/hu1020935219" target="_blank">振生</a> 2015-04-01 14:44发表  <a href="#reply" title="回复" target="_blank">[回复]</a> </dt><dd>请问fork您的博客模板之后如何绑定自己的域名呢?</dd><dl id="comment_item_4908259"><dt>Re: <a href="/on_1y" target="_blank">on_1y</a> 2015-04-01 19:02发表  <a href="#reply" title="回复" target="_blank">[回复]</a> </dt><dd>回复hu1020935219：我自己没有绑定过，所以没有写过程，你可以看看 GitHub Pages 帮助文档里的内容：<br /><br />https://help.github.com/articles/setting-up-a-custom-domain-with-github-pages/<br /><br />希望对你有帮助</dd></dl></dl><dl id="comment_item_4856693"><dt>11楼 <a href="/u010571656" target="_blank">_WitNesS</a> 2015-03-18 14:21发表  <a href="#reply" title="回复" target="_blank">[回复]</a> </dt><dd>在加入插件的时候， jekyll-category-archive-plugin,在github上clone了最新版 但是加入之后jekyll serve报错stack level too deep。这个错误如何解决...</dd></dl><dl id="comment_item_4847985"><dt>10楼 <a href="/u012203889" target="_blank">BigBallon</a> 2015-03-14 21:34发表  <a href="#reply" title="回复" target="_blank">[回复]</a> </dt><dd>您好，，请问一下，我将`disqus_shortname ` 修改成你的博客短名，但是出现下面的问题：<br />We were unable to load Disqus. If you are a moderator please see our troubleshooting guide.<br /><br />请问是什么原因呢</dd><dl id="comment_item_4848041"><dt>Re: <a href="/u012203889" target="_blank">BigBallon</a> 2015-03-14 22:02发表  <a href="#reply" title="回复" target="_blank">[回复]</a> </dt><dd>回复u012203889：现在问题解决了。。</dd><dl id="comment_item_5435341"><dt>Re: <a href="/chengyifly" target="_blank">chengyifly</a> 2015-09-24 16:05发表  <a href="#reply" title="回复" target="_blank">[回复]</a> </dt><dd>回复u012203889：请问你是怎么解决的？</dd></dl></dl></dl><dl id="comment_item_4815757"><dt>9楼 <a href="/draem0507" target="_blank">draem0507</a> 2015-02-28 17:37发表  <a href="#reply" title="回复" target="_blank">[回复]</a> </dt><dd>没有用jekyll-bootstrap?</dd></dl><dl id="comment_item_4645861"><dt>8楼 <a href="/bjq1016" target="_blank">itfanr</a> 2014-12-29 13:27发表  <a href="#reply" title="回复" target="_blank">[回复]</a> </dt><dd>十分感谢  把jekyll分析的透彻了   受益匪浅</dd></dl><dl id="comment_item_4595983"><dt>7楼 <a href="/q279838089" target="_blank">q279838089</a> 2014-12-09 11:01发表  <a href="#reply" title="回复" target="_blank">[回复]</a> </dt></dl><dl id="comment_item_4411257"><dt>6楼 <a href="/u010311064" target="_blank">KevinIsSoCool</a> 2014-10-19 16:17发表  <a href="#reply" title="回复" target="_blank">[回复]</a> </dt><dd>你好，文章分类功能本地搭建的jekyll平台能用，但是github pages上好像不行，请问有什么解决方法么？</dd><dl id="comment_item_4412039"><dt>Re: <a href="/on_1y" target="_blank">on_1y</a> 2014-10-19 21:37发表  <a href="#reply" title="回复" target="_blank">[回复]</a> </dt><dd>回复u010311064：你好，可以做两个分支。把本地生成的 html 页面上传到 master 分支里，这些 html 页面中包含有分类相关的页面。你对比一下我的项目里 source 分支和 master 分支的内容，应该能看出来，master 分支里的内容是在本地生成好的。</dd></dl></dl><dl id="comment_item_4410083"><dt>5楼 <a href="/fxmmc" target="_blank">民兵戈尔丹</a> 2014-10-19 00:40发表  <a href="#reply" title="回复" target="_blank">[回复]</a> </dt><dd>不是说解析http://username.github.io/下的master分支吗<br />楼主怎么又多出个source分支？？不明白</dd><dl id="comment_item_4412027"><dt>Re: <a href="/on_1y" target="_blank">on_1y</a> 2014-10-19 21:33发表  <a href="#reply" title="回复" target="_blank">[回复]</a> </dt><dd>回复fxmmc：在 master 分支中，如果是 markdown 格式的，由 github 转化成 html 格式的。也可以是本地自己转化成 html 格式的，这样 github 就直接用这些 html 格式的了。我这里因为 github 不支持分类功能，不能自动生成分类页面，所以我需要本地生成与分类相关的html页面。所以，需要一个 source 分支，编写 markdown 格式的文章，给文章加入分类标签。然后在本地生成 html 格式的文章以及分类页面，然后将生成html页面后的文件放到 master 分支里。</dd></dl></dl><dl id="comment_item_4091823"><dt>4楼 <a href="/a739697044" target="_blank">cug_liuyatao</a> 2014-07-28 15:15发表  <a href="#reply" title="回复" target="_blank">[回复]</a> </dt><dd>谢谢  讲的很好！</dd></dl><dl id="comment_item_4031321"><dt>3楼 <a href="/bloomcat" target="_blank">bloomcat</a> 2014-07-09 18:15发表  <a href="#reply" title="回复" target="_blank">[回复]</a> </dt><dd><legend>引用“bloomcat”的评论：</legend>你好，请问一个问题，我的.md文件上传后不能正常解析，发现是因为第一行的---前有个空格，可是我本地...<br />啊，是bom头字符的缘故，解决了~打扰打扰~</dd><dl id="comment_item_4031323"><dt>Re: <a href="/on_1y" target="_blank">on_1y</a> 2014-07-09 18:16发表  <a href="#reply" title="回复" target="_blank">[回复]</a> </dt><dd>回复bloomcat：解决了就好～</dd></dl></dl><dl id="comment_item_4031293"><dt>2楼 <a href="/bloomcat" target="_blank">bloomcat</a> 2014-07-09 17:56发表  <a href="#reply" title="回复" target="_blank">[回复]</a> </dt><dd>你好，请问一个问题，我的.md文件上传后不能正常解析，发现是因为第一行的---前有个空格，可是我本地的.md文件里是没有空格的，上传后就有空格了。。每次都要上传了之后再手动把空格去掉才能解析出来，请问你知道这是什么原因吗？<br />我就是复制粘贴一个.md文件然后修改再提交上传，是这样的过程么？还是漏了什么环节？或者要用命令行先生成一个md文件才行？</dd></dl><dl id="comment_item_3860655"><dt>1楼 <a href="/u010890647" target="_blank">小津</a> 2014-05-22 12:41发表  <a href="#reply" title="回复" target="_blank">[回复]</a> </dt><dd>你好，请问一个问题：我执行下面命令<br />jekyll new test<br />cd test<br />然后执行jekyll serve 或者jekyll build --trace都会报错：<br />错误信息是：  Liquid Exception: cannot load such file -- yajl/2.0/yajl in _posts/2014-05-22-welcome-to-jekyll.markdown<br />但是在我另一个git里执行jekyll serve就没有问题，请问这是什么原因？<br />请问这是什么原因？</dd><dl id="comment_item_3860753"><dt>Re: <a href="/on_1y" target="_blank">on_1y</a> 2014-05-22 13:23发表  <a href="#reply" title="回复" target="_blank">[回复]</a> </dt><dd>回复u010890647：我之前也遇到过类似的问题，当时是 jekyll 的版本问题，导致有些markdown文件没法正确解析。我Google 了"Liquid Exception: cannot load such file welcome-to-jekyll.markdown"，有文章提到 “安装Ruby 1.9的版本可以解决此问题”，你试试看能不能解决。</dd><dl id="comment_item_3932727"><dt>Re: <a href="/u010890647" target="_blank">小津</a> 2014-06-06 15:59发表  <a href="#reply" title="回复" target="_blank">[回复]</a> </dt><dd>回复on_1y：谢谢，我把原博文全删了就解决了~虽然搞不懂为什么。</dd></dl></dl></dl></div>
    
    <div id="comment_form"><div>您还没有登录,请<a href="javascript:void(0);" target="_blank">[登录]</a>或<a href="http://passport.csdn.net/account/register?from=http%3A%2F%2Fblog.csdn.net%2Fon_1y%2Farticle%2Fdetails%2F19259435" target="_blank">[注册]</a></div>
    <div>
        * 以上用户言论只代表其个人观点，不代表CSDN网站的观点或立场</div>




    




























                        
                    
