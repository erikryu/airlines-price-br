#

<div>
  <h1 align="center"> Automação de Web e de Processos utilizando Python e Google BigQuery (Data Engineering) 👩‍💻🦾🖥</h1>
</div>

#

<h3>➡Sobre o Desafio </h3>

A principal proposta deste desafio era de integrar um código Python com o serviço de armazenagem Google BigQuery. 
Os dados coletados foram os preços de passagens aéreas da companhia 
Latam.

Então o desafio é pegar deste site todas informações sobre os destinos e vôos, fazer dessas informações um banco de dados e 
fazer upload dessa base no Google BigQuery. E tudo automaticamente. 

Para isso eu utilizei a linguagem de programação Python e as bibliotecas Selenium, Pandas e Pandas-gbq. 

Site de onde foi feita a coleta:  https://www.latamairlines.com/br/pt/destinos.

# 

<h3>➡ Passo a passo para resolver o desafio: </h3>

1. Coletar dados de viagens:
    - Destino;
    - Dia de ida;
    - Tipo de passagem;
    - Tipo de classe do avião;
    - Tipo de voo;
    - Preço.
2. Transformar esses dados em um DataFrame;
3. Tratar o DataFrame;
4. Criar uma tabela para armazenar os dados no GoogleBigQuery;
5. Fazer upload dos dados para o BigQuery usando API.
