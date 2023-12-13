pipeline{
    agent any
    stages {
        stage('hotfix') {
            steps {
                sh 'echo "this is hotfix application" '
            }
        }
    stages {
        stage('test1') {
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
