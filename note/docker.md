### Dockernized Terraform

```
$ docker pull hashicorp/terraform:0.12.5

// confirm version
$ docker run --rm hashicorp/terraform:0.12.5 --version

// execute
$ docker run --rm -i -v $PWD:/work -w /work \
  -e AWS_ACCESS_KEY_ID=$AWS_ACCESS_KEY_ID \
  -e AWS_SECRET_ACCESS_KEY=AWS_SECRET_ACCESS_KEY \
  -e AWS_DEFAULT_REGION=AWS_DEFAULT_REGION \
  hashicorp/terraform:0.12.5 <command>
```
