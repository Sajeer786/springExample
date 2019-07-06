pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh ' sudo yum update -y'
      }
    }
    stage('Test') {
      steps {
        sh 'sudo yum innstall httpd -y '
      }
    }
    stage('Deploy') {
      steps {
        sh 'sudo mkdir /var/www/html/tc'
      }
    }
    stage('report') {
      steps {
        echo "Congratulations, Your Build Pipeline has executed successfully"
      }
    }
  }
}
