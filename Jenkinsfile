pipeline
    {
        agent any
        tools
        {
            maven 'mvn'
        }
        stages
        {
            stage('Build')
            {
                steps
                {
                    sh 'mvn clean package'
                }
            }
            stage('test')
            {
                steps
                {
                    sh 'mvn clean test'
                }
            }
        }
    }