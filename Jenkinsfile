pipeline {
    agent any

 options {
      throttleJobProperty(
          categories: ['throttle'],
          throttleEnabled: true,
		  throttleOption: 'project',
          maxConcurrentTotal: 2
          
      )
    }

    stages {
        stage('Throttle3') {
            steps {
                echo 'I m in Throttle3'
               bat ''':a
echo "i m here"
goto a''' 
            }
        }
    }
}
