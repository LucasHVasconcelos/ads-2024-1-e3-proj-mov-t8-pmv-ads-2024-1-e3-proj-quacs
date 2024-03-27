# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

Definição do problema e ideia de solução a partir da perspectiva do usuário. É composta pela definição do  diagrama de personas, histórias de usuários, requisitos funcionais e não funcionais além das restrições do projeto.

Apresente uma visão geral do que será abordado nesta parte do documento, enumerando as técnicas e/ou ferramentas utilizadas para realizar a especificações do projeto

## Personas

1. **Ana, a Usuária Casual:**
   - **Idade:** 25 anos
   - **Profissão:** Estudante universitária
   - **Conhecimento em Tecnologia:** Básico
   - **Uso de Redes Sociais:** Regular, principalmente para se manter em contato com amigos e seguir páginas de interesse.
   - **Interesses:** Moda, viagens e fotografia
   - **Comportamento:** Ana busca uma experiência simples e intuitiva nas redes sociais, preferindo conteúdos que sejam relevantes aos seus interesses sem a necessidade de configurações complexas.
     
2. **Pedro, o Entusiasta de Tecnologia:**
   - **Idade:** 30 anos
   - **Profissão:** Desenvolvedor de software
   - **Conhecimento em Tecnologia:** Avançado
   - **Uso de Redes Sociais:** Ativo em várias plataformas, tanto para networking profissional quanto para interesses pessoais.
   - **Interesses:** Tecnologia, games e programação
   - **Comportamento:** Pedro está sempre em busca de novidades tecnológicas e ferramentas que otimizem sua experiência online. Ele valoriza a personalização e está disposto a experimentar novas plataformas que ofereçam recursos avançados.

3. **Mariana, a Profissional de Marketing:**
   - **Idade:** 35 anos
   - **Profissão:** Gerente de marketing digital
   - **Conhecimento em Tecnologia:** Intermediário
   - **Uso de Redes Sociais:** Estratégico, para promover marcas e produtos, bem como monitorar tendências e engajamento.
   - **Interesses:** Marketing digital, análise de dados e branding
   - **Comportamento:** Mariana utiliza as redes sociais como parte de sua estratégia de trabalho, buscando ferramentas que facilitem a segmentação de público e a análise de métricas de desempenho. Ela valoriza plataformas que ofereçam insights detalhados sobre o comportamento do usuário e o impacto das campanhas.


## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Ana, a Usuária Casual| Poder personalizar minha feed de acordo com meus interesses          |  Ver apenas conteúdos relevantes para mim               |
|Pedro, o Entusiasta de Tecnologia       | Ter acesso a configurações avançadas de personalização da minha feed                 | Adaptar a experiência às minhas preferências específicas |
| Mariana, a Profissional de Marketing | Poder segmentar o público-alvo das minhas publicações e campanhas | Direcionar melhor meus esforços de marketing |


## Modelagem do Processo de Negócio 

### Análise da Situação Atual

O projeto Quacs surge em resposta aos problemas enfrentados pelos usuários das redes sociais atuais, que frequentemente se deparam com uma inundação de conteúdo não relevante e fragmentação na comunicação entre diferentes grupos. O modelo atual das redes sociais envolve algoritmos que determinam o que é exibido nas feeds dos usuários, mas muitas vezes falham em oferecer uma experiência personalizada e significativa. Além disso, encontrar e participar de comunidades específicas dentro das redes sociais pode ser uma tarefa desafiadora e demorada.

O Quacs busca resolver esses problemas oferecendo uma plataforma inovadora que simplifica a descoberta, interação e engajamento com comunidades e conteúdos de interesse dos usuários. Ao priorizar a personalização e integração eficaz do conteúdo de diferentes grupos, o Quacs visa oferecer uma experiência mais relevante e significativa, promovendo uma interação mais rica e focada dentro das redes sociais. 

### Descrição Geral da Proposta

Uma das dificuldades enfrentadas pelo projeto Quacs pode ser a incapacidade de utilizar algoritmos de preferência para os usuários devido a restrições de recursos, complexidade técnica ou falta de dados suficientes para treinamento. A implementação de algoritmos de recomendação personalizada requer recursos significativos de desenvolvimento e manutenção, além de uma quantidade substancial de dados sobre as preferências dos usuários. No entanto, pode ser desafiador adquirir e processar esses dados de maneira eficaz, especialmente considerando preocupações com privacidade e segurança.

Como resultado, o Quacs pode enfrentar dificuldades em oferecer uma experiência altamente personalizada para cada usuário, o que pode limitar sua capacidade de atender às expectativas e necessidades individuais. Para contornar essa dificuldade, o projeto pode precisar explorar abordagens alternativas, como permitir que os usuários personalizem manualmente suas preferências de conteúdo ou oferecer opções de filtragem mais avançadas. Além disso, parcerias estratégicas com plataformas ou serviços externos que oferecem algoritmos de recomendação personalizada podem ser consideradas para complementar as capacidades do Quacs e proporcionar uma experiência mais rica e personalizada para os usuários.

### Processo 1 – NOME DO PROCESSO

Apresente aqui o nome e as oportunidades de melhorias para o processo 1. Em seguida, apresente o modelo do processo 1, descrito no padrão BPMN. 

![Processo 1](img/02-bpmn-proc1.png)

### Processo 2 – NOME DO PROCESSO

Apresente aqui o nome e as oportunidades de melhorias para o processo 2. Em seguida, apresente o modelo do processo 2, descrito no padrão BPMN.

![Processo 2](img/02-bpmn-proc2.png)

## Indicadores de Desempenho

Apresente aqui os principais indicadores de desempenho e algumas metas para o processo. Atenção: as informações necessárias para gerar os indicadores devem estar contempladas no diagrama de classe. Colocar no mínimo 5 indicadores. 

Usar o seguinte modelo: 

![Indicadores de Desempenho](img/02-indic-desemp.png)
Obs.: todas as informações para gerar os indicadores devem estar no diagrama de classe a ser apresentado a posteriori. 

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto. Para determinar a prioridade de requisitos, aplicar uma técnica de priorização de requisitos e detalhar como a técnica foi aplicada.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| Permitir que o usuário cadastre tarefas | ALTA | 
|RF-002| Emitir um relatório de tarefas no mês   | MÉDIA |

### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O sistema deve ser responsivo para rodar em um dispositivos móvel | MÉDIA | 
|RNF-002| Deve processar requisições do usuário em no máximo 3s |  BAIXA | 

Com base nas Histórias de Usuário, enumere os requisitos da sua solução. Classifique esses requisitos em dois grupos:

- [Requisitos Funcionais
 (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
 correspondem a uma funcionalidade que deve estar presente na
  plataforma (ex: cadastro de usuário).
- [Requisitos Não Funcionais
  (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
  correspondem a uma característica técnica, seja de usabilidade,
  desempenho, confiabilidade, segurança ou outro (ex: suporte a
  dispositivos iOS e Android).
Lembre-se que cada requisito deve corresponder à uma e somente uma
característica alvo da sua solução. Além disso, certifique-se de que
todos os aspectos capturados nas Histórias de Usuário foram cobertos.

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |

Enumere as restrições à sua solução. Lembre-se de que as restrições geralmente limitam a solução candidata.

> **Links Úteis**:
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)

## Diagrama de Casos de Uso

O diagrama de casos de uso é o próximo passo após a elicitação de requisitos, que utiliza um modelo gráfico e uma tabela com as descrições sucintas dos casos de uso e dos atores. Ele contempla a fronteira do sistema e o detalhamento dos requisitos funcionais com a indicação dos atores, casos de uso e seus relacionamentos. 

As referências abaixo irão auxiliá-lo na geração do artefato “Diagrama de Casos de Uso”.

> **Links Úteis**:
> - [Criando Casos de Uso](https://www.ibm.com/docs/pt-br/elm/6.0?topic=requirements-creating-use-cases)
> - [Como Criar Diagrama de Caso de Uso: Tutorial Passo a Passo](https://gitmind.com/pt/fazer-diagrama-de-caso-uso.html/)
> - [Lucidchart](https://www.lucidchart.com/)
> - [Astah](https://astah.net/)
> - [Diagrams](https://app.diagrams.net/)

# Matriz de Rastreabilidade

A matriz de rastreabilidade é uma ferramenta usada para facilitar a visualização dos relacionamento entre requisitos e outros artefatos ou objetos, permitindo a rastreabilidade entre os requisitos e os objetivos de negócio. 

A matriz deve contemplar todos os elementos relevantes que fazem parte do sistema, conforme a figura meramente ilustrativa apresentada a seguir.

![Exemplo de matriz de rastreabilidade](img/02-matriz-rastreabilidade.png)

> **Links Úteis**:
> - [Artigo Engenharia de Software 13 - Rastreabilidade](https://www.devmedia.com.br/artigo-engenharia-de-software-13-rastreabilidade/12822/)
> - [Verificação da rastreabilidade de requisitos usando a integração do IBM Rational RequisitePro e do IBM ClearQuest Test Manager](https://developer.ibm.com/br/tutorials/requirementstraceabilityverificationusingrrpandcctm/)
> - [IBM Engineering Lifecycle Optimization – Publishing](https://www.ibm.com/br-pt/products/engineering-lifecycle-optimization/publishing/)


# Gerenciamento de Projeto

De acordo com o PMBoK v6 as dez áreas que constituem os pilares para gerenciar projetos, e que caracterizam a multidisciplinaridade envolvida, são: Integração, Escopo, Cronograma (Tempo), Custos, Qualidade, Recursos, Comunicações, Riscos, Aquisições, Partes Interessadas. Para desenvolver projetos um profissional deve se preocupar em gerenciar todas essas dez áreas. Elas se complementam e se relacionam, de tal forma que não se deve apenas examinar uma área de forma estanque. É preciso considerar, por exemplo, que as áreas de Escopo, Cronograma e Custos estão muito relacionadas. Assim, se eu amplio o escopo de um projeto eu posso afetar seu cronograma e seus custos.

## Gerenciamento de Tempo

Com diagramas bem organizados que permitem gerenciar o tempo nos projetos, o gerente de projetos agenda e coordena tarefas dentro de um projeto para estimar o tempo necessário de conclusão.

![Diagrama de rede simplificado notação francesa (método francês)](img/02-diagrama-rede-simplificado.png)

O gráfico de Gantt ou diagrama de Gantt também é uma ferramenta visual utilizada para controlar e gerenciar o cronograma de atividades de um projeto. Com ele, é possível listar tudo que precisa ser feito para colocar o projeto em prática, dividir em atividades e estimar o tempo necessário para executá-las.

![Gráfico de Gantt](img/02-grafico-gantt.png)

## Gerenciamento de Equipe

O gerenciamento adequado de tarefas contribuirá para que o projeto alcance altos níveis de produtividade. Por isso, é fundamental que ocorra a gestão de tarefas e de pessoas, de modo que os times envolvidos no projeto possam ser facilmente gerenciados. 

![Simple Project Timeline](img/02-project-timeline.png)

## Gestão de Orçamento

O processo de determinar o orçamento do projeto é uma tarefa que depende, além dos produtos (saídas) dos processos anteriores do gerenciamento de custos, também de produtos oferecidos por outros processos de gerenciamento, como o escopo e o tempo.

![Orçamento](img/02-orcamento.png)
