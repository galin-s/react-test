pipeline {
  agent any
    
  tools {nodejs "NodeJS-15.3.0"}
    
  stages {
        
    stage('Git') {
      steps {
        git 'https://github.com/galin-s/react-test'
      }
    }
     
    stage('Deliver') {
      steps {
      sh 'npm run build'
}
    }
  }
}
