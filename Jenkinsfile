pipeline {
    agent any

 options {
      throttleJobProperty(
          categories: ['throttle'],
          throttleEnabled: true,          
          maxConcurrentTotal: 1,
	  throttleOption: 'project',
          
      )
    }

    stages {
        stage('Throttle1') {
            steps {
                echo 'I m in Throttle1 branch'
               bat ''':a
echo "i m here"
goto a''' 
            }
        }
    }
}
