pipeline {
  agent any
  stages {
    stage('Compile') {
      steps{
        bat 'mvn clean compile'
      }
    }

    stage('UnitTest') {
      steps{
        bat 'mvn clean test'
      }
    }
    
    stage('Package') {
      steps{
        bat 'mvn package'
     }
    }
  }
}
