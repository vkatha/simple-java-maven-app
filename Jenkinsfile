pipeline {
    agent{
        label 'master'
    }
    stages{
        stage('build'){
        agent{
            label 'master'
        }
            steps{
                sh ' echo " running docker command" '
                sh '''
                cd /Users/vkatha
                pwd
                docker ps -a
                '''

            }
        }
    }


}