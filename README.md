Previsão de Estoque Inteligente na AWS com SageMaker Canvas:
Este projeto faz parte do Lab “Previsão de Estoque Inteligente na AWS com SageMaker Canvas”, proposto pela Digital Innovation One (DIO).
O objetivo do desafio é aplicar conceitos práticos de Machine Learning (ML) utilizando o Amazon SageMaker Canvas, uma ferramenta no-code que permite a criação de modelos preditivos sem a necessidade de programação.

Objetivo do Projeto:
Desenvolver e treinar um modelo de Machine Learning no Amazon SageMaker Canvas, explorando o uso de dados, definição de variáveis alvo, análise de métricas e geração de previsões, documentando todo o processo neste repositório.


Ferramentas Utilizadas:
Amazon Web Services (AWS)
Amazon SageMaker Canvas
GitHub

Etapas do Desenvolvimento
1. Seleção do Dataset
O dataset utilizado foi obtido a partir da pasta datasets do repositório base disponibilizado pela DIO.
Os dados foram importados diretamente no Amazon SageMaker Canvas, onde foi possível visualizar, validar e explorar as colunas disponíveis.

2. Construção e Treinamento do Modelo
No SageMaker Canvas, o dataset foi configurado definindo-se a coluna loan_status como variável alvo (Target Column).
O tipo de modelo selecionado foi 3+ Category Prediction, conforme recomendação automática da plataforma.

O treinamento foi realizado utilizando o modo Quick Build, permitindo a criação rápida do modelo sem necessidade de ajustes manuais ou programação.

3. Análise do Modelo
Após o treinamento, foram analisadas as métricas de desempenho fornecidas pelo SageMaker Canvas.
O modelo alcançou uma acurácia aproximada de 72,63%, indicando boa capacidade de previsão da variável alvo.

Também foi possível identificar as variáveis com maior impacto nas previsões, como:
loan_term
loan_amount
verification_status

4. Previsões
O modelo foi treinado utilizando o Amazon SageMaker Canvas, em ambiente privado da AWS, por meio do modo Quick Build.
Com o modelo treinado, foram realizadas previsões de estoque. Os resultados obtidos permitiram analisar padrões de demanda e auxiliar na tomada de decisão relacionada ao controle de estoque.

Conclusão
Este projeto demonstrou como o Amazon SageMaker Canvas possibilita a criação de modelos de Machine Learning de forma simples, rápida e acessível, mesmo para usuários sem experiência prévia em programação.
A experiência reforça o potencial das ferramentas no-code da AWS na aplicação prática de Machine Learning em cenários reais de negócio.

