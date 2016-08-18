`aws ecr get-login`
docker build -t nginx .
docker tag nginx:latest 278641342404.dkr.ecr.us-east-1.amazonaws.com/nginx:v7
docker push 278641342404.dkr.ecr.us-east-1.amazonaws.com/nginx:v7
# update trees task def
