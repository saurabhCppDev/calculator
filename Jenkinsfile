pipeline {
  agent any
  stages {
    stage('Compile') {
      steps{
        bat 'mvn clean compile'
      }
    }

    stage('Package') {
      steps{
        bat 'mvn package -DskipTests'
     }
    }
  }
}
