pipeline{
    agent any
        stages
        {
            stage('clone')
            {
                   steps
                   {
                         git branch:'main',url:'https://github.com/23p61a0551-art/pipeline.git'
                   }
            }
            stage('build')
            {
                steps
                {
                    sh 'javac Hello.java'
                }
            }
            stage('run')
            {
                steps
                {
                    sh 'java Hello'
                }
            }
        
    }
}
