def kw()
{
	echo "process kw"
}

def coverity()
{
	echo "process coverity"
}

def deploy()
{
	echo "process deploy" 
}

def build()
{
	echo "build"
}

def main()
{
	node("Test"){
		stage('kw'){
			kw()
		}
		stage('coverity'){
			coverity()
		}
		stage('build'){
			build()
		}
		stage('deploy'){
			deploy()
		}
	}
}
