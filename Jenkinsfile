pipeline{
    agent any

    stages{
        stage('Build') {
            agent any
            options{
                skipdefaultCheckout()
            }
            steps{
                echo 'Hello World'
            }
        }
    }
}