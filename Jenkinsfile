pipeline {
  agent any
    
  tools {
    nodejs "NodeJS-15.3.0",
    git "galin-git"
  }
    
  stages {
        
    stage('Deliver') {
      steps {
      sh 'npm install'
      }
    }
  }
}
