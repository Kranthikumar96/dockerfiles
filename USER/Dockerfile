FROM almalinux:9
RUN dnf install nginx -y
RUN useradd KRANTHI
USER KRANTHI
CMD ["nginx","-g","daemon off;"]