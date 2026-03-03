FROM almalinux:9
RUN useradd kranthi
RUN dnf install nginx -y
USER kranthi
CMD ["nginx","-g","daemon off;"]