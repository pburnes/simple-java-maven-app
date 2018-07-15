pipeline 
{
agent any

	stages
	{
		stage("Verify AWS is active")
		{
			steps
				{
				echo "run script that checks AWS infrastructure is availabile, VPCs, Subnets, etc."
				}
		}
		stage("Deploy SN onto AMI")
		{
			steps
				{
				echo "run TF of CF script that deploys versioned SN onto AMI"
				}
		}
		stage("Integration Testing")
		{
			steps
				{
				echo "call script that verify that SN is up and running"
				}
				{
				echo "call script to verify login to SN is possible"
				}
		}
	}	
}