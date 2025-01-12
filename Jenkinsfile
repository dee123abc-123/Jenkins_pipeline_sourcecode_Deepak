pipeline {
    agent any

    stages {
        stage('installing_tomcat') {
            steps {
                sh "sudo ansible-playbook /etc/ansible/tomcat1.yml"
            }
        }
    }
}
