# Plano de testes de software

<span style="color:red">Pré-requisitos: <a href="03-Product-design.md"> Especificação do projeto</a></span>, <a href="05-Projeto-interface.md"> Projeto de interface</a>

**Caso de teste** -> **CT-001 – Cadastrar perfil**
Requisito associado: RF-001 - A aplicação deve apresentar a funcionalidade de cadastro de usuários para que estes consigam criar seu perfil.

Objetivo do teste: Verificar se o usuário consegue se cadastrar na aplicação.

Passos:
- Acessar o navegador;
- Link do Site -> [https://focustime-five.vercel.app/](https://focustime-five.vercel.app/);
- Clicar em "Criar nova conta"
- Preencher os campos obrigatórios (e-mail, nome, sobrenome, celular, CPF, senha, confirmação de senha)
- Clicar em "Criar conta"

Critério de êxito: O cadastro foi realizado com sucesso.

Responsável pela elaboração do caso de teste: Fernando

Responsável pelo artefato: Matheus

![Cadastro realizado](https://github.com/user-attachments/assets/a0ac8085-2dab-41f0-bd3e-3ee0e9746bb3)

**Caso de teste** -> **CT-002 – Cadastro com e-mail já existente**
Requisito associado: RF-001 - A aplicação deve apresentar a funcionalidade de cadastro de usuários para que estes consigam criar seu perfil.

Objetivo do teste: Verificar se a aplicação impede o cadastro de um usuário com e-mail já registrado no sistema.

Passos:
- Acessar o navegador;
- Link do Site → [https://focustime-five.vercel.app/](https://focustime-five.vercel.app/);
- Clicar em "Criar nova conta";
- Preencher os campos obrigatórios com dados válidos, utilizando um e-mail já cadastrado no sistema (exemplo: matheushbf14@gmail.com);
- Clicar em "Criar conta".

Critério de êxito: A aplicação deve exibir uma mensagem de erro informando que o e-mail já está cadastrado e não deve permitir o cadastro duplicado.

Mensagem esperada:

"Este e-mail já está cadastrado."

Responsável pela elaboração do caso de teste: Fernando
Responsável pelo artefato: Matheus
![Screenshot_4](https://github.com/user-attachments/assets/5622c535-b152-42fc-ad62-a908b5ff57ee)

**Caso de teste** -> **CT-003 – Cadastro com CPF já existente**
Requisito associado: RF-001 - A aplicação deve apresentar a funcionalidade de cadastro de usuários para que estes consigam criar seu perfil.

Objetivo do teste: Verificar se a aplicação impede o cadastro de um usuário com CPF já cadastrado.

Passos:

- Acessar o navegador;
- Link do Site -> [https://focustime-five.vercel.app/](https://focustime-five.vercel.app/);
- Clicar em "Criar nova conta"
- Preencher os campos obrigatórios (e-mail, nome, sobrenome, celular, CPF já cadastrado, senha, confirmação de senha)
- wwClicar em "Criar conta"

Critério de êxito: A aplicação exibe a mensagem “Este CPF já está cadastrado.” e impede a criação da conta.

Responsável pela elaboração do caso de teste: Fernando

Responsável pelo artefato: Matheus
![Screenshot_5](https://github.com/user-attachments/assets/e5c56546-ed62-4865-965a-a00f8c7bd53d)

**Caso de teste** -> **CT-004 – Cadastro com senhas diferentes**
Requisito associado: RF-001 - A aplicação deve apresentar a funcionalidade de cadastro de usuários para que estes consigam criar seu perfil.

Objetivo do teste: Verificar se a aplicação impede o cadastro quando as senhas digitadas não coincidem.

Passos:

- Acessar o navegador;
- Link do Site -> [https://focustime-five.vercel.app/](https://focustime-five.vercel.app/);
- Clicar em "Criar nova conta"
- Preencher os campos obrigatórios (e-mail, nome, sobrenome, celular, CPF, senha e confirmação de senha com valor diferente)
- Clicar em "Criar conta"

Critério de êxito: A aplicação exibe a mensagem “As senhas não coincidem!” e impede a criação da conta.

Responsável pela elaboração do caso de teste: Fernando

Responsável pelo artefato: Matheus
![Screenshot_1](https://github.com/user-attachments/assets/4894a385-de85-4fb8-bf72-400ed9412465)

**Caso de teste** -> **CT-005 – Login com e-mail ou senha incorretos**
Requisito associado: RF-002 - A aplicação deve permitir o login apenas com credenciais corretas de usuários cadastrados.

Objetivo do teste: Verificar se a aplicação exibe uma mensagem de erro ao tentar realizar login com e-mail ou senha incorretos.

Passos:

- Acessar o navegador;
- Link do Site -> [https://focustime-five.vercel.app/](https://focustime-five.vercel.app/);
- Preencher o campo “Email” com um endereço válido cadastrado ou inválido;
- Preencher o campo “Senha” com uma senha incorreta;
- Clicar em "Entrar"

Critério de êxito: A aplicação exibe a mensagem “Email ou senha incorretos” e impede o login.

Responsável pela elaboração do caso de teste: Fernando

Responsável pelo artefato: Matheus
![Screenshot_3](https://github.com/user-attachments/assets/f25aff53-7d86-4ee4-ac82-22b30c5b6990)

**Caso de teste** -> **CT-006 – Login realizado com sucesso**
Requisito associado: RF-002 - A aplicação deve permitir o login apenas com credenciais corretas de usuários cadastrados.

Objetivo do teste: Verificar se o usuário consegue realizar login corretamente na aplicação com e-mail e senha válidos.

Passos:

- Acessar o navegador;
- Link do Site -> [https://focustime-five.vercel.app/](https://focustime-five.vercel.app/);
- Preencher o campo “Email” com um e-mail válido e cadastrado;
- Preencher o campo “Senha” com a senha correta;
- Clicar em "Entrar"

Critério de êxito: A aplicação exibe a mensagem “Login realizado com sucesso! Redirecionando...” e permite o acesso à conta do usuário.

Responsável pela elaboração do caso de teste: Fernando

Responsável pelo artefato: Matheus
![Imagem do WhatsApp de 2025-06-29 à(s) 11 28 43_0bb3612e](https://github.com/user-attachments/assets/62a83086-6922-41c0-82f0-5aa9fd793329)
