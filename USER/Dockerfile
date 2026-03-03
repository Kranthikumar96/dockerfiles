FROM almalinux:9
RUN dnf install nginx -y
RUN useradd kranthi
USER kranthi
CMD ["nginx","-g","daemon off;"]