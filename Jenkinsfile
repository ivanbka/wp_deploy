pipeline {
    agent any

    stages {
        stage("git clone") {
            steps {
                sh "git clone https://github.com/ivanbka/wp_deploy.git"
                sh "ansible-lint -p ./wp_deploy/playbook_roles.yaml"
            }
        }
    }
}