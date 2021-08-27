pipeline{
    agent any
    tools {
        terraform 'terraform'
    }
    stages{
        stage('Checkout from Git') {
            steps {
                git branch: 'main', url: 'https://github.com/chucklapress/simplest-terraform'
            }
            
        }
        stage('Terraform Init') {
            steps {
                sh 'terraform init'
            }
            
        }
        stage('Terraform fmt') {
            steps {
                sh 'terraform fmt'
            }
        }
        stage('Terraform plan') {
            steps {
                sh 'terraform plan'
            }
        }
        stage('Terraform apply') {
            steps {
                sh 'terraform apply --auto-approve'
            }
        }
    }
    post {
    always {
        script {
            deleteDir()
        }
    }
  }
}
