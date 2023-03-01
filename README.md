# Aplicação de Machine Learning em um Caso de Churn


## :dart: Objetivo
Desenvolver conhecimentos de Machine Learning aplicado no mercado Financeiro através do Curso de Machine Learning da Alura, dataset de uma empresa de telecomunicações, onde foi solicitado ao Cientista de Dados que desenvolvesse um modelo de machine learning para que posssa Classificar seus clientes com a Taxa de Evasão de Clientes (Churn)

## :bookmark: Contexto
Muitas empresas de diversos segmentos adotam esta Métrica Churn por ser muito importante já que possibilita prever o comportamento para reter seus clientes, você pode analisar todos os dados relevantes do cliente e desenvolver programas de retenção focados no cliente. Esta métrica se torna tão mais necessária quando a receita da empresa depende do número de assinantes de uma plataforma, como por exemplo: Spotify, Zen. 

Este Dataset utilizado, consiste em dados limpos de atividade do cliente (features), juntamente com um rótulo de churn especificando se um cliente cancelou a assinatura, será usado para desenvolver modelos preditivos.
Churn é uma métrica utilizada para mostrar o número de clientes que cancelam serviço em um determinado período de tempo.


## :pushpin: Considerações do Dataset
Este conjunto de dados foi extraído do repositório Kaggle (Telecom Churn Dataset) dados reais, onde classifica as pessoas descritas por um conjunto de atributos como bons ou maus riscos de crédito.
- A Base de Dados utilizada neste exemplo foi a `dados/Customer-Churn.csv` já traduzidas, contendo 7043 registros;
- Variável Resposta `churn`, onde: 0 =  Cliente Continua | 1 =  Deixa de ser cliente
- A variável `default` é a nossa variável resposta, onde: 0 = Credito Não Concedido | 1 = Crédito Concedido;



## :computer: Conteúdo
O Projeto foi organizados nos seguintes tópicos para uma melhor organização e compressão:
1. Dataset - Lendo o Dataset e visualizando os dados;
2. Preparação dos dados de treino e teste (Split dos dados, Normalização);
3. Implementando o Modelo (KNN, BernoulliNB,DecisionTree)
5. Validação dos Modelos (MatrixConfusion, Accurance, Precision, Recall Scores);
6. Escolhendo o melhor Modelo;

## :closed_book: Conclusão
Agora, ao final deste case conseguimos responder o problema de negócio proposto: ***Qual modelo classifica melhor nossos clientes?***
Neste estudo foi decidido considerar a métrica de precisão que mede quantos valores positivos foram previstos de forma correta com um todo no nosso modelo. Lembrando que os verdadeiros positivos é o foco, aquele onde Churn =1. Sendo assim, é este Churn que precisamos dar atenção, é o Churn que temos que reduzir, são clientes que estão deixando a empresa, reduzindo seus ganhos.



## :bulb: Referências
[Churn Dataset Kaggle](https://www.kaggle.com/datasets/mnassrib/telecom-churn-datasets?select=churn-bigml-20.csv)
