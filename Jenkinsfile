pipeline{
	agent any
		stages{
			stage('One'){
				steps{
						exho 'Hi, this is my first jenkins thing'
					}
			stage('Two'){
				steps{
						input('Do you want to proceed?')
				}
			}
			stage('Three'){
					when{
							not{
								branch "master"
							}
					}
					steps{
							echo "Hello"
						}
							}
						}
		}
}