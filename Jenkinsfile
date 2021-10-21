pipeline
{
    agent any
    parameters
    {
        choice(name: 'Branch', choicess: ['main', 'Feature_1', 'Feature_2'])
    }

    stages
    {
        stage("test")
        {
            steps
            {
                script
                {
                    if (param.Branch == 'Feature_1')
                    {
                        echo 'Testing application Feature_1.....'                 
                    }
                    else
                    {
                        echo 'Testing application ${Param.Branch}..........'
                    }                
                }
            } 
        }
    }
}
