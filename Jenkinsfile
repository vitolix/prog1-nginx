pipeline {
  agent {
    docker { image 'nginx' }
  stages {
    stage('Test') {
      steps {
        sh 'echo daii > /usr/share/nginx/index.html'
      }
    }
  }
}
