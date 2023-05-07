# Python_Flask_ershou
Python基于Flask框架二手交易购物商城设计毕业源码案例设计

## 技术环境: PyCharm + Flask + Python3.7 + Redis + mysql

## 功能说明：
1.用户在没有登录的时候点击买东西，会弹出首先登录，同时也可以选择注册，注册需要邮箱验证码
2.商品有二级分类，可以按照大类或小类列表展示商品
3.加入购物车之后，用户可以去个人中心查看,由于二手商品数量每件比较少，所以限定用户在提交到购物车20分钟内完成结算，否则商品会从购物车内清除
4.如果用户没有完成结算的话，会在订单中，同样也有时间限制，每件商品都有根据当初进入订单那个时间算起至三十分钟后自动从订单中取消
5.在二手商城中难免有些买家觉着卖家定价不合适，会跟商家交谈，所以做了一个商品议价的模块，可以实现回复再回复的问题
6.卖东西的界面使用了可以拖拽的方式让用户上传商品更方便
7.用户发布的商品需要管理员审核后才能在前端展示出来哦
