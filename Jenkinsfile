pipeline {
    agent any

    stages {
        stage("install ansible") {
            steps {
                sudo apt update
                sudo apt install ansible
                echo "Ansible was installed"
            }
        }
    }
}