pipeline {
    agent any
     

  stages {
    stage('Install') {
      steps { 
        sh 'nvm use 18'
        sh 'npm install'
              sh 'npm audit fix --force'
               }
 
    }

 

    stage('Build') {
      steps { sh 'ng build' }
    }
  }
}