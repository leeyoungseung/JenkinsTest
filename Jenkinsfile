pipeline {
  agent any
  stages {
    stage('HelloJenkins') {
      parallel {
        stage('HelloJenkins') {
          steps {
            sh 'ls -la'
            echo 'Hello Jenkins'
          }
        }
        stage('') {
          steps {
            echo 'Hello Second Hello'
            sh 'ls -la'
          }
        }
      }
    }
    stage('findHome') {
      steps {
        sh 'pwd'
        sh 'ls -la'
        sh '''cd /
pwd
ls -la'''
        sh 'ls -la /'
      }
    }
  }
}