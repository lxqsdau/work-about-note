# work-about-note
业务相关

## 记住密码
> 无论是否选中记住密码，每次登录都要把用户名，密码保存在 localstorage，
> 本地存储，还有一个值来保存是否，点击了记住密码按钮
> 进入登录页面，先判断上次是否点击了，记住密码，是则获取用户名密码，执行登录提交函数

三个值，需要保存在localstorage，用户名，密码，是否记住密码

## 退出登录
把localstorage里记住密码按钮值，设置为不记住密码

## 是否登录
封装ajax，返回code是某个值，则回到登录页面

## 手机号，关键词搜索
去除前后空格