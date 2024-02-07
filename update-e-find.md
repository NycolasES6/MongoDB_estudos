# Update e Find

## Criação do banco
### `use db_escola`
### `db.createCollection("aluno")`
### `db.aluno.insertOne()`
### `db.aluno.insertMany([`<br>`{matricula:12345, nome:"Atylas Ramos"},`<br>`{matricula:154376, nome:"Davi Ramos"}, `<br>`{matricula:1029384756,nome:"Nycolas Ramos"}])`

<hr><hr>

## update
### `db.aluno.updateOne({nome : "Nycolas Ramos"}, {$set:{nome:"Eryck Cardoso"}})`
Atualiza o documento que tiver o `{nome : "Nycolas Ramos"}`, e vai atualizalo para `{nome:"Eryck Cardoso"}`


<hr><hr>

## find

### 