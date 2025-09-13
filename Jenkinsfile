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
                script{
                    sh '''
                    echo " Hello Lakshman"
                    echo " This is a Deployment Stage"
                    '''
                }
            }
        }
        post{
            always{
                echo 'Hello Lasya your Deployment successfully complted'
            }
        }
    }
}