# Em 2023-2 (6º Semestre)

## Sobre o Projeto

Para o último projeto no sexto semestre, a empresa colaborativa foi a [Pro4Tech](https://www.pro4tech.com.br/), uma empresa que trabalha com soluções inovadoras que impulsionam o crescimento, otimizam processos e potencializa o negócio de seus clientes. Eles possuem serviços na área de desenvolvimento web, aplicativos, inteligência artificial (IA), inteligência empresarial (BI), automação de processos robóticos (RPA) e inteligência das coisas (IoT), utilizando métodos ágeis.

O projeto proposto pelo cliente foi de desenvolver um aplicativo para otimizar o processo de recrutamento e seleção de candidatos dentro das empresas, através de login e autenticação multifator e inserindo a descrição da vaga. Com base nos CHA's (Competências, Habilidades e Atitudes) de cada cargo, um web scraping deve ser realizado em uma rede social de recrutamento e os candidatos devem ser ranqueados de acordo com sua aderência ao perfil da vaga. As empresas também serão notificadas quando os resultados estiverem disponíveis.

Assim, a partir da proposta e requisitos solicitados pela empresa, a solução implementada trouxe as seguintes funcionalidades ao sistema:

* **Autenticação:** A primeira tela inicial é a de autenticação, onde a empresa deve fornecer suas credenciais, que consistem em um endereço de e-mail, senha e realizar uma autenticação de dois fatores antes de obter acesso a qualquer funcionalidade.;
* **Autenticação dois fatores:** Como mencionado anteriormente, a empresa deve completar a autenticação de dois fatores para acessar a aplicação, a qual é realizada por meio de um e-mail previamente cadastrado pela empresa 
* **Cadastro de Empresa:** Se a empresa ainda não possui uma conta, ela pode se cadastrar selecionando a opção correspondente na tela inicial. Após essa seleção, o usuário será redirecionado para um formulário que precisa ser preenchido para criar uma conta, permitindo assim que a empresa acesse o sistema;
* **Listagem das Vagas:** Após o login, a empresa terá acesso à listagem de vagas que foram cadastradas. Nesta página, a empresa pode editar as informações da vaga e visualizar o ranqueamento mais recente dos candidatos para essa vaga;
* **Ranqueamento de Candidatos:** Ao clicar no ícone de visualização, o usuário poderá ver os oito melhores candidatos para a vaga em questão, juntamente com a porcentagem de correspondência que cada candidato possui, indicando o quanto são adequados para aquela vaga; 
* **Cadastro da Vaga (CHA):** Nesta tela, o usuário pode criar uma nova vaga, fornecendo um nome e um nível. Com base nessas informações, uma IA gerará uma descrição da vaga com base nos Conhecimentos, Habilidades e Atitudes (CHA). Essa descrição pode ser posteriormente editada e aprimorada pela IA. Após isso, é possível salvar os dados da vaga novamente ou solicitar a correspondência dos candidatos, onde será realizado um Web Scrapping e os melhores perfis serão selecionados para a vaga;
* **Perfil:** A empresa pode visualizar suas informações cadastradas nesta página, além de poder editá-las e redefinir a senha, proporcionando flexibilidade na gestão da conta;
* **Redefinição de senha:** Além de poder redefinir a senha através da página de perfil mencionada anteriormente, é possível fazê-lo também na tela de login, caso a pessoa tenha esquecido sua senha;
* **Notificações:** Quando a empresa gera uma descrição CHA ou realiza um match, a empresa é notificada por e-mail. Adicionalmente, é possível acessar uma página de notificações dentro do site para acompanhar as informações relevantes.

![Gif da execução do projeto](../img/6-semestre.gif)

> [Acesse o repositório no GitHub clicando aqui](https://github.com/Inodevs-6/Inodevs-doc)

## Tecnologias Utilizadas

* **Front-end:** 
    - **HTML:** linguagem de marcação para a criação do site;
    - **CSS:** linguagem para a estilização do site;
    - **TypeScript:** linguagem de programação para desenvolvimento de interações da aplicação web;
    - **Vue.js:** framework em JavaScript para desenvolvimento de interfaces gráficas.
* **Back-end - Persistência de Dados:** 
    - **Java:** linguagem de programação para contrução do Back-End;
    - **Spring:** framework em Java para controle de dependência para fazer a persistência de dados;
    - **MySQL:** sistema de gerenciamento de banco de dados.
* **Back-end - Inteligência Artificial:** 
    - **Python:** linguagem de programação para contrução da inteligência artificial;
    - **Django:** framework em Python utilizado como servidor para acesso da inteligência artificial.
* **Outros:** 
    - **Figma:** ferramenta para criação do protótipo do projeto;
    - **Jira:** ferramenta para a gestão de projetos utilizando a metodologia Scrum.

## Contribuições Pessoais

Nesse último semestre, atuei com desenvolvedor, onde participei principalmente no desenvolvimento do backend, com a linguagem java através do framework Spring. Participei da criação do DDL do banco de dados Mysql e de suas adições/modificações. Com o Spring trabalhei em diversas rotas, tais quais: cadastro de cargo, edição de cargo, login de usuário, cadastro de novo usuário, edição de usuário, redefinição de senha de usuário logado, redefinição de senha para usuários que esqueceram a senha e fatores de segurança da senha. Além disso, também participei do desenvolvimento do frontend, principalmente nas conexões com o backend das rotas que fiz e no desenvolvimento de algumas interfaces, como a edição de cargo já cadastrada, cadastro de empresa, perfil de usuário e redefinição de senha.

## Hard Skills

* **HTML5** - sei fazer com autonomia;
* **CSS3** - sei fazer com auxílio de consultas;
* **TypeScript** - sei fazer com auxílio de consultas;
* **Vue.js** - sei fazer com auxílio de consultas;
* **Java** - sei fazer com autonomia;
* **Spring Boot** - sei fazer com auxílio de consultas;
* **Python** - sei fazer com autonomia;
* **Django:** - conhecimento básico.

## Soft Skills

### Proatividade:

Nesse semestre uma caracteristica em que me destaquei, foi a proatividade, pois todo começo de sprint me dispus a participar de varias task's e em todas comecei cedo para prevenir atrasos e poder ajudar a completar a entrega com forme o planejado.

### Entrega de Resultado:

Entreguei todas as minhas task's e colaborei em varias outra para ajudar a equipe, também me dispus a fazer as task's sem desenvolvedores e estive em todas as finalizações de entrega, para garantir que tudo estava funcionando e sem bugs. Trabalhei principalmente com o backend, mas também tive colaborações importantes no frontend. Também me ofereci para apresentar as sprint's para o cliente.