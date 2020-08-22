pipeline {
    agent any {
        stages {
            stage('Dploy') {
                steps {
                    retry(3) {
                        echo "hello"
                    }
                    timeout(time: 3, unit: 'SECONDS')
                        sh 'sleeo 5'
                    }
                }
            }
        }
    }
