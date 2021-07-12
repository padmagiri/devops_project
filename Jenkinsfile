node('master')
{
    stage('Continuous Download')
        {
    git 'https://github.com/padmagiri/devops_project.git'
        }
    stage('Continuous Build')
        {
    sh label: '', script: 'mvn package'
        }

}
