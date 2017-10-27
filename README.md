# j9tutorial
Java 9 Tutorial


cd first-module
javac -d module-out src/com.ror.hello/module-info.java src/com.ror.hello/com/ror/hello/MyMain.java
java --module-path module-out -m com.ror.hello/com.ror.hello.MyMain

