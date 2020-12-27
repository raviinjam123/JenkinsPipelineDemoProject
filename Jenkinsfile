node()
{
    stage('Code checkout')
    {
        git credentialsId: 'github_cred', url: 'https://github.com/raviinjam123/JenkinsPipelineDemoProject.git'
    }
    
    stage('compile')
    {
        sh "mvn clean"
    }
    
   /* stage('build')
    {
        sh "mvn clean package"
    }
    stage("install")
    {
       sh "mvn install"
    }
    */
}
