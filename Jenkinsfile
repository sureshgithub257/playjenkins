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
      steps {
        sh 'echo Testing Demo stage'
      
      }
    }
  
  }
}
