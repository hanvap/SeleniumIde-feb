pipeline {  
    agent any  
    stages {  
        stage("Buid") {  
            steps {  
                bat 'dotnet build'  
            }  
        }
         
        stage("Tests") {  
            steps {  
                bat 'dotnet test'  
            }  
        }  
    }  
}