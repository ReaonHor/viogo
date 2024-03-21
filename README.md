# VIOGO
首页

![image](https://github.com/ReaonHor/viogo/assets/116567159/01bd1eed-2841-4f52-b9c3-618872526139)

个人中心
![image](https://github.com/ReaonHor/viogo/assets/116567159/97b56b14-b40a-4405-b05e-7360a57888c7)
播放页面
![image](https://github.com/ReaonHor/viogo/assets/116567159/3f78aa84-d1ef-4d10-9006-d8e334eba8f6)



## 实现功能

1. 用户登录、注册、弹幕，评论，个人收藏，点赞内容体系
2. 视频播放
3. 直播栏
4. 一对一私信实时聊天

## 前端

**技术栈**

react18、redux/react-redux、react-router-dom v6  axios  CSS-IN-JS(style-components)、sass、AntDesign



**页面层级目录**

* 登录
* app
  * 首页

    * 推荐

    * 热门
    * 直播

  * 动态

    * 综合
    * 写动态

  * 我的

    * 历史记录
    * 我的收藏
    * 点赞

  * 个人中心

    * 动态
    * 投稿

  * 消息
    * 聊天列表
    * 回复我的
    * 收到的赞

## 后端

**技术栈**

nestjs、mysql

* react-intersection-observer  github上的一个

* redux
* 视屏封面组件的优化
* 历史记录的封装，localstorage优化，LRU算法
* socket.io的
* axios转发cookie
* 登录鉴权
