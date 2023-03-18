FROM almalinux:9

RUN yum update -y

RUN yum install -y \
   git \
   mc \
   wget \
   zsh

RUN sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

ENTRYPOINT [ "/bin/zsh" ]