
// pipeline {
//     agent any

//     environment {
//         NODEJS_HOME = tool 'NodeJS 16'  // Ensure this matches the Jenkins tool name
//         PATH = "${NODEJS_HOME}/bin:${env.PATH}"
//     }

//     stages {
//         stage('Checkout') {
//             steps {
//                 git branch: 'main', url: 'https://github.com/patildinu/Restaurent_Application.git'
//             }
//         }

//         stage('Install Dependencies') {
//             steps {
//                 sh 'npm install'
//             }
//         }

//         stage('Build') {
//             steps {
//                 sh 'ng build --configuration production'
//             }
//         }

//         stage('Test') {
//             steps {
//                 sh 'ng test --watch=false --browsers=ChromeHeadless'
//             }
//         }

//         stage('Deploy') {
//             steps {
//                 echo 'Deploying Application...'
//                 // Add deployment steps here (e.g., AWS S3, Firebase, Nginx, etc.)
//             }
//         }
//     }
// }




// For Windowa 

pipeline {
    agent any
    stages {
        stage('Install Dependencies') {
            steps {
                bat 'npm install' // Use "bat" instead of "sh" for Windows
            }
        }
        stage('Build') {
            steps {
                bat 'npm run build' // Adjust command for your project
            }
        }
    }
}






// // For node 18 version


// pipeline {
//     agent any

//     environment {
//         NODEJS_HOME = tool 'NodeJS 18+'  // Ensure this matches the Jenkins tool name
//         PATH = "${NODEJS_HOME}/bin:${env.PATH}"
//     }

//     stages {
//         stage('Checkout') {
//             steps {
//                 git branch: 'main', url: 'https://github.com/patildinu/Restaurent_Application.git'
//             }
//         }

//         stage('Install Dependencies') {
//             steps {
//                 sh 'npm install'
//             }
//         }

//         stage('Build') {
//             steps {
//                 sh 'ng build --configuration production'
//             }
//         }

//         stage('Test') {
//             steps {
//                 sh 'ng test --watch=false --browsers=ChromeHeadless'
//             }
//         }

//         stage('Deploy') {
//             steps {
//                 echo 'Deploying Application...'
                
//             }
//         }
//     }
// }




