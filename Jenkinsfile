pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                // Checkout your source code from version control system
                git 'https://github.com/Dileepv7878/GIT_Exampale.git'

                // Run Maven build
                sh 'mvn clean install'
            }
        }
    }
}
