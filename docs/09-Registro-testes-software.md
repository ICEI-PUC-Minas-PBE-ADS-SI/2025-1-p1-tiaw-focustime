# Registro de testes de software

<span style="color:red">Pré-requisitos: <a href="05-Projeto-interface.md"> Projeto de interface</a></span>, <a href="08-Plano-testes-software.md"> Plano de testes de software</a>

Relatório com as evidências dos testes de software realizados no sistema pela equipe, baseado em um plano de testes pré-definido.

Para cada caso de teste definido no <a href="08-Plano-testes-software.md"> Plano de testes de software</a>, realize o registro das evidências dos testes feitos na aplicação pela equipe, que comprovem que o critério de êxito foi alcançado (ou não!). Para isso, utilize uma ferramenta de captura de tela que mostre cada um dos casos de teste definidos. Observação: cada caso de teste deverá possuir um vídeo do tipo _screencast_ para caracterizar uma evidência do referido caso.

| **Caso de teste** 	| **CT-001 – Cadastrar perfil** 	|
|:---:	|:---:	|
| Requisito associado | RF-00X - A aplicação deve apresentar, na página principal, a funcionalidade de cadastro de usuários para que esses consigam criar e gerenciar seu perfil. |
| Registro de evidência | [www.teste.com.br/drive/ct-01](http://www.teste.com.br/drive/ct-01) |

| **Caso de teste** 	| **CT-002 – Realizar login** 	|
|:---:	|:---:	|
| Requisito associado | RF-00Y - A aplicação deve permitir que um usuário previamente cadastrado faça login. |
| Registro de evidência | [www.teste.com.br/drive/ct-02](http://www.teste.com.br/drive/ct-02) |

**Caso de teste	CT-001 – Cadastrar perfil**

- Requisito associado	RF-001 - A aplicação deve apresentar a funcionalidade de cadastro de usuários para que estes consigam criar seu perfil.
- Registro de evidência	[https://focustime-five.vercel.app/evidencias/ct-001](https://focustime-five.vercel.app/)

**Caso de teste	CT-002 – Cadastro com e-mail já existente**

- Requisito associado	RF-001 - A aplicação deve apresentar a funcionalidade de cadastro de usuários para que estes consigam criar seu perfil.
- Registro de evidência	[https://focustime-five.vercel.app/evidencias/ct-002](https://focustime-five.vercel.app/)

**Caso de teste	CT-003 – Cadastro com CPF já existente**

- Requisito associado	RF-001 - A aplicação deve apresentar a funcionalidade de cadastro de usuários para que estes consigam criar seu perfil.
- Registro de evidência	[https://focustime-five.vercel.app/evidencias/ct-003](https://focustime-five.vercel.app/)

**Caso de teste	CT-004 – Cadastro com senhas diferentes**

- Requisito associado	RF-001 - A aplicação deve apresentar a funcionalidade de cadastro de usuários para que estes consigam criar seu perfil.
- Registro de evidência	[https://focustime-five.vercel.app/evidencias/ct-004](https://focustime-five.vercel.app/)

**Caso de teste	CT-005 – Login com e-mail ou senha incorretos**

- Requisito associado	RF-002 - A aplicação deve permitir o login apenas com credenciais corretas de usuários cadastrados.
- Registro de evidência	[https://focustime-five.vercel.app/evidencias/ct-005](https://focustime-five.vercel.app/)

**Caso de teste	CT-006 – Login realizado com sucesso**

- Requisito associado	RF-002 - A aplicação deve permitir o login apenas com credenciais corretas de usuários cadastrados.
- Registro de evidência	[https://focustime-five.vercel.app/evidencias/ct-006](https://focustime-five.vercel.app/)

 **Caso de teste CT-007 – Tarefa Criada com Sucesso**

Requisito associado - A aplicação deve permitir ao usuário criar tarefas na sua área logada.
Registro de evidência: [Evidência CT-007](https://focustime-five.vercel.app/tarefas.html) — Página: tarefas.html


**Caso de teste CT-008 – Visualizar tarefas ativas e verificar pontuação de XP**

Requisito associado - O sistema deve apresentar todas as tarefas ativas de um usuário logado e deve atualizar a pontuação do usuário ao concluir uma tarefa.
Registro de evidência: [Evidência CT-008](https://focustime-five.vercel.app/tarefas.html) — Página: tarefas.html

**Caso de teste CT-009 – Excluir tarefa**

Requisito associado - A aplicação deve permitir a exclusão de tarefas pelo usuário.
Registro de evidência: [Evidência CT-009](https://focustime-five.vercel.app/tarefas.html) — Página: tarefas.html

**Caso de teste CT-010 – Criação de Evento**

Requisito associado - A aplicação deve permitir a criação de um novo evento.
Registro de evidência:  [Evidência CT-010](https://focustime-five.vercel.app/criarevento.html) — Página: criarevento.html

**Caso de teste CT-011 – Tentativa de criar evento em data passada**

Requisito associado - A aplicação deve impedir criação de evento em data anterior.
Registro de evidência:  [Evidência CT-011](https://focustime-five.vercel.app/criarevento.html) — Página: criarevento.html

**Caso de teste CT-012 – Tentativa sem preencher campos obrigatórios**

Requisito associado - A aplicação deve impedir o usuário de avançar sem os campos obrigatórios do evento.
Registro de evidência:  [Evidência CT-012](https://focustime-five.vercel.app/criarevento.html) — Página: criarevento.html

**Caso de teste CT-013 – Tentativa com horário já passado no mesmo dia**

Requisito associado - A aplicação deve impedir criação de evento em horário anterior ao atual.
Registro de evidência:  [Evidência CT-0013](https://focustime-five.vercel.app/criarevento.html) — Página: criarevento.html

**Caso de teste CT-014 – Exibição do evento na agenda**

Requisito associado - A aplicação deve exibir o evento criado na agenda.
Registro de evidência:  [Evidência CT-014](https://focustime-five.vercel.app/agenda.html) — Página: agenda.html

**Caso de teste CT-015 – Editar e excluir evento na agenda**

Requisito associado - O sistema deve permitir a edição de eventos salvos pelo usuário e deve permitir a exclusão de eventos da agenda.
Registro de evidência:  [Evidência CT-015](https://focustime-five.vercel.app/agenda.html) — Página: agenda.html


> **Links úteis**:
> - [Screencast: entenda o que é e como gravar vídeos com ele](https://rockcontent.com/br/blog/screencast/) 

## Avaliação

Discorra sobre os resultados do teste, ressaltando os pontos fortes e fracos identificados na solução. Comente como o grupo pretende abordar esses pontos nas próximas iterações. Apresente as falhas detectadas e as melhorias geradas a partir dos resultados obtidos nos testes.

> **Links úteis**:
> - [Ferramentas de Teste para JavaScript](https://geekflare.com/javascript-unit-testing/)
