# Java Maven First Steps ;)
First steps to install and use maven in a simple project!
### Installing Maven
URL to download:  http://maven.apache.org/download.cgi. 
 - Download the gzip file using the browser *"apache-maven-{version}-bin.tar.gz"*.
 - Unzip file in  the following directory *"/opt/maven"*.
 > tar xzvf apache-maven-3.5.2-bin.tar.gz 
 - Add the bin folder to OS Path *"/etc/profile.d"* (maybe need reboot)
 > **/etc/profile.d:**
   *MAVEN_HOME=/opt/maven/apache-maven-3.5.2*
   *PATH=$PATH:$HOME/bin:$MAVEN_HOME/bin*
   *export MAVEN_HOME*
   *export PATH*
- Then you are be able to test
> mvn -v
