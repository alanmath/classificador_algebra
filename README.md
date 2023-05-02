# Modelo classificador de fatores de rico para AVC
## Análise de fatores de risco para ter AVC, utilizando o dataset do Kaggle, arvore de decisão e gradiente descendente.
### Resumo
O presente trabalho consistiu na manipulação de dados do dataset "stroke prediction", presente no kaggle. Foi escolhido um subset equilibrado dos dados, para permitir o treinamento de dois modelos classificatórios: gradiente descendente e árvore de decisão. Para tanto foi utilizada uma implementação própria do algoritmo descendente, a versão do sklearn (para comparar com o modelo implementado) e a “decision tree” do sklearn. Para tanto, todos os dados numéricos foram categorizados e postos na forma de “one hot encoding”.  

A partir da análise dos vetores de peso e importância das features, percebeu-se uma grande influência do fator idade (idoso, seguido de adulto), já ter fumado e apresentar um quadro de hipertensão. Apesar de alguns fatores serem conhecidos na literatura, a quantidade de dados disponíveis foi diminuta, de modo que a análise precisa de ser refinada, tendo em vista que fatores como “nível médio de glicose normal” figura como um fator de peso, o que vai de encontro com a literatura e mesmo o senso comum. 


### Como instalar?  
Para garantir o funcionamento da aplicação é recomedado a criação de um ambiente virtual (venv) para instalar as dependência, como apresentado em https://docs.python.org/3/library/venv.html. Para esse projeto foi utilizado o python 3.8.10  
Em seguida, deve-se ativar o ambiente virtual e instalar as dependências através do comando:  
```pip install -r requirements.txt```

Protinho agora é só rodar o arquivo em sua IDE ou Jupyter notebook.


### Referências 
Artigo citado ao fim:  

https://www.ahajournals.org/doi/full/10.1161/CIRCULATIONAHA.114.010942
