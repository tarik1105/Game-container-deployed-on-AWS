# 2048-Game and deployed on AWS

requirements: docker, vs code.

step1. create Dockerfile.
step2. create an image.
step3. create docker container.
step4. deploy it on AWS (Elastic Beanstalk)

commands:
$ docker build -t [image-name]
$ docker images
$ docker run -d -p 80:80 [image-ID]