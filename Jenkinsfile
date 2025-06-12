pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                script {
                    sh 'pip install pandas'
                    sh 'python data_analysis.py'
                }
            }
        }
    }
}