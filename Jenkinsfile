pipeline{
    agent any
    stages{
        stage("Build"){
            steps{
                echo "========executing A========"
                sh 'mvn --version'
            }
           
        }
    }
    post{
        always{
            echo "========always========"
        }
        success{
            echo "========pipeline executed successfully ========"
        }
        failure{
            echo "========pipeline execution failed========"
        }
    }
}
