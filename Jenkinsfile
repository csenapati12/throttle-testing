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
        stage('Main') {
            steps {
                echo 'I m in main branch'
               bat ''':a
echo "i m here"
goto a''' 
            }
        }
    }
}
