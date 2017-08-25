# logger.js

前端error和自定义日志日志上报服务器
		

# 使用方法
		前端引入logger.js自动使用
		
# 服务端配置
    依赖socket服务，需要自己配置一个socket服务器
    简单配置：基于socket.io快速搭建一个socket服务

- 前端配置自己的服务地址
``` 
    var url = "XXX.XXX.com";//socket地址
    BugTrack({socketUrl: url})
```

- 添加前端日志
``` 
    var BugTrack = new BugTrack({socketUrl: url})
    BugTrack.logger("错误日志")
```    




 		






		
