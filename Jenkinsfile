pipeline
{
    agent any
        stages
        {
            stage('clone')
            {
                steps
                {
                    git branch:'jntuh',url:'https://github.com/ramyabilla2005-bot/Devops1week.demo.git'
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
