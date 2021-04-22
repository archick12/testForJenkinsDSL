pipeline {
    agent {
        docker {
            label 'docker'
            image 'maven:3.5.2-jdk-8-alpine'
            args '-v /root/.m2:/root/.m2'
        }
    }

    stages {
        // The pipeline has the sources already checked out from source control
        stage('Compilation') {
            steps {
                sh 'print "Compilation step"'
            }
        }
    }
}