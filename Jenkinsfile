pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        catchError() {
          sh 'echo "Hello"'
        }

      }
    }
  }
}