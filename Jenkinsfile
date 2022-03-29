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
        sh 'npm install && sleep 10 && cat /home/ec2-user/password.txt | docker login --username prabha038 --password-stdin && docker build -t prabha038/nodeapp . && sleep 5 && docker push prabha038/nodeapp:latest'
      }

  }
}
}
