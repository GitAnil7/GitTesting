pipeline{
    agent any
    stages {
        stage('sprint application') {
            steps {
                sh 'echo "this is sprint" '
            }
        }
    stages {
        stage('test') {
            steps {
                sh 'echo "sprint1 applicaiton" '
            }
        }
    stages {
        stage('deploy application') {
            steps {
                sh 'echo "deploy application" '
            }
        }
    }
}
