
# Setup Docker Para Projetos Laravel 9 com PHP 8

### Passo a passo
Clone Repositório
```sh
git clone https://github.com/GuilhermeLegramante/filament-test.git
```

```sh
cd filament-test/
```

Crie o Arquivo .env
```sh
cd filament-test/
cp .env.example .env
```

Suba os containers do projeto
```sh
docker-compose up -d
```

Acessar o container
```sh
docker-compose exec app bash
```

Instalar as dependências do projeto
```sh
composer install
```

Gerar a key do projeto Laravel
```sh
php artisan key:generate
```

Acesse o projeto
[http://localhost:8181](http://localhost:8181)
