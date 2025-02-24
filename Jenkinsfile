pipeline {
  agent any
  stages {
    stage('testing') {
      steps {
        sh 'echo "Hello world"'
      }
    }

    stage('execute how r u') {
      parallel {
        stage('execute how r u') {
          steps {
            echo 'Hi how are you'
          }
        }

        stage('2A') {
          steps {
            echo 'hi i am the branch of second pipeline'
          }
        }

      }
    }

    stage('Final stage') {
      steps {
        sh 'echo "this is my last stage"'
      }
    }

  }
}