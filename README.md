# java-wrapper

将jar 文件设为windows 服务并自动启动
generated using [wrapper](http://wrapper.tanukisoftware.com/doc/english/integrate-simple-win.html)

请查上以上文档

## usage

mv you app.jar to bin/
and modify conf/wrapper.conf

add wrapper.java.classpath.2=../bin/app.jar

add app params

wrapper.app.parameter.1=web.core

change service name
wrapper.name=webtest
