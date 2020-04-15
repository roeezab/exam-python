    node {
        stage('Checkout') { 
            git 'https://github.com/roeezab/exam-python.git'
        }
        
        stage('Build Docker Image'){
            customImage = docker.build('roeezab/exam-python')
        }
        
        stage('Run Tests'){
            customImage.inside() {
                sh "py.test"
            }
        }
        
        stage('Upload to Docker Hub'){
            docker.withRegistry('','dockerhub') {
                customImage.push()
            }
        }
}
