pipeline{
    agent any
    tools{
        maven 'localMvn'
    }
    stages{
        stage('Build'){
            steps{
                sh 'mvn clean package'
            }
        }
    }
}