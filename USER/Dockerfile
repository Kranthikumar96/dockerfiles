FROM almalinux:9
RUN useradd KRANTHI
RUN dnf install nginx -y
USER KRANTHI
CMD ["nginx","-g","daemon off;"]