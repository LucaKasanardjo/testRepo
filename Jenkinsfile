pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                    echo "Building... !!!"
            
            }
        }
        stage('Test') {
            steps {
                    echo "Testing...."
            }
        }
        stage('Deploy') {
            steps {
                script {
                    echo "Deploying...."
                    Boolean bool = fileExists 'lijstmetvrachtwagens.txt'
                    if (bool) {
                        println "De lijst met vrachtwagens is gedownload."
                    } else {
                        println "De lijst met vrachtwagens is niet gedownload."
                    }  
                }
            }
        }
    }
}
