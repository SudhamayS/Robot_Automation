pipeline
{
    agent any
    parameters
    {
        choice(name: 'Branch', choices: ['main', 'Feature_1', 'Feature_2'])
    }

    stages
    {
        stage("test")
        {
            steps
            {
                script
                {
                    if (params.Branch == 'Feature_1')
                    {
                        echo 'Testing application Feature_1.....'                 
                    }
                    else
                    {
                        echo 'Testing application ${params.Branch}..........'
                    }                
                }
            } 
        }
    }
}
