# Briefing

## 01. PROJECT DESCRIPTION/DESCRIÇÃO DO PROJECTO

No contexto da L-EI pretende-se que os alunos desenvolvam um projeto multidisciplinar, integrando os conhecimentos e aprendizagens adquiridos em várias unidades curriculares do 3º semestre do curso.

O projeto consiste no desenvolvimento de uma **Aplicação Mobile** com respectivo suporte aplicacional através de **Webservices** desenvolvidos utilizando a arquitetura **REST** e **base de dados** de suporte modelada segundo o modelo relacional.

*A escolha do projeto deve ter em conta as características particulares das aplicações mobile. As aplicações têm como requisito técnico fundamental a utilização da localização do dispositivo (salvo autorização em contrário dos Docentes), trabalhando em conjunto com mapas e dados salvaguardados na base de dados com eventual utilização de profile matching. Pode ainda utilizar tecnologias distintas do GPS para obter a localização (vizinhos bluetooth, QRCodes ou outros métodos aprovados pelos Docentes).*

A utilização de localização do dispositivo deverá seguir o Regulamento Geral de Proteção de Dados (RGPD), temática que será abordada nas aulas da unidade curricular.

## 02. CONTEÚDOS PROGRAMÁTICOS/SYLLABUS CONTENTS

Este projeto baseia-se na análise, desenho e implementação de um Projeto de Engenharia Informática. Os alunos são assim guiados através de todo o processo de desenvolvimento, recorrendo a uma metodologia ágil, que inclui também um trabalho de comunicação que culmina com uma apresentação dos resultados. Irão utilizar algumas ferramentas para auxiliar a Gestão do Projeto.

As diversas fases incluem obrigatoriamente:

- Análise e conceptualização, nas diversas áreas do projeto (desenvolvimento mobile, programação orientada a objetos e base de dados);
- Planeamento;
- Prototipagem;
- Implementação;
- Teste;
- Apresentação.

## 03. OBJECTIVOS/LEARNING OUTCOMES

No final da unidade curricular, o aluno deverá ser capaz de:

- Analisar, planear, e implementar um projeto de Engenharia Informática;
- Ter capacidade de trabalhar em grupo para atingir o objetivo final a que o grupo se propõe;
- Compreender as diferentes tecnologias e etapas envolvidas no desenvolvimento de um projeto;
- Trabalhar no desenvolvimento de um projeto através de um sistema/plataforma colaborativa de controlo de versões;
- Utilizar uma metodologia de desenvolvimento ágil, com várias apresentações de funcionalidades e possibilidade de acomodar alterações durante a execução do projeto;
- Saber comunicar de forma clara e efetiva com o público-alvo, quer oralmente quer por escrito, explicitando as características e vantagens do produto desenvolvido.

## 04. PROJECT REQUIREMENTS/REQUISITOS

O projeto deve ter em conta os seguintes requisitos obrigatórios:

- Os grupos são constituídos por 2 (dois) alunos
  - Em avaliação final o projeto é individual salvo exceções devidamente autorizadas pelo corpo docente (ex: alunos que transitam da avaliação contínua onde o projeto tenha sido avaliado com um mínimo de 8.0 valores)
- A escolha do projeto é da responsabilidade dos alunos com obrigatória validação dos docentes das unidades curriculares envolvidas
- O projeto tem que ser implementado em Java (Programação Móvel e Programação Orientada Objeto) utilizando a tecnologia Spring Boot e as arquiteturas MVC e REST (em Programação Orientada a Objeto) e Android Studio Arctic Fox | 2020.3.1 Patch 2
- O projeto deve separar claramente o código em módulos com diferentes responsabilidades (serviços, modelos, acesso a dados, interfaces, etc) de acordo com o que será ensinado durante as aulas
- É obrigatório usar as seguintes plataformas (a avaliação tem em conta a interação com estas plataformas, sendo que elas são usadas para uma monitorização diária do projeto):
  - GitHub para gestão de versões e documentação em que a página de descrição do projeto contém a descrição e links para demais documentação do projeto;
  - ClickUp para gestão do projeto;
  - Slack para comunicação dentro da equipa de projeto.
- Na documentação deve ser incluído o diagrama de classes, o modelo ER da Base de Dados e a documentação REST. A documentação REST segue o formato indicado no seguinte site: https://bocoup.com/blog/documenting-your-api
- A base de dados é obrigatoriamente relacional e desenvolvida em PosgreSQL:
  - Devem ser desenvolvidos vários ficheiros SQL a entregar nas milestones 2 e 3:
    - Um ficheiro `create.sql` com todas as instruções necessárias à criação da BD e de todos os objetos (tabelas, views, stored procedures, etc) necessários ao seu funcionamento.
    - Um ficheiro `populate.sql` com as instruções de inserção de dados que que permitam criar uma base de dados de teste coerente e com dados que simulem situações reais de utilização.
    - um ficheiro `queries.sql` com as pesquisas mais relevantes, que ilustrem o tipo de informação que é possível extrair da BD
      - A avaliação terá em conta a complexidade e diversidade das queries apresentadas
      - As queries não devem ser submetidas de uma forma que permita o seu teste individualizado sobre a BD criada, ou seja, apenas o código SQL.
  - A base de dados poderá ser utilizada numa instalação local durante o desenvolvimento mas o objectivo final deverá ser que esta possa integrar um serviço disponível publicamente através da infraestrutura Heroku (heroku.com)
- Dados e conteúdos:
  - Os dados e conteúdos usados no desenvolvimento do projeto devem ser representativos, não devem ser uma caricatura e, quando se tratar de dados sensíveis (e.g. nomes, números de telefone, etc.), não devem ser reais.
- É obrigatória a produção de relatórios quinzenais (_sprint report_) sobre a evolução do projeto (tarefas realizadas e planeamento da semana/_sprint_ seguinte)
- É obrigatória a produção de um relatório final do projecto, que deve incluir:
  - folha de rosto com título e identificação dos alunos;
  - resumo e palavras-chave;
  - identificação do contexto do projecto e definição de um problema/necessidade, apoiados em pesquisa e em dados retirados da literatura científica;
  - descrição do produto e diferenciação face a outros semelhantes;
  - definição do público-alvo;
  - descrição de cenários e personae;
  - componente técnica, com a documentação e os ficheiros anteriormente mencionados
  - conclusão, incluindo objetivos atingidos e por atingir, dificuldades, etc.
  - anexos, incluindo: cópia dos slides da apresentação, ...

## 05. CURRICULAR UNIT CONTRIBUTIONS / CONTRIBUIÇÕES DAS UCs

| **ECTS** | **HRS**** /WEEKS **|** CURRICULAR UNIT CONTRIBUTIONS **|** PROFESSOR **|** % OF FINAL PROJECT** |
| --- | --- | --- | --- | --- |
| 6 | 3h(14w) | **Programação Móvel** Desenvolvimento de uma aplicação móvel utilizando Android Studio Arctic Fox 2020.3.1 Patch 2. | João Dias | |
| 6 | 4h(14w) | **Programação Orientada a Objetos** Desenvolvimento de um servidor em Spring Boot usando arquitetura REST , integração da aplicação com a base de dados, gestão de versões usando GIt, criação da documentação. | Miguel Bugalho | 60% Av. Continua50% Av. Final |
| 6 | 4h(14w) | **Bases de Dados** Desenvolvimento de uma base de dados de suporte à gestão de dados do projeto. Desenvolvimento do modelo de dados com recurso a diagramas E-R. Implementação da base de dados em PostgreSQL. | Miguel Boavida | |
| 6 | 4h(14w) | **Competências Comunicacionais** Acompanhamento da evolução da capacidade de comunicação dos projetos para um público leigo, através de apresentações orais e preparação de suportes visuais. | ???? ???? | 40% Avaliação (apresentação final + relatório) |
| 5 | 3h(14w) | **Matemática Discreta** Desenvolvimento da componente de processamento e análise dos dados recolhidos pela aplicação. | Rodolfo Bendoyro ||

## 06. PROJECT METHODOLOGY/METODOLOGIA

O projeto será desenvolvido ao longo do semestre com a colaboração das diferentes unidades curriculares envolvidas. Cada unidade curricular faz o acompanhamento dos trabalhos para cada milestone até à entrega e validação dos respetivos Deliverables.

## 07. GRADING / AVALIAÇÃO

Para cumprir com o método de avaliação contínua, os alunos têm que efetuar 3 entregas. Há um mínimo de 70% de assiduidade (50% para casos especiais previstos no regulamento) para que os alunos sejam elegíveis para avaliação contínua.

A avaliação de cada aluno é efetuada de acordo com o trabalho dos alunos em resultados específicos, conforme descrito abaixo. De notar que há uma penalização de até 4 pontos se as instruções de entrega não forem seguidas com precisão.

## 08. DELIVERABLES AND SCHEDULE / ENTREGAS E DATAS

### Group membership / Constituição dos Grupos:

** Obrigatoriamente na 1ª Aula

### 1st Delivery/ 1ª Entrega (1-3 semanas):**

- Submission/Data de Submissão: final da terceira semana ( 01.10.2021 às 23h59 )
- Deliverables/Entregas:
  - Primeira versão do relatório, disponibilizada numa plataforma git (em markup language) que deve incluir:
    - Uma proposta inicial de projeto
      - Nome do projeto
      - Enquadramento do projeto (incluindo a ideia, uma pesquisa sobre o contexto em que se insere, descrição dos objetivos, definição do público-alvo e pesquisa sobre outras ferramentas que já existam)
    - Uma versão preliminar com pelo menos três guiões de teste (descrição textual passo a passo do progresso do utilizador na aplicação)
      - 1 caso de utilização que descreva o objecto "core" do projeto
      - outros 2 casos de utilização diferentes do "core" e entre eles (podem partir do caso de utilização descrito anteriormente)
  - Entrega de vídeo com Pitch de 3 min com apresentação da proposta na semana seguinte no mesmo formato.
- Avaliação (20%)
  - Progressos semanais
  - Proposta de solução com cenários e personas
  - Plano de trabalhos
  - Requisitos funcionais e não funcionais
  - Modelo do domínio
  - Mockups e interfaces
  - Project Charter and WBS
  - Pitch

### 2nd Delivery/ 2ª Entrega (4-9 semanas):**

- Submission/Data de Submissão: final da nona semana ( 12.11.2021 às 23h59 )
- Deliverables/Entregas:
  - Protótipo / Versão alfa do projeto com um servidor funcional e BD online
  - Versão atualizada do relatório de projeto na plataforma git, incluindo também:
    - Definição final dos guiões e personas
    - Esboço do diagrama de classes no git (diagrama conceptual com foco nas entidades e relações entre elas)
    - Primeira versão da documentação REST adicionada ao relatório
    - Primeira versão do Dicionário de Dados com a descrição detalhada do Modelo Entidade-Relação,
    - Um esboço da estrutura dos dados presentes na BD exemplo (Guia de Dados)
  - Ficheiros para a criação da BD (create, populate e queries) e código fonte (disponível no GitHub)
  - Suporte visual da apresentação (PPT ou outro), que não pode ultrapassar os 6 slides de conteúdo (i.e. excluindo capa)
- Avaliação (30%):
  - Progressos semanais
  - Protótipo funcional do projeto com demo
  - Código fonte disponível online numa plataforma git
  - Plano de trabalhos atualizado
  - Apresentação

### 3th Delivery/ 3ª Entrega (10-14 semanas):**

- Submission/Data de Submissão: Submissão na plataforma Canvas na data/hora da prova de avaliação contínua, marcada pela secretaria (última semana de aulas).
- Presentation Date/Data da Apresentação: a agendar (uma semana a seguir à data de submissão)
- Deliverables/Entregas:
  - Versão final do projeto com GUI e BD online
  - Versão atualizada do relatório de projeto (documento único para todas as unidades curriculares) na plataforma git:
    - Versão atualizada dos casos de utilização
    - Versão atualizada do diagrama de classes
    - Versão atualizada do Dicionário de Dados (documentação que descreve o modelo ER)
    - Versão atualizada do Guia de Dados (documentação que descreve a BD exemplo)
    - Versão atualizada da documentação REST
    - Manual do utilizador (com print screens, pode ter semelhanças aos guiões, mas pode ser diferente).
  - Ficheiros para a criação da BD (create, populate e queries) na plataforma git
  - Código fonte (código java) disponível no GitHub
  - Suporte visual da apresentação (PPT ou outro), que não pode ultrapassar os 8 slides de conteúdo (i.e. excluindo capa)
  - Vídeo de apresentação do projeto, com duração máxima de 2 minutos, que deve incluir um narrador a descrever o que se vai observando
  - Apresentação oral (duração máxima 10 minutos, incluindo o visionamento do vídeo), com recurso ao suporte visual previamente entregue
- Avaliação (50%):
  - Progressos semanais
  - Versão final do projeto disponível online
  - Código fonte disponível online numa plataforma git
  - Relatório final de projeto
  - Apresentação
  - Poster
  - Vídeo

### Caso os prazos não sejam cumpridos:**

Cada dia de atraso na entrega dos elementos de avaliação implica a perda de 1 valor na avaliação de cada unidade curricular, relativamente à respetiva entrega (i.e. 1 dia de atraso equivale a menos 1 valor por UC).

## Avaliação Final / Exame** :

- Entrega e apresentação únicas: 100%
- Projeto disponível online
- Código fonte disponível online numa plataforma git
- Relatório final de projeto
- Apresentação e discussão
- Poster
- Vídeo
