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
      <td> Danielle Soares </td>
      <td> 16/05/2025 </td>
      <td> 23:28 </td>
    </tr>
    <tr>
      <td> Eduardo de Pina </td>
      <td> - </td>
      <td> - </td>
    </tr>
    <tr>
      <td> Enzo Emir </td>
      <td> 17/05/2025 </td>
      <td> 00:48   </td>
    </tr>
    <tr>
      <td> Leticia Arisa </td>
      <td> 16/05 </td>
      <td> 23:50 </td>
    </tr>
    <tr>
      <td> Marcelo Makoto </td>
      <td> 17/05/2025 </td>
      <td> 09:14 </td>
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

## Cenário 1

<font size="3"><p style="text-align: center">Tabela 1: Cenário...</p></font>

<center>

| Cenário 1 | Visualizar Status Comentado do Saque |  
| :-:       | :-:            |  
| **Título** | EN02 |  
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

## Cenário 2

<font size="3"><p style="text-align: center">Tabela 2: Cenário...</p></font>

<center>

| Cenário 2 | Visualizar Data Prevista para Liberação de Valores |  
| :-:       | :-:            |  
| **Código** | EN03 |  
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

## Cenário 3

<font size="3"><p style="text-align: center">Tabela 3: Cenário...</p></font>

<center>

| Cenário 3 | Título do Cenário | 
| :-:       | :-:            |
| **Título** |  | 
| **Objetivo** |  | 
| **Contexto** |  | 
| **Atores** |  | 
| **Recursos** |  | 
| **Episódios** |   | 
| **Restrições** |  | 
| **Exceção** |  | 
| **Autor** | [Maria Eduarda](https://github.com/dudaa28) | 

</center>

<font size="2"><p style="text-align: center">Fonte: <i>[Maria Eduarda](https://github.com/dudaa28)</i> </p></font>

## Cenário 4

<font size="3"><p style="text-align: center">Tabela 4: Cenário...</p></font>

<center>

| Cenário 4 | Cancelar Solicitação de Saque |  
| :-:       | :-:            |  
| **Código** | IS06 |  
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

## Cenário 5

<font size="3"><p style="text-align: center">Tabela 5: Cenário...</p></font>

<center>


| Cenário 5 | Filtrar Saques por Tipo |  
| :-:       | :-:            |  
| **Código** | IS07 |  
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

## Cenário 6

<font size="3"><p style="text-align: center">Tabela 6: Fornecer informações sobre saques bloqueados</p></font>

<center>

| **Cenário 6**               | **Consulta de saques bloqueados** |
|----------------------------|------------------------------------|
| **Objetivo**               | <p>Permitir que o usuário visualize quais saques estão bloqueados e os motivos do bloqueio.</p> |
| **Contexto**               | <p>Local: Casa do Usuário</p> <p>Tempo: Durante o dia</p> <p>Pré-condições: Ter uma conta FGTS, aplicativo FGTS instalado, estar logado e com acesso à internet.</p> |
| **Atores**                 | <p>Usuário do App FGTS</p> |
| **Recursos**               | <p>Dispositivo com o aplicativo instalado</p> <p>Conexão com a internet</p> <p>Base de dados com status dos saques e motivos de bloqueio</p> |
| **Episódios**              | <p>1. O usuário abre o aplicativo.</p> <p>2. Insere seus dados de acesso e realiza o login.</p> <p>3. Acessa a seção "Saques" no menu principal.</p> <p>4. Seleciona a opção "Saques Bloqueados".</p> <p>5. O sistema exibe a lista de saques bloqueados com os respectivos detalhes, incluindo o motivo do bloqueio.</p> |
| **Restrições**             | <p>O motivo do bloqueio só será exibido se estiver registrado no sistema; caso contrário, uma mensagem genérica será apresentada.</p> <p>O usuário também precisa ter saques bloqueados.</p> |
| **Exceção**                | <p>Se houver falha na conexão com o servidor ou indisponibilidade dos dados, o sistema exibirá uma mensagem de erro informando a impossibilidade de recuperar as informações no momento.</p> |
| **Autor**                  | [Danielle Soares](https://github.com/danielle-soaress) |

</center>

<font size="2"><p style="text-align: center">Fonte: <i>[Danielle Soares](https://github.com/danielle-soaress)</i> </p></font>

## Cenário 7

<font size="3"><p style="text-align: center">Tabela 7: Cenário de visualizar histórico de movimentação financeira</p></font>

<center>

| Cenário 7 | Visualizar histórico de movimentação financeira | 
| :-:       | :-:            |
| **Título** | Visualizar informações detalhadas do histórico de movimentação financeira | 
| **Objetivo** | Permitir que o usuário consulte informações detalhadas de suas movimentações financeiras passadas | 
| **Contexto** | Local: Página "Movimentações" (a ser implementada no aplicativo) <br> Tempo: A qualquer momento <br> Pré-condição: O usuário deve estar autenticado no sistema e deve possuir movimentações financeiras anteriores registradas | 
| **Atores** | Usuário do aplicativo FGTS | 
| **Recursos** | Conexão com a internet <br> Smartphone com o aplicativo FGTS instalado | 
| **Episódios** | Usuário abre o aplicativo e faz login. <br> Usuário acessa a página "Movimentações". <br> Aplicativo exibe uma lista de movimentações. <br> Usuário seleciona uma movimentação especifíca. <br> Aplicativo exibe os detalhes da movimentação. | 
| **Restrições** | O usuário precisa estar conectado à internet. <br> O usuário precisa ter movimentações financeira registradas. <br> O aplicativo precisa ter acesso aos dados de movimentação do usuário. | 
| **Exceção** | Falha na conexão com a internet. <br> Caso não haja movimentações registradas, o aplicativo deve exibir uma mensagem informando: "Nenhuma movimentação encontrada." | 
| **Autor** | [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa) | 

</center>

<font size="2"><p style="text-align: center">Fonte: <i>[Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa)</i> </p></font>

## Cenário 8

<font size="3"><p style="text-align: center">Tabela 8: Cenário de filtrar extrato por data</p></font>

<center>

| Cenário 8 | Filtrar extrato por data | 
| :-:       | :-:            |
| **Título** | Filtrar extrato por data (mês e ano) | 
| **Objetivo** | Permitir que o usuário selecione um mês e ano específico para visualizar os extratos correspondentes. | 
| **Contexto** | Local: Página "Movimentações" (a ser implementada no aplicativo) <br> Tempo: A qualquer momento <br> Pré-condição: O usuário deve estar autenticado no sistema e deve possuir movimentações financeiras registradas em diferentes datas | 
| **Atores** | Usuário do aplicativo FGTS | 
| **Recursos** | Conexão com a internet <br> Smartphone com o aplicativo FGTS instalado | 
| **Episódios** |  Usuário abre o aplicativo e faz login. <br> Usuário acessa a página "Movimentações". <br> Aplicativo exibe uma lista de movimentações. <br> Usuário clica no filtro de data. <br> Usuário seleciona o mês e o ano desejado. <br> Aplicativo filtra e exibe apenas os extratos correspondentes ao período selecionado. | 
| **Restrições** | O filtro deve permitir selecionar apenas períodos válidos (mês e ano) | 
| **Exceção** | Falha na conexão com a internet. <br> Caso não haja extratos registrados no período selecionado, o aplicativo deve exibir uma mensagem informando: "Nunhum extrato encontrado para o período selecionado" | 
| **Autor** | [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa) | 

</center>

<font size="2"><p style="text-align: center">Fonte: <i>[Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa)</i> </p></font>

## Cenário 9

<font size="3"><p style="text-align: center">Tabela 9: Cadastro de múltiplas contas bancárias</p></font>

<center>

| **Cenário 9**               | **Cadastro de mais de uma conta bancária** |
|----------------------------|---------------------------------------------|
| **Objetivo**               | <p>Permitir que o usuário cadastre uma ou mais contas bancárias de diferentes instituições financeiras.</p> |
| **Contexto**               | <p>Local: Casa do Usuário</p> <p>Tempo: Durante o dia</p> <p>Pré-condições: Ter o aplicativo FGTS instalado, estar logado em sua conta, ter os dados da(s) conta(s) bancária(s) em mãos e acesso à internet.</p> |
| **Atores**                 | <p>Usuário do App FGTS</p> |
| **Recursos**               | <p>Aplicativo FGTS instalado</p> <p>Conexão com a internet</p> <p>Dados da(s) conta(s) bancária(s)</p> |
| **Episódios**              | <p>1. O usuário acessa e realiza login no aplicativo.</p> <p>2. Acessa a seção "Meus Dados" no menu principal.</p> <p>3. Seleciona a opção "Conta Bancária".</p> <p>4. Clica em "Cadastrar nova conta bancária".</p> <p>5. O sistema solicita os dados da nova conta: banco, agência, número da conta, tipo de conta e titularidade.</p> <p>6. O usuário preenche os dados e confirma o cadastro.</p> <p>7. O sistema valida as informações e salva a nova conta associada ao usuário.</p> <p>8. O usuário repete o processo para adicionar outra conta de uma instituição diferente.</p> <p>9. O sistema exibe a lista completa de contas cadastradas.</p> |
| **Restrições**             | <p>O sistema não deve permitir contas duplicadas (mesmo banco, agência e número).</p> <p>Deve haver validação de CPF/titularidade.</p> |
| **Exceção**                | <p>Se os dados da conta forem inválidos ou incompletos, o sistema exibirá uma mensagem de erro orientando a correção.</p> |
| **Autor**                  | [Danielle Soares](https://github.com/danielle-soaress) |

</center>

<font size="2"><p style="text-align: center">Fonte: <i>[Danielle Soares](https://github.com/danielle-soaress)</i> </p></font>

## Cenário 10

<font size="3"><p style="text-align: center">Tabela 10: Contato com Assistente via Chat</p></font>

<center>

| Cenário 10 | Contato com Assistente via Chat |  
| :-:       | :-:            |  
| **Título** | IS13 |  
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

## Cenário 11

<font size="3"><p style="text-align: center">Tabela 11: Busca de Funcionalidades e Informações</p></font>

<center>

| Cenário 11 | Busca de Funcionalidades e Informações |  
| :-:       | :-:            |  
| **Título** | IS14 |  
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

## Cenário 12

<font size="3"><p style="text-align: center">Tabela 12: Cenário...</p></font>

<center>

| Cenário 12 | Título do Cenário | 
| :-:       | :-:            |
| **Título** |  | 
| **Objetivo** |  | 
| **Contexto** |  | 
| **Atores** |  | 
| **Recursos** |  | 
| **Episódios** |   | 
| **Restrições** |  | 
| **Exceção** |  | 
| **Autor** | [Eduardo de Pina](https://github.com/eduardodpms) | 

</center>

<font size="2"><p style="text-align: center">Fonte: <i>[Eduardo de Pina](https://github.com/eduardodpms)</i> </p></font>

## Cenário 13

<font size="3"><p style="text-align: center">Tabela 13: Cenário...</p></font>

<center>

| Cenário 13 | Título do Cenário | 
| :-:       | :-:            |
| **Título** |  | 
| **Objetivo** |  | 
| **Contexto** |  | 
| **Atores** |  | 
| **Recursos** |  | 
| **Episódios** |   | 
| **Restrições** |  | 
| **Exceção** |  | 
| **Autor** | [Eduardo de Pina](https://github.com/eduardodpms) | 

</center>

<font size="2"><p style="text-align: center">Fonte: <i>[Eduardo de Pina](https://github.com/eduardodpms)</i> </p></font>

## Cenário 14

<font size="3"><p style="text-align: center">Tabela 14: Cenário...</p></font>

<center>

| Cenário 14 | Título do Cenário | 
| :-:       | :-:            |
| **Título** |  | 
| **Objetivo** |  | 
| **Contexto** |  | 
| **Atores** |  | 
| **Recursos** |  | 
| **Episódios** |   | 
| **Restrições** |  | 
| **Exceção** |  | 
| **Autor** | [Maria Eduarda](https://github.com/dudaa28) | 

</center>

<font size="2"><p style="text-align: center">Fonte: <i>[Maria Eduarda](https://github.com/dudaa28)</i> </p></font>


## Bibliografia
> 1.</a> BARBOSA, Simone Diniz Junqueira et al. Interação humano-computador e experiência do usuario. Auto publicação, 2021. 

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
| `1.7` | 17/05/2025 | Adição dos cenários 04 e 05 + correção de formatação | [Victor Pontual](https://github.com/VictorPontual) | - |

