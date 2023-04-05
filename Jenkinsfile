pipeline {
  agent any 
  
  stages {
    stage ('GIT Checkout') {
      steps {
        git branch: 'main' , url '  '
        
        
        
          }
    }
    
    stage ('UNIT TESTING') {
      steps {
        sh 'mvn test' 
      }
      
        stage ('INTEGRATION TESTING') {
      steps {
        sh 'mvn verify -DskipUnitTests' 
      }
          
          stage ('BUILD') {
      steps {
        sh 'mvn clean install' 
      }
    
  }
}
