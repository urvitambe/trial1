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
        sh '''rows=4
for((i=1; i<=rows; i++))
do
  for((j=1; j<=i; j++))
  do
    echo -n "* "
  done
  echo
done
'''
      }
    }

  }
}