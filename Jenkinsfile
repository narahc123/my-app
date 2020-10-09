pipeline {
    agent {docker { image 'openjdk' } }
    stages {
        stage('build') {
            steps {
                sh 'java -version'
                echo "Building Application"         
            }
        }
        stage('test') {
            steps {
                echo "Testing Application"         
            }
        }
        stage('deploy') {
            steps {
                echo "Deploying Application"         
            }
        }
    }
}

 
