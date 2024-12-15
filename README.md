# 1. Problema de negócio

 A empresa Fome Zero é uma marketplace de restaurantes. Ou seja, seu core
 business é facilitar o encontro e negociações de clientes e restaurantes. Os
 restaurantes fazem o cadastro dentro da plataforma da Fome Zero, que disponibiliza
 informações como endereço, tipo de culinária servida, se possui reservas, se faz
 entregas e também uma nota de avaliação dos serviços e produtos do restaurante,
 dentre outras informações.

 Você acaba de ser contratado como Cientista de Dados da empresa
 Fome Zero, e a sua principal tarefa nesse momento é ajudar o CEO Kleiton Guerra
 a identificar pontos chaves da empresa, respondendo às perguntas que ele fizer
 utilizando dados.

 ## O Desafio
 O CEO Guerra também foi recém contratado e precisa entender melhor o negócio
 para conseguir tomar as melhores decisões estratégicas e alavancar ainda mais a empresa
 Fome Zero, e para isso, ele precisa que seja feita uma análise nos dados da
 empresa e que sejam gerados dashboards, a partir dessas análises, para responder
 às seguintes perguntas:

 ### Geral
 1. Quantos restaurantes únicos estão registrados?
 2. Quantos países únicos estão registrados?
 3. Quantas cidades únicas estão registradas?
 4. Qual o total de avaliações feitas?
 5. Qual o total de tipos de culinária registrados?

 ### Pais
 1. Qual o nome do país que possui mais cidades registradas?
 2. Qual o nome do país que possui mais restaurantes registrados?
 3. Qual o nome do país que possui mais restaurantes com o nível de preço igual a 4
 registrados?
 4. Qual o nome do país que possui a maior quantidade de tipos de culinária
 distintos?
 5. Qual o nome do país que possui a maior quantidade de avaliações feitas?
 6. Qual o nome do país que possui a maior quantidade de restaurantes que fazem
 entrega?
 7. Qual o nome do país que possui a maior quantidade de restaurantes que aceitam
 reservas?
 8. Qual o nome do país que possui, na média, a maior quantidade de avaliações
 registrada?
 9. Qual o nome do país que possui, na média, a maior nota média registrada?
 10. Qual o nome do país que possui, na média, a menor nota média registrada?
 11. Qual a média de preço de um prato para dois por país?

 ### Cidade
 1. Qual o nome da cidade que possui mais restaurantes registrados?
 2. Qual o nome da cidade que possui mais restaurantes com nota média acima de
 4?
 3. Qual o nome da cidade que possui mais restaurantes com nota média abaixo de
 2.5?
 4. Qual o nome da cidade que possui o maior valor médio de um prato para dois?
 5. Qual o nome da cidade que possui a maior quantidade de tipos de culinária
 distintas?
 6. Qual o nome da cidade que possui a maior quantidade de restaurantes que fazem
 reservas?
 7. Qual o nome da cidade que possui a maior quantidade de restaurantes que fazem
 entregas?
 8. Qual o nome da cidade que possui a maior quantidade de restaurantes que
 aceitam pedidos online?

 ### Restaurantes
 1. Qual o nome do restaurante que possui a maior quantidade de avaliações?
 2. Qual o nome do restaurante com a maior nota média?
 3. Qual o nome do restaurante que possui o maior valor de uma prato para duas
 pessoas?
 4. Qual o nome do restaurante de tipo de culinária brasileira que possui a menor
 média de avaliação?
 5. Qual o nome do restaurante de tipo de culinária brasileira, e que é do Brasil, que
 possui a maior média de avaliação?
 6. Os restaurantes que aceitam pedido online são também, na média, os
 restaurantes que mais possuem avaliações registradas?
 7. Os restaurantes que fazem reservas são também, na média, os restaurantes que
 possuem o maior valor médio de um prato para duas pessoas?
 8. Os restaurantes do tipo de culinária japonesa dos Estados Unidos da América
 possuem um valor médio de prato para duas pessoas maior que as churrascarias
 americanas (BBQ)?

 ### Tipos de Culinária
 1. Dos restaurantes que possuem o tipo de culinária italiana, qual o nome do
 restaurante com a maior média de avaliação?
 2. Dos restaurantes que possuem o tipo de culinária italiana, qual o nome do
 restaurante com a menor média de avaliação?
 3. Dos restaurantes que possuem o tipo de culinária americana, qual o nome do
 restaurante com a maior média de avaliação?
 4. Dos restaurantes que possuem o tipo de culinária americana, qual o nome do
 restaurante com a menor média de avaliação?
 5. Dos restaurantes que possuem o tipo de culinária árabe, qual o nome do
 restaurante com a maior média de avaliação?
 6. Dos restaurantes que possuem o tipo de culinária árabe, qual o nome do
 restaurante com a menor média de avaliação?
 7. Dos restaurantes que possuem o tipo de culinária japonesa, qual o nome do
 restaurante com a maior média de avaliação?
 8. Dos restaurantes que possuem o tipo de culinária japonesa, qual o nome do
 restaurante com a menor média de avaliação?
 9. Dos restaurantes que possuem o tipo de culinária caseira, qual o nome do
 restaurante com a maior média de avaliação?
 10. Dos restaurantes que possuem o tipo de culinária caseira, qual o nome do
 restaurante com a menor média de avaliação?
 11. Qual o tipo de culinária que possui o maior valor médio de um prato para duas
 pessoas?
 12. Qual o tipo de culinária que possui a maior nota média?
 13. Qual o tipo de culinária que possui mais restaurantes que aceitam pedidos
 online e fazem entregas?

# 2. Premissas assumidas para a análise
1. A análise foi realizada com dados dos 100 melhores restaurantes de cada cidade.
2. Marketplace foi o modelo de ngócio assumido.
3. As 3 principais visões de negócio foram: dados por país, cidade e  culinária.

# 3.Estratégia da solução
O painel estratégico foi desenvolvido utilizando as métricas que refletem as 3 visões do modelo de negócio da empresa:

1. Visão por país
   i.Quantidade de restaurantes por país
  ii.Quantidade de cidades por país
 iii.Média de avaliações por país
  iv.Preço médio para duas pessoas por país

2. Visão por cidade
   i.Top 10 cidades com mais restaurantes
  ii.Quantidade de restaurantes por cidade com avaliação média acima de 50
 iii.Quantidade de restaurantes por cidade com avaliação média abaixo de 50
  iv.Quantidade de restaurantes por cidade mais de uma culinária

3. Visão por tipo de culinária
   i.Melhor restaurante das 5 principais culinárias
  ii.Top 10 melhores restaurantes
 iii.TOP 10 Melhores tipos de culinária
  iv.TOP 10 Piores tipos de culinária

# 4. O produto final do projeto
  Painel online, hospedado em um Cloud e disponível para acesso em qualquer dispositivo conectado à internet.
  O painel pode ser acessado através do link: https://projetosfomezero.streamlit.app/Countries

# 5. Conclusão
O objetivo desse projeto é criar um conjunto de gráficos e ou tabelas que exibam essas métricas da melhor forma possível para o CEO.


