# app_python_prometheus

## Instrumentação de aplicação com python e prometheus

### Criando Imagem do projeto

* docker build -t app_python .

### Executando Container

* docker run --name app_python -h my_hostaname -p5000:5000 -d
