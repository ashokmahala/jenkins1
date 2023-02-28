pipeline {
    agent any

    stages {
        stage('Hello1') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Hello2') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Hello3') {
            steps {
                echo 'Hello World'
            }
        }
    }
    post{
        always{
            emailext body: 'summary', replyTo: '1ms21mc010@gmail.com', subject: 'pipelien noti', to: '1ms21mc010@gmail.com'
        }
    }
}
