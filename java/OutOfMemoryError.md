# exception-2018-001 @2018.1.11
    tomcat:java.lang.OutOfMemoryError: Java heap space
原因:<br>
应用程序中启动线程增多，tomcat启动参数内存值设定的过小导致<br>
方案:<br>
对tomcat容器，启动时对jvm设置内存<br>
C:\Program Files\Apache Software Foundation\Tomcat 8.0\bin\bcatalina.bat<br>
JAVA_OPTS=-Xms512M -Xmx2048M -server<br>
