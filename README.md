# SportcheckChatbot
#Step1. Install Docker 
###       yum install docker -y 
###	   usermod -aG docker ($username) #assign the user to use
###	   service docker start 
#Step2. Install Docker-compose 
###       curl -L "https://github.com/docker/compose/releases/download/1.23.1/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose 
###	   chmod +x /usr/local/bin/docker-compose 
#Step3. Edit docker-compose.yml
###        revise token as yours.
#Step4. Run dockerfile
###        docker-compose up --build -d #start dc
###        docker-compose -f yourFilePath/dockerComposeFileName.yml up --build -d #start build with dc file
#Step5. check containers
###        docker ps
###	   
