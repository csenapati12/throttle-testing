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
        stage('Throttle2') {
            steps {
                echo 'I m in Throttle2 branch'
               bat ''':a
echo "i m here"
goto a''' 
            }
        }
    }
}
