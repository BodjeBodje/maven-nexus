How Install java and Maven packages

sudo apt update                       
sudo apt install openjdk-17-jdk -y
sudo apt install openjdk-17-jre -y
sudo apt install maven -y
java --version 
mvn --version 
mkdir class24-maven
cd class24-maven/
nano hello.java
mv hello.java Hello.java
javac Hello.java 
javac Hello.java 
 java Hello Hello.java 

nana Creetings.java
mv Creetings.java Creeter.java
cat Creeter.java 

jar cfe sample.jar Hello .
mkdir out
java -jar sample.jar 

echo "ghjfjhfddifjf">>Hello.java
javac Hello.java 
mvn --version 

mvn archetype:generate (package has install when you have more maven project )
	Define value for property 'groupId': com.class24.mvn
	Define value for property 'artifactId': class24App
 cd class24App/
 mvn compile
 mvn test
 mvn package
 delete target package in project
 mvn cleaan (rmove target folder)
  
If want to go up your local repository
 cd .m2

 Dependencies from project class24App	 pom.xml
Maven central 	https://mvnrepository.com/repos/central
<img width="1256" height="1628" alt="image" src="https://github.com/user-attachments/assets/7344fdac-ade3-484e-8790-49a2851429c9" />
