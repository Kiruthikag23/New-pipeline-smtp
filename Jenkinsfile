pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('email notification') {
            mail bcc: '', body: '', cc: '', from: '', replyTo: '', subject: 'This is pipeline build message', to: 'kiruthikag23@gmail.com'
            }
        }
    }
