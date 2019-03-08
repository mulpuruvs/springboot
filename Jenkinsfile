pipeline {

  agent any
  
  tools {    
    maven 'maven3'
    jdk 'java8'    
  }
  
  stages {
  
    stage('Build') {
      steps {
        bat "mvn -B -DskipTests clean install"
      }      
    }  
  
  }

}
