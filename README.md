# Atividade de CRUD no Node.JS com banco de dados não-relacional

Parabéns, se você chegou nesse ponto da trajetória da Arbyte, você de fato já passou por uma grande jornada. Diferente do que passamos antes, neste momento estamos trabalhando no backend, especificamente construindo APIs no padrão REST que se comunicam via o protocolo HTTP de suas rotas.

Chegou a hora de nos desafiarmos a construir uma API que de fato manipula um banco de dados. Para esta atividade, utilizaremos o mongoDB com o Javascript no Node. O banco que utilizaremos é o mesmo banco NoSQL que já trabalhamos nas úlitmas aulas: O banco de dados de restaurantes, cujo JSON pode ser obtido aqui neste mesmo repositório caso você já tenha deletado (restaurants.json). 

## Requisitos

Nesta atividade, portanto, vamos cumprir os seguintes objetivos:

* Criar um arquivo chamado servico.js que importará o Express.JS.
* Criar uma aplicação que rodará no localhost na porta 3000
* Conectar no banco de dados através do módulo do mongo para javascript (se você ainda não tem instalado, obtenha-o através do `npm install mongodb`
* Criar um endpoint para cada operação principal do banco: CREATE, READ, UPDATE, DELETE
* Testar todas as queries e o resultado que elas geram no formato json no browser

Essa atividade será guiada pelos nossos tutores, e é a primeira parte da construção de uma aplicação completa com backend. Posteriormente, aplicaremos segurança nessas requisições e também construiremos um frontend para renderizar esses dados para nossos clientes.
