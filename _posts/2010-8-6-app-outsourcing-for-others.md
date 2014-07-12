---

layout: post
category: topic
title: iOS App 外包过程

---

最近帮助 The American Dollar 乐队制作了一个 App，外包过程如下:  

1. 交流之后确定下来。我是直接用 PS 画的，敲定后就当作参考图纸用了。 

2. 基本完成后，开始 Ad Hoc Testing，然后进一步交流，小幅改动，修复错误。 

3. 结束 Ad Hoc 测试阶段，客户开始去注册 iDP，之后加你的 Apple ID 为 iTunes Connect Technical User，这个时间你需要准备好一个没有参与其它 iTC 的 Apple ID 给他们。 

4. 用客户提供的信息（他们注册时候的邮箱以及公司或者个人名称）在 Keychain Access 生成一个 Request，就像第一次激活 iDP 那样，之后发给他们。 

5. 客户通过提交你的 Request 来生成一个 Distribution Certificate File 给你。 

6. 客户制作 App ID 以及 Distribution Provisioning File，之后发给你。 

7. Build，然后就全是 Technical User 的事情了。当然，如果是第一个 App，提交程序前你可能需要向客户确定他们的 Company Name，因为只有这一次设定机会。另外，什么类别，介绍，截图，关键词，以及 EULA 等等都需要提前问清楚，这个一般都是他们准备的。 

8. All Done. 


欢迎你来 [这里](http://v2ex.appspot.com/t/524 "V2EX") 发表看法 :)