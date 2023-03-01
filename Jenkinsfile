pipeline {
  agent {
    stages {
      stage ("stage1") {
        steps {
          sh "docker cp /mnt/assign/httpd index.html 23Q2:/usr/local/apache2/htdocs/"
        }
      
      }
    }
  }
}
