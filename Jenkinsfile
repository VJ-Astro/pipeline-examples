pipeline {
  agent any
  stages {
    stage('testing') {
      parallel {
        stage('testing') {
          steps {
            sh 'echo "Hello world"'
          }
        }

        stage('step1') {
          steps {
            sh 'echo "this is step 1"'
          }
        }

      }
    }

    stage('Final stage') {
      parallel {
        stage('Final stage') {
          steps {
            sh 'echo "this is my last stage"'
          }
        }

        stage('step2') {
          steps {
            sh 'echo "this is step 2"'
          }
        }

      }
    }

  }
}