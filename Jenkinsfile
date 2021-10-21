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
                echo 'Testing application.....'
            }
        }
    }
}
