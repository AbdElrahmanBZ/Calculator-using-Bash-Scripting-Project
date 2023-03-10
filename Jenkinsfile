pipeline {
    agent any

    stages {
        stage('pipeline test2') {
            steps {
                echo 'built '
                sh """ 
                    echo "hello from prod"
                """
            }
        }
    }
}
