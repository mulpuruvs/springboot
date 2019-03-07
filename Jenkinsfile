pipeline {

  agent any
  
  tools {    
    maven 'maven3'
    jdk 'java8'    
  }
  
  stages {
  
    stage('Build') {
      steps {
        sh "mvn -B -DskipTests clean package"
      }      
    }  
  
  }

}
