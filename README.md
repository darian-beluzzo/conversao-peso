# Conversão de Peso
> Repositório dedicado ao Desafio 1 da **Iniciativa Kubernetes**
---
## Instruções
```
# Clone o repositório
git clone https://github.com/darian-beluzzo/conversao-peso
cd ./conversao-peso

# Construa a imagem
docker image build -t {usuario_dockerhub}/conversao-peso:1.0 .

# Rode o container
docker run --rm -d -p 80:80 --name conversao-peso {usuario_dockerhub}/conversao-peso:1.0

# Verifique o IP com:
docker container inspect conversao-peso

# Acesse a aplicação pela porta 80
http://localhost
```