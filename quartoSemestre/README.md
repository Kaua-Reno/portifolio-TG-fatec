# Em 2022-2 (4º Semestre)

## Sobre o Projeto

O cliente do projeto no quarto semestre foi a 2RP, uma empresa que traz soluções e serviços personalizados para demandas na área de TI, atuando em qualquer segmento de mercado.

O objetivo do projeto deste semestre foi de desenvolver uma plataforma web para controlar a jornada de trabalho dos colaboradores da empresa em horas extras e sobreavisos.

 ![Gif da execução do projeto](../img/4-semestre.gif)

Desse modo, de acordo com o que foi solicitado, foi criado um website para solucionar este problema. Como pode ser visto no GIF acima, as funcionalidades implementadas na aplicação foram:

* **Autenticação:** Inicialmente, temos a tela de autenticação de usuário que necessita do e-mail e senha para acessar o sistema;
------------------------------------
* **Home:** Após se autenticar, o usuário estará na página Home com detalhes de seus últimos apontamentos e as horas trabalhadas, além de botões que redirecionam para páginas de apontar horas e visualizar esses apontamentos;
------------------------------------
* **Cadastrar Horas:** Página com a funcionalidade principal do sistema. É um cadastro com 3 etapas para realizar o cadastro das horas extras e de sobreavisos trabalhadas por um colaborador;
------------------------------------
* **Tabela de Apontamentos:** Nesta tela é possível visualizar os apontamentos de todos os colaboradores e, ao clicar no botão visualizar, é possível ter mais detalhes dos apontamentos e editá-los;
------------------------------------
* **Usuários, Projetos, Clientes e Centros de Resultados:** Nestas páginas, temos a listagem, cadastro e edição de usuários, projetos, centros de resultados e clientes;
------------------------------------
* **Manipulação de Verbas:** Similar com as páginas anteriores, nesta tela é possível visualizar, cadastrar e editar as verbas que serão utilizadas para o cálculo do valor de cada hora dos apontamentos;
------------------------------------
* **Dashboards Individuais e Dashboards Gerais:** Nessas páginas, podemos visualizar dados anuais e mensais sobre os apontamentos de horas extras e de sobreavisos realizados durante este período. Nos Dashboards Individuais é apresentado dados do usuário autenticado e nos Dashboards Gerais é dado as informações gerais dos apontamentos de toda a empresa. Além disso é possível gerar um pdf com um resumo desses dados;
------------------------------------
* **Histórico de Apontamentos:** Nesta tela, pode ser visualizado histórico de apontamentos do usuário que está utilizando o sistema;
------------------------------------
* **Integração do Login:** Para maior facilidade de acessar a aplicação, foi implementada uma integração com o login da Google como opção de autenticação;
------------------------------------
* **Nivelamento de Acesso:** Por fim, também implementamos três níveis de acesso de acordo com a pessoa autenticada, esses níveis são:
    * **Administrador:** Possui acesso completo da aplicação; 
    * **Gestor:** Possui o acesso completo da aplicação, com exceção da páginas de Usuários e Manipulação de Verbas;
    * **Colaborador:** Só tem permissão de acessar a página Home, Cadastrar de Horas, Dashboards Individuais e Histórico de Apontamentos (ele pode editar o Apontamento, porém a aprovação ou reporvação só será feita pelo gestor ou administrador).
------------------------------------

> [Acesse o repositório no GitHub clicando aqui](https://github.com/Inodevs-4/2RP)

## Tecnologias Utilizadas

* **Front-end:** 
    - **HTML:** linguagem de marcação para a criação do site;
    - **CSS:** linguagem para a estilização do site;
    - **TypeScript:** linguagem de programação para a criação do site;
    - **React:** biblioteca para desenvolvimento de interfaces gráficas em páginas web.
* **Back-end:** 
    - **TypeScript:** linguagem de programação para contrução do Back-End;
    - **NodeJS:** para execução de JavaScript fora de um navegador web;
    - **TypeORM:** ORM em TypeScript para criação da persistência de dados;
    - **PostgreSQL:** linguagem de programação para banco de dados para pesistência de dados.
* **Outros:** 
    - **Figma:** ferramenta para criação do protótipo do projeto.

## Contribuições Pessoais

No quarto projeto, sendo PO(Product Owner), cuidei da parte do contato com o cliente, tirando dúvidas sobre o produto de valor de cada sprint, organizando cada entrega de Sprint, criando a modelagem dos dados cadastrados no sistema e do protótipo de cada funcionalidade para validação e esclarecimento do produto para o cliente e para a Equipe de desenvolvimento. Na parte da programação, atuei principalmente na parte do backend com o Typescript, utilizando o framework NodeJS, nas funcionalidades de: algumas modelagem de entidades com o TypeORM. Participei das operações de CRUD de algumas entidades, tais como: projetos, centro de resultados e clientes. Também tive algumas colaborações na parte do frontend, principalmente nas revisões, onde com um ou mais colaborador do projeto, entravamos em ligação para revisar o projeto e resolver os "bugs", tanto de CSS(alinhamento, UX e etc..), quanto das funcionalidades do Backend da Sprint.

## Hard Skills

* **HTML5** - sei fazer com autonomia;
* **CSS3** - sei fazer com auxílio de consultas;
* **TypeScript** - sei fazer com auxílio de consultas;
* **React** - sei fazer com auxílio de consultas;
* **NodeJS** - sei fazer com autonomia;
* **Typeorm** - sei fazer com autonomia;
* **MySQL:** - sei fazer com autonomia.

## Soft Skills

* **Comunicação:** como fui PO, a comunicação foi fundamental para as entregas de cada Sprint, para esclarecimento de cada task e entendimento claro de cada pergunta e resposta passada pelo cliente;
* **Proatividade:** até o 4º semestre, ainda não havia sido o PO da equipe, por conta disso, a proatividade foi fundamental para esse semestre, pois tive que ir atrás de estudar como ser um bom PO, quais eram as minhas tarefas e como organizar as entregas;
* **Organização:** com maior número de pessoas no time, a organização das atividades foi imporante para entregar tudo o que foi proposto para as sprints, pois sem uma boa organização alguns colaboradores da equipe poderiam trabalhar mais do que outros nas tasks da Sprint.