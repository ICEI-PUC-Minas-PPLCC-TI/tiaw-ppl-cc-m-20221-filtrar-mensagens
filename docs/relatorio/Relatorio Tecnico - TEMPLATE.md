# Informações do Projeto
`MFilter` 

`Trabalho Interdisciplinar: Aplicações WEB;Ciência da Computação` 

## Participantes
> Os membros do grupo são: 
> - André Fazito
> - Arthur Torres
> - Barbara Soraggi
> - Bernardo D'Ávila
> - Camila Hollerbach
> - Henrique Lourenço Pinto Coelho
> - Marcelo Freitas

# Estrutura do Documento

- [Informações do Projeto](#informações-do-projeto)
  - [Participantes](#participantes)
- [Estrutura do Documento](#estrutura-do-documento)
- [Introdução](#introdução)
  - [Problema](#problema)
  - [Objetivos](#objetivos)
  - [Justificativa](#justificativa)
  - [Público-Alvo](#público-alvo)
- [Especificações do Projeto](#especificações-do-projeto)
  - [Personas e Mapas de Empatia](#personas-e-mapas-de-empatia)
  - [Histórias de Usuários](#histórias-de-usuários)
  - [Requisitos](#requisitos)
    - [Requisitos Funcionais](#requisitos-funcionais)
    - [Requisitos não Funcionais](#requisitos-não-funcionais)
  - [Restrições](#restrições)
- [Projeto de Interface](#projeto-de-interface)
  - [User Flow](#user-flow)
  - [Wireframes](#wireframes)
- [Metodologia](#metodologia)
  - [Divisão de Papéis](#divisão-de-papéis)
  - [Ferramentas](#ferramentas)
  - [Controle de Versão](#controle-de-versão)
- [**############## SPRINT 1 ACABA AQUI #############**](#-sprint-1-acaba-aqui-)
- [Projeto da Solução](#projeto-da-solução)
  - [Tecnologias Utilizadas](#tecnologias-utilizadas)
  - [Arquitetura da solução](#arquitetura-da-solução)
- [Avaliação da Aplicação](#avaliação-da-aplicação)
  - [Plano de Testes](#plano-de-testes)
  - [Ferramentas de Testes (Opcional)](#ferramentas-de-testes-opcional)
  - [Registros de Testes](#registros-de-testes)
- [Referências](#referências)


# Introdução

## Problema

Em grandes grupos e salas de conversa, devido ao elevado número de mensagens, sendo muitas delas não relevantes para o tópico principal do chat, é possível sentir uma frustração com a **falta de organização das mensagens importantes**, e por isso, gostaríamos de propor uma solução.

## Objetivos

Temos como objetivo geral propor um software para que usuários possam **organizar suas mensagens de forma fácil, customizável e objetiva.** 

>Como **objetivos específicos**, colocamos em evidência:
> - Garantir uma experiência fácil e intuitiva para o usuário
> - Oferecer variadas opções para a filtração de mensagens
> - Garantir uma interface bonita, minimalista e leve
> - Garantir a segurança de nossos usuários e criptografar suas mensagens

## Justificativa

  Após a realizarmos um quiz, com base nas respostas dadas as pessoas, percebemos suas frustrações de não poderem agrupar suas mensagens por ordem de prioridade e de não poderem separar suas mensagens mais importantes, para que sejam de fácil localização e acesso.

  Por isso, estamos realizando esse projeto com o intuito de ajudar os usuários a filtrarem as mensagens que eles julgam mais importantes, uma vez que, quando se tem muitos grupos diferentes e muitas pessoas em um só grupo, as mensagens acabam se perdendo e fica difícil achar aquela mensagem que você procura.

## Público-Alvo

Todos os indivíduos podem se beneficiar com esse projeto, mas nosso público alvo é qualquer pessoa que esteja inserida em um grande número de grupos ou que esteja em grupos que possuem muitos integrantes.

Mais especificamente, o foco desse projeto é para as pessoas que estão trabalhando/estagiando, estão na graduação ou que são CEO 's de grandes empresas que buscam filtrar e separar as mensagens importantes, das mensagens inúteis do dia a dia, uma vez que recebem um grande número de mensagens, já que possuem diversos grupos diferentes.

# Especificações do Projeto

A definição do problema e os pontos mais relevantes a serem tratados neste projeto foi consolidada a partir da participação dos usuários em formulário feito pelos membros da equipe. Os detalhes levantados nesse processo foram consolidados na forma de personas e histórias de usuários.

## Personas e Mapas de Empatia

> **Persona Ângela**
>    
> ![Persona](imaages/../images/persona1.png)
> 
> ![mapa](imaages/../images/mp1.PNG)
> 
> **Persona Bruna**
>    
> ![Persona](imaages/../images/persona2.png)
> 
> ![mapa](imaages/../images/mp2.PNG)
> 
> **Persona Pedro**
> 
> ![Persona](imaages/../images/persona3.png)
> 
> ![mapa](imaages/../images/mp3.PNG)
>

## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
| Ângela Mercury     | filtrar as informações importantes relacionadas ao meu curso.     | para caso alguém fale alguma coisa importante ou relevante relacionada a matéria, uma vez que, às vezes essas mensagens se perdem no meio de mensagens inúteis do dia a dia, como por exemplo futebol.              |
|Bruna Sampaio       | organizar e separar minhas mensagens pessoais e profissionais.      | para que assim consiga garantir notas melhores na faculdade, e consiga persuadir o seu sonho de, um dia, se tornar editora. |
|Pedro Alves         |organizar as mensagens dos meus vários grupos: de sair com amigos, de técnicas para bonsais, que é o meu hobby preferido, de minhas atividades esportivas e do meu trabalho.|para que eu consiga estar inteirado de todos os grupos de uma vez, sem me perder em todos eles.|

## Requisitos
Nosso projeto é definido por **requisitos funcionais**, que descrevem os principais aspectos do programa, assim como os **requisitos não funcionais**, que descrevem como o programa deve funcionar de uma forma mais geral. Estes requisitos estão apresentados abaixo.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001|dar ao usuário a opção de atribuir prioridade aos contatos.| ALTA | 
|RF-002|ter um sistema de tags que pode ser organizado por cores ou nomes. | ALTA |
|RF-003|apresentar a opção de destacar uma ou mais mensagens para todos os integrantes de um grupo.| ALTA |
|RF-004|ter um sistema de organização de mensagens por meio de pastas.| ALTA |
|RF-005|dar a opção de silenciar integrantes de um grupo individualmente.| MÉDIA |
|RF-006|ter um sistema de filtração de mensagens de áudio e mídias (fotos, vídeos e documentos).| MÉDIA |
|RF-007|apresentar a opção de implementar um sistema de cooldown para integrantes de um grupo.| MÉDIA |
|RF-008|dar a opção de implementar senhas para diferentes pastas e mensagens salvas.| BAIXA |
|RF-009|ter um modo noturno e um modo diurno.| BAIXA |
|RF-010|apresentar a opção individual de apagar as mensagens de um grupo após um certo tempo. | BAIXA |


### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O programa deve funcionar em mais de um sistema operacional (Android e iOS). | ALTA | 
|RNF-002| O programa deve funcionar sem internet para mensagens já filtradas e carregadas. |  ALTA |
|RNF-003| O programa deve respeitar as regras individuais de privacidade de cada aplicativo. |  BAIXA |
|RNF-004| O programa deve funcionar para mais de um aplicativo. |  BAIXA |

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o dia 28/04/2022 |
|02| Não pode ser desenvolvido um módulo de backend        |
|03|A equipe deve participar de todo o desenvolvimento do trabalho |

# Projeto de Interface

......  COLOQUE AQUI O SEU TEXTO DE INTRODUÇÃO ......

> Apresente as principais interfaces da solução. Discuta como 
> foram elaboradas de forma a atender os requisitos funcionais, não
> funcionais e histórias de usuário abordados nas [Especificações do
> Projeto](#especificações-do-projeto).

## User Flow

......  INCLUA AQUI O DIAGRAMA COM O FLUXO DO USUÁRIO NA APLICAÇÃO ......

> Fluxo de usuário (User Flow) é uma técnica que permite ao desenvolvedor
> mapear todo fluxo de telas do site ou app. Essa técnica funciona
> para alinhar os caminhos e as possíveis ações que o usuário pode
> fazer junto com os membros de sua equipe.
>
> **Links Úteis**:
> - [User Flow: O Quê É e Como Fazer?](https://medium.com/7bits/fluxo-de-usu%C3%A1rio-user-flow-o-que-%C3%A9-como-fazer-79d965872534)
> - [User Flow vs Site Maps](http://designr.com.br/sitemap-e-user-flow-quais-as-diferencas-e-quando-usar-cada-um/)
> - [Top 25 User Flow Tools & Templates for Smooth](https://www.mockplus.com/blog/post/user-flow-tools)
>
> **Exemplo**:
> 
> ![Exemplo de UserFlow](images/userflow.jpg)


## Wireframes

......  INCLUA AQUI OS WIREFRAMES DAS TELAS DA APLICAÇÃO COM UM BREVE DESCRITIVO ......

> Wireframes são protótipos das telas da aplicação usados em design de interface para sugerir a
> estrutura de um site web e seu relacionamentos entre suas
> páginas. Um wireframe web é uma ilustração semelhante ao
> layout de elementos fundamentais na interface.
> 
> **Links Úteis**:
> - [Ferramentas de Wireframes](https://rockcontent.com/blog/wireframes/)
> - [Figma](https://www.figma.com/)
> - [Adobe XD](https://www.adobe.com/br/products/xd.html#scroll)
> - [MarvelApp](https://marvelapp.com/developers/documentation/tutorials/)
> 
> **Exemplo**:
> 
> ![Exemplo de Wireframe](images/wireframe-example.png)


# Metodologia

Para a realização do projeto, adotamos a metodologia do Design Thinking e Scrum Framework, com isso, possibilitou uma ampla visão sobre nossos futuros clientes, e a divisão de cada etapa da Sprint, mantendo uma coerência . Iniciamos com o processo de Design Thinking, no Miro, etapas como Matriz CSD, Mapa de Stakeholders, Personas, Mapas de Empatia, Brainstorming de ideias, essas, foram etapas essenciais para compreendermos o desenvolvimentos desse projeto.

## Divisão de Papéis

|Integrantes      |Função       |
|-----------------|-------------|
|André Fazito     |Desenvolvedor|
|Arthur Torres    |Desenvolvedor|
|Barbara Soraggi  |Scrum Master |
|Bernardo D'Ávila |Desenvolvedor|
|Camila Hollerbach|Desenvolvedor|
|Henrique Lourenço|Desenvolvedor|
|Marcelo Freitas  |Desenvolvedor|
|Professores      |Product Owner|

## Ferramentas

......  COLOQUE AQUI O SEU TEXTO - SIGA O EXEMPLO DA TABELA ABAIXO  ......

| Ambiente  | Plataforma              |Link de Acesso |
|-----------|-------------------------|---------------|
|Processo de Design Thinkgin  | Miro |  https://miro.com/app/board/uXjVOBuEkiQ=/ | 
|Repositório de código | GitHub | https://github.com/ICEI-PUC-Minas-PPLCC-TI/tiaw-ppl-cc-m-20221-filtrar-mensagens/blob/master/docs/relatorio/Relatorio%20Tecnico%20-%20TEMPLATE.md |  
|Protótipo Interativo Desktop |Figma | https://www.figma.com/proto/7ooGBgBuhTfEbSfdmuBODS/TIAW-Prot%C3%B3tipo-Interativo-DESKTOP?node-id=1%3A80&scaling=scale-down&page-id=0%3A1&starting-point-node-id=1%3A730 | 
|Protótipo Interativo Mobile |Figma | https://www.figma.com/proto/bFc4DXWn8Avo1MnyDSk9Vc/TIAW-Prot%C3%B3tipo-Interativo-MOBILE?node-id=1%3A2&scaling=scale-down&page-id=0%3A1&starting-point-node-id=9%3A775 |
|Protótipo Interativo Mobile |Figma | https://figma.com/XXXXXXX |

>
> Liste as ferramentas empregadas no desenvolvimento do
> projeto, justificando a escolha delas, sempre que possível.
> 
> As ferramentas empregadas no projeto são:
> 
> - Editor de código.
> - Ferramentas de comunicação
> - Ferramentas de diagramação
> - Plataforma de hospedagem
> 
> O editor de código foi escolhido porque ele possui uma integração com o
> sistema de versão. As ferramentas de comunicação utilizadas possuem
> integração semelhante e por isso foram selecionadas. Por fim, para criar
> diagramas utilizamos essa ferramenta por melhor captar as
> necessidades da nossa solução.
> 
> **Links Úteis - Hospedagem**:
> - [Getting Started with Heroku](https://devcenter.heroku.com/start)
> - [Crie seu Site com o HostGator](https://www.hostgator.com.br/como-publicar-seu-site)
> - [GoDady](https://br.godaddy.com/how-to)
> - [GitHub Pages](https://pages.github.com/)

## Controle de Versão

......  COLOQUE AQUI O SEU TEXTO ......

> Discuta como a configuração do projeto foi feita na ferramenta de
> versionamento escolhida. Exponha como a gerência de tags, merges,
> commits e branchs é realizada. Discuta como a gerência de issues foi
> realizada.
> A ferramenta de controle de versão adotada no projeto foi o
> [Git](https://git-scm.com/), sendo que o [Github](https://github.com)
> foi utilizado para hospedagem do repositório `upstream`.
> 
> O projeto segue a seguinte convenção para o nome de branchs:
> 
> - `master`: versão estável já testada do software
> - `unstable`: versão já testada do software, porém instável
> - `testing`: versão em testes do software
> - `dev`: versão de desenvolvimento do software
> 
> Quanto à gerência de issues, o projeto adota a seguinte convenção para
> etiquetas:
> 
> - `bugfix`: uma funcionalidade encontra-se com problemas
> - `enhancement`: uma funcionalidade precisa ser melhorada
> - `feature`: uma nova funcionalidade precisa ser introduzida
>
> **Links Úteis**:
> - [Tutorial GitHub](https://guides.github.com/activities/hello-world/)
> - [Git e Github](https://www.youtube.com/playlist?list=PLHz_AreHm4dm7ZULPAmadvNhH6vk9oNZA)
> - [5 Git Workflows & Branching Strategy to deliver better code](https://zepel.io/blog/5-git-workflows-to-improve-development/)
>
> **Exemplo - GitHub Feature Branch Workflow**:
>
> ![Exemplo de Wireframe](images/Github-Workflow.png)

# **############## SPRINT 1 ACABA AQUI #############**


# Projeto da Solução

......  COLOQUE AQUI O SEU TEXTO ......

## Tecnologias Utilizadas

......  COLOQUE AQUI O SEU TEXTO ......

> Descreva aqui qual(is) tecnologias você vai usar para resolver o seu
> problema, ou seja, implementar a sua solução. Liste todas as
> tecnologias envolvidas, linguagens a serem utilizadas, serviços web,
> frameworks, bibliotecas, IDEs de desenvolvimento, e ferramentas.
> Apresente também uma figura explicando como as tecnologias estão
> relacionadas ou como uma interação do usuário com o sistema vai ser
> conduzida, por onde ela passa até retornar uma resposta ao usuário.
> 
> Inclua os diagramas de User Flow, esboços criados pelo grupo
> (stoyboards), além dos protótipos de telas (wireframes). Descreva cada
> item textualmente comentando e complementando o que está apresentado
> nas imagens.

## Arquitetura da solução

......  COLOQUE AQUI O SEU TEXTO E O DIAGRAMA DE ARQUITETURA .......

> Inclua um diagrama da solução e descreva os módulos e as tecnologias
> que fazem parte da solução. Discorra sobre o diagrama.
> 
> **Exemplo do diagrama de Arquitetura**:
> 
> ![Exemplo de Arquitetura](images/arquitetura-exemplo.png)


# Avaliação da Aplicação

......  COLOQUE AQUI O SEU TEXTO ......

> Apresente os cenários de testes utilizados na realização dos testes da
> sua aplicação. Escolha cenários de testes que demonstrem os requisitos
> sendo satisfeitos.

## Plano de Testes

......  COLOQUE AQUI O SEU TEXTO ......

> Enumere quais cenários de testes foram selecionados para teste. Neste
> tópico o grupo deve detalhar quais funcionalidades avaliadas, o grupo
> de usuários que foi escolhido para participar do teste e as
> ferramentas utilizadas.
> 
> **Links Úteis**:
> - [IBM - Criação e Geração de Planos de Teste](https://www.ibm.com/developerworks/br/local/rational/criacao_geracao_planos_testes_software/index.html)
> - [Práticas e Técnicas de Testes Ágeis](http://assiste.serpro.gov.br/serproagil/Apresenta/slides.pdf)
> -  [Teste de Software: Conceitos e tipos de testes](https://blog.onedaytesting.com.br/teste-de-software/)

## Ferramentas de Testes (Opcional)

......  COLOQUE AQUI O SEU TEXTO ......

> Comente sobre as ferramentas de testes utilizadas.
> 
> **Links Úteis**:
> - [Ferramentas de Test para Java Script](https://geekflare.com/javascript-unit-testing/)
> - [UX Tools](https://uxdesign.cc/ux-user-research-and-user-testing-tools-2d339d379dc7)

## Registros de Testes

......  COLOQUE AQUI O SEU TEXTO ......

> Discorra sobre os resultados do teste. Ressaltando pontos fortes e
> fracos identificados na solução. Comente como o grupo pretende atacar
> esses pontos nas próximas iterações. Apresente as falhas detectadas e
> as melhorias geradas a partir dos resultados obtidos nos testes.


# Referências

......  COLOQUE AQUI O SEU TEXTO ......

> Inclua todas as referências (livros, artigos, sites, etc) utilizados
> no desenvolvimento do trabalho.
> 
> **Links Úteis**:
> - [Formato ABNT](https://www.normastecnicas.com/abnt/trabalhos-academicos/referencias/)
> - [Referências Bibliográficas da ABNT](https://comunidade.rockcontent.com/referencia-bibliografica-abnt/)
