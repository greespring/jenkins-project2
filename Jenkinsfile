pipeline{
    agent any
    stages{
        stage('git-clone'){
            steps{
                checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/greespring/jenkins-project2']])
            }
        }
    }
}
