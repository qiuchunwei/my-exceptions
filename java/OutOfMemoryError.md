# exception-2018-001 @2018.1.11
### tomcat:java.lang.OutOfMemoryError: Java heap space


**原因:**
	
	应用程序中启动线程增多，tomcat启动参数内存值设定的过小导致
	
**解决方案:**

*对tomcat容器，启动时对jvm设置内存*

C:\Program Files\Apache Software Foundation\Tomcat 8.0\bin\bcatalina.bat

`JAVA_OPTS=-Xms512M -Xmx2048M -server`


**更详细的参照以下链接:**

[outofmemory](http://outofmemory.cn/c/java-outOfMemoryError "Google")