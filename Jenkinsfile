pipeline {
    agent {
        docker {
            image 'openjdk:11'  // This will use official Java 11 Docker image
        }
    }
    
    stages {
        stage('Compile') {
            steps {
                sh 'javac HelloWorld.java'
            }
        }
        
        stage('Run') {
            steps {
                sh 'java HelloWorld'
            }
        }
    }
}
