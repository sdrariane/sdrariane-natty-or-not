# Proposta
Como *spin-off* do meu TCC, a proposta desde espaço é de discutir como as ferramentas de inteligência artificial podem ser utilizadas para combate as *fake news* promovendo conteúdo científico, embasado e reflexivo à população.

É aconselhável que sigam toda construção argumentativa aqui apresentada, mas sintam-se à vontade de consultar apenas o tópico desejado através do *dropdown* abaixo.

[TOCM]

# Navegador

Sim, todo projeto que trabalha com dados precisa de um rigor mais delicado quando o assunto são fatos e isso inclui a ferramenta utilizada para pesquisar componentes que hão de integrar a construção argumentativa - que deve ser a mais completa e honesta possível.

As *Search Engines*, ou melhor, Ferramentas de Pesquisa atuam com base em 3 princípios:

**1.** **Rastreamento:** vasculha a Internet em busca de conteúdo, examinando o código/conteúdo de cada URL encontrado - realizado por bots.
**2.** **Indexação:** armazene e organize o conteúdo encontrado durante o processo de rastreamento. Quando uma página está no índice, ela está em execução para ser exibida como resultado de consultas relevantes.
**3.** **Classificação:** forneça as partes de conteúdo que melhor responderão à consulta de um pesquisador, o que significa que os resultados são ordenados por mais relevante para menos relevante.

A indexação vem acompanhada de um ranqueamento (ranking) com base nos conteúdos de maior relevância - supostamente igual ao Twitter e derivados - isso se chamda SERP (*Search Engine Results Page*). Você pode verificar indo na barra de pesquisa do seu navegador e digitar `site:seudominio.com`.

Agora, porque o Google não é recomendado para pesquisas envolvendo dados? Ou melhor: não deveria ser.

### #1 Rastreamento
No Google, suas pesquisas são rastreadas, exploradas e agrupadas em um perfil de dados para que os anunciantes os utilizem na fabricação de anúncios veiculados pelo Google, incorporados em sites e aplicativos.

O **modo anônimo não é anônimo** se ele deleta apenas seu histórico de navegação local após a sessão em seu dispositivo, mas não impede que qualquer site que você visite, incluindo o Google, rastreie você por meio de seu endereço IP e outros mecanismos de rastreamento, como impressão digital do navegador.

O Google Analytics também executa um papel de rastreamento da sua e nossa atividade ao estar instalado na maioria dos sites. O mesmo se aplica aos anúncios em si, com o Google executando três das maiores redes de anúncios não relacionados à pesquisa instaladas em milhões de sites e aplicativos: Adsense, Admob e DoubleClick.

O problema em si, não é o rastreio, até porque quem não deve, não teme. Mas sim o propósito da utilização destes dados, qual(is) é(são) e para quem?

### #2 Pesquisa Enviesada

Quando pesquisamos por algo, esperamos um retorno objetivo, conciso e imparcial, mas não é isso o que ocorre no Google, porque **você obtém resultados adaptados estatisticamente à sua preferência**, com base no perfil de dados que construíram sobre você ao longo do tempo, a partir de todo o rastreamento realizado. E para isso eles filtram e 'escondem' os resultados que você supostamente iria ignorar - tirando a sua autonomia informacional.

Portanto, se você tem tendências políticas de uma forma ou de outra, é mais provável que obtenha resultados com os quais já concorda e é menos provável que veja pontos de vista opostos.

Você pode conferir pesquisando a mesma coisa em mecanismos de pesquisa distintos, nenhum deles irá mostrar os mesmos resultados.

### #3 Trap Location

Se o seu mecanismo de pesquisa estiver localizado no Brasil e você for pesquisar por informações sobre a Argentina por exemplo, você não terá as mesmas informações se o seu mecanismo de pesquisa estiver localizado na Argentina. Parece bobo, mas a pesquisa de dados internacionais para o desenvolvimento de correlações e comparativos nacionais em algumas áreas, fica deveras comprometido. Como eu posso estabelecer uma comparação aprofundada, nos mínimos detalhes com uma riqueza de informações, se tenho acesso somente à uma parte delas?

### #4 True Anonymous

Ante ao exposto, a utilização de um navegador que preze pela transparência e equidade informacional culminou na escolha do [DuckDuckGo](https://spreadprivacy.com/ "DuckDuckGo") como Search Engine.

----------

# Machine Learning

Machine Learning (ML), or Aprendizado de Máquina, é um subcampo da inteligência artificial (IA) que se concentra no desenvolvimento de algoritmos e técnicas que permitem aos computadores aprenderem a partir de dados e experiências passadas, sem serem explicitamente programados para isso. O objetivo principal do machine learning é capacitar os sistemas computacionais a reconhecer padrões nos dados e tomar decisões ou fazer previsões com base nesses padrões.

Em vez de seguir instruções específicas para realizar uma tarefa, os sistemas de machine learning aprendem com exemplos passados e são capazes de generalizar esse conhecimento para realizar tarefas semelhantes em novos dados. Essencialmente, o processo de machine learning envolve o desenvolvimento de modelos matemáticos e estatísticos que são treinados em dados de entrada para fazer previsões ou tomar decisões.

Existem várias abordagens e técnicas de machine learning, incluindo:

**1. Aprendizado Supervisionado:** Os algoritmos de aprendizado supervisionado são treinados em pares de entrada-saída, onde o modelo aprende a mapear as entradas para as saídas desejadas. Exemplos incluem classificação (prever uma categoria ou classe) e regressão (prever um valor numérico).

**2. Aprendizado Não Supervisionado:** Neste caso, os algoritmos são treinados em dados de entrada sem rótulos, e o objetivo é descobrir estruturas ou padrões nos dados. Exemplos incluem clustering (agrupamento de dados semelhantes) e redução de dimensionalidade (representação de dados em um espaço de menor dimensão).

**3. Aprendizado por Reforço:** Neste paradigma, os agentes de aprendizado interagem com um ambiente dinâmico e aprendem a realizar ações que maximizam uma recompensa acumulada ao longo do tempo. É comumente usado em jogos, robótica e otimização.

<details>
  <summary>Bibliotecas de Machine Learning</summary>

  ## Bibliotecas de Machine Learning

### NumPy

[NumPy](https://numpy.org/ "NumPy") é uma biblioteca Python popular para array multidimensional e processamento de matrizes porque pode ser usada para realizar uma grande variedade de operações matemáticas. Sua capacidade de lidar com álgebra linear, Fourier e muito mais torna o [NumPy](https://numpy.org/ "NumPy") ideal para projetos de aprendizado de máquina e inteligência artificial (IA), permitindo que os usuários manipulem a matriz para melhorar facilmente o desempenho do aprendizado de máquina. NumPy é mais rápido e fácil de usar do que a maioria das outras bibliotecas Python.

### Scikit-learn

[Scikit-learn](https://scikit-learn.org/stable/index.html "Scikit-learn") é uma biblioteca de aprendizado de máquina muito popular construída em NumPy e [SciPy](https://scipy.org/ "SciPy"). Ele suporta a maioria dos algoritmos clássicos de aprendizagem supervisionada e não supervisionada e também pode ser usado para mineração, modelagem e análise de dados. O design simples do [Scikit-learn](https://scikit-learn.org/stable/index.html "Scikit-learn") oferece uma biblioteca fácil de usar para quem é novo no aprendizado de máquina.

### Pandas

[Pandas](https://pandas.pydata.org/ "Pandas") é outra biblioteca Python construída sobre NumPy, responsável por preparar conjuntos de dados de alto nível para aprendizado de máquina e treinamento. Baseia-se em dois tipos de estruturas de dados, unidimensionais (série) e bidimensionais (DataFrame). Isso permite que o Pandas seja aplicável em diversos setores, incluindo finanças, engenharia e estatística. Ao contrário dos próprios animais lentos, a biblioteca Pandas é rápida, compatível e flexível.

### TensorFlow

A biblioteca Python de código aberto do [TensorFlow](https://www.tensorflow.org/ "TensorFlow") é especializada no que é chamado de programação diferenciável, o que significa que pode calcular automaticamente as derivadas de uma função em uma linguagem de alto nível. Os modelos de aprendizado de máquina e de aprendizado profundo são facilmente desenvolvidos e avaliados com a arquitetura e a estrutura flexíveis do [TensorFlow](https://www.tensorflow.org/ "TensorFlow"). O [TensorFlow](https://www.tensorflow.org/ "TensorFlow") pode ser usado para visualizar modelos de aprendizado de máquina em computadores e dispositivos móveis.

### Seaborn

[Seaborn](https://seaborn.pydata.org/ "Seaborn") é outra biblioteca Python de código aberto, baseada em [Matplotlib](https://matplotlib.org/ "Matplotlib") (que se concentra em plotagem e visualização de dados), mas apresenta estruturas de dados do Pandas. [Seaborn](https://seaborn.pydata.org/ "Seaborn") é frequentemente usado em projetos de ML porque pode gerar gráficos de dados de aprendizagem. De todas as bibliotecas Python, ela produz os gráficos e plotagens mais esteticamente agradáveis, tornando-a uma escolha eficaz se você também a usar para marketing e análise de dados.

### Theano

[Theano](https://theano.readthedocs.io/en/0.8.x/ "Theano") é uma biblioteca Python focada em computação numérica e feita especificamente para aprendizado de máquina. É capaz de otimizar e avaliar modelos matemáticos e cálculos matriciais que usam matrizes multidimensionais para criar modelos de ML. [Theano](https://theano.readthedocs.io/en/0.8.x/ "Theano") é usado quase exclusivamente por desenvolvedores ou programadores de aprendizado de máquina e aprendizado profundo.

### Keras

[Keras](https://keras.io/ "Keras") é uma biblioteca Python projetada especificamente para o desenvolvimento de redes neurais para modelos de ML. Ele pode ser executado em Theano e TensorFlow para treinar redes neurais. [Keras](https://keras.io/ "Keras") é flexível, portátil, fácil de usar e facilmente integrado com múltiplas funções.

### PyTorch

[PyTorch](https://pytorch.org/ "PyTorch") é uma biblioteca Python de aprendizado de máquina de código aberto baseada na estrutura da linguagem de programação C, Torch. É usado principalmente em aplicativos de ML que envolvem processamento de linguagem natural ou visão computacional. [PyTorch](https://pytorch.org/ "PyTorch") é conhecido por ser excepcionalmente rápido na execução de conjuntos de dados e gráficos grandes e densos.

### Matplotlib

[Matplotlib](https://matplotlib.org/ "Matplotlib") é uma biblioteca Python focada na visualização de dados e usada principalmente para criar belos gráficos, plotagens, histogramas e gráficos de barras. É compatível com plotagem de dados de SciPy, NumPy e Pandas. Se você tem experiência no uso de outros tipos de ferramentas gráficas, [Matplotlib](https://matplotlib.org/ "Matplotlib") pode ser a escolha mais intuitiva para você.

</details>
