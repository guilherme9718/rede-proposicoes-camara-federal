# Plano do projeto

1. Definir até que ano vou analisar os dados (provavelmente a partir de 1998)

2. Fazer um algoritmo simples para baixar todos os dados a partir desse ano (utilizando curl ou scrapy)
    - Deverá baixar 3 arquivos por ano
    - link [dados abertos](https://dadosabertos.camara.leg.br/swagger/api.html#staticfile)

3. Juntar todos os dados relevantes em um único dataframe

4. Montar o gml geral pelo networkx

5. Analisar o gml no gephi
