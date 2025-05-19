# Diagrama de Caso de Uso

## Introdução

O Diagrama de Casos de Uso representa, de forma clara e objetiva, as funcionalidades essenciais do aplicativo **FTGS**, a partir da interação entre o sistema e seus usuários.

Utilizando a notação UML, este diagrama comportamental identifica os **Atores** (usuários ou sistemas externos) e os **Casos de Uso** (ações que geram valor para o usuário), mostrando como o aplicativo deve se comportar para atender às suas necessidades.

No caso do FTGS, o foco está em mapear quem utiliza o sistema e quais ações podem realizar, como acessar funcionalidades, enviar informações ou visualizar conteúdos.

Quando necessário, cada caso de uso pode ser detalhado em uma **Especificação de Casos de Uso**, para descrever o fluxo completo da funcionalidade.


## Metodologia

Todo o processo de elaboração do Diagrama de Casos de Uso do aplicativo **FTGS** está sendo desenvolvido pelos próprios membros da equipe, com base nos conceitos discutidos em sala de aula e nos materiais disponibilizados pelo professor.

A ferramenta utilizada para construção do diagrama foi o [diagrams.net](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwj84t78ka6NAxVgrJUCHeWABk4QFnoECAwQAQ&url=https%3A%2F%2Fapp.diagrams.net%2F&usg=AOvVaw28S23h4_WI8toant9FYDpi&opi=89978449) <a id="anchor_1" href="#REF2">(2)</a>, escolhida por sua facilidade de uso e clareza na apresentação visual. Além disso, o modelo segue as diretrizes da **Notação UML** <a id="anchor_1" href="#REF1">(1)</a> , conforme exemplificado nos slides do professor.

O diagrama passou por uma validação inicial junto ao cliente (a definir), garantindo que as funcionalidades levantadas estejam alinhadas com as necessidades esperadas.

Abaixo, segue a tabela com os membros participantes do processo de construção do trabalho:

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
      <td> 18/05/2025 </td>
      <td> 10:57 </td>
    </tr>
    <tr>
      <td> Enzo Emir </td>
      <td> 17/05/2025 </td>
      <td> 02:00 </td>
    </tr>
    <tr>
      <td> Leticia Arisa </td>
      <td> 17/05/2025 </td>
      <td> 14:45 </td>
    </tr>
    <tr>
      <td> Marcelo Makoto </td>
      <td> 17/05/2025 </td>
      <td> 09:37 </td>
    </tr>
    <tr>
      <td> Maria Eduarda </td>
      <td> 18/05/2025 </td>
      <td> 17:00 </td>
    </tr>
    <tr>
      <td> Victor Pontual </td>
      <td> 17/05/2025 </td>
      <td> 17:00 </td>
    </tr>
  </tbody>
</table>

</div>


<p style="text-align: center; font-size: 16px;">Fonte: <i>Leticia Arisa</i></p>

## Diagramas de Casos de Uso

<font size="3"><p style="text-align: center">Figura 1: Diagrama de Casos de uso do App FGTS - Requisitos Implementados</p></font>

![Diagrama](./../assets/diagramas/implementado.png)

<font size="2"><p style="text-align: center">Fonte: [Danielle Soares](https://github.com/danielle-soaress) e [Enzo Emir](https://github.com/EnzoEmir), 2025.</p></font>

<br>

<font size="3"><p style="text-align: center">Figura 1: Diagrama de Casos de uso do App FGTS - Requisitos Não Implementados</p></font>

![Diagrama](./../assets/diagramas/nao_implementado.png)

<font size="2"><p style="text-align: center">Fonte: [Danielle Soares](https://github.com/danielle-soaress) e [Enzo Emir](https://github.com/EnzoEmir), 2025.</p></font>



### Descrição

No contexto do aplicativo **FGTS**, o Diagrama de Casos de Uso é uma ferramenta visual que mostra como os usuários interagem com o sistema e quais funcionalidades o aplicativo deve oferecer.

Esse tipo de diagrama é importante porque permite entender, de forma clara e rápida, o que o usuário pode fazer no aplicativo, facilitando o planejamento, o desenvolvimento e a comunicação entre a equipe e o cliente.

### Atores

Atores são os usuários ou sistemas que interagem com o aplicativo **FGTS**. Um ator pode ser uma pessoa, uma organização ou até mesmo um sistema externo que se conecta ao aplicativo para realizar ou receber alguma ação.

No caso do aplicativo FGTS, os atores representam os elementos externos que produzem ou consomem dados do sistema. São eles que iniciam os casos de uso, como consultar saldo, solicitar saque ou atualizar informações. Segue um exemplo:

#### Usuário
Ator principal que representa o trabalhador com conta vinculada ao FGTS. Ele:

- Consulta o saldo disponível em sua conta do FGTS.
- Visualiza o extrato detalhado das movimentações.
- Solicita saques, quando permitido pelas regras do fundo.
- Atualiza informações cadastrais como endereço e dados bancários.


#### Sistema da Caixa Econômica Federal
Ator secundário representando um sistema externo. Ele:

- Valida os dados de acesso e autenticação do usuário.
- Atualiza em tempo real as informações de saldo e extrato.
- Autoriza ou recusa solicitações de saque, conforme regras do FGTS.
- Envia informações ao aplicativo com base em eventos relevantes (ex: novo depósito, liberação de saque).


## Especificação dos Casos de Uso

Esta seção apresenta a especificação dos principais casos de uso relacionados ao aplicativo **FGTS**. O objetivo é descrever, de forma detalhada, como cada funcionalidade deve se comportar, considerando as interações entre os atores (usuário, sistema da Caixa e administrador) e o sistema.

As especificações foram elaboradas com base nos requisitos funcionais ainda não implementados, identificados durante a análise do sistema. Cada integrante da equipe foi responsável por desenvolver as descrições de acordo com os critérios discutidos em grupo e orientados pelo material da disciplina.

As informações estão organizadas em campos como **Nome**, **Descrição**, **Atores**, **Pré-Condições**, **Pós-Condições**, além dos **Fluxos Principal, Alternativo e de Exceção**, seguindo a estrutura padrão da UML <a id="anchor_1" href="#REF1">(1)</a> para casos de uso.


## Caso de Uso 1 (EN02)

<font size="3"><p style="text-align: center">Tabela 2: Visualizar Status Comentado do Saque </p></font>


| **Elemento**                     | **Descrição** |
|----------------------------------|----------------|
| **Nome do Caso de Uso**          | Visualizar Status Comentado do Saque |
| **Rastreabilidade** | [EN02](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Entrevista/#requisitos-funcionais) |
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
| **Rastreabilidade** | [EN03](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Entrevista/#requisitos-funcionais) |
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

## Caso de Uso 3 (EN04)

<font size="3"><p style="text-align: center">Tabela 4: Acessar Suporte via Chatbot </p></font>

| **Elemento**                     | **Descrição** |
|---------------------------------|---------------|
| **Nome do Caso de Uso**          | Acessar Suporte via Chatbot |
| **Rastreabilidade** | [EN04](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Entrevista/#requisitos-funcionais) |
| **Ator Principal**               | Usuário |
| **Atores Secundários**           | Sistema FGTS, Serviço de Chatbot |
| **Objetivo**                    | Permitir que o usuário utilize um canal de suporte automatizado (chatbot) para esclarecer dúvidas sobre o aplicativo e serviços do FGTS. |
| **Pré-condições**               | • Usuário deve estar autenticado no aplicativo.<br>• Serviço de chatbot disponível e operacional. |
| **Fluxo Principal de Eventos**  | 1. Usuário acessa a seção “Suporte” no aplicativo.<br>2. O sistema exibe a interface do chatbot.<br>3. Usuário digita ou seleciona uma dúvida.<br>4. Chatbot processa e retorna resposta.<br>5. Usuário pode continuar a conversa ou encerrar. |
| **Fluxos Alternativos**         | - Usuário opta por enviar dúvida para atendimento humano.<br>- Sistema registra solicitação e informa prazo de resposta. |
| **Exceções**                   | • Chatbot indisponível:<br>- Sistema exibe mensagem de erro.<br>- Sugere canais alternativos (telefone, e-mail).<br>• Falha na conexão:<br>- Sistema informa erro e solicita nova tentativa. |
| **Pós-condições**               | • Usuário recebeu resposta ou encaminhamento da dúvida.<br>• Interação registrada para análise futura. |
| **Autor**                      | [Maria Eduarda](https://github.com/dudaa28) |

<font size="2"><p style="text-align: center"><b>Fonte: <i> [Maria Eduarda](https://github.com/dudaa28) </i></b></p></font>



## Caso de Uso 4 (IS06)

<font size="3"><p style="text-align: center">Tabela 5: Cancelar Solicitação de Saque </p></font>

| **Elemento**                     | **Descrição** |
|----------------------------------|----------------|
| **Nome do Caso de Uso**          | Cancelar Solicitação de Saque |
| **Rastreabilidade** | [IS06](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/) |
| **Ator Principal**               | Usuário |
| **Atores Secundários**           | Sistema do FGTS |
| **Objetivo**                     | Permitir que o usuário cancele uma solicitação de saque feita anteriormente no aplicativo FGTS.|
| **Pré-condições**                | - O usuário deve estar autenticado no aplicativo.<br>- Deve existir um pedido de saque ativo que possa ser cancelado. |
| **Fluxo Principal de Eventos**   | 1. O usuário acessa o aplicativo do FGTS.<br>2. Navega até a seção "Meus Saques".<br>3. Seleciona o saque que deseja cancelar.<br>4. Clica na opção “Cancelar solicitação”.<br>5. O sistema solicita confirmação do cancelamento.<br>6. O usuário confirma.<br>7. O sistema processa o cancelamento e atualiza o status do saque.<br>8. O sistema notifica o usuário sobre o sucesso da operação. |
| **Fluxos Alternativos**          | - O usuário decide não confirmar o cancelamento.<br>- O sistema exibe mensagem caso o saque não possa ser cancelado. |
| **Exceções**                    | - Tentativa de cancelar saque já processado: sistema bloqueia a ação.<br>- Falha de conexão ou erro interno: sistema exibe mensagem de erro. |
| **Pós-condições**                | - O pedido de saque foi cancelado ou a operação foi abortada pelo usuário. |
| **Autor**                       | [Victor Pontual](https://github.com/VictorPontual) |

<font size="2"><p style="text-align: center"><b>Fonte: <i> [Victor Pontual](https://github.com/VictorPontual) </i></b></p></font>

## Caso de Uso 5 (IS07)

<font size="3"><p style="text-align: center">Tabela 6: Filtrar Saques por Tipo </p></font>

| **Elemento**                     | **Descrição** |
|----------------------------------|----------------|
| **Nome do Caso de Uso**          | Filtrar Saques por Tipo |
| **Rastreabilidade** | [IS07](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/) |
| **Ator Principal**               | Usuário |
| **Atores Secundários**           | Sistema do FGTS |
| **Objetivo**                     | Permitir que o usuário filtre a lista de solicitações de saque por tipo (ex: aniversário, doença, falecimento) para facilitar a consulta. |
| **Pré-condições**                | - O usuário deve estar autenticado no aplicativo.<br>- O sistema deve possuir registros de saques com tipos definidos. |
| **Fluxo Principal de Eventos**   |1. O usuário acessa o aplicativo do FGTS.<br>2. Navega até a seção "Histórico de Saques".<br>3. Clica na opção de filtro.<br>4. Seleciona o tipo de saque desejado.<br>5. O sistema exibe os saques filtrados conforme a seleção.<br>6. O usuário visualiza e pode acessar detalhes dos saques filtrados. |
| **Fluxos Alternativos**          | - O usuário remove o filtro para visualizar todos os saques.<br>- O sistema informa caso não existam saques do tipo selecionado. |
| **Exceções**                    | - Falha de conexão: o sistema exibe mensagem de erro.<br>- Erro na aplicação do filtro: o sistema solicita nova tentativa. |
| **Pós-condições**                | - O usuário visualizou a lista de saques filtrada por tipo. |
| **Autor**                       | [Victor Pontual](https://github.com/VictorPontual) |


<font size="2"><p style="text-align: center"><b>Fonte: <i> [Victor Pontual](https://github.com/VictorPontual) </i></b></p></font>

## Caso de Uso 6 (IS08)

<font size="3"><p style="text-align: center">Tabela 7: Consultar Saques Bloqueados </p></font>


| **RF11** | **Descrição** |
|---------|----------------|
| **Nome do Caso de Uso**          | Consultar Saques Bloqueados |
| **Rastreabilidade** | [IS08](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/) |
| **Atores** | Usuário (Ator Primário), Sistema do FGTS (Ator Secundário) |
| **Ação** | O usuário visualiza seus saques bloqueados e os respectivos motivos. |
| **Pré-condições** | <p>O usuário deve estar autenticado no aplicativo FGTS.</p><p>Deve existir pelo menos um saque bloqueado registrado no sistema.</p> |
| **Fluxo básico** | 1. O usuário acessa o aplicativo FGTS.<br>2. Realiza login com seus dados.<br>3. Navega até a seção “Saques”.<br>4. Seleciona a opção “Saques Bloqueados”.<br>5. O sistema exibe a lista de saques bloqueados com os respectivos motivos. |
| **Fluxos alternativos** | 1. O sistema apresenta mensagem genérica caso o motivo do bloqueio não esteja registrado.<br>2. Não há saques bloqueados: o sistema informa a ausência de registros.<br>3. O usuário solicita mais informações e o sistema oferece um link para ajuda externa. |
| **Exceções** | 1. O usuário acessa o aplicativo FGTS<br>2. Realiza login com seus dados.<br>2.1. Conexão com o servidor falhou: o sistema exibe uma mensagem de erro e orienta o usuário a tentar novamente.|
| **Pós-condições** | O usuário visualizou a lista de saques bloqueados (ou a ausência dela) com as devidas explicações. |
| **Autor** | [Danielle Soares](https://github.com/danielle-soaress) |


<font size="2"><p style="text-align: center"><b>Fonte: <i> [Danielle Soares](https://github.com/danielle-soaress)</i></b></p></font>

## Caso de Uso 7 (IS09)

<font size="3"><p style="text-align: center">Tabela 8: Exibir informações detalhadas sobre o histórico de movimentações financeiras </p></font>

| **IS09** | **Descrição** |
| ----- | ---------- |
| **Nome do Caso de Uso**          | Exibir informações detalhadas sobre o histórico de movimentações financeiras |
| **Rastreabilidade** | [IS09](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/) |
| **Atores** | Usuários do aplicativo FGTS |
| **Ação** | O usuário acessa o histórico de movimentações financeiras e seleciona uma movimentação para visualizar informações detalhadas |
| **Pré-condições** | O usuário deve estar logado no aplicativo FGTS. <br> O sistema deve possuir movimentações financeiras registradas. |
| **Fluxo básico** | 1. O usuário efetua o login no FGTS <br> 2. O usuário acessa a página de movimentações financeiras. <br> 3. O sistema exibe a lista de movimentações registradas. <br> 4. O usuário seleciona uma movimentação específica. <br> 5. O sistema exibe as informações detalhadas da movimentação. |
| **Fluxos alternativos** | 1. O usuário efetua o login no FGTS. <br> 2. O usuário acessa a página de movimentações financeiras. <br> 3. O usuário usa o filtro para selecionar o mês e o ano. <br> O sistema exibe as movimentações financeiras do período selecionado. |
| **Exceções** | 1. O usuário efetua o login no FGTS. <br> 2. O usuário acessa a página de movimentações financeiras. <br> 3. O sistema não encontra nenhuma movimentação financeira. <br> 4. O sistema exibe uma mensagem indicando o problema. |
| **Pós-condições** | O sistema exibe corretamente as informações detalhadas da movimentação selecionada. |
| **Autor** | [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa) |

<font size="2"><p style="text-align: center"><b>Fonte: <i> [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa) </i></b></p></font>

## Caso de Uso 8 (IS10)

<font size="3"><p style="text-align: center">Tabela 9: Filtrar extrato por data </p></font>

| **IS10** | **Descrição** |
| ----- | ---------- |
| **Nome do Caso de Uso**          | Filtrar extrato por data |
| **Rastreabilidade** | [IS10](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/) |
| **Atores** | Usuários do aplicativo FGTS |
| **Ação** | O usuário filtra as movimentações financeiras exibidas no histórico de movimentações financeiras com base no mês e no ano |
| **Pré-condições** | O usuário deve estar logado no aplicativo FGTS. <br> O sistema deve possuir movimentações financeiras com diferentes datas registradas.  |
| **Fluxo básico** | 1. O usuário efetua o login no FGTS <br> 2. O usuário acessa a página de movimentações financeiras. <br> 3. O sistema exibe a lista de movimentações registradas. <br> 4. O usuário seleciona uma data (mês e ano) como filtro <br> 5. O sistema exibe apenas as movimentações correspondentes à data selecionada. |
| **Fluxos alternativos** | 1. O usuário efetua o login no FGTS <br> 2. O usuário acessa a página de movimentações financeiras. <br> 3. O sistema exibe uma lista com todas as movimentações registradas.  |
| **Exceções** | 1. O usuário efetua o login no FGTS <br> 2. O usuário acessa a página de movimentações financeiras. <br> 3. O sistema exibe a lista de movimentações registradas. <br> 4. O usuário seleciona uma data (mês e ano) inválida ou sem movimentações <br> 5. O sistema exibe uma mensagem indicando o problema. |
| **Pós-condições** | O sistema exibe o histórico de movimentações financeiras filtrado de acordo com a data selecionada. |
| **Autor** | [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa) |

<font size="2"><p style="text-align: center"><b>Fonte: <i> [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa)</i></b></p></font>

## Caso de Uso 9 (IS12)

<font size="3"><p style="text-align: center">Tabela 10: Cadastrar Múltiplas Contas Bancárias </p></font>

| **RF35** | **Descrição** |
|---------|----------------|
| **Nome do Caso de Uso**          | Cadastrar Múltiplas Contas Bancárias |
| **Rastreabilidade** | [IS12](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/) |
| **Atores** | Sistema do FGTS |
| **Ação** | <p>O usuário pode cadastrar uma ou mais contas bancárias de diferentes instituições financeiras.</p> |
| **Pré-condições** | <p>O usuário deve estar autenticado no aplicativo FGTS.</p><p>O usuário deve possuir os dados completos da conta bancária a ser cadastrada.</p> |
| **Fluxo básico** | <p>1. O usuário acessa e loga no aplicativo FGTS.</p><p>2. Navega até a seção “Meus Dados” e seleciona a opção “Conta Bancária”.</p><p>5. Clica em “Cadastrar nova conta bancária”.</p>6. O sistema solicita os dados bancários necessários.</p><p>7. O usuário preenche os campos obrigatórios e confirma o envio.</p><p>8. O sistema valida os dados informados.</p><p>9. A conta é associada ao perfil do usuário.</p>|
| **Fluxos alternativos** | <p>1. O usuário acessa e realiza login no aplicativo FGTS.</p><p>2. Navega até “Meus Dados” e seleciona “Conta Bancária”.</p><p>3. Clica em “Cadastrar nova conta bancária”.</p><p>4. O usuário informa os dados da nova conta e confirma o envio.</p><p>5. O sistema identifica que a conta já está cadastrada.</p><p>6. O sistema exibe uma mensagem informando que a conta já existe e impede duplicação.</p> |
| **Exceções** | <p>1. O usuário acessa o aplicativo FGTS e realiza login.</p><p>2. Preenche os dados da conta bancária.</p><p>3. O sistema identifica dados inválidos ou incompletos e exibe mensagem de erro destacando os campos com problema.</p><p>4. Caso ocorra falha de conexão com o servidor, o sistema exibe mensagem informativa e orienta o usuário a tentar novamente mais tarde.</p> |
| **Pós-condições** | <p>O usuário cadastrou com sucesso uma ou mais contas bancárias, ou recebeu uma mensagem com o motivo da falha.</p> |
| **Autor** | [Danielle Soares](https://github.com/danielle-soaress) |

<font size="2"><p style="text-align: center"><b>Fonte: <i> [Danielle Soares](https://github.com/danielle-soaress) </i></b></p></font>

## Caso de Uso 10 (IS13)

<font size="3"><p style="text-align: center">Tabela 11: Contato com Assistente via Chat </p></font>

| **Elemento**                     | **Descrição** |
|----------------------------------|----------------|
| **Nome do Caso de Uso**          | Contato com Assistente via Chat |
| **Rastreabilidade** | [IS13](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/) |
| **Ator Principal**               | Usuário |
| **Atores Secundários**           | Sistema do FGTS, Assistente Virtual |
| **Objetivo**                     | Permitir que o usuário entre em contato com um assistente via chat para tirar dúvidas ou obter suporte relacionado ao FGTS. |
| **Pré-condições**                | - O usuário deve estar autenticado no aplicativo.<br>- A funcionalidade de chat deve estar disponível e operacional. |
| **Fluxo Principal de Eventos**   | 1. O usuário acessa o aplicativo do FGTS.<br>2. Seleciona a opção de "Ajuda" ou "Suporte".<br>3. O sistema exibe a interface do chat.<br>4. O usuário digita sua dúvida.<br>5. O assistente responde com orientações baseadas no contexto da solicitação.<br>6. O usuário continua a conversa ou encerra o atendimento. |
| **Fluxos Alternativos**          | - O usuário acessa o chat por meio de outro ponto do aplicativo (ex: ao visualizar um status de saque).<br>- O assistente direciona o usuário para funcionalidades específicas com base na dúvida.<br> |
| **Exceções**                    | - Falha de conexão com o servidor: o app exibe mensagem de erro e oferece opção de tentar novamente.<br>- Módulo de chat indisponível: o app exibe alternativa de contato por outros canais.<br>- Dúvida não compreendida: o assistente oferece opções adicionais ou redireciona para atendimento humano. |
| **Pós-condições**                | - O usuário recebeu suporte via chat e teve sua dúvida resolvida ou foi orientado sobre próximos passos. |
| **Autor** | [Marcelo Makoto](https://github.com/MM4k)|

<font size="2"><p style="text-align: center"><b>Fonte: <i> [Marcelo Makoto](https://github.com/MM4k) </i></b></p></font>

## Caso de Uso 11 (IS14)

<font size="3"><p style="text-align: center">Tabela 12: Busca de Funcionalidades e Informações </p></font>

| **Elemento**                     | **Descrição** |
|----------------------------------|----------------|
| **Nome do Caso de Uso**          | Busca de Funcionalidades e Informações |
| **Rastreabilidade** | [IS14](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/) |
| **Ator Principal**               | Usuário |
| **Atores Secundários**           | Sistema do FGTS |
| **Objetivo**                     | Permitir que o usuário localize rapidamente funcionalidades ou informações no aplicativo por meio de um campo de busca. |
| **Pré-condições**                | - O usuário deve estar autenticado no aplicativo.<br>- O mecanismo de busca deve estar ativo e sincronizado com o conteúdo do sistema. |
| **Fluxo Principal de Eventos**   | 1. O usuário acessa o aplicativo do FGTS.<br>2. Digita um termo no campo de busca.<br>3. O sistema processa a consulta e exibe resultados relevantes.<br>4. O usuário seleciona uma funcionalidade ou informação listada.<br>5. O sistema redireciona o usuário para a área ou funcionalidade escolhida. |
| **Fluxos Alternativos**          | - O usuário limpa o campo de busca para iniciar nova consulta.<br>- O sistema sugere termos relacionados para ampliar a busca.<br> |
| **Exceções**                    | - Termo pesquisado não retorna resultados: o sistema informa que não foram encontrados itens correspondentes.<br>- Falha na comunicação com o servidor de busca: o app exibe mensagem de erro e permite nova tentativa. |
| **Pós-condições**                | - O usuário localizou e acessou a funcionalidade ou informação desejada via busca. |
| **Autor** | [Marcelo Makoto](https://github.com/MM4k)|

<font size="2"><p style="text-align: center"><b>Fonte: <i> [Marcelo Makoto](https://github.com/MM4k) </i></b></p></font>

## Caso de Uso 12 (IS16)

<font size="3"><p style="text-align: center">Tabela 13: Página de Ajuda </p></font>

| **Elemento** | **Descrição** |
|-|-|
| **Nome do Caso de Uso** | Página de Ajuda |
| **Rastreabilidade** | [IS16](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#requisitos-funcionais) |
| **Ator Principal** | Usuário |
| **Atores Secundários** | - |
| **Objetivo** | Proporcionar uma seção explicativa ao usuário, que solucione dúvidas relacionadas ao uso do aplicativo. |
| **Pré-condições** | - |
| **Fluxo Principal de Eventos** | 1. O usuário acessa o aplicativo do FGTS.<br>2. Na página de autenticação e na página inicial, o usuário seleciona o botão "Ajuda".<br>3. O sistema é direcionado à página de ajuda, com uma lista de dúvidas frequentes e uma caixa de pesquisa.<br>4. O usuário seleciona uma dúvida listada ou pesquisa na caixa de busca.<br>5. O sistema abre uma nova página com uma explicação detalhada sobre aquele tópico. |
| **Fluxos Alternativos** | - O usuário aborta a operação e retorna à página inicial. |
| **Exceções** | - Falha de conexão com o servidor: o app exibe um aviso, mas mostra as informações de ajuda offline. |
| **Pós-condições** | - O usuário sanou a sua dúvida sobre o aplicativo e está pronto para utilizá-lo normalmente. |
| **Autor** | [Eduardo de Pina](https://github.com/eduardodpms) |



<font size="2"><p style="text-align: center"><b>Fonte: <i> [Eduardo de Pina](https://github.com/eduardodpms) </i></b></p></font>

## Caso de Uso 13 (ST07)

<font size="3"><p style="text-align: center">Tabela 14: Guia Interativo </p></font>

| **Elemento** | **Descrição** |
|-|-|
| **Nome do Caso de Uso** | Guia Interativo |
| **Rastreabilidade** | [ST07](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#requisitos-funcionais) |
| **Ator Principal** | Usuário |
| **Atores Secundários** | - |
| **Objetivo** | Auxiliar, interativamente, o usuário durante a realização de ações básicas no app. |
| **Pré-condições** | - |
| **Fluxo Principal de Eventos** | 1. O usuário acessa o aplicativo do FGTS.<br>2. Em cada botão de ação do aplicativo, o usuário será capaz de clicar em um botão "?".<br>3. O sistema iniciará um guia interativo com um balão de texto e uma seta, indicando o que o usuário pode/deve fazer.<br>4. Ao seguir o passo a passo indicado, o usuário poderá ser guiado para todas as funções do aplicativo. |
| **Fluxos Alternativos** | - O usuário aborta o guia interativo clicando em um "X".<br>- O usuário volta para a etapa anterior, clicando em uma seta. |
| **Exceções** | - Falha de conexão com o servidor: o app exibe uma mensagem de erro, pois a falha impede que o usuário se quer acesse a opção para a qual ele pode requerer o guia interativo. |
| **Pós-condições** | - O usuário realiza a ação que planejava inicialmente.<br>- O usuário é capaz de repetir essa ação sem a necessidade de um guia. |
| **Autor** | [Eduardo de Pina](https://github.com/eduardodpms) |

<font size="2"><p style="text-align: center"><b>Fonte: <i> [Eduardo de Pina](https://github.com/eduardodpms) </i></b></p></font>

## Caso de Uso 14 (ST08)

<font size="3"><p style="text-align: center">Tabela 15: Ajuste do Tamanho da Fonte </p></font>

| **Elemento**                     | **Descrição** |
|----------------------------------|----------------|
| **Nome do Caso de Uso**          | Ajustar Tamanho da Fonte |
| **Rastreabilidade** | [ST08](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#requisitos-funcionais) |
| **Ator Principal**               | Usuário |
| **Atores Secundários**           | Sistema FGTS |
| **Objetivo**                     | Permitir que o usuário personalize o tamanho das fontes na interface do aplicativo para melhor acessibilidade e leitura. |
| **Pré-condições**                | - O usuário deve estar autenticado no aplicativo.<br>- O sistema deve oferecer suporte a variações de tamanho de fonte na interface. |
| **Fluxo Principal de Eventos**   | 1. O usuário acessa as configurações do aplicativo.<br>2. Seleciona a opção "Ajuste de Fonte".<br>3. Escolhe o tamanho de fonte desejado (pequeno, médio, grande).<br>4. O sistema aplica o novo tamanho de fonte em toda a interface do aplicativo.<br>5. O sistema confirma a atualização visual com feedback ao usuário. |
| **Fluxos Alternativos**          | - O usuário testa visualmente diferentes tamanhos antes de confirmar.<br>- O usuário opta por restaurar o tamanho padrão. |
| **Exceções**                     | • Tamanho de fonte inválido ou incompatível:<br>- O sistema exibe mensagem de erro e mantém o tamanho anterior.<br>• Erro de salvamento nas preferências:<br>- Sistema alerta e solicita nova tentativa. |
| **Pós-condições**                | - O tamanho de fonte é atualizado e refletido na interface.<br>- Preferência é salva para sessões futuras. |
| **Autor**                        | [Maria Eduarda](https://github.com/dudaa28) |

<font size="2"><p style="text-align: center"><b>Fonte: <i> [Maria Eduarda](https://github.com/dudaa28) </i></b></p></font>

## Pré-condição

A **pré-condição** é uma condição ou estado que deve ser verdadeiro antes do início da execução de um caso de uso para que ele possa ocorrer corretamente. Ela garante que o sistema e os atores estejam preparados para que a funcionalidade desejada seja executada sem erros. No processo de modelagem com UML, definir as pré-condições ajuda a esclarecer os requisitos necessários para que o fluxo principal do caso de uso aconteça.

No app FGTS, uma pré-condição para o caso de uso **Visualizar Data Prevista para Liberação de Valores** é:

• Que usuário esteja autenticado
• Que exista um pedido de saque registrado no sistema. 

Sem essas condições, o sistema não pode fornecer a informação solicitada, evitando falhas e garantindo a integridade da interação.


## Pós-Condições

A pós-condição descreve o estado esperado do sistema após a execução bem-sucedida de um caso de uso. Ela assegura que, ao final do processo, o sistema tenha alcançado um resultado consistente e esperado. Na modelagem de sistemas com UML, as pós-condições ajudam a definir claramente o que deve ter mudado ou sido garantido após o término do caso de uso.

No contexto do app FGTS, uma pós-condição para o caso de uso **Visualizar Data Prevista para Liberação de Valores** é:

• Que o usuário tenha obtido acesso à data estimada de liberação (ou à informação de que não há previsão cadastrada), garantindo clareza e transparência sobre o andamento do seu pedido.


## Fluxos

| Caso de Uso                 | Fluxo Básico                                                                                     | Fluxos Alternativos                         | Fluxos de Exceção                                                                                               |
| --------------------------- | ------------------------------------------------------------------------------------------------ | ------------------------------------------- | --------------------------------------------------------------------------------------------------------------- |
| [EN02](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Entrevista/#requisitos-funcionais) | Usuário acessa o app → vai à seção Saque → seleciona pedido → vê status e comentário atualizados | Seleciona outro pedido → vê status anterior | Falha conexão → mostra erro e tenta de novo<br>Sem saques → informa ausência<br>Comentário ausente → link ajuda |                                                                                            |
| [EN03](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Entrevista/#requisitos-funcionais) | Usuário acessa app → vai a Meus Saques → seleciona saque → vê data prevista e histórico | Consulta histórico de datas → vê etapas → recebe notificações | Data expirou → aviso e orientação<br>Sem previsão → informa ausência<br>Sem conexão → erro e tentar novamente |
| [EN04](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Entrevista/#requisitos-funcionais) | Usuário abre app → vai à seção Suporte → interage com chatbot → recebe resposta → continua ou encerra conversa | Usuário envia dúvida para atendimento humano → sistema registra e informa prazo | Chatbot indisponível → mostra erro e sugere canais alternativos<br>Falha conexão → informa erro e pede nova tentativa |
| [IS06](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/) | Usuário acessa app → vai a Meus Saques → seleciona saque → clica em cancelar → confirma → sistema cancela e notifica | Usuário não confirma cancelamento → operação abortada | Saque já processado → bloqueia ação<br>Falha conexão/erro → mostra erro |
| [IS07](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/) | Usuário acessa app → vai a Histórico de Saques → seleciona filtro → escolhe tipo → sistema exibe lista filtrada | Usuário remove filtro → vê todos os saques<br>Sistema informa ausência de saques do tipo | Falha conexão → mostra erro<br>Erro no filtro → tenta novamente |
|    [IS08](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/)     | Usuário acessa app → faz login → vai a Saques → seleciona Saques Bloqueados → vê lista com motivos | Motivo bloqueio ausente → mensagem genérica<br>Sem saques bloqueados → informa ausência<br>Usuário pede mais info → link ajuda | Falha conexão login → erro e orientação para tentar novamente |
|    [IS09](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/)     | Usuário faz login → acessa movimentações → vê lista → seleciona movimentação → vê detalhes  | Usuário usa filtro → vê movimentações do período            | Sem movimentações → sistema avisa                            |
| [IS10](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/)        | Usuário faz login → acessa movimentações → seleciona filtro por mês/ano → vê movimentações    | Usuário faz login → acessa movimentações → vê lista completa | Data inválida ou sem movimentações → sistema exibe mensagem de erro          |
| [IS12](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/)        | Usuário loga no app → vai em “Meus Dados” → seleciona “Conta Bancária” → clica em “Cadastrar nova conta” → preenche dados → confirma → sistema valida → conta associada ao perfil | Usuário tenta cadastrar conta já existente → sistema mostra mensagem de conta duplicada e impede cadastro | Dados inválidos/incompletos → sistema exibe erro e destaca campos<br>Falha de conexão → mensagem e orientação para tentar novamente |
| [IS13](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/) | Usuário acessa o app FGTS → seleciona "Ajuda" ou "Suporte" → sistema exibe interface de chat → usuário digita dúvida → assistente responde → usuário continua conversa ou encerra | Usuário acessa chat por outro ponto do app (ex: status de saque) → assistente direciona para funcionalidades específicas | Falha de conexão com servidor → exibe erro e oferece tentar novamente<br>Módulo de chat indisponível → oferece contato por outros canais<br>Dúvida não compreendida → oferece opções adicionais ou redireciona para atendimento humano |
| [IS14](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/) | Usuário acessa o app FGTS → digita termo no campo de busca → sistema processa e exibe resultados → usuário seleciona funcionalidade/informação → sistema redireciona para a área escolhida | Usuário limpa campo de busca para nova consulta → sistema sugere termos relacionados | Termo pesquisado não retorna resultados → sistema informa ausência<br>Falha na comunicação com servidor → exibe erro e permite nova tentativa |
| [IS16](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#requisitos-funcionais)            | Usuário acessa app FGTS → na autenticação ou página inicial seleciona "Ajuda" → sistema direciona à página de ajuda → usuário seleciona dúvida listada ou pesquisa → sistema abre explicação detalhada | Usuário aborta operação e retorna à página inicial | Falha de conexão → app exibe aviso e mostra informações de ajuda offline                                      |
| [ST07](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#antonio-ribeiro-persona-secundaria)       | Usuário acessa app FGTS → clica no botão "?" em qualquer ação → sistema inicia guia interativo com balão e seta → usuário segue passo a passo para usar funções do app | Usuário aborta guia clicando em "X" → usuário volta etapa anterior clicando em seta | Falha de conexão → app exibe erro e impede acesso à opção para o guia interativo                                         |
| [ST08](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#requisitos-funcionais) | Usuário acessa configurações do app → seleciona "Ajuste de Fonte" → escolhe tamanho desejado (pequeno, médio, grande) → sistema aplica novo tamanho → sistema confirma atualização com feedback | Usuário testa diferentes tamanhos antes de confirmar → usuário opta por restaurar tamanho padrão | Tamanho inválido/incompatível → sistema exibe erro e mantém tamanho anterior<br>Erro ao salvar preferências → sistema alerta e solicita nova tentativa |

<font size="2"><p style="text-align: center"><b>Fonte: <i> [Maria Eduarda](https://github.com/dudaa28) </i></b></p></font>




## Bibliografia

> <a id="BIB1" href="#anchor_1">1.</a> SERRANO, Milene; SERRANO, Maurício. Requisitos – Aula 13. UnB, 2025, p. [11]. Disponível em: [https://aprender3.unb.br/pluginfile.php/3096118/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf](https://aprender3.unb.br/pluginfile.php/3096118/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf). Acesso em: 17 de maio de 2025.

><a id="BIB2" href="#anchor_2">2.</a> Lucid Software. *Diagrama de caso de uso UML: o que é, como fazer e exemplos*. Lucidchart, 2025. Disponível em: [https://www.lucidchart.com/pages/pt/diagrama-de-caso-de-uso-uml](https://www.lucidchart.com/pages/pt/diagrama-de-caso-de-uso-uml). Acesso em: 18 de maio de 2025.

## Referências

> <a id="REF1" href="#anchor_3">1.</a> SERRANO, Milene; SERRANO, Maurício. *Requisitos – Aula 13*. UnB, 2025. Disponível em: [https://aprender3.unb.br/pluginfile.php/3096118/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf](https://aprender3.unb.br/pluginfile.php/3096118/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf). Acesso em: 17 de maio de 2025.


> <a id="REF2" href="#anchor_4">2.</a> DIAGRAMS.NET. App Diagrams.net. Disponível em: https://app.diagrams.net/. Acesso em: 18 maio 2025.



## Histórico de Versão

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| :-: | :-: | :-: | :-: | :-: |
| `1.0` | 16/05/2025 | Criação do documento | [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa) | [Enzo Emir](https://github.com/EnzoEmir)|
| `1.1` | 17/05/2025 | Adição do caso de uso 1 e 2 |  [Enzo Emir](https://github.com/EnzoEmir) | [Marcelo Makoto](https://github.com/MM4k) |
| `1.2` | 17/05/2025 | Adição dos casos de uso 10 e 11 | [Marcelo Makoto](https://github.com/MM4k) | [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa) |
| `1.3` | 17/05/2025 | Adição dos casos de uso 07 e 08 | [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa) | [Victor Pontual](https://github.com/VictorPontual) |
| `1.4` | 17/05/2025 | Adição dos casos de uso 05 e 06 | [Victor Pontual](https://github.com/VictorPontual) | [Danielle](https://github.com/danielle-soaress) |
| `1.5` | 17/05/2025 | Adição dos casos de uso 09 e 12 | [Danielle](https://github.com/danielle-soaress) | [Victor Pontual](https://github.com/VictorPontual) |
| `1.6` | 18/05/2025 | Correção de erros e padronização dos tópicos | [Victor Pontual](https://github.com/VictorPontual) | [Maria Eduarda](https://github.com/dudaa28) |
| `1.7` | 18/05/2025 | Adição de Casos de Uso e Correções | [Maria Eduarda](https://github.com/dudaa28) | [Danielle](https://github.com/danielle-soaress) |
| `1.8` | 18/05/2025 | Atualização de detalhes na página | [Maria Eduarda](https://github.com/dudaa28) | [Danielle](https://github.com/danielle-soaress) |
| `1.9` | 18/05/2025 | Inserção dos Diagramas | [Danielle](https://github.com/danielle-soaress), [Eduardo](https://github.com/eduardodpms), [Enzo](https://github.com/EnzoEmir), [Leticia](https://github.com/Leticia-Arisa-K-Higa), [Marcelo](https://github.com/MM4k), [Maria](https://github.com/dudaa28), [Victor](https://github.com/VictorPontual) | [Danielle](https://github.com/danielle-soaress), [Eduardo](https://github.com/eduardodpms), [Enzo](https://github.com/EnzoEmir), [Leticia](https://github.com/Leticia-Arisa-K-Higa), [Marcelo](https://github.com/MM4k), [Maria](https://github.com/dudaa28), [Victor](https://github.com/VictorPontual) |
| `2.0` | 18/05/2025 | Atualização de detalhes na página | [Maria Eduarda](https://github.com/dudaa28) | [Danielle](https://github.com/danielle-soaress) |
| `2.1` | 18/05/2025 | Atualização de detalhes na página e adição de referências | [Maria Eduarda](https://github.com/dudaa28) | [Eduardo de Pina](https://github.com/eduardodpms) |
| `2.2` | 18/05/2025 | Adição de casos de uso faltantes | [Eduardo de Pina](https://github.com/eduardodpms) | [Maria Eduarda](https://github.com/dudaa28) |
| `2.3` | 18/05/2025 | Adição Fluxos | [Maria Eduarda](https://github.com/dudaa28) | [Danielle](https://github.com/danielle-soaress) |
| `2.4` | 18/05/2025 | Atualização Página | [Maria Eduarda](https://github.com/dudaa28) | [Danielle](https://github.com/danielle-soaress) |Corrigindo Diagrama | [Danielle](https://github.com/danielle-soaress) |[Maria Eduarda](https://github.com/dudaa28) |