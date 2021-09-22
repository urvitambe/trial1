pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        git(url: 'https://github.com/urvitambe/trial1.git', branch: 'main')
        echo 'GITHUB Checkout'
      }
    }

    stage('Test') {
      steps {
        echo 'test done'
      }
    }

    stage('Test2') {
      steps {
        git(url: 'https://github.com/urvitambe/trial1.git', branch: 'master')
        bat 'cd C:\\Users\\URVI\\OneDrive\\Desktop\\demo'
      }
    }

  }
}