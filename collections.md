# Collections

## Introducao

### `use db_escola`

Aqui dizemos que vamos *usar* o banco de dados `db_escola`, mas caso ele não exista ele sera *criado*.
</hr>

### `db.createCollection("aluno")`

Criamos uma colecao chamada `aluno`.
</hr>

### `db.aluno.insertOne({matricula:1029384756,nome:"Nycolas Ramos"})`

Aqui estamos *inserindo* um documento na colecao `aluno`.
>Esse comando recebe os valores do documento em formato JSON.
>
> Ao executarmos ele cria um campo `_id: ObjectId('65c27c936e534b6e6dd2aa23')` que será o identificador único de cada documento.
</hr>

### `db.aluno.insertMany([{matricula:12345, nome:"Atylas Ramos"},{matricula:154376, nome:"Davi Ramos"}])`

Para inserir mais de um documento, basta colocarmos dentro de *colchetes* e separarmos os *objetos* por vírgula.
</hr>

### `db.aluno.find()`

Ele procura todos os documentos sem algum tipo de filtro.
</hr>
