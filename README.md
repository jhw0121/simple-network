# simple-network

#nodejs 설치
-sudo apt-get update
#docker 설치
-sudo apt-get install docker.io
-sudo apt-get install docker-compose
#사용자에게 권한 주기
-sudo usermod -aG docker$USER
#reboot
-sudo reboot
#curl 설치
-sudo apt-get install curl -y
-curl -sL https://raw.githubusercontent.com/creationix/nvm/v0.31.0/install.sh -o install_nvm.sh
-bash install_nvm.sh
-source ~/.profile
-nvm install v12
-node -v
-npm -v
#go install
-curl -O https://storage.googleapis.com/golang/go1.13.14.linux-amd64.tar.gz
-tar -xvf go1.13.14.linux-amd64.tar.gz
-sudo mv go/usr/local
-sudo ln -s usr/local/go/bin/go/usr/local/bin/go
-nano ~/.profile 마지막 줄에 추가
-export GOPATH=$HOME/go
-export PATH+$PATH:/usr/local/go/bin:$GOPATH/bin
-source ~/.profile

