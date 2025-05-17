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
      <td> 17/05 </td>
      <td> 14:45 </td>
    </tr>
    <tr>
      <td> Marcelo Makoto </td>
      <td> 17/05/2025 </td>
      <td> 09:37 </td>
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

## Caso de Uso 1 (EN02)

<font size="3"><p style="text-align: center">Tabela 2: Visualizar Status Comentado do Saque </p></font>


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

## Caso de Uso 2 (EN03)

<font size="3"><p style="text-align: center">Tabela 3: Visualizar Data Prevista para Liberação de Valores </p></font>


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

<font size="3"><p style="text-align: center">Tabela 8: Exibir informações detalhadas sobre o histórico de movimentações financeiras </p></font>

| UC07 | Descrição |
| ----- | ---------- |
| Data da criação | 17/05 |
| Rastreabilidade | <a href ="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#requisitos-funcionais">RF12</a> <br> <a href ="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#requisitos-funcionais">IS09</a> |
| Atores | Usuários do aplicativo FGTS |
| Ação | O usuário acessa o histórico de movimentações financeiras e seleciona uma movimentação para visualizar informações detalhadas |
| Pré-condições | O usuário deve estar logado no aplicativo FGTS. <br> O sistema deve possuir movimentações financeiras registradas. |
| Fluxo básico | 1. O usuário efetua o login no FGTS <br> 2. O usuário acessa a página de movimentações financeiras. <br> 3. O sistema exibe a lista de movimentações registradas. <br> 4. O usuário seleciona uma movimentação específica. <br> 5. O sistema exibe as informações detalhadas da movimentação. |
| Fluxos alternativos | 1. O usuário efetua o login no FGTS. <br> 2. O usuário acessa a página de movimentações financeiras. <br> 3. O usuário usa o filtro para selecionar o mês e o ano. <br> O sistema exibe as movimentações financeiras do período selecionado. |
| Fluxo de exceção | 1. O usuário efetua o login no FGTS. <br> 2. O usuário acessa a página de movimentações financeiras. <br> 3. O sistema não encontra nenhuma movimentação financeira. <br> 4. O sistema exibe uma mensagem indicando o problema. |
| Pós-condições | O sistema exibe corretamente as informações detalhadas da movimentação selecionada. |
| Autor | [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa) |

<font size="2"><p style="text-align: center"><b>Fonte: <i> [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa) </i></b></p></font>

<font size="3"><p style="text-align: center">Tabela 9: Filtrar extrato por data </p></font>

| UC08 | Descrição |
| ----- | ---------- |
| Data da criação | 17/05 |
| Rastreabilidade | <a href ="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#requisitos-funcionais">RF13</a> <br> <a href ="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#requisitos-funcionais">IS10</a> |
| Atores | Usuários do aplicativo FGTS |
| Ação | O usuário filtra as movimentações financeiras exibidas no histórico de movimentações financeiras com base no mês e no ano |
| Pré-condições | O usuário deve estar logado no aplicativo FGTS. <br> O sistema deve possuir movimentações financeiras com diferentes datas registradas.  |
| Fluxo básico | 1. O usuário efetua o login no FGTS <br> 2. O usuário acessa a página de movimentações financeiras. <br> 3. O sistema exibe a lista de movimentações registradas. <br> 4. O usuário seleciona uma data (mês e ano) como filtro <br> 5. O sistema exibe apenas as movimentações correspondentes à data selecionada. |
| Fluxos alternativos | 1. O usuário efetua o login no FGTS <br> 2. O usuário acessa a página de movimentações financeiras. <br> 3. O sistema exibe uma lista com todas as movimentações registradas.  |
| Fluxo de exceção | 1. O usuário efetua o login no FGTS <br> 2. O usuário acessa a página de movimentações financeiras. <br> 3. O sistema exibe a lista de movimentações registradas. <br> 4. O usuário seleciona uma data (mês e ano) inválida ou sem movimentações <br> 5. O sistema exibe uma mensagem indicando o problema. |
| Pós-condições | O sistema exibe o histórico de movimentações financeiras filtrado de acordo com a data selecionada. |
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

## Caso de Uso 10 (IS13)

<font size="3"><p style="text-align: center">Tabela 11: Contato com Assistente via Chat </p></font>

| **Elemento**                     | **Descrição** |
|----------------------------------|----------------|
| **Nome do Caso de Uso**          | Contato com Assistente via Chat |
| **Ator Principal**               | Usuário |
| **Atores Secundários**           | Sistema do FGTS, Assistente Virtual |
| **Objetivo**                     | Permitir que o usuário entre em contato com um assistente via chat para tirar dúvidas ou obter suporte relacionado ao FGTS. |
| **Pré-condições**                | - O usuário deve estar autenticado no aplicativo.<br>- A funcionalidade de chat deve estar disponível e operacional. |
| **Fluxo Principal de Eventos**   | 1. O usuário acessa o aplicativo do FGTS.<br>2. Seleciona a opção de "Ajuda" ou "Suporte".<br>3. O sistema exibe a interface do chat.<br>4. O usuário digita sua dúvida.<br>5. O assistente responde com orientações baseadas no contexto da solicitação.<br>6. O usuário continua a conversa ou encerra o atendimento. |
| **Fluxos Alternativos**          | - O usuário acessa o chat por meio de outro ponto do aplicativo (ex: ao visualizar um status de saque).<br>- O assistente direciona o usuário para funcionalidades específicas com base na dúvida.<br> |
| **Exceções**                    | - Falha de conexão com o servidor: o app exibe mensagem de erro e oferece opção de tentar novamente.<br>- Módulo de chat indisponível: o app exibe alternativa de contato por outros canais.<br>- Dúvida não compreendida: o assistente oferece opções adicionais ou redireciona para atendimento humano. |
| **Pós-condições**                | - O usuário recebeu suporte via chat e teve sua dúvida resolvida ou foi orientado sobre próximos passos. |
| Autor | [Marcelo Makoto](https://github.com/MM4k)|

<font size="2"><p style="text-align: center"><b>Fonte: <i> [Marcelo Makoto](https://github.com/MM4k) </i></b></p></font>

## Caso de Uso 11 (IS14)

<font size="3"><p style="text-align: center">Tabela 12: Busca de Funcionalidades e Informações </p></font>

| **Elemento**                     | **Descrição** |
|----------------------------------|----------------|
| **Nome do Caso de Uso**          | Busca de Funcionalidades e Informações |
| **Ator Principal**               | Usuário |
| **Atores Secundários**           | Sistema do FGTS |
| **Objetivo**                     | Permitir que o usuário localize rapidamente funcionalidades ou informações no aplicativo por meio de um campo de busca. |
| **Pré-condições**                | - O usuário deve estar autenticado no aplicativo.<br>- O mecanismo de busca deve estar ativo e sincronizado com o conteúdo do sistema. |
| **Fluxo Principal de Eventos**   | 1. O usuário acessa o aplicativo do FGTS.<br>2. Digita um termo no campo de busca.<br>3. O sistema processa a consulta e exibe resultados relevantes.<br>4. O usuário seleciona uma funcionalidade ou informação listada.<br>5. O sistema redireciona o usuário para a área ou funcionalidade escolhida. |
| **Fluxos Alternativos**          | - O usuário limpa o campo de busca para iniciar nova consulta.<br>- O sistema sugere termos relacionados para ampliar a busca.<br> |
| **Exceções**                    | - Termo pesquisado não retorna resultados: o sistema informa que não foram encontrados itens correspondentes.<br>- Falha na comunicação com o servidor de busca: o app exibe mensagem de erro e permite nova tentativa. |
| **Pós-condições**                | - O usuário localizou e acessou a funcionalidade ou informação desejada via busca. |
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
| `1.1` | 17/05/2025 | Adição do caso de uso 1 e 2 |  [Enzo Emir](https://github.com/EnzoEmir) | [Marcelo Makoto](https://github.com/MM4k) |
| `1.2` | 17/05/2025 | Adição dos casos de uso 10 e 11 | [Marcelo Makoto](https://github.com/MM4k) | [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa) |
| `1.3` | 17/05/2025 | Adição dos casos de uso 07 e 08 | [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa) | - |