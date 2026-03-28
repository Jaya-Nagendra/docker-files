FROM almalinux:9
# this will run with root user
RUN dnf install nginx -y
# create roboshop user
RUN useradd roboshop

USER roboshop
# run the below command with roboshop user
CMD ["ping","google.com"]