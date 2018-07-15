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
		}
		stage("Deploy SN onto AMI")
		{
			steps
				{
				echo "run TF script that deploys versioned SN onto AMI"
				}
		}
		
}