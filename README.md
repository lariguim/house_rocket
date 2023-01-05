# House Rocket Project

# 1.0 Descrição
A House Rocket é uma empresa fictícia que utiliza a tecnologia para tomar decisões de compra e venda de imóveis. Este projeto de Ciência de Dados tem como objetivo encontrar as melhores oportunidades de negócio para maximizar o faturamento da empresa. A melhor estratégia é a compra de casas em ótimas condições por baixos preços e a venda desses imóveis por um preço superior. Nesse projeto o cientista de dados deve obter insights através da manipulação de dados para auxiliar as melhores decisões da equipe de negócios. As questões a serem respondidas são:

1. Quais casas o CEO da House Rocket deveria comprar e por qual preço de compra?

2. Uma vez a casa em posse da empresa, qual o melhor momento para vendê-las e qual seria o preço da venda?


# 2.0 Atributos
Os dados para este projeto podem ser encontrados em: https://www.kaggle.com/harlfoxem/housesalesprediction/discussion/207885. 

# 3. Premissas do Negócio
Para o desenvolvimento desse projeto, seguimos as seguintes premissas:
  - Valores iguais a zero corresponde a casas nunca reformadas em yr_renovated.
  - Na coluna bathroom o valor 33 foi considerado como um erro de digitação e foi substituído por 3 nas análises.
  - Para valores de ID duplicados, apenas os mais recentes foram considerados.
  - As localidades e estação do ano foram decisivas para compra ou venda dos imóveis.
  
  
# 4. Planejamento e estratégia de solução:
#### Etapas para solucionar o problema de negócio:
- Coleta de dados via Kaggle
- Entendimento de negócio
- Tratamento de dados (Transformação de variaveis, limpeza, entendimento)
- Responder problemas do negócio
- Resultados para o negócio
- Conclusão

# 4.1 Produto Final
  - Relatório com as sugestões de compra do imóvel por um valor recomendado
  - Relatório com as sugestões de venda de um imóvel por um valor recomendado
  - Aplicativo contendo detalhes das casas e recomendações: https://lariguim-house-rocket-streamlit-app-akb1o2.streamlit.app/

# 5. Ferramentas
- Python 3.15
- Jupyter Notebook
- Streamlit
- Streamlit Cloud

# 6. Insights e análise das hipóteses (H) de negócio
- H1.Falso | Imoveis com vista para agua são aproximadamente 200% mais caros
- H2.Falso | Imóveis com data de construção não afeta o preço
- H3.Falso | Imoveis sem porão possuem area 18% maior que imoveis com porão
- H4.Falso | o crescimento YoY do preço é de 0,5%
- H5.Falso | O crescimento MoM dos imoveis com 3 banheiros no periodo analisado é de 12%
- H6.Falso | A diferença percentual de preços é de 4%
- H7.Falso | Casas com alto padrão de design sao aproximadamente 200% mais caras
- H8.Falso | Imoveis não reformados sao aproximadamente 40% mais baratos.

# 7. Resultados Finaneiros para o Negócio
Após a análise, dentre os 21.435 imóveis disponíveis para a compra na região de King Country, 3808 foram sugeridos para compra e detalhados em relatório.
Caso os imóveis sugeridos sejam comprados, o investimento inicial esperado é de $11,5 bilhões. 
Após a revenda de todos os imóveis, o lucro previsto é superior a 1,02 bilhões.


     
    
