# aws-terraform-docker

  Este repositorio contiene una solución de IaC en AWS usando Terraform y Docker, con variantes en EC2 y ECS, y un módulo adicional para bootstrap de backend remoto (S3 + DynamoDB).

-Estructura de carpetas

  - 'package-ec2': Despliegue en EC2 con Docker usando 'userdata'.
  - 'package-ecs': Despliegue en ECS Fargate con contenedor montado y ALB.
  - 'package-backend-bootstrap': Terraform para crear S3 + DynamoDB y configurar el backend remoto.

-Contenido inicial

  Este commit solo incluye la estructura vacía, gitignore, y un script para empaquetar.  
  Los archivos de Terraform, Dockerfile y workflows deberán colocarse dentro de sus respectivas carpetas.


-Ejecutar para crear paquete y ejecutarlo:

  chmod +x create_package.sh
  ./create_package.sh
