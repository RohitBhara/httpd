pipeline {
    agent any 
    stages {
        stage ("docker-deploy") {
            
            steps {
                sh "git checkout RO1"
                sh "docker run -itdp 92:80 --name RO1 httpd"
            
                sh "docker cp /mnt/assign/httpd/index.html test1:/usr/local/apache2/htdocs/"
            }
        }
    }
}
