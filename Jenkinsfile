pipeline{
    agent any
    stages{
        stage('Build'){
            steps{
                script{
                    sh '''
                    echo " Hello Lakshman"
                    echo " This is a Build Stage"
                    '''
                }
            }
        }
        stage('Test'){
            steps{
                script{
                    sh '''
                    echo " Hello Lakshman"
                    echo " This is a Test Stage"
                    '''
                }
            }
        }
        stage('Deployment'){
        steps{
            scripts{
                sh '''
                echo " Hello Lakshman"
                echo " This is a Deployment Stage "
                '''
            }
        }
        }
    }
}