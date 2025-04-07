# Microsoft-Copilot-Studio
Definições e conceitos abordados em aula para o desenvolvimento prático das orientações explanadas.

Conteúdos programados:

- Conhecendo o Microsoft Copilot Studio
- O que é o Microsoft Copilot Studio?
- O que é a Power Patform?
- Qual a importância do copilot Studio no cenário da inteligência Artificial?
- Entendendo o licenciamento do Copilot
- Tipos de Copilot disponíveis

  A Microsoft Copilot Studio é uma ferramenta lançada em novembro de 2019 com o intuito de facilitar a criação de chatbots e, atualmente, agentes e copilotos estão agregados às suas funcionalidades. Antigamente denominada Power Virtual Agents, permitia apenas a criação de perguntas e respostas para a geração de inteligencia e revolucionar a inteligencia artificial sem código. Visada ao usuário de negócios, é low-code pois faz uso da power platform.
  
  Programadores podem implantar/agregar seus códigos na plataforma, configurando-a. Esse copilot Studio vai ser disponibilido...Por se tratar de uma ferramenta intermediária, fica entre usuario final e o conteúdo. Usuário final acessa uma plataforma (como whatsapp) e mandará uma mensagem para um agente (copiloto) conectado ao copilot studio, que fará o processamento das informações e conectará a base de dados que possui para retornar uma resposta válida(pre-programada com base no database) para o canal. O Copilot studio não é o canal oficial!

## 🌱Ciclo de Vida do copilot studio

  --> Criação do agente (agente inteligente) --> Conxão com a base de conhecimento (dataverse, sql, Azure as Service, Microsoft fabric) --> Criação de topicos específicos (Customização de conversas) --> Ações e Plugins (visão de produtos) --> Multiplos canais (Canais de publicação e rápida alteração) -->  Melhoria e monitoramento (Feedbacks - pesquisa de satisfação) --> Extensão com Azure (GPT ou outras extensões) -->

## 🏛️Arquitetura

  Segue o padrão com base em estágios:
  
- Estagio 1: São as conversas padrões de agradecimentos, cumprimentos, saudações e serviços que oferece. Apenas uma conversa simples e sem especificações.
- Estagio 2: Geração de respostas generativas. Por pafrão usa o GPT e conteúdos da internet.
  Aqui também temos modelos de extensão
- Estagio 3: Temos os estágios anteriores que escalam com o humano. Fazer ligações e interagir com funcionários como ferramenta de integração

## 🖥️Power Platform

  Conjunto de ferramentas desenvolvidas pela Microsoft com o objetivo de democratizar o desenvolvimento de soluções empresariais, oferecendo plataformas low-code/no-code para criação de aplicações, automação de processos, análise de dados e desenvolvimento de agentes inteligentes. Inicialmente com recursos limitados, a plataforma evoluiu significativamente para atender às demandas de transformação digital corporativa, permitindo que usuários de negócio desenvolvam soluções com menor dependência do setor de Tecnologia da Informação (TI).

- Power Apps - Ferramenta de desenvolvimento low-code para criação de aplicativos personalizados que podem ser executados em navegadores ou dispositivos móveis. Integra dados de diversas fontes com foco em eficiência operacional e digitalização de processos internos.

- Power Automate - Automação de processos.
Processos online: fluxos da nuvem - Serviços online como do google, da Microsoft, AWS, API
Processos locais: Fluxos de desktops - carregamento de arquivos
- Power BI - Plataforma de Business Intelligence que permite conectar, transformar, modelar e visualizar dados. Possui suporte a linguagem DAX (Data Analysis Expressions) e Power Query (M), permitindo a construção de dashboards interativos e relatórios com foco em tomada de decisão orientada a dados.
- Copilot Studio - Ferramenta para desenvolvimento de agentes conversacionais (chatbots) com suporte a modelos de linguagem natural. Permite integração com fontes de dados corporativas, além da personalização do comportamento do bot com Power Fx, fluxos do Power Automate e extensões via código.
- Power Pages - Plataforma para criação de sites corporativos e portais externos com abordagem low-code. Suporta autenticação de usuários, integração com o Microsoft Dataverse, customizações via HTML/CSS e recursos avançados para desenvolvedores.

- Data connectors -Conectores prontos que permitem integração da Power Platform com mais de 900 fontes de dados (Microsoft e de terceiros). Existem conectores padrão (Standard) e premium (Premium), com suporte a autenticação OAuth, chamadas REST e outras formas de comunicação com serviços externos.
- AI builder -Módulo que permite incorporar modelos de Inteligência Artificial nas soluções da Power Platform, mesmo sem conhecimento prévio de ciência de dados. Inclui modelos prontos para classificação de texto, extração de formulários, detecção de objetos, previsão de valores, entre outros, além de suporte para treinar modelos personalizados com dados do usuário.
- Microsoft Dataverse -Banco de dados relacional baseado em nuvem, projetado para armazenar e gerenciar dados usados por aplicativos empresariais. Oferece suporte a entidades relacionais, controle de acesso, auditoria, versionamento e regras de negócios, sendo o backend nativo do Power Apps e Power Pages.
- Power Fx - Linguagem de fórmula open-source e declarativa baseada em Excel, utilizada no Power Apps e em outras partes da Power Platform. Projetada para facilitar a criação de expressões de lógica de negócios e manipulação de dados em ambientes low-code.
- Ambientes - Estruturas de isolamento lógico utilizadas para organização, governança e controle de acesso dentro da Power Platform. Cada ambiente pode conter seus próprios recursos, dados, permissões e conectores, sendo uma prática recomendada para separar ambientes de desenvolvimento, homologação e produção.


## Conectores

Desenvolvimento de conexões de serviços de diversas ferramentas de um serviço online para um serviço local. Usuários de negócios apenas passam suas credenciais.


## Importância no cenário da IA

Ela veio para automatizar os processos locais, como tarefas repetitivas cotidianas, tornando mais eficiente. Ela ainda faz uma boa gestão das informações com a análise de uma quantidade de dados massiva, servindo até como seu assistente pessoal e prestador de serviços aos seu clientes 24h por dia, sem a necessidade da equipe de TI constantemente.
O copilot Studio por sua vez pode acelerar esse processo de criação e aplicabilidade.

## Licenciamento do Copilot

Há diversos tipos de serviços oferecidos por essa ferramenta que se distinguem entre si por publicações, usos e canais de disponibilidade. Os planos ofertados podem ser: Copilot Studio for Teams, Premium, for M365 e Pay-as-you-go. Os licenciamentos dependem muito da sua necessidade.

## Tipos de Copilot

A ferramenta principal da Microsoft, que faz uso de agentes e diferentes ferramentas para o desenvolvimento de um copiloto é a Copilot Studio, como o próprio nome sugere.
  



