# moui
moui.js in for javascript es5+es6 专业数据绑定+双向数据思维
<!-- wp:quote -->
<blockquote class="wp-block-quote"><p><strong>功能介绍：</strong></p><p>1.能够快速把数据绑定在一起，利用了json格式去定义数据的类型和属性，满足大部分项目的需要。</p><p>2.能够在dom层级上，自定义任何静态标签，只需手动解析和绑定需要的数据。</p><p>3.废话不想说太多了，灵活性、兼容性、调试性、优化性、优越性。</p><p></p><cite>我不是程序员，爱好写javascript的人，哈！</cite></blockquote>
<!-- /wp:quote -->

<!-- wp:paragraph -->
<p>使用说明：</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p><strong>1.如何用此数据绑定呢？</strong></p>
<!-- /wp:paragraph -->

<!-- wp:preformatted -->
<pre class="wp-block-preformatted">在body中添加id“moui”，使得数据绑定在dom层上。丢失此id，无法使用！</pre>
<!-- /wp:preformatted -->

<!-- wp:paragraph -->
<p><strong><em>&lt;body id="moui"&gt;&lt;/body&gt;</em></strong></p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p><strong>2.在页面中任何一处地方加上您的数据，如何加呢？</strong></p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>2.1例子：在&lt;header&gt;此时你在这，加入自己的定义的布局，布局里加上id和“{{数据}}”&lt;/header&gt; 代码如下</p>
<!-- /wp:paragraph -->

<!-- wp:code -->
<pre class="wp-block-code"><code>&lt;header>
    &lt;div id="nav">
        &lt;p>{{title}}&lt;/p>
    &lt;/div>
&lt;/header></code></pre>
<!-- /wp:code -->

<!-- wp:paragraph -->
<p>2.2 解析方式：</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>app ： </p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>固定参数两个  el ：DOM层 输入您的元素id   |   data：你需要绑定的数据 </p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>代码如下：</p>
<!-- /wp:paragraph -->

<!-- wp:code -->
<pre class="wp-block-code"><code>app({
    el: "nav",
    data: {
        title: '标题',
    },
});</code></pre>
<!-- /wp:code -->

<!-- wp:file {"id":19,"href":"http://www.datouyu.net/wp-content/uploads/2019/08/app.m.js.zip"} -->
<div class="wp-block-file"><a href="http://www.datouyu.net/wp-content/uploads/2019/08/app.m.js.zip">app.m.js</a><a href="http://www.datouyu.net/wp-content/uploads/2019/08/app.m.js.zip" class="wp-block-file__button" download>下载</a></div>
<!-- /wp:file -->

<!-- wp:paragraph -->
<p>GitHub ： <a href="https://github.com/qq252454/moui">https://github.com/qq252454/moui</a></p>
<!-- /wp:paragraph -->
