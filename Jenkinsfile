pipeline {
    agent any
    stages {
        stage('MainBuild') {
            steps {
                sh 'echo "Succesful Build Complete"'
                sh '''
                    echo "Multiline shell steps"
                    echo "Multiline complete"
                '''
            }
        }
    }
}