pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/Ashwini2593/linux-bash-scripting.git'
            }
        }
        stage('Run Script') {
            steps {
                sh 'chmod +x system_admin.sh'
                sh './system_admin.sh'
            }
        }
    }
}
