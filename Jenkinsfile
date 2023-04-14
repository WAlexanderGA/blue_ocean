pipeline {
  agent {
    node {
      label 'docker'
    }

  }
  stages {
    stage('Test') {
      parallel {
        stage('Test') {
          steps {
            echo '*testing"'
            echo 'test'
            echo 'testing'
          }
        }

        stage('parallel') {
          steps {
            echo 'parellel'
          }
        }

      }
    }

    stage('build') {
      steps {
        echo 'build'
      }
    }

    stage('clean up') {
      steps {
        echo 'clean up.'
      }
    }

  }
}