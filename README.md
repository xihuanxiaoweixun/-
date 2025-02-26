# 送给安泰宝宝们

uu们！最近有小伙伴反馈，在浏览 [https://www.acem.sjtu.edu.cn/notices/87236.html](https://www.acem.sjtu.edu.cn/notices/87236.html) 这个页面时，
只能看到带着 xxx 学号的同学的主修和辅修专业信息。
可大家心里就犯嘀咕啦：这些学号背后到底是哪位同学呀？

这不，我就被紧急 “抓壮丁”，肩负起揭开这个小谜团的重任。
费了老大劲，总算是把对应的同学名字都找齐啦！
现在就把这份精心整理的 “大礼包” 双手奉上，让大家对这些信息有个完完整整的了解～

## 礼包介绍
1. **“安泰主修辅修数据 - 无姓名”**：即 [https://www.acem.sjtu.edu.cn/notices/87236.html](https://www.acem.sjtu.edu.cn/notices/87236.html) 网站上看到的表格。
2. **“安泰主修辅修数据 - 有姓名”**：增添了学生姓名这一列。大家可以直接看到 uu 们的名字，以及 uu 们修了什么专业。
3. **“姓名获取.ipynb”**：得到 “安泰主修辅修数据 - 有姓名” 数据的代码。
4. **“数据拆分.ipynb”**：得到 “主修辅修一览” 文件夹的代码。
5. **“主修辅修一览”文件夹**：各种主辅搭配，uu 们可以看到谁和自己并肩作战。双学位的 uu 们，可以看辅修是 “无” 的那两个表格。

## 复现步骤
1. 下载压缩包，解压。
2. 代码在当前目录下可直接运行：
    - 先运行 `姓名获取.ipynb`，可得到 “安泰主修辅修数据 - 有姓名”。在运行程序之后，会打开一个网页，需要你输入自己的jaccount信息（默认必须在20秒内填完，此时间可在程序中修改），登录之后就开始正式“抓人”了。抓名字速度可调整（在代码中修改time.sleep()参数即可）
    - 再运行 `数据拆分.ipynb`，可得到 “主修辅修一览”。
