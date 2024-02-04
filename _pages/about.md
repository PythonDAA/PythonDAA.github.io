---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# 📝 Python 数据分析与应用

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/maxresdefault.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

### 课程介绍

本课程的建设目标是把Python数据分析与应用课程建设成为一门教学内容丰富全面，教学方法合理先进，教学体系人性化与差异化相结合的课程。在课程设计时充分考虑到本课程实践性与应用性较强的特点，在授课过程中致力于将理论与实践相结合并兼顾基础技术与前沿应用，从而更好地培养学生的编程能力，数据分析能力和实际问题分析解决能力。


</div>
</div>


# 📖 参考资料

<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Recommended Readings</title>
</head>
<body>

<ul>
  <li><p><a href="files/教学大纲.pdf">[教学大纲]</a></p></li>
  <li>Dan Jurafsky and James H. Martin. <em>Speech and Language Processing</em> (3rd ed. draft)</li>
  <li>Jacob Eisenstein. <em>Natural Language Processing</em></li>
  <li>Yoav Goldberg. <em>A Primer on Neural Network Models for Natural Language Processing</em></li>
  <li>Ian Goodfellow, Yoshua Bengio, and Aaron Courville. <em>Deep Learning</em></li>
  <li>Delip Rao and Brian McMahan. <em>Natural Language Processing with PyTorch</em> (requires Stanford login)</li>
</ul>

<p>If you have no background in neural networks but would like to take the course anyway, you might well find one of these books helpful to give you more background:</p>

<ul>
  <li>Michael A. Nielsen. <em>Neural Networks and Deep Learning</em></li>
  <li>Eugene Charniak. <em>Introduction to Deep Learning</em></li>
</ul>

</body>
</html>

# 💬 课程内容

<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Course Schedule</title>
<style>
  table {
    width: 100%;
    border-collapse: collapse;
  }
  th, td {
    border: 1px solid #ddd;
    padding: 8px;
    text-align: left;
  }
  th {
    background-color: #f2f2f2;
  }
  a {
    color: blue;
  }
</style>
</head>
<body>

<table>
  <tr>
    <th>内容描述</th>
    <th>课程资料</th>
    <th>练习题目</th>
  </tr>
  <tr>
    <td>
      Python编程基础 (9学时)
      <br>
    本章节将深入介绍Python语言的编程基础，包括:
    <ul>
      <li>
        Python语法
      </li>
      
      <li>
        基本数据类型、变量、运算符
      </li>
      <li>
        逻辑控制
      </li>
      <li>
      列表、元组、字符串、集合、字典
      </li>
      <li>
      函数、类与对象
      </li>
      <li>
      异常处理以及包的使用
      </li>
    </ul>
    </td>
    
    <td>
      <ul>
        <li>  Python编程基础(1) [<a href="/files/Python编程基础(1).ipynb">Notebook</a>]
        [<a href="/files/Python编程基础(1).pdf">pdf</a>] [<a href="https://pan.baidu.com/s/1rXTzyazwJ6TAck7vk2e-HQ?pwd=4n41">视频</a>]
        </li>
         <li>  Python编程基础(2) [<a href="/files/Python编程基础(2).ipynb">Notebook</a>]
        [<a href="/files/Python编程基础(2).pdf">pdf</a>] [<a href="https://pan.baidu.com/s/1XHN9pVG8LY4hevGa2w9Y1A?pwd=uipw">视频</a>]
        </li>
        <li>  Python编程基础(3) [<a href="/files/Python编程基础(3).ipynb">Notebook</a>]
        [<a href="/files/Python编程基础(3).pdf">pdf</a>] [<a href="https://pan.baidu.com/s/1UUlFe5ojWX1BjxLXGJthDA?pwd=lsl3">视频</a>]
        </li>
      </ul>
    </td>
    <td>
      <ul>
        <li>
         Python编程基础(1) [<a href="link-to-word2vec-paper">Notebook</a>][<a href="xxx">pdf</a>]
        </li>
        <li>
         Python编程基础(2) [<a href="link-to-word2vec-paper">Notebook</a>][<a href="xxx">pdf</a>]
        </li>
        <li>
         Python编程基础(3) [<a href="link-to-word2vec-paper">Notebook</a>][<a href="xxx">pdf</a>]
        </li>
      </ul>
    </td>
  </tr>
 
  <!-- More rows can be added here -->

  <!-- Second Row, Chapter 2 -->
  <tr>
    <td>
      Numpy介绍 (3学时)
      <br>
    本章节将介绍Python中的用于高效存储和操作数值数组的科学计算包Numpy，涵盖基本Numpy数组操作和整合函数。
    </td>
    
    <td>
      <ul>
        <li>  Numpy介绍(1) [<a href="/files/Numpy介绍(1).ipynb">Notebook</a>]
        [<a href="/files/Numpy介绍(1).pdf">pdf</a>] [<a href="https://pan.baidu.com/s/1S1WnACPL2mm-SUpIx-9mDQ?pwd=euir">视频</a>]
        </li>
         <li>  Numpy介绍(2) [<a href="/files/Numpy介绍(2).ipynb">Notebook</a>]
        [<a href="/files/Numpy介绍(2).pdf">pdf</a>] [<a href="https://pan.baidu.com/s/1hbCmhzlQk-AVhDKy_ZSJ0Q?pwd=2j5c</a>]
        </li>
      </ul>
    </td>
    <td>
      <ul>
        <li>
         Numpy介绍(1) [<a href="link-to-word2vec-paper">Notebook</a>][<a href="xxx">pdf</a>]
        </li>
        <li>
         Numpy介绍(2) [<a href="link-to-word2vec-paper">Notebook</a>][<a href="xxx">pdf</a>]
        </li>
        数据集：
        [<a href="/files/president_heights.csv">president_heights.csv</a>] [<a href="/files/Seattle2014.csv">Seattle2014.csv</a>]       
      </ul>
    </td>
  </tr>
  
</table>

</body>
</html>
