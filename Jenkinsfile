pipeline
{
agent any
stages{
stage('Build Apllication'){
steps{
bat 'mvn clean install'
}
}


stage('Deploy Application To Mulesoft CloudHub'){
steps{
bat 'mvn package deploy -DmuleDeploy'
}
}
}
}