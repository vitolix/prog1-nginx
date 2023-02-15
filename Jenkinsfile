pipeline {
agent {
docker { image 'nginx' }
stages {
stage('Test') {
steps {
sh 'whet https://raw.githubusercontent.com/vitolix/prog1-nginx/main/index.html'
sh 'cp index.html /usr/share/nginx/html/index.html'
}}}}
