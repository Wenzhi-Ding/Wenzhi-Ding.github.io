---
layout: page
---

中文\|[English](./project.html)

<li class="posts-labelgroup2"></li>

### Coding Notes

- GitHub仓库：<a class='icon-ext-link' href='https://github.com/Wenzhi-Ding/coding_notes' target="_blank">链接</a>

在这个仓库中同步了我做过的编程或数据练习，主要是用Python写的。在首页罗列了一些我认为比较有趣、有价值的题目和我的解。欢迎尝试这些题目并提出思路和意见。

<li class="posts-labelgroup2"></li>

### PyReminder

- 版本：0.1.1
- 发布日期：2019年10月28日
- GitHub仓库：<a class='icon-ext-link' href='https://github.com/Wenzhi-Ding/py_reminder' target="_blank">链接</a>

这是一个发送邮件的Python装饰器。在Python函数体前附加了该装饰器后，一旦该函数执行完毕，程序将按照状态向你发送一封邮件，既可以提示完成信息，也可以捕捉发送报错信息。这个工具特别适用于以下两个场景：

- **周期性任务**：比如每天定时的爬虫完成后，可以邮件提示你完成的情况。我们监视的网页随时可能会改版导致爬虫失败，这个工具可以及时的提醒你，从而尽快做出调整，避免损失观测数据。
- **长耗时任务**：对于机器学习或大型数据集的处理，常常需要等待较长的时间。通过应用该工具，你可以提交任务后放心的去做其他事情，等收到邮件提醒了再回来继续。

<li class="posts-labelgroup2"></li>

### Error Catcher

- 版本：0.2
- 发布日期：2020年12月24日
- GitHub仓库：<a class='icon-ext-link' href='https://github.com/Wenzhi-Ding/error_catcher' target="_blank">链接</a>

这是一个用于捕获报错信息的Python装饰器。在捕获错误提示的同时，它还能捕获在该时刻（1）与该错误有关的变量的值和（2）其他你设定的感兴趣的变量的值。该装饰器返回的信息既可以是打印在命令行的，也可以是在日志文件中的。总结而言，该工具比原生的`try & except`在处理异常时更有用，同时更方便。

<li class="posts-labelgroup2"></li>

### Standardize Country Code

- 版本：0.1
- 发布日期：2021年6月3日
- GitHub仓库：<a class='icon-ext-link' href='https://github.com/Wenzhi-Ding/StdCountryCode' target="_blank">链接</a>

这个工具帮助社会科学的研究人员将各个数据来源中五花八门的国家名、国家代码标准划成统一的ISO国家编码。

目前这套数据是横截面的。考虑政权变化的版本在计划中。如果您有兴趣加入此项目，请务必联系我！
