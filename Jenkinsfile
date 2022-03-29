pipeline {
  agent any
    
  tools {nodejs "NodeJS"}
    
  stages {
        
    stage('Cloning Git') {
      steps {
        git 'https://github.com/prabha38/nodejs.git'
      }
    }
        
    stage('Install dependencies') {
      steps {
        ssh 'npm install'
      }
    }
  }
  }
