pipeline {
    agent any

    stages {
        stage('01.Clone Repo') {
            steps {
                echo "Git Cloning"
                git branch: 'main', credentialsId: 'abcd', url: 'https://github.com/shubhamdhole97/msexcell.git'
            }
        }
    }
}