pipeline{
    agent any
    stages{
        stage('build'){
            steps{
                echo "I am in delcerative pipeline"
            }
        }
        stage('Test'){
            steps{
            git branch: 'main', credentialsId: 'Github', url: 'https://github.com/S-2648/Dev_Public'
            }
        }
    }
    
}
