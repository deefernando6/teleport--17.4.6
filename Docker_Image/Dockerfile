FROM ubuntu:noble 

RUN apt update -y
RUN apt upgrade -y
RUN apt install -y sudo 
RUN apt install -y curl
#RUN sudo curl https://deb.releases.teleport.dev/teleport-pubkey.asc -o /usr/share/keyrings/teleport-archive-keyring.asc
#RUN echo "deb [signed-by=/usr/share/keyrings/teleport-archive-keyring.asc] https://deb.releases.teleport.dev/ stable main" | sudo tee /etc/apt/sources.list.d/teleport.list > /dev/null
#RUN apt update -y
#RUN apt install -y teleport=14.3.3
RUN curl https://cdn.teleport.dev/install.sh | bash -s "17.4.6" "oss"