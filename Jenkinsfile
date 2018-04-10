pipeline {
  agent {
    docker {
      image 'node'
      args '-u root'
    }
    
  }
  stages {
    stage('build') {
      steps {
        echo 'Building....'
        sh 'sudo npm install'
      }
    }
  }
}