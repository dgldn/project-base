pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'run_base_build.sh'
      }
    }
    stage('Test') {
      steps {
        sh 'run_base_test.sh'
      }
    }
  }
}
