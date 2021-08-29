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

<figcaption>Tabela 3 - Descrição do processo de cadastro de medicamento</figcaption>

</center>
<br/>