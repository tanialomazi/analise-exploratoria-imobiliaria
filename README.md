# Projeto: Compra e Venda de Imóveis
Fonte: https://medium.com/@meigarom/os-5-projetos-de-data-science-que-far%C3%A1-o-recrutador-olhar-para-voc%C3%AA-c32c67c17cc9

## Introdução

Projeto em andamento que tem por objetivo responder as três questões relacionadas abaixo, utilizando base de dados com informações de compra e venda de imóveis entre os anos de 2014 e 2015.

1. Quais casas o CEO da House Rocket deveria comprar e por qual preço de compra?
2. Uma vez a casa em posse da empresa, qual o melhor momento para vendê-las e qual seria o preço da venda?
3. A House Rocket deveria fazer uma reforma para aumentar o preço da venda? Quais seriam as sugestões de mudanças? Qual o incremento no preço dado por cada opção de reforma?

Realizada em Python através do Jupyter Notebook, utilizando as bibliotecas Pandas e Plotly.


## O Projeto

<img src="https://github.com/tanialomazi/analise-exploratoria-imobiliaria/blob/master/gif_projeto.gif"> 


## Resultados

Os fatores que influenciam diretamente o preço dos imóveis para os dados analisados são, em ordem crescente:

1. tamanho do imóvel em m²
2. nota do design
3. tamanho do andar superior em m²
4. quantidade de banheiros

## Conclusão

Não foram necessários realizar tratamentos para valores nulos, uma vez que todas as linhas estão preenchidas. Em compensação, algumas linhas da tabela tiveram que ser excluídas, pois apresentaram valores inconsistentes, como quantidade de banheiros inexistentes ou quantidade de quartos muito maior do que o tamanho do imóvel comportaria. 

Após as análises estatísticas e a partir dos gráficos, chegou-se a conclusão que as características ideais do imóvel que o CEO deve comprar para obter máximo ganho são:

- Preço abaixo de 450k;
- 3 ou 4 quartos;
- Até 3 banheiros;
- Até 200m² construídos e 20.000m² de terreno;
- Nota de design entre 6 e 8;
- Imóveis da década de 40 ou reformados a partir da década de 60.
- Reformar os imóveis, de forma que o valor total após reforma não ultrapasse 700k;
- Ideal seria comprar os imóveis entre novembro e fevereiro e vendê-los entre os meses de abril e julho.

> **Porque?**

> O CEO deve comprar casas com valor abaixo da mediana, já que mais de 50% dos imóveis encontra-se abaixo desse valor, que no caso é de 450k. Casas com 3 ou 4 quartos podem ser vendidas um pouco acima da média, portanto podem ser uma boa opção. Uma casa com até 3 banheiros permanece dentro de uma mesma faixa de preço, portanto seria mais fácil vendê-las. Imóveis com até 200m² e terreno de até 20.000m² são as mais frequentes, portanto mais interessantes. Imóveis com a nota de design entre 6 e 8 são mais interessantes e estão dentro da média de preço geral. Imóveis da década de 40 são os mais baratos, mas talvez precisem de reforma. Imóveis que foram reformados a partir da década de 60 apresentam valores de venda superiores a média geral. Imóveis reformados são vendidos, em média, por um valor de 760k. Nos meses de abril a julho, o valor da venda dos imóveis é mais alto, enquanto entre novembro e fevereiro é mais baixa. 
