pipeline {
  agent any
  stages {
    stage('say hello') {
      parallel {
        stage('say hello') {
          steps {
            echo 'hello world'
          }
        }

        stage('error') {
          steps {
            sh 'java -version'
          }
        }

      }
    }

  }
}