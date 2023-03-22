<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  
  
  <title>aa | Hexo</title>
  <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
  <meta name="description" content="山东大学 计算机科学与技术 学院云计算技术 课程实验报告学号：202000130085 姓名： 冯帅 班级： 20 级计科 1 班实验题目：利用云平台搭建个人博客实验学时：2 实验日期： 2023 年 3 月 11 日实验目的：熟悉个人博客系统的搭建。具体包括：参考方案：注册 Github 账号，搭建 Hexo 环境并实现个人博客搭建，撰写实验报告。硬件环境：联网的计算机一台软件环境：Window">
<meta property="og:type" content="article">
<meta property="og:title" content="aa">
<meta property="og:url" content="http://example.com/2023/03/14/aa/index.html">
<meta property="og:site_name" content="Hexo">
<meta property="og:description" content="山东大学 计算机科学与技术 学院云计算技术 课程实验报告学号：202000130085 姓名： 冯帅 班级： 20 级计科 1 班实验题目：利用云平台搭建个人博客实验学时：2 实验日期： 2023 年 3 月 11 日实验目的：熟悉个人博客系统的搭建。具体包括：参考方案：注册 Github 账号，搭建 Hexo 环境并实现个人博客搭建，撰写实验报告。硬件环境：联网的计算机一台软件环境：Window">
<meta property="og:locale" content="en_US">
<meta property="og:image" content="https://github.com/sssssfs/ssssfs.github.io/blob/master/2023/03/14/aa/1.png">
<meta property="og:image" content="https://github.com/sssssfs/ssssfs.github.io/blob/master/2023/03/14/aa/2.png">
<meta property="og:image" content="https://github.com/sssssfs/ssssfs.github.io/blob/master/2023/03/14/aa/3.png">
<meta property="og:image" content="https://github.com/sssssfs/ssssfs.github.io/blob/master/2023/03/14/aa/4.png">
<meta property="og:image" content="https://github.com/sssssfs/ssssfs.github.io/blob/master/2023/03/14/aa/5.png">
<meta property="og:image" content="https://github.com/sssssfs/ssssfs.github.io/blob/master/2023/03/14/aa/6.png">
<meta property="article:published_time" content="2023-03-14T13:04:22.000Z">
<meta property="article:modified_time" content="2023-03-22T03:23:58.462Z">
<meta property="article:author" content="John Doe">
<meta name="twitter:card" content="summary">
<meta name="twitter:image" content="https://github.com/sssssfs/ssssfs.github.io/blob/master/2023/03/14/aa/1.png">
  
    <link rel="alternate" href="/atom.xml" title="Hexo" type="application/atom+xml">
  
  
    <link rel="shortcut icon" href="/favicon.png">
  
  
    
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/typeface-source-code-pro@0.0.71/index.min.css">

  
  
<link rel="stylesheet" href="/css/style.css">

  
    
<link rel="stylesheet" href="/fancybox/jquery.fancybox.min.css">

  
<meta name="generator" content="Hexo 6.3.0"></head>

<body>
  <div id="container">
    <div id="wrap">
      <header id="header">
  <div id="banner"></div>
  <div id="header-outer" class="outer">
    <div id="header-title" class="inner">
      <h1 id="logo-wrap">
        <a href="/" id="logo">Hexo</a>
      </h1>
      
    </div>
    <div id="header-inner" class="inner">
      <nav id="main-nav">
        <a id="main-nav-toggle" class="nav-icon"></a>
        
          <a class="main-nav-link" href="/">Home</a>
        
          <a class="main-nav-link" href="/archives">Archives</a>
        
      </nav>
      <nav id="sub-nav">
        
          <a id="nav-rss-link" class="nav-icon" href="/atom.xml" title="RSS Feed"></a>
        
        <a id="nav-search-btn" class="nav-icon" title="Search"></a>
      </nav>
      <div id="search-form-wrap">
        <form action="//google.com/search" method="get" accept-charset="UTF-8" class="search-form"><input type="search" name="q" class="search-form-input" placeholder="Search"><button type="submit" class="search-form-submit">&#xF002;</button><input type="hidden" name="sitesearch" value="http://example.com"></form>
      </div>
    </div>
  </div>
</header>

      <div class="outer">
        <section id="main"><article id="post-aa" class="h-entry article article-type-post" itemprop="blogPost" itemscope itemtype="https://schema.org/BlogPosting">
  <div class="article-meta">
    <a href="/2023/03/14/aa/" class="article-date">
  <time class="dt-published" datetime="2023-03-14T13:04:22.000Z" itemprop="datePublished">2023-03-14</time>
</a>
    
  </div>
  <div class="article-inner">
    
    
      <header class="article-header">
        
  
    <h1 class="p-name article-title" itemprop="headline name">
      aa
    </h1>
  

      </header>
    
    <div class="e-content article-entry" itemprop="articleBody">
      
        <p>山东大学 计算机科学与技术 学院<br>云计算技术 课程实验报告<br>学号：202000130085 姓名： 冯帅 班级： 20 级计科 1 班<br>实验题目：利用云平台搭建个人博客<br>实验学时：2 实验日期： 2023 年 3 月 11 日<br>实验目的：熟悉个人博客系统的搭建。<br>具体包括：<br>参考方案：注册 Github 账号，搭建 Hexo 环境并实现个人博客搭建，撰写实验报告。<br>硬件环境：<br>联网的计算机一台<br>软件环境：<br>Windows or Linux<br>实验步骤与内容：</p>
<ol>
<li>首先安装两个需要使用的软件 node.js 和 Git。<br><img src="https://github.com/sssssfs/ssssfs.github.io/blob/master/2023/03/14/aa/1.png"><br><img src="https://github.com/sssssfs/ssssfs.github.io/blob/master/2023/03/14/aa/2.png"></li>
<li>登陆 Github 建立仓库<br><img src="https://github.com/sssssfs/ssssfs.github.io/blob/master/2023/03/14/aa/3.png"></li>
<li>搭建 Hexo 环境并实现个人博客搭建<br><img src="https://github.com/sssssfs/ssssfs.github.io/blob/master/2023/03/14/aa/4.png"><br><img src="https://github.com/sssssfs/ssssfs.github.io/blob/master/2023/03/14/aa/5.png"><br><img src="https://github.com/sssssfs/ssssfs.github.io/blob/master/2023/03/14/aa/6.png"><br>结论分析与体会：<br>我成功地注册了 Github 账号，搭建了 Hexo 环境并实现了个人博客搭建，<br>我的博客网站可以通过访问“<a target="_blank" rel="noopener" href="https://ssssfs.github.io”来查看,通过本次实验,我掌握/">https://ssssfs.github.io”来查看，通过本次实验，我掌握</a><br>了 Github 账号注册、Hexo 环境搭建、博客网站生成等技能，了解到了一些 Hexo 的基本<br>命令。</li>
</ol>

      
    </div>
    <footer class="article-footer">
      <a data-url="http://example.com/2023/03/14/aa/" data-id="clf89mhzw0000pwvj2tt36czi" data-title="aa" class="article-share-link">Share</a>
      
      
      
    </footer>
  </div>
  
    
<nav id="article-nav">
  
    <a href="/2023/03/22/111/" id="article-nav-newer" class="article-nav-link-wrap">
      <strong class="article-nav-caption">Newer</strong>
      <div class="article-nav-title">
        
          111
        
      </div>
    </a>
  
  
    <a href="/2023/03/14/hello-world/" id="article-nav-older" class="article-nav-link-wrap">
      <strong class="article-nav-caption">Older</strong>
      <div class="article-nav-title">Hello World</div>
    </a>
  
</nav>

  
</article>


</section>
        
          <aside id="sidebar">
  
    

  
    

  
    
  
    
  <div class="widget-wrap">
    <h3 class="widget-title">Archives</h3>
    <div class="widget">
      <ul class="archive-list"><li class="archive-list-item"><a class="archive-list-link" href="/archives/2023/03/">March 2023</a></li></ul>
    </div>
  </div>


  
    
  <div class="widget-wrap">
    <h3 class="widget-title">Recent Posts</h3>
    <div class="widget">
      <ul>
        
          <li>
            <a href="/2023/03/22/111/">111</a>
          </li>
        
          <li>
            <a href="/2023/03/14/aa/">aa</a>
          </li>
        
          <li>
            <a href="/2023/03/14/hello-world/">Hello World</a>
          </li>
        
      </ul>
    </div>
  </div>

  
</aside>
        
      </div>
      <footer id="footer">
  
  <div class="outer">
    <div id="footer-info" class="inner">
      
      &copy; 2023 John Doe<br>
      Powered by <a href="https://hexo.io/" target="_blank">Hexo</a>
    </div>
  </div>
</footer>

    </div>
    <nav id="mobile-nav">
  
    <a href="/" class="mobile-nav-link">Home</a>
  
    <a href="/archives" class="mobile-nav-link">Archives</a>
  
</nav>
    


<script src="/js/jquery-3.4.1.min.js"></script>



  
<script src="/fancybox/jquery.fancybox.min.js"></script>




<script src="/js/script.js"></script>





  </div>
</body>
</html>