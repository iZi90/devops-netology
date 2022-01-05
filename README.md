<<<<<<< HEAD
# devops-netologynew line
new line
=======
Игнорировать все каталоги входящие в состав terraform
**/.terraform/*

Игнорировать все файлы с расширением .tfstate и входящих в них такие как *.tfstate.*
.tfstate
*.tfstate.*

Игнорировать файлы
crash.log
crash. *.log

Исключить все файлы .tfvars




*.tfvars

Игнорировать файлы переопределения

override.tf
override.tf.json
*_override.tf
*_override.tf.json

Включить файлы 

! example_override.tf

Включить файлы tfplan


Игнорировать файлы конфигурации CLI
.terraformrc
terraform.rc
>>>>>>> 6ebef866ee433a1b440bf0305662af843137398b
