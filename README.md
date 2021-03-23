# 039ssm知识库管理系统
039ssm知识库管理系统

#### 介绍
```
文件集中上传：系统支持单文件上传以及批量上传，系统支持zip、rar格式的压缩包导入。
亮点创新 多格式文件在线预览 用户可以对所有公共文件进行浏览，
支持office，pdf格式以及常见图片格式，音频格式，音频播放以流媒体服务搭载实现边下边播的用户体验。
文档链接：系统支持用户对喜爱的文档进行收藏及发送到常用文档。
文档关联：手动关联：用户可以手动对文件关联相关的文件。
自动关联：系统可以自动关联类似文档
规则使用：系统对用户上传的过大文件（视频）进行压缩来加快用户在线预览打开的速度，对文档自动提取简介和关键词。
对视频、office等文件提取缩略图。
系统中可增加词典，增强分词效果
智能检索：系统包含全文检索、多重条件检索、关键词检索。同时还支持对检索结果再次附加条件检索。
用户管理：普通用户可以对自己的文件夹、收藏夹管理。用户可以分享自己的文档到公共资源库中。
管理员可以对系统中的用户管理、公共文件审核，系统分类的管理，一些数据的统计和日志记录的查看
用户评论：用户可以对文档进行评论
文本处理：能够支持中文，人名、组织机构名、时间、地名、目标类型、目标名称等实体识别，能对常见文本格式抽取。
文档推荐：系统使用协同过滤算法推荐用户可能会查看的文档
知识图谱：系统中的知识以树结构存放，可以通过知识图谱快速到达你要找的知识点。对于每个节点都有详细的介绍。
智能提取：系统结合PageRank、TF-IDF等算法组织知识点在我们的库中，用户可以通过半自动化的操作，去提取归纳知识，产生新的文档。
信息统计：系统对文档的数据进行统计分析，以图表的方式呈现。
新建文档：用户可以使用在线多功能编辑器新建文档
```

源码获取：[点此获取](http://www.shuyue.fun/index.php?type=productinfo&id=140)

#### 环境需要
```
1.运行环境：最好是java jdk 1.8，我们在这个平台上运行的。其他版本理论上也可以。
2.IDE环境：IDEA，Eclipse,Myeclipse都可以。推荐IDEA;
3.tomcat环境：Tomcat 7.x,8.x,9.x版本均可
4.硬件环境：windows 7/8/10 1G内存以上；或者 Mac OS；
5.是否Maven项目: 查看源码目录中是否包含pom.xml；若包含，则为maven项目，否则为非maven项目
6.数据库：MySql 5.7版本；
```

#### 技术栈
```
1. spring+spring mvc+mybatis+bootstrap+jquery
```

#### 使用说明
```
1. 使用Navicat或者其它工具，在mysql中创建对应名称的数据库，并导入项目的sql文件；
2. 将项目中jdbc.properties配置文件中的数据库配置改为自己的配置
3. 使用IDEA/Eclipse/MyEclipse导入项目，Eclipse/MyEclipse导入时，若为maven项目请选择maven;若为maven项目，导入成功后请执行maven clean;maven install命令，配置tomcat，然后运行；
4. 运行项目，输入http://localhost:8081/lib/login 登录
5. 登录账号：11184629@qq.com  密码：123456
```

#### 注意事项
```
需要先安装openoffice，下载地址：http://www.openoffice.org/download/index.html
并在TranslateUtils中修改相关路径；
```
#### 运行截图
![输入图片说明](https://images.gitee.com/uploads/images/2021/0315/132011_82b631cd_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0315/132028_41f53d4a_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0315/132047_3fc983ce_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0315/132057_0339831d_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0315/132109_d024ea31_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0315/132119_ad0b43ee_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0315/132130_7fb825e4_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0315/132138_e1774997_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0315/132148_62d04045_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0315/132158_3a59ce9e_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0315/132218_0a460f8d_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0315/132229_9d74c12b_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0315/131938_65f53a48_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0315/132258_81a8e044_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0315/132306_8f5618d5_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0315/132313_7d443025_863230.png "屏幕截图.png")
