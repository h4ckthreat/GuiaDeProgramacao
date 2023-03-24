## Guia básico de introdução à programação
### Definições, ferramentas auxiliares e dicas
<em construção>

### Índice
- 💻 O que faz um programador?
- 📄 O que são algoritmos?
- 📧 O que são linguagens de programação?
- 📁 O que é um sistema operacional?
- 📈 O que são estruturas de dados?
- 🎁 O que é um compilador?
- ☎️ O que é um interpretador?
- 🕑 O que são frameworks?
- 🎭 O que é front-end e back-end?
- 🔧 O que são IDEs?
- 🔒 O que são os bancos de dados?
- 🏭 O que é o GIT?
- :octocat: O que é o Github?
- 🚀 O que é o Gitlab?
- 🔑 O que é o SSH?
- ☁️ O que é uma rede de computadores?
- 🚪 O que é uma porta de rede?
- ⚡ Métodos Ágeis
- :pencil2: Padroẽs de Projeto (Design Patterns)
- 📋 Informações complementares e links úteis
- ☀️ Listas de Atalhos de IDEs e demais ferramentas
- 🔨 Ferramentas auxiliares

### O que faz um programador?
É o profissional que escreve, desenvolve ou faz manutenção de software em um grande sistema ou alguém que desenvolve software para uso em computadores pessoais.

### O que são algoritmos?
Proramar é resolver problemas usando algoritmos. Algoritmo é uma sequência de etapas lógicas organizadas de maneira a solucionar um problema específico. É um conjunto de instruções estruturadas e ordenadas com o objetivo de realizar uma tarefa ou operação específica. Os algoritmos são utilizados para manipular dados nas estruturas de várias formas, como por exemplo: inserir, excluir, procurar e ordenar dados.

### O que são linguagens de programação?
É uma linguagem formal que, através de uma série de instruções, permite ao programador passar instruções de processamento ao computador.

<div align = "center">
<img src="https://user-images.githubusercontent.com/36556279/128284472-867902b0-840a-43e6-9513-364269d814bc.png" width = "600px" />
</div>

Linguagens de programação geraalmente precisam ser instaladas como se pode ver nesse [tutorial para instalar o JDK da linguagem Java no Windows.](https://techexpert.tips/pt-br/windows-pt-br/instalar-java-jdk-no-windows/#:~:text=Tutorial%20Windows%20-%20Instalar%20Java%20JDK%20Acesse%20o,Next.%20Aguarde%20a%20finaliza%C3%A7%C3%A3o%20da%20instala%C3%A7%C3%A3o%20Java%20JDK.)

### O que é um sistema operacional?

Sistema operativo ou operacional é um programa ou um conjunto de programas cuja função é gerenciar os recursos do sistema, fornecendo uma interface entre o computador e o usuário ou utilizador. Além dos sistemas operacionais para computadores, também há sistemas operacionais específicos para dispositivos móveis, como, por exemplo, o Android, Windows Mobile, BlackBerry, entre outros.

Cada sistema operacional utiliza um tipo de sistema de arquivo, que é um conjunto de rotinas e estruturas lógicas para possibilitar ao sistema operacional controlar o acesso às informações do disco rígido. As informações são armazenadas no disco rígido em trilhas e setores, mas o sistema operacional reconhece apenas uma lista de endereços conhecidos como clusters, que são conjuntos de setores. Assim, quando o sistema operacional necessita de um determinado arquivo, ele envia o endereço do cluster que deve ser lido e a controladora do disco rígido faz o restante. O sistema NTFS é utilizado pela Microsoft nas versões atuais do Windows. O sistema Ext foi criado para ser utilizado pelo sistema operacional Linux.

### O que são estruturas de dados?

É uma estrutura que armazena e organiza dados/informações de modo que os dados possam ser acessados e manipulados de forma eficiente. Essas estruturas encontram muitas aplicações no desenvolvimento e sistemas, sendo que algumas são altamente especializadas e utilizadas em tarefas específicas. Usando as estruturas adequadas através de algoritmos, podemos trabalhar com uma grande quantidade de dados, como aplicações em bancos de dados ou serviços de busca.

### Principais Estruturas de Dados

Vetores e Matrizes, Registro, Lista, Pilha, Fila, Árvore, Tabela Hash, Grafos

### O que é um compilador?

Um compilador é um programa de computador que, a partir de um código-fonte escrito em uma linguagem compilada, cria um programa semanticamente equivalente, porém escrito em outra linguagem, código objeto.

### O que é um interpretador?

Interpretadores são programas de computador que leem um código-fonte de uma linguagem de programação interpretada e o converte em código executável. Ao contrário do compilador, o interpretador roda o código-fonte escrito como sendo o código objeto, ele traduz o programa linha a linha, o programa vai sendo utilizado na medida em que vai sendo traduzido. Cada execução do programa precisa ser novamente traduzido e interpretado.

### O que são frameworks?
Em desenvolvimento de software, é um conjunto de códigos prontos que podem ser usados no desenvolvimento de aplicativos e sites.

[Lista de frameworks mais usados](https://www.digitalhouse.com/br/blog/frameworks-mais-usados-em-programacao)

### O que é front-end e back-end?
São termos para diferenciar onde uma pessoa que programa acaba se especializando. Quem trabalha com front-end desenvolve a interface que interage diretamente com o usuário. O desenvolvedor back-end trabalha com os sistemas que agem por trás dessa mesma aplicação.

### O que são IDEs?
IDE, ou ambiente de desenvolvimento integrado, é um software que combina características e ferramentas de apoio ao desenvolvimento de software com o objetivo de agilizar este processo.

### O que são os bancos de dados?
Bancos de dados ou bases de dados são coleções organizadas de dados que se relacionam de forma a criar algum sentido (informação) e dar mais eficiência durante uma pesquisa ou estudo científico. Existem vários Modelos de Base de Dados: Modelo Plano (ou tabular), Modelo em Rede, Modelo Hierárquico, Modelo Relacional, Orientado a objetos e Objeto-Relacional. 

Bancos de dados NoSQL ou "não relacional" é um termo genérico que representa os bancos de dados não relacionais. Uma classe definida de banco de dados que fornecem um mecanismo para armazenamento e recuperação de dados que são modelados de formas diferentes das relações tabulares usadas nos bancos de dados relacionais. Bancos de dados NoSQL são cada vez mais usados em big data e aplicações web de tempo real. 

Bancos de dados relacionais representam e armazenam dados em tabelas e linhas, sendo baseados em um ramo da teoria dos conjuntos algébricos conhecido como álgebra relacional. Exemplos de bancos de dados relacionais: MySQL, PostgreSQL e SQLite3. Enquanto isso, bancos de dados não relacionais, como o MongoDB, representam dados em coleções de documentos JSON.

Os bancos de dados são operados pelos Sistemas Gerenciadores de Bancos de Dados (SGBD).

[Banco de Dados Relacional ou não Relacional?](https://www.iperiusbackup.net/pt-br/qual-a-solucao-mais-adequada-banco-de-dados-relacional-ou-nao-relacional/)

### O que é o GIT?

O GIT é um Sistema de Controle de Versões Distribuído — ou DVCS — desenvolvido pelo engenheiro de software Linus Torvalds. Estes sistemas de controle possuem a função de registrar quaisquer alterações feitas em cima de um código, armazenando essas informações e permitindo que, caso seja necessário, um(a) programador(a) possa regredir a versões anteriores de uma aplicação de modo simples e rápido.

[**Comandos GIT**](https://gitfichas.com/)

### O que é o Github?

GitHub é uma plataforma de hospedagem de código-fonte e arquivos com controle de versão usando o Git. Ele permite que programadores, utilitários ou qualquer usuário cadastrado na plataforma contribuam em projetos privados e/ou Open Source de qualquer lugar do mundo.

### O que é o Gitlab?

O GitLab é um gerenciador de repositório de software baseado em Git, com suporte a Wiki, gerenciamento de tarefas e CI/CD. GitLab é similar ao GitHub, mas o GitLab permite que os desenvolvedores armazenem o código em seus próprios servidores, ao invés de servidores de terceiros.

### O que é o SSH?

O SSH (Secure Socket Shell) é um protocolo de rede criptográfico para operar serviços de rede com segurança em uma rede não segura. Os aplicativos típicos incluem linha de comando remota, login e execução de comando remoto, mas qualquer serviço de rede pode ser protegido com SSH.

Para saber mais sobre [o que é o SSH](https://www.weblink.com.br/blog/tecnologia/acesso-ssh-o-que-e/)

### O que é uma rede de computadores?

Rede de computadores é uma malha que interliga milhares de sistemas computacionais para a transmissão de dados. Também conhecidos como nós, esses dispositivos interconectados enviam, recebem e trocam tráfego de dados, voz e vídeo, graças ao hardware e software que compõe o ambiente.

### O que é uma porta de rede?

Em redes de computadores, uma porta é um software de aplicação específica ou processo específico servindo de ponto final de comunicações em um sistema operacional hospedeiro de um computador. Uma porta tem associação com o endereço de IP do hospedeiro, assim como o tipo de protocolo usado para comunicação. O propósito das portas é para singularmente identificar aplicações e processos de um único computador e assim possibilitá-los a compartilhar uma única conexão física com uma rede de comutação de pacotes, como a internet.

Os protocolos que usam principalmente portas são os protocolos da camada de transporte, tais como o Protocolo de controle de transmissão (TCP) e User Datagram Protocol (UDP) do conjunto de protocolos da internet. A porta é identificada por um protocolo, com um número de 16 bits, vulgarmente conhecido como port number(número de porta). O port number é adicionado a um endereço de IP do computador, completando o endereço de destino para uma sessão de comunicação. Isto é, os pacotes de dados são encaminhados através da rede para um endereço de IP de destino especifico, e em seguida, ao atingir o computador de destino, são encaminhados para o processo especifico ligado ao número de porta de destino. 

[Lista de portas dos protocolos TCP e UDP](https://pt.wikipedia.org/wiki/Lista_de_portas_dos_protocolos_TCP_e_UDP)

[Artigo sobre escalabilidade e performance](https://www.linkedin.com/pulse/20141120153113-36733727-how-to-start-to-learn-high-scalability/)

### Métodos Ágeis

**SCRUM** - é uma estrutura de gestão de projetos de agilidade. As equipes utilizam para desenvolver, entregar e sustentar produtos em um ambiente complexo, com ênfase no desenvolvimento de software, mas já tendo sido utilizado em outras áreas. O Scrum descreve um conjunto de reuniões, ferramentas e cargos que atuam juntos para ajudar na organização e gerenciamento de trabalho das equipes.

**KANBAN** - é um quadro de sinalização com cartões coloridos (post-its) que controla os fluxos de produção ou transporte em uma indústria. Os cartões servem para indicar e acompanhar o andamento das tarefas conforme elas se movem pelo processo. O termo "Kanban" é de origem japonesa e quer dizer "sinalização" ou "cartão".

**PDCA** - é uma metodologia de gestão de quatro passos, utilizado para o controle e melhoria contínua de processos e produtos. É também conhecido como círculo/ciclo/roda de Deming, ciclo de Shewhart, círculo/ciclo de controle ou PDSA.

**Lean** - Lean manufacturing ou Lean production significa manufatura enxuta ou manufatura esbelta e é uma filosofia de gestão vinda do Sistema Toyota de Produção cuja premissa é focada na redução dos sete tipos de desperdícios.

## Padrões de Projeto

Padrões de projeto (design patterns) são soluções típicas para problemas comuns em projeto de software. Cada padrão é como uma planta de construção que você pode customizar para resolver um problema de projeto particular em seu código.

Saiba mais [aqui](https://refactoring.guru/pt-br/design-patterns)

## Informações complementares e links úteis

### Listas de Atalhos de IDEs e demais ferramentas

#### Intellij Idea

[Download do Intellij](https://www.jetbrains.com/pt-br/idea/download/#section=linux)

[Atalhos do Intellij Idea](http://www.basef.com.br/index.php/Atalhos_do_IntelliJ_Idea)

#### Visual Studio Code

[Download VS Code](https://code.visualstudio.com/download)

[Todos os atalhos do VS Code](https://pt.linkedin.com/pulse/todos-os-atalhos-do-vs-code-mateus-barbosa)

[Atalhos do VS Code](https://claudiojunior.me/posts/atalhos-do-vs-code)

#### Apache Maven (ferramenta de automação e gerenciamento de projetos Java)

[Download do Maven](https://maven.apache.org/download.cgi)

[Comandos úteis no Maven](https://gist.github.com/erkobridee/3287943)

#### Eclipse

[Download do Eclipse](https://www.eclipse.org/downloads/)

[Eclipse Shortcuts](https://www.w3big.com/pt/eclipse/eclipse-shortcuts.html)

### Ferramentas auxiliares

A seguir, algumas ferramentas complementares para auxiliar no trabalho:

#### Ferramentas de Design

[**AvePDF**](https://avepdf.com/pt) - Ferramentas online gratuitas para PDF e documentos.

[**Font Awesome**](https://fontawesome.com/) - Biblioteca de ícones vetoriais

[**Canva**](https://www.canva.com/pt_br/) - Ferramenta de design online.

[**Colors and Fonts**](https://www.colorsandfonts.com/) - Paleta de cores e tipografia.

[**Coolors**](https://coolors.co/) - Monte sua própria paleta de cores.

[**Devicon**](https://devicon.dev/) - Conjunto de ícones que representam linguagens de programação, ferramentas de design e desenvolvimento.

[**Figma**](https://www.figma.com/) - Editor gráfico de vetor e prototipagem de projetos de design baseado principalmente no navegador web, com ferramentas offline adicionais para aplicações desktop para GNU/Linux, macOS e Windows.

[**Github Icons**](https://gist.github.com/rxaviers/7360908) - Ícones para usar no Github.

[**List of Github Markdown Emojis**](https://dev.to/nikolab/complete-list-of-github-markdown-emoji-markup-5aia) - lista de emojis para arquivo markdown.

[**Markdown Guide**](https://www.markdownguide.org/basic-syntax/) - Guia da sintaxe de arquivos markdown.

#### Ferramentas de Desenvolvimento

[**Bootstrap**](https://getbootstrap.com/) - Framework CSS.

[**Chrome DevTools**](https://developer.chrome.com/docs/devtools/) - Conjunto de ferramentas de criação e depuração da web integradas ao Google Chrome.

[**Dicionário da TI**](https://www.opservices.com.br/dicionario-da-ti/) - 120 termos e siglas sobre tecnologia

[**Github Gist**](https://gist.github.com/) - Para fazer pequenas anotações e pequenos códigos no GitHub Gist

[**Insomnia**](https://insomnia.rest/download) - Ferramenta cliente de API REST, como o Postman, mas tem alguns recursos adicionais, como suporte a GraphQL, gRPC, entre outros.

[**JSON Editor Online**](https://jsoneditoronline.org/) - Ferramenta para visualizar e editar arquivos JSON.

[**PageSpeed Insights**](https://pagespeed.web.dev) - Também conhecido como PSI, é uma ferramenta online do Google que avalia a velocidade de carregamento de páginas da web.

[**Postman**](https://www.postman.com/) - Plataforma de API para desenvolvedores projetar, construir, testar e iterar suas APIs.

[**Como instalar o Postman no Linux**](https://terminalroot.com.br/2021/02/como-instalar-o-postman-no-ubuntu-e-em-qualquer-distro-linux.html)

[**Spring Initializr**](https://start.spring.io/) - Fornece uma interface web simples para gerar seu projeto a partir de uma estrutura de configurações pré-moldadas de versões do java/spring boot, grupo/nome do projeto, série de lista de dependências e etc.

[**Swagger Editor**](https://editor.swagger.io/) - Ferramenta online que permite criar manualmente a documentação da API. Ao utilizar YAML, faz com que o desenvolvedor não tenha dificuldades em descrever os seus serviços.

#### Ferramentas de Gestão

[**Confluence**](https://www.atlassian.com/br/software/confluence) - Software de documentação colaborativa

[**Jira**](https://www.atlassian.com/br/software/jira) - Ferramenta que permite o monitoramento de tarefas e acompanhamento de projetos garantindo o gerenciamento de todas as atividades em único lugar.

[**Notion**](https://www.notion.so/login) - Notas e gerenciamento de projetos online

[**Pipefy**](https://www.pipefy.com/pt-br/) - Gerenciador de projetos

[**Trello**](https://trello.com/) - Gerenciamento seus projetos com quadros
