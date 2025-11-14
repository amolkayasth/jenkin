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
                bat "C:\\Users\\amols\\AppData\\Local\\Microsoft\\WindowsApps\\python.exe e.py"

            }
        }
    }
}
