# <a>Introdução </a>

<p style="text-indent: 20px; text-align: justify">
Usados para descrever um conjunto de ações que um sistema ou um conjunto de sistemas deve desempenhar em
colaboração com um ou mais usuários externos ao sistema, ou seja tem como objetivo descrever como será o uso de uma funcionalidade de um sistema. Nosso grupo escolheu diagrama de estados da UML para descrever como ocorre as interações do usuário com o sistema. Definindo os atores (pessoas ou outros sistemas), as classes de interação (ações dos usuários ou do sistema), os relacionamentos (ligação entre os atores e a interação) e o limite do sistema (escopo do sistema para os casos de uso).
</p>

# <a>Diagramas </a>

# <a>Descrição dos casos de uso</a>

## Realizar cadastro de usuário
<center>

Caso 1 | Informações
|-------|---------|
Descrição | Quando o aplicativo é acessado pela primeira vez após o download, é necessário realizar login utilizando uma conta governamental.
Ator(es) | Usuário
Pré-condições | Ter acesso à internet e o aplicativo instalado
Fluxo | 1 - O ator precisa abrir o aplicativo <br/>2 - Necessita inserir o CPF do autor, para vincular a uma conta governamental <br/>3 - Necessita inserir a senha da conta GOV.br <br/>4 - O autor então terá de resolver um CAPTCHA e então é finalizado o login
Pós-condições | O autor terá acesso a todas as funcionalidades do aplicativo
Rastreabilidade | Pasta: Elicitação de Requisitos/Técnicas/Requisitos elicitados -> RF01 e RF02
<figcaption>Tabela 1 - Descrição de login</figcaption>
</center>
<br/>

## Realizar cadastro de medicação
<center>

Caso 2 | Informações
|-------|---------|
Descrição | Quando o aplicativo é acessado pela primeira vez após o download, é necessário realizar login utilizando uma conta governamental.
Ator(es) | Usuário
Pré-condições | Ter acesso à internet e o aplicativo instalado
Fluxo | 1 - O ator precisa abrir o aplicativo <br/>2 - Necessita inserir o CPF do autor, para vincular a uma conta governamental <br/>3 - Necessita inserir a senha da conta GOV.br <br/>4 - O autor então terá de resolver um CAPTCHA e então é finalizado o login
Pós-condições | O autor terá acesso a todas as funcionalidades do aplicativo
Rastreabilidade | Pasta: Elicitação de Requisitos/Técnicas/Requisitos elicitados -> RF01 e RF02
<figcaption>Tabela 1 - Descrição de login</figcaption>
</center>
<br/>

## Cadastrar um exame
<center>

Caso 3 | Informações
|-------|---------|
Descrição | Quando é feito um agendamento de algum exame, é necessário realizar um cadastro desse exame.
Ator(es) | Usuário
Pré-condições | Ter acesso à internet e o aplicativo instalado
Fluxo | 1 - O ator precisa ir na aba de exames<br/>2 - Necessita ir em adicionar exames<br/>3 - Precisa incluir <br/>4 - Se o cadastro for efetivado, então poderá escolher uma senha para efetuar o login (Caso 2)
Pós-condições |
Rastreabilidade |
<figcaption>Tabela 1 - Descrição de login</figcaption>
</center>
<br/>


## Acessar notificações
<center>

Caso 5 | Informações
|-------|---------|
Descrição |Ao iniciar a aplicação, o ator pode verificar se ele tem novas notificações e visualizá-las clicando no ícone "Notificações"
Ator(es) | Usuário
Pré-condições | Ter acesso à internet e o logado no aplicativo
Fluxo |1 - O ator precisa abrir o aplicativo<br/>2 - Necessita realizar o login (Caso 2)<br/>3 - Na tela inicial, o ator clica no ícone "Notificações"<br/>4 - O ator pode verificar se existem notificações e visualizá-las
Pós-condições | Possibilita manter o ator informado pelas notificações recebidas
Rastreabilidade |
<figcaption>Tabela 5 - Descrição de login</figcaption>
</center>
<br/>

## <a>Referências e Bibliografias</a>



## <a>Versionamento</a>
| Versão | Data | Modificação | Autor |
|--|--|--|--|
| 1.0 | 29/08/2021 | Criação do documento, Introdução | João Victor Valadão |
| 1.0 | 29/08/2021 | Criação dos diagramas | Gabriel e Ítalo |

