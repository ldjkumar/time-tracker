node
{
    stage('checkout')
    {
        checkout([$class: 'GitSCM', branches: [[name: '*/master']], extensions: [], userRemoteConfigs: [[credentialsId: 'ad3b35c3-ea29-4465-99ef-85bbe152cd5d', url: 'https://github.com/ldjkumar/time-tracker.git']]])
        def workspace
        workspace = pwd()
    }
    stage('Static code Analisys')
    {
        echo "Static code Analysis"
    }
    stage('Build')
    {
        echo "Build the code here"
    }
    stage('Unit Test')
    {
        echo "Unit Testing"
    }
    stage('Delivery')
    {
        echo "Delivery of code/project"
    }
}
