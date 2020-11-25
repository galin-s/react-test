pipeline {
  agent any
    
  stages {

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

    stage('Install serve') {
      steps {
        sh 'npm install -g serve'
      }
    }
    stage('Serve') {
      steps {
        sh 'serve -s build'
      }
    }
  }
}
