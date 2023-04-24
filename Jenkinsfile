pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                git branch: 'main', url: 'https://github.com/naveenappajigol/naveentest.git' 
            }
        }
        stage('Test') { 
            steps {
                sh 'java -version' 
            }
        }
        stage('Deploy') { 
            steps {
                sh 'jenkins --version' 
            }
        }
    }
}
