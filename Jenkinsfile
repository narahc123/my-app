pipeline {
    agent {docker {image 'maven:3.3.3' } }
   
    stages {
        stage('build') { 
            steps {
                sh "mvn --version"
            }
        }
        stage('clean') { 
            steps {
                sh "mvn clean"
            }
        }
        stage('Test') { 
            steps {
                sh "mvn test"
            }
        }
        stage('Deploy') { 
            steps {
                sh "mvn package"
            }
        }
    }
}
