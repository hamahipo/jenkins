pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'echo "Hello World"'
      }
    }

    stage('Test') {
      steps {
        sh 'sudo yum install -y httpd'
      }
    }

  }
}