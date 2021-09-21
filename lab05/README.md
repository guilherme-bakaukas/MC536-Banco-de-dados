# Lab05 - Marcadores e Taxonomia em Cypher

# Aluno
* `217332`: `Guilherme Tezoli Bakaukas`

## Tarefa de Cypher sobre Marcadores e Taxonomia

## Tarefa 1

Escreva em Cypher uma consulta que retorne os marcadores da categoria `Serviços`, sem considerar as categorias subordinadas.

### Resolução
~~~cypher
MATCH (m: Marcador) MATCH (c: Categoria {id:"Serviços"}) WHERE (m)-[:Pertence]->(c) RETURN m
~~~

## Tarefa 2

Escreva em Cypher uma consulta que retorne os marcadores da categoria `Serviços`, considerando as categorias subordinadas.

### Resolução
~~~cypher
MATCH (sub:Categoria)-[:Superior*1..3]->(cat:Categoria {id: "Serviços"}) MATCH (m:Marcador) WHERE (m)-[:Pertence]->(sub) OR (m)-[:Pertence]->(cat) RETURN m
~~~
