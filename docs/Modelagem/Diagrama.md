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
      <td> 17/05/2025 </td>
      <td> 22:50 </td>
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

<font size="3"><p style="text-align: center">Tabela 7: Consultar Saques Bloqueados </p></font>


| **RF11** | **Descrição** |
|---------|----------------|
| **Data da criação** | 17/05/2025 |
| **Rastreabilidade** | IS08 |
| **Atores** | Usuário (Ator Primário), Sistema do FGTS (Ator Secundário) |
| **Ação** | O usuário visualiza seus saques bloqueados e os respectivos motivos. |
| **Pré-condições** | <p>O usuário deve estar autenticado no aplicativo FGTS.</p><p>Deve existir pelo menos um saque bloqueado registrado no sistema.</p> |
| **Fluxo básico** | 1. O usuário acessa o aplicativo FGTS.<br>2. Realiza login com seus dados.<br>3. Navega até a seção “Saques”.<br>4. Seleciona a opção “Saques Bloqueados”.<br>5. O sistema exibe a lista de saques bloqueados com os respectivos motivos. |
| **Fluxos alternativos** | 1. O sistema apresenta mensagem genérica caso o motivo do bloqueio não esteja registrado.<br>2. Não há saques bloqueados: o sistema informa a ausência de registros.<br>3. O usuário solicita mais informações e o sistema oferece um link para ajuda externa. |
| **Fluxo de exceção** | 1. O usuário acessa o aplicativo FGTS<br>2. Realiza login com seus dados.<br>2.1. Conexão com o servidor falhou: o sistema exibe uma mensagem de erro e orienta o usuário a tentar novamente.|
| **Pós-condições** | O usuário visualizou a lista de saques bloqueados (ou a ausência dela) com as devidas explicações. |
| **Autor** | [Danielle Soares](https://github.com/danielle-soaress) |


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

<font size="3"><p style="text-align: center">Tabela 10: Cadastrar Múltiplas Contas Bancárias </p></font>

| **RF35** | **Descrição** |
|---------|----------------|
| **Data da criação** | 17/05/2025 |
| **Rastreabilidade** | IS12 |
| **Atores** | Sistema do FGTS |
| **Ação** | <p>O usuário pode cadastrar uma ou mais contas bancárias de diferentes instituições financeiras.</p> |
| **Pré-condições** | <p>O usuário deve estar autenticado no aplicativo FGTS.</p><p>O usuário deve possuir os dados completos da conta bancária a ser cadastrada.</p> |
| **Fluxo básico** | <p>1. O usuário acessa e loga no aplicativo FGTS.</p><p>2. Navega até a seção “Meus Dados” e seleciona a opção “Conta Bancária”.</p><p>5. Clica em “Cadastrar nova conta bancária”.</p>6. O sistema solicita os dados bancários necessários.</p><p>7. O usuário preenche os campos obrigatórios e confirma o envio.</p><p>8. O sistema valida os dados informados.</p><p>9. A conta é associada ao perfil do usuário.</p>|
| **Fluxos alternativos** | <p>1. O usuário acessa e realiza login no aplicativo FGTS.</p><p>2. Navega até “Meus Dados” e seleciona “Conta Bancária”.</p><p>3. Clica em “Cadastrar nova conta bancária”.</p><p>4. O usuário informa os dados da nova conta e confirma o envio.</p><p>5. O sistema identifica que a conta já está cadastrada.</p><p>6. O sistema exibe uma mensagem informando que a conta já existe e impede duplicação.</p> |
| **Fluxo de exceção** | <p>1. O usuário acessa o aplicativo FGTS e realiza login.</p><p>2. Preenche os dados da conta bancária.</p><p>3. O sistema identifica dados inválidos ou incompletos e exibe mensagem de erro destacando os campos com problema.</p><p>4. Caso ocorra falha de conexão com o servidor, o sistema exibe mensagem informativa e orienta o usuário a tentar novamente mais tarde.</p> |
| **Pós-condições** | <p>O usuário cadastrou com sucesso uma ou mais contas bancárias, ou recebeu uma mensagem com o motivo da falha.</p> |
| **Autor** | [Danielle Soares](https://github.com/danielle-soaress) |

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
| `1.2` | 17/05/2025 | Adição dos casos de uso 10 e 11 | [Marcelo Makoto](https://github.com/MM4k) | - |