node
{
    stage('Commit')
    {
        echo "This is Code Download from GIT Project Repository.................."
    }

      stage('Build') {
            steps {
               
                sh 'mvn clean install'
    }
      }
    stage('Test')
    {
       sh 'mvn clean test'
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
