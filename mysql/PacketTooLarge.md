# exception-2018-002 @2018.1.11
### Packet for query is too large (3991 > 1024). You can change this value on the server by setting the max_allowed_packet'



**原因:**

	max_allowed_packet配置过小

**解决方案:**

*修改max_allowed_packet*

	set global max_allowed_packet = 2*1024*1024*10;

查看是否生效:1
查看是否生效:2
查看是否生效:3
查看是否生效:4
查看是否生效:5
查看是否生效:6
查看是否生效:7
查看是否生效:8


show variables like '%max_allowed_packet%';

![Smaller icon](/var/folders/js/cd5xbdxs7d37xsgv4gx3r4f00000gn/T/com.evernote.Evernote/com.evernote.Evernote/WebKitDnD.F3VEg2/QQ图片20180111102610.png)
