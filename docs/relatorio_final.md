# Sleep Research


* Arthur Henrique Chaves Oliveira 
* Júlio Lage Alexandre
* Rhudson Douglas Mota Sampaio 
* Sara Alves Martins 
* Sophia Neves Alvim Ottoni 

---

Professores:

* Prof. Hugo Bastos de Paula 

---

_Curso de Ciência de Dados, Unidade Praça da Liberdade_

_Instituto de Informática e Ciências Exatas – Pontifícia Universidade de Minas Gerais (PUC MINAS), Belo Horizonte – MG – Brasil_

---

_**Resumo** Este estudo investiga a correlação entre a qualidade do sono e o desempenho acadêmico de estudantes universitários no Brasil. Baseando-se em dados de pesquisas acadêmicas e de saúde pública, examina-se como noites mal dormidas podem influenciar negativamente a produtividade em sala de aula e a saúde dos alunos. Os resultados destacam a necessidade de promover uma boa higiene do sono entre os estudantes como parte dos esforços para melhorar a qualidade da educação e o bem-estar geral da população. Enfoca-se a importância de conscientizar sobre os impactos do sono na educação e na vida dos alunos, ressaltando a necessidade de intervenções para melhorar os hábitos de sono e, consequentemente, os resultados acadêmicos._

---

## Introdução

Mesmo com todos os avanços científicos, técnicos e tecnológicos tidos na contemporaneidade, vários desafios mundiais estão em pauta, exigindo um trabalho colaborativo e global para serem minimizados. Sendo assim, a Organização das Nações Unidas (ONU) definiu, em 2015, 17 objetivos globais<sup>[1]</sup>. Dentre estes, tem um que objetiva a saúde e bem-estar e, embora não haja uma meta dentro dessa área que fale especificamente sobre o sono, estudos mostram que há uma relação muito forte entre esta necessidade fisiológica e a saúde humana. Entrando mais a fundo, em diversas estatísticas observa-se um comportamento esperado quando se analisa o desempenho em certas atividades - físicas e mentais - e os maus hábitos de dormir<sup>[2]</sup>. Assim, este estudo propõe investigar as possíveis associações entre desempenho acadêmico e padrões de sono, visando obter "insights" que possam ser transformados em conhecimento útil, baseado em dados, para ressaltar a importância de bons hábitos para extrair os benefícios da educação.

Em outras palavras, a investigação visa abranger tanto uma problemática do bem-estar e da saúde dos indivíduos quanto a interferência de um mau sono nas atividades acadêmicas. Pesquisas mostram que sociedades com melhor descanso tendem a ser mais prósperas<sup>[4]</sup>. Isso levanta a questão de se o sono realmente desempenha um papel tão significativo no desenvolvimento humano. Com isso, pretende-se alcançar estudantes universitários, já que são mais propícios a sofrerem com o problema devido a diversos fatores. Adicionalmente, há o intuito de investigar possíveis hábitos, como o de não praticar atividades físicas, com noites mal dormidas ou distúrbios de insônia<sup>[2]</sup>. E tudo isso para que seja possível o levante do problema e/ou a análise de possíveis intervenções. Assim, utilizando-se a metodologia "Knowledge Discovery in Database" (KDD) e seguindo as suas etapas, espera-se obter produtos pertinentes.

###    Contextualização

Esta questão do sono já é abordada em diversas pesquisas, tais quais indicam números alarmantes em relação à qualidade dos hábitos noturnos. 
Um exemplo, foi uma pesquisa feita na Universidade Federal de Pelotas (UFPel) por Carone et al. (2020), segundo ela: "Dos 1.865 estudantes, 32% apresentaram sono insuficiente nos dias de aula, 8,2% sono insuficiente nos finais de semana, 18,6% latência longa nos dias de aula, 17,2% latência longa nos finais de semana, 30% baixa qualidade autopercebida, 12,7% despertares noturnos e 32,2% sonolência diurna". 
Portanto, visualizando estes números pode-se notar um alto percentual de estudantes que possuem problemas noturnos, tanto nos dias letivos quanto nos finais de semana.

Outra pesquisa relevante feita por Tozer (2018) em que ele analisa a média de sono da população de diversos países, chegando a conclusão que países mais desenvolvidos possuem um tempo de sono maior.
Ademais, em sua pesquisa ele também analisa alguns fatos sobre a deprivação do sono, como por exemplo o fato de que uma pessoa que fique 20 horas consecutivas acordada tem o mesmo raciocínio e tempo de reação que alguem que bebeu 1 taça de vinho ou o fato de que pessoas que consistentemente dormem 6 horas por dia aumenta a chance de uma morte precoce em 13%. Essa deprivação do sono também pode extender seus impactos para um país inteiro como no caso do Japão, que 3% do seu produto interno bruto anual é afetado pela exaustão. 

Haja vista essas pesquisas, que ressaltam uma problemática contemporânea associada ao sono, o trabalho visa tratar tal questão na vida dos indivíduos, mostrando seus impactos e apontando relações. 
Os bons hábitos, como por exemplo a aderência de uma higiene do sono - uma série de comportamentos que equilibram o ciclo circadiano - estão atrelados a uma boa saúde, disposição, bem-estar, raciocínio, memória e desempenho esportivo, por exemplo. 
Sabendo disso, torna-se necessário abordar, mais especificamente, a relação entre a qualidade de sono e desempenho acadêmico, buscando observar se há associação entre ambos, em um mundo em que a educação assume um papel importante.

###    Problema

Tendo em vista o que foi apontado anteriormente, é de suma importância que seja analisado o sono dos alunos dos cursos de graduação de certas instituições de ensino. Portanto, devemos analisar os graduandos que estão tendo problemas com o descanso e como isso impacta a rotina e desempenho escolar. Esses impactos podem ocorrer de diversas formas, como: défict de atenção, diminuição da capacidade cognitiva (raciocínio mais lento e diminuição da memória), aumento da sonolência diurna, que levaria a perda de atenção nas aulas para o caso de estudantes dos cursos diurnos<sup>[2]</sup>. Sendo assim, podemos inferir que há uma associação entre a má qualidade do sono e a redução do rendimento acadêmico.

Se for levado em consideração que é na graduação que a maioria dos alunos passa por uma mudança de rotina repentina, com sobrecarga de atividades acadêmicas e grade de horários de aulas com longas janelas, e que é nela onde se desenvolve os principais hábitos praticados durante toda a vida adulta. Dessa forma, problemas como a sonolência diurna excessiva é uma importante questão de saúde pública e clínica, pois ela pode levar a reduções significativas na qualidade de vida, um aumento do risco de acidentes de trabalho e de trânsito, e poderá afetar a realização das tarefas da vida diária<sup>[2]</sup>. 

Ademais, o sono não afeta somento o dia a dia de uma pessoa, mas também pode alterar a economia de um país. A exemplo disso, temos países como Estados Unidos, Reino Unido, Alemanha, Japão e Canadá que possuem uma perda considerável no PIB anual, devido a falta de sono de seus trabalhadores. Essa perda pode ser causada de diversas formas, como o fato de que trabalhadores cansados são menos eficientes, têm mais chaces de faltar e são mais sucetíveis a doenças. Outra causa é que a falta de sono durante o período acadêmico afeta o desenvolvimento de habilidades, refletindo eventualmente no nível educacional do país e no mercado de trabalho<sup>[5]</sup>.

###    Objetivo geral

O objetivo geral deste trabalho é desenvolver um sistema inteligente para analisar bases de dados e a partir delas encontrar correlações que se traduzam em informações úteis sobre o sono e o desempenho acadêmico. Em outras palavras, o projeto busca identificar relação na qualidade do sono dos alunos dos cursos de graduação de certas instituições de ensino, com a finalidade de compreender a associação entre noites mal dormidas e a redução da produtividade em sala de aula e nos estudos independentes, além da redução significativa na qualidade de vida.

####    Objetivos específicos

Implementar algoritmos de análise de dados capazes de identificar padrões de sono e desempenho acadêmico entre os estudantes de diferentes cursos de graduação em determinadas instituições de ensino. (//ETL)

Este objetivo específico envolverá as seguintes etapas:

- Coleta e preparação dos dados: Recolher dados sobre o sono dos alunos, incluindo horas de sono, qualidade do sono, padrões de sono irregulares, entre outros, bem como dados sobre o desempenho acadêmico, como notas, frequência, e feedback dos professores.

- Pré-processamento dos dados: Limpar e organizar os dados coletados para garantir a consistência e a integridade, além de remover dados irrelevantes ou duplicados.

- Desenvolvimento de algoritmos de análise de dados: Utilizar técnicas de análise estatística e aprendizado de máquina para identificar correlações entre os padrões de sono dos alunos e seu desempenho acadêmico. Isso pode envolver técnicas como regressão linear, árvores de decisão, redes neurais, entre outras.

- Avaliação e validação dos resultados: Avaliar a eficácia dos algoritmos desenvolvidos em identificar padrões significativos de sono e desempenho acadêmico. Isso incluirá a comparação dos resultados obtidos com estudos prévios e a realização de testes estatísticos para verificar a significância das correlações identificadas.

###    Justificativas

O que motivou a escolha dessa temática foi, após leitura de estudos e também observações cotidianas, a consciência de que o sono é uma necessidade básica do ser humano e que, muitas vezes, é negligenciado. Um ciclo circadiano equilibrado é responsável por inúmeros benefícios e tem influência direta nas funções metabólcias humanas, e isso é apontado em diversas pesquisas científicas. Entretanto, inúmeros fatores fazem com que os indivíduos não consigam sustentar uma boa higiene do sono, impactando suas atividades diárias. O trabalho enfoca na perspectiva de sono no ramo acadêmico devido ao reconhecimento de padrões de baixo desempenho dos alunos com a má qualidade de descanso, e como isso pode afetar a educação do país e a vida profissional.

Considerando a relevância do sono para a saúde e o desempenho humano, sustenta-se o uso dos processos de KDD (Knowledge Discovery in Databases) e ETL (Extract, Transform, Load) como metodologias para a obtenção de conhecimento, permitindo a extração de dados e a geração de insights. Dessa forma, ao trabalhar com bases de dados selecionadas que se relacionam tanto diretamente quanto indiretamente com a temática do sono, é possível transformá-las em estatísticas relevantes. Com isso, as instituições de ensino poderão captar tais resultados, utilizando o conhecimento gerado por dados para conscientizar sobre a importância do sono na busca por melhores resultados educacionais.    

##    Público alvo

O projeto tem como público alvo universitários (de qualquer modalidade de curso) que estudem no Brasil, possuam mais de 18 anos, que se enquadrem em qualquer faixa de renda e morem em qualquer região do país.

### Diagrama de persona:

**Nome	:**	Lucas Martins  
**Gênero	:**	Masculino  
**Idade	:** 23  
**Cidade	:**	Belo Horizonte

**Bio:** 
Lucas é formado em ciência da computação e está atualmente fazendo uma pós em segurança da informação, trabalha como desenvolvedor de sistemas e mora sozinho no centro da cidade. 

**Objetivos:**
- Se formar em sua pós graduação. 
- Conseguir um melhor emprego, com um maior salário.

**Problemas:**
Dificuldades em se concentrar nas aulas devido à rotina exaustiva e falta de foco causada pela má qualidade de sono.

## Análise exploratórida dos dados

O projeto vai utilizar o dataset "Student Stress Factors" como sua fonte de dados principal. Este dataset busca relacionar variáveis que podem causar ou são causa de estresses.

Nele temos os seguintes atributos:

| Atributo | Descrição | Tipo de dado |
| ---------|-----------|--------------|
| Sleep Quality | Atributo que observa a autoavaliação que o estudante dá para seu sono | número inteiro |
| suffer headaches| Atributo que observa quantas vezes o aluno teve dor de cabeça na semana | número inteiro|
| academic performance | Atributo que observa a autoavaliação que o estudante dá para sua performance acadêmica | número inteiro|
| study load |Atributo que observa a nota que o estudante dá para sua grade curricular | número inteiro|
| How many times a week you practice extracurricular activities | Atributo que observa quantas vezes na semana o aluno pratica atividades extracurriculares | número inteiro|
| stress levels | Atributo que observa a nota que o estudante dá para seu nível de estress | número inteiro|

Para complementar e enriquecer a base principal temos o dataset "Student_Performance" que tem como objetivo examinar os fatores que influênciam a perfomance acadêmica. relacionar variáveis que podem causar ou são causa de estresses.

Nele temos os seguintes atributos:
| Atributo | Descrição | Tipo de dado |
| ---------|-----------|--------------|
| Hours Studied | Atributo que observa o número total de horas gastas estudando |  números inteiros|
| Previous Scores | Atributo que observa a nota obtida pelos estudantes em exames anteriores | números inteiros |
| Extracurricular Activities |  Atributo que observa se um aluno participa de atividades extracurriculares ou não | booleano |
|Sleep Hours | Atributo que observa o tempo médio de sono que um estudante tem por dia | números inteiros | 
| Sample Question Papers Practiced | Atributo que observa o número de questionários não obrigatórios realizados | número inteiro |
| Performance Index | atributo que observa a performance média de cada estudante | numero real|

###    Descrição de dados

Por meio de uma análise dos dados de ambas as tabelas, foi possivel observar relações já esperadas entre os dados, médias com valores significativos e algumas informações que poderiam ser consideradas estranhas.

Estas relações foram feitas por meio medias, valores mínimos e máximos para os tipos de dados inteiros, e uma separação de dados por meio da moda, quantidade de valores distintos(categorias). Além de uma análise de gráficos gerados por programas em python.

Para uma melhor análise dos dados [clique aqui.](https://github.com/ICEI-PUC-Minas-PPL-CD/ppl-cd-pcd-sist-int-2024-1-sleepresearch-2024-1/blob/main/assets/results/README.md)

## Preparação dos dados

### Seleção dos atributos

Os seguintes atributos das respectivas bases são indispensáveis ao se tratar de um projeto que visa a análise do relacionamento entre performance escolar e qualidade de sono, pois ter em mãos dados quantitativos e qualitativos que englobam esses dois aspectos é a base da pesquisa. 

- Tabela "Student Stress Factors.csv" (Principal):

	| Atributos | Motivo |
	| --------- | ------ |
	| Sleep Quality | Um dos atributos principais, pois nele temos a autoavaliação do estudante sobre sua qualidade de sono |
	| Suffer headaches| Podem-se procurar relações entre as dores de cabeça e disturbios do sono no geral |
	| Academic performance | Por se tratar da variável que nos mostra a performance academica de um aluno é interessante mantê-la |
	| Study load | Seria possível observar relações entre a carga horária da instituição e a performance |
	| Practice extracurricular activities | Alunos que fazem atividades extra curriculares podem ter performance acadêmica melhor que os demais |
	| Stress levels | É possivel relacionar o nível de stress dos alunos com o tempo de sono, carga acadêmica e atividades extracurriculares | 

- Tabela "Student_Performance.csv" (Enriquecimento):

	| Atributos | Motivo |
	| --------- | ------ |
	| Hours Studied |  essa coluna é essencial, é nela que se verifica quanto o aluno passou estudando, fortes correlações com `academic performance`, `Performance Index` podem ser realizadas |
	| Sleep Hours |  A colunas mais importante desta tabela, pode ser utilizada em correlações com `Sleep Quality` da tabela anterior | 
	| Extracurricular Activities |  Vai ser utilizado para relacionarmos com o campo `Practice extracurricular activities` |
	| Previous Scores | Atributo importante pois com ele conseguimos ter uma ideia da nota do aluno anterior, podendo assim medir a capacidade do mesmo |
    | Sample Question Papers Practiced | Atributo que poderá ser utilizado futuramanente para saber o nível de dedicação do estudante |
	| Performance Index | Um dos atributos principais da tabela, com ele é possivel analisar a performance do estudante, além de que é possivel realizar correlações com `academic performance` |

Os demais atributos foram julgados desnecessários, pois são redundantes ou não acrescentam informações de maneira significativa.

### Tratamento dos valores faltantes ou omissos 

#### Student stress factors: 

A ausência de valores faltantes em uma tabela pode ser atribuída ao contexto em que os dados foram coletados, particularmente quando se trata de informações de um questionário. A estrutura do formulário normalmente não permite respostas em branco, pois cada pergunta é projetada para eliciar uma resposta específica, seja numérica, qualitativa ou de múltipla escolha. Essa característica intrínseca dos questionários ajuda a garantir que os dados coletados estejam completos e livres de lacunas, resultando em uma tabela sem valores faltantes. Cada célula da tabela corresponde a uma resposta fornecida pelo respondente, refletindo a totalidade das informações coletadas durante o processo de coleta de dados. Como resultado, a integridade dos dados na tabela é preservada, fornecendo uma base sólida para análises subsequentes. A transparência e a confiabilidade dos resultados obtidos a partir desses dados são reforçadas pela ausência de valores faltantes, evidenciando a robustez do questionário como instrumento de pesquisa.

#### Student performance: 

A tabela secundária “Student performance” não precisa passar por tratamento de dados omissos, já que não os possui por se tratar de uma base de dados sintética, ou seja, foi gerada artificialmente e projetada originalmente para que todos os atributos sejam devidamente preenchidos pelo algoritmo.

### Tratamento dos valores inconsistentes

#### Student stress factors: 

A ausência de valores inconsistentes na tabela principal pode ser atribuída à presença de faixas bem definidas para cada atributo. As pontuações estão em intervalos específicos e bem definidos, o que reflete em uma classificação clara e consistente em relação à intensidade de cada fator. Com essa abordagem estruturada valores discrepantes ou outliers são evitados, caso contrário, a análise poderia ser distorcida. Com faixas pré-determinadas sendo estabelecidas para a pontuações, os dados se mantêm alinhados com a metodologia adotada, facilitando interpretações e correlações entre os diferentes atributos apresentados.

#### Student performance: 

Esta tabela trata cada linha como se fosse individuos diferentes, por causa disso não existe problema na existência de valores duplicados, pois um aluno pode ter valores iguais a um outro. Além disso, a tabela, que já é sintética, define valores mínimos e máximos para cada campo, extinguindo assim a possibilidade da existência de um outlier.

### Conversão de dados

Primeiramente, é importante ressaltar que é incondizente unir os atributos das bases que foram escolhidas como principal e secundária, uma vez que elas, embora tratem de uma mesma dimensão, têm diferentes abordagens - uma mostra o valor bruto, além de ser sintética, enquanto a outra é uma autoavaliação com valores reais. Por isso, foi escolhido fazer uma relação por meio de voto, em que há uma mesma pergunta para ambas as bases. No entanto, os métodos para chegar em uma resposta seriam pensados em casos isolados para ambas as bases.

Na base principal "Student_stress_factors", há seis atributos, que são referentes à qualidade do sono, dor de cabeça, performance acadêmica, carga horária de estudo, atividades extracurriculares e ao nível de estresse. Estes são atributos que informam a autoavaliação de cada aluno de 1 a 5, em que 1 se traduz em um índice baixo, e 5 a um índice alto. Foi decidido não fazer o descarte ou alteração de nenhum desses atributos, uma vez que todos estão limpos e apresentam relevância para o problema. Já na base secundária "Student_performance", há os seguintes atributos: "Hours studied", "Previous score", "Extracurricular activities", "Sleep hours", "Sample Question Papers Practiced" e "Performance Index". Todos estes são úteis para se chegar em informações, mas há algumas possíveis alterações que podem ser feitas, como formar faixas que mostrem categorias. 

Foi preparado uma base de dados onde trocamos os valores de "Extracurricular activities" para o tipo booleano e o tipo da coluna "Performance Index" de float para int, essa tabela chama [performance_data_converted](../assets/data/performance_data_converted.csv). As tabelas abaixo foram baseadas nesta.

A tabela [performance_data_convertido_por_faixas](../assets/data/performance_data_convertido_por_faixas.csv) é a tabela em que convertemos todos os valores para uma faixa deles que variava de 1 a 5, ou seja, transformamos os dados em categóricos.

Já na tabela [performance_data_convertido_por_faixas_sem_Previous](../assets/data/performance_data_convertido_por_faixas_sem_Previous.csv) é identica a tabela anterior, a única diferença esta na retirada da coluna "Previous Scores".

Por ultimo, a tabela [performance_data_Index_convertido_por_faixas](../assets/data/performance_data_Index_convertido_por_faixas.csv), que foi definida como a tabela final com qual trabalhariamos, foi alterado para valores em faixa apenas a coluna "Performance Index".

## Indução de modelos

### Modelo 1: KNN (K-Nearest Neighbors)

O modelo escolhido foi o KNN, pois é um algoritmo supervisionado de categorização. Esse modelo permite gerar agrupamentos por categoria a partir do conjunto de dados, possibilitando a extração de informações úteis com base nos resultados obtidos.

Foi utilizado cross validation para amostragem de dados da seguinte maneira: Utilizando os parametros knn, (modelo utilizado) data,(tabela) e data['academic performance'], (dado a ser avaliado) repartiu-se o dataset em 5 partes, 4 usadas parar teste e 1 usada para testar o resultado, alternando-se cada parte pode forma cruzada por 5 vezes, para que assim se pudesse observar o acurancy de 100%. Foi feita da mesma forma com o modelo da segunda tabela, adquirindo-se uma precisão de 94%.

Para podermos utilizar o KNN corretamente é preciso antes normalizar os dados presentes no dataset, para isso utiliza-se a função standard scaler.

![Normalização tabela 1](./imagens/modelo1/tabela1/normalização_t1.png)

![Normalização tabela 2](./imagens/modelo1/tabela2/normalização_t2.png)	

Agora, usamos a função `train_test_split` para separar os dados de treino dos dados de teste e, após isso, utilizamos esses dados no KNN com o numero de vizinhos definido como 1.

![KNN tabela 1](./imagens/modelo1/tabela1/knn_n=1_t1.png)

![KNN tabela 2](./imagens/modelo1/tabela2/knn_n=1_t2.png)

Como o número de vizinhos ideal pode variar de acordo com cada tabela devemos descobrir o numero ideal para cada uma delas. Para isso refazemos o processo do KNN dentro de um for que incrementa os valores de uma variavel `i` de 1 a 40, essa variável é utilizada como parâmetro do número de vizinhos. Após esse for é plotado um gráfico que nos mostra as taxas de erro para cada número de vizinhos.

![error rate tabela 1](./imagens/modelo1/tabela1/error_rate_t1.png)

![gráfico tabela 1](./imagens/modelo1/tabela1/error_rate_graph_t1.png)

Tabela 2:

![error rate tabela 2](./imagens/modelo1/tabela2/error_rate_t2.png)

![gráfico tabela 2](./imagens/modelo1/tabela2/error_rate_graph_t2.png)

O KNN é novamente feito após a descoberta do melhor número de vizinhos, utilizando o melhor encontrado.

![KNN2 tabela 1](./imagens/modelo1/tabela1/knn_n=3_t1.png)

![KNN2 tabela 2](./imagens/modelo1/tabela2/knn_n=38_t2.png)

Por último, para validarmos os modelos, utilizamos metodo de Cross validation.

![Cross validation tabela 1](./imagens/modelo1/tabela1/cross_validation_t1.png)

![Cross validation tabela 2](./imagens/modelo1/tabela2/cross_validation_t2.png)

### Modelo 2: Árvore de decisão

O modelo escolhido foi a árvore de decisão, que é um algoritmo de aprendizado de máquina supervisionado utilizado para classificação e regressão. No contexto do problema apresentado, a árvore de decisão foi escolhida por ser adequada para lidar com dados numéricos e categóricos, como os presentes nos datasets "Student Stress Factors.csv" e "Student_Performance.csv". A árvore de decisão permite identificar padrões nos dados, dividindo-os em subconjuntos menores com base em características relevantes, o que facilita a interpretação dos resultados e a tomada de decisões.

A árvore de decisão é um modelo adequado para este problema por várias razões:

Interpretabilidade: As árvores de decisão são altamente interpretáveis, permitindo visualizar as regras de decisão aprendidas pelo modelo. Isso é crucial para entender os fatores que contribuem para o estresse do aluno e o desempenho acadêmico.

Lidar com Dados Numéricos e Categóricos: As árvores de decisão podem lidar com uma mistura de dados numéricos (por exemplo, "Horas de Estudo", "Pontuações Anteriores") e categóricos (por exemplo, "Atividades Extracurriculares"). Isso é importante, pois os conjuntos de dados contêm ambos os tipos de dados.

Não Linearidade: As árvores de decisão podem capturar relações não lineares entre as variáveis, o que pode ser importante para modelar relações complexas entre os fatores de estresse, o desempenho acadêmico e outros atributos dos alunos.

Seleção Automática de Recursos: As árvores de decisão realizam implicitamente a seleção de recursos, identificando as variáveis mais importantes para a previsão. Isso pode ajudar a identificar os principais fatores que influenciam o estresse e o desempenho dos alunos.

Fácil Implementação: As árvores de decisão são relativamente simples de implementar e entender, tornando-as uma boa escolha para este problema.

Árvore da primeira tabela (academic performance):

Primeiramente foi feita a normalização dos dados do dataset utilizando a função standard scaler.

![Standard Scaler tabela 1](https://github.com/ICEI-PUC-Minas-PPL-CD/ppl-cd-pcd-sist-int-2024-1-sleepresearch-2024-1/blob/main/docs/imagens/modelo2/Tabela1/Standard.jpeg?raw=true)

Após isso, um novo dataset foi gerado com o nome df_parm com os dados normalizados, excluindo a coluna academic performance, pois é a que será prevista. 

![Parâmetros tabela 1](https://github.com/ICEI-PUC-Minas-PPL-CD/ppl-cd-pcd-sist-int-2024-1-sleepresearch-2024-1/blob/main/docs/imagens/modelo2/Tabela1/Parametros.jpeg?raw=true)

Foram separados 25% dos dados da tabela para teste e 75% para treinamento utilizando a função `train_test_split`.

![Treinamento tabela 1](https://github.com/ICEI-PUC-Minas-PPL-CD/ppl-cd-pcd-sist-int-2024-1-sleepresearch-2024-1/blob/main/docs/imagens/modelo2/Tabela1/Treinamento.jpeg?raw=true)

Plotagem da árvore de decisão:

![Plotando a árvore tabela 1](https://github.com/ICEI-PUC-Minas-PPL-CD/ppl-cd-pcd-sist-int-2024-1-sleepresearch-2024-1/blob/main/docs/imagens/modelo2/Tabela1/Plot_arvore.jpeg?raw=true)

![Árvore tabela 1](https://github.com/ICEI-PUC-Minas-PPL-CD/ppl-cd-pcd-sist-int-2024-1-sleepresearch-2024-1/blob/main/docs/imagens/modelo2/Tabela1/Arvore.jpeg?raw=true)

Para que se obtivesse uma melhor visualização, a árvore de decisão também foi plotada em formato docs. 

![Plotando em docs tabela 1](https://github.com/ICEI-PUC-Minas-PPL-CD/ppl-cd-pcd-sist-int-2024-1-sleepresearch-2024-1/blob/main/docs/imagens/modelo2/Tabela1/Plot_dot.jpeg?raw=true)

Logo após, foram feitos a matriz de confusão e um heatmap, utilizado para validar o modelo.

![Matriz tabela 1](https://github.com/ICEI-PUC-Minas-PPL-CD/ppl-cd-pcd-sist-int-2024-1-sleepresearch-2024-1/blob/main/docs/imagens/modelo2/Tabela1/Matriz.jpeg?raw=true)

Plotagem do heatmap: 

![Plotando heatmap tabela 1](https://github.com/ICEI-PUC-Minas-PPL-CD/ppl-cd-pcd-sist-int-2024-1-sleepresearch-2024-1/blob/main/docs/imagens/modelo2/Tabela1/Plot_heatmap.jpeg?raw=true)

![Heatmap tabela 1](https://github.com/ICEI-PUC-Minas-PPL-CD/ppl-cd-pcd-sist-int-2024-1-sleepresearch-2024-1/blob/main/docs/imagens/modelo2/Tabela1/Heatmap.jpeg?raw=true)



Árvore da segunda tabela (student stress factor):

Para a segunda árvore, o mesmo processo foi feito, começando pela normalização com a função standard scaler.

![Standard scaler tabela 2](https://github.com/ICEI-PUC-Minas-PPL-CD/ppl-cd-pcd-sist-int-2024-1-sleepresearch-2024-1/blob/main/docs/imagens/modelo2/Tabela2/StandardScaler2.jpeg?raw=true)

Um novo dataset foi gerado com o nome df_parm com os dados normalizados, excluindo a coluna academic performance, pois é a que será prevista.

![Parâmetros tabela 2](https://github.com/ICEI-PUC-Minas-PPL-CD/ppl-cd-pcd-sist-int-2024-1-sleepresearch-2024-1/blob/main/docs/imagens/modelo2/Tabela2/Parametros2.jpeg?raw=true)

Foram separados 25% dos dados da tabela para teste e 75% para treinamento utilizando a função `train_test_split`.

![Treinamento tabela 2](https://github.com/ICEI-PUC-Minas-PPL-CD/ppl-cd-pcd-sist-int-2024-1-sleepresearch-2024-1/blob/main/docs/imagens/modelo2/Tabela2/Treinamento2.jpeg?raw=true)

Plotagem da árvore:

![Plotando a árvore tabela 2](https://github.com/ICEI-PUC-Minas-PPL-CD/ppl-cd-pcd-sist-int-2024-1-sleepresearch-2024-1/blob/main/docs/imagens/modelo2/Tabela2/Plot_arvore2.jpeg?raw=true)

![Árvore tabela 2](https://github.com/ICEI-PUC-Minas-PPL-CD/ppl-cd-pcd-sist-int-2024-1-sleepresearch-2024-1/blob/main/docs/imagens/modelo2/Tabela2/Arvore2.jpeg?raw=true)

Foi também plotada a segunda árvore em formato docs.

![Plotando em docs tabela 2](https://github.com/ICEI-PUC-Minas-PPL-CD/ppl-cd-pcd-sist-int-2024-1-sleepresearch-2024-1/blob/main/docs/imagens/modelo2/Tabela2/Plot_dot2.jpeg?raw=true)

Por fim, foi feita a plotagem da matriz de confusão e a validação do modelo utilizando o heatmap.

![Matriz tabela 2](https://github.com/ICEI-PUC-Minas-PPL-CD/ppl-cd-pcd-sist-int-2024-1-sleepresearch-2024-1/blob/main/docs/imagens/modelo2/Tabela2/Matriz2.jpeg?raw=true)

Plotagem do heatmap:

![Plotando o heatmap tabela 2](https://github.com/ICEI-PUC-Minas-PPL-CD/ppl-cd-pcd-sist-int-2024-1-sleepresearch-2024-1/blob/main/docs/imagens/modelo2/Tabela2/Plot_heatmap2.jpeg?raw=true)

![Heatmap tabela 2](https://github.com/ICEI-PUC-Minas-PPL-CD/ppl-cd-pcd-sist-int-2024-1-sleepresearch-2024-1/blob/main/docs/imagens/modelo2/Tabela2/Heatmap2.jpeg?raw=true)



## Resultados

### Resultados obtidos com o modelo 1.

#### Resultados antes do ajuste de vizinhos:

![ClassReport tabela 1](./imagens/modelo1/tabela1/Classification_Report_t1.png)
![Confusion Matrix tabela 1](./imagens/modelo1/tabela1/Matriz_Confusao_graph_t1.png)

Tabela 2:

![ClassReport tabela 2](./imagens/modelo1/tabela2/Classification_report_n1_t2.png)

![Confusion Matrix tabela 2](./imagens/modelo1/tabela2/Matriz_confusao_n1_t2.png)

#### Resultados após do ajuste de vizinhos:

![ClassReport tabela 1 apos ajuste](./imagens/modelo1/tabela1/Classification_Report_t1.png)
![Confusion Matrix tabela 1 apos ajuste](./imagens/modelo1/tabela1/Matriz_Confusao_graph_t1.png)

Tabela 2:

![ClassReport tabela 2](./imagens/modelo1/tabela2/Classification_report_n38_t2.png)
![Confusion Matrix tabela 2](./imagens/modelo1/tabela2/Matriz_confusao_n38_t2.png)

### Interpretação do modelo 1

#### Descrição dos Parâmentros Utilizados

O código desenvolvido envolve parâmetros que desempenham funções cruciais na análise dos dados e no treinamento do modelo KNN.

- **Parâmetros gerais:**

	 - **random_state:** Este parâmetro define a semente para o gerador de números aleatórios, garantindo a reprodutibilidade dos resultados em diferentes execuções. Um valor específico (por exemplo, 42) garante divisões de dados e comportamento do modelo consistentes.

- **Parâmetros de Pré-processamento de Dados:**

	- **StandardScaler:** Este parâmetro normaliza as características padronizando-as, garantindo que tenham média zero e desvio padrão de um. Isso evita que características com escalas maiores dominem o aprendizado do modelo.

- **Parâmetros de Treinamento do Modelo:**

	- **KNeighborsClassifier:** É uma classe que implementa o algoritmo k-Nearest Neighbors para classificação.

		- n_neighbors (padrão 1): Este parâmetro especifica o número de vizinhos mais próximosa serem considerados ao fazer previsões. Um valor maior considera mais vizinhos, potencialmente aumentando a precisão, mas com o contra de um custo computacional maior.

	- **train_test_split:** Esta função divide os dados em conjuntos de treinamento e teste, permitindo que o modelo aprenda com um conjunto e avalie seu desempenho no outro.

	- **test_size (Padrão 0.25):** este parâmetro determina a proporção de dados alocados ao conjunto de teste. Um valor mais alto aumenta o tamanho do conjunto de teste, fornecendo mais dados para avaliação, mas reduzinho o tamanho do conjunto de treinamento.

- **Parâmetros de Avaliação:**

	- **classification_report:** Esta função gera um relatório detalhado do desempenho de classificação do modelo, incluindo precisão e suporte para cada classe.

	- **confusion_matrix:** Esta função cria uma matriz que visualiza a distribuição de previsões corretas e incorretas entre as classes.

	- **cross_val_score:** Esta função realiza validação cruzada, avaliando o desempenho do modelo em várias divisões aleatórias dos dados.
		- cv (Padrão: 5): Este parâmetro especifica o número de dobras para validação cruzada. Quanto mais alto o valor, mais confiável é a avaliação.

- **Parâmetros de visualização:**
	- **plotly.express.scatter:** Esta função cria um gráfico de dispersão que visualiza a relação entre as variáveis.

		- x: Este parâmetro especifica os dados a serem plotados no eixo x.

		- y: Este parâmetro especifica os dados a serem plotados no eixo y.

	- **color:** Este parâmetro atribui cores aos pontos de dados com base em uma variável especificada.

		- symbol: Este parâmetro atribui símbolos aos pontos de dados com base em uma variável especificada.

		- labels: Este parâmetro define rótulos para o eixo x e a legenda de cores.

- **Observações:**

	- O código utiliza bibliotecas para manipulação de dados, visualização e aprendizado de máquina, incluindo pandas, numpy, seaborn, matplotlib, plotly, cufflinks e sklearn.
	- O pré-processamento garante que o formato dos dados esteja adequado para que o modelo aprenda de forma eficaz.
	- O treinamento divide os dados em conjuntos de treinamento e teste.
	- Após estes processos, o desempenho do modelo é avaliado usando métricas como relatório de classificação, matriz de confusão e validação cruzada.
	- A etapa de visualização é usada para interpretar resultados do modelo e identificar padrões nos dados.
	



### Resultados obtidos com o modelo 2.

Resultados da tabela 1:

![Resultados tabela 1](https://github.com/ICEI-PUC-Minas-PPL-CD/ppl-cd-pcd-sist-int-2024-1-sleepresearch-2024-1/blob/946cdecd9e7cc7874c62db4294e7c62929e95515/docs/imagens/modelo2/Tabela1/parametrosmode2.png?raw=true)

Resultados da tabela 2: 

![Resultados tabela 2](https://github.com/ICEI-PUC-Minas-PPL-CD/ppl-cd-pcd-sist-int-2024-1-sleepresearch-2024-1/blob/946cdecd9e7cc7874c62db4294e7c62929e95515/docs/imagens/modelo2/Tabela2/Parametrotabela2.png?raw=true)


### Interpretação do modelo 2

O código desenvolvido envolve parâmetros que desempenham funções cruciais na análise dos dados e no treinamento do modelo de Árvore de Decisão. Além disso, apresentamos as regras que são utilizadas no processo de raciocínio do sistema inteligente e utilizamos medidas como `feature importances` para entender quais atributos o modelo se baseia na tomada de decisão.

- **Parâmetros Gerais:**
  - **random_state:** Este parâmetro define a semente para o gerador de números aleatórios, garantindo a reprodutibilidade dos resultados em diferentes execuções. No caso deste modelo, foi utilizado `random_state=1`.

- **Parâmetros de Pré-processamento de Dados:**
  - **StandardScaler:** Este parâmetro normaliza as características padronizando-as, garantindo que tenham média zero e desvio padrão de um. Isso evita que características com escalas maiores dominem o aprendizado do modelo.

- **Parâmetros de Treinamento do Modelo:**
  - **DecisionTreeClassifier:** É uma classe que implementa o algoritmo de árvore de decisão para classificação.
    - **criterion (Padrão 'gini'):** Este parâmetro especifica a função de medida de qualidade da divisão. 'gini' para o índice de Gini e 'entropy' para a entropia da informação.

- **Processo de Raciocínio e Feature Importances:**
  - **plot_tree:** Esta função visualiza a estrutura da árvore de decisão, mostrando as divisões em cada nó com base nos atributos mais importantes.
    - **filled:** Este parâmetro habilita o preenchimento das células com cores baseadas na classe majoritária.
    - **rounded:** Este parâmetro habilita as bordas arredondadas das células.
    - **special_characters:** Este parâmetro permite caracteres especiais na visualização.
  - **feature_importances_:** Este atributo do modelo de árvore de decisão fornece um array de importâncias das características, indicando a relevância de cada atributo no processo de tomada de decisão.
    ```python
    importances = clf.feature_importances_
    feature_names = data.drop('academic performance', axis=1).columns
    feature_importances = pd.DataFrame(importances, index=feature_names, columns=['importance']).sort_values(by='importance', ascending=False)
    ```

- **Parâmetros de Avaliação:**
  - **classification_report:** Esta função gera um relatório detalhado do desempenho de classificação do modelo, incluindo precisão e suporte para cada classe.
  - **confusion_matrix:** Esta função cria uma matriz que visualiza a distribuição de previsões corretas e incorretas entre as classes.

- **Parâmetros de Visualização:**
  - **plot_tree:** Esta função visualiza a estrutura da árvore de decisão.
    - **filled:** Este parâmetro habilita o preenchimento das células com cores baseadas na classe majoritária.
    - **rounded:** Este parâmetro habilita as bordas arredondadas das células.
    - **special_characters:** Este parâmetro permite caracteres especiais na visualização.
  - **Graphviz Export:** Exporta a árvore de decisão para um formato visual usando Graphviz.
    - **feature_names:** Este parâmetro especifica os nomes das características (colunas) usadas na árvore.
    - **class_names:** Este parâmetro especifica os nomes das classes alvo.

- **Observações:**
  - O código utiliza bibliotecas para manipulação de dados, visualização e aprendizado de máquina, incluindo pandas, numpy, seaborn, matplotlib, sklearn e graphviz.
  - O pré-processamento garante que o formato dos dados esteja adequado para que o modelo aprenda de forma eficaz.
  - O treinamento divide os dados em conjuntos de treinamento e teste.
  - Após estes processos, o desempenho do modelo é avaliado usando métricas como relatório de classificação e matriz de confusão.
  - A etapa de visualização é usada para interpretar resultados do modelo e identificar padrões nos dados.

## Análise comparativa dos modelos

Discuta sobre as forças e fragilidades de cada modelo. Exemplifique casos em que um
modelo se sairia melhor que o outro. Nesta seção é possível utilizar a sua imaginação
e extrapolar um pouco o que os dados sugerem.


### Distribuição do modelo (opcional)

Tende criar um pacote de distribuição para o modelo construído, para ser aplicado 
em um sistema inteligente.


## 8. Conclusão

Apresente aqui a conclusão do seu trabalho. Discussão dos resultados obtidos no trabalho, 
onde se verifica as observações pessoais de cada aluno.

Uma conclusão deve ter 3 partes:

   * Breve resumo do que foi desenvolvido
	 * Apresenação geral dos resultados obtidos com discussão das vantagens e desvantagens do sistema inteligente
	 * Limitações e possibilidades de melhoria


# REFERÊNCIAS

**[1]** - _ONU. **Sobre o nosso trabalho para alcançar os Objetivos de Desenvolvimento Sustentável no Brasil**. Disponível em: <https://brasil.un.org/pt-br/sdgs>. Acesso em: 25 mar. 2024._

**[2]** - _PEREIRA, Ana Raquel do Souto. **Hábitos de sono em estudantes universitários**. 84 f.Dissertação (Mestrado em Ciências Farmacêuticas) - Faculdade de Ciências da Saúde, Universidade Fernando Pessoa, Porto, 2013. Disponível em: <http://hdl.handle.net/10284/4079>. Acesso em: 21 mar. 2024._

**[3]** - _TOZER, James. Which countries get the most sleep?. **The Economist - 1843 magazine**. 1 mar. 2018. Disponível em: <https://www.economist.com/1843/2018/03/01/which-countries-get-the-most-sleep>. Acesso em: 23 mar. 2024._

**[4]** - _CARONE, Caroline Maria de Mello; Silva, Bianca Del Ponte da; Rodrigues, Luciana Tovo; Tavares, Patrice de Souza; Carpena, Marina Xavier; Santos, Iná S. Fatores associados a distúrbios do sono em estudantes universitários. **Cadernos de Saúde Pública 2020**, v.36, n.3, mar. 2020. Disponível em: <https://cadernos.ensp.fiocruz.br/ojs/index.php/csp/article/view/7325>. Acesso em: 21 mar. 2024._

**[5]** - _CALEIRO, João Pedro. Sua falta de sono está tirando bilhões da economia. **exame.**. dez. 2016. Disponível em: <https://exame.com/economia/sua-falta-de-sono-esta-tirando-bilhoes-da-economia/amp/>. Acesso em: 25 mar. 2024._

# APÊNDICES

**Colocar link:**

Do código (armazenado no repositório);

Dos artefatos (armazenado do repositório);

Da apresentação final (armazenado no repositório);

Do vídeo de apresentação (armazenado no repositório).
