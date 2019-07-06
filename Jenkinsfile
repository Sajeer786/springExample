pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'yum update -y'
      }
    }
    stage('Test') {
      steps {
        sh 'yum innstall httpd -y '
      }
    }
    stage('Deploy') {
      steps {
        sh 'mkdir /var/www/html/tc'
      }
    }
    stage('report') {
      steps {
        echo "Congratulations, Your Build Pipeline has executed successfully"
      }
    }
  }
}
