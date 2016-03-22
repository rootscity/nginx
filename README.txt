`aws ecr get-login`
docker build -t nginx .
docker tag nginx:latest 278641342404.dkr.ecr.us-east-1.amazonaws.com/nginx:v4
docker push 278641342404.dkr.ecr.us-east-1.amazonaws.com/nginx:v4
# update trees task def
