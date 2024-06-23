
# Laravel 11 - Arquivo base com docker

### Subir os containers do projeto

```bash
    sudo docker-compose up -d
```

### Criar o arquivo .env

```bash
    cp .env.example .env
```

### Acessar o container app

```bash
    sudo docker-compose exec app bash
```

### Instalar as dependências do projeto

```bash
    composer install
```

- Sair do bash terminal -> exit

### Instalar dependências NPM
```bash
    npm install
```

### Rodar localmente
```bash
    npm run dev
```
