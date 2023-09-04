- 👋 Hi, I’m @siddhin23
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

pipeline {
    agent any
     stages {
        stage('Build') {
            steps {
                echo 'Hello Peter!'
            }
        }
        stage('Test') {       
            steps {
                echo 'Peter listen to me, you idiot!'
            }
        }
        stage('Deploy') {
            steps {
                echo 'mj misses you'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Venom gonna come for you'
            }
        }
    }
}

