pipeline {

  options {
    ansiColor('xterm')
  }

  agent {
    kubernetes {
      yamlFile 'builder.yaml'
    }
  }
  
  stages {
    stage('Demo') {
      step {
        sh 'echo Testing Demo stage'
      
      }
    }
  
  }
}
