pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        sh 'sh "ls"'
      }
    }

  }
  environment {
    aaa = '"""${sh(script: "date +\'%Y-%m-%d_%H-%M-%S\'", returnStdout: true).trim()}"""'
  }
}