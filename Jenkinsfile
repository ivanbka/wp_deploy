pipeline {
    agent any

    stages {
        stage("git clone") {
            steps {
                sh "cd /home/ubuntu"
                sh "git clone https://github.com/ivanbka/wp_deploy.git"
            }
        }
    }
}