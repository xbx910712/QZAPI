#时间信息
获取当前时间、周次、学年等信息

##请求
``` url
GET http://jwxt.xxx.edu.cn/app.do?method=getCurrentTime&currDate={$查询日期}
```

##返回
``` json
{
	"zc":20, //当前周次
	"e_time":"2019-01-20", //本周结束时间
	"s_time":"2019-01-14", //本周开始时间
	"xnxqh":"2018-2019-1" //学年学期名称
}
```

##例程
``` url
GET http://jwxt.xxx.edu.cn/app.do?method=getCurrentTime&currDate=2019-01-14
```