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
        echo 'Building...'
        sh 'rm -rf node_modules/'
        sh 'npm install'
      }
    }
  }
}