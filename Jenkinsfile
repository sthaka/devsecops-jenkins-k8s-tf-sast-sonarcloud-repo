pipeline {
  agent any
  tools { 
        maven 'Maven_3_5_2'  
    }  
  stages{
    stage(complile){
      steps{
        sh 'mvn clean verify'
      }
    }
  }
  
}
