pipeline {

  agent any
  node {
    stage('Checkout') {
        checkout scm
       sh "echo 'Run Static Code Analysis'"
    }
  }
     
  stages {
    stage('helloworld') {
      steps {
        echo 'helloworld'
      }
    } 
  }
}
