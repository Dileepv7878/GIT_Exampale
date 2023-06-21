node
{
    stage('Commit')
    {
        echo "This is Code Download from GIT Project Repository.................."
    }

      stage('Build') {
            steps {
               
                git 'https://github.com/Dileepv7878/Sample_Groovy.git'
                sh 'mvn clean install'
    }
    stage('Test')
    {
        echo "This is Test project Implementation using Selenium................."
    }
    stage('Release')
    {
        echo "This is Delivery using Dcoker......................................"
    }
    stage('Monitor')
    {
        echo "This is Application Logs Monitorinig using tool Splunk............."
    }
}
