pipeline{
    agent any
    stages{
        stage('checkout'){
            steps{
                sh git-clone
                stage('hello-world'){
                    steps{
                        echo "hello world"
                    }
                }
            }
        }
    }
} 
