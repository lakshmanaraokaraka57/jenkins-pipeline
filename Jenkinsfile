pipeline{
    agent any
    stages{
        stage('Build'){
            steps{
                script{
                    sh '''
                    echo " Hello Lakshmana Rao"
                    echo " This is a Build Stage"
                    '''
                }
            }
        }
        stage('Test'){
            steps{
                script{
                    sh '''
                    echo " Hello Lakshmana Rao"
                    echo " This is a Test Stage"
                    '''
                }
            }
        }
        stage('Deployment'){
            steps{
                script{
                    sh '''
                    echo " Hello Lakshmana Rao"
                    echo " This is a Deployment Stage"
                    '''
                }
            }
        }
    }
        post{
            success{
                echo " Deployment is Successfully completed"
            }
            failure{
                echo " Deployment is not Successfully completed "
            }
        }
}