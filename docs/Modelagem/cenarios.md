# Cenários
## Introdução

<p style="text-indent: 20px; text-align: justify">
O design baseado em cenários é um processo que utiliza diferentes tipos de cenários
como representação básica e fundamental durante todas as atividades envolvidas na
concepção de uma solução de IHC (Rosson e Carroll, 2002; Carroll, 1995), assim adotaremos essa técnica para mostrar as funções acessíveis do VivaBem ilustrando esses cenários.
</p>

## Objetivo
<p style="text-indent: 20px; text-align: justify">
Os cenários podem ser usados em todas as etapas do processo de design como descrever objetivos numa atividade do sistema elicitando os requisitos e descreveendos numa forma de história. Os cenários podem ser dividos em diferentes tipos como: <a>cenários de problemas, cenários de atividade, cenários de informações e cenários de interação.</a> Com a adoção dessa técnica podemos prever os possíveis cenários que atingiram os casos de usos elicitados, confirmando se os nossos casos de usos abordam todos os casos que podem ser utilizados em diferentes cenários pelo o usuário do sistema. Sendo assim, o cenário servindo para descrever e prever a experiência e o comportamento que o usuário vai ter em relação ao sistema.
</p>

## Cenários
### C01: Realizar cadastro

<center>

|Cenário|Descrição|
|:---|:---|
|Título|Realizar cadastro|
|Objetivo|Permitir que os usuários realizem cadastro no aplicativo|
|Contexto|Local: Entrar no aplicativo. <br/> Pré-condição: Ter o app instalado <br> Pós-condição: Usuário realiza a inscrição|
|Atores|Usuário que usa medicamentos e/ou faz exames, e que deseja utilizar o aplicativo|
|Recursos|Conexão de internet, aplicativo instalado|
|Episódios|Usuário entra pela primeira vez no aplicativo. <br/> Usuário informa o CPF, insere a senha da conta GOV.br e terá de resolver um CAPTCHA|
|Exceção|Internet cair <br/> Não possuir conta no GOV.br |

<figcaption>Tabela 1 - Descrição do processo de cadastro de usuário</figcaption>

</center>
<br/>

### C02: Realizar cadastro de um medicamento

<center>

|Cenário|Descrição|
|:---|:---|
|Título|Realizar cadastro de um medicamento|
|Objetivo|Permitir que os usuários realize o cadastro de um medicamento|
|Contexto|Local: Entrar no aplicativo e ir na aba de medicamentos <br/> Pré-condição: Estar logado no app <br> Pós-condição: Usuário realiza o cadastro|
|Atores|Usuário que usa medicamentos, e que deseja cadastrar um medicamento no aplicativo|
|Recursos|Conexão de internet, aplicativo instalado, usar medicamento|
|Episódios|Usuário deseja cadastrar um novo medicamento <br/>Usuário informa nome do medicamento, suas informações, o horário, e o laudo|
|Exceção|Internet cair <br/> Não tomar medicamento<br/> Não possuir laudo médico |

<figcaption>Tabela 2 - Descrição do processo de cadastro de medicamento</figcaption>

</center>
<br/>


### C03: Realizar cadastro de um exame

<center>

|Cenário|Descrição|
|:---|:---|
|Título|Realizar cadastro de um exame|
|Objetivo|Permitir que os usuários realize o cadastro de um exame|
|Contexto|Local: Entrar no aplicativo e ir na aba de exame <br/> Pré-condição: Estar logado no app <br> Pós-condição: Usuário realiza o cadastro|
|Atores|Usuário que realiza exame, e que deseja cadastrar um exame no aplicativo|
|Recursos|Conexão de internet, aplicativo instalado, realiza exames|
|Episódios|Usuário deseja cadastrar um novo exame <br/>Usuário insere as infomações do exame|
|Exceção|Internet cair <br/> Não tem exames

<figcaption>Tabela 3 - Descrição do processo de cadastro de exame</figcaption>

</center>
<br/>

### C04: Diário do usuário

<center>

|Cenário|Descrição|
|:---|:---|
|Título|Diário do usuário|
|Objetivo|Permitir que o usuário visualize as horários dos medicamentos cadastrados e responder a como o usuário está se sentindo|
|Contexto|Local: Entrar no aplicativo e ir na aba diário <br/> Pré-condição: Estar logado no app <br> Pós-condição: Usuário visualizar os horários dos próximos medicamentos|
|Atores|Usuário que usa medicamentos, e que deseja visualizar os horários|
|Recursos|Conexão de internet, aplicativo instalado, usar medicamento|
|Episódios|Usuário deseja visualizar os horários das proximas medicações<br/> O usuário deseja relatar como está se sentindo|
|Exceção|Internet cair <br/> Não tomar medicamento<br/> Não possuir laudo médico |

<figcaption>Tabela 4 - Descrição da aba diário</figcaption>

</center>
<br/>


### C05: Acessar Notificações

<center>

|Cenário|Descrição|
|:---|:---|
|Título|Acessar notificações|
|Objetivo|Acessar informações e notícias que o aplicativo expõe ao usuário|
|Contexto|Local: Iniciar o aplicativo<br/>Pré-condição: Ter o app instalado, cadastro realizado<br/>Pós-condição: O usuário se mantém informado pelas notificações do aplicativo|
|Atores|Usuário que usa medicamentos e/ou faz exames, e que deseja utilizar o aplicativo|
|Recursos|Conexão de internet, aplicativo instalado|
|Episódios|Usuário já se cadastrou no aplicativo<br/>Usuário acessa a página de notificações<br/>Usuário visualiza suas notificações<br/>|
|Exceção|Sem conexão com a internet<br/>Acessa a página mais não possui nenhuma notificação|

<figcaption>Tabela 5 - Descrição do processo de notificações</figcaption>
<br/>

</center>

### C06: Sair do aplicativo

<center>

|Cenário|Descrição|
|:---|:---|
|Título|Sair do aplicativo|
|Objetivo|Sair do aplicativo retirando a conta|
|Contexto|Local: Aba das configurações<br/>Pré-condição: Ter o app instalado, cadastro realizado<br/>Pós-condição: O usuário desloga a conta que estava utilizando|
|Atores|Usuário que estava cadastrado e quer retirar a conta cadastrada|
|Recursos|Conexão de internet, aplicativo instalado|
|Episódios|Usuário já se cadastrou no aplicativo<br/>Usuário quer retirar a conta do aplicativo
|Exceção|Sem conexão com a internet<br/>Não ter conta cadastrada|

<figcaption>Tabela 6 - Descrição do processo de sair do aplicativo</figcaption>
<br/>

</center>

### C07: Registrar efeitos colaterais

<center>

|Cenário|Descrição|
|:---|:---|
|Título|Registrar um efeito colateral|
|Objetivo|Identificar um efeito colateral de algum medicamento|
|Contexto|Entrar no aplicativo<br/>Pré-condição: Possuir cadastro no aplicativo e ter ao menos um medicamento cadastrado<br/>Pós-condição: Acesso ao questionário de saúde|
|Atores|Usuário que usa medicamentos e/ou faz exames, e que deseja utilizar o aplicativo|
|Recursos|Aplicativo instalado, ao menos um medicamento cadastrado|
|Episódios|Usuário acessa o aplicativo<br/>seleciona a função de Diário ou as configurações de "Mais Opções"<br/>Usuário seleciona a opção "Registrar efeito colateral"<br/>Será direcionado a um questionário com perguntas sobre os principais sintomas|
|Exceção|Indisponibilidade do aplicativo|

<figcaption>Tabela 7 - Descrição do processo para registrar efeitos colaterais</figcaption>
<br/>

</center>

### C08: Realizar interação medicamentosa

<center>

|Cenário|Descrição|
|:---|:---|
|Título|Realizar interação medicamentosa|
|Objetivo|Permitir que os usuários visualize os medicamentos|
|Contexto|Local: Entrar no aplicativo e ir na aba de medicamentos <br/> Pré-condição: Estar logado no app <br> Pós-condição: Usuário olha o medicamento cadastrado|
|Atores|Usuário que deseja visualizar os medicamentos, e que queira ver as suas informações no aplicativo|
|Recursos|Conexão de internet, aplicativo instalado|
|Episódios|Usuário deseja ver um medicamento cadastrado <br/>Usuário seleciona o medicamento<br/>Usuário analisa as informações do medicamento|
|Exceção|Internet cair <br/> Não ter medicamento cadastrado

<figcaption>Tabela 8 - Descrição do processo de interação medicamentosa</figcaption>

</center>
<br/>

### C09: Termos de uso do aplicativo

<center>

|Cenário|Descrição|
|:---|:---|
|Título|Termos de uso do aplicativo|
|Objetivo|Consultar os termos de uso do aplicativo|
|Contexto|Entrar no aplicativo<br/>Pré-condição: Possuir cadastro no aplicativo<br/>Pós-condição: Visualizar os termos de uso|
|Atores|Usuário que usa medicamentos e/ou faz exames, e que deseja utilizar o aplicativo|
|Recursos|Aplicativo instalado|
|Episódios|Usuário acessa o aplicativo<br/>seleciona a função Mais opções<br/>Usuário seleciona a opção Termos de uso|
|Exceção|Indisponibilidade do aplicativo|

<figcaption>Tabela 9 - Descrição do processo para consulta dos termos de uso</figcaption>
<br/>

</center>

### C10: Trocar senha

<center>

|Cenário|Descrição|
|:---|:---|
|Título|Trocar senha para acesso|
|Objetivo|Trocar senha do seu login no aplicativo|
|Contexto|Entrar no aplicativo<br/>Pré-condição: Possuir cadastro no aplicativo<br/>Pós-condição: Senha trocada com sucesso|
|Atores|Usuário que usa medicamentos e/ou faz exames, e que deseja utilizar o aplicativo|
|Recursos|Conexão de internet, aplicativo instalado|
|Episódios|Usuário acessa o aplicativo<br/>Usuário seleciona a função Mais opções<br/>Usuário seleciona a opção Trocar senha<br/>Usuário digita nova senha|
|Exceção|Sem conexão com a internet<br/>Servidor fora do ar<br/>Nova senha inválida|

<figcaption>Tabela 10 - Descrição do processo de alteração de senha</figcaption>
<br/>

</center>

### C11: Rendimentos

<center>

|Cenário|Descrição|
|:---|:---|
|Título|Rendimentos|
|Objetivo|Ver o rendimento do usuário na utilização do aplicativo|
|Contexto|Entrar no aplicativo<br/>Pré-condição: Ter cadastrado e utilizado o aplicativo por um dia<br/>Pós-condição: Rendimento mostrado na tela|
|Atores|Usuário que usa medicamentos e/ou faz exames, e que deseja ver como está seu desempenho durante o uso do aplicativo|
|Recursos|Conexão de internet, aplicativo instalado, medicamentos e/ou exames cadastrados|
|Episódios|Usuário acessa o aplicativo<br/>Usuário seleciona a função Mais opções<br/>Usuário seleciona a opção rendimento<br/>Usuário visualiza seu rendimento durante um certo período|
|Exceção|Sem conexão com a internet<br/>Servidor fora do ar<br/>Não ter cadastrado nenhum medicamento e/ou exames|

<figcaption>Tabela 11 - Descrição do rendimento</figcaption>
<br/>
</center>

### C12: Novidades
<center>

|Cenário|Descrição|
|:---|:---|
|Título|Novidades|
|Objetivo|Ver as novidades que envolve o aplicativo|
|Contexto|Entrar no aplicativo<br/>Pré-condição: Possuir cadastro no aplicativo<br/>Pós-condição: visualizar todas as novidades|
|Atores|Usuário que usa medicamentos e/ou faz exames, e que deseja saber as novidades sobre o aplicativo|
|Recursos|Conexão de internet, aplicativo instalado|
|Episódios|Usuário acessa o aplicativo<br/>Usuário seleciona a função Mais opções<br/>Usuário seleciona a opção Novidades<br/>Usuário visualizar as notícias|
|Exceção|Sem conexão com a internet<br/>Servidor fora do ar<br/>Nenhuma novidade no momento|

<figcaption>Tabela 12 - Descrição do processo novidades</figcaption>
<br/>

</center>

### C13: Informações de emergência

<center>

|Cenário|Descrição|
|:---|:---|
|Título|Informações de emergência|
|Objetivo|Manter contatos caso ocorra alguma emergência|
|Contexto|Entrar no aplicativo e selecionar a opção de "Informações de emergência"<br/>Pré-condição: Possuir cadastro no aplicativo<br/>Pós-condição: Notificação do contato registrado caso ocorra alguma emergência|
|Atores|Usuário que usa medicamentos e/ou faz exames, e que deseja utilizar o aplicativo|
|Recursos|Aplicativo instalado, ao menos um medicamento cadastrado|
|Episódios|Usuário acessa o aplicativo<br/>seleciona a função de configurações no botão "Mais Opções"<br/>Usuário seleciona a opção "Informações de emergência"<br/>Será direcionado a um formulário para preencher os dados do contato de emergência|
|Exceção|Indisponibilidade do aplicativo<br/>Sem conexão com a internet|

<figcaption>Tabela 13 - Descrição do processo de informações de emergência</figcaption>
<br/>

</center>

## Referências e Bibliografias

- Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. Autopublicação.



## Versionamento
| Versão | Data | Modificação | Autor |
|--|--|--|--|
| 1.0 | 29/08/2021 | Criação do documento| Ítalo Serra |
| 1.1 | 29/08/2021 | Introdução e objetivo | Gabriel Avelino|
| 1.2 | 29/08/2021 | Criação dos cenários| Gabriel Avelino, Ítalo Serra e João Victor|
| 1.3 | 29/08/2021 | Revisor do documento| João Victor|