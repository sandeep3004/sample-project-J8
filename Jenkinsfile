
node() 
{
    stage('Git')
    {
        echo "Checkout from Github"
    }
    
    stage('Code Audit')
    {
        parallel (
            "JUnit" : { 
                     
                      },
            "Sonar" : { 
                      
                      }
                )
    }
    
    stage('Build')
    {
      echo "Building war"
      
    }
    stage('Upload Artifacts')
    {
        echo "Checkout from Github"
    }
    stage('Deploy_to_Dev')
    {
        echo "Deploying artifacts "
    }
    stage('Testing')
    {
        echo "Running Functional Tests"

    }
}

