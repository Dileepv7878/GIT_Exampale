pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                // Checkout your source code from version control system
                git 'https://github.com/Dileepv7878/Sample_Groovy.git'

                // Run Maven build
                script {
                    sh 'mvn clean install'
                }
            }
        }
    }
}
