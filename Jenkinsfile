pipeline {

  stages {
  node("slavebits"){
    stage("Build") {
       steps {
          // Just print a Hello, Pipeline to the console
          echo "BITS Jenkins Assignment 3"
          // Compile a Java file. This requires JDKconfiguration from Jenkins
          //javac HelloWorld.java
          // Execute the compiled Java binary called HelloWorld. This requires JDK configuration from Jenkins
          //java HelloWorld
          // Executes the Apache Maven commands, clean then package. This requires Apache Maven configuration from Jenkins
          //mvn clean package ./HelloPackage
          // List the files in current directory path by executing a default shell command
          //sh "ls -ltr"
       }
   }
   // And next stages if you want to define further...
   }//running on slave slavebits
 } // End of stages
} // End of pipeline
