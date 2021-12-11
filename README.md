# Projeto Netflix [Postgresql + NestJs + TypeScript + Prisma]

## Rotas: Filme, Gênero e Participante

##### Integração Backend + Postgresql + Prisma.

API com rotas e banco de dados distintos, através do VS Code.

**** Existem os seguintes Endpoints por rota:

[GET] Leitura de todos os itens
[GET] Leitura de itens individuais (por ID)
[POST] Cadastro
[PATCH] Edição de item por ID
[DELETE] Exclusão de item por ID

## **** Endpoints - Filme ****

[GET] Leitura de todos os itens
http://localhost:3000/filme/

[GET] Leitura de itens individuais (por ID)
http://localhost:3000/filme/id

[POST] Cadastro
http://localhost:3000/filme/


Todos os campos são obrigatórios:
```

{
  "nome": "String", 
  "imagem": "String",
  "data_lancamento": "String", 
  "tempo_duracao": "String",
  "generoid": "Int",
  "participantes: "Int"
}

```

[PATCH] Edição de item por ID
http://localhost:3000/filme/id


Todos os campos são obrigatórios:
```

{ 
  "nome": "String", 
  "imagem": "String",
  "data_lancamento": "String", 
  "tempo_duracao": "String",
  "generoid": "Int",
  "participantes: "Int"
}

```
[DELETE] Exclusão de item por ID
http://localhost:3000/filme/id

## **** Endpoints - Gênero ****

[GET] Leitura de todos os itens
http://localhost:3000/genero/

[GET] Leitura de itens individuais (por ID)
http://localhost:3000/genero/id

[POST] Cadastro
http://localhost:3000/genero/


Todos os campos são obrigatórios:
```

{
  "nome": "String"
}

```
[PATCH] Edição de item por ID
http://localhost:3000/genero/id


Todos os campos são obrigatórios:
```

{ 
  "nome": "String"
}

```

[DELETE] Exclusão de item por ID
http://localhost:3000/genero/id

## **** Endpoints - Participante ****

[GET] Leitura de todos os itens
http://localhost:3000/participante/

[GET] Leitura de itens individuais (por ID)
http://localhost:3000/participante/id

[POST] Cadastro
http://localhost:3000/participante/


Todos os campos são obrigatórios:
```

{ 
  "nome": "String", 
  "imagem": "String",
  "data_nascimento": "String", 
  "staff": "Number",
  "filmeid": "Int"
}

```
[PATCH] Edição de item por ID
http://localhost:3000/participante/id


Todos os campos são obrigatórios:
```

{ 
  "nome": "String", 
  "imagem": "String",
  "data_nascimento": "String", 
  "staff": "Number",
  "filmeid": "Int"
}

```

[DELETE] Exclusão de item por ID
http://localhost:3000/participante/id


### Projeto configurado e conectado ao Postgresql.


