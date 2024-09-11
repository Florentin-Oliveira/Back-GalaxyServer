# Pré-requisitos:

- Python
- 


### Execute o seguinte comando para instalar as dependências do projeto:

```
pip install -r requirements.txt
```

### Execute o seguinte comando para iniciar o servidor de desenvolvimento Django:

```
python manage.py runserver
```

Isso iniciará um servidor local na porta 8000. Você poderá acessar seu aplicativo em http://localhost:8000/ em seu navegador.


## Criar migrations:

### Execute o seguinte comando para gerar migrations para suas alterações no modelo de dados:

```
python manage.py makemigrations

```

## Aplicar migrations:

### Execute o seguinte comando para aplicar as migrations geradas ao seu banco de dados:

```
python manage.py migrate
```

# Observações: Para rodar no Docker:

```
docker-compose build 
```

```
docker-compose up 
```


