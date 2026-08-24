---
layout: home
title: 主页
nav_exclude: true
seo:
  type: 课程
  name: 离散数学
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

<!-- {% if site.announcements %}
{{ site.announcements.last }}
[Announcements](announcements.md){: .btn .btn-outline .fs-3 }
{% endif %} -->

## 关于本课程

离散数学是计算机科学的数学基础。在这门课程中，学生将学习计算机所需要的数学知识，并培养其逻辑思维和数学思维能力。为了实现这些目标，课程将涵盖以下主题：逻辑学、集合论、代数结构、组合数学、图论和初等数论。完成这门课程后，学生将掌握计算机科学未来学习所需的必要数学基础。

关于课程介绍的更多信息和课程要求请关注 [课程信息](syllabus.md)

## 课程基本信息

**主讲人:** [杨启哲](https://basics.sjtu.edu.cn/~yangqizhe/), qzyang(at)shnu.edu.cn

**课程时间地点:** &ensp;&nbsp;8:00 a.m.- 9:30 a.m. &emsp; 每周二(1-16周), 奉贤3教楼512
 <br/>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&nbsp;&ensp;&nbsp;1:00 p.m.- 2:30 p.m. &emsp;每周五(1-16周), 奉贤3教楼512


 更多信息可以关注 [课程安排](schedule.md).

## 期末考试

期末考试的时间已经发布，具体信息为：
   - 地点：<font color="#dd0000"> 奉贤3教楼202</font>
   - 考试时间：**2026年1月19日上午8:30-10:00** 
  
请同学们注意，该考试为**闭卷考试**，<font color="#dd0000">但允许使用**计算器**</font>，并请各位同学注意，一定要带好**学生证**和**身份证**。

## 课程反馈

我们建立了一个长期的课程反馈问卷:

- [《离散数学》课程调查问卷](https://www.wjx.cn/vm/YDpvisZ.aspx# )

欢迎大家提出关于本课程的问题或建议。

**2026年1月8日更新**

本学期的课程即将结束，为了更好的改进课程，我建立了一个完课调查问卷：

- [《离散数学》完课调查问卷](https://v.wjx.cn/vm/rnOj3A8.aspx)

该问卷不是强制性的，但我衷心希望每位同学都能参与，提出你们对于这堂课的想法和建议，谢谢！

## 之前的课程资料

- [2023年秋季学期](https://www.dm2023w.spacepenguin.com.cn)
- [2024年秋季学期](https://www.dm2024w.spacepenguin.com.cn)
- [2025年春季学期](https://www.dm2025s.spacepenguin.com.cn)

## 课程通知

{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %}

