pipeline {
  agent any
  stages {
    stage('git') {
      parallel {
        stage('git') {
          steps {
            echo 'git'
          }
        }

        stage('verify') {
          steps {
            echo 'verify'
          }
        }

        stage('check') {
          steps {
            echo 'check'
          }
        }

        stage('run') {
          steps {
            echo 'run'
          }
        }

        stage('test') {
          steps {
            echo 'test'
          }
        }

      }
    }

    stage('deploy') {
      steps {
        echo 'deploy'
      }
    }

  }
}