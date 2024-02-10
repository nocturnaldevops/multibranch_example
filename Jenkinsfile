pipeline
{
    agent any
    stages
    {
        stage("get_the_code")
        {
            steps
            {
                git branch: 'main', url: 'https://github.com/nocturnaldevops/multibranch_example.git'
            }
        }
        stage("run_thescript")
        {
            steps
            {
                sh 'sh script1.sh'
            }
            
        }
    }
}
