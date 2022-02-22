# Lista de requisitos

## Histórico de Versões
|Data|Versão|Modificação|Autores|
|:---|:-----|:----------|:------|
|14/02/2022|0.1|Criação do documento |Henrique Hida, Felipe Agustini|
|21/02/2022|0.2|Adição dos requisitos no padrão SAFe|Henrique Hida, Felipe Agustini, Christian Fleury|

## Requisitos Funcionais
| Requisito |Descrição|
|:---|:-----|
| RF01 | Permitir criação de usuário  |
| RF02 | Permitir edição de dados do usuário |
| RF03 | Permitir exclusão de usuário  |
| RF04 | Permitir recuperação de conta  |
| RF05 | Permitir autenticação de usuário|
| RF06 | Permitir o cadastro de entrada e saída de caixa. |
| RF07 | Permitir a edição de entrada e saída de caixa. |
| RF08 | Permitir a exclusão de entrada e saída de caixa.|
| RF09 | Permitir visualização da listagem de gastos|
| RF10 | Permitir criação de cobranças recorrentes |
| RF11 | Permitir edição de cobranças recorrentes |
| RF12 | Permitir exclusão de cobranças recorrentes |
| RF13 | Permitir criação de um plano financeiro. |
| RF14 | Permitir edição de um plano financeiro. |
| RF15 | Permitir exclusão de um plano financeiro. |
| RF16 | Permitir a criação de objetivos a serem atingidos|
| RF17 | Permitir a edição de objetivos a serem atingidos|
| RF18 | Permitir a exclusão de objetivos a serem atingidos|
| RF19 | Notificar o usuário por cumprimento de objetivos|
| RF20 | Recompensar o usuário por cumprimento de objetivos|
| RF21 | Recompensar o usuário por manter uma sequência de metas|

## Requisitos Não-funcionais 
### Requisitos de implementação
| Requisito |Descrição|
|:---|:-----|
| RNF1 | O front-end será desenvolvido em react  |
| RNF2 | O back-end deve ser desenvolvido em node.js, adonisJS e typescript|
| RNF3 | O back-end deve ser uma API Rest|
| RNF4 | O banco de dados deve ser o PostgreSQL |
| RNF5 | A gamificação utilizará o framework Octalize|

### Requisitos de segurança
| Requisito |Descrição|
|:---|:-----|
| RNF6 | Deve ter segurança no armazenamento das informações do usuário  |

### Requisitos de Usabilidade 
| Requisito |Descrição|
|:---|:-----|
| RNF7 | O layout do sistema deve ser em português  |

## Requisitos no padrão SAFe
| Requisitos  | Épico | Funcionalidade | História de usuários |
|:---|:-----|:-----|:-----|
|RF01 |Sessão de usuário| CRUD de usuário | Eu como usuário desejo me cadastrar na plataforma.|
|RF02|Sessão de usuário | CRUD de usuário | Eu como usuário desejo editar meus dados.|
|RF03|Sessão de usuário | CRUD de usuário | Eu como usuário desejo ter opção de excluir minha conta.|
|RF04|Sessão de usuário | Acesso de usuário | Eu como usuário desejo poder recuperar minha senha.|
|RF05|Sessão de usuário | Acesso de usuário | Eu como usuário desejo acessar a plataforma com a minha conta.|
|RF06| Gestão financeira | Gerenciamento de gastos | Eu como usuário desejo cadastrar minha entrada e saída de caixa. |
|RF07 | Gestão financeira| Gerenciamento de gastos | Eu como usuário desejo editar minha entrada e saída de caixa.|
|RF08 | Gestão financeira| Gerenciamento de gastos | Eu como usuário desejo excluir minha entrada e saída de caixa.|
|RF09 | Gestão financeira| Gerenciamento de gastos | Eu como usuário desejo visualizar a listagem de gastos.|
|RF10| Gestão financeira| Gerenciamento de gastos | Eu como usuário desejo cadastrar cobranças recorrentes.|
|RF11 | Gestão financeira| Gerenciamento de gastos | Eu como usuário desejo editar cobranças recorrentes.|
|RF12 | Gestão financeira| Gerenciamento de gastos | Eu como usuário desejo excluir cobranças recorrentes.|
|RF13 | Gestão financeira | Planejamento financeiro | Eu como usuário desejo criar um plano financeiro.|
|RF14 | Gestão financeira| Planejamento financeiro | Eu como usuário desejo editar um plano financeiro.|
|RF15 | Gestão financeira| Planejamento financeiro | Eu como usuário desejo excluir um plano financeiro.|
|RF16 | Gestão financeira| Planejamento financeiro | Eu como usuário desejo adicionar objetivos de compra.|
|RF17 | Gestão financeira| Planejamento financeiro | Eu como usuário desejo editar objetivos de compra.|
|RF18 | Gestão financeira| Planejamento financeiro | Eu como usuário desejo excluir objetivos de compra.|
|RF19 | Gamificação | Gratificação do usuário  | Eu como usuário desejo ser notificado por cumprimento de objetivos.|
|RF20 | Gamificação | Gratificação do usuário  | Eu como usuário desejo ser recompensado por cumprimento de objetivos.|
|RF21 | Gamificação | Gratificação do usuário | Eu como usuário desejo ser recompensado por manter uma sequência de metas concluídas.|

## Referências Bibliográficas
* MARSICANO, George. Requisitos de Software: Tipos e Característica de Requisitos. Brasília. 2021. Apresentação em PowerPoint. 36 slides, color, Material de aula do curso de Engenharia de Software da FGA/UNB. Disponível em: https://aprender3.unb.br/pluginfile.php/1624498/mod_resource/content/0/REQ_Aula%202.1%20-%20Introdu%C3%A7%C3%A3o%20a%20ER-atualizado.pdf. Acesso em: 18 fev 2022