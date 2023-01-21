pipeline {
    agent any
     

  stages {
    stage('Install') {
      steps { sh 'npm install' }
      steps {sh 'npm audit fix --force'}
    }

 

    stage('Build') {
      steps { sh 'ng build' }
    }
  }
}