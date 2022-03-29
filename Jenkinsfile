pipeline {
  agent any
    
  tools {nodejs "Nodejs"}
    
  stages {
        
    stage('Cloning Git') {
      steps {
        git 'https://github.com/prabha38/nodejs.git'
      }
    }
        
    stage('Install dependencies') {
      steps {
        sh 'npm install'
      }
    }
  }
  }
