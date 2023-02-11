# datascience

Estudo na área de Ciência de Dados para Desafio Cientista de Dados - Manutenção preventiva

Feito em Python via Google Colab https://colab.research.google.com/drive/1__251NvB_sU_S56XN1S9U6zwh10oo2kz?usp=sharing

Bibliotecas utilizadas foram majoritariamente Pandas e PyCarot, outras que foram instaladas mas podem não estar no projeto final pois acabaram sendo utilizadas somente para conferências e outras análises, sendo retiradas da apresentação final.

Variáveis de udi, product_id e type foram retiradas da etapa de treino e modelagem.
Foi utlizada a Classificação com base na coluna failure_type, transformada em Dummy. Depois, cada categoria de tipo de erro foi estuda de forma individual com o auxílio do PyCaret, onde os modelos selecionados foram:
KNN - simplicidade e fácil implementação, com bons resultados em diversas aplicações. Todavia roda mais devagar.
Regressão Logística - ótima opção para variáveis binárias, o que é o caso. 
Light Gradient Boosting Machine - constrói o modelo em etapas, se assemelha  a decision tree

Os 5 modelos diferentes ( um para cada um dos tipos de falha) foram salvos e depois aplicados ao dataset de teste.
Por fim o resultado unificada, o que, diferentemente dos arquivo inicial de Treino gerou resultados em que é possível ter probabilidade de mais de um tipo de falha para a mesma RowNumber.


