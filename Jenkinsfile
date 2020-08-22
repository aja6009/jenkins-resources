pipeline {
    agent any
    stages {
        stage('deploy') {
            steps {
                retry(3) {
                    echo "hello"
                }
                timeout(time: 3, unit:'SECONDS') {
                    sh 'sleep 5'
                }
            }
        }
    }
}
