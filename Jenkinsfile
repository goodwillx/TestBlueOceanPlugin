pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'build copeted'
      }
    }

    stage('Test stage') {
      parallel {
        stage('test') {
          steps {
            echo 'running test 1'
          }
        }

        stage('test1') {
          steps {
            echo 'running test2'
          }
        }

      }
    }

    stage('deploy ') {
      steps {
        echo 'deployment copleted'
      }
    }

  }
}