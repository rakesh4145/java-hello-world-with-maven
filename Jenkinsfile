pipeline {
    agent any
        
    stages{
        stage('checkout'){
            steps{
                git branch:'master',url:'https://github.com/rakesh4145/java-hello-world-with-maven.git'
            }
        }
    stage('unit testing'){
            steps{
                sh 'mvn test'
            }
        }
     stage('integration testing'){
            steps{
                sh 'mvn verify -dskipUnitTests'
            }
        }
    }
}  
