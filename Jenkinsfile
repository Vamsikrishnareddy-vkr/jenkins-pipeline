pipeline {
    agent any

    stages {
        stage('Clone Repo') {
            steps {
                echo '✅ Repo already cloned by Jenkins'
            }
        }

        stage('Build') {
            steps {
                echo '🛠️ Building the project...'
                sh 'ls -l'
            }
        }

        stage('Deploy') {
            steps {
                echo '🚀 Deployment done!'
            }
        }
    }
}
