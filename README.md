# Projeto de classificação de empréstimo

<figure>
  <img src="./imagens/emprestimo1.jpg " alt="Figura 1" />
</figure>

## Observações
* Este projeto teve o intuito de simular um cenário para classificar se um cliente será aprovado ou não para um empréstimo.

* Sinta-se à vontade para olhar todo o código e análises feitas.

## Planejamento da solução
1. Carregar o conjunto de dados
2. Observar e tratar os dados
3. Criar hipóteses
4. Analisar os dados
5. Validar o rejeitar as hipóteses
6. Analisar a correlação entre as variáveis
7. Preparar os dados
8. Estimar o modelo de aprendizado de máquina
9. Tirar conclusões

## Projeto

Esse projeto teve o intuito de fazer a análise de fatores que podem influenciar na obtenção de empréstimo em um determinada empresa. A empresa fictícia é a Empréstimo Fácil S.A que tem como objetivo avaliar as pessoas para saber se deve ou não conceder o empréstimo. Seu CEO queria uma forma melhor de fazer essa avaliação, já que atualmente eles usam o método de entrevista apenas. Esse projeto tem o objetivo de automatizar isso.

Esse projeto começou com a obtenção dos dados, uma breve análise para poder descrever os dados, usando estatística descritiva para conhecer melhor os dados. Terminada essa parte  foram criadas algumas hipóteses de senso comum sobre empréstimo.

Com as hipóteses prontas, foi feita a análise exploratória dos dados em 3 partes: Na primeira, com anaĺise univariada, como pode ser visto na Figura 1 e Figura 2. Em segundo momento com análise bivariada, como pode ser visto na Figura 3 e por último com a análise multivariada, como pode ser visto na Figura 4

<figure>
  <img src="/assets/images/emprestimo1.png " alt="Figura 1" />
  <figcaption>Figura 1. Análise univariada da variável resposta do projeto.</figcaption>
</figure>

<figure>
  <img src="/assets/images/emprestimo2.png " alt="Figura 2" />
  <figcaption>Figura 2. Análise univariada das variáveis categóricas.</figcaption>
</figure>

<figure>
  <img src="/assets/images/emprestimo3.png " alt="Figura 3" />
  <figcaption>Figura 3. Análise bivariada avaliando se ensino superior é um fator relevante para conseguir o empréstimo.</figcaption>
</figure>


<figure>
  <img src="/assets/images/emprestimo4.png " alt="Figura 3" />
  <figcaption>Figura 4. Análise multivariada das variáveis categóricas.</figcaption>
</figure>


Depois de verificar diferentes hipóteses entramos na preparação dos dados para criação dos modelos de machine learning. O modelo escolhido foi o de regressão logística, que é um modelo de classificação Com as etapas anteriores chegamos a um modelo final de regressão logística que nos deu previsões como na Figura 5.

<figure>
  <img src="/assets/images/emprestimo5.png " alt="Figura 1" />
  <figcaption>Figura 5. Previsão do modelo.</figcaption>
</figure>

Foi analisado outras bibliotecas de Python para a criação do modelo, nos dando uma acurácia final de 85,25%

Por último foi testado o modelo com dados de validação onde o mesmo retornou valores que estão na Figura 6


<figure>
  <img src="/assets/images/emprestimo6.png " alt="Figura 1" />
  <figcaption>Figura 6. Previsão do modelo com dados de validação.</figcaption>
</figure>

o notebook com todas as etapas está [aqui](https://github.com/fhfraga/loan_predict/blob/master/previsao_emprestimo.ipynb)

## Conclusão
Conclui-se com esse projeto que a automatização ajudará o CEO da Empréstimo Fácil S.A a ter um maior acerto na hora de dar o empréstimo.
