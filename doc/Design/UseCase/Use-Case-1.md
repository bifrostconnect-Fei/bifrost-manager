# Use Case Templet

## Use Case Name

## Revision History

**Date** : 16-10-2023
**Version** : 001
**Description**  : User check device list
**Author** : fei 

## Contant

### Brief Description

User can check the device which belong to the organisation and groups same as the user.

### Pre-Condition

1. User be regist in the organisation and group by admin
2. There are some device be registed in same group by admin.

### Post Condition 

The device are online. 

## Flow of Event 

### Basic Flows



格式:
1. 每个步骤都有数字编号来表明它的先后顺序
2. 每个步骤都有简短的标题来概括它的内容
3. 每个步骤要详细描述参与者跟系统之间的交互，一般按照正反两个方面来描述
    - 参与者向系统提交了什么信息
    - 系统作出了什么反应

### Alternative Flows

*branch flows, like user choose different action will lead different opration.*

备选流除了包括基本流类似的描述外，还包括：

起点：备选流从事件流的哪一步开始
条件：在什么条件下触发
动作：备选流下系统采取了哪些操作
恢复：备选流结束后，用例如何继续

### Spicial Requirment

*descripte un-functionality require*
- prefamence, stable, relable, scalable etc
- OS, devlop requirement
- Auth

### User interface

prototype 

### Additon info

## Example


名称	内容
用例名称	网站公告发布
用例标识号	202
参与者	负责人
基本描述	负责人用来填写和修改家教网站首页的公告，公告最终显示在家教网站的首页上。
前置条件	负责人已经登陆家教网站管理系统
基本流程	1． 负责人鼠标点击“修改公告”按钮
2． 系统出现一个文本框，显示着原来的公告内容
3． 负责人可以在文本框上修改公告，也可以完全删除，重新写新的公告
4． 负责人编辑完文本框，按“提交”按钮，首页公告就被修改
5． 用例终止
选择性流程 A1	在按“提交”按钮之前，负责人随时可以按“返回”按钮，文本框的任何修改内容都不会影响网站首页的公告
异常流程	1． 提示错误信息，负责人确认
2． 返回到管理系统主页面
事后状态	网站首页的公告信息被修改