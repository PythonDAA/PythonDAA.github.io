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
    <th>课程视频</th>
    <th>练习题目</th>
  </tr>
  <tr>
    <td>
      Python编程基础 (9学时)
      <br>
    包含如下内容：
    <ul>
      <li>数组</li>
      <li>主函数</li>
    </ul>
    </td>
    
    <td>
      Jupyter Notebook 文件：
      <ul>
        <li>
          <a href="/files/02_PythonBasics_part1.ipynb">Python编程基础(1)</a>
        </li>
        <li>
          <a href="/files/03_PythonBasics_part2.ipynb">Python编程基础(2)</a>
        </li>
        <li>
          <a href="/files/04_PythonBasics_part3.ipynb">Python编程基础(3)</a>
        </li>
      </ul>
    </td>
    
    <td>
    <ul>
        <li>
          <a href="link-to-word2vec-paper">Python编程基础(1)</a>
        </li>
        <li>
          <a href="link-to-negative-sampling-paper">Python编程基础(2)</a>
        </li>
        <li>
          <a href="link-to-negative-sampling-paper">Python编程基础(3)</a>
        </li>
      </ul>
    </td>
    <td>
      <ul>
        <li>
          <a href="link-to-word2vec-paper">Python编程基础(1)</a>
        </li>
        <li>
          <a href="link-to-negative-sampling-paper">Python编程基础(2)</a>
        </li>
        <li>
          <a href="link-to-negative-sampling-paper">Python编程基础(3)</a>
        </li>
      </ul>
    </td>
  </tr>
  <!-- More rows can be added here -->

   <tr>
    <td>
      Numpy 介绍 (3学时)
      <br>
    包含如下内容：
    <ul>
      <li>数组</li>
      <li>主函数</li>
    </ul>
    </td>
    
    <td>
      Jupyter Notebook 文件：
      <ul>
        <li>
          <a href="/files/02_PythonBasics_part1.ipynb">Python编程基础(1)</a>
        </li>
        <li>
          <a href="link-to-negative-sampling-paper">Python编程基础(2)</a>
        </li>
        <li>
          <a href="link-to-negative-sampling-paper">Python编程基础(3)</a>
        </li>
      </ul>
    </td>
    
    <td>
    <ul>
        <li>
          <a href="link-to-word2vec-paper">Python编程基础(1)</a>
        </li>
        <li>
          <a href="link-to-negative-sampling-paper">Python编程基础(2)</a>
        </li>
        <li>
          <a href="link-to-negative-sampling-paper">Python编程基础(3)</a>
        </li>
      </ul>
    </td>
    <td>
      <ul>
        <li>
          <a href="link-to-word2vec-paper">Python编程基础(1)</a>
        </li>
        <li>
          <a href="link-to-negative-sampling-paper">Python编程基础(2)</a>
        </li>
        <li>
          <a href="link-to-negative-sampling-paper">Python编程基础(3)</a>
        </li>
      </ul>
    </td>
  </tr>


 <tr>
    <td>
      Pandas介绍与数据处理 (3学时)
      <br>
    包含如下内容：
    <ul>
      <li>数组</li>
      <li>主函数</li>
    </ul>
    </td>
    
    <td>
      Jupyter Notebook 文件：
      <ul>
        <li>
          <a href="link-to-word2vec-paper">Python编程基础(1)</a>
        </li>
        <li>
          <a href="link-to-negative-sampling-paper">Python编程基础(2)</a>
        </li>
        <li>
          <a href="link-to-negative-sampling-paper">Python编程基础(3)</a>
        </li>
      </ul>
    </td>
    
    <td>
    <ul>
        <li>
          <a href="link-to-word2vec-paper">Python编程基础(1)</a>
        </li>
        <li>
          <a href="link-to-negative-sampling-paper">Python编程基础(2)</a>
        </li>
        <li>
          <a href="link-to-negative-sampling-paper">Python编程基础(3)</a>
        </li>
      </ul>
    </td>
    <td>
      <ul>
        <li>
          <a href="link-to-word2vec-paper">Python编程基础(1)</a>
        </li>
        <li>
          <a href="link-to-negative-sampling-paper">Python编程基础(2)</a>
        </li>
        <li>
          <a href="link-to-negative-sampling-paper">Python编程基础(3)</a>
        </li>
      </ul>
    </td>
  </tr>
  
<!-- Thrid Row -->

 <tr>
    <td>
      数据采集 (3学时)
      <br>
    包含如下内容：
    <ul>
      <li>数组</li>
      <li>主函数</li>
    </ul>
    </td>
    
    <td>
      Jupyter Notebook 文件：
      <ul>
        <li>
          <a href="link-to-word2vec-paper">Python编程基础(1)</a>
        </li>
        <li>
          <a href="link-to-negative-sampling-paper">Python编程基础(2)</a>
        </li>
        <li>
          <a href="link-to-negative-sampling-paper">Python编程基础(3)</a>
        </li>
      </ul>
    </td>
    
    <td>
    <ul>
        <li>
          <a href="link-to-word2vec-paper">Python编程基础(1)</a>
        </li>
        <li>
          <a href="link-to-negative-sampling-paper">Python编程基础(2)</a>
        </li>
        <li>
          <a href="link-to-negative-sampling-paper">Python编程基础(3)</a>
        </li>
      </ul>
    </td>
    <td>
      <ul>
        <li>
          <a href="link-to-word2vec-paper">Python编程基础(1)</a>
        </li>
        <li>
          <a href="link-to-negative-sampling-paper">Python编程基础(2)</a>
        </li>
        <li>
          <a href="link-to-negative-sampling-paper">Python编程基础(3)</a>
        </li>
      </ul>
    </td>
  </tr>
  
</table>

</body>
</html>
