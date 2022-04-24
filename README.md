# terraform-docker-container
Provision NGINX webserver with Terraform in less than a minute using Docker.

## Requirements
-	[Terraform](https://www.terraform.io/downloads.html) >=0.12.x
-	[Docker](https://www.docker.com/get-started/)

## Provision container

```sh
$ git clone https://github.com/kabandr/terraform-docker-container.git
$ terraform init
$ terraform apply
```

## Stop container

```sh
$ terraform destroy
```