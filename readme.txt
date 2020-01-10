wget https://vlab3.dyndns.org/public/sdk/sdk-installer.sh


install:

mkdir -p ~/projects/sdk

docker run --rm -it -v ~/projects/sdk:/workdir reliableembeddedsystems/extsdk-container:ubuntu-16.04



---

docker run --rm -it -v /home/student/projects/sdk:/workdir reliableembeddedsystems/extsdk-container:ubuntu-16.04 --url https://vlab3.dyndns.org/sdk/sdk-installer.sh

docker run --rm -it -v /home/student/projects/sdk:/workdir -v /home/student/projects:/projects reslocal/extsdk-container







