pipeline 
{
agent any

	stages
		{
		stage("Verify AWS is active")
			{
			step
				{
				echo "run script that checks AWS infrastructure is availabile, VPCs, Subnets, etc."
				}
			}
		}
		
}