pipeline {
  agent any
  stages {
    stage('foo') {
      parallel {
        stage('foo') {
          steps {
            echo 'hello'
            echo 'world'
          }
        }
        stage('bar') {
          steps {
            echo 'fads'
          }
        }
        stage('adfa') {
          steps {
            echo 'asdfa'
          }
        }
      }
    }
  }
}