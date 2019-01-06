Pipeline{
    agent{
        docker{
            image 'maven:3-Alpine'
            args '-v /root/.m2:/root/.m2'
        }
    }
    stage('Build'){
        steps{
            sh 'mvn -B -DskipTests clean package'
        }
    }
}