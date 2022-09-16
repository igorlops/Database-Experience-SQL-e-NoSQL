# Database Experience - SQL e NoSQL


## SQL e NoSQL

Os dados relacionais por muito tempo supriram grande necessidades, 
porém é uma determinada data da história
viu-se a necessidade de uma gama maior de dados, e que 
fossem mais escaláveis.
Foi então criado o modelo NoSQL, que é um complemento, com dados não 
estruturados e com soluções mais viáveis para o contexto de grande volume
de dados. NoSQL não significa Não SQL, na verdade significa não relacional,
posteriormente estendido para Not Only SQL - Não Somente SQL.

O NoSQL não veio pra substituir o SQL, ele veio pra atender o que a gente
não conseguia fazer no modelo relacional, pois com o absurdo de um grande 
volume de informação, fez-se necessário criá-lo. No modelo NoSQL é bastante
flexível em relação aos dados, pois aceita todo tipo de dado sem contar que
é bem mais fácil de realizar consultas.

Sobre o NoSQL, como encontrar algo armazenado quando não se sabe a estrutura?

- A consulta no NoSQL deve ser pensada desde o inicio, por exemplo definindo
as chaves, pois é por onde vamos pesquisar. A aplicação também deve prever 
toda modelagem que será no banco de dados NoSQL.


Conhecer um SGBD de cada tipo é o suficiente para iniciar?

- Você não necessita precisamente de conhecer todos, mas na verdade deve
entender o conceito de SQL, e banco de dados, conhecer a essência, chave-valor,
entre outros. Primeiramente devemos observar qual a nossa necessidade no momento
 com a curva de aprendizado, pra depois poder ter as boas práticas ao praticar.

Vale ressaltar ainda que os bancos de dados relacionais seguem o modelo 
ACID para preservar a integridade de uma transação. Este conjunto de 
procedimentos é dividido em quatro propriedades, e são elas:

Atomicidade: As ações que compõe a ação da transação devem ser concluídas
 com sucesso para ser efetivada. Se esta transação falhar, será feito o 
rollback.

Consistência: Todas as regras/restrições descritas no banco de dados 
devem ser obedecidas garantindo que o banco de dados passe de uma forma 
consistente para outra forma consistente.

Isolamento: Neste caso, a propriedade de isolamento garante que a 
transição não será interferida por nenhuma outra transação concorrente.

Durabilidade: Os resultados de uma transação são permanentes, ou seja, o 
que foi salvo não será mais perdido.


Todos esses diferentes recursos auxiliaram a manter os SGBDs Relacionais 
sempre em uma posição de predominância entre os mais diversos tipos de ambientes 
computacionais, mas ao mesmo tempo, não impediu o aparecimento de determinados
 problemas, isso devido ao grande crescimento do volume de dados presente nos
 bancos de dados de algumas organizações.

 
