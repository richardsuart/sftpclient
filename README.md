# sftpclient

Simple sftp file upload service. Only password login is supported.

Sends given file to an ssh server to given path. If file exists, it will overwrite. 


To compile and run project,

1- mvn package

2- cd target

3- java -jar sftpclient-0.0.1-SNAPSHOT.jar

And project listens http://localhost:8080/file/upload

You can check required parameters from controller file.
