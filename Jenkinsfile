pipeline {
    agent any

    stages {
        
        stage("version") {
            
            steps {
                sh 'pyhton3 --version'
                
            }
        }    
        stage("script") {
            
            steps {
                sh 'python3 main.py'
            }
        
        }
    }    
}
