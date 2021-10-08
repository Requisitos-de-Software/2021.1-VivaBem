## <a>Introdução</a>

<p style="text-indent: 20px; text-align: justify">
A pré-rastreabilidade, Como visto em entregas passadas, documenta a o contexto a partir do qual emergem os requisitos, 
já a pós-rastreabilidade, que estamos abordando nesta entrega, vincula os requisitos ao desenho do sistema e sua 
implementação. No primeiro tipo temos a rastrebilidade forward-to (para frente) liga documentos obtidos no processo 
de elicitação a requisitos relevantes. Será abordado ao longo deste documento as caracteristicas assim como será
feito a rastreabilidade do tipo forward-to no nosso projeto.
</p>

## <a>Metodologia</a>


## <a>Forward-Form</a>

### <a>Matriz de Requisitos Funcionais</a>


| Id | Requisito | Cenários | Léxicos | Casos de Uso | Histórias de Usuários |
|--|--|--|--|--|--|
| 01 | Autenticar usuário | | [L03 - Autenticar usuário](./../Modelagem/lexicos.md#l03-Autenticar-usuário) | | |
| 02 | Confirmar dados para autenticação | | | | |
| 03 | Alterar Senha | [C10 - Trocar senha](./../Modelagem/cenarios.md#c10-Trocar-senha) | | | [US05 - Alterar a senha](./../Modelagem/BacklogDoProduto/HistoriasDeUsuario/epico01.md#us05-Alterar-a-senha) |
| 04 | Aceitar termo de uso | [C09 - Termos de uso do aplicativo](./../Modelagem/cenarios.md#c09-Termos-de-uso-do-aplicativo) | | | [US29 - Visualizar os termos de uso](./../Modelagem/BacklogDoProduto/HistoriasDeUsuario/epico06.md#us29-Visualizar-os-termos-de-uso) |
| 05 | Recuperar senha | | | | [US04 - Recuperar a senha](./../Modelagem/BacklogDoProduto/HistoriasDeUsuario/epico01.md#us04-Recuperar-a-senha) |
| 06 | Adicionar sintoma no diário | | [L14 - Registrar sintoma](./../Modelagem/lexicos.md#l14-Registrar-sintoma) | | |
| 07 | Registrar efeito colateral | [C07 - Registrar efeitos colaterais](./../Modelagem/cenarios.md#c07-Registrar-efeitos-colaterais) | [L06 - Efeito colateral](./../Modelagem/lexicos.md#l06-Efeito-colateral) | | [US08 - Registrar efeito colateral](./../Modelagem/BacklogDoProduto/HistoriasDeUsuario/epico02.md#us08-Registrar-efeito-colateral) |
| 08 | Visualizar lista de compromissos do dia | | | | [US09 - Visualizar lista de compromissos do dia](./../Modelagem/BacklogDoProduto/HistoriasDeUsuario/epico02.md#us09-Visualizar-lista-de-compromissos-do-dia) |
| 09 | Registrar evento | | [L17 - Visualizar eventos](./../Modelagem/lexicos.md#l17-Visualizar-eventos) | | [US10 - Registrar evento](./../Modelagem/BacklogDoProduto/HistoriasDeUsuario/epico02.md#us10-Registrar-evento) |
| 10 | Editar ou excluir evento | | [L17 - Visualizar eventos](./../Modelagem/lexicos.md#l17-Visualizar-eventos) | | [US11 - Editar ou Excluir evento](./../Modelagem/BacklogDoProduto/HistoriasDeUsuario/epico02.md#us11-Editar-ou-Excluir-evento) |
| 11 | Visualizar calendário | [C04 - Diário do usuário](./../Modelagem/cenarios.md#c04-Diário-do-usuário) | [L04 - Calendário](./../Modelagem/lexicos.md#l04-Calendário) | | [US12 - Visualizar calendário](./../Modelagem/BacklogDoProduto/HistoriasDeUsuario/epico02.md#us12-Visualizar-calendário) |
| 12 | Sugerir próximos exames | | | | [US31 - Verificar exames sugeridos](./../Modelagem/BacklogDoProduto/HistoriasDeUsuario/epico07.md#us31-Verificar-exames-sugeridos) |
| 13 | Adicionar lembrete de medicamento acabando | | [L12 - Medicamento](./../Modelagem/lexicos.md#l12-Medicamento) | | |
| 14 | Visualizar lista de informação, PCDT e dicas | | [L18 - Visualizar informações](./../Modelagem/lexicos.md#l18-Visualizar-informações) | | [US32 - Lista de informação, PCDT e dicas](./../Modelagem/BacklogDoProduto/HistoriasDeUsuario/epico07.md#us32-Lista-de-informação-PCDT-e-dicas) |
| 15 | Consultar lista de medicamentos | | [L08 - Lista de Medicamentos](./../Modelagem/lexicos.md#l08-Lista-de-Medicamentos) | [Cadastrar medicação](./../Modelagem/casos_de_uso.md#Cadastrar-medicação) | [US15 - Consultar a lista de medicamentos](./../Modelagem/BacklogDoProduto/HistoriasDeUsuario/epico03.md#us15-Consultar-a-lista-de-medicamentos) |
| 16 | Adicionar medicamento para lembrete | [C02 - Realizar cadastro de um medicamento](./../Modelagem/cenarios.md#c02-Realizar-cadastro-de-um-medicamento) | [L01 - Adicionar Medicamento](./../Modelagem/lexicos.md#l01-Adicionar-Medicamento) | | [US13 - Realizar o cadastro de uma medicação](./../Modelagem/BacklogDoProduto/HistoriasDeUsuario/epico03.md#us13-Realizar-o-cadastro-de-uma-medicação) |
| 17 | Sugerir lista do SICLOM na pesquisa do remédio | | | | |
| 18 | Visualizar gráfico de desempenho do uso do medicamento | | [L12 - Medicamento](./../Modelagem/lexicos.md#l12-Medicamento) | | |
| 19 | Consultar gráfico Carga Viral | | | | |
| 20 | Visualizar resultado do laudo | | [L15 - Resultado](./../Modelagem/lexicos.md#l15-Resultado) | | |
| 21 | Visualizar dados do usuário | | [L05 - Dados do usuário](./../Modelagem/lexicos.md#l05-Dados-do-usuário) | | |
| 22 | Receber notificações/avisos | | [L11 - Notificar](./../Modelagem/lexicos.md#l11-Notificar) | [Acessar notificações](./../Modelagem/casos_de_uso.md#Acessar-notificações) | [US17 - Receber notificação](./../Modelagem/BacklogDoProduto/HistoriasDeUsuario/epico04.md#us17-Receber-notificação) |
| 23 | Habilitar/Desabilitar recebimento de notificações | [C05 - Acessar Notificações](./../Modelagem/cenarios.md#c05-Acessar-Notificações) | | | [US18 - Habilitar/desabilitar recebimento de notificações](./../Modelagem/BacklogDoProduto/HistoriasDeUsuario/epico04.md#us18-Habilitar-desabilitar-recebimento-de-notificações) |
| 24 | Gerenciar função "soneca" | | | | [US19 - Função "soneca"](./../Modelagem/BacklogDoProduto/HistoriasDeUsuario/epico04.md#us19-Função-soneca) |
| 25 | Manter informações de emergência | | | | |
| 26 | Deslogar do aplicativo | | | | |
| 27 | Aceitar, recusar ou adiar alerta de medicação | | | | [US16 - Aceitar, recusar ou adiar o alerta de uma medicação](./../Modelagem/BacklogDoProduto/HistoriasDeUsuario/epico03.md#us16-Aceitar-recusar-ou-adiar-o-alerta-de-uma-medicação) |
| 28 | Receber push com alarme do medicamento | | | | [US20 - Receber push com alarme do medicamento](./../Modelagem/BacklogDoProduto/HistoriasDeUsuario/epico04.md#us20-Receber-push-com-alarme-do-medicamento) |
| 29 | Confirmar realização de exame, consulta ou compromissos | [C03: Realizar cadastro de um exame](./../Modelagem/cenarios.md#c03-Realizar-cadastro-de-um-exame) | [L09 - Marcar consulta](./../Modelagem/lexicos.md#l09-Marcar-consulta) | [Cadastrar exame](./../Modelagem/casos_de_uso.md#Cadastrar-exame) | [US24 - Confirmar realização de exame, consulta ou compromissos](./../Modelagem/BacklogDoProduto/HistoriasDeUsuario/epico05.md#us24-Confirmar-realização-de-exame-consulta-ou-compromissos) |
| 30 | Cadastrar resultado de exames específicos | | [L02 - Adicionar resultados](./../Modelagem/lexicos.md#l02-Adicionar-resultados) | | |
| 31 | Cadastrar resultado de exames gerais | | [L02 - Adicionar resultados](./../Modelagem/lexicos.md#l02-Adicionar-resultados) | | [US21-Realizar-o-cadastro-de-um-exame](./../Modelagem/BacklogDoProduto/HistoriasDeUsuario/epico05.md#us21-Realizar-o-cadastro-de-um-exame) |
| 32 | Consultar resultados de exames | | [L02 - Adicionar resultados](./../Modelagem/lexicos.md#l02-Adicionar-resultados) | | |
| 33 | Consultar histórico de dispensação | | | | [US33 - Histórico de dispensação](./../Modelagem/BacklogDoProduto/HistoriasDeUsuario/epico07.md#us33-Histórico-de-dispensação) |
| 34 | Responder questionário | | | | [US34 - Questionário](./../Modelagem/BacklogDoProduto/HistoriasDeUsuario/epico07.md#us34-Questionário) |

### <a>Matriz de Requisitos Não Funcionais</a>


## <a>Referências</a>

* LSAYÃO, Miriam; DO PRADO LEITE, Julio Cesar Sampaio. Rastreabilidade de requisitos. RITA, v. 13, n. 1, p. 57-86, 2006. Disponível em: <http://www-di.inf.puc-rio.br/~julio/rastreabilidade5.pdf> . Acesso em: 07 de outubro de 2021.

## <a>Versionamento</a>

| Versão | Data | Modificação | Autor |
|--|--|--|--|
| 1.0 | 07/10/2021 | Criação do documento na WIKI | Nathan Fernandes e Philipe Serafim |