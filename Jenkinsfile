pipeline {
  agent any
  stages {
    stage('Stage1') {
      parallel {
        stage('Stage1') {
          steps {
            echo 'Hello, Today we are learning  Blue Ocean'
            echo 'IBM_WebAppDevelopment1 & Status is Successfull'
            echo 'hi all, we are learning blueocean in jenkins'
          }
        }

        stage('Stage 3') {
          steps {
            echo 'This is saturday'
          }
        }

      }
    }

    stage('Stage 2') {
      parallel {
        stage('Stage 2') {
          steps {
            echo 'Hello, This is stage 2'
          }
        }

        stage('') {
          steps {
            echo 'github in blueocean'
          }
        }

      }
    }

  }
}