pipeline {
    agent any
    

    stages {
        stage('Git') {
            steps {
                sh 'cd /var/www/httpdtest.com/'
                
                echo 'Getting Backend project from Git';
                 git branch:'main',
                 url: 'https://github.com/AbdelhamidAtallah/testhttpd.git'
       
                
           }
        }
}
}
