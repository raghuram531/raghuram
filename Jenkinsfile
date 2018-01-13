node {
    stage ('Get the code'){
        checkout scm;
    }
    stage ('Compile the code'){
        bat 'C:\\Users\\ragvadla\\PycharmProjects\\venv\\Scripts\\python trial2.py'
    }
    stage('Unit Test'){
        echo "Unit Test Done"
    }
    stage('Build'){
        echo "Built, Ready for Deployment..."
    }
}
