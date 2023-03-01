pipeline {
    agent any 
    stages {
        stage ("docker-deploy") {
            
            steps {
                
                sh "docker run -itdp 90:80 --name test1 httpd"
            
                sh "docker cp /mnt/assign/httpd/index.html test1:/usr/local/apache2/htdocs/"
            }
        }
    }
}
