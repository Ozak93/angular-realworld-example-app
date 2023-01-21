pipeline {
    agent any
     

  stages {
    stage('Install') {
      steps { 
      
        sh 'npm install'
              sh 'npm audit fix '
               }
 
    }

 

    stage('Build') {
      steps { sh 'ng build' }
    }
  }
}