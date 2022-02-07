Jenkinsfile (Declarative Pipeline)
node {
    scm checkout
    https://github.com/rwheeler-7864/practice-tools.git
}

pipeline {
    agent any

    stages {
        stage('Launcher Project') {
            steps {
                echo "running.. ${env.BUILD_ID} on ${env.JENKINS_URL}"
            }
        }
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
