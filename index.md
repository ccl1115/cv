# 禹璐

## 个人资料

*   姓名 禹璐
*   年龄 28
*   性别 男
*   电话 18688716376
*  Email bb.simon.yu@gmail.com
* Github https://github.com/ccl1115

## 教育

#### 大连理工大学 `2007-2011`
* 软件学院 网络工程 本科


## 工作及项目

#### 蓝莓 `2014.05 - 2015.09`
* 蓝莓Android客户端
* 业务开发：
     * 聊天模块：语音，图片，匿名实名
     * 个人中心：个人资料，发表的帖子，赞列表
     * 发现模块：搜索，附近的人，老乡动态，打工圈
     * Feeds：朋友，附近，在职三个Feeds流
* 核心技术：
     * 外部依赖库完全接口化，使得推送服务（百度推送，腾讯信鸽），统计（MTA，友盟），网络库等模块可以灵活切换
     * 安全并且严格的图片加载，极低的OOM错误率
     * 使用维纳斯长链接网络库，保证极高的连通率，解决DNS污染、劫持，网络链接超时，套接字无法建立等问题
     * 谨慎地网络数据处理，全局性地保证Server回吐任何数据不会造成App出现Crash
     * Pub/Sub消息系统，减少模块间的依赖，高效的模块间通讯
     * 配置系统：通过一个外部配置App直接对App进行配置，例如修改服务端Host等
     * 内存溢出监测：使用开源的LeakCanary监测Activity，Fragment等组建的内存溢出
     * 自定义控件：
         * AdvancedListView 可复用的支持下拉刷新、加载更多的ListView
         * AsyncImageView 异步加载图片的ImageView，支持url，file，resources等方式，包含二级缓存（内存Cache，文件LRUCache）
         * RoundedButton 不使用额外图片的圆角按钮，支持自定义背景色和圆角弧度
         * TopBar 接口化的自定义标题栏
* 项目管理
     * 早期使用Maven项目管理，后期使用Gradle系统
     * 使用持续集成系统
     * 使用[OSChina](http://www.oschina.net)提供的免费Git服务和Issue系统，自己搭建Git服务（[Stash](https://www.atlassian.com/software/bitbucket/server)）作为备份。
     * Gitflow开发模式，保证更好地响应需求变更，高效地进行合并、回滚、预先开发以及紧急修复。
* iOS版本：Feeds模块开发

#### 百度 `2013.05 - 2014.05`
* 百度贴吧Android客户端
* 工作内容：
    * 业务开发：语音聊天版本，我的帖子，可复用标题栏等
    * 技术难题：multi-dex实现，代码、模块插件化，自定义布局实现层级优化
    * 贴吧SDK：集成至其它App中，包括核心功能，极简版SDK仅500KB
    * 垂直版本：可自定义的版本，自定义启动页面、新手引导页面，推荐吧列表等；编写Python脚本自动生成并打包；例如贴吧青春版，贴吧视频版
* 技术分享：动态加载，高效的自定义布局和控件，Android UI系统解析

#### 人人网 `2011.09 - 2013.04`
* Android官方客户端
* 工作内容：
    * 新版本UI重构，基于Fragment架构
    * 核心业务开发

## 技能

#### 语言
* Java
* Python
* JavaScript
* Golang
* Objective-C

#### 平台
* 客户端：Android/iOS
* 前段框架：Angular/Bootstrap
* 后台框架：
    * NodeJS: Express
    * Golang: Martini, Gorilla
    * Python: Django, Flask
* UI Design/Prototype

#### 工具
* Intellij IDEA/Android Studio/Eclipse (Android development)
* Xcode (iOS development)
* Vim (Front-end/Back-end development)
* Latex, Markdown (Document writing)
* Shell script
* Adobe Illustrator/Photoshop
