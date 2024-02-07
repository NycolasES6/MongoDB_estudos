# Update e Find

## Criação do banco

### `use db_escola`

### `db.createCollection("aluno")`

### `db.aluno.insertOne()`

### `db.aluno.insertMany([`</br>`{matricula:12345, nome:"Atylas Ramos"},`</br>`{matricula:154376, nome:"Davi Ramos"},`</br>`{matricula:1029384756,nome:"Nycolas Ramos"}])`

</br>

## update

### `db.aluno.updateOne({nome : "Nycolas Ramos"}, {$set:{nome:"Eryck Cardoso"}})`

Atualiza o documento que tiver o `{nome : "Nycolas Ramos"}`, e vai atualizalo para `{nome:"Eryck Cardoso"}`

</br>

## find

### `db.aluno.find({nome:"Eryck Cardoso"})`

Retorna os documento que contenham `nome:"Eryck Cardoso"`

### `db.aluno.find({nome:{$ne:null}})`

Retorna todos os documentos que tiverem o `nome` diferente de `null`

