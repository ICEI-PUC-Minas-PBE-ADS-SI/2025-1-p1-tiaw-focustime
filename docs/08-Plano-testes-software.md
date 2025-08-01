# Plano de testes de software

<span style="color:red">Pré-requisitos: <a href="03-Product-design.md"> Especificação do projeto</a></span>, <a href="05-Projeto-interface.md"> Projeto de interface</a>

**Caso de teste** -> **CT-001 – Cadastrar perfil**

Requisito associado: A aplicação deve apresentar a funcionalidade de cadastro de usuários para que estes consigam criar seu perfil.

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

Requisito associado: A aplicação deve apresentar a funcionalidade de cadastro de usuários para que estes consigam criar seu perfil.

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

Requisito associado: A aplicação deve apresentar a funcionalidade de cadastro de usuários para que estes consigam criar seu perfil.

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

Requisito associado: A aplicação deve apresentar a funcionalidade de cadastro de usuários para que estes consigam criar seu perfil.

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

Requisito associado: A aplicação deve permitir o login apenas com credenciais corretas de usuários cadastrados.

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

Requisito associado: A aplicação deve permitir o login apenas com credenciais corretas de usuários cadastrados.

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

**Caso de teste** -> **CT-007 – Criar tarefa**

Requisito associado: A aplicação deve permitir ao usuário criar tarefas na sua área logada.

Objetivo do teste: Verificar se o usuário consegue criar uma nova tarefa com sucesso.

Passos:

- Navegar até a área de tarefas
- Clicar em “Nova Tarefa”
- Preencher os campos obrigatórios (título, descrição, data, dificuldade)
- Clicar em “Salvar”

Critério de êxito: Aparece uma mensagem de concluído com sucesso e a nova tarefa aparece listada corretamente entre as tarefas ativas.

Responsável pela elaboração do caso de teste: Ana Luiza

Responsável pelo artefato: Fernando

[Vídeo](https://github.com/user-attachments/assets/6f871439-677a-4fdc-b068-3860e4162ec9)

**Caso de teste** -> **CT-008 – Visualizar tarefas ativas e verificar pontuação de XP**

Requisito associado: O sistema deve apresentar todas as tarefas ativas de um usuário logado e deve atualizar a pontuação do usuário ao concluir uma tarefa.

Objetivo do teste: Verificar se as tarefas ativas são exibidas corretamente, se ao concluir uma tarefa, o sistema remove ela da lista ativa e se a pontuação de XP do usuário é atualizada corretamente.

Passos:

- Navegar até a área de tarefas
- Verificar a listagem das tarefas ativas
- Concluir uma ou mais tarefas
- Observar se:
  - A tarefa desaparece da lista ativa
  - A pontuação de XP é aumentada

Critério de êxito: As tarefas ativas são listadas corretamente, a conclusão de tarefas remove elas da lista e a pontuação de XP aumenta conforme esperado.

Responsável pela elaboração do caso de teste: Ana Luiza

Responsável pelo artefato: Fernando

[Vídeo](https://github.com/user-attachments/assets/d2abc800-eb1b-43b7-81d5-ef3852ac3555)

**Caso de teste** -> **CT-009 – Excluir tarefa**

Requisito associado: A aplicação deve permitir a exclusão de tarefas pelo usuário.

Objetivo do teste: Garantir que o usuário possa excluir uma tarefa.

Passos:

- Acessar a lista de tarefas
- Identificar a tarefa desejada
- Clicar no ícone ou botão de exclusão
- Confirmar a exclusão se solicitado

Critério de êxito: A tarefa é removida da lista com sucesso e não aparece mais entre as tarefas concluídas.

Responsável pela elaboração do caso de teste: Ana Luiza

Responsável pelo artefato: Fernando

[Vídeo](https://github.com/user-attachments/assets/198f25bc-b1ae-4461-9704-063dd464df6e)

**Caso de teste** -> **CT-010 – Criação de Evento**

Requisito associado: A aplicação deve permitir a criação de um novo evento.

Objetivo do teste: Espera-se que, ao digitar todas as informações (título, horário e data), o usuário consiga salvar o evento.

Passos:

- Acessar a página de Agenda
- Clicar em "Criar Evento"
- Digitar as informações
- Clicar em "Salvar"

Critério de êxito: O evento é salvo corretamente e o usuário é redirecionado para a página de Agenda (na qual ele pode visualizar o/os evento/s).

Responsável pela elaboração do caso de teste: Matheus

Responsável pelo artefato: Ana Luiza

![Imagem do WhatsApp de 2025-06-29 à(s) 16 47 33_b7af118a](https://github.com/user-attachments/assets/386fa993-c0c3-4193-9e80-bb13033ecef7)

**Caso de teste** -> **CT-011 – Tentativa de criar evento em data passada**

Requisito associado: A aplicação deve impedir criação de evento em data anterior.

Objetivo do teste: Verificar se o sistema impede a criação de eventos em datas passadas.

Passos:

- Acessar a página de criação de evento ("Criar Evento")
- Selecionar uma data anterior à atual
- Preencher horário e título
- Clicar em "Salvar"

Critério de êxito: Mensagem de alerta -> "❌ Não é possível criar eventos em datas passadas".

Responsável pela elaboração do caso de teste: Matheus

Responsável pelo artefato: Ana Luiza

![Imagem do WhatsApp de 2025-06-29 à(s) 16 47 32_89351662](https://github.com/user-attachments/assets/f333fb42-6bd7-4387-a12c-35dafc686b64)

**Caso de teste** -> **CT-012 – Tentativa sem preencher campos obrigatórios**

Requisito associado: A aplicação deve impedir o usuário de avançar sem os campos obrigatórios do evento.

Objetivo do teste: Verificar se o sistema valida a obrigatoriedade do título, horário e seleção de data.

Passos:

- Acessar a página de criação de evento ("Criar Evento")
- Não selecionar o dia e/ou não preencher título e horário
- Clicar em "Salvar"

Critério de êxito: Mensagem de alerta -> "Por favor, selecione um dia e preencha título e horário!".

Responsável pela elaboração do caso de teste: Matheus

Responsável pelo artefato: Ana Luiza

![Imagem do WhatsApp de 2025-06-29 à(s) 16 47 33_bf40b10a](https://github.com/user-attachments/assets/058f82d5-dfe0-4571-9fa7-416cb388c574)

**Caso de teste** -> **CT-013 – Tentativa com horário já passado no mesmo dia**

Requisito associado: A aplicação deve impedir criação de evento em horário anterior ao atual.

Objetivo do teste: Garantir que o sistema impeça eventos com horário anterior ao momento atual.

Passos:

- Acessar a página de criação de evento ("Criar Evento")
- Selecionar o dia atual
- Informar um horário anterior ao horário atual do sistema
- Clicar em "Salvar"

Critério de êxito: Mensagem de alerta -> "❌ Não é possível criar eventos para horários que já passaram".

Responsável pela elaboração do caso de teste: Matheus

Responsável pelo artefato: Ana Luiza

![Imagem do WhatsApp de 2025-06-29 à(s) 16 47 33_5c33646f](https://github.com/user-attachments/assets/c73536de-3c54-42e0-bfd0-b82536195155)

**Caso de teste** -> **CT-014 – Exibição do evento na agenda**

Requisito associado: A aplicação deve exibir o evento criado na agenda.

Objetivo do teste: Verificar se o evento salvo aparece corretamente na lista da agenda.

Passos:

- Após a criação de evento, o usuário será redirecionado para a página de Agenda
- Observar se o evento aparece na listagem, com data, horário, título e botões de "Editar" e "Apagar"

Critério de êxito: O evento "Teste", com data 30/06/2025 e horário 10:00, aparece corretamente na Agenda de Eventos.

Responsável pela elaboração do caso de teste: Matheus

Responsável pelo artefato: Ana Luiza

![Imagem do WhatsApp de 2025-06-29 à(s) 16 47 32_313e9949](https://github.com/user-attachments/assets/b99613e8-3065-433e-89c5-042d8832f365)

**Caso de teste** -> **CT-015 – Editar e excluir evento na agenda**

Requisito associado: O sistema deve permitir a edição de eventos salvos pelo usuário e o deve permitir a exclusão de eventos da agenda.

Objetivo do teste: Verificar se o sistema permite -> editar corretamente um evento já criado e excluir um evento da agenda com sucesso.

Passos:

- Acessar a agenda com eventos cadastrados
- Clicar no botão “Editar” ao lado de um evento
- Alterar os dados do evento (como título, data ou horário)
- Clicar em “Salvar”

Critério de êxito: O evento é atualizado com as novas informações, mensagem de sucesso (ex: “Evento atualizado com sucesso!”) é exibida e as informações antigas são substituídas na agenda.

Responsável pela elaboração do caso de teste: Matheus

Responsável pelo artefato: Ana Luiza

[Vídeo](https://github.com/user-attachments/assets/af4fa0a0-bd9f-4a18-b965-bf6b3f269707)
