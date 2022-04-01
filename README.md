# Requisitos
Docker instalado
# Download do projeto
https://github.com/mauricionh01/conversao-temperatura.git
# Criação da imagem
docker build -t mauricionhptbr/conversao-temperatura:v1 .
# Visualizar a imagem criada
docker image ls
# Criação do container
docker container run -d \
--name conversao-temperatura \
-p 8080:8080 mauricioptbr/conversao-temperatura:v1
# Visualizar container
docker container ls


