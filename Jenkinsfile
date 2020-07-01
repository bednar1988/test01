pipeline {
    agent any
    stages { 
        stage('Verify Branch') {
            steps {
                echo "$GIT_BRANCH"
            }
        }
        stage('Example') {
            steps {
                echo 'Hello World'
            }
        }
				stage('Goodbye') {
					steps {
							echo "Goodbye"
					}
				}
    }
}
