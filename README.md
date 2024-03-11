## Instruções de execução
### Dependências
 - Docker
### Execução
- Buildar a imagem
  - `docker build -t ${image-name}`
- Executar o programa
  - `docker run --rm ${image-name}t --url ${url} --requests ${request-number} --concurrency #{concurrency-number}`
    - --url => url para receber requisições GET
    - --requests => quantidade de requisições que serão feitas
    - --concurrencty => quantidades de requisições que serão feitas de forma concorrente

  