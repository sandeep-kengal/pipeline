pipeline {
    agent {label ('master')} {
        docker { image 'nginx:latest' }
    }
    stages {
        stage('Test') {
            steps {
                sh ''' docker run --rm -p 8000:8000 nginx '''
            }
        }
    }
}
