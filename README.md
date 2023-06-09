# 反弹Shell生成工具（Web离线版）

近期一直在学习攻击相关知识，学海无涯，还有很多知识需要掌握，在这些过程中发现了一些大佬写的文章和工具等，自己用起来很方便，在这里做个知识收集，我会一点一点更新，可能每次更新排版都不一样，因为自己还没完全总结，此文章有空会持续更新……

今天先分享第一个工具：反弹Shell生成工具（Web离线版）：Reverse-Shell_Web_Tools

**这个修改的工具没有加到公众号后台的自动回复，有需要的朋友直接关注微信公众号留言就行，我看到就会发**
近期还在给这个工具增加点内容，争取做到全部静态使用

------

### 反弹shell编写
之前在网上找到【**棱角安全团队**】制作的反弹shell在线编写工具，当时收藏了，近期看了一下有更新，特别推荐这个工具，原项目是开源的，原项目地址：[reverse-shell-generator](https://github.com/0dayCTF/reverse-shell-generator)。棱角团队的大佬应该有所优化，我自己也结合另一个大佬的工具添了点东西，如有有喜欢的可以联系我。

#### 增加内容：
![image.png](https://cdn.nlark.com/yuque/0/2023/png/26729627/1681830298663-dd676623-4d75-45ea-b20b-a5d7c9472c72.png#averageHue=%231f1f1f&clientId=uc1088a34-34b7-4&from=paste&height=841&id=u84c02eb4&name=image.png&originHeight=1262&originWidth=2560&originalType=binary&ratio=1.5&rotation=0&showTitle=false&size=84456&status=done&style=none&taskId=udc03d970-8661-4f1c-960f-c2594847996&title=&width=1706.6666666666667)<br />![image.png](https://cdn.nlark.com/yuque/0/2023/png/26729627/1681830305970-0689dd9a-facf-49ca-add7-62d0a8133732.png#averageHue=%231e1e1e&clientId=uc1088a34-34b7-4&from=paste&height=841&id=u476e0fea&name=image.png&originHeight=1262&originWidth=2560&originalType=binary&ratio=1.5&rotation=0&showTitle=false&size=102571&status=done&style=none&taskId=u12dc0590-cd1c-42e7-8f36-9586073b678&title=&width=1706.6666666666667)<br />![image.png](https://cdn.nlark.com/yuque/0/2023/png/26729627/1681830314096-5dbafdb0-e919-40df-8615-2c9c24aa9408.png#averageHue=%231d1d1d&clientId=uc1088a34-34b7-4&from=paste&height=841&id=u9bc29b1a&name=image.png&originHeight=1262&originWidth=2560&originalType=binary&ratio=1.5&rotation=0&showTitle=false&size=93508&status=done&style=none&taskId=u4933e39e-1063-4020-ac43-d432e5c15c0&title=&width=1706.6666666666667)<br />![image.png](https://cdn.nlark.com/yuque/0/2023/png/26729627/1681830355059-6ff7ff0e-7d74-4ea2-bec5-e06217f19f1a.png#averageHue=%231d1d1d&clientId=uc1088a34-34b7-4&from=paste&height=841&id=uce936447&name=image.png&originHeight=1262&originWidth=2560&originalType=binary&ratio=1.5&rotation=0&showTitle=false&size=82598&status=done&style=none&taskId=ua97fb907-c970-4f3a-8e90-457a23f3df7&title=&width=1706.6666666666667)

修改后的工具在【[棱角社区反弹shell在线生成](https://forum.ywhack.com/reverse-shell/)】的基础上，结合【[凌星阁-Shell编码](https://sec.lintstar.top/Java-shell.html)】完成。
以上的修改后的工具可以直接在本地静态使用，也可以放到自己的VPS里，随时使用，如果有需要的话可以联系我分享给你们。**

#### 棱角社区反弹shell在线生成：
[https://forum.ywhack.com/reverse-shell/](https://forum.ywhack.com/reverse-shell/)<br />**截图：**<br />![image.png](https://cdn.nlark.com/yuque/0/2023/png/26729627/1681829938106-8965b7ca-c1f5-47d7-9d37-98d5308add2a.png#averageHue=%231f1f1f&clientId=uc1088a34-34b7-4&from=paste&height=841&id=u7308aa88&name=image.png&originHeight=1262&originWidth=2560&originalType=binary&ratio=1.5&rotation=0&showTitle=false&size=85700&status=done&style=none&taskId=ue4b67429-f83d-4785-8cd4-ecc4251fb51&title=&width=1706.6666666666667)<br />![image.png](https://cdn.nlark.com/yuque/0/2023/png/26729627/1681829957540-8f4346a3-5dab-453b-9016-a760ba7cb210.png#averageHue=%231f1e1e&clientId=uc1088a34-34b7-4&from=paste&height=841&id=udf97d1d3&name=image.png&originHeight=1262&originWidth=2560&originalType=binary&ratio=1.5&rotation=0&showTitle=false&size=104532&status=done&style=none&taskId=u19611049-8b25-4696-8c2a-e04d0635470&title=&width=1706.6666666666667)<br />![image.png](https://cdn.nlark.com/yuque/0/2023/png/26729627/1681829966218-e330bf6a-f57f-47be-b63d-08e25cc1e629.png#averageHue=%231f1e1e&clientId=uc1088a34-34b7-4&from=paste&height=841&id=u8d483fea&name=image.png&originHeight=1262&originWidth=2560&originalType=binary&ratio=1.5&rotation=0&showTitle=false&size=96201&status=done&style=none&taskId=u735215cb-905b-4944-a8c7-2fef7fed265&title=&width=1706.6666666666667)

**PS：**
如果大佬对我修改这个工具有意见，也麻烦及时告知，我尽快撤掉。

**需要离线版的朋友可以关注微信公众号【小白变身】，留言我私发你们。**

【小白变身】

![image](https://user-images.githubusercontent.com/107027804/232938244-1b0e01c6-3a74-4457-8047-42d29781ee0d.png)

