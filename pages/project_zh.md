---
layout: page
---

中文\|[English](./project.html)

<li class="posts-labelgroup2"></li>

### PyReminder

- 版本：0.1.1
- 发布日期：2019年10月28日
- Github仓库：<a class='icon-ext-link' href='https://github.com/Wenzhi-Ding/py_reminder' target="_blank">链接</a>

这是一个发送邮件的Python装饰器。在Python函数体前附加了该装饰器后，一旦该函数执行完毕，程序将按照状态向你发送一封邮件，即可以提示完成信息，也可以捕捉发送报错信息。这个工具特别适用于以下两个场景：

- **周期性任务**：比如每天定时的爬虫完成后，可以邮件提示你完成的情况。我们监视的网页随时可能会改版导致爬虫失败，这个工具可以及时的提醒你，从而尽快做出调整，避免损失观测数据。
- **长耗时任务**：对于机器学习或大型数据集的处理，常常需要等待较长的时间。通过应用该工具，你可以提交任务后放心的去做其他事情，等收到邮件提醒了再回来继续。

<li class="posts-labelgroup2"></li>

### Standardize Country Code

- 版本：0.1
- 发布日期：【将于8月中旬上线（博士生资格考试后）】
- Github仓库：【将于8月中旬上线（博士生资格考试后）】

这个工具帮助社会科学的研究人员将各个数据来源中五花八门的国家名、国家代码标准划成统一的ISO国家编码。如果你的研究还包括了时间的维度，该工具同时考虑了政权变迁带来的编码变化。

- 对于Python用户，可以直接通过`pip`命令安装并导入运行；
- 其他语言的用户可以下载各个格式的数据集，通过合并的方式获得标准编码；
- Stata和R的包在开发计划中，不过尚未进行。

<li class="posts-labelgroup2"></li>