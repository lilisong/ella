<h1>Ella: HBase Cluster Monitor on Region,Table,Server Level.<br />
<em><sup><sup>'A Watchdog on HBase'</sup></sup></em></h1>

###More details, see wiki page(will include chinese wiki 中文使用手册，NOT AVAILABLE NOW！): 
https://github.com/mayanhui/ella/wiki

###################################################
## Ella ############
###################################################
Ella is a "Border Collie", a handsome and smart dog.

A watchdog, monitor hbase.

Watching list:

1. Table level request statistics (Write/Read/Total Count, TPS)
2. Region level request statistics (Hot Region)
3. Server level request statistics (Write/Read/Total Count, TPS, Hot Server)
4. zookeeper monitor
5. Chart display



##Environment
Only Support Linux.

##License
Released under the GPLv3 license. For full details, pleasesee the LICENSE file included in this distribution.



## Framwork
* Java 1.6 (http://www.oracle.com/technetwork/java/index.html)
* Jetty 8.1.11.v20130520 (http://www.eclipse.org/jetty/)
* HBase 0.94.0 (http://hbase.apache.org/)
* Hadoop 1.1.2 (http://hadoop.apache.org/)
* Maven 2.2.1 (http://maven.apache.org/)
* MySQL 5.5.29 (http://www.mysql.com/)
* JMX (http://zh.wikipedia.org/wiki/JMX)
* FastJson (https://github.com/alibaba/fastjson)
* Quartz 1.5 (http://www.quartz-scheduler.org/)
* D3 (https://github.com/mbostock/d3)
* gRaphael (http://g.raphaeljs.com/)


## Roadmap
1. Add color to TPS value, like red if bigger than 0. (done)
2. Add Hot Region Request list. (done)
3. Add Server Request list. (done)
4. <b>Simple install and deploy steps. Change the index page to configuration page, input hbase jmx url and other configure.</b>
5. Add zookeeper monitor. (done)
6. change css style. (done)
7. <b>Add user guide for ella.</b>
8. Add return home page link in details page. (done)
9. Add footer.jsp for Copyright. (done)
10. <b>Add detail page for server,region</b>
11. Add JVM_OPTS for Jetty Server (done)


## Ella First Page
![Ella First Page](http://static.oschina.net/uploads/space/2013/0720/142647_s5dz_818358.jpg)
