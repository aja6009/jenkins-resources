pipeline {
    agent any
    stages {
        stage ('timeout') {
            steps {
                retry(2) {
                    sh 'i was in box of art'
                }
            }
        }
    }
}
