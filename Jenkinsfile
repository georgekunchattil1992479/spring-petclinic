pipeline {
    agent {label 'master'}
    tools {
        maven 'M3'
    }
    stages {
        stage ('Checkout') {
            steps {
                git 'https://github.com/georgekunchattil1992479/spring-petclinic.git'
            }
        }
    }
}
