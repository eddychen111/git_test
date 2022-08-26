pipeline {
  agent any
  stages {
    stage('stage1') {
      parallel {
        stage('stage1') {
          agent any
          steps {
            sh 'echo "hello"'
          }
        }

        stage('') {
          steps {
            git(url: 'https://github.com/eddychen111/git_test.git', branch: 'master', changelog: true, credentialsId: '0')
          }
        }

      }
    }

  }
  environment {
    env1 = 'value1'
  }
}