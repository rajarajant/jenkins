pipeline {
    agent any
 
    stages {
        stage('Welcome') {
            steps {
                echo 'webhook trigger'
            }
        }
    }
 
    post {
        success {
            echo "Pipeline Executed Successfully"
        }
        failure {
            echo "Pipeline Execution Failed"
        }
    }
}
