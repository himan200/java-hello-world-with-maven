pipeline {
    agent any 
     tools {
         maven 'maven-3.9.11'
     }
     stages {
         stage('Checking MAven version') {
             steps {
                 sh 'mvn -v'
             }
         }
         stage('Pull the git Repa') {
             steps {
                 git branch: 'master', url:'https://github.com/himan200/java-hello-world-with-maven.git'
             }
         }
         
         }
     }
