pipeline {
    agent any

    stages {
        stage("My-Pipeline") {
            steps {
                ansible-lint -p playbook_roles.yaml
            }
        }
    }
}