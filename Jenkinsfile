pipeline {
  agent any

  stages {

    stage('Checkout code'){
      steps {
        echo "Code checked out by Jenkins SCM"
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