pipeline{
    agent{
        label 'ws'
    }
    stages{
        stage('Lint Checks') {
            steps {
                sh "echo ****** Starting Style Checks ****** "
                sh "pip3 install pylint"
                sh "pylint *.py || true"
                sh "echo ****** Style Check are Completed ******"
            }
        }
        stage('Static Code Analysis') {
            steps{
                sh "echo ****** Starting Static Code Analysis ******"
            }   
        }
    }
}