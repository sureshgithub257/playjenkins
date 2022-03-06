pipeline {

  options {
    ansiColor('xterm')
  }

  agent {
    kubernetes {
      yamlFile 'builder.yaml'
    }
  }
}
