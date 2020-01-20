pipeline {
    agent { label 'devenv' }
    stages {
        stage('build') {
            steps {
                sh './gradlew build'
            }
        }
    }
}
