pipeline {
    
    agent any
    stages {
        stage('Build') {
            steps {
                // Get some code from a GitHub repository
                git 'https://github.com/marutibhosale/ansible-jenkins-ecs.git'

            }

        }
        stage('Deliver') {
            steps {
                sh 'ansible-playbook ansible.yaml'
            }
        }
    }
}
