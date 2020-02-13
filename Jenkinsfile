pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'ping -c 192.168.0.19'
      }
    }

    stage('test') {
      steps {
        sh 'ping -c  2 localhost'
      }
    }

    stage('deploy') {
      steps {
        sh 'ping -c 4 localhost'
      }
    }

  }
}