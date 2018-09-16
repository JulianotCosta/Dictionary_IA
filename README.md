
# Dictionary of Artificial Intelligence
## by Juliano Costa - Data Scientist student

Linkedin: https://www.linkedin.com/in/julianocosta/



# Presentation
Here is my dictionary about all stuffs related of Artificial Intelligence, Machine Learning, Deep Learning, etc.

Any think to complete, please email me! :)  I will do my best!!
juliano.t.costa@hotmail.com



<a href='#Letter_A'>A</a> | <a href='#Letter_B'>B</a> | <a href='#Letter_C'>C</a> | <a href='#Letter_D'>D</a> | <a href='#Letter_E'>E</a> | <a href='#Letter_F'>F</a> | <a href='#Letter_G'>G</a>
<a href='#Letter_H'>H</a> | <a href='#Letter_I'>I</a> | <a href='#Letter_J'>J</a> | <a href='#Letter_K'>K</a> | <a href='#Letter_L'>L</a> | <a href='#Letter_M'>M</a> | <a href='#Letter_N'>N</a>
<a href='#Letter_O'>O</a> | <a href='#Letter_P'>P</a> | <a href='#Letter_Q'>Q</a> | <a href='#Letter_R'>R</a> | <a href='#Letter_S'>S</a> | <a href='#Letter_T'>T</a> | <a href='#Letter_U'>U</a>
<a href='#Letter_V'>V</a> | <a href='#Letter_X'>X</a> | <a href='#Letter_W'>W</a> | <a href='#Letter_Y'>Y</a> | <a href='#Letter_Z'>Z</a> | <a href='#Number1'>1</a> | <a href='#Number2'>2</a>





# <a id='Letter_A'>A</a>

# <a id='Letter_B'>B</a>

# <a id='Letter_C'>C</a>

## Cassandra
É um banco de dados distribuído altamente escalável, que reúne a arquitetura do DynamoDB e modelo de dados baseado no BigTale. É mantido pela fundação Apache.

## Clickstream 
dados de cliques

# <a id='Letter_D'>D</a>

Data Lake: a ideia é ter um repositório único dentro da empresa para que todos os dados brutos estejam disponíveis q qualquer pessoa que precise fazer análise sobre eles. Os Data Lakes armazenam os dados em seu formato bruto, sem qualquer processamento e sem governança.
São projetados para o consumo de dados (coleta e processamento) e é um recurso de toda a organização, não só de TI.
Data Lake não são substituídos para plataformas analíticas ou infraestrutura existente. Em vez disso, eles complementam os esforços existentes e apoiam a descoberta de novas perguntas sobre os dados.


# <a id='Letter_E'>E</a>

# <a id='Letter_F'>F</a>

# <a id='Letter_G'>G</a>

# <a id='Letter_H'>H</a>

## Hadoop
É uma plataforma de software em Java de computação distribuída voltada para clusters e processamento de grandes volumes de dados, com atenção a tolerância de falhas. Trata-se de um projeto da Apache de alto nível, construído por uma comunidade de contribuidores e utilizando a linguagem Java. Além de gratuito, foi criado para ser usado em hardware de baixo custo.
Hadoop Commom: Contém as bibliotecas e arquivos comuns e necessários para todos os módulos do Hadoop
Hadoop Distributed File System (HDFS): Sistema de arquivos distribuído que armazena dados em máquinas dentro do cluster, sob demanda, permitindo uma largura de banda muito grande em todo o cluster.
Hadoop Yarn: é uma plataforma de gerenciamento de recursos responsáveis pelo gerenciamento dos recursos computacionais em cluster, assim como pelo agendamento dos recursos
Hadoop MapReduce: Modelo de programação para processamento em larga escala
Spark: projeto open source que foi concebido com o principal objetivo de ser veloz, tanto no processamento de queries quanto de algoritmos, além de processamento em memoria e eficiente recuperação de falha.


# <a id='Letter_I'>I</a>

# <a id='Letter_J'>J</a>

# <a id='Letter_K'>K</a>

## K-média ou K-means
Algoritmo de agrupamento é fornecer uma classificação de informações de acordo com os próprios dados, em um determinado número predefinido K de grupos (cluster). Tem como função de classificação a distância do objeto ao centro do grupo (Centroide).
O algoritmo automaticamente vai fornecer uma classificação automática sem a necessidade de nenhuma supervisão humana, ou seja, sem nenhuma pre-classificação existente. Por causa desta característica, o k-means é considerado como um algoritmo de mineração de dados não supervisionados.

Vantagens: 
•	Todos os objetos de informação são automaticamente atribuídos a um grupo
•	A localização inicial do centroide do grupo pode variar, o que permite estabelecer condições iniciais de dependência
Desvantagens
•	Antes do algoritmo ser iniciado, tem que ser escolhido o número de grupos
•	Todos os objetos de informação são forçados a pertencer a um grupo

##Kohonen Algorithm
É um algoritmo com a capacidade de organizar dimensionalmente dados complexos em grupos (cluster), de acordo com suas relações. Esse método solicita apenas os parâmetros de entrada, mostrando-se ideal para problemas onde os padrões são desconhecidos ou indeterminados. É considerado um mapa auto organizável, capas de diminuir a dimensão de um grupo de dados, conseguindo manter a representação real com relação as propriedades relevantes dos vetores de entrada, tendo-se como resultado um conjunto das características do espaço de entrada.


# <a id='Letter_L'>L</a>

# <a id='Letter_M'>M</a>

## MapReduce
Um modelo de programação desenhado para processar grandes volumes de dados em paralelo, dividindo o trabalho em um conjunto de tarefas independentes. MapReduce passa a ser considerado um novo modelo computacional distribuído, inspirado pelas funções map e reduce usadas comumente em programação funcional.
Os pontos que define a aplicação são:
•	Um leitor de entrada: divide os dados em blocos
•	Uma função de map: leva uma serie de pares (chave e valor) processa e gera pares de saída
•	Uma função de partição: aloca um redutor determinado pela própria função
•	Uma função de comparação: o reduce é classificado usando função de comparação
•	Uma função de reduce: reduzir função da aplicação uma vez para cada chave
•	Um escritor de saída: escreve a saída do reduce


A filosofia por trás do MapReduce é: Diferentemente de data-stores centrais, como um banco de dados, você não pode assumir que todos os dados residem em um lugar central portanto você não pode executar uma query e esperar obter os resultados em uma operação síncrona. Em vez disso, você precisa executar a query em cada fonte de dados simultaneamente. O processo de mapear a requisição do originador para o data source é chamado de ‘Map’, e o processo de agregação do resultado em um resultado consolidado é chamado de ‘Reduce’.


# <a id='Letter_N'>N</a>

# <a id='Letter_O'>O</a>

# <a id='Letter_P'>P</a>

# <a id='Letter_Q'>Q</a>

# <a id='Letter_R'>R</a>

## Redes neurais
São modelos computacionais inspirados pelo sistema nervoso central que são capazes de realizar o aprendizado de máquina bem como o reconhecimento de padrões, simulando o comportamento de redes neurais biológicas.
Por exemplo, uma rede neural para o reconhecimento de escrita manual é definida por um conjunto de neurônios de entrada que podem ser ativados pelos pixels de uma imagem de entrada. As ativações desses neurônios são então repassadas, ponderadas e transformadas por uma função determinada pelo designer de rede a outros neurônios. Este processo é repetido até que, finalmente um neurônio de saída é ativado. Isso determina que caractere foi lido.
A inspiração original para essa técnica advém do exame das estruturas do cérebro, em particular dos exames de neurônios. A propriedade mais importante das redes neurais é a habilidade de aprender de seu ambiente e com isso melhorar seu desempenho. Isso é feito através de um processo interativo de ajustes aplicados aos seus pesos, o treino


# <a id='Letter_S'>S</a>

# <a id='Letter_T'>T</a>

# <a id='Letter_U'>U</a>

# <a id='Letter_V'>V</a>

# <a id='Letter_X'>X</a>

# <a id='Letter_W'>W</a>

# <a id='Letter_Y'>Y</a>

# <a id='Letter_Z'>Z</a>

# <a id='Number1'>1</a>

# <a id='Number2'>2</a>


