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
        sh 'sudo npm install -g serve'
      }
    }
    stage('Serve') {
      steps {
        sh 'sudo serve -s build'
      }
    }
  }
}
