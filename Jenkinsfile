pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        bat(script: 'asd', label: 'Lint', returnStatus: true, returnStdout: true)
        sh 'asdasd'
      }
    }
    stage('Test') {
      steps {
        sleep 5
        bat 'asd'
      }
    }
    stage('Publish') {
      agent any
      steps {
        timeout(time: 5) {
          sleep 8
        }

      }
    }
  }
}