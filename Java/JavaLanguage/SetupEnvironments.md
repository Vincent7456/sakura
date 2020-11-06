
- download the jdk from <a href="http://jdk.java.net/15/" target="_blank">openJDK</a>.
- use `tar zxvf jdk15.tar.gz` to unzip jdk file.
- copy the unzipped folder to **/Library/Java/JavaVirtualMachines**.
- edit ~/.bash_profile.
- run `source ~/.bash_profile`.

```
# java
JAVA_HOME=/Library/Java/JavaVirtualMachines/jdk-15.0.1.jdk/Contents/Home

# tomcat
CATALINA_HOME=/Users/${USER_NAME}/Dev/apache-tomcat-9.0.33

# maven
MAVEN_HOME=/Users/${USER_NAME}/Dev/apache-maven-3.6.3

PATH=$PATH:$JAVA_HOME/bin:$MAVEN_HOME/bin:.

export JAVA_HOME
export CATALINA_HOME
export MAVEN_HOME
export PATH
```
