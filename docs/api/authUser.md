#登录
登录帐号

##请求
``` url
GET http://jwxt.xxx.edu.cn/app.do?method=authUser&xh={$学号}&pwd={$密码}
```

##返回
``` json
{
	"flag":"1", //是否成功
	"userrealname":"张三", //用户真实姓名
	"token":"", //令牌，调用其它API时需要附带到HTTP请求header中的token参数中
	"userdwmc":"XXXX学院", //用户所在学院名称
	"usertype":"2", //用户类别
	"msg":"登录成功" //返回消息
}
```

##例程
``` url
GET http://jwxt.xxxx.edu.cn/app.do?method=authUser&xh=17111111&pwd=1234578
```