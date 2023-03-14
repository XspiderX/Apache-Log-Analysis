# Apache-Log-Analysis
Apache日志分析程序，Linux开发课程实践项目

通过C++实现日志分析，使用一个类Log-Analysis，借助该开源代码(https://github.com/xjtuecho/IPLocator)实现IP查询

调用方式:
Log-Analysis log("日志文件路径");
log.time_analysis("统计结果保存路径"); //统计每个时间段的请求数
log.ip_analysis("统计结果保存路径"); //统计不同ip地域的请求数
log.user_analysis("统计结果保存路径"); //统计不同用户的行为

生成库方式见INSTALL，可通过test文件夹下make test,make test-install生成可执行程序测试代码及生成的库

data文件夹存放了示例日志文件，纯真IP数据库，以及默认日志分析结果保存文件
