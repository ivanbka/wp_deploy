pipeline {
    agent any

    stages {
        stage("install an") {
            steps {
                sh 'sudo apt update'
                sh 'sudo apt install ansible'
                echo "ansible is installed"
            }
        }
    }
}