FROM httpd
RUN apt-get update -y
RUN apt-get install -y python3-pip
RUN pip3 install awscli
COPY . /usr/local/apache2/htdocs
