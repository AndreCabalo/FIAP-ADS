# IA Generativa 

- A IA Generativa é uma subcategoria da inteligencia artificial para geração de conteúdos como textos e imagens.

- Normalmente é menos restriva do que uma chatbox
- AI Generativa trabalho com o treinamento de <b>modelo não supervisionado</b> 
- Ja o Chatbot trabalha com o treinamento de <b>modelo supervisionado</b>

<h3>Quais seus principais casos de uso da IA Generativa: </h3>

- Criação de conteúdo textou
- Criação de conteúdo imagens
- Geração de códigos
- Tradução de conteúdo
- Explicação de conteúdos
- Sintetizar e resumir conteúdos  
- Capacitar chatbots
  - Aumentando sua capacidade de compreensão da linguagem natural, fluxo de conversação, respostas personalizadas

<h3>Tecnólogias utilizadas:</h3> 

- Foundation Model
  - Modelo de base para construção de aplicações de machine learning para IA Generativa
- Large Language Model
  - Modelo de linguagem que visa simular a interação e linguagem humana

<h3>Desafios atuais: </h3>

- <b>Alucinações (Como resultados incorretos)</b>
- Resposta que divergem do prompt
- Estes problemas podem surgir por vários motivos:
  - Overfitting (Aprendido a replicar padrões específicos nos dados de treinamento)
  - Falta de compreensão do contexto
  - Viés de dados(dados do treinamento com infos tendenciosas ou imprecisas)
  - Dados de treinamento limitado

<h3>Componentes fundamentais</h3>

- Large Langue Model e Fundation Model são componenetes integrantes da IA Generativa
- Servem como blocos de construção sobre os quais vários aplicativos, incluindo chatbots,-servições de tradução e geranção de conteúdo são desenvolvidos

<h4>Largue Language Model (LLMs)</h4>

- <b>Projetados para compreendar e gerar a linguagem humana</b>
- <b>Modelos sofisticados baseados em redes neurais</b>
- Capacidade de processar grandes quantidades de dados
- Aprende padrões, gramática e a semântica da linguagem
- Exemplo: GPT-3.5 e BERT da Google

<h4>Fundation Model</h4>

- <b>Modelo base/Pai para aplicações em IA Generativas</b>
- São versões ainda mais extensas e poderosas dos LLMS
- Servem para criação de vários modelos especializados e são pré-treinados em diversos e extensos conjuntos de dados.
- Servem como ponto de partida para várias aplicações posteriores
- Existem pouco Foundation Model, por exemplo : GPT3, GPT4 e outros como StableDifusion
- Em geral cada tipo de rede funcione de maneira diferente, mas por tras de seu funcionamento, a maioria usa utiliza padrõese relações aprendidadas para prever o proximo item de sequencia
- De forma simplificada o processo de criação de um Fundation Model utiliza as seguintes etapas:
    - Coleta de dados de diversas fontes na internet
    - Pré-processamento e Tokenização. dividindo-o em unidades menores, como palavras,subpalavras ou caracteres
    - Treinamento(Pré-treinamento), usando uma arquitetura de transformador, aprendendo a prever a próxima palavras
    - Ajuste fino(fine-tunning), após o pré-treinamento o modelo pode ser ajustado em tarefas especificas usando um conjunto de dados menores.

<h3>Desafios com Foundation Models</h3>

- Requisitos de infraestrutura
- Desenvolvimento front-end, usando inumeros recursos em uma única plataforma
- Falta de compreensão
- Resposta não confiáveis
- Viés(Bias), pois os modelos podem captar discursos ódio e conotações inaquedads em conjuntos de dados de treinamento.

<h3>Técnicas de prompt Enginner para uso em LLMs</h3>

- <b>Zero -Shot Leaning</b>, enviar uma única mensagem e o LLM retorna a resposta esperada, LLM já passou por diversas otimizações para que o modelo em si podesse responder sem grandes contextos.
  
- <b>Few-Shot Learning</b>, o LLM ainda não foi refinido a ponto de darmos um unico comando e ele nós trazer a resposta esperada, nesse caso, precisamos enviar no msm prompt exemplos, contexto, sáida esperada e em seguida enviar a questão.
  
- <b>Chain-of-Thought Prompting</b>, nesse caso precisamos passar instruções mais complexas, passando toda lógica para chegar em tal resposta, passando todo contexto, lógica e no final solicitar a resposta.

<h3>Prompt Enginnering e suas técnicas</h3>

- Técnica para otimizar seus comandos, afim de ter um respostas ainda mais precisa do LLM
- Carateristicas para uma resposta mais apurada
  - Instrução (oque precisa ser feito)
  - Contexto
  - Dados de entrada
  - Saída esperada
  - Detalhes especificos

<h3>Parametros que podemos configurar para obter resultados diferentes</h3>

<h4>Temperatura de criatividade</h4>

- Quanto mais baixa a temperatura, mais preciso
- Quanto mais alta a temperatura, maior criatividade
- Pode ser mais criativo ou mais preciso
- É o grau de liberdade que damos a LLM para retornar resultados

<h4>Top_p</h4>

- Quanto maior o top_p menor a precisão
- Quanto menor o top_p maior mais diversas serão as respostas

