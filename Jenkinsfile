pipeline {
    agent any
    stages {
        stage('Check folders') {
            steps {
                sh "ls -la"
            }
        }

        stage('Update Cluster Code') {
            steps {
                sh "cp -r test-project/airflow/* test-cluster/"
            }
        }
    }
}
