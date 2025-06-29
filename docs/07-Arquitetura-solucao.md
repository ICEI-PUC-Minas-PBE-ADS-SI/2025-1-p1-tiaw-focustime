# Arquitetura da solução

<span style="color:red">Pré-requisitos: <a href="05-Projeto-interface.md"> Projeto de interface</a></span>

![Arquitetura do Site](https://github.com/user-attachments/assets/3aeef79f-6013-44eb-9e42-b534cba82ab3)
      
## Funcionalidades

Esta seção apresenta as funcionalidades da solução.

##### Funcionalidade 1 - Cadastro de contatos

Permite a inclusão de contatos para o sistema

* **Estrutura de dados:** [Contatos](#estrutura-de-dados---contatos)
* **Instruções de acesso:**
  * Abra o site;
  * Acesse o link "Criar nova conta" (abaixo do botão "Entrar");
  * Em seguida, realize o cadastro.
* **Tela da funcionalidade**:

![image](https://github.com/user-attachments/assets/1626af3f-5df1-4e8a-b636-1413046f0f0a)

Permite a alteração dos dados pessoais para o sistema

* **Estrutura de dados:** [Contatos](#estrutura-de-dados---contatos)
* **Instruções de acesso:**
  * Abra o site;
  * Após a criação do usuário, faça o login;
  * Em seguida, ao ser redirecionado para a página principal, clique no perfil (personagem no canto superior direito da tela);
  * Faça as alterações.
* **Tela da funcionalidade**:

![image](https://github.com/user-attachments/assets/e1566b43-c101-4fea-8989-ae2b53e5ddf8)

Permite a exclusão dos dados pessoais para o sistema

* **Estrutura de dados:** [Contatos](#estrutura-de-dados---contatos)
* **Instruções de acesso:**
  * Abra o site;
  * Após a criação do usuário, faça o login;
  * Em seguida, ao ser redirecionado para a página principal, selecione a barra de pesquisa e coloque a seguinte URL -> https://focustime-five.vercel.app/admin.html;
  * Já está disponível para exclusão (confira nesse link -> https://focustime-9z8f.onrender.com/usuarios).
* **Tela da funcionalidade**:

![image](https://github.com/user-attachments/assets/47628d79-43f7-4328-bce2-7ee58dff8f44)

##### Funcionalidade 2 - Criação de Tarefas

Permite a criação de tarefas para o sistema

* **Estrutura de dados:** [Tarefas](#estrutura-de-dados---tarefas)
* **Instruções de acesso:**
  * Abra o site;
  * Faça o login;
  * Em seguida, ao ser redirecionado para a página principal, selecione, no menu, a opção "TAREFAS";
  * Coloque as informações da tarefa e a dificuldade;
  * Clique em "Criar Tarefa".
* **Tela da funcionalidade**:

![image](https://github.com/user-attachments/assets/c1f48039-a5ed-4e9c-a71d-4ba0212f05a9)

##### Funcionalidade 3 - Eventos na Agenda

Permite a adição de eventos na agenda

* **Estrutura de dados:** [Agenda](#estrutura-de-dados---agenda)
* **Instruções de acesso:**
  * Abra o site;
  * Faça o login;
  * Em seguida, ao ser redirecionado para a página principal, selecione, no menu, a opção "AGENDA";
  * Selecione o botão "Criar Evento";
  * Coloque as informações (título, horário e data);
  * Clique em "Salvar";
  * Visualize seus compromissos em "Ver Todos os Eventos".
* **Tela da funcionalidade**:

![image](https://github.com/user-attachments/assets/199d6e9b-1528-44b3-a401-e2d6177d809d)
![image](https://github.com/user-attachments/assets/26f7edb6-d644-4b58-8e58-9c62dd3fe29d)

### Estruturas de dados

Descrição das estruturas de dados utilizadas na solução com exemplos no formato JSON.Info.

##### Estrutura de dados - Contatos

Contatos da aplicação

```json
  {
    "id": "586a",
    "nome": "Matheus Henrique",
    "idade": 18,
    "cpf": "15975395175",
    "telefone": "15975395175",
    "email": "matheushbf14@gmail.com",
    "password": "123456Ma",
    "foto": "https://res.cloudinary.com/dqmrubnvg/image/upload/v1750995730/k6pdjdh2pmjw4u4abipj.jpg",
    "dataCadastro": "2025-06-24T21:08:14.339Z"
  }
  
```

##### Estrutura de dados - Usuários 

Registro dos usuários do sistema utilizados para login e para o perfil do sistema.

```json
  {
      "id": "586a",
      "nome": "Matheus Henrique",
      "email": "matheushbf14@gmail.com",
      "password": "123456Ma",
      "foto": "https://res.cloudinary.com/dqmrubnvg/image/upload/v1750995730/k6pdjdh2pmjw4u4abipj.jpg",
  }
```

##### Estrutura de dados - Tarefas

Contatos da aplicação

```json
  {
      "id": "9178",
      "titulo": "Documentação",
      "descricao": "Documentação do nosso projeto de TIAW - Gestão de Tempo.",
      "data": "2025-06-29",
      "dificuldade": "difícil"
    }
  
```

##### Estrutura de dados - Agenda

Contatos da aplicação

```json
  {
    "id": "9ec3",
    "dia": 2,
    "mes": 7,
    "ano": 2025,
    "titulo": "Apresentação de TIAW",
    "horario": "19:00"
  }
  
```

### Módulos e APIs

Esta seção apresenta os módulos e APIs utilizados na solução.

**Images**:

* Cloudinary - [https://cloudinary.com/](https://cloudinary.com/)

**Fonts:**

* Icons Font Face - [https://fontawesome.com/](https://fontawesome.com/)

**Scripts:**

* Render - [https://render.com/](https://render.com/)


## Hospedagem

Utilizamos o [Render](https://render.com/) para hospedar os dados do db.json, então tudo que estava rodando no LocalHost passou a rodar no link https://focustime-9z8f.onrender.com;
E para a parte de Front-end utilizamos o [Vercel](https://vercel.com/), na qual busca as informações do último commit no GitHub.
