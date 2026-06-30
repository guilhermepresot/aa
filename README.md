# Metodologia

Detalhes sobre a organização do grupo e o ferramental empregado.

## Ferramentas

Relação de ferramentas empregadas pelo grupo durante o projeto.

| Categoria | Ferramenta | Justificativa | Link de acesso |
|---|---|---|---|
| Editor de código | VS Code + JSON Server | Editor de código utilizado no desenvolvimento, com o JSON Server simulando uma API REST para fornecer e armazenar os dados durante o desenvolvimento das telas | - |
| Comunicação | WhatsApp | Ferramenta utilizada no dia a dia pela equipe, facilitando alinhamentos e comunicação | - |
| Diagramação / Design Thinking | Miro | Quadro colaborativo usado para mapear o processo de Design Thinking (Matriz CSD, Mapa de Stakeholders) | [Acessar](https://miro.com/app/board/uXjVGiKWrH4=/?share_link_id=736897638297) |
| Prototipação | Figma | Criação de wireframes e do protótipo interativo navegável | [Acessar](https://www.figma.com/proto/KKf7LQEyghzePUoGEpu5hS/Tiaw----Structa?node-id=1-13&t=WNjbVHuP1sh4yTUj-1&scaling=contain&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=1%3A2) |
| Versionamento | GitHub | Controle de versão e hospedagem do repositório de código-fonte do projeto | [Acessar](https://github.com/ICEI-PUC-Minas-PMGES-TI/pmg-es-2026-1-ti1-0427100-g5-manutencao-do-predio-escolar/tree/master) |
| Hospedagem | Render | Hospedagem da aplicação em ambiente de produção, permitindo acesso ao sistema fora do ambiente local | - |

## Gerenciamento do Projeto

### Organização da Equipe e Divisão de Papéis

A equipe organizou o desenvolvimento do projeto em **3 sprints**, seguindo uma adaptação do framework Scrum. Cada sprint contou com reuniões de planejamento e revisão (início e fim de cada ciclo), realizadas de forma informal entre os membros via WhatsApp.

A organização e o acompanhamento do andamento das sprints ficaram a cargo de **Larissa Cravo Carvalho Câmara Santos** e **Guilherme Miranda Presot**, que lideraram a definição de prioridades e o acompanhamento das entregas da equipe. Além da liderança, ambos também atuaram como desenvolvedores, assim como os demais membros, cada um responsável pela implementação de uma ou mais telas do sistema.

As sprints foram organizadas da seguinte forma:

- **Sprint 1** — Implementação das telas iniciais do sistema;
- **Sprint 2** — Continuidade da implementação das telas restantes;
- **Sprint 3** — Integração de todas as telas desenvolvidas e implementação da tela de login.

A divisão de tarefas por funcionalidade ficou definida da seguinte forma:

- **Larissa Cravo Carvalho Câmara Santos** — Cadastro de queixas e gerenciamento;
- **Guilherme Miranda Presot** — Listagem de enquetes do aluno e sistema de votação;
- **Guilherme Ferreira Valadares** — Apresentação de métricas e orçamentos;
- **Pedro Henrique da Silva Fonseca** — Listagem de tarefas e atribuição de tarefas a funcionários;
- **Guilherme Gonçalves Meireles** — Listagem de principais queixas e da tarefa expandida.

## Quadro de Controle de Tarefas (Kanban)

A equipe utilizou um quadro Kanban com as colunas **Backlog**, **Fazendo** e **Feito** para o controle das tarefas ao longo das 3 sprints do projeto.

### Sprint 1 e 2 — Implementação das telas

<img width="851" height="552" alt="image" src="https://github.com/user-attachments/assets/94b74ba4-660d-49cd-8ca1-168a86b0fb6b" />


### Sprint 3 — Integração e finalização

<img width="845" height="632" alt="image" src="https://github.com/user-attachments/assets/4287d1a3-45e3-44b4-bb16-a4aba7d82394" />

## Funcionalidades

Esta seção apresenta as funcionalidades da solução.

##### Funcionalidade 1 - Login

Permite que os usuários (aluno, funcionário e diretora) acessem o sistema informando e-mail, senha e tipo de perfil.

- **Estrutura de dados:** [Usuários](#estrutura-de-dados-usuarios)
- **Instruções de acesso:**
  - Acesse a página inicial do sistema
  - Informe e-mail, senha e tipo de usuário
  - Ao confirmar, o sistema redireciona automaticamente para a tela inicial correspondente ao perfil (aluno, funcionário ou diretora)
- **Tela da funcionalidade:**

![Tela de Login](images/login.png)

##### Funcionalidade 2 - Cadastro de Queixas (Aluno)

Permite que o aluno registre um problema de infraestrutura encontrado na escola, incluindo título, local, descrição e uma imagem do problema.

- **Estrutura de dados:** [Queixas](#estrutura-de-dados-queixas)
- **Instruções de acesso:**
  - Efetue login como aluno
  - Acesse a opção "Reportar problema"
  - Preencha título, local, descrição e anexe uma imagem (opcional)
  - Envie a queixa
- **Tela da funcionalidade:**

![Tela de Cadastro de Queixas](images/cadastro-queixas.png)

##### Funcionalidade 3 - Enquetes e Votação (Aluno)

Permite que o aluno visualize as queixas registradas por outros alunos e vote a favor ou contra a prioridade de resolução de cada uma.

- **Estrutura de dados:** [Enquetes](#estrutura-de-dados-enquetes)
- **Instruções de acesso:**
  - Efetue login como aluno
  - Acesse a opção "Enquetes"
  - Visualize as queixas em votação e registre seu voto
- **Tela da funcionalidade:**

![Tela de Enquetes](images/enquetes.png)

##### Funcionalidade 4 - Gestão de Queixas (Diretora)

Permite que a diretora visualize todas as queixas registradas pelos alunos, acompanhe seu status e acesse o detalhamento de cada uma.

- **Estrutura de dados:** [Queixas](#estrutura-de-dados-queixas)
- **Instruções de acesso:**
  - Efetue login como diretora
  - Acesse o Dashboard
  - Visualize a lista de queixas e clique em uma delas para ver os detalhes
- **Tela da funcionalidade:**

![Tela do Dashboard da Diretora](images/dashboard.png)

##### Funcionalidade 5 - Atribuição de Tarefas a Funcionários (Diretora)

Permite que a diretora atribua uma queixa registrada a um funcionário responsável, transformando-a em uma tarefa.

- **Estrutura de dados:** [Tarefas](#estrutura-de-dados-tarefas)
- **Instruções de acesso:**
  - Efetue login como diretora
  - Acesse a opção "Funcionários"
  - Selecione o funcionário e confirme a atribuição da tarefa
- **Tela da funcionalidade:**

![Tela de Atribuição de Funcionários](images/atribuir-funcionarios.png)

##### Funcionalidade 6 - Listagem e Acompanhamento de Tarefas (Funcionário)

Permite que o funcionário visualize as tarefas atribuídas a ele, com detalhes do problema a ser resolvido.

- **Estrutura de dados:** [Tarefas](#estrutura-de-dados-tarefas)
- **Instruções de acesso:**
  - Efetue login como funcionário
  - Acesse o painel do funcionário
  - Visualize a listagem de tarefas e clique em uma tarefa para ver os detalhes
- **Tela da funcionalidade:**

![Tela de Listagem de Tarefas](images/listagem-tarefas.png)

##### Funcionalidade 7 - Visualização de Métricas e Orçamentos (Diretora)

Permite que a diretora visualize indicadores gerais (incidentes, tarefas resolvidas, gastos por setor) e cadastre o orçamento referente à resolução de uma queixa.

- **Estrutura de dados:** [Orçamentos](#estrutura-de-dados-orcamentos), [Métricas](#estrutura-de-dados-metricas)
- **Instruções de acesso:**
  - Efetue login como diretora
  - Acesse a opção "Métricas"
  - Visualize os indicadores ou cadastre um novo gasto referente a uma queixa
- **Tela da funcionalidade:**

![Tela de Métricas](images/metricas.png)
