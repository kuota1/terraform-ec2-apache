##  Terraform EC2 Apache  

Este repositorio contiene la configuración de Terraform para desplegar una instancia EC2 en AWS con Apache instalado.  

---

##  Descripción  

- Se utiliza **Terraform** para aprovisionar la infraestructura en AWS.  
- Se crea una **instancia EC2** con un **grupo de seguridad** que permite tráfico HTTP en el puerto 80.  
- Se usa un **script de `user_data`** para instalar Apache y servir una página web automáticamente.  

---

##  Archivos incluidos  

- **`main.tf`**: Configuración principal de Terraform.  
- **Capturas de pantalla** del proceso (`terraform init`, `terraform plan`, `terraform apply`) y de la página web funcionando.  

---

##  Requisitos  

- Tener **AWS CLI** configurado.  
- Tener **Terraform** instalado.  

---

##  Uso  

1 Clonar el repositorio:  
```sh
git clone https://github.com/kuota1/terraform-ec2-apache.git
cd terraform-ec2-apache
