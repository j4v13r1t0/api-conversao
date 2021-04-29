```
docker image build -t j4v13r1t0/api-conversao:v1 .
docker build -t j4v13r1t0/api-conversao:v1 .
docker push j4v13r1t0/api-conversao:v1

docker image ls
docker images

docker tag j4v13r1t0/api-conversao:v1 j4v13r1t0/api-conversao:latest
docker push j4v13r1t0/api-conversao:latest

docker container run -d -p 8080:8080 j4v13r1t0/api-conversao:v1
docker run -d -p 8080:8080 j4v13r1t0/api-conversao:v1


cat ~/my_password.txt | docker login --username j4v13r1t0 --password-stdin
```