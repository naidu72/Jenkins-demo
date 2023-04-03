pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            echo 'This is my first build'
          }
        }

        stage('test') {
          steps {
            echo 'This is testing'
          }
        }

      }
    }

    stage('deploy') {
      steps {
        echo 'deployment is completed  '
      }
    }

  }
}