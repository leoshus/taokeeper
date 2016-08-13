Notice:The file is encoded by UTF-8

   
   
1. Use To manage projects dependence using maven
2. Database Initialization: taokeeper-build/sql/taokeeper.sql
3. Implements com.taobao.taokeeper.reporter.alarm.MessageSender to send message.
4. Exec taokeeper-build/build.cmd to generate taokeeper-monitor.war

dependency jar:
mvn install:install-file -DgroupId=com.taobao.taokeeper -DartifactId=zkclient -Dversion=0.2-SNAPSHOT -Dfile=D:/mywork/zkclient-0.2-SNAPSHOT.jar -Dpackaging=jar -DgeneratePom=true
mvn install:install-file -DgroupId=common.toolkit -DartifactId=common-toolkit -Dversion=0.0.6-SNAPSHOT -Dfile=D:/mywork/common-toolkit-0.0.6-SNAPSHOT.jar -Dpackaging=jar -DgeneratePom=true





        