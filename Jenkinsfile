pipeline {
    agent {
        label 'DemoAgent'
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
    }
    post {
        always {
            echo '20220600208 :)'
        }
    }
}
