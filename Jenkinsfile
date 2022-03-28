pipeline {
  agent any
    
  tools {nodejs "NodeJS"}
    
  stages {
        
    stage('Cloning Git') {
      steps {
        git 'https://github.com/NIK8H/nodejsk8s.git'
      }
    }
        
    stage('Install dependencies') {
      steps {
        bat 'npm install'
      }
    }
  }
  }
