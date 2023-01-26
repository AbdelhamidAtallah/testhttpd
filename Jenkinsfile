pipeline {
    agent any
    

    stages {
        stage('Git') {
            steps {
                sh 'cd /var/www/testhttpd'
                echo 'Getting Backend project from Git';
                 git branch:'main',
                 url: 'https://github.com/AbdelhamidAtallah/testhttpd.git'
                
           }
        }
}
}
