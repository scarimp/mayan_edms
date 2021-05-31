
Docker compose file for mayan edms  **docker-compose.yml**

# uninstall docker-compose

To uninstall Docker Compose if you installed using curl:

- *sudo rm /usr/local/bin/docker-compose*

To uninstall Docker Compose if you installed using pip:

- *pip uninstall docker-compose*

install docker_compose vers. 1.9.2 on your local system

sudo curl -L "https://github.com/docker/compose/releases/download/1.29.1/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose

## version 4.0  of mayan-edms
curl https://gitlab.com/mayan-edms/mayan-edms/-/raw/master/docker/docker-compose.yml -O

sudo chmod +x /usr/local/bin/docker-compose

see https://docs.mayan-edms.com/chapters/docker/install_docker_compose.html#docker-compose-install


# LINKS to use with curl , get to download files from web**

curl -O https://www.digitalocean.com/robots.txt



https://github.com/scarimp/my_NLP/blob/master/chow-params.pdf

https://github.com/scarimp/my_NLP/blob/master/INLP_LAB/Tesi_Chiara_Alzetta.pdf

https://raw.githubusercontent.com/scarimp/my_NLP/master/INLP_LAB/Tesi_Chiara_Alzetta.pdf

https://raw.githubusercontent.com/scarimp/my_NLP/master/INLP_LAB/Natural_Language_Processing_in_Action_v9.pdf

curl -O https://github.com/scarimp/my_NLP/blob/master/INLP_LAB/Tesi_Chiara_Alzetta.pdf

curl -O https://raw.githubusercontent.com/scarimp/my_NLP/master/chow-params.pdf

--------------------------------------------------------
OR rename the file to download

curl -o do-bots.txt  https://www.digitalocean.com/robots.txt

OR redirect

    curl -I www.digitalocean.com

The output shows that the URL was redirected. 
The first line of the output tells you that it 
was moved, and the Location line tells you where:

You could use curl to make another request manually, 
or you can use the --location or -L argument which 
tells curl to redo the request to the new location 
whenever it encounters a redirect. Give it a try:

    curl -L www.digitalocean.com/robots.txt
    
You can combine the -L argument with some of 
the aforementioned arguments to download the 
file to your local system:

    curl -L -o do-bots.txt www.digitalocean.com/robots.txt






