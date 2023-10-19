pipeline{
    agent{label 'Maven'}

environment {
    PATH = "/opt/apache-maven-3.9.4/bin:$PATH"
}
stages{
 stage("Maven Build"){
    steps {
        sh 'mvn clean install'
    }
 }

 }
}
