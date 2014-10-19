HIT腾讯俱乐部网站规划文档
技术部/胡文杰

　　新学期开始，腾讯俱乐部迎来新的成员换血换代，作为新的俱乐部成员，应主席倡议，决定新开发俱乐部官方网站，具体规划如下。
一、主体部分
1、成员注册、登陆（每位成员都有自己在俱乐部中的成长经历与贡献，同时可以查看俱乐部分发下来的任务）
　　具体包括：成员信息（头像、个人信息、俱乐部内职务），任务（俱乐部实时发布的任务，消息），成长信息（完成的任务情况、心灵墙）
　　按照职务不同应该拥有不同的权限，主席或负责人可以查询各成员心灵墙反馈的消息，多一个部分可以来查询这些信息
　　2、主体包括：相片墙（展示腾讯俱乐部的文化、性质的一些图片，腾讯公司的照片），
　　             成员风采（历任主席、负责人的介绍），
　　             新闻中心（俱乐部实时的一些活动，腾讯公司发生大事件等新闻素材），
　　             项目概况（显示最新的项目信息，同时展示优秀项目的成果）
　　             规章制度（俱乐部的规章制度，规范成员的工作活动）
                 俱乐部资源（成员申请借书，送公仔）
　　             公司链接（与腾讯公司官网链接，与腾讯公司学长、HR链接）
　	3、尾部：
　　             俱乐部logo，备注，链接其他俱乐部网站，链接学院、学校网站
　　
二、前端设计（采用bootstrap框架）
  
1、相片墙

1、顶端选项栏应有 成员登陆状态（左上角显示小头像），注册选项，登陆选项（点击登陆后下滑出一个登陆窗口，登陆不成功反馈信息，登陆后去除登陆注册选项，变为显示个人信息）
2、照片风格如图片显示，下面有div有渐变度的处理（类似ios桌面风格），显示每张照片的信息

　　2、主体部分

　　每一块以圆型风格（倾向于移动端应用的图标，扁平清晰化的设计风格）一共是7块
　　
　　3、尾部


三、其他页面
　　1、成员登陆界面

每个成员都有相应的经验条和等级，每天签到，参加完成项目，参与俱乐部活动，完成俱乐部相关办公工作都可以获得一定份额的经验（学期终评优看经验给予奖励，红包。每学期归0一次（或每年））　
2、成员风采

（点击每一块，都可以看到相应人的介绍，介绍页面如百度百科）
　　
3、新闻中心

（项目概况与规章制度同风格）

4、心灵墙
    提供一个textarea用来大家来写自己想给俱乐部和俱乐部负责人的话，风格如邮箱，
    这些话统一都发到同一个平台，主席或负责人等可以在这个平台看到这些信息，收集这些信息作为开展活动资料。

5、俱乐部资源
在这个模块内成员可以申请借书，拿公仔，网站会显示书借出收回情况，公仔的收入送出情况 

6、其他
做一个悬浮的云，用float定位始终在页面上端，显示天气情况（倾向于做天气动画，并相应的调节页面背景颜色（白-灰））

四、使用技术
前端使用HTML，CSS，js开发，使用bootstrap框架
后台（根据项目组成员的学习情况，用PHP或Java）
    （做用户登录，心灵墙，后台反馈登录状态，后台反馈前台消息的数量）
数据库 mysql

