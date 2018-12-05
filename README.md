# raspberrypi
라즈베리파이 활용
# TensorFlow 설치
sudo apt-get install libatlas-base-dev

pip3 install tensorflow

https://github.com/tensorflow/tensorflow
# Docker
1. 도커 설치 scrpit 다운

curl -fsSL get.docker.com -o get-docker.sh

2. 도커 설치

sudo bash get-docker.sh

3. 도커 서비스 동작 확인

ps auwx|grep docker

4. 도커 프로세스 확인

sudo docker ps

5. 사용자 계정으로 도커 사용 

sudo usermod -aG docker pi

# flat
curl http://host.wednus.com/getflat|sh

sudo apt update && sudo apt upgrade -y

curl http://host.wednus.com/onlyflat|sh

sudo apt install docker-compose

sudo docker-compose up -d
