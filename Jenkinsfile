pipeline {

  agent master
   stages {

    // Build
    stage('Build') {
      agent {
        label 'master'
      }
      steps {
        deleteDir()
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
