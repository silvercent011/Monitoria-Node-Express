### Lista de Exercícios

1. Monte um servidor HTTP com o Node JS onde:
  * Qualquer request devolva o horário do servidor
  * Requests GET para um path específico devem devolver uma imagem para o usuário (Fica a seu criterio decidir qual path é esse!)

2. Faça um script Node para fazer uma request no servidor que você mesmo montou
  * Dica: [Existem muitas bibliotecas Node que te ajudariam com isso](https://nodejs.dev/learn/making-http-requests-with-nodejs)

3. Faça uma API Node Node/Express que contenha:
  * Uma rota POST ou PUT /user onde se insere um user com nome, idade e estado civil numa base de dados
  * UMA rota DELETE /user/(nome) onde se deletaria da base o usuário que possuir esse nome
  * Uma rota GET com /user/(nome) onde se pegaria o user pelo nome e devolveria a quem busca as informações dele

4. Retorne ao seu usuário uma página num arquivo HTML ao acessar uma rota específica (Fica a seu critério decidir qual!)

5. [Trate os erros da sua API!](https://expressjs.com/en/starter/faq.html)