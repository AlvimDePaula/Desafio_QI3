# Desafio_QI3

Desafio foi realizado em 3 partes(Edital Desafio em PDF na pasta): 

1- Limpeza de dados recebido, na qual, tinha linhas duplicadas, dados faltantes, datas em formato númerico, etc (BigStore_Sujo).

2- Criar através de uma ferramenta de visualização gráficos para para responder as seguintes perguntas do cliente:
 * Quais são os três estados com maior valor de vendas para o ano de 2018?
 * Retorne os 3 primeiros dígitos para cada país e crie uma relação de país e estados. Exemplo: “BRA-Acre”
 * Quanto o produto ‘Carregador’ contribuiu percentualmente para cada país alcançar sua meta no ano de
2015?
 * Existem pedidos sem itens registrados? Se sim, para quantos pedidos e qual o valor total desses pedidos sem
itens?
 * Quantos clientes compraram mais de 2 vezes, durante 2015 e 2018, e gastaram no total mais de 1 mil reais?

3- Criar um algoritmo de Machine Learning para categorizar os clientes a partir do valor gasto.

Sabendo disso, foi criado um arquivo em excel com diversos inner join para se consiga fazer a limpeza e exploração dos dados (arquivo BIGSTORE_LIMPO).

Dentro do jupyter notebook foi realizado diversos insights e correção dos dados, além da criação da categoria para os clientes (arquivo em excel Podia_Cliente) em ouro, prata e bronze através do algoritmo Kmeans, onde é um modelo não-supervisionado que agrupa em "k" grupos instâncias com comportamento parecidos.

Para no final criar gráficos interativos no software Tableau para responder as perguntas do cliente e além de outras informações que podem ser de interesse do cliente.
