# nessus docker crack version

This project is only for non -profit learning research. Do not use it for illegal purposes. If there is any infringement, please contact it in time to delete it

[more info](https://twitter.com/elliot58616851)
# Install Docker
```
	sudo apt update && apt upgrade -y

	sudo apt install apt-transport-https curl gnupg-agent ca-certificates software-properties-common -y

	curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -

	sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu focal stable"

	sudo apt install docker-ce docker-ce-cli containerd.io -y

	sudo usermod -aG docker $USER

	newgrp docker

	docker version
 ```
	
	sudo curl -L "https://github.com/docker/compose/releases/download/1.29.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose

# Usage
`docker run -itd --name=ramisec_nessus -p 8834:8834 ramisec/nessus`  (497MB Only!!!)

That's right, easy like that! But it need update the plugins with the following command. 🤣

# Update
`docker exec -it ramisec_nessus /bin/bash /nessus/update.sh`  
No UPDATE_URL_YOU_GOT você precisa entrar no https://tenable.com/products/nessus/nessus-essentials do nessus para obter um código de ativação e gerá-lo neste https://plugins.nessus.org/v2/offline.php
![image](https://github.com/sidneysimas/nessus/assets/9019646/04940da9-8254-4ccc-8f96-57a702906c40)

Qualquer serial como esse aaaaaa11b2222cc33d44e5f6666a777b8cc99912 estaria disponível, mas lembre-se de que não deve ser a mesma :)

E você receberá o UPDATE_URL_YOU_GOT

![image](https://github.com/sidneysimas/nessus/assets/9019646/c7dfe212-7aae-4305-81f5-9a40c3afc22d)



__Alert__  
If you CAN NOT update successful, please CHECK the network connection!


# Account & Password

account: `admin`

Password: Easter Egg! Check the change version  
Let you explore the function, if you solved the password, Keep It Secret😉

or

```
docker ps

docker exec -it <container_id> /bin/bash

/opt/nessus/sbin/nessuscli chpasswd admin
new password
```
To restart docker container automaticaly procedure
```
sudo systemctl enable docker.service
```
```
docker update --restart=always [container id or container name]
```
# Readme

This crack was originally used, and I didn't plan to make it public  
But when I used the FAHAI cracked version of AWVS yesterday, I saw such a sentence:  
`Thank's Fahai && Open Source ENTHUSIAST`  
 <img src="https://user-images.githubusercontent.com/40572216/174698816-440d4969-f9d6-4c7d-982c-9af9c4a3e875.png" width = "400" height = "200" alt="图片名称" align=center />
 
So I was thinking, I used so many open source projects, how many contributions did I make?  
I simply disclose this project, which can also be considered a little contribution to the Internet security  
If there is no accident, it will continue to be updated, after all, I also need to use  
~~Don't get the automatic update plug -in version, use it first!~~  
I had release auto-update version, check Update log!

The Original Intention of the Project is in the Spirit of Open Source  
We can do a little thing for open source, for the world!  

# Update log

## v3 20220722
__Big update：auto-update plugins version has release！__

usage： `docker run -itd --name=ramisec_nessus -p 8834:8834 ramisec/nessus`  
The container had no plugins, it need to update by following command:  
`docker exec -it ramisec_nessus /bin/bash /nessus/update.sh`  
and it can be update again next time by the same command ！



## v2 20220621

Update the latest version of 20220620, and use 2 versions of NESSUS/JESSUSLITE  
The former has been cracked and compiled the plug -in.  
The latter needs to wait a few minutes to compile the plug -in  
password:  
`U2FSDGVKX19WZV+Qoe8awvyjwxDPSNSIC1X4AMNA4+3RO8ml/3Hz+MS/OR3DHCWXKS0WHFVOH1Q/yntvdxnahg ==`  

__TIPS__: gitHub/elliot-bia


> ~~# Old Usage~~
> ~~`docker run -itd -p 8834:8834 ramisec/nessus`   (4.73GB)~~
> ~~ or~~  
> ~~`docker run -itd -p 8834:8834 ramisec/nessuslite` (3.55GB)~~ 
> ~~The former does not require compilation and is suitable for low-performance high-bandwidth machines~~  
> ~~The latter requires compilation and is suitable for high-performance low-bandwidth machines~~  
> ~~What? high-performance and high-bandwidth machines? Never mind, just use it! have fun!~~

In fact, there is another EASY way to solved the encryption, try and find it!😆

# Thanks note
Some English text translated by [Aholicknight](https://github.com/Aholicknight)

thanks a lot! 

# donate
If you like this project, you can be a sponsor!  

[Pay Me via PayPal](https://www.paypal.com/paypalme/pay2rami)
