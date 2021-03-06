java-notes
==========

### JVM (Java Virtual Machine)

+ `Sun Classic`
+ `Exact VM`
+ `HotSpot`
+ `JRockit`
+ `J9`
+ `Harmony`
+ `Azul VM`
+ `Zulu`
+ `BEA Liquid VM`

http://rednaxelafx.iteye.com/blog/362738

Java Bytecode Instruction: http://en.wikipedia.org/wiki/Java_bytecode_instruction_listings

JVM note book: https://code.google.com/p/jvmnotebook/

GC: http://www.cs.kent.ac.uk/people/staff/rej/gc.html

find . -name '*.java' -print > java.list
javac -d classes @java.list

find . -name '*.class' -print > classes.list
jar cf my.jar @classes.list

jstat -J-Djstat.showUnsupported=true -snap <pid>

-XX:+UnlockDiagnosticVMOptions -XX:+LogCompilation
\>\>\> `hotspot.log`

http://jinwoohwang.com/index.html

虚拟JUG：http://www.youtube.com/user/virtualJUG?feature=watch

### Java Performance
http://www.javaperformancetuning.com/ 

- Java不慢
- 反射不慢
- 异常不慢 

### Java Concurrent
1. http://sourceforge.net/projects/javaconcurrenta/
2. http://gee.cs.oswego.edu/dl/concurrency-interest/jsr166-slides.pdf 

### 参考书籍

- 《深入Java虚拟机(原书第2版)》 	http://book.douban.com/subject/1138768/
- 《深入理解Java虚拟机》 	http://book.douban.com/subject/6522893/
- 《Effective Java 第二版 中文版》 	http://book.douban.com/subject/3360807/
