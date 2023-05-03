pipeline{
    agent any
    stages{
        stage('checkout'){
            steps{
                checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/greespring/jenkins-project2']])
                stage('hello-world'){
                    steps{
                        echo "hello world"
                    }
                }
            }
        }
    }
} 
