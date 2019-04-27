pipeline{
    agent none

    stages{
        stage('skipDefaultCheckout'){

            agent any

            options{
                skipDefaultCheckout()
            }

            steps{
                echo "skipDefaultCheckout success"
            }
        }
    }
}
