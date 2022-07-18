pipeline{
    agent { label 'linux' }
    stages{
        stage("git checkout")
        {
            steps{
                    git url: 'https://github.com/akhilesh-007/mavepro.git', branch: 'main'
                 }
          }
stage("maven build"){
steps{
sh "mvn clean package"
}
}
  stage("maven build"){
steps{
sh "mvn clean package"      
    }
}
