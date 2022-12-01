pipeline{
    agent any
    stages{
        stage('Hello'){
            steps{
                echo 'Hello World'
            }
        }
        stage('Master-only'){

            when{
                branch 'master'
            }
            steps{
                echo 'Auf Master branch'
            }
        }
    }
}