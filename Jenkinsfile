pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            echo 'first build step comments'
          }
        }

        stage('Sub build stage') {
          steps {
            echo 'sub build stage comments'
          }
        }

      }
    }

    stage('deploy') {
      steps {
        echo 'Deploy comments on production'
      }
    }

  }
}