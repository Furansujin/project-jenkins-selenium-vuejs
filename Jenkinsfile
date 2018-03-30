pipeline {
  agent {
    docker {
      image 'node'
      args '-u root'
    }
    
  }
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            echo 'Building...'
            sh 'rm -rf node_modules/'
            sh 'npm install'
          }
        }
        stage('runparal') {
          steps {
            sh 'npm run dev'
          }
        }
      }
    }
  }
}