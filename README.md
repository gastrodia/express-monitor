express-monitor
===============

在node-mointor之上 提供并行状态监控和相应时长监控，提供四条曲线

请求增长曲线，是指系统收到的全部请求数随系统运行时间的变化（每收到一个请求记录一次 time totalReqNumber）

并行状态曲线，是指系统当前负载的请求数随系统运行时间的变化（每收到一个请求记录一次 time parallelNumber）

响应时间曲线，是指每个请求的相应时间随系统运行时间的变化   (每完成一个请求记录一次 time spendTime）

请求频度曲线，对请求增长曲线求导，得到请求频度曲线（或者应该叫请求进行的速度吧，不知道怎么描述了，随便起的名字）

