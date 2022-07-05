pipeline{
    agent any
    stages{
        stage('build'){
            step{
                echo "I am in delcerative pipeline"
            }
        }
        stage('Test'){
            step{
            git branch: 'main', credentialsId: 'Github', url: 'https://github.com/S-2648/Dev_Public'
            }
        }
    }
    
}
