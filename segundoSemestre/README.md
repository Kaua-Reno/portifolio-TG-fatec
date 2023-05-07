 Em 2021-1 (1º Semestre)

## Sobre o Projeto

Neste segundo projeto, foi o primeiro com uma empresa parceira da Faculdade, a JetSoft, uma empresa de software que oferece serviços e produtos a outros clientes.

O objetivo do projeto foi de criar um CRUD (Create, Read, Update e Delete) para essa empresa de software com intuito de emitir relatórios mensais de controle de presença de colaboradores com alocação específica de diferentes postos de trabalhos acordados em um contrato com o seu respectivo cliente.

Assim como está sendo mostrado no GIF abaixo, a partir do problema, foi criado um aplicativo web para solucioná-lo:

![Gif da execução do projeto](../img/2-semestre.gif)

## Funcionalidade:

O gif acima demostra as funcionalidades que foram implementadas, listadas a baixo:

------------------------------------
* **Marcação de presença:** Essa é a principal função para o usuário operacional, onde ele marcar a sua presença diária de trabalho.
------------------------------------
* **Autentificação e Nivelamento de acesso:** ao realizar o login o usuário pode ter dois niveis de acesso(Operacional e Tático), onde de acordo com seu nivel de acesso ele pode entrar e tem permissão para realizar ações que o outro nivel de acesso não consegue, Os niveis de acesso são separados em:
    - **Operacional:** Nível padrão de acesso para usuários que utilizam o sistema apenas para marcar sua presença e que também podem consultar informações sobre os desenvolvedores;
    - **Tático:** Nível mais alto de acesso, esse nível tem acesso a todas as páginas do site e também pode realizar todas as funcionalidades do mesmo.
------------------------------------
* **Controle de Perfis:** Nesta página, é onde fica os 6 cadastros implementados para solução do problema, sendo eles: Colaboradores, Contratos, Clientes, Postos de Trabalho, Alocações e Usuários. E, ao serem selecionados, o usuário é redirecionado para um formulário para inserir os campos necessários e cadastrar novos dados no sistema;
------------------------------------
* **Quadro de Presença:** Essa é a página principal, o quadro de presenças. Nele contém as presenças dos postos de trabalho e também as presenças de cada colaborador do seu respectivo posto, essas presenças podem  ser editadas e/ou excluídas, caso aja algum erro ou equívoco. Nesta tela, também é permitido realizar buscas com o nome do colabodor ou posto e também existe a funcionalidade de gerar relatório do quadro de presença (como uma cópia do quadro com dados de frequência de presença) e um relatório gerencial (com gráficos, dados e porcentagens da frequência de colaboradores e dos postos), que podem ser exportados como pdf ou salvos dentro de um histórico na aplicação;
------------------------------------
* **Edições:** Tela com tabelas de Colaboradores, Contratos, Clientes, Postos de Trabalho, Alocações e Usuários e seus respectivos dados. Nesta página é possível a visualização, edição e exclusão destes dados;
------------------------------------
* **Página dos Desenvolvedores:** Uma página simples com informações sobre os desenvolvedores do sistema;
------------------------------------
* **Guias:** Além das páginas do sistema, foram implementados os seguintes PDF's para auxílio na utilização do sistema:
    - **Instalação:** Com instruções de como executar a aplicação em localhost;
    - **Usuário:** Para auxiliar os usuários a utilizar o sistema;
    - **Contenção de Problemas:** Soluções de possiveis erros que podem ocorrer na aplicação.
 
### > [Acesse o repositório no GitHub clicando aqui](https://github.com/Inodevs/Inodevs)


## Tecnologias Utilizadas

* **Front-end:** 
    - **HTML:** linguagem de marcação para a criação do site;
    - **CSS:** linguagem para a estilização do site;
    - **JavaScript:** linguagem de programação para criar as interações do site.
* **Back-end:** 
    - **PHP:** linguagem de programação que foi utilizado para armazenar e consultar dados no banco;
    - **MySQL:** linguagem de programação para banco de dados para pesistência de dados do cadastros.
* **Outros:** 
    - **Figma:** ferramenta para criação do protótipo do projeto;

## Contribuições Pessoais

No projeto do segundo semestre, tive o papel de Scrum master, onde acretido ter exercido bem o meu papel de organizar a equipe e as tasks de cada um de acordo com a entrega da sprint, nesse semestre também trabalhei na parte do back-end, onde cuidei de fazer alguns dos CRUD's e também trabalhei na parte principal do projeto que é o quadro de marcação de presenças, outra função que fiz foi a de tester e de correção de bugs juntos com outros membros da equipe, nessa parte mexi com o frontend para corrigir bugs de centralização e estilização do projeto em todos os finais de sprint, também realizei a apresentação de duas sprints para o cliente.

## Hard Skills

* **HTML5** - sei fazer com auxílio de consultas;
* **CSS3** - sei fazer com auxílio de consultas;
* **JavaScript** - sei fazer com auxílio de consultas;
* **PHP** - sei fazer com auxílio de consultas;
* **MySQL:** - sei fazer com autonomia;

## Soft Skills

* **Planejamento:** para organizar a equipe e o andamento da sprint, junto com as minhas próprias tasks das sprints;
* **Proatividade:** por conta do novo desafio, toda equipe teve que ir atras de novos conhecimentos para entrega do produto, e acredito que tenha tido um bom desempenho nesse critério, pois tive particpação em muitos códigos desse projeto;
* **Entrega de Resultados:** obtive sucesso em todas as minhas tasks de cada sprint e ainda consegui ajudar com alguns atrasos e correção de bugs que cada sprint teve.
