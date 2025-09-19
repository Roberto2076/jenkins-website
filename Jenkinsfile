pipeline {
    agent any
    stages {
        stage('1. Clonar Código') {
            steps {
                git url: 'https://github.com/Roberto2076/jenkins-website.git', branch: 'main'
            }
        }
        stage('2. Desplegar en Servidor Web') {
            steps {
                sh 'cp -f *.html /var/website-data/'
            }
        }
    }

}
