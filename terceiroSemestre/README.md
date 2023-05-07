 Em 2022-1 (3º Semestre)

 ## Sobre o Projeto

No terceiro semestre, o cliente foi a TecSus, uma empresa de automação empresarial.

A proposta fornecida pela empresa foi de criar um sistema para coletar e processar contas de água, energia e gás com direcionamento a diversas empresas de setores de atacado e varejo, para assim ser possível realizar a digitação de todos os campos das contas de forma fácil, eficiente e agradável que serão salvos em um banco de dados para eventuais consultas e análises técnicas ou financeira, possibilitando trazer ao cliente oportunidades de redução de custos e alteração de contratos.

 ![Gif da execução do projeto](../img/3-semestre.gif)

Desse modo, de acordo com o que foi solicitado, foi criado um website para solucionar este problema. Como pode ser visto no GIF acima, as funcionalidades implementadas na aplicação foram:

* **Autenticação:** Ao entrar no sistema, a primeira tela é a de autenticação do usuário(login);
------------------------------------
* **Dashboards:** A primeira página, após o usuário realizar o login, é a de dashboards. Primeiramente, nela contém uma lista de unidades que podem ser clicadas para exibir gráficos e outros dados relevantes relacionados aos gastos das contas do contrato com a concessionária, disparando uma mensagem de aviso para caso o consumo seja maior que a do mês anterior. Além disso, é possível gerar um relatório em pdf com estes dados;
------------------------------------
* **Tabelas:** Nesta página é possível visualizar e excluir os dados dos cadastros de contas, concessionárias, unidades e contratos. Além disso, ao clicar em um cadastro específico, é possível ver todos os campos para editá-los;
* **Cadastros:** Na barra de navegação, a opção de cadastros abre uma janela com as seguintes opções de formulários: 
    * **Conta:** para cadastrar as contas (com um campo incluso para upload do arquivo da conta);
    * **Concessionária:** para cadastrar as concessionárias (com opções se ela é de água, energia ou gás);
    * **Unidade:** para cadastrar unidades (com um auxílio de uma API para a automatização de preenchimento de dados apenas com o CEP);
    * **Contrato:** para cadastrar os contratos (com dois selects com apenas concessionárias e unidades cadastradas no sistema).
------------------------------------
* **Perfils:** página com um CRUD de usuários, sendo possível visualizar, cadastrar, editar e excluir. Além disso, também possui uma opção para redefinição de senha;
------------------------------------
* **Histórico:** A última página é a de histórico. Nela contém informações de quem, o que e quando algum dado de cadastro foi adicionado, alterado ou excluído;
------------------------------------
* **Perfil, ajuda, notificações, e pesquisa:** No canto superior direito da tela, temos alguns ícones que trazem infromações de perfil (dados do usuário logado e botão de sair), ajuda (instruções sobre a página em questão), notificações (com avisos de pendência e reprovação de cadastros) e pesquisa (em algumas páginas com tabela com vários dados é possível realizar uma pesquisa para encontrá-los mais facilmente);
------------------------------------
* **Níveis de Acesso:** Por fim, neste sistema existe um nivelamento de acesso de acordo com a pessoa autenticada, e cada tipo de usuário possui as seguintes funcionalidades:
    * **Digitador:** Consegue cadastrar, visualizar e editar contas, concessionárias, unidades e contratos. Ele recebe notificações para caso seus cadastros sejam reprovados pelo gestor;
    * **Gestor:** Pode realizar todas as funções do sistema. Ele possui um papel de analisar o que foi cadastrado pelo digitador, recebendo sempre notificações de novos cadastros;
    * **Administrador:** Assim como o gestor, possui todo acesso da aplicação. Porém, ele tem uma função mais geral da manipulação do sistema, cuidando, principalmente, do controle de usuários e seus históricos de ações.
------------------------------------
> [Acesse o repositório no GitHub clicando aqui](https://github.com/NewInoDevs/NewInoDevs)

## Tecnologias Utilizadas

* **Front-end:** 
    - **HTML:** linguagem de marcação para a criação do site;
    - **CSS:** linguagem para a estilização do site;
    - **JavaScript:** linguagem de programação para criar as interações do site;
    - **Bootstrap:** framework web para desenvolvimento de interfaces gráficas.
* **Back-end:** 
    - **Java:** linguagem de programação para contrução do Back-end;
    - **Spring:** framework em Java para controle de dependência, com JPA (persistência de dados), Thymeleaf (integração com o front) e Spring Security (autenticação);
    - **MySQL:** linguagem de programação para banco de dados para pesistência de dados do cadastros.
* **Outros:** 
    - **Figma:** ferramenta para criação do protótipo do projeto;

## Contribuições Pessoais

Nesse projeto novamente trabalhei focalmente na parte do back-end, onde nesse semestre trabalhamos com a liguagem de programação JAVA com o framework Spring, tive grande participação na parte do nivelamento de acesso dos usuários, também participei dos CRUD's, juntamente com o banco de dados, onde também tive participação, também fiz a integração de algumas funções entre o back-end e o front-end e por último ajudei na parte dos Dashbords e da mecânica de notificações.

## Hard Skills

* **HTML5** - sei fazer com autonomia;
* **CSS3** - sei fazer com auxílio de consultas;
* **JavaScript** - sei fazer com auxílio de consultas;
* **Bootstrap** - sei fazer com auxílio de consultas;
* **Java** - sei fazer com auxílio de consultas;
* **Spring** - sei fazer com auxílio de consultas;
* **MySQL:** - sei fazer com autonomia;

## Soft Skills

* **Trabalho em Equipe:** nesse semestre tivemos uma equipe menor, mas ainda assim conseguimos entregar mais do que o esperado; 
* **Autonomia:** foi o primeiro semestre onde utilizamos frameworks, então tivemos que estudar essas novas ferramentas, mas graças a isso conseguimos entregar um bom projeto e com uma maneira mais facil de testar suas funcionalidades;
* **Entrega de Resultados:** como já citado anteriormente, com o grupo menor, ainda conseguimos entragar excelentes resultados, onde todo do grupos foram fundamentais.