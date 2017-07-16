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
        runPythonScript 'al/jenkins/batman.py'
      }
    }
    stage('release') {
      steps {
        sh 'echo "Releasing"'
      }
    }
  }
}
