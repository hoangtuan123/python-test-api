node {
    def app

    stage('Clone repository') {
        checkout scm
    }

    stage('docker-compose down') {
        sh 'docker-compose up --build -d'
    }

    stage('docker-compose up') {
        sh 'docker-compose up --build -d'
    }
}
