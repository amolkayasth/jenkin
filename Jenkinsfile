pipeline{
    agent any
    stages {
        stage('checkout code'){
        steps {
            checkout scm
        }
        
        }
        stage('extrack data'){
            steps {
                bat "\"C:\\Program Files\\Python313\\python.exe\" e.py"

            }
        }
    }
}
