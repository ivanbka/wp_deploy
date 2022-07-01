pipeline {
    agent any

    stages {
        stage("git clone") {
            steps {
                sh "ansible-lint -p ./wp_deploy/playbook_roles.yaml"
            }
        }
    }
}