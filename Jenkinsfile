pipeline
{
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                Running ${env.BUILD_ID} on ${env.JENKINS_URL}
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                Running ${env.BUILD_ID} on ${env.JENKINS_URL}
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
                Running ${env.BUILD_ID} on ${env.JENKINS_URL}
            }
        }
    }
}
