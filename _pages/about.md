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
<!--
<span class='anchor' id='about-me'></span>
-->
# 📝 Python 数据分析与应用

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/maxresdefault.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

### 课程介绍

本课程旨在引导学生学习如何使用Python进行数据分析与处理，并应用这些技能解决实际应用问题。课程内容覆盖了数据处理和分析的整个生命周期，包括数据获取、数据清理、数据存储、数据分析和数据可视化等方面。由于本课程强调实践性和应用性，因此课程内容着重将理论与实践相结合，同时关注基础技术和前沿应用。学生通过参与本课程将能够熟练掌握Python数据分析的基础知识，并应用所学内容解决现实世界中的数据处理和分析问题。


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
<li> Mastering python for data science. Samir Madhavan. Packt Publishing.</li>
<li> Python Data Science Handbook: Essential Tools for Working with Data. Jake VanderPlas. O'Reilly Media, Inc..</li> 
<li>	Github Reposiroty: https://github.com/jakevdp/PythonDataScienceHandbook</li>

<p>本课程使用Jupyter Notebook作为课程讲义并在云平台部署搭建JupyterHub, 为每个学生提供便捷的Jupyter Notebook服务，教师与学生可以在该平台上完成讲义和作业分发，作业编写、提交和评分。JupyterHub系统的使用可以下载<a href="/files/JupyterHub系统使用手册(学生版).pdf">JupyterHub系统使用手册</a>。</p>

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
      Jupyter基础 (1学时)
      <br>
    本章节将介绍如何使用Jupyter Notebook来编写Python代码。
    <td>
      Jupyter基础[<a href="/files/Jupyter基础.ipynb">Notebook</a>]
        [<a href="/files/Jupyter基础.pdf">pdf</a>]
    </td>
    <td>
     --
    </td>
  </tr>
 <!-- More Row -->
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
        [<a href="/files/Numpy介绍(2).pdf">pdf</a>] [<a href="https://pan.baidu.com/s/1hbCmhzlQk-AVhDKy_ZSJ0Q?pwd=2j5c">视频</a>]
        </li>
         数据集：
        [<a href="/files/president_heights.csv">president_heights.csv</a>] [<a href="/files/Seattle2014.csv">Seattle2014.csv</a>]  
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
      </ul>
    </td>
  </tr>
  
</table>

</body>
</html>
