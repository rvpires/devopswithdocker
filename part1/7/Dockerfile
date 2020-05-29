FROM ubuntu:16.04 

COPY script.sh . 
RUN apt-get update && apt-get install -y curl
RUN chmod 777 script.sh

CMD ./script.sh