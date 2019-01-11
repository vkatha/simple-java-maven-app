#! /usr/bin -l

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
                #!/usr/bin/env bash -l
                cd /Users/vkatha
                pwd
                docker ps -a
                '''

            }
        }
    }


}