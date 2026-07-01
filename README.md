# Introdução

Informações básicas do projeto.

* **Projeto:** Structa
* **Repositório GitHub:** [Repositório](https://github.com/ICEI-PUC-Minas-PMGES-TI/pmg-es-2026-1-ti1-0427100-g5-manutencao-do-predio-escolar/tree/master)
* **Membros da equipe:**

  * [Larissa Cravo Carvalho Câmara Santos](https://github.com/L4r1ss4Cr4v0) 
  * [Guilherme Miranda Presot](https://github.com/guilhermepresot) 
  * [Guilherme Gonçalves Meireles](https://github.com/GuiMeirelesK) 
  * [Guilherme Ferreira Valadares](https://github.com/guilhermevaladares7) 
  * [Pedro Henrique da Silva Fonseca](https://github.com/pedrohenriquesf0701) 

A documentação do projeto é estruturada da seguinte forma:

1. Introdução
2. Contexto
3. Product Discovery
4. Product Design 
5. Metodologia
6. Solução
7. Referências Bibliográficas

✅ [Documentação de Design Thinking (MIRO)](files/G5.pdf)

# Contexto

Detalhes sobre o espaço de problema, os objetivos do projeto, sua justificativa e público-alvo.

## Problema

No ambiente escolar, é comum a ocorrência de problemas estruturais e organizacionais, como equipamentos danificados e necessidade de manutenção em salas e áreas mais utilizadas. No entanto, esses problemas muitas vezes não são comunicados de forma eficiente à gestão, ocorrendo por meio de interações informais, descentralizadas ou até mesmo inexistentes, o que dificulta sua identificação e resolução.
Esse cenário está presente em instituições de ensino que não possuem um processo estruturado para registro e acompanhamento dessas demandas. Como consequência, a direção enfrenta dificuldades para organizar os problemas, enquanto alunos e funcionários convivem com situações que impactam diretamente o funcionamento do ambiente escolar e a qualidade das atividades realizadas no dia a dia.


## Objetivos

O objetivo geral deste trabalho é desenvolver um software capaz de solucionar os problemas de comunicação e organização de demandas no ambiente escolar, proporcionando uma forma mais estruturada de registro e acompanhamento das necessidades existentes.
Como objetivos específicos, destacam-se: permitir que os alunos registrem problemas e participem das demandas por meio de votação. Possibilitar que a gestão escolar e os funcionários responsáveis pela limpeza acompanhem e gerenciem as solicitações de forma eficiente. Para promover maior organização e transparência no processo de identificação e resolução dos problemas no ambiente escolar.


## Justificativa

A escolha deste projeto se justifica pela necessidade de melhorar a organização e a comunicação no ambiente escolar, especialmente no que se refere à identificação e resolução de problemas cotidianos. A ausência de um processo estruturado para o registro dessas demandas pode gerar desorganização, retrabalho e demora na solução, impactando diretamente a qualidade do ambiente para alunos e funcionários.
Além disso, a definição dos objetivos específicos está relacionada à busca por maior eficiência e transparência nesse processo, permitindo compreender melhor as necessidades dos usuários. A equipe baseou-se em discussões internas para identificar os principais pontos de dificuldade, o que orientou a escolha de aprofundar aspectos como organização das informações, acompanhamento das solicitações e participação dos alunos na votação dos problemas.


## Público-Alvo

A solução é voltada para o ambiente educacional, especialmente instituições de ensino que enfrentam dificuldades na organização e comunicação de demandas internas. O público-alvo é composto principalmente por alunos, direção escolar e funcionários responsáveis pela manutenção e limpeza.
Os alunos representam a maior parte dos usuários e, em geral, possuem familiaridade com tecnologia e dispositivos digitais, sendo capazes de interagir facilmente com sistemas simples e intuitivos. Eles são responsáveis por registrar problemas e participar da priorização das demandas por meio de votação.
A direção escolar, representada pela diretora, possui um papel administrativo, sendo responsável por acompanhar as solicitações e tomar decisões com base nas demandas registradas. Já os funcionários, como a equipe de limpeza (por exemplo, a faxineira), possuem um papel operacional, sendo responsáveis por executar as tarefas necessárias e acompanhar as demandas relacionadas ao seu trabalho. Esse grupo pode apresentar menor familiaridade com tecnologias, o que exige que o sistema seja simples, intuitivo e de fácil utilização.
A relação entre esses grupos é hierárquica e complementar: os alunos identificam e sinalizam os problemas, enquanto a gestão organiza e direciona as soluções, que são executadas pelos funcionários. Dessa forma, o sistema atende diferentes perfis de usuários, considerando suas necessidades, níveis de acesso e responsabilidades dentro do ambiente escolar.


# Product Discovery

## Etapa de Entendimento

![Matriz CSD](images/Matriz-CSD.png)

![Mapa Stakeholder](images/MapaStakekholder.png)

![Entrevista Qualitativa](images/Entrevista-Qualitativa.png)

![Matriz CSD](images/Highlight-pesquisa.png)

![Matriz CSD](images/persona1.png)
![Matriz CSD](images/persona2.png)
![Matriz CSD](images/persona3.png)

## Etapa de Definição


# Product Design

## Histórias de Usuários

Com base na análise das personas foram identificadas as seguintes histórias de usuários:



| EU COMO           | QUERO/PRECISO                                                                     | PARA                                                                                                       |
| ----------------- | --------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- |
|                   |                                                                                   |                                                                                                            |
| Faxineira         | Um aplicativo simplificado com interface visual de ícones e fotos para reporte    | Reportar problemas de infraestrutura, como vazamentos e lâmpadas queimadas, sem precisar de                |
|                   | imediato de problemas                                                             | intermediários. Garantindo que eu seja ouvida.                                                             |
|                   |                                                                                   |                                                                                                            |
| Diretora          | Um dashboard administrativo que centralize as queixas, com gráfico e um lugar em | Ter visibilidade e controle das demandas de manutenção para garantir a segurança da escola.                |
|                   | que posso ver os problemas resolvidos.                                            |                                                                                                            |
|                   |                                                                                   |                                                                                                            |
| Aluno             | Um sistema de ticket com gamificação e possibilidade de votar em causas de outros | Ter um canal acessível para reportar problemas, como ventiladores estragados, falta de materiais e outros. |
|                   | alunos                                                                            |                                                                                                            |
|                   |                                                                                   |                                                                                                            |
| Faxineira         | Visualizar rapidamente quais problemas já foram reportados no meu setor           | Evitar retrabalho e organizar melhor minha rotina de limpeza                                               |
|                   |                                                                                   |                                                                                                            |
| Diretora          | Receber notificações em tempo real sobre problemas urgentes                       | Tomar decisões rápidas e garantir a segurança da escola                                                    |
|                   |                                                                                   |                                                                                                            |
| Aluno             | Acompanhar o status das minhas solicitações                                       | Saber se o problema que reportei já foi resolvido                                                          |
|                   |                                                                                   |                                                                                                            |


## Proposta de Valor


![Exemplo de proposta de valor](images/diretora.png)
![Exemplo de proposta de valor](images/faxineira.png)
![Exemplo de proposta de valor](images/aluno.png)

## Projeto de Interface

### Wireframes

![Login](images/login2.png)
![Tela Diretora](images/diretora2.png)
![Tela Faxineira](images/faxineira2.png)
![Tela Aluno](images/aluno2.png)



### User Flow

![User Flow](images/userflow.png)

### Protótipo Interativo


[Protótipo Interativo (Figma)](https://www.figma.com/proto/KKf7LQEyghzePUoGEpu5hS/Tiaw----Structa?node-id=1-13&t=WNjbVHuP1sh4yTUj-1&scaling=contain&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=1%3A2) 

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

# Solução Implementada

Esta seção apresenta todos os detalhes da solução criada no projeto.

## Vídeo do Projeto

O vídeo a seguir traz uma apresentação do problema que a equipe está tratando e a proposta de solução. ⚠️ EXEMPLO ⚠️

[![Vídeo do projeto](images/video.png)](https://www.youtube.com/embed/70gGoFyGeqQ)

> ⚠️ **APAGUE ESSA PARTE ANTES DE ENTREGAR SEU TRABALHO**
>
> O video de apresentação é voltado para que o público externo possa conhecer a solução. O formato é livre, sendo importante que seja apresentado o problema e a solução numa linguagem descomplicada e direta.
>
> Inclua um link para o vídeo do projeto.

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

- **Estrutura de dados:** Usuários

```json
{
  "id": 1,
  "nome": "Aluno",
  "senha": "123",
  "email": "aluno@abc.com",
  "tipo": "aluno"
}
```

- **Instruções de acesso:**
  - Acesse a página inicial do sistema
  - Informe e-mail, senha e tipo de usuário
  - Ao confirmar, o sistema redireciona automaticamente para a tela inicial correspondente ao perfil (aluno, funcionário ou diretora)
- **Tela da funcionalidade:**

<img width="1535" height="778" alt="image" src="https://github.com/user-attachments/assets/b2675ba0-dc9a-4f40-b1d5-13269b16858d" />

##### Funcionalidade 2 - Cadastro de Queixas (Aluno)

Permite que o aluno registre um problema de infraestrutura encontrado na escola, incluindo título, local, descrição e uma imagem do problema.

- **Estrutura de dados:** Queixas

```json
{
  "id": 1,
  "usuarioId": 1,
  "imagem": "data:image/avif;base64,...",
  "titulo": "Goteira no telhado do banheiro",
  "local": "Banheiro",
  "descricao": "No telhado do banheiro masculino no prédio 34, há uma goteira.",
  "status": "fechado",
  "data_envio": "2026-04-20T11:21:00Z",
  "motivoCancelamento": "diretora"
}
```

- **Instruções de acesso:**
  - Efetue login como aluno
  - Acesse a opção "Reportar problema"
  - Preencha título, local, descrição e anexe uma imagem (opcional)
  - Envie a queixa
- **Tela da funcionalidade:**

<img width="1516" height="781" alt="image" src="https://github.com/user-attachments/assets/3b01fe16-1fc6-4e6b-828b-7e19564d7dff" />


##### Funcionalidade 3 - Enquetes e Votação (Aluno)

Permite que o aluno visualize as queixas registradas por outros alunos e vote a favor ou contra a prioridade de resolução de cada uma.

- **Estrutura de dados:** Enquetes

```json
{
  "id": 1,
  "idQueixa": 1,
  "votos_a_favor": 14,
  "votos_contra": 3,
  "idUsuariosVotantes": [4, 5]
}
```

- **Instruções de acesso:**
  - Efetue login como aluno
  - Visualize as queixas em votação e registre seu voto
  - Acesse a opção "Suas Enquetes"
  - Visualize as enquetes que você reportou
- **Tela da funcionalidade:**

<img width="1517" height="780" alt="image" src="https://github.com/user-attachments/assets/1380a72c-71f4-477a-b562-9cd1fb1e8daa" />

<img width="1534" height="780" alt="image" src="https://github.com/user-attachments/assets/573c7bfd-3779-4551-9fcf-6fef4f786441" />

##### Funcionalidade 4 - Gestão de Queixas (Diretora)

Permite que a diretora visualize todas as queixas registradas pelos alunos, acompanhe seu status e acesse o detalhamento de cada uma.

- **Estrutura de dados:** Queixas

```json
{
  "id": 1,
  "usuarioId": 1,
  "imagem": "data:image/avif;base64,...",
  "titulo": "Goteira no telhado do banheiro",
  "local": "Banheiro",
  "descricao": "No telhado do banheiro masculino no prédio 34, há uma goteira.",
  "status": "fechado",
  "data_envio": "2026-04-20T11:21:00Z",
  "motivoCancelamento": "diretora"
}
```

- **Instruções de acesso:**
  - Efetue login como diretora
  - Acesse o Dashboard
  - Clique em "Queixas Reportadas"
  - Visualize as queixas criadas
- **Tela da funcionalidade:**

<img width="1521" height="781" alt="image" src="https://github.com/user-attachments/assets/4da2c643-66d1-469e-840f-2db3cfc8feeb" />

##### Funcionalidade 5 - Atribuição de Tarefas a Funcionários (Diretora)

Permite que a diretora atribua uma queixa registrada a um funcionário responsável, transformando-a em uma tarefa.

- **Estrutura de dados:** Tarefas

```json
{
  "id": 1,
  "funcionarioId": 2,
  "queixaId": 1,
  "titulo": "Goteira no telhado do banheiro",
  "local": "Banheiro",
  "descricao": "No telhado do banheiro masculino no prédio 34, há uma goteira.",
  "data_envio": "2026-04-20T11:21:00Z"
}
```

- **Instruções de acesso:**
  - Efetue login como diretora
  - Acesse a opção "Queixas Reportadas"
  - Acesse acesse "Detalhes completos"
  - Clique em "Delegar tarefa a funcionário"
  - Selecione o funcionário e confirme a atribuição da tarefa
- **Tela da funcionalidade:**

<img width="1519" height="780" alt="image" src="https://github.com/user-attachments/assets/91af78cd-70d6-49d8-8ccf-26e65df86fc7" />

<img width="1534" height="783" alt="image" src="https://github.com/user-attachments/assets/c36a0057-cbc8-4551-9412-4346cac9385d" />

<img width="1536" height="782" alt="image" src="https://github.com/user-attachments/assets/59158361-d109-49cb-b4ed-b3c4e2da16fc" />


##### Funcionalidade 6 - Listagem e Acompanhamento de Tarefas (Funcionário)

Permite que o funcionário visualize as tarefas atribuídas a ele, com detalhes do problema a ser resolvido.

- **Estrutura de dados:** Tarefas

```json
{
  "id": 1,
  "funcionarioId": 2,
  "queixaId": 1,
  "titulo": "Goteira no telhado do banheiro",
  "local": "Banheiro",
  "descricao": "No telhado do banheiro masculino no prédio 34, há uma goteira.",
  "data_envio": "2026-04-20T11:21:00Z"
}
```

- **Instruções de acesso:**
  - Efetue login como funcionário
  - Acesse o painel do funcionário
  - Visualize a listagem de tarefas e clique em uma tarefa para ver os detalhes
- **Tela da funcionalidade:**

<img width="1536" height="779" alt="image" src="https://github.com/user-attachments/assets/ac8e5900-e346-4e65-97de-8702f1981978" />

<img width="1536" height="782" alt="image" src="https://github.com/user-attachments/assets/c685376b-ded7-436d-86e4-b24d9ae10836" />

##### Funcionalidade 7 - Visualização de Métricas e Orçamentos (Diretora)

Permite que a diretora visualize indicadores gerais (incidentes, tarefas resolvidas, gastos por setor) e cadastre o orçamento referente à resolução de uma queixa.

- **Estrutura de dados:** Orçamentos, Métricas
```json
{
  "id": 1,
  "queixaId": 6,
  "valor": 1000,
  "data": "2026-04-20T11:21:00Z"
}
```

```json
{
  "incidentes": 8,
  "pendentes": 2,
  "resolvidos": 6,
  "gastos": 2350,
  "gastosPorSetor": [
    { "nome": "Banheiros", "valor": 300 },
    { "nome": "Cantina", "valor": 500 }
  ]
}
```



<img width="1520" height="777" alt="image" src="https://github.com/user-attachments/assets/82b61ae9-6374-4e99-9447-f90c94ee5023" />

## Estruturas de Dados

Descrição das estruturas de dados utilizadas na solução, baseadas no arquivo `db.json` consumido pelo JSON Server.

##### Estrutura de Dados - Usuários

Armazena os dados de login e o tipo de perfil de cada usuário do sistema (aluno, funcionário ou diretora).

```json
{
  "id": 1,
  "nome": "Aluno",
  "senha": "123",
  "email": "aluno@abc.com",
  "tipo": "aluno"
}
```

##### Estrutura de Dados - Queixas

Armazena os problemas reportados pelos alunos, incluindo imagem, status e motivo de cancelamento (quando aplicável).

```json
{
  "id": 1,
  "usuarioId": 1,
  "imagem": "data:image/avif;base64,...",
  "titulo": "Goteira no telhado do banheiro",
  "local": "Banheiro",
  "descricao": "No telhado do banheiro masculino no prédio 34, há uma goteira.",
  "status": "fechado",
  "data_envio": "2026-04-20T11:21:00Z",
  "motivoCancelamento": "diretora"
}
```

##### Estrutura de Dados - Tarefas

Representa uma queixa que foi atribuída a um funcionário responsável por resolvê-la.

```json
{
  "id": 1,
  "funcionarioId": 2,
  "queixaId": 1,
  "titulo": "Goteira no telhado do banheiro",
  "local": "Banheiro",
  "descricao": "No telhado do banheiro masculino no prédio 34, há uma goteira.",
  "data_envio": "2026-04-20T11:21:00Z"
}
```

##### Estrutura de Dados - Enquetes

Armazena os votos dos alunos sobre a prioridade de resolução de cada queixa.

```json
{
  "id": 1,
  "idQueixa": 1,
  "votos_a_favor": 14,
  "votos_contra": 3,
  "idUsuariosVotantes": [4, 5]
}
```

##### Estrutura de Dados - Orçamentos

Armazena os valores gastos para a resolução de cada queixa.

```json
{
  "id": 1,
  "queixaId": 6,
  "valor": 1000,
  "data": "2026-04-20T11:21:00Z"
}
```

##### Estrutura de Dados - Métricas

Armazena os indicadores agregados exibidos no painel da diretora (incidentes, pendências, gastos por setor).

```json
{
  "incidentes": 8,
  "pendentes": 2,
  "resolvidos": 6,
  "gastos": 2350,
  "gastosPorSetor": [
    { "nome": "Banheiros", "valor": 300 },
    { "nome": "Cantina", "valor": 500 }
  ]
}
```
## Módulos e APIs

Esta seção apresenta os módulos e APIs utilizados na solução.

**Frameworks e bibliotecas:**

- Bootstrap 5 (+ Bootstrap Icons e Popper.js) — framework CSS/JS para estilização, componentes de interface e responsividade
- jQuery — biblioteca utilizada em conjunto com os componentes do Bootstrap

**Images:**

- Unsplash — utilizado para imagens de perfil ilustrativas

**Backend / API:**

- JSON Server — utilizado como API REST simulada para fornecer e persistir os dados da aplicação (usuários, queixas, tarefas, enquetes, orçamentos e métricas), a partir do arquivo `db.json`. Expõe endpoints como `/usuarios`, `/queixas`, `/tarefas`, `/enquetes`, `/orcamentos` e `/metricas`, suportando operações de GET, POST, PUT, PATCH e DELETE
