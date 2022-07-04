pipeline {
    agent any

    stages {
        stage("git clone") {
            steps {
                sh '''
                cd /home/jenkins
                git clone https://github.com/ivanbka/wp_deploy.git || true
                ansible-lint -p /home/jenkins/wp_deploy/playbook_roles.yaml || true
                yamllint /home/jenkins/wp_deploy/playbook_roles.yaml || true
                echo "smth 1"
                '''
            }
        }
    }
}
