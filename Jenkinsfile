pipeline {
    agent any 
    stages {
        stage ("docker-deploy") {
            
            steps {
                sh "git checkout RO3"
                sh "docker run -itdp 8080:80 --name RO3 httpd"
            
                sh "docker cp /mnt/assign/httpd/index.html test1:/usr/local/apache2/htdocs/"
            }
        }
    }
}
