# Install Wordpress in Local Machine in Windows

## Install Docker Desktop
install and login (it is 1GB)

## Install wordpress docker
open powershell and type this:  
`docker pull wordpress`  
`docker run --name some-wordpress -p 8080:80 -d wordpress`   

open your browser and type:  
`http://localhost:8080`  

then you can access wordpress installation  

## Install MySQL

`docker run -it -p 8080:80 -p 3306:3306 -d wordpress`

