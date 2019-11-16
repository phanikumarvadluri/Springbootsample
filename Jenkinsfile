node{
stage('SCM checkout')
{
def mvnHome= tool name: 'Maven', type: 'maven'
git 'https://github.com/phanikumarvadluri/Springbootsample/'
}
stage('Compile Package')
{
bat 'mvn package'
}
}
