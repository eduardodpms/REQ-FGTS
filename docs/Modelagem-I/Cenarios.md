# Cenários

## Introdução

Este documento apresenta a especificação de cenários de uso relacionados à experiência do usuário no aplicativo do FGTS (Fundo de Garantia do Tempo de Serviço). Os cenários foram elaborados com base em requisitos  funcionais não implementados identificados durante a análise das necessidades dos usuários, especialmente no que diz respeito à clareza das informações e à confiabilidade da comunicação.

O objetivo é representar, de forma estruturada, como o sistema deve se comportar para atender aos requisitos esperados pelos usuários, utilizando uma abordagem centrada na experiência e na interação humano-computador. 

## Metodologia

A elaboração dos cenários seguiu uma abordagem centrada no usuário, que envolvem a descrição dos seguintes elementos: título, metas/objetivo, contexto, atores, recursos, exceções e episódios.

Os requisitos foram analisados e transformados em cenários descritivos com foco na melhoria da experiência do usuário. Cada cenário reflete uma situação prática que pode ocorrer durante o uso do aplicativo do FGTS e apresenta uma solução esperada com base no requisito correspondente.

Para organizar o trabalho em grupo, cada membro da equipe ficou responsável por desenvolver e apresentar **dois cenários completos**. Essa divisão garantiu a participação equilibrada e permitiu uma análise mais aprofundada de cada situação, favorecendo a compreensão coletiva dos requisitos e o desenvolvimento colaborativo da documentação.

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
      <td><a href="https://github.com/danielle-soaress">Danielle Soares</a></td>
      <td>16/05/2025</td>
      <td>23:28</td>
    </tr>
    <tr>
      <td><a href="https://github.com/eduardodpms">Eduardo de Pina</a></td>
      <td>18/05/2025</td>
      <td>12:03</td>
    </tr>
    <tr>
      <td><a href="https://github.com/EnzoEmir">Enzo Emir</a></td>
      <td>17/05/2025</td>
      <td>00:48</td>
    </tr>
    <tr>
      <td><a href="https://github.com/Leticia-Arisa-K-Higa">Leticia Arisa</a></td>
      <td>16/05/2025</td>
      <td>23:50</td>
    </tr>
    <tr>
      <td><a href="https://github.com/MM4k">Marcelo Makoto</a></td>
      <td>17/05/2025</td>
      <td>09:14</td>
    </tr>
    <tr>
      <td><a href="https://github.com/dudaa28">Maria Eduarda</a></td>
      <td>17/05/2025</td>
      <td>19:17</td>
    </tr>
    <tr>
      <td><a href="https://github.com/VictorPontual">Victor Pontual</a></td>
      <td>17/05/2025</td>
      <td>17:00</td>
    </tr>
  </tbody>
</table>

</div>



<font size="2"><p style="text-align: center">Fonte: <i>[Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa)</i> </p></font>

## Cenário 1 : Visualizar Status Comentado do Saque

<font size="3"><p style="text-align: center">Tabela 1: Cenário de vizualização Status Comentado do Saque</p></font>

<center>

| Cenário 1 | Visualizar Status Comentado do Saque |  
| :-:       | :-:            |  
| **ID** | [EN02](https://eduardodpms.github.io/REQ-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Entrevista/#requisitos-funcionais) |  
| **Objetivo** | Permitir que o usuário acompanhe o andamento do processo de saque com status detalhado e comentários explicativos. |  
| **Contexto** | O usuário deseja entender em que etapa está seu pedido de saque do FGTS e o motivo da situação atual. |  
| **Atores** | Usuário, Sistema do FGTS |  
| **Recursos** | Aplicativo FGTS, conexão à internet, API de status e comentários do saque |  
| **Episódios** | 1. O usuário acessa o app do FGTS.<br>2. Navega até a seção "Saque".<br>3. Seleciona o pedido ativo.<br>4. O sistema exibe o status atual com um comentário explicativo.<br>5. O sistema atualiza automaticamente status e comentário conforme o processo avança. |  
| **Restrições** | O status e o comentário devem estar sincronizados com o sistema central em tempo real. |  
| **Exceção** | Falha de conexão, ausência de comentário, saque inexistente ou erro na obtenção dos dados. |  
| **Autor** | [Enzo Emir](https://github.com/EnzoEmir) |


</center>

<font size="2"><p style="text-align: center">Fonte: <i>[Enzo Emir](https://github.com/EnzoEmir)</i> </p></font>

## Cenário 2: Visualizar Data Prevista para Liberação de Valores

<font size="3"><p style="text-align: center">Tabela 2: Cenário de vizualização Data Prevista para Liberação de Valores</p></font>

<center>

| Cenário 2 | Visualizar Data Prevista para Liberação de Valores |  
| :-:       | :-:            |  
| **ID** | [EN03](https://eduardodpms.github.io/REQ-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Entrevista/#requisitos-funcionais) |
| **Objetivo** | Garantir que o usuário visualize uma data realista e seja avisado em caso de alterações na previsão de liberação do valor. |  
| **Contexto** | O usuário realizou um saque e deseja saber quando o valor será liberado para planejamento financeiro. |  
| **Atores** | Usuário, Sistema do FGTS, Servidor de Notificações |  
| **Recursos** | Aplicativo FGTS, banco de dados com previsão de liberação, sistema de notificações |  
| **Episódios** | 1. O usuário acessa o app e vai para "Meus Saques".<br>2. Seleciona o saque em andamento.<br>3. O sistema mostra a data prevista de liberação.<br>4. Se a data foi alterada, o app mostra a nova previsão e o motivo.<br>5. O histórico de alterações fica disponível. |  
| **Restrições** | Toda alteração de data deve ser notificada ao usuário com justificativa. |  
| **Exceção** | Data expirou sem atualização, ausência de previsão, falha de sincronização. |  
| **Autor** | [Enzo Emir](https://github.com/EnzoEmir) |


</center>

<font size="2"><p style="text-align: center">Fonte: <i>[Enzo Emir](https://github.com/EnzoEmir)</i> </p></font>


## Cenário 3: Atendimento de Dúvidas via Chatbot

<font size="3"><p style="text-align: center">Tabela 3: Cenário de Atendimento de Dúvidas via Chatbot</p></font>

<center>

| Cenário 3 | Atendimento de Dúvidas via Chatbot | 
| :-:       | :-:            |
| **ID** | [EN04](https://eduardodpms.github.io/REQ-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Entrevista/#requisitos-funcionais) | 
| **Objetivo** | Permitir que o usuário esclareça dúvidas frequentes por meio de um canal automatizado de atendimento dentro do aplicativo | 
| **Contexto** | Local: Residência do usuário<br>Tempo: Durante o uso do aplicativo<br>Pré-condições: Estar logado, possuir conexão com a internet e ter o aplicativo instalado | 
| **Atores** | Usuário do aplicativo FGTS, sistema de chatbot | 
| **Recursos** | Dispositivo com o aplicativo FGTS instalado<br>Conexão com a internet<br>Banco de dados com perguntas e respostas<br>Módulo de chatbot funcional | 
| **Episódios** | 1. Usuário acessa o aplicativo FGTS e faz login<br>2. Acessa o menu de "Ajuda" ou "Suporte"<br>3. Chatbot é carregado<br>4. Usuário digita a dúvida<br>5. Chatbot responde automaticamente<br>6. Caso necessário, oferece atendimento humano | 
| **Restrições** | O chatbot precisa estar online e conectado ao banco de dados<br>Atendimento humano limitado ao horário comercial<br>Necessário internet estável | 
| **Exceção** | Se o chatbot não responder ou falhar, o sistema exibe: "Desculpe, não entendi sua pergunta. Você pode reformular ou entrar em contato com o suporte humano." | 
| **Autor** | [Maria Eduarda](https://github.com/dudaa28) | 

</center>

<font size="2"><p style="text-align: center">Fonte: <i>[Maria Eduarda](https://github.com/dudaa28)</i> </p></font>


## Cenário 4: Cancelar Solicitação de Saque

<font size="3"><p style="text-align: center">Tabela 4: Cenário de cancelamento de solicitação de saque</p></font>

<center>

| Cenário 4 | Cancelar Solicitação de Saque |  
| :-:       | :-:            |  
| **Código** | [IS06](https://eduardodpms.github.io/REQ-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#requisitos-funcionais) |  
| **Objetivo** | Permitir que o usuário cancele uma solicitação de saque feita anteriormente no aplicativo FGTS. |  
| **Contexto** | O usuário deseja cancelar um pedido de saque ativo por motivos pessoais ou por erro na solicitação. |  
| **Atores** | Usuário, Sistema do FGTS |  
| **Recursos** | Aplicativo FGTS, conexão à internet, API de gerenciamento de saques |  
| **Episódios** | 1. O usuário acessa o aplicativo do FGTS.<br>2. Navega até a seção "Saque".<br>3. Seleciona o pedido de saque ativo.<br>4. Opta pela opção “Cancelar solicitação”.<br>5. O sistema solicita confirmação da ação.<br>6. O usuário confirma o cancelamento.<br>7. O sistema processa a solicitação e atualiza o status para cancelado.<br>8. O usuário recebe notificação da confirmação do cancelamento. |  
| **Restrições** | O cancelamento só pode ser feito enquanto o saque não estiver processado ou concluído. |  
| **Exceção** | Falha na comunicação com o servidor, tentativa de cancelamento após processamento, erro interno. |  
| **Autor** | [Victor Pontual](https://github.com/VictorPontual) | 

</center>

<font size="2"><p style="text-align: center">Fonte: <i>[Victor Pontual](https://github.com/VictorPontual)</i> </p></font>

## Cenário 5: Filtrar Saques por Tipo

<font size="3"><p style="text-align: center">Tabela 5: Cenário de filtragem de saques por tipo</p></font>

<center>


| Cenário 5 | Filtrar Saques por Tipo |  
| :-:       | :-:            |  
| **Código** | [IS07](https://eduardodpms.github.io/REQ-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#requisitos-funcionais) |  
| **Objetivo** | Permitir que o usuário filtre a lista de solicitações de saque pelo tipo específico, como saque-aniversário, doença ou falecimento. |  
| **Contexto** | O usuário deseja visualizar apenas os saques de um determinado tipo para facilitar a consulta e o gerenciamento de seus pedidos. |  
| **Atores** | Usuário, Aplicativo FGTS |  
| **Recursos** | Aplicativo FGTS, conexão à internet, base de dados de saques com classificação por tipo |  
| **Episódios** | 1. O usuário acessa o aplicativo do FGTS.<br>2. Navega até a seção "Histórico de Saques".<br>3. Seleciona a opção de filtro.<br>4. Escolhe o tipo de saque desejado (ex: aniversário, doença, falecimento).<br>5. O sistema exibe apenas os saques correspondentes ao filtro selecionado.<br>6. O usuário visualiza a lista filtrada e pode acessar detalhes de cada saque. |  
| **Restrições** | O filtro deve refletir apenas os tipos válidos e previamente cadastrados no sistema. |  
| **Exceção** | Falha na aplicação do filtro, ausência de saques para o tipo selecionado, erro na consulta ao banco de dados. |  
| **Autor** | [Victor Pontual](https://github.com/VictorPontual) | 

</center>

<font size="2"><p style="text-align: center">Fonte: <i>[Victor Pontual](https://github.com/VictorPontual)</i> </p></font>

## Cenário 6: Fornecimento de informações sobre saques bloqueados

<a name="C06"></a>

<font size="3"><p style="text-align: center">Tabela 6: Cenário de fornecimento de informações sobre saques bloqueados</p></font>

<center>

| **Cenário 6** | **Consulta de saques bloqueados** | 
| :-:           | :-:                              |
| **ID**    | [IS08](https://eduardodpms.github.io/REQ-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#requisitos-funcionais) |
| **Objetivo**  | Permitir que o usuário visualize quais saques estão bloqueados e os motivos do bloqueio. |
| **Contexto**  | Local: Casa do Usuário <br> Tempo: Durante o dia <br> Pré-condições: Ter uma conta FGTS, aplicativo FGTS instalado, estar logado e com acesso à internet. |
| **Atores**    | Usuário do App FGTS |
| **Recursos**  | Dispositivo com o aplicativo instalado <br> Conexão com a internet <br> Base de dados com status dos saques e motivos de bloqueio |
| **Episódios** | 1. O usuário abre o aplicativo. <br> 2. Insere seus dados de acesso e realiza o login. <br> 3. Acessa a seção "Saques" no menu principal. <br> 4. Seleciona a opção "Saques Bloqueados". <br> 5. O sistema exibe a lista de saques bloqueados com os respectivos detalhes, incluindo o motivo do bloqueio. |
| **Restrições** | O motivo do bloqueio só será exibido se estiver registrado no sistema; caso contrário, uma mensagem genérica será apresentada. <br> O usuário também precisa ter saques bloqueados. |
| **Exceção**   | Se houver falha na conexão com o servidor ou indisponibilidade dos dados, o sistema exibirá uma mensagem de erro informando a impossibilidade de recuperar as informações no momento. |
| **Autor**     | [Danielle Soares](https://github.com/danielle-soaress) |

</center>

<font size="2"><p style="text-align: center">Fonte: <i>[Danielle Soares](https://github.com/danielle-soaress)</i> </p></font>


## <a name="C07"></a> Cenário 7: Visualizar histórico de movimentação financeira

<font size="3"><p style="text-align: center">Tabela 7: Cenário de visuaização histórico de movimentação financeira</p></font>

<center>

| Cenário 7 | Visualizar histórico de movimentação financeira | 
| :-:       | :-:            |
| **ID** | [IS09](https://eduardodpms.github.io/REQ-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#requisitos-funcionais) | 
| **Objetivo** | Permitir que o usuário consulte informações detalhadas de suas movimentações financeiras passadas | 
| **Contexto** | Local: Página "Movimentações" (a ser implementada no aplicativo) <br> Tempo: A qualquer momento <br> Pré-condição: O usuário deve estar autenticado no sistema e deve possuir movimentações financeiras anteriores registradas | 
| **Atores** | Usuário do aplicativo FGTS | 
| **Recursos** | Conexão com a internet <br> Smartphone com o aplicativo FGTS instalado | 
| **Episódios** | 1. Usuário abre o aplicativo e faz login. <br> 2. Usuário acessa a página "Movimentações". <br> 3. Aplicativo exibe uma lista de movimentações. <br> 4. Usuário seleciona uma movimentação especifíca. <br> 5. Aplicativo exibe os detalhes da movimentação. | 
| **Restrições** | O usuário precisa estar conectado à internet. <br> O usuário precisa ter movimentações financeira registradas. <br> O aplicativo precisa ter acesso aos dados de movimentação do usuário. | 
| **Exceção** | Falha na conexão com a internet. <br> Caso não haja movimentações registradas, o aplicativo deve exibir uma mensagem informando: "Nenhuma movimentação encontrada." | 
| **Autor** | [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa) | 

</center>

<font size="2"><p style="text-align: center">Fonte: <i>[Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa)</i> </p></font>

## <a name="C08"></a> Cenário 8: Filtrar extrato por data

<font size="3"><p style="text-align: center">Tabela 8: Cenário de filtragem de extrato por data</p></font>

<center>

| Cenário 8 | Filtrar extrato por data | 
| :-:       | :-:            |
| **ID** | [IS10](https://eduardodpms.github.io/REQ-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#requisitos-funcionais) | 
| **Objetivo** | Permitir que o usuário selecione um mês e ano específico para visualizar os extratos correspondentes. | 
| **Contexto** | Local: Página "Movimentações" (a ser implementada no aplicativo) <br> Tempo: A qualquer momento <br> Pré-condição: O usuário deve estar autenticado no sistema e deve possuir movimentações financeiras registradas em diferentes datas | 
| **Atores** | Usuário do aplicativo FGTS | 
| **Recursos** | Conexão com a internet <br> Smartphone com o aplicativo FGTS instalado | 
| **Episódios** |  1. Usuário abre o aplicativo e faz login. <br> 2. Usuário acessa a página "Movimentações". <br> 3. Aplicativo exibe uma lista de movimentações. <br> 4. Usuário clica no filtro de data. <br> 5. Usuário seleciona o mês e o ano desejado. <br> 6. Aplicativo filtra e exibe apenas os extratos correspondentes ao período selecionado. | 
| **Restrições** | O filtro deve permitir selecionar apenas períodos válidos (mês e ano) | 
| **Exceção** | Falha na conexão com a internet. <br> Caso não haja extratos registrados no período selecionado, o aplicativo deve exibir uma mensagem informando: "Nunhum extrato encontrado para o período selecionado" | 
| **Autor** | [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa) | 

</center>

<font size="2"><p style="text-align: center">Fonte: <i>[Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa)</i> </p></font>

## Cenário 9: Cadastro de múltiplas contas bancárias

<font size="3"><p style="text-align: center">Tabela 9: Cenário do Cadastro de múltiplas contas bancárias</p></font>

<center>

| **Cenário 9** | **Cadastro de mais de uma conta bancária** | 
| :-:           | :-:                                        |
| **ID**    | [IS12](https://eduardodpms.github.io/REQ-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#requisitos-funcionais) |
| **Objetivo**  | Permitir que o usuário cadastre uma ou mais contas bancárias de diferentes instituições financeiras. |
| **Contexto**  | Local: Casa do Usuário <br> Tempo: Durante o dia <br> Pré-condições: Ter o aplicativo FGTS instalado, estar logado em sua conta, ter os dados da(s) conta(s) bancária(s) em mãos e acesso à internet. |
| **Atores**    | Usuário do App FGTS |
| **Recursos**  | Aplicativo FGTS instalado <br> Conexão com a internet <br> Dados da(s) conta(s) bancária(s) |
| **Episódios** | 1. O usuário acessa e realiza login no aplicativo. <br> 2. Acessa a seção "Meus Dados" no menu principal. <br> 3. Seleciona a opção "Conta Bancária". <br> 4. Clica em "Cadastrar nova conta bancária". <br> 5. O sistema solicita os dados da nova conta: banco, agência, número da conta, tipo de conta e titularidade. <br> 6. O usuário preenche os dados e confirma o cadastro. <br> 7. O sistema valida as informações e salva a nova conta associada ao usuário. <br> 8. O usuário repete o processo para adicionar outra conta de uma instituição diferente. <br> 9. O sistema exibe a lista completa de contas cadastradas. |
| **Restrições** | O sistema não deve permitir contas duplicadas (mesmo banco, agência e número). <br> Deve haver validação de CPF/titularidade. |
| **Exceção**   | Se os dados da conta forem inválidos ou incompletos, o sistema exibirá uma mensagem de erro orientando a correção. |
| **Autor**     | [Danielle Soares](https://github.com/danielle-soaress) |

</center>


<font size="2"><p style="text-align: center">Fonte: <i>[Danielle Soares](https://github.com/danielle-soaress)</i> </p></font>

## Cenário 10: Contato com Assistente via Chat

<font size="3"><p style="text-align: center">Tabela 10: Cenário de Contato com Assistente via Chat</p></font>

<center>

| Cenário 10 | Contato com Assistente via Chat |  
| :-:       | :-:            |  
| **ID** | [IS13](https://eduardodpms.github.io/REQ-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#requisitos-funcionais) |  
| **Objetivo** | Permitir que o usuário entre em contato com um assistente via chat para tirar dúvidas ou obter suporte relacionado ao FGTS. |  
| **Contexto** | O usuário deseja esclarecer dúvidas ou obter ajuda durante a navegação no aplicativo do FGTS. |  
| **Atores** | Usuário, Sistema do FGTS, Assistente Virtual |  
| **Recursos** | Aplicativo FGTS, conexão à internet e módulo de chat com assistente |  
| **Episódios** | 1. O usuário acessa o aplicativo do FGTS.<br>2. Clica na opção de ajuda ou suporte.<br>3. O sistema exibe a interface de chat.<br>4. O usuário digita sua dúvida.<br>5. O assistente virtual responde com informações relevantes. |  
| **Restrições** | A funcionalidade de chat exige conexão com a internet e deve estar disponível em tempo integral. |  
| **Exceção** | Falha de conexão, erro ao carregar o chat, ausência de resposta do assistente. |  
| **Autor** | [Marcelo Makoto](https://github.com/MM4k) | 

</center>

<font size="2"><p style="text-align: center">Fonte: <i>[Marcelo Makoto](https://github.com/MM4k)</i> </p></font>

## Cenário 11: Busca de Funcionalidades e Informações

<font size="3"><p style="text-align: center">Tabela 11: Cenário de Busca de Funcionalidades e Informações</p></font>

<center>

| Cenário 11 | Busca de Funcionalidades e Informações |  
| :-:       | :-:            |  
| **ID** | [IS14](https://eduardodpms.github.io/REQ-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#requisitos-funcionais) |  
| **Objetivo** | Permitir que o usuário localize rapidamente funcionalidades ou informações no aplicativo por meio de um campo de busca. |  
| **Contexto** | O usuário deseja encontrar uma funcionalidade específica ou obter informações sem navegar por várias seções do aplicativo. |  
| **Atores** | Usuário, Sistema do FGTS |  
| **Recursos** | Aplicativo FGTS, conexão à internet e mecanismo de busca interno |  
| **Episódios** | 1. O usuário acessa o aplicativo do FGTS.<br>2. Digita um termo no campo de busca (ex: “extrato”, “saldo”, “saque”).<br>3. O sistema exibe os resultados correspondentes.<br>4. O usuário seleciona o item desejado e é redirecionado à funcionalidade. |  
| **Restrições** | O mecanismo de busca deve abranger todas as funcionalidades e textos informativos disponíveis no aplicativo. |  
| **Exceção** | Termo não encontrado, falha no carregamento dos resultados, ausência de retorno relevante. |  
| **Autor** | [Marcelo Makoto](https://github.com/MM4k) | 

</center>

<font size="2"><p style="text-align: center">Fonte: <i>[Marcelo Makoto](https://github.com/MM4k)</i> </p></font>

## Cenário 12: Seção de ajuda com explicações relacionadas ao app

<font size="3"><p style="text-align: center">Tabela 12: Cenário de Seção de ajuda com orientações sobre o uso do aplicativo</p></font>

<center>

| Cenário 12 | Utilização da página de dúvidas | 
| :-:       | :-:            |
| **ID** | [IS16](https://eduardodpms.github.io/REQ-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#requisitos-funcionais) | 
| **Objetivo** | Fornecer explicações ao usuário sobre dúvidas relacionadas à utilização do app. | 
| **Contexto** | O usuário possui alguma dúvida sobre as funcionalidades do app e deseja esclarecimentos. | 
| **Atores** | Usuário | 
| **Recursos** | App FGTS | 
| **Episódios** | 1. O usuário acessa o aplicativo do FGTS.<br>2. O usuário seleciona o botão "Ajuda".<br>3. O sistema exibe uma lista de dúvidas frequentes relacionadas ao app.<br>4. O usuário encontra a sua dúvida e a seleciona.<br>5. O sistema exibe uma explicação a respeito daquela dúvida. | 
| **Restrições** | O sistema deve possuir uma caixa de busca para uma pesquisa mais extensa no banco de dúvidas. | 
| **Exceção** | Na ausência de conexão com o servidor, o app será capaz de mostrar somente as dúvidas mais frequentes. | 
| **Autor** | [Eduardo de Pina](https://github.com/eduardodpms) | 

</center>

<font size="2"><p style="text-align: center">Fonte: <i>[Eduardo de Pina](https://github.com/eduardodpms)</i> </p></font>

## Cenário 13: Guia interativo para orientação sobre o uso do aplicativo

<font size="3"><p style="text-align: center">Tabela 13: Cenário de Guia interativo para orientação sobre o uso do aplicativo</p></font>

<center>

| Cenário 13 | Utilização do guia interativo | 
| :-:       | :-:            |
| **ID** | [ST07](https://eduardodpms.github.io/REQ-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#requisitos-funcionais) | 
| **Objetivo** | Guiar interativamente o usuário pelos botões, até que ele conclua seu objetivo. | 
| **Contexto** | O usuário é novato na utilização do app e deseja utilizar alguma função específica ou básica do aplicativo. | 
| **Atores** | Usuário | 
| **Recursos** | App FGTS | 
| **Episódios** | 1. O usuário acessa o aplicativo do FGTS.<br>2. O usuário seleciona o botão "?", na ação que deseja ser orientado.<br>3. O aplicativo inicia um guia interativo para orientar o usuário.<br>4. O usuário é levado até a ação que desejava, inicialmente, realizar. | 
| **Restrições** | O usuário deve ser capaz de abortar o guia interativo e de voltar etapas. | 
| **Exceção** | Na ausência de conexão com o servidor, o usuário ficará incapacitado de acessar certas funções, portanto, também ficará incapacitado de acessar seus respectivos guias interativos. | 
| **Autor** | [Eduardo de Pina](https://github.com/eduardodpms) | 

</center>

<font size="2"><p style="text-align: center">Fonte: <i>[Eduardo de Pina](https://github.com/eduardodpms)</i> </p></font>

## Cenário 14: Ajuste do Tamanho das Fontes na Interface

<font size="3"><p style="text-align: center">Tabela 14: Cenário Ajuste do Tamanho das Fontes na Interface</p></font>

<center>

| Cenário 14 | Ajuste do Tamanho das Fontes na Interface | 
| :-:       | :-:            |
| **ID**  | [ST08](https://eduardodpms.github.io/REQ-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#requisitos-funcionais) | 
| **Objetivo** | Permitir que o usuário ajuste o tamanho das fontes exibidas na interface do aplicativo para melhorar a acessibilidade e a usabilidade. | 
| **Contexto** | Usuário acessa o aplicativo e deseja aumentar ou diminuir o tamanho da fonte para melhor visualização do conteúdo. | 
| **Atores** | Usuário do aplicativo FGTS | 
| **Recursos** | Interface do aplicativo, configurações de exibição, controle de tamanho de fonte | 
| **Episódios** | 1. Usuário abre as configurações da interface. <br> 2. Usuário seleciona a opção de ajuste de tamanho da fonte. <br> 3. Usuário escolhe o tamanho desejado (ex: pequeno, médio, grande). <br> 4. A interface atualiza o tamanho das fontes exibidas. | 
| **Restrições** | O ajuste de tamanho deve ser aplicado a todos os elementos textuais da interface. <br> Deve ser possível retornar ao tamanho padrão. | 
| **Exceção** | Caso o ajuste não seja aplicado corretamente, o aplicativo deve exibir uma mensagem de erro e manter o tamanho anterior. | 
| **Autor** | [Maria Eduarda](https://github.com/dudaa28) | 

</center>

<font size="2"><p style="text-align: center">Fonte: <i>[Maria Eduarda](https://github.com/dudaa28)</i> </p></font>



## Referências Bibliográficas
> 1.</a> BARBOSA, Simone Diniz Junqueira et al. Interação humano-computador e experiência do usuario. Auto publicação, 2021. 

> 2.</a> SERRANO, Milene; SERRANO, Maurício. Requisitos – Aula 10. UnB, 2025, p. 8. Disponível em: [https://aprender3.unb.br/pluginfile.php/3096108/mod_resource/content/1/Aula%2010.pdf](https://aprender3.unb.br/pluginfile.php/3096108/mod_resource/content/1/Aula%2010.pdf). Acesso em: 17 de maio de 2025.



## Histórico de Versão

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| :-: | :-: | :-: | :-: | :-: |
| `1.0` | 15/05/2025 | Criação do documento | [Danielle Soares](https://github.com/danielle-soaress) |[Enzo Emir ](https://github.com/EnzoEmir) |
| `1.1` | 16/05/2025 | Adição do texto da Introdução,Metodologia e Bibliografia | [Enzo Emir ](https://github.com/EnzoEmir) |[Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa)|
| `1.2` | 16/05/2025 | Organização das tabelas | [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa) |[Danielle Soares](https://github.com/danielle-soaress)|
| `1.3` | 16/05/2025 | Adicionando cenários 6 e 9 | [Danielle Soares](https://github.com/danielle-soaress) | [Enzo Emir ](https://github.com/EnzoEmir) |
| `1.4` | 17/05/2025 | Adição cenários 1 e 2 | [Enzo Emir ](https://github.com/EnzoEmir) | [Marcelo Makoto](https://github.com/MM4k) |
| `1.5` | 17/05/2025 | Adição dos cenários 10 e 11 | [Marcelo Makoto](https://github.com/MM4k) | [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa) |
| `1.6` | 17/05/2025 | Adição dos cenários 07 e 08 | [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa) | [Victor Pontual](https://github.com/VictorPontual) |
| `1.7` | 17/05/2025 | Adição dos cenários 04 e 05 + correção de formatação | [Victor Pontual](https://github.com/VictorPontual) | [Maria Eduarda](https://github.com/dudaa28) |
| `1.8` | 17/05/2025 | Adição dos cenários 03 e 14 | [Maria Eduarda](https://github.com/dudaa28) | [Danielle Soares](https://github.com/danielle-soaress) |
| `1.9` | 17/05/2025 | Atualização do Documento | [Maria Eduarda](https://github.com/dudaa28) | [Danielle Soares](https://github.com/danielle-soaress) |
| `2.0` | 17/05/2025 | Atualizações para melhoria do Documento | [Maria Eduarda](https://github.com/dudaa28) | [Eduardo de Pina](https://github.com/eduardodpms) |
| `2.1` | 17/05/2025 | Correção do atributo "título" para "id" | [Danielle Soares](https://github.com/danielle-soaress) | [Eduardo de Pina](https://github.com/eduardodpms) |
| `2.2` | 18/05/2025 | Adição de cenários para os casos de uso faltantes | [Eduardo de Pina](https://github.com/eduardodpms) | [Maria Eduarda](https://github.com/dudaa28) |
| `2.3` | 22/06/2025 | Adição de revisores | [Victor Pontual](https://github.com/VictorPontual) | [Marcelo Makoto](https://github.com/MM4k) |