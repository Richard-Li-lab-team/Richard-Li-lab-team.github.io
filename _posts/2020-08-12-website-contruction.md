---

layout: post

title: 网站构建指南

subtitle: 通过beautiful-jekyll工具来完成整个架构

gh-repo: /Richard-Li-lab-team/Richard-Li-lab-team.github.io

gh-badge: [star, fork, follow]

tags: [website]

comments: true

---

#### **beautiful-jekyll**简介

> **Beautiful Jekyll** is a ready-to-use template to help you create a beautiful website quickly. Perfect for personal sites, blogs, or simple project websites. [Check out a demo](https://beautifuljekyll.com/) of what you'll get after just two minutes. You can also look at [my personal website](https://deanattali.com/) to see it in use, or see examples of websites other people created using this theme [below](https://github.com/daattali/beautiful-jekyll#showcased-users-success-stories).



我们的课题组网页以[beautiful-jekyll](https://github.com/daattali/beautiful-jekyll)为基础进行架构。该工具的最大优势就是可以使用markdown文件构建页面。markdown语法学习可参照该教程：[Markdown 基本要素](https://shd101wyy.github.io/markdown-preview-enhanced/#/zh-cn/markdown-basics?id=markdown-基本要素)。编写markdown文件可使用[*Typora*](https://www.typora.io/)。



#### 网页界面介绍

- Richard Li's Lab页面

该页面为根目录下index.html文件（注意不是index1.html），若要进行修改，应使用html与CSS语法。

然后该页面下为post，用来展示新的文章。此处可使用markdown文件，放置在post文件夹中，注意命名统一，在编写过程中，应注意在最开始添加如下语句，如：

```
---
layout: post
title: 网站构建指南
subtitle: 通过**beautiful-jekyll**工具来完成整个架构
gh-repo: /Richard-Li-lab-team/Richard-Li-lab-team.github.io
gh-badge: [star, fork, follow]
tags: [website]
comments: true
---
```

- Home界面

该页面源文件为pages文件夹下的home.md，可通过修改该文件修改页面布局。此时（2020.8.12）暂未完成美化工作，未来计划使用CSS语法进行布局优化。

- People界面

该页面源文件为pages文件夹下的people.md，可通过修改该文件修改页面布局。未来计划将实验室成员简历及照片展示于此。

- Publications界面

该页面源文件为pages文件夹下的publications.md，可通过修改该文件修改页面布局。目前（2020.8.12）已完成2020年6月前lab文章的汇总，并关联至李学军教授的google scholar界面。未来新文章发表后需添加信息于此，并加上pubmed页面作为abstract，若为开源文章，可添加文章页面于此。同时应在google scholar主页上添加相应文章信息。

- Teaching界面

暂未计划开发。

- Careers界面

记录李学军教授的职业生涯与相应社会兼职。

- Contact界面

记录李学军教授联系方式，包括E-mail与中南大学教师主页

#### 网站整体布局修改

可通过根目录下_config.yml进行修改，具体方法可参见[beautiful-jekyll](https://github.com/daattali/beautiful-jekyll)的Github主页。建议尽量不改动。

