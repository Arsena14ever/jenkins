pipeline {
  agent any
  stages {
    stage('test') {
      parallel {
        stage('test') {
          steps {
            echo 'helloworld'
          }
        }

        stage('maven') {
          steps {
            sh 'mvn -version'
          }
        }

      }
    }

  }
}