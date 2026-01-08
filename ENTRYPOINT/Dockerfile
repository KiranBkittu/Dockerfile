FROM almalinux:9
#RUN dnf install nginx -y
#CMD ["google.com"]
RUN dnf install -y iputils && dnf clean all
ENTRYPOINT ["ping","google.com"]
## Entrypoint overrides cmd command we can use outside also ..docker run entry:v1 ping facebook.com ..
