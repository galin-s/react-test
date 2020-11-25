pipeline {
  agent any
    
  stages {
    stage('Test') {
      steps {
        sh 'npm test'
      }
    }

    stage('Install') {
      steps {
        sh 'npm install'
      }
    }

    stage('Build') {
      steps {
        sh 'npm run  build'
      }
    }

  }
}
