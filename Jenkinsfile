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
            sh 'echo "hi how are you?"'
          }
        }

        stage('2A') {
          steps {
            sh 'echo "i am the second option for branch 2"'
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