pipeline {
    agent any 

    stages {
        stage('scm') {
            steps {
                echo 'my main branch'
            }
        }
     }
  } 
