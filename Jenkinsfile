pipeline {
  agent any
  
  stages {
    stage('Buil') {
  steps {
    bat 'mvn clean package'
  }
}

stage('Test') {
      steps {
        bat 'mvn test'
      }
    }

  }
}