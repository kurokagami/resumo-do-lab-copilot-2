
<h1>
    <a href="https://www.dio.me/" style="color:8542DB">
     <img align="center" alt="Dio Logo" width="66px" src="https://ac-landing-pages-user-uploads-production.s3.amazonaws.com/0000051657/a6176d56-6fab-496b-93a9-b95c0f49b56b.png">
    <span>Atividade Laboratorial de Copilot - DIO</span></a>
</h1>

<main>
<img align="right" alt="Platform" height="350" src="https://ragnarheil.de/wp-content/uploads/2024/10/image-1024x842.jpg">
<p align="justify"><h1> 2° Laboratório da trilha de Copilot Studio DIO.</h1>
<br/>
O intuito deste laboratório é apresentar um pouco sobre o que foi estudado nas demais aulas de copilot studio, visando testar os conhecimentos adquiridos durante as videoaulas.
<br>Este resumo é uma continuação do anterior, para visualizar o primeiro resumo <a href="https://github.com/kurokagami/resumo-do-lab-copilot-1">acesse aqui</a>.
</p>
</main>

<article>
<br/>
<h1>Percurso</h1>

<h2>
    <img align="center" alt="Copilot Logo" width="45px" src="https://brandlogos.net/wp-content/uploads/2023/09/microsoft_copilot-logo_brandlogos.net_zaqzr.png"> Tópicos de Copilot Studio
</h2>
<p>Os tópicos são conversas fixas que definem como o chatbot responde a perguntas e interage com os usuários.
<br>Funcionam como fluxos de conversação estruturados, onde cada tópico pode conter gatilhos, ações e respostas específicas.</p>
<h3>Principais Elementos de um Tópico:</h3>
<ul>
    <li>Gatilhos (Triggers): Frases ou palavras-chave que ativam o tópico.</li>
    <li>Fluxo de Conversação: Definição do diálogo entre o bot e o usuário.</li>
    <li>Ações: Integrações com APIs, chamadas de banco de dados ou execução de lógica personalizada.</li>
    <li>Respostas: Mensagens enviadas ao usuário, podendo incluir texto, botões, imagens, etc.</li>
</ul>
<h3>Prompts</h3>
<p>Uma mensagem ou conjunto de diretrizes usadas para orientar o chatbot na geração de respostas.<br>
Ele funciona como uma instrução que define como o bot deve responder e agir em diferentes situações.</p>
Ele pode conter informações como:
<ul>
    <li>Tons e estilos de resposta: formal, casual, técnico, etc.</li>
    <li>Contexto da conversa: como deve responder a diferentes perguntas.</li>
    <li>Limites do chatbot: o que ele pode ou não responder.</li>
    <li>Ações que deve realizar: integração com APIs, banco de dados, etc.</li>
</ul>
<p>Um chatbot eficiente deve ter prompts precisos, claros e concisos, evitando respostas erradas, mantendo a identidade da empresa, melhorando a experiência do usuário e facilitando a personalização.</p>
<h3>Boas Práticas</h3>

+ Ter entre 5 a 10 frases para cada gatilho, garantindo variedade nas respostas.
+ Usar nomes que descrevam claramente o propósito e evite repetições.
+ Evitar conflitos, garantindo que as frases de gatilho não se sobreponham, para respostas precisas.
+ Criar copilotos e tópicos de forma lógica, evitando tópicos genéricos.
+ Usar condições e autenticação quando necessário para garantir segurança e personalização.

<h3>Variáveis</h3>
<p>São valores ou informações armazenadas que podem ser manipuladas e utilizadas pelo sistema para realizar tarefas específicas.<br>
Aprimoram a personalização e o controle dinâmico das interações, adaptando o comportamento do sistema às necessidades do usuário.
</p>
Tipos de Variáveis:

+ Globais: Acessíveis em todo o sistema, como configurações de usuário.
+ Locais: Específicos de um tópico, como dados temporários de uma interação.
+ De Sistema: Armazenam informações sobre o funcionamento do sistema, como status de execução.
+ Locais: Configuradas para refletir o ambiente em que o sistema opera, como variáveis de configuração de servidores ou APIs.

<h3>Entidades</h3>
<p>Componentes de dados que representam informações específicas dentro de uma frase, como "tipos de assunto".<br>
Facilitam a captura e processamento de informações essenciais, melhorando a experiência do usuário.
</p>
Há dois tipos de Entidades:

1. Predefinidas: Já configuradas, como date, location.
2. Personalizadas: Criadas para um domínio específico: Closed List ou Regex.

+ Preenchimento de Slot: Processo de capturar informações das entidades para completar uma tarefa ou entendimento.

<h3>Power Fx</h3>
<p>Utilizado para criar fórmulas que manipulam dados e controlam a lógica das aplicações.
<br>
Facilita a criação de lógicas dinâmicas e interativas, permitindo o controle dos comportamentos e dados nas aplicações.
</p>
Componentes:

+ Funções: Executam cálculos ou ações específicas, como operações matemáticas ou lógicas.
+ Referências a Controles: Permitem acessar dados de controles na interface, como campos de entrada ou botões.
+ Preenchimento de Slot: Processo de captura e validação de dados específicos inseridos pelo usuário.

<h3>Respostas Generativas</h3>
<p>Respostas criadas automaticamente com base no que o usuário diz, usando inteligência artificial para entender e responder de forma adequada.
<br>
Proporciona respostas personalizadas e flexíveis, tornando a conversa mais natural e relevante.
</p>
Personalização da IA:

+ **Carregamento de Arquivos**:
<br/>
Envio de imagens, documentos e outros arquivos importantes para o sistema.
<br/>
A IA generativa pode usar arquivos carregados para gerar respostas mais contextuais e personalizadas.

+ **Ações e Plugins**:
<br/>
Adicionam funcionalidades extras ao sistema, como integrar com outros serviços.
<br/>
São cruciais para que o Agente Copilot execute tarefas específicas, como enviar um e-mail automaticamente ou acessar um banco de dados para fornecer informações atualizadas.

<br/>

<h2>
    <img align="center" alt="Copilot Agent Logo" width="45px" src="https://media.licdn.com/dms/image/v2/D560BAQH9cD7QSKRYnQ/company-logo_200_200/company-logo_200_200/0/1696650669339/agent_copilot_ai_logo?e=2147483647&v=beta&t=OueZ4lFwMVwKtS4hzMpdcGcjcsYoTiXwFRkDG8jgGps"> Criando Agente Copiloto.
</h2>
<p>Após configurar o ambiente no Microsoft Copilot Studio, o agente pode ser criado nas seguintes etapas:</p>

1.  **Acessando Copilot Studio**: 
<br/>
Acessar https://copilotstudio.microsfot.com/; 
<br/>
No painel inicial, clique em **+New Agent**;

<img align="right" alt="Platform Agent" height="280" src="https://pub-c2c1d9230f0b4abb9b0d2d95e06fd4ef.r2.dev/sites/418/2024/10/OMB-Copilot-Innovation-Hero.png">

2.  **Configuração Inicial**: 
<br/> 
Recomendado Idioma Inglês para melhor experiência; 
<br/> 
Insira um **nome** para o seu agente;

3.  **Descrição**: 
<br/> 
Adicione uma **descrição** para o agente;
<br/>
Especificando sua **função** e o **objetivo** da criação do chatbot;

4.  **Instruções**:
<br/>
Define o **comportamento**, **tom** e **diretrizes** que o chatbot deve seguir ao interagir com os usuários;
<br/>
É importante utilizar o conhecimento da **engenharia de prompt** para definir um comportamento para o agente de maneira correta;
<br/>
Evitando **respostas erradas**, **garantindo consistência**, **melhorando a experiência** do usuário com respostas claras e úteis e **facilitando a manutenção** e **escalabilidade** do chatbot.

5.  **Conhecimento Sólido**:
<br/>
+ Defina as fontes de conhecimento que a IA utilizará para obter informações;
<br/>
+ Uma seção **opcional** a ser utilizada conforme a necessidade da funcionalidade do agente.;

****

<h3>Customizando Tópicos</h3>
<img align="right" alt="Platform Topics" height="280" src="https://learn.microsoft.com/lt-lt/microsoft-copilot-studio/media/authoring-template-topics/topic-list.png">

1.  **Criando Tópico**: 
<br/>
+ Após criar o agente, selecione o agente, vá na aba **topics**; 
<br/>
+ **+ Add a topic**, Selecione em branco;

2.  **Gatilhos**: 
<br/>
+ As frases de gatilhos determinam quando um chatbot deve iniciar um determinado fluxo de conversa. Elas ajudam a tornar a interação mais natural e eficiente;
<br/>
+ Para adicionar uma, vá em **edit**, e adicione frases de gatilhos em **Add phrases**;

3.  **Utilizando IA Generativa**: 
<br/>
+ Permite ao chatbot gerar respostas **dinâmicas** e **contextuais** com base em fontes de conhecimento;
<br/>
+ Após configurar um tópico adicione **Generative Answers**;;

****

<img align="right" alt="Platform Topics" height="280" src="https://learn.microsoft.com/en-us/microsoft-copilot-studio/media/authoring-system-fallback-topic/fallback-system-topic.png">
<h3>Conversational Boosting e Fallback</h3>

<p>Utilizados para evitar falhas e mitigar erros em um agente;
<br/>
São tópicos padrão no Copilot Studio pré-configurados para garantir que o chatbot tenha uma resposta apropriada em situações onde ele não encontra uma correspondência direta com os tópicos definidos;</p>

1. **Conversational Boosting** 
+ ajuda o chatbot a buscar respostas em fontes externas para melhorar sua inteligência;


2. **Fallback** 
+  Garante que o bot tenha uma resposta útil quando não entende uma pergunta;

***

<h3>Qualidade da Resposta com GenAI</h3>
<img align="right" alt="Platform IA Gen" height="300" src="https://www.karlex.fi/wp-content/uploads/2024/10/image-31-945x678.png">
<p>Há 3 maneiras de melhorar ou controlar uma resposta generativa:</p>

1. **Knowledge Sources** 
+ Configura uma seleção de conhecimentos para IA utilizar;
+ Alguns exemplos de fontes de conhecimento: **Bancos de Dados**, **APIs Externas** e **Arquivos de Texto**;


2. **Classic Data** 
+  Permite que a IA utilize seu conhecimento geral;
+  Utiliza o conhecimento do **GPT-4 atualmente**;

3. **Através de Prompts** 
+  O agente pode ser orientado com informações fornecidas pelo desenvolvedor de maneira escrita;
+  É possível personalizar o nível de **concisão** e **precisão** nas respostas através de **probabilidade**;
+  Através de **Settings**, também é possível configurar a nível global ou do ambiente de forma geral;

<br/>
<p>Após seguir essas etapas de criação, o agente está parcialmente configurado e pronto para realizar **testes**;</p>
<br/>

<div align="center">Made by <a href="https://github.com/kurokagami/">Kuro Kagami</a>.</div>

