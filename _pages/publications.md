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
<p><b>A New Formulation of Lipschitz Constrained With Functional Gradient Learning for GANs</b>
<br />Chang Wan, Ke Fan, Xinwei Sun, Yanwei Fu, Minglu Li, Yunliang Jiang, Zhonglong Zheng<sup><a title='Corresponding author'>✉</a></sup>
<br /> Machine Learning <br /> 
</p>
</li>

<li>
<p><b>Repositioning the Subject within Image</b>
<br />Yikai Wang, Chenjie Cao, Ke Fan, Qiaole Dong, Yifan Li, Xiangyang Xue, Yanwei Fu<sup><a title='Corresponding author'>✉</a></sup>
<br /> TMLR, 2024 <br /> 
<a href="https://openreview.net/forum?id=orHH4fCtR8" class="blue-text">Paper</a> |
<a href="https://github.com/Yikai-Wang/SEELE-ReS" class="blue-text">Code</a> |

</p>
</li>

<li>
<p><b>Adaptive Slot Attention: Object Discovery with Dynamic Slot Number</b>
<br />Ke Fan, Zechen Bai, Tianjun Xiao, Tong He, Max Horn, Yanwei Fu<sup><a title='Corresponding author'>✉</a></sup>, Francesco Locatello, Zheng Zhang
<br /> CVPR, 2024 <br /> 
<a href="https://arxiv.org/abs/2406.09196" class="blue-text">Paper</a> |
<a href="https://kfan21.github.io/AdaSlot/" class="blue-text">Code</a> |

</p>
</li>


<li>
<p><b>Test-Time Linear Out-of-Distribution Detection</b>
<br />Ke Fan<a>*</a>, Tong Liu<a>*</a>, Xingyu Qiu, Yikai Wang, Lian Huai<sup><a title='Corresponding author'>✉</a></sup>, Zeyu Shangguan, Shuang Gou, Fengjian Liu, Yuqian Fu, Yanwei Fu, Xingqun Jiang
<br /> CVPR, 2024. <br /> 
<a href="https://openaccess.thecvf.com/content/CVPR2024/papers/Fan_Test-Time_Linear_Out-of-Distribution_Detection_CVPR_2024_paper.pdf" class="blue-text">Paper</a> |
<a href="https://github.com/kfan21/RTL" class="blue-text">Code</a> |

</p>
</li>


<li>
<p><b>Unsupervised Open-Vocabulary Object Localization in Videos</b>
<br />Ke Fan<a>*</a>, Zechen Bai<a>*</a>, Tianjun Xiao, Dominik Zietlow, Max Horn, Zixu Zhao, Carl-Johann Simon-Gabriel, Mike Zheng Shou, Francesco Locatello, Bernt Schiele, Thomas Brox, Zheng Zhang<sup><a title='Corresponding author'>✉</a></sup>, Yanwei Fu<sup><a title='Corresponding author'>✉</a></sup>, Tong He
<br /> ICCV, 2023; CVPR 2024 Workshop CORR. <br /> 
<a href="https://arxiv.org/pdf/2309.09858.pdf" class="blue-text">Paper</a> |
<a href="https://github.com/amazon-science/object-centric-vol" class="blue-text">Code</a> |
</p>
</li>

<li>
<p><b>Rethinking Amodal Video Segmentation from Learning Supervised Signals with Object-centric Representation</b>
<br />Ke Fan<a>*</a>, Jingshi Lei<a>*</a>, Xuelin Qian<sup><a title='Corresponding author'>✉</a></sup>, Miaopeng Yu, Tianjun Xiao<sup><a title='Corresponding author'>✉</a></sup>, Tong He, Zheng Zhang, Yanwei Fu
<br /> ICCV, 2023. <br /> 
<a href="https://arxiv.org/pdf/2309.13248.pdf" class="blue-text">Paper</a> |
<a href="https://github.com/amazon-science/efficient-object-centric-representation-amodal-segmentation" class="blue-text">Code</a> |

</p>
</li>

<li>
<p><b>Clustering by the Probability Distributions From Extreme Value Theory</b>
<br />Sixiao Zheng<a>*</a>, Ke Fan<a>*</a>, Yanxi Hou, Jianfeng Feng, and Yanwei Fu<sup><a title='Corresponding author'>✉</a></sup>
<br /> IEEE Transactions on Artificial Intelligence, 2022. <br /> 
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
  You can also find my articles on <u><a href="https://scholar.google.com/citations?user=426Vf3kAAAAJ">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}