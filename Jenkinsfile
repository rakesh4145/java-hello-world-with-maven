pipeline{
    agent any
    stages{
        stage('checkout'){
            steps{
                git branch:'master',url:'https://github.com/rakesh4145/java-hello-world-with-maven.git'
            }
        }
    stages{
        stage('unit testing'){
            steps{
                sh 'mvn test'
            }
        }
    }
}
}
