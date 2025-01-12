pipeline {
    agent any

    stages {
        stage('Grafana_install') {
            steps {
                sh "sudo ansible-playbook /grafana.yml"
            }
        }
    }
}
