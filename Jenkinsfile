pipeline {
    agent any
    environment {
        DB_PASSWORD = credentials('databasepassword')
    }

    stages{
        stage('Accessing Credentials'){
             steps{
                echo "My DB password is: $DB_PASSWORD"
             }
        }

    }
}