pipeline {
    agent any
    

    stages {
        stage('Git') {
            steps {
              
                
                echo 'Getting Backend project from Git';
                 git branch:'main',
                 url: 'https://github.com/AbdelhamidAtallah/testhttpd.git'
                sh 'cp /var/lib/jenkins/jobs/testphp/workspace/httpdtest.com/index.html /var/www/httpdtest.com/index.html' 
       
                
           }
        }
}
}
