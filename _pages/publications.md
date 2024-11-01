---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
<style>
        a.blue-text {
        color: #87CEEB;
    }
</style>

<a>*</a> indicates co-first authour

<ul>

<li>
<p><b>Clustering by the Probability Distributions From Extreme Value Theory</b>
<br />Sixiao Zheng<a>*</a>,, Ke Fan<a>*</a>, Yanxi Hou, Jianfeng Feng, and Yanwei Fu<sup><a title='Corresponding author'>✉</a></sup>
<br /> IEEE Transactions on Artificial Intelligence, 2022. <br /> 
<a href="https://ieeexplore.ieee.org/document/9720078" class="blue-text">Link</a> |
<a href="https://arxiv.org/pdf/2202.09784.pdf" class="blue-text">Paper</a> |
<a href="https://github.com/sixiaozheng/EVT-K-means" class="blue-text">Code</a> |

</p>
</li>
</ul>

# Preprints

<ul>
<li>
<p><b>A Simple Test-Time Method for Out-of-Distribution Detection
</b>
<br />Ke Fan, Yikai Wang, Qian Yu, Da Li, Yanwei Fu<sup><a title='Corresponding author'>✉</a></sup>
<br /> Technical Report, 2022. <br /> 
<a href="https://arxiv.org/abs/2207.08210" class="blue-text">Paper</a> |
</p>
</li>

</ul>

{% if site.author.googlescholar %}
  You can also find my articles on <u><a href="{{https://scholar.google.com/citations?user=426Vf3kAAAAJ}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}