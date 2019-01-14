#时间信息
获取当前时间、周次、学年等信息

##请求
``` url
GET http://jwxt.xxx.edu.cn/app.do?method=getKbcxAzc&xh={$学号}&xnxqid={$学年学期ID}&zc={$周次}
```

##返回
``` json
[
	{
		"jsxm":"张三", //教师姓名
		"jsmc":"教学楼101", //教师名称
		"jssj":"10:00", //结束时间
		"kssj":"08:00", //开始时间
		"kkzc":"1", //开课周次
		"kcsj":"1000000", //课程ID
		"kcmc":"大学英语", //课程名称
		"sjbz":"0" //未知
	},{
		"jsxm":"李四",
		"jsmc":"教学楼101",
		"jssj":"12:00",
		"kssj":"10:00",
		"kkzc":"1",
		"kcsj":"1000000",
		"kcmc":"微积分",
		"sjbz":"0"
	}
]
```

##例程
``` url
GET http://jwxt.xxx.edu.cn/app.do?method=getKbcxAzc&xh=101010000&xnxqid=2018-2019-1&zc=5
```