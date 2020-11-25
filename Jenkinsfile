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
stage('Serve') {

steps {

sh '  npm install -g serve'
}
}
  }
}
