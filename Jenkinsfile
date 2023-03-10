pipeline {
    agent any

    stages {
        stage('pipeline test1') {
            steps {
                sh 'ls '
            }
        }
        stage('pipeline test2') {
            steps {
                echo 'built '
                sh """ 
                    echo "hello from release"
                """
            }
        }
    }
}
