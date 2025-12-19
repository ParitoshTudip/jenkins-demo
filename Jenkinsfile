pipeline {
  agent any

  stages {

    stage('Checkout code'){
      steps {
        get branch: 'main',
        url: 'https://github.com/ParitoshTudip/jenkins-demo.git'
      }
    }

    stage('Build'){
      steps {
        echo "Building the application...."
      }
    }

    stage('Test'){
      steps {
        echo "Running Tests...."
      }
    }

    stage('Deploy'){
      steps {
        echo "Deploying Application...."
      }
    }
  }
}