# biu-jenkins-jobs

## 说明

本工具主要是针对公司业务所写，具有较强的局限性，并不能直接应用到其他项目。
因为配置文件涉及到公司业务，所以不会提供配置文件。

## 思路

1. 读取用户输入
2. 读取提取好配置信息 xml 模板
3. 用输入的信息替换模板中的模板字符串
4. 用替换好的 xml，POST 请求 http://username:tokenf@jenkins.examle.com/createItem?name=jobsName
