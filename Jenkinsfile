pipeline {
    node {
        stages {
            stage ('Get the code'){
                checkout scm;
            }
            stage ('Compile the code'){
                python trial1.py
            }
            stage('Unit Test'){
                echo "Unit Test Done"
            }
            stage('Build'){
                echo "Built, Ready for Deployment..."
            }
        }
    }
}
