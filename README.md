PRE REQUISITES
-> make sure you have installed the JDK version 9 or above
-> make sure you have installed maven 
-> extract the installed zip or tar folders
-> set the system environment variables ( in the variable value use the file location of the installed maven folder)
-> Edit the path as %Maven_Home%\bin

Open the command prompt / terminal and use the command to build the hello world application:
 " mvn archetype:generate -DgroupId=org.lfs.mavenlearning -DartifactId=mavenlearning -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false "

 once the build is completed , run these commands
     cd Mavenlearning
     mvn clean package 

 the compilation will be started by implementing 
     java -cp target/mavenlearning-1.0-SNAPSHOT.jar org.lfs.mavenlearning.App
