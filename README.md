# 【原创项目】教务管理系统
基于Springboot+Vue的【教务管理系统】，系统代码全部原创，并提供带敲视频和笔记  
大家好，我是武哥，最近给大家手撸了一个基于Springboot+Vue的教务系统，选课系统、课表、考勤系统、请假系统、成绩管理、作业等，可用于实习项目、毕业设计、课程设计等，系统全部原创，如有遇到网上抄袭站长的，欢迎联系博主~  

#### 项目在线体验地址  
体验地址：**（请电脑端浏览器访问）**：[http://111.229.67.228:85/](http://111.229.67.228:85/)  
管理员账号：**admin 123456**    
教师账号：**zhang 123456**  
学生账号：**zhangsan 123456**    
**管理员登录后，可以看到不同的教师和学生账号，均可登录，密码统一123456**  
线上环境，部分基础数据不允许修改（例如系统公告、课程和用户数据等等，否则可能影响其他小伙伴体验）业务功能可以随意体验。  

#### 项目技术栈 
> 前后端分离  
> 后端：Springboot2 + Mybatis  
> 前端：Vue2 + ElementUI  
> 数据库： MySQL  

#### 项目功能描述  

>**管理员**  
>登录、个人信息、修改密码、管理后台管理系统所有数据  
>首页查看各种通知、考勤状态和成绩分布的echarts统计图 
>####   
>**信息公告部分：**  
>1、**教务通知**：管理学校公布的教务通知，且在首页展示  
>2、**考试安排**：管理学校的各种考试安排，包括期末考试、补考重修考试安排等  
>3、**教室安排**：管理学校公共资源的使用情况  
>**行政管理部分：**  
>1、**学院管理**：管理学院的基本信息  
>2、**专业管理**：管理专业的基本信息（包括专业最低学分限制）  
>3、**班级管理**：管理班级的基本信息  
>**教学管理部分：**  
>1、**课程管理**：管理所有课程的信息，包括授课教师，上课时间，学分，课程状态等  
>2、**选课管理**：管理所有学生的选课信息  
>3、**成绩管理**：管理所有学生的成绩信息（成绩信息由授课教师录入）成绩分为平时分、考试分和总成绩，**其中平时分占30%，考试分占70%，总成绩自动计算**  
>4、**网上评教**：管理所有学生对他选的课的授课教师的评价信息  
**教务管理部分：**  
>1、**请假管理**：管理所有学生的请假信息，并且审核学生的请假信息  
>2、**作业提交**：管理所有学生提交的作业信息  
>3、**考勤管理**：管理所有学生的考勤信息（考勤信息由授课教师录入）  
>**用户管理部分：**  
>1、**管理员信息**：管理系统管理员账号  
>2、**教师信息**：管理系统教师的账号  
>3、**学生信息**：管理系统学生的账号  
>####   
>**教师**  
>登录、个人信息、修改密码  
>首页查看各种通知、考勤状态和成绩分布的echarts统计图  
>**信息公告部分：**  
>1、**教务通知**：查看系统首页的教务通知  
>2、**考试安排**：查看系统首页的考试安排  
>3、**教室安排**：查看学校教室的使用情况，可以看到哪些教室空闲，可以去使用  
>**行政管理部分：**  
>1、**学院管理**：查看学院的基本信息  
>2、**专业管理**：查看专业的基本信息（包括专业最低学分限制）  
>3、**班级管理**：查看班级的基本信息  
>**教学管理部分：**  
>1、**课程管理**：查看自己的所有课程的信息（包括必修和选修课），可以修改自己的课程状态  
>2、**选课管理**：查看所有学生选择自己课程的信息  
>3、**成绩管理**：管理所有自己课程的学生成绩信息，录入平时分和期末分，自动计算学生总成绩  
>4、**网上评教**：查看所有学生对他选的课的授课教师的评价信息  
>**教务管理部分：**  
>1、**请假管理**：查看所有学生的请假信息  
>2、**作业提交**：管理他的课程的所有学生提交的作业信息，**并且可以给学生提交的作业进行下载查看，然后完成打分**  
>3、**考勤管理**：管理他的课程的所有学生的考勤信息（考勤信息由授课教师录入）  
>####   
>**学生**  
>注册、登录、个人信息、修改密码  
>首页查看各种通知、考勤状态和成绩分布的echarts统计图  
>**信息公告部分：**  
>1、**教务通知**：查看系统首页的教务通知  
>2、**考试安排**：查看系统首页的考试安排  
>3、**教室安排**：查看学校教室的使用情况，可以看到哪些教室空闲，可以去使用  
>**行政管理部分：**  
>1、**学院管理**：查看学院的基本信息  
>2、**专业管理**：查看专业的基本信息（包括专业最低学分限制）  
>3、**班级管理**：查看班级的基本信息  
>**教学管理部分：**  
>1、**课程管理**：查看所有的课程信息，**并且可以对自己喜欢的课程进行选课操作，系统会自动根据学生已选的课程的上课时间进行冲突性校验，确保学生选的不同课的时间不冲突**  
>2、**选课管理**：查看自己选的所有课程，**在开课前，如果不想选了可以支持取消选课**  
>3、**我的课表**：可以查看自己选的课的课表信息。**系统会自动根据学生选的课的时间（周几、第几大节）动态生成真实对应的课表**  
>4、**成绩管理**：查看自己所有选课的成绩信息  
>5、**网上评教**：可以对自己选过的课的授课教师进行评教处理，提交对授课教师的评价，并且可以查看所有其他的评价信息  
>**教务管理部分：**  
>1、**请假管理**：学生可以提交自己的请假信息，等待管理员审核，审核通过后可请假  
>2、**作业提交**：学生可以提交自己选的课的课程作业，由授课教师下载查看并打分  
>2、**考勤管理**：学生可以查看自己上课的考勤情况，由授课教师录入  


#### 创新点  
> 1、echarts统计图统计，使用饼图统计学生的考勤状态、使用折线图统计成绩分布情况  
> 2、真实模拟实际教务业务：例如选课、课表、成绩、请假、评教、作业、考勤等  
> 3、课表的设计，实时动态根据学生选的课生成对应的真实课表（周几、第几大节、授课教师）  
> 4、巧妙的二级联动设计：在学生成绩模块，通过课程自动联动选课学生，避免手动选择  
> 5、巧妙的多模块之间关联设计：课程、选课、成绩等不同模块和三个角色之间的不同关联实现整个业务的闭环  
#### 部分关键页面截图  
登陆页面:![请添加图片描述](https://img-blog.csdnimg.cn/direct/3770352bc6614a1f9231e19793648bfb.png)
#### 管理系统页面  
系统首页![请添加图片描述](https://img-blog.csdnimg.cn/direct/105184f7015442508b2b68ae18856be3.png)
教室安排：![请添加图片描述](https://img-blog.csdnimg.cn/direct/ca809d629d8c4fa1be360606a7a8c09e.png)专业管理：![请添加图片描述](https://img-blog.csdnimg.cn/direct/e22faa904bce46278cf2ade5fde031af.png)课程信息：
管理员视角![请添加图片描述](https://img-blog.csdnimg.cn/direct/e8c3940ad1184c4ab19cc833086a11dc.png)![请添加图片描述](https://img-blog.csdnimg.cn/direct/78cb99e4934142888f6708306c88ceec.png)学生视角（可选课）：![请添加图片描述](https://img-blog.csdnimg.cn/direct/92267b3431e94cd18762b1902e1ffebe.png)我的选课（学生视角）：![请添加图片描述](https://img-blog.csdnimg.cn/direct/c07215fa35c645feb27e60f9341acee6.png)我的课表（学生视角）：![请添加图片描述](https://img-blog.csdnimg.cn/direct/9bc874751f214715a7cedcc695bae6b1.png)我的成绩（学生视角）：![请添加图片描述](https://img-blog.csdnimg.cn/direct/4451588873f345b0aa8f90547c544087.png)成绩录入（教师视角）：![请添加图片描述](https://img-blog.csdnimg.cn/direct/2244d6c40a5d415c9feba8d3e68fbb85.png)网上评教：![请添加图片描述](https://img-blog.csdnimg.cn/direct/b2d031bce99c4a82a4eeb660d525c5bd.png)
评教入口：![请添加图片描述](https://img-blog.csdnimg.cn/direct/6958157d3a8541fd9ac8862afd3730ca.png)
请假申请（学生视角）：![请添加图片描述](https://img-blog.csdnimg.cn/direct/4f0969025147462985bcf8d18f1b787d.png)
作业提交：![请添加图片描述](https://img-blog.csdnimg.cn/direct/27a3590e3111429bb43bab788b6ffe4f.png)
考勤管理：![请添加图片描述](https://img-blog.csdnimg.cn/direct/74dbfeda4cea44a59f8b08c1a3b414dc.png)
系统用户管理：![请添加图片描述](https://img-blog.csdnimg.cn/direct/9803613f0c3a4f27a3aa202101ed822c.png)

资料获取方式：加入知识星球：【项目训练营】即可  
<img src="https://img-blog.csdnimg.cn/direct/44f688415c0c47cc81ad08a1f275e6a4.png" width="300px" />

**星球提供**：  

1. （**价值**）星球内部的所有实战项目均提供脚手架、详细的笔记和完整的带敲视频，可以跟着完整学习视频敲出来，学习过程中提供一对一答疑。  
2. 星球内部的实战项目会一直更新，星球成员可以学习所有项目，具体项目列表如下（长期更新）：[https://www.yuque.com/xiaqing-en2ii/skflxg/cayqu7tvpxrwt9tf](https://www.yuque.com/xiaqing-en2ii/skflxg/cayqu7tvpxrwt9tf)  
3. 星球内部会提供不同的专栏，其中除了上述实战项目外，还有学习资料，比如经典学习笔记、超全面试题等  
4. 星球内部会不定期分享学习经验，开发经验，工作经验，如果你有需要，也可以提供相应文档    
