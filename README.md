pipeline {
    
    stages {
       
        stage('deploy') {
            steps {
                echo 'this is dev branch'
            }
        }
    }
}
        
