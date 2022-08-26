pipeline {
  agent any
  stages {
    stage('stage1') {
      agent any
      steps {
        sh 'echo "hello"'
      }
    }

  }
  environment {
    env1 = 'value1'
  }
}