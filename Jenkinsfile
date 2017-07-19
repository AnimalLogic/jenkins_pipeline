pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'echo "Building"'
      }
    }
    stage('test') {
      steps {
        sh 'echo "running unit tests"'
      }
    }
    stage('release') {
      steps {
        sh 'echo "Releasing"'
      }
    }
  }
}
