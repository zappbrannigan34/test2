pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        sh '''env
ls -lah'''
      }
    }
  }
  environment {
    test = 'test'
  }
}