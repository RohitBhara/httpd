pipeline {
    agent any 
    stages {
        stage ("docker-deploy") {
            
            steps {
                
                sh "docker run -itdp 91:80 --name RO2 httpd"
            
                sh "docker cp /mnt/assign/httpd/index.html test1:/usr/local/apache2/htdocs/"
            }
        }
    }
}
