# 仿网易云音乐APP
该项目是我刚学完vue2，vuex时拿来练手的项目，里面只实现了部分主要功能（包括：网易云主页面轮播图、推荐歌单展示、歌单列表详情、歌曲播放、歌词滚动、歌曲搜索、用户登录、个人中心页面展示）
## 技术栈
- vue2全家桶
- axios
- swiper
- vant
- less
## 项目介绍
本项目使用vue-cli搭建项目，使用less预处理器和vant组件库构建项目的页面；通过axios调用网易云API接口获取音乐、歌单、账号信息、搜索功能；通过构建路由组件，实现各个功能页面之间的切换，实现路由的懒加载和组件懒加载，减少打包压力。封装公用组件，如：推荐歌单、歌曲列表，提高组件的复用性、降低耦合度；对登录功能使用token进行验证，配置全局路由守卫和路由独享守卫实现用户未登录前进入个人中心需先进行登录。
## 补充
本项目包含网易云音乐API接口，即：NeteaseCloudMusicApi，运行本项目时需先调用接口
