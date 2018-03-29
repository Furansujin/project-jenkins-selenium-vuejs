pipeline {
  agent any
  stages {
    stage('helloworld') {
      steps {
        echo 'helloworld'
      }
    }
     stage('check tools') {
        sh "node -v"
        sh "npm -v"
    }
  }
}
