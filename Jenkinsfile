pipeline {
    agent { label 'jdk_17' }
    stages {
        stage {
            steps {
                git url: git@github.com:mounika000/spring-petclinic.git
            }
        }
        stage {
            steps {
                sh 'mvn package'
            }
        }    
    }    
}
