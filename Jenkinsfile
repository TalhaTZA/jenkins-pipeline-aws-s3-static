pipeline{
    agent any
    stages{
        stage('Build'){
            steps{
                sh 'echo "Hello World"'
                sh '''
                    echo "Mutli Line Commands"
                    ls -al
                '''
            }
        }
    }
}