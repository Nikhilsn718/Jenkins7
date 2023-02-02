pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'This is bulid'
            }
        }
         stage('Test') {
            steps {
                echo 'This is test'
            }
        }
        stage('Deploy') {
            steps {
                echo 'This is Deploy'
            }
        }
        stage('integrate') {
            steps {
                echo 'this is for integration' 
            }
                
            }
        }
    
     post {
        always {
         emailext body: 'Built: Jenkinsfile_pipeline', subject: 'Jenkinsfile_pipeline', to: 'harnilakshmi111@gmail.com'
        }
    }
}
