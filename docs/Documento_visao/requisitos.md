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
<table>
    <thead>
        <tr style="border: 1px solid black; border-collapse: collapse;">
            <th > Requisitos</th>
            <th> Épico </th>
            <th> Funcionalidade </th>
            <th> História de usuários </th>
        </tr>
    </thead>
    <tbody style="border: 1px solid black; border-collapse: collapse;">
        <tr>
            <td>RF01</td>
            <td rowspan=5 style="border: 1px solid black; border-collapse: collapse;">Sessão de usuário</td>
            <td rowspan=3 style="border: 1px solid black; border-collapse: collapse;">CRUD de usuário</td>
            <td >Eu como usuário desejo me cadastrar na plataforma.</td>
        </tr>
        <tr>
            <td>RF02</td><td>Eu como usuário desejo editar meus dados.</td>
        </tr>
        <tr>
            <td>RF03</td><td>Eu como usuário desejo ter opção de excluir minha conta.</td>
        </tr>
        <tr>
            <td>RF04</td>
            <td style="border: 1px solid black; border-collapse: collapse;" rowspan=2>Acesso de usuário</td> 
            <td>Eu como usuário desejo poder recuperar minha senha.</td>
        </tr>
        <tr>
            <td>RF05</td><td>Eu como usuário desejo acessar a plataforma com a minha conta.</td>
        </tr>
        <tr>
            <td>RF06</td>
            <td style="border: 1px solid black; border-collapse: collapse;" rowspan=13>Gestão financeira</td>
            <td style="border: 1px solid black; border-collapse: collapse;" rowspan=7>Gerenciamento de gastos</td>
            <td>Eu como usuário desejo cadastrar minha entrada e saída de caixa.</td>
        </tr>
        <tr>
            <td>RF07</td><td>Eu como usuário desejo editar minha entrada e saída de caixa.</td>
        </tr>
        <tr>
            <td>RF08</td><td>Eu como usuário desejo excluir minha entrada e saída de caixa.</td>
        </tr>
        <tr>
            <td>RF09</td><td>Eu como usuário desejo visualizar a listagem de gastos.</td>
        </tr>
        <tr>
            <td>RF10</td><td>Eu como usuário desejo cadastrar cobranças recorrentes.</td>
        </tr>
        <tr>
            <td>RF11</td><td>Eu como usuário desejo editar cobranças recorrentes.</td>
        </tr>
        <tr>
            <td>RF12</td><td>Eu como usuário desejo excluir cobranças recorrentes.</td>
        </tr>
        <tr>
            <td>RF13</td>
            <td style="border: 1px solid black; border-collapse: collapse;" rowspan=6>Planejamento financeiro</td>
            <td>Eu como usuário desejo criar um plano financeiro.</td>
        </tr>
        <tr>
            <td>RF14</td><td>Eu como usuário desejo editar um plano financeiro.</td>
        </tr>
        <tr>
            <td>RF15</td><td>Eu como usuário desejo excluir um plano financeiro.</td>
        </tr>
        <tr>
            <td>RF16</td><td>Eu como usuário desejo adicionar objetivos de compra.</td>
        </tr>    
        <tr>
            <td>RF17</td><td>Eu como usuário desejo editar objetivos de compra.</td>
        </tr>    
        <tr>
            <td>RF18</td><td>Eu como usuário desejo excluir objetivos de compra.</td>
        </tr>    
        <tr>
            <td>RF19</td>
            <td style="border: 1px solid black; border-collapse: collapse;" rowspan=3>Gamificação</td>
            <td style="border: 1px solid black; border-collapse: collapse;" rowspan=3>Gratificação do usuário</td>
            <td>Eu como usuário desejo ser notificado por cumprimento de objetivos.</td>
        </tr>
        <tr>
            <td>RF20</td><td>Eu como usuário desejo ser recompensado por cumprimento de objetivos.</td></tr>
        <tr>
            <td>RF21</td><td>Eu como usuário desejo ser recompensado por manter uma sequência de metas concluídas.</td>
        </tr>
    </tbody>
</table>

## Referências Bibliográficas
* MARSICANO, George. Requisitos de Software: Tipos e Característica de Requisitos. Brasília. 2021. Apresentação em PowerPoint. 36 slides, color, Material de aula do curso de Engenharia de Software da FGA/UNB. Disponível em: https://aprender3.unb.br/pluginfile.php/1624498/mod_resource/content/0/REQ_Aula%202.1%20-%20Introdu%C3%A7%C3%A3o%20a%20ER-atualizado.pdf. Acesso em: 18 fev 2022