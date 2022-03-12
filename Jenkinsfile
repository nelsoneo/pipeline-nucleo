pipeline {
  agent any
  stages {
    stage('start') {
      parallel {
        stage('start') {
          steps {
            echo 'hello'
          }
        }

        stage('firststep') {
          steps {
            echo 'nelson'
          }
        }

        stage('new') {
          steps {
            build 'new'
          }
        }

      }
    }

    stage('end') {
      steps {
        echo 'end'
      }
    }

  }
}