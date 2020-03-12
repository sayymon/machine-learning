Aula 1 - 
No primeiro, criamos dados manualmente para entendermos o fluxo de treinamento e teste de um estimador que define qual a classe dos dados que estávamos analisando.

Geramos um conjunto de treino e outro de teste, e utilizamos um estimador simples, chamado LinearSVC (baseado em Support Vector Machines), para fazermos nossas previsões.

Ainda consultamos a documentação para conhecer uma variedade maior de estimadores, dentre os quais testamos três tipos diferentes, cada um com suas características.

Nesse primeiro projeto, aprendemos esse fluxo tradicional, e utilizamos uma medida para analisar o número de acertos (a acurácia) em classificações - que queríamos, obviamente, maximizar.

Em diferentes projetos, podemos utilizar estimadores, fontes de dados e medidas diferentes.

Aula 2 = 

Abrir arquivo CSV;
Imprimir as primeiras linhas com a função head;
Renomear as colunas;
Utilizar a função shape para ver a quantidade de elementos;
Separar dados para treino e teste;
Definir a ordem para os números aleatórios;
Utilizar a função value_counts.

No segundo projeto, utilizamos uma fonte de dados externa: uma tabela na qual cada linha representava um usuário. Com base nesses dados, tentamos prever se o usuário compraria ou não um determinado produto de um site.

Aprendemos a renomear colunas, trabalhamos algumas funcionalidades do Pandas e depois executamos o processo de treinamento. Também utilizamos a documentação para obtermos mais informações, separamos os dados de treino e de teste e estudamos a importância da aleatoriedade (SEED) na reprodutibilidade dos nossos experimentos.

Além disso, também abordamos a importância da estratificação para coletar um conjunto de testes e de treino que tivesse uma proporção próxima das classes trabalhadas.

Aula 3 - 

No terceiro projeto, utilizamos outro conjunto de dados em que trabalhamos com duas dimensões nas features e uma dimensão em Y (os resultados que queríamos prever). Com isso, ocorreu uma situação curiosa: conseguíamos plotar essas duas dimensões e visualizar esses dados de diversas maneiras diferentes, analisando as diferenças entre as decisões positivas (da classe 1) e negativas (da classe 0).

Descobrimos que e estimador com que estávamos trabalhando não era muito eficiente em comparação com nossa baseline, um estimador simples (construído manualmente) que previa o mesmo valor para todos os elementos.

Posteriormente, conhecemos o estimador SVC que apreende outros tipos de relacionamentos. Então, consultamos a documentação para conhecermos uma maior variedade de estimadores.

O estimadores SVC, assim como diveros outros, é muito afetado pelas escalas. Exatamente por isso, aprendemos como reescalar nossos dados (o conjunto de features no eixo x), mantendo a mesma classificação binária tradicional. O SVC, inclusive, é capaz de classificar mais de duas classes, se esse for um requisito do projeto.

Nós plotamos a decison boundary (curva de decisão) em duas dimensões para visualizarmos com clareza os processos do algorítimo.

Aula 4 e 5

Já no quarto e último projeto, utilizamos um outro tipo de estimador, mais transparente, que exibe para nós como as decisões estão sendo tomadas, ou seja, a árvore de decisão do algorítimo.

Aprendemos que algorítimos estimadores possuem parâmetros, por exemplo a profundidade máxima (max_depth). O LinearSVC, o SVC, o USG e diversos outros classificadores/estimadores também possuem parâmetros, e podemos ainda otimizá-los na prática.

No nosso caso, utilizamos um classificador que nos permite visualizar como as decisões do algorítimo são tomadas. Dessa forma, aprendemos uma gama de funcionalidades no processo de estudo dos dados. Isso pode ser transposto para o seu fluxo de trabalho, no qual você carrega os dados, os manipula, analisa visualmente e os explora (exploratory data analysis).


