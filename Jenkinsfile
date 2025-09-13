pipeline{
    agent any
    enviornment{
        PROJECT='Lasya-InfoTech'
        component='Dev'
    }
    stages{
        stage('Build'){
            steps{
                script{
                    sh '''
                    echo " Hello Lakshmana Rao"
                    echo " This is a Build Stage"
                    echo "project:$PROJECT"
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
            script{
                def timestamp= new Date()
                echo 'Deployment completed at ${timestamp}'
            }
        }
        failure{
            script{
                def timestamp = new Date()
                echo  'Deployment is not completed at ${timestamp}'
            }
        }
    }
}
