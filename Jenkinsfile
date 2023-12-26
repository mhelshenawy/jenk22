pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
        
                git 'https://github.com/mhelshenawy/jenk22.git'
            }
        }

        stage('Execute Bash Script') {
            steps {
               
                sh 'bash ls_script.sh'
            }
        }
    }
}
