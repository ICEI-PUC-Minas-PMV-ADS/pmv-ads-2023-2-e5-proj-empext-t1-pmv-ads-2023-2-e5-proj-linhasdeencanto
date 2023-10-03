# Especificações do Projeto

A definição exata do problema e os pontos mais relevantes a serem tratados neste projeto foi consolidada com a participação do parceiro do projeto junto com a equipe. Os detalhes levantados nesse processo foram consolidados na forma de personas e histórias de usuários.

## Arquitetura e Tecnologias

O projeto adotará uma arquitetura moderna e escalável para atender às necessidades do Studio Feminino. A solução será desenvolvida utilizando as seguintes tecnologias:

<ul>
  <li>Frontend: A interface do usuário será desenvolvida utilizando HTML, CSS e JavaScript.</li>
  <li>Backend: A lógica de negócio será desenvolvida utilizando PHP e MySQL.</li>
</ul>

As tecnologias escolhidas foram as mais adequadas para atender aos requisitos do projeto, que são:

<ul>
  <li>Fácil de usar: HTML, CSS e JavaScript são tecnologias de fácil aprendizado e uso, o que facilita o desenvolvimento da interface do usuário.</li>
  <li>Acessível: O PHP é uma linguagem de programação amplamente utilizada e que está disponível em uma variedade de plataformas, o que garante que a solução será acessível a um grande público.</li>
  <li>Eficiente: O MySQL é um banco de dados relacional de alto desempenho, o que garante que a solução será eficiente no armazenamento e recuperação de dados.</li>
</ul>


## Project Model Canvas

Colocar a imagem do modelo construído apresentando a proposta de solução.

> **Links Úteis**:
> Disponíveis em material de apoio do projeto


## GitHub Project (KANBAN)

O projeto Kanban do GitHub é uma ferramenta poderosa para gerenciar e visualizar o fluxo de trabalho de projetos de desenvolvimento de software. Baseado no sistema Kanban, originário do Lean Manufacturing, o GitHub Kanban oferece uma abordagem flexível e eficaz para organizar tarefas, acompanhar o progresso e melhorar a colaboração em equipes de desenvolvimento.

A vantagem de usá-lo diretamente no GitHub é a integração perfeita com seus repositórios. Você pode vincular facilmente problemas, pull requests e outros itens diretamente ao seu quadro Kanban, o que facilita a associação de tarefas a código-fonte e oferece uma visão holística do seu projeto.

Estamos incorcorando o modelo, haja visto a possibilidade de visão macro do controle de tarefas. O mesmo pode ser acessado através do link abaixo:
https://github.com/orgs/ICEI-PUC-Minas-PMV-ADS/projects/716/views/1

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto. Para determinar a prioridade de requisitos, aplicar uma técnica de priorização de requisitos e detalhar como a técnica foi aplicada.

### Requisitos Funcionais

|       ID      |                Descrição              |   Prioridade  |
| ------------- | ------------------------------------- |-------------  |
|      RF-1     | A aplicação deve permitir que os usuários façam login.           |      Alta     |
|      RF-2     | A aplicação deve permitir que os usuário alterem o cadastro.               |      Alta     |
|      RF-3     | A aplicação deve permitir que os usuários façam cadastro. |      Alta    |
|      RF-4     | A aplicação deve permitir que os usuários realizem pagamento dentro do site                  |      Alta     |
|      RF-5     | A aplicação deve permitir que o administrador gerencie o estoque                |      Média    |
|      RF-6     | A aplicação deve permitir gerenciar cadastro de usuários pelo administrador. (incluir/alterar/excluir )                 |      Média    |
|      RF-7     | A aplicação deve exibir ose produtos com imagens, descrições e preços.              |      Alta    |
|      RF-8     | A aplicação deve permitir que os usuários busquem os produtos por nome.                   |      Baixa    |
|      RF-9     | A aplicação deve apresentar as avaliações e comentários dos clientes para cada produto.            |      Baixa    |
|      RF-10    | A aplicação deve permitir o gerenciamento do carrinho de compras    |      Média    |

### Requisitos não Funcionais

|       ID      |                Descrição              |   Prioridade  |
| ------------- | ------------------------------------- |-------------  |
|     RNF-1     | A aplicação será publicado em um ambiente na Internet. (hostinger) | ALTA | 
|     RNF-2     | A aplicação será compatível com os principais navegadores do mercado. |  ALTA | 
|     RNF-3     | A aplicação deve ser confiável, deve atender às suas especificações. |  MÉDIA | 



## Restrições

As questões que limitam a execução desse projeto e que se configuram como obrigações claras para o desenvolvimento do projeto em questão são apresentadas 
na tabela a seguir.

|       ID      |                Descrição              |
| ------------- | ------------------------------------- |
|      RE-1     | A aplicação deve se restringir às tecnologias básicas da Web de FrontEnd e Backend |
|      RE-2     | A aplicação deverá ser entregue no final do semestre letivo             |
|      RE-3     | A aplicação deve estar em conformidade com as leis e normas vigentes         |

## Diagrama de Casos de Uso

O diagrama de casos de uso é o próximo passo após a elicitação de requisitos, que utiliza um modelo gráfico e uma tabela com as descrições sucintas dos casos de uso e dos atores. Ele contempla a fronteira do sistema e o detalhamento dos requisitos funcionais com a indicação dos atores, casos de uso e seus relacionamentos. 

As referências abaixo irão auxiliá-lo na geração do artefato “Diagrama de Casos de Uso”.

> **Links Úteis**:
> - [Criando Casos de Uso](https://www.ibm.com/docs/pt-br/elm/6.0?topic=requirements-creating-use-cases)
> - [Como Criar Diagrama de Caso de Uso: Tutorial Passo a Passo](https://gitmind.com/pt/fazer-diagrama-de-caso-uso.html/)
> - [Lucidchart](https://www.lucidchart.com/)
> - [Astah](https://astah.net/)
> - [Diagrams](https://app.diagrams.net/)

## Modelo ER (Projeto Conceitual)

O Modelo ER representa através de um diagrama como as entidades (coisas, objetos) se relacionam entre si na aplicação interativa.

Sugestão de ferramentas para geração deste artefato: LucidChart e Draw.io.

A referência abaixo irá auxiliá-lo na geração do artefato “Modelo ER”.

> - [Como fazer um diagrama entidade relacionamento | Lucidchart](https://www.lucidchart.com/pages/pt/como-fazer-um-diagrama-entidade-relacionamento)

## Projeto da Base de Dados

O projeto da base de dados corresponde à representação das entidades e relacionamentos identificadas no Modelo ER, no formato de tabelas, com colunas e chaves primárias/estrangeiras necessárias para representar corretamente as restrições de integridade.
