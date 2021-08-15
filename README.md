# JAVA_JDBC_MySQL
Accessing MySQL Database using JDBC<br>
Compilation and Preparation of JAR file<br>

Java Program File Name: NameSearchApp.java<br>
MySQL Driver: mysql-connector-java-5.1.45-bin.jar<br>
Manifest File Name: NameSearchApp.mf<br>
Contents of NameSearchApp.mf<br>
    Manifest-Version: 1.0<br>
    Main-Class: SwingSearchApp<br>
    Class-Path: mysql-connector-java-5.1.45-bin.jar<br>

Note: All the files in the same folder (NameSearchApp.java, NameSearchApp.mf, mysql-connector-java-5.1.45-bin.jar)<br>

Compiling:<br>
    javac NameSearchApp.java<br>
Prparing the JAR file:<br>
    jar cmf NameSearchApp.mf NameSearchApp.jar NameSearchApp.class<br>

Running from Command Line:<br>
    java -jar SwingSearchApp.jar<br>
Running as Desktop App:<br>
    Just double-click on the JAR file.<br>
 
