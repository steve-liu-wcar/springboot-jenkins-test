pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'echo "this is ${steve}"'
      }
    }

  }
  environment {
    steve = '111'
  }
}