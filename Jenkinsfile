pipeline {
  agent any
  stages {
    stage('HelloJenkins') {
      steps {
        sh 'ls -la'
        echo 'Hello Jenkins'
      }
    }
    stage('findHome') {
      steps {
        sh 'pwd'
        sh 'ls -la'
        sh 'cd /'
        sh '''pwd
ls -la'''
      }
    }
  }
}