# aws-cli

```
docker pull nickromano/aws-cli-docker
docker run --rm -e "AWS_ACCESS_KEY_ID=mykey" -e "AWS_SECRET_ACCESS_KEY=myaccesskey" -e "AWS_DEFAULT_REGION=us-east-1" nickromano/aws-cli-docker ecr get-login --no-include-email
```
