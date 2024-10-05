pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                sh '/Users/yash/HelloWorld/gradlew check'
            }
        }
    }
    post {
        always {
            junit '/Users/yash/HelloWorld/app/build/reports/**/*.xml'
        }
    }
}
