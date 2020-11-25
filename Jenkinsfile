pipeline {
  agent any
    
  tools {nodejs "NodeJS-15.3.0"}
    
  stages {
        
    stage('Git') {
      steps {
        git 'https://github.com/galin-s/react-test'
      }
    }
     
    stage('Build') {
      steps {
        sh 'npm -v'
      }
    }  
    
            
    stage('Test') {
      steps {
        sh 'node test'
      }
    }

    stage('Deliver') {
      sh 'npm run build'
    }
  }
}
