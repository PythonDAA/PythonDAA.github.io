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

<p>The following texts are useful, but none are required. All of them can be read free online.</p>

<ul>
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
    <th>Date</th>
    <th>Description</th>
    <th>Course Materials</th>
    <th>Events</th>
    <th>Deadlines</th>
  </tr>
  <tr>
    <td>Tue Jan 10</td>
    <td>
      Word Vectors (by John Hewitt)
      <br>
      <a href="link-to-slides">[slides]</a>
      <a href="link-to-notes">[notes]</a>
      <br>
      Gensim word vectors example:
      <br>
      <a href="link-to-code">[code]</a>
      <a href="link-to-preview">[preview]</a>
    </td>
    <td>
      Suggested Readings:
      <ol>
        <li>
          <a href="link-to-word2vec-paper">Efficient Estimation of Word Representations in Vector Space (original word2vec paper)</a>
        </li>
        <li>
          <a href="link-to-negative-sampling-paper">Distributed Representations of Words and Phrases and their Compositionality (negative sampling paper)</a>
        </li>
      </ol>
    </td>
    <td>Assignment 1 out</td>
    <td>
      <a href="link-to-assignment-code">[code]</a>
      <a href="link-to-assignment-preview">[preview]</a>
    </td>
  </tr>
  <!-- More rows can be added here -->
</table>

</body>
</html>
