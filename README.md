AV2 Bando de Dados / ADS_Noite / Equipe: Devs

Projeto acadêmico da AV2 de Banco de Dados do curso de Análise e Desenvolvimento de Sistemas.

## Objetivo

Modelar e implementar um banco de dados para o atendimento presencial de um restaurante, registrando mesas, garçons, produtos, pedidos, itens consumidos e pagamentos.

## Tecnologias

* SQLite: banco de dados.
* DB Browser for SQLite: criação e execução dos scripts.
* draw.io: elaboração da UML.
* Git e GitHub: versionamento e colaboração.

## Tabelas

* `categorias`
* `produtos`
* `mesas`
* `garcons`
* `pedidos`
* `itens_pedido`
* `pagamentos`

## Principais regras

* Cada pedido pertence a uma mesa e possui um garçom responsável.
* Cada produto pertence a uma categoria.
* Um pedido pode conter vários itens e receber vários pagamentos.
* Cada item registra a quantidade e o preço cobrado na venda.
* Valores monetários são armazenados em centavos.
* O total do pedido é calculado a partir dos seus itens.
* A finalização exige itens e pagamentos suficientes para quitar o pedido.
* `pedidos` e `itens_pedido` representam o relacionamento mestre-detalhe.

## Conteúdos trabalhados

* Criação de tabelas, chaves primárias e estrangeiras.
* Restrições de integridade.
* CRUD: inserção, consulta, atualização e exclusão.
* Filtros com `WHERE`, `AND`, `IN` e `IS NULL`.
* Relacionamentos com `JOIN`.
* Transações com `BEGIN`, `COMMIT` e `ROLLBACK`.
* Documentação da estrutura em UML.

## Organização

* `docs/`: UML e regras do negócio.
* `sql/`: scripts de estrutura, dados, consultas e operações.

## Equipe

* **João G Santos 01510041:** documentação, UML e organização da apresentação.
* **Luiz H Souza:** estrutura das tabelas, chaves e restrições.
* **Diego de Lima:** dados de exemplo, CRUD e consultas.

Todos participam da revisão, dos testes e da apresentação.
