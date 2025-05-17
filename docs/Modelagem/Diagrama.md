# Diagrama de Caso de Uso

## Introdução


## Metodologia

<font size="3"><p style="text-align: center">Tabela 1: Participantes</p></font>

<div align="center">

<table>
  <thead>
    <tr>
      <th>Nome</th>
      <th>Data</th>
      <th>Hora</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Danielle Soares </td>
      <td> - </td>
      <td> - </td>
    </tr>
    <tr>
      <td> Eduardo de Pina </td>
      <td> - </td>
      <td> - </td>
    </tr>
    <tr>
      <td> Enzo Emir </td>
      <td> 17/05/2025 </td>
      <td> 02:00 </td>
    </tr>
    <tr>
      <td> Leticia Arisa </td>
      <td> - </td>
      <td> - </td>
    </tr>
    <tr>
      <td> Marcelo Makoto </td>
      <td> - </td>
      <td> - </td>
    </tr>
    <tr>
      <td> Maria Eduarda </td>
      <td> - </td>
      <td> - </td>
    </tr>
    <tr>
      <td> Victor Pontual </td>
      <td> - </td>
      <td> - </td>
    </tr>
  </tbody>
</table>

</div>


<p style="text-align: center; font-size: 16px;">Fonte: <i>Leticia Arisa</i></p>

## Diagrama de Casos de Uso

## Especialização dos Casos de Uso

<font size="3"><p style="text-align: center">Tabela 2: Visualizar Status Comentado do Saque </p></font>


## Caso de Uso 1 (EN02)

| **Elemento**                     | **Descrição** |
|----------------------------------|----------------|
| **Nome do Caso de Uso**          | Visualizar Status Comentado do Saque |
| **Ator Principal**               | Usuário |
| **Atores Secundários**           | Sistema do FGTS, Servidor da Caixa |
| **Objetivo**                     | Permitir que o usuário acompanhe o andamento do processo de saque com status detalhado e comentários explicativos. |
| **Pré-condições**                | - O usuário deve estar autenticado no aplicativo.<br>- Deve existir ao menos um pedido de saque realizado. |
| **Fluxo Principal de Eventos**   | 1. O usuário acessa o aplicativo do FGTS.<br>2. Navega até a seção "Saque".<br>3. Seleciona o pedido de saque ativo.<br>4. O sistema exibe o status atual do saque em formato de linha do tempo.<br>5. Um comentário explicativo é exibido para esclarecer o status atual.<br>6. O sistema atualiza automaticamente o status e o comentário conforme o processo evolui. |
| **Fluxos Alternativos**          | - Usuário seleciona outro pedido de saque para visualização.<br>- O sistema exibe status anterior se o atual não estiver disponível temporariamente.<br> |
| **Exceções**                    | - Falha de conexão com o servidor: o app exibe mensagem de erro e oferece opção de tentar novamente.<br>- Nenhum saque solicitado: o app informa que não há saques ativos para acompanhamento.<br>- Comentário ausente ou genérico: o sistema exibe aviso e oferece link para ajuda ou suporte. |
| **Pós-condições**                | - O usuário visualizou o status atual e o comentário explicativo de seu pedido de saque. |
| **Autor**                       | [Enzo Emir](https://github.com/EnzoEmir) |


<font size="2"><p style="text-align: center"><b>Fonte: <i> [Enzo Emir](https://github.com/EnzoEmir) </i></b></p></font>

<font size="3"><p style="text-align: center">Tabela 3: Visualizar Data Prevista para Liberação de Valores </p></font>

## Caso de Uso 2 (EN03)

| **Elemento**                     | **Descrição** |
|----------------------------------|----------------|
| **Nome do Caso de Uso**          | Visualizar Data Prevista para Liberação de Valores |
| **Ator Principal**               | Usuário |
| **Atores Secundários**           | Sistema do FGTS, Servidor de Notificações |
| **Objetivo**                     | Permitir que o usuário consulte a data estimada para liberação do valor solicitado no saque do FGTS. |
| **Pré-condições**                | - O usuário deve estar autenticado no aplicativo.<br>- Deve existir um pedido de saque com previsão de liberação cadastrada no sistema. |
| **Fluxo Principal de Eventos**   | 1. O usuário acessa o aplicativo do FGTS.<br>2. Navega até a seção "Meus Saques".<br>3. Seleciona o saque em andamento.<br>4. O sistema exibe a data prevista de liberação em destaque.<br>5. Caso a previsão tenha sido alterada, o sistema exibe também o histórico da data anterior e o motivo da alteração. |
| **Fluxos Alternativos**          | - Usuário consulta histórico de alterações na data prevista.<br>- O sistema exibe datas previstas para diferentes etapas do processo.<br>- O usuário opta por receber notificações sobre mudanças nas datas. |
| **Exceções**                    | - A data prevista expirou sem atualização: o sistema exibe aviso e orienta o usuário a buscar atendimento.<br>- Não há previsão cadastrada: o sistema informa a ausência e oferece explicação contextual.<br>- Conexão indisponível: o sistema exibe mensagem de erro e sugere tentar novamente. |
| **Pós-condições**                | - O usuário visualizou a data prevista (ou a ausência dela) com a devida explicação. |
| **Autor**                       | [Enzo Emir](https://github.com/EnzoEmir) |
<font size="2"><p style="text-align: center"><b>Fonte: <i> [Enzo Emir](https://github.com/EnzoEmir) </i></b></p></font>

<font size="3"><p style="text-align: center">Tabela 4: Nome do caso de uso </p></font>

| UC01 | Descrição |
| ----- | ---------- |
| Data da criação |  |
| Rastreabilidade |  |
| Atores |  |
| Ação |  |
| Pré-condições |  |
| Fluxo básico |  |
| Fluxos alternativos |  |
| Fluxo de exceção |  |
| Pós-condições |  |
| Autor | [Maria Eduarda](https://github.com/dudaa28) |

<font size="2"><p style="text-align: center"><b>Fonte: <i> [Maria Eduarda](https://github.com/dudaa28) </i></b></p></font>

<font size="3"><p style="text-align: center">Tabela 5: Nome do caso de uso </p></font>

| UC01 | Descrição |
| ----- | ---------- |
| Data da criação |  |
| Rastreabilidade |  |
| Atores |  |
| Ação |  |
| Pré-condições |  |
| Fluxo básico |  |
| Fluxos alternativos |  |
| Fluxo de exceção |  |
| Pós-condições |  |
| Autor | [Victor Pontual](https://github.com/VictorPontual) |

<font size="2"><p style="text-align: center"><b>Fonte: <i> [Victor Pontual](https://github.com/VictorPontual) </i></b></p></font>

<font size="3"><p style="text-align: center">Tabela 6: Nome do caso de uso </p></font>

| UC01 | Descrição |
| ----- | ---------- |
| Data da criação |  |
| Rastreabilidade |  |
| Atores |  |
| Ação |  |
| Pré-condições |  |
| Fluxo básico |  |
| Fluxos alternativos |  |
| Fluxo de exceção |  |
| Pós-condições |  |
| Autor | [Victor Pontual](https://github.com/VictorPontual) |

<font size="2"><p style="text-align: center"><b>Fonte: <i> [Victor Pontual](https://github.com/VictorPontual) </i></b></p></font>

<font size="3"><p style="text-align: center">Tabela 7: Nome do caso de uso </p></font>

| UC01 | Descrição |
| ----- | ---------- |
| Data da criação |  |
| Rastreabilidade |  |
| Atores |  |
| Ação |  |
| Pré-condições |  |
| Fluxo básico |  |
| Fluxos alternativos |  |
| Fluxo de exceção |  |
| Pós-condições |  |
| Autor | [Danielle Soares](https://github.com/danielle-soaress) |

<font size="2"><p style="text-align: center"><b>Fonte: <i> [Danielle Soares](https://github.com/danielle-soaress)</i></b></p></font>

<font size="3"><p style="text-align: center">Tabela 8: Nome do caso de uso </p></font>

| UC01 | Descrição |
| ----- | ---------- |
| Data da criação |  |
| Rastreabilidade |  |
| Atores |  |
| Ação |  |
| Pré-condições |  |
| Fluxo básico |  |
| Fluxos alternativos |  |
| Fluxo de exceção |  |
| Pós-condições |  |
| Autor | [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa) |

<font size="2"><p style="text-align: center"><b>Fonte: <i> [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa) </i></b></p></font>

<font size="3"><p style="text-align: center">Tabela 9: Nome do caso de uso </p></font>

| UC01 | Descrição |
| ----- | ---------- |
| Data da criação |  |
| Rastreabilidade |  |
| Atores |  |
| Ação |  |
| Pré-condições |  |
| Fluxo básico |  |
| Fluxos alternativos |  |
| Fluxo de exceção |  |
| Pós-condições |  |
| Autor | [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa) |

<font size="2"><p style="text-align: center"><b>Fonte: <i> [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa)</i></b></p></font>

<font size="3"><p style="text-align: center">Tabela 10: Nome do caso de uso </p></font>

| UC01 | Descrição |
| ----- | ---------- |
| Data da criação |  |
| Rastreabilidade |  |
| Atores |  |
| Ação |  |
| Pré-condições |  |
| Fluxo básico |  |
| Fluxos alternativos |  |
| Fluxo de exceção |  |
| Pós-condições |  |
| Autor | [Danielle Soares](https://github.com/danielle-soaress)|

<font size="2"><p style="text-align: center"><b>Fonte: <i> [Danielle Soares](https://github.com/danielle-soaress) </i></b></p></font>

<font size="3"><p style="text-align: center">Tabela 11: Nome do caso de uso </p></font>

| UC01 | Descrição |
| ----- | ---------- |
| Data da criação |  |
| Rastreabilidade |  |
| Atores |  |
| Ação |  |
| Pré-condições |  |
| Fluxo básico |  |
| Fluxos alternativos |  |
| Fluxo de exceção |  |
| Pós-condições |  |
| Autor | [Marcelo Makoto](https://github.com/MM4k)|

<font size="2"><p style="text-align: center"><b>Fonte: <i> [Marcelo Makoto](https://github.com/MM4k) </i></b></p></font>

<font size="3"><p style="text-align: center">Tabela 12: Nome do caso de uso </p></font>

| UC01 | Descrição |
| ----- | ---------- |
| Data da criação |  |
| Rastreabilidade |  |
| Atores |  |
| Ação |  |
| Pré-condições |  |
| Fluxo básico |  |
| Fluxos alternativos |  |
| Fluxo de exceção |  |
| Pós-condições |  |
| Autor | [Marcelo Makoto](https://github.com/MM4k)|

<font size="2"><p style="text-align: center"><b>Fonte: <i> [Marcelo Makoto](https://github.com/MM4k) </i></b></p></font>

<font size="3"><p style="text-align: center">Tabela 13: Nome do caso de uso </p></font>

| UC01 | Descrição |
| ----- | ---------- |
| Data da criação |  |
| Rastreabilidade |  |
| Atores |  |
| Ação |  |
| Pré-condições |  |
| Fluxo básico |  |
| Fluxos alternativos |  |
| Fluxo de exceção |  |
| Pós-condições |  |
| Autor | [Eduardo de Pina](https://github.com/eduardodpms)|

<font size="2"><p style="text-align: center"><b>Fonte: <i> [Eduardo de Pina](https://github.com/eduardodpms) </i></b></p></font>

<font size="3"><p style="text-align: center">Tabela 14: Nome do caso de uso </p></font>

| UC01 | Descrição |
| ----- | ---------- |
| Data da criação |  |
| Rastreabilidade |  |
| Atores |  |
| Ação |  |
| Pré-condições |  |
| Fluxo básico |  |
| Fluxos alternativos |  |
| Fluxo de exceção |  |
| Pós-condições |  |
| Autor | [Eduardo de Pina](https://github.com/eduardodpms)|

<font size="2"><p style="text-align: center"><b>Fonte: <i> [Eduardo de Pina](https://github.com/eduardodpms) </i></b></p></font>

<font size="3"><p style="text-align: center">Tabela 15: Nome do caso de uso </p></font>

| UC01 | Descrição |
| ----- | ---------- |
| Data da criação |  |
| Rastreabilidade |  |
| Atores |  |
| Ação |  |
| Pré-condições |  |
| Fluxo básico |  |
| Fluxos alternativos |  |
| Fluxo de exceção |  |
| Pós-condições |  |
| Autor | [Maria Eduarda](https://github.com/dudaa28) |

<font size="2"><p style="text-align: center"><b>Fonte: <i> [Maria Eduarda](https://github.com/dudaa28) </i></b></p></font>

## Bibliografia


## Histórico de Versão

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| :-: | :-: | :-: | :-: | :-: |
| `1.0` | 16/05/2025 | Criação do documento | [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa) | [Enzo Emir](https://github.com/EnzoEmir)|
| `1.1` | 17/05/2025 | Adição do caso de uso 1 e 2 |  [Enzo Emir](https://github.com/EnzoEmir) |-|