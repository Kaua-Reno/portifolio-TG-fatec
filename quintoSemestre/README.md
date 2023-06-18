# Em 2023-1 (5º Semestre)

## Sobre o Projeto

A empresa parceira deste projeto foi a IACIT, uma empresa que atua no desenvolvimento de produtos e sistemas aplicados às áreas de auxílio do controle e do tráfego aéreo e marítimo, defesa e segurança pública, fábrica de software, meteorologia, telemetria e agronegócio e pesquisa, desenvolvimento e inovação.

O cliente propôs para o quinto semestre o desenvolvimento de uma aplicação híbrida que funcione como Serviço de Atendimento ao Cliente (SAC), onde o usuário poderá cadastrar registros de ocorrências (RO's) e o suporte conseguirá verificar as solicitações criadas e solucionar os problemas do usuário, podendo também entrar em contato via chat.

Sendo assim, a solução que implementamos foi o desenvolvimento de uma aplicação mobile e web, que pode ser visto sua execução no primeiro e segundo GIF abaixo respectivamente:

![Gif da execução do projeto app](../img/5-semestre-app.gif)

![Gif da execução do projeto web](../img/5-semestre-web.gif)

Como pode ser visto nos GIFs acima, as funcionalidades implementadas na aplicação foram:

* **Autenticação:** Para acessar a aplicação, primeiramente, é necessário se autenticar no sistema com e-mail e senha;
------------------------------------
* **Nivelamento de Acesso:** Existem dois níveis de acesso:
    * **Cliente:** Usuários que criam os RO's e aguardam serem resolvidas. Ele tem as seguintes permissões: acessar a página Home; criar, fechar e acompanhar os RO's; e entrar em contato com o suporte via chat;
    * **Administrador:** Encaminhado para resolver os RO's. Possui acesso completo da aplicação;
------------------------------------
* **Home:** Após se autenticar, o usuário possui várias opções de botões para acessar as funcionalidades do sistema (apenas na versão mobile, na versão web o usuário é redirecionado para página Registro de Ocorrência, já que temos um menu de navegação maior);
------------------------------------
* **Registro de Ocorrência:** Nesta página, contém a listagem de registros de ocorrências, que podem ser buscados por ID ou título e, caso o usuário seja um administrador, pode ser filtrado por Minhas Tasks, onde é mostrado apenas ROs indicados para o usuário resolver. Além disso, ao clicar em um RO específico, o administrador consegue atualizá-lo com uma solução para o problema. Após esta resposta, o cliente poderá analisar e concluir ou recusar o RO. Caso seja a primeira opção, o RO é fechado, caso contrário, ele deverá ser analisado novamente pelo administrador;
------------------------------------
* **Membros do Suporte:** Tela com a listagem dos usuários cadastrados no sistema. Ao clicar em um usuário específico, será mostrado mais detalhes dele e seus dados poderão ser atualizados;
------------------------------------
* **Novo Registro de Ocorrência:** Nesta tela é possível cadastrar um novo Registro de Ocorrência;
------------------------------------
* **Cadastrar Novo Usuário:** Página para a criação de um novo usuário para entrar na aplicação;
------------------------------------
* **Redefnição de Senha:** Quando um usuário é criado pelo administrador, o usuário receberá um e-mail com um link de redefinição de senha, que será redirecionado a uma página da aplicação para que ele possa definir sua senha. Além disso, também é possível clicar em "Esqueci a senha" para receber um e-mail para a redefinição;
------------------------------------
* **Meus Chats:** Página que é possível conversar diretamente com o responsável da resolução dos RO's;
------------------------------------
* **Opções Extras:** Tela com opções extras de segurança. É possível, caso o usuário seja um administrador, criar um backup e restaurar o último backup, além de disponibilizar, independetemente de ser administrador, os termos de compromisso na utilização da aplicação;
------------------------------------
* **Relatório:** Nesta página temos um gráfico com os dados dos RO's que foram abertos, além de especificar quantos estão sem tratamento, em tratamento e concluídos. É possível filtrar os dados do dashboard pro mês e usuário;
------------------------------------
* **Notificações:** Nesta tela, é possível visualizar as notificações que aparecem para caso um RO seja criado, atualizado, recusado ou concluído. Além disso, caso o usuário queira, ele pode receber e-mails dessas notificações;
------------------------------------
* **Perfil:** Página com as informações do usuário.
------------------------------------

> [Acesse o repositório no GitHub clicando aqui](https://github.com/inodevs-5)

## Tecnologias Utilizadas

* **Front-end:** 
    - **TypeScript:** linguagem de programação para criação tanto da aplicação mobile quanto da web;
    - **React Native:** biblioteca para desenvolvimento de sistemas Android e iOS de forma nativa;
    - **HTML:** linguagem de marcação para a criação do site;
    - **CSS:** linguagem para a estilização do site;
    - **React:** biblioteca para desenvolvimento de interfaces gráficas em páginas web.
* **Back-end:** 
    - **JavaScript:** linguagem de programação para contrução do Back-End;
    - **NodeJS:** para execução de JavaScript fora de um navegador web;
    - **MongoDB:** banco de dados NoSQL para pesistência de dados;
    - **Mongoose:** ORM em JavaScript para o MongoDB.
* **Outros:** 
    - **Figma:** ferramenta para criação do protótipo do projeto;

## Contribuições Pessoais

Nesse semestre, trabalhei como programador na parte do backend com Typescript, utilizando o Framework NodeJS. As tasks que fiquei responsavel foram as do Login na parte do backend e da conexão com o frontend. Cuidei do envio de notificações do Cadastro, da edição e do fechameto dos RO's via email. Também cuidei de adicionar os numeros de notificações no icone de notificações e no botão do chat do app no frontend. No final de cada Sprint fiquei a diposição e ajudei colegas a finalizarem suas tasks, principalmente no frontend. Por fim nesse semestre tomei a iniciativa e apresentei 3 entregas(2º, 3º e 3º entrega) de Sprints para o cliente.

## Hard Skills

* **TypeScript** - sei fazer com auxílio de consultas;
* **React Native** - sei fazer com auxílio de consultas;
* **HTML5** - sei fazer com autonomia;
* **CSS3** - sei fazer com auxílio de consultas;
* **React** - sei fazer com auxílio de consultas;
* **JavaScript** - sei fazer com autonomia;
* **NodeJS** - sei fazer com autonomia;
* **Mongoose** - sei fazer com auxílio de consultas;
* **MongoDB:** - sei fazer com auxílio de consultas.

## Soft Skills

* **Colaboração:** Nesse semestre a colaboração do grupo foi essencial, pelo fato das novas tecnologias e novo ambiente de programação(mobile), pois com a boa colaboração todo o time evoluia junto;
* **Trabalho em Equipe:** foi essencial um bom trabalho em equipe, por conta da separação das tasks, pois todas as sprints tiveram varias tasks, para que assim entregássemos tudo o que era necessário para entregar um bom produto final para o cliente;
* **Comunicação:** com uma equipe com bastante integrantes, foi importante ter uma comunicação eficaz para todos estarem cientes de como estava andamento do projeto e a entrega que cada um iria realizar, assim como as ligações que uma task tem com outra.
