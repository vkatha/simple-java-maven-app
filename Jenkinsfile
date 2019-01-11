pipeline {
    agent{
        label 'dockerserver'
    }
    stages{
        stage('build'){
            agent{
                docker{
                label 'dockerserver'
                image 'node:6-alpine'
                }
            }
            steps{
                sh ' echo " installing node"'
            }
        }
    }


}