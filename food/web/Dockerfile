#Set the base image
FROM centos

#Docker file author
MAINTAINER Sunny Rampalli <sunnysudershan@gmail.com>

#Install Apache server package
RUN yum install -y httpd

#Install git repository
RUN yum install -y git

#Obtain git clone
RUN git clone https://github.com/demoglot/html-samples-food.git /var/www/html

# Run the httpd server
CMD ["httpd", "-DFOREGROUND"]

# Expose the port
EXPOSE 80
