pipeline {
  agent {
    stages {
      stage ("stage1") {
        steps {
          sh "docker cp /mnt/assign/httpd index.html 23Q3:/usr/local/apache2/htdocs/"
        }
      
      }
    }
  }
}
