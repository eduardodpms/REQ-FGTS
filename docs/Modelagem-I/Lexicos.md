# Léxicos

## Introdução

**Léxico** é uma técnica utilizada para descrever os símbolos(termos) de uma linguagem, identificado palavras ou expressões específicas. Cada símbolo é descrito por meio de **noção** e **impacto**. A **noção** corresponde à denotação do símbolo, ou seja, seu significado literal. Já o **impacto** refere-se à conotação, descrevendo o efeito,uso ou ocorrência do símbolo na aplicação, ou ainda o impacto que algum elemento da aplicação exerce sobre ele.
Um símbolo pode possuir zero ou mais senônimos, uma ou mais noções, e um ou mais impactos (SERRANO et al.).

## Metodologia

A construção dos léxicos foi baseada na notação LAL — Léxico Ampliado da Linguagem —, que utiliza a descrição de termos por meio de léxicos. Na Tabela 1, é possível observar as regras utilizadas para a elaboração dos léxicos, categorizadas por tipo. Já a Tabela 2 apresenta o template adotado para a criação dos léxicos.

Seguindo a recomendação do professor de que cada membro do grupo fosse responsável por, no mínimo, dois requisitos funcionais não implementados, todos os integrantes contribuíram com a criação dos léxicos. Na Tabela 3, estão listados os nomes dos participantes, a data de elaboração dos léxicos por cada um e o horário de conclusão.

<font size="3"><p style="text-align: center">Tabela 1: Tipos de léxicos</p></font>

<center>

| Tipo    | Noção                                                                       | Impacto                                                                                  |
| ------- | --------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- 
| Verbo   | Quem realiza, quando acontece e quais os procedimentos envolvidos.          | Quais os reflexos da ação no ambiente (outras ações que devem ocorrer) e quais os novos estados decorrentes    |
| Objeto  | Definir o objeto e identificar os outros objetos com os quais se relaciona. | Ações que podem ser aplicadas ao objeto.                                                 |
| Estado  | O que significa e quais ações levaram a esse estado.                        | Identificar outros estados e ações que podem ocorrer a partir do estado que se descreve. |

</center>

<font size="2"><p style="text-align: center">Fonte: SERRANO et al.</p></font>

<br>

<font size="3"><p style="text-align: center">Tabela 2: Template Léxicos</p></font>

<center>

| L0X | Descrição | 
| :-:       | :-:            |
| **Termo** |  | 
| **Tipo** |  | 
| **Impacto** |  | 
| **Noção** |  | 
| **Sinônimos** |  | 
| **Autor** |  | 

</center>

<font size="2"><p style="text-align: center">Fonte: [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa)</p></font>

<br>

<font size="3"><p style="text-align: center">Tabela 3: Participantes</p></font>

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
      <td> 00:01 </td>
    </tr>
    <tr>
      <td> Eduardo de Pina </td>
      <td> 18/05/2025 </td>
      <td> 17:35 </td>
    </tr>
    <tr>
      <td> Enzo Emir </td>
      <td> 17/05/2025 </td>
      <td> 01:21 </td>
    </tr>
    <tr>
      <td> Leticia Arisa </td>
      <td> 17/05 </td>
      <td> 8:24 </td>
    </tr>
    <tr>
      <td> Marcelo Makoto </td>
      <td> 17/05/2025 </td>
      <td> 15:10 </td>
    </tr>
    <tr>
      <td> Maria Eduarda </td>
      <td> 17/05/2025 </td>
      <td> 22:00 </td>
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

## Sumário

**Requisito N02:**

- [L01 – Consultar Status](#l01-consultar-status)
- [L02 – Status do Saque](#l02-status-do-saque)
- [L03 – Comentário Explicativo](#l03-comentario-explicativo)
- [L04 – Saque em Análise](#l04-saque-em-analise)
- [L05 – Saque Aprovado](#l05-saque-aprovado)
- [L06 – Saque Efetuado](#l06-saque-efetuado)
- [L07 – Saque Pendente](#l07-saque-pendente)
- [L08 – Saque Cancelado](#l08-saque-cancelado)
- [L09 – Status Visualizado](#l09-status-visualizado)

**Requisito EN03:**

- [L10 – Visualizar Data Prevista](#l10-visualizar-data-prevista)
- [L11 – Data Prevista](#l11-data-prevista)
- [L12 – Notificação](#l12-notificacao)
- [L13 – Data Visualizada](#l13-data-visualizada)

**Requisito EN04:**

- [L14 – Oferecer Canal de Suporte](#l14-oferecer-canal-de-suporte)
- [L15 – Canal de Suporte](#l15-canal-de-suporte)

**Requisito ST08:**

- [L16 – Ajustar Tamanho da Fonte](#l16-ajustar-tamanho-da-fonte)
- [L17 – Tamanho da Fonte](#l17-tamanho-da-fonte)
- [L18 – Acessibilidade](#l18-acessibilidade)
- [L19 – Interface do Aplicativo](#l19-interface-do-aplicativo)

**Requisito IS06:**

- [L20 – Cancelar Solicitação](#l20-cancelar-solicitacao)
- [L21 – Solicitação de Saque](#l21-solicitacao-de-saque)
- [L22 – Confirmação de Cancelamento](#l22-confirmacao-de-cancelamento)
- [L23 – Solicitação Ativa](#l23-solicitacao-ativa)
- [L24 – Solicitação Cancelada](#l24-solicitacao-cancelada)
- [L25 – Solicitação Processada](#l25-solicitacao-processada)

**Requisito IS07:**

- [L26 – Filtrar Saques por Tipo](#l26-filtrar-saques-por-tipo)
- [L27 – Lista de Saques](#l27-lista-de-saques)
- [L28 – Filtro de Tipo](#l28-filtro-de-tipo)
- [L29 – Lista Filtrada](#l29-lista-filtrada)

**Requisito IS12:**

- [L30 – Cadastrar](#l30-cadastrar)

**Requisito IS09:**

- [L31 – Exibir Informações Detalhadas](#l31-exibir-informacoes-detalhadas)
- [L32 – Informações Detalhadas](#l32-informacoes-detalhadas)
- [L33 – Histórico de Movimentações Financeiras](#l33-historico-de-movimentacoes-financeiras)

**Requisito IS10:**

- [L34 – Filtrar](#l34-filtrar)

**Requisito IS08:**

- [L35 – Bloqueado](#l35-bloqueado)

**Requisito IS13:**

- [L36 – Chat](#l36-chat)
- [L37 – Assistente Virtual](#l37-assistente-virtual)
- [L38 – Mensagem](#l38-mensagem)

**Requisito IS14:**

- [L39 – Buscar](#l39-buscar)
- [L40 – Campo de Busca](#l40-campo-de-busca)
- [L41 – Termo de Pesquisa](#l41-termo-de-pesquisa)

**Requisito IS16:**

- [L42 – Acessar Ajuda](#l42-acessar-ajuda)
- [L43 – Procurar Dúvida](#l43-procurar-duvida)

**Requisito ST07:**

- [L44 – Requerer Guia](#l44-requerer-guia)
- [L45 – Seguir Guia](#l45-seguir-guia)

---

## Requisito EN02

---

### L01: Consultar Status

O léxico L01 utiliza o requisito funcional EN02 (O sistema deve permitir que o usuário visualize o status do saque com comentários explicativos). Esse léxico é detalhado na tabela abaixo:

<font size="3"><p style="text-align: center">Tabela 4: Léxico L01 – Consultar Status</p></font>

<center>

| L01 | Descrição |  
| :-:       | :-:            |  
| **Termo** | Consultar Status |  
| **Tipo** | Verbo |  
| **Impacto** | - Permite ao usuário acompanhar o andamento do processo de saque.<br> - Oferece clareza sobre a situação atual por meio de comentários explicativos.<br> - Melhora a transparência e reduz a necessidade de contato com o suporte. |  
| **Noção** | Ação de verificar, dentro do aplicativo, a situação atual de um pedido de saque, incluindo o status e uma descrição explicativa. |  
| **Sinônimos** | Verificar andamento, Acompanhar processo |  
| **Autor** | [Enzo Emir](https://github.com/EnzoEmir) |  

</center>

<font size="2"><p style="text-align: center">Fonte: [Enzo Emir](https://github.com/EnzoEmir)</p></font>

---

### L02: Status do Saque

O léxico L02 utiliza o requisito funcional EN02 (O sistema deve permitir que o usuário visualize o status do saque com comentários explicativos). Esse léxico é detalhado na tabela abaixo:

<font size="3"><p style="text-align: center">Tabela 5: Léxico L02 – Status do Saque</p></font>

<center>

| L02 | Descrição |  
| :-:       | :-:            |  
| **Termo** | Status do Saque |  
| **Tipo** | Objeto |  
| **Impacto** | - Representa a etapa atual do processo de saque.<br> - Permite ao usuário compreender a situação da solicitação.<br> - Pode influenciar ações do usuário, como aguardar, cancelar ou buscar suporte. |  
| **Noção** | Informação exibida no aplicativo que mostra em que estágio o pedido de saque se encontra (ex: Em análise, Aprovado, Efetuado). |  
| **Sinônimos** | Situação do Saque, Etapa do Processo |  
| **Autor** | [Enzo Emir](https://github.com/EnzoEmir) |  

</center>

<font size="2"><p style="text-align: center">Fonte: [Enzo Emir](https://github.com/EnzoEmir)</p></font>

---

### L03: Comentário Explicativo

O léxico L03 utiliza o requisito funcional EN02 (O sistema deve permitir que o usuário visualize o status do saque com comentários explicativos). Esse léxico é detalhado na tabela abaixo:

<font size="3"><p style="text-align: center">Tabela 6: Léxico L03 – Comentário Explicativo</p></font>

<center>

| L03 | Descrição |  
| :-:       | :-:            |  
| **Termo** | Comentário Explicativo |  
| **Tipo** | Objeto |  
| **Impacto** | - Ajuda o usuário a entender o significado do status atual do saque.<br> - Reduz dúvidas e melhora a experiência do usuário.<br> - Pode ser atualizado dinamicamente pelo sistema. |  
| **Noção** | Texto exibido junto ao status do saque para explicar sua situação de forma acessível e clara. |  
| **Sinônimos** | Explicação, Descrição do Status |  
| **Autor** | [Enzo Emir](https://github.com/EnzoEmir) |  

</center>

<font size="2"><p style="text-align: center">Fonte: [Enzo Emir](https://github.com/EnzoEmir)</p></font>

---

### L04: Saque em Análise

O léxico L04 utiliza o requisito funcional EN02 (O sistema deve permitir que o usuário visualize o status do saque com comentários explicativos). Esse léxico é detalhado na tabela abaixo:

<font size="3"><p style="text-align: center">Tabela 7: Léxico L04 – Saque em Análise</p></font>

<center>

| L04 | Descrição |  
| :-:       | :-:            |  
| **Termo** | Saque em Análise |  
| **Tipo** | Estado |  
| **Impacto** | - Indica que o pedido de saque foi recebido e está sendo avaliado.<br> - Sinaliza ao usuário que nenhuma ação adicional é necessária no momento.<br> - Pode ser acompanhado de um comentário explicativo. |  
| **Noção** | Estado inicial do processo de saque após a solicitação pelo usuário, durante o qual o sistema verifica a elegibilidade. |  
| **Sinônimos** | Em Avaliação, Aguardando Aprovação |  
| **Autor** | [Enzo Emir](https://github.com/EnzoEmir) |  

</center>

<font size="2"><p style="text-align: center">Fonte: [Enzo Emir](https://github.com/EnzoEmir)</p></font>

---

### L05: Saque Aprovado

O léxico L05 utiliza o requisito funcional EN02 (O sistema deve permitir que o usuário visualize o status do saque com comentários explicativos). Esse léxico é detalhado na tabela abaixo:

<font size="3"><p style="text-align: center">Tabela 8: Léxico L05 – Saque Aprovado</p></font>

<center>

| L05 | Descrição |  
| :-:       | :-:            |  
| **Termo** | Saque Aprovado |  
| **Tipo** | Estado |  
| **Impacto** | - Informa que o pedido de saque foi aceito pelo sistema.<br> - Gera expectativa de liberação dos valores.<br> - Pode disparar notificações e atualizações no sistema. |  
| **Noção** | Estado do pedido que indica que a solicitação passou na análise e será processada. |  
| **Sinônimos** | Liberação Autorizada, Solicitação Aprovada |  
| **Autor** | [Enzo Emir](https://github.com/EnzoEmir) |  

</center>

<font size="2"><p style="text-align: center">Fonte: [Enzo Emir](https://github.com/EnzoEmir)</p></font>

---

### L06: Saque Efetuado

O léxico L06 utiliza o requisito funcional EN02 (O sistema deve permitir que o usuário visualize o status do saque com comentários explicativos). Esse léxico é detalhado na tabela abaixo:

<font size="3"><p style="text-align: center">Tabela 9: Léxico L06 – Saque Efetuado</p></font>

<center>

| L06 | Descrição |  
| :-:       | :-:            |  
| **Termo** | Saque Efetuado |  
| **Tipo** | Estado |  
| **Impacto** | - Informa ao usuário que o valor foi efetivamente transferido.<br> - Representa o encerramento do fluxo de saque.<br> - Garante segurança e rastreabilidade do processo. |  
| **Noção** | Estado final do processo de saque, quando os valores foram transferidos para a conta informada. |  
| **Sinônimos** | Valor Transferido, Saque Realizado |  
| **Autor** | [Enzo Emir](https://github.com/EnzoEmir) |  

</center>

<font size="2"><p style="text-align: center">Fonte: [Enzo Emir](https://github.com/EnzoEmir)</p></font>

---

### L07: Saque Pendente

O léxico L07 utiliza o requisito funcional EN02 (O sistema deve permitir que o usuário visualize o status do saque com comentários explicativos). Esse léxico é detalhado na tabela abaixo:

<font size="3"><p style="text-align: center">Tabela 10: Léxico L07 – Saque Pendente</p></font>

<center>

| L07 | Descrição |  
| :-:       | :-:            |  
| **Termo** | Saque Pendente |  
| **Tipo** | Estado |  
| **Impacto** | - Indica que alguma ação ainda precisa ser realizada.<br> - Pode depender do usuário ou de uma etapa interna do sistema.<br> - Ajuda a identificar bloqueios no processo. |  
| **Noção** | Estado intermediário que sinaliza que o saque está aguardando um passo adicional para prosseguir. |  
| **Sinônimos** | Aguardando Ação, Em Espera |  
| **Autor** | [Enzo Emir](https://github.com/EnzoEmir) |  

</center>

<font size="2"><p style="text-align: center">Fonte: [Enzo Emir](https://github.com/EnzoEmir)</p></font>

---

### L08: Saque Cancelado

O léxico L08 utiliza o requisito funcional EN02 (O sistema deve permitir que o usuário visualize o status do saque com comentários explicativos). Esse léxico é detalhado na tabela abaixo:

<font size="3"><p style="text-align: center">Tabela 11: Léxico L08 – Saque Cancelado</p></font>

<center>

| L08 | Descrição |  
| :-:       | :-:            |  
| **Termo** | Saque Cancelado |  
| **Tipo** | Estado |  
| **Impacto** | - Informa que o pedido de saque foi encerrado sem sucesso.<br> - Pode ocorrer por decisão do usuário ou por falha na análise.<br> - Permite a solicitação de um novo saque. |  
| **Noção** | Estado que indica a interrupção do processo de saque, impedindo a liberação do valor. |  
| **Sinônimos** | Solicitação Anulada, Pedido Cancelado |  
| **Autor** | [Enzo Emir](https://github.com/EnzoEmir) |  

</center>

<font size="2"><p style="text-align: center">Fonte: [Enzo Emir](https://github.com/EnzoEmir)</p></font>

---

### L09: Status Visualizado

O léxico L09 utiliza o requisito funcional EN02 (O sistema deve permitir que o usuário visualize o status do saque com comentários explicativos). Esse léxico é detalhado na tabela abaixo:

<font size="3"><p style="text-align: center">Tabela 12: Léxico L09 – Status Visualizado</p></font>

<center>

| L09 | Descrição |  
| :-:       | :-:            |  
| **Termo** | Status Visualizado |  
| **Tipo** | Estado |  
| **Impacto** | - Confirma que o usuário acessou a tela de acompanhamento do saque.<br> - Permite que o sistema registre interações para fins de rastreamento.<br> - Pode ser usado para avaliar usabilidade e engajamento. |  
| **Noção** | Estado do sistema após a exibição da informação de status e comentário ao usuário. |  
| **Sinônimos** | Informações Acessadas, Tela Visualizada |  
| **Autor** | [Enzo Emir](https://github.com/EnzoEmir) |  

</center>

<font size="2"><p style="text-align: center">Fonte: [Enzo Emir](https://github.com/EnzoEmir)</p></font>

---

## Requisito EN03

---

### L10: Visualizar Data Prevista

O léxico L10 utiliza o requisito funcional EN03 (O sistema deve permitir que o usuário visualize a data prevista de liberação dos valores). Esse léxico é detalhado na tabela abaixo:

<font size="3"><p style="text-align: center">Tabela 13: Léxico L10 – Visualizar Data Prevista</p></font>

<center>

| L10 | Descrição |  
| :-:       | :-:            |  
| **Termo** | Visualizar Data Prevista |  
| **Tipo** | Verbo |  
| **Impacto** | - Permite ao usuário saber quando o valor do saque estará disponível.<br> - Aumenta a previsibilidade e a confiança no processo.<br> - Pode ser acessado via notificações ou diretamente pelo aplicativo. |  
| **Noção** | Ação realizada pelo usuário para acessar a estimativa de data de liberação dos valores solicitados para saque. |  
| **Sinônimos** | Consultar Previsão, Ver Data Estimada |  
| **Autor** | [Enzo Emir](https://github.com/EnzoEmir) |  

</center>

<font size="2"><p style="text-align: center">Fonte: [Enzo Emir](https://github.com/EnzoEmir)</p></font>

---

### L11: Data Prevista

O léxico L11 utiliza o requisito funcional EN03 (O sistema deve permitir que o usuário visualize a data prevista de liberação dos valores). Esse léxico é detalhado na tabela abaixo:

<font size="3"><p style="text-align: center">Tabela 14: Léxico L11 – Data Prevista</p></font>

<center>

| L11 | Descrição |  
| :-:       | :-:            |  
| **Termo** | Data Prevista |  
| **Tipo** | Objeto |  
| **Impacto** | - Informa ao usuário o momento estimado para a liberação do valor.<br> - Pode ser alterada conforme o andamento do processo.<br> - Serve de base para a geração de notificações. |  
| **Noção** | Informação exibida no aplicativo que representa a estimativa de quando o valor estará disponível. |  
| **Sinônimos** | Previsão, Estimativa de Liberação |  
| **Autor** | [Enzo Emir](https://github.com/EnzoEmir) |  

</center>

<font size="2"><p style="text-align: center">Fonte: [Enzo Emir](https://github.com/EnzoEmir)</p></font>

---

### L12: Notificação

O léxico L12 utiliza o requisito funcional EN03 (O sistema deve permitir que o usuário visualize a data prevista de liberação dos valores). Esse léxico é detalhado na tabela abaixo:

<font size="3"><p style="text-align: center">Tabela 15: Léxico L12 – Notificação</p></font>

<center>

| L12 | Descrição |  
| :-:       | :-:            |  
| **Termo** | Notificação |  
| **Tipo** | Objeto |  
| **Impacto** | - Comunica ao usuário sobre mudanças importantes no processo.<br> - Garante que o usuário seja informado de forma proativa.<br> - Pode envolver status de saque ou alteração na data prevista. |  
| **Noção** | Mensagem gerada automaticamente pelo sistema para alertar o usuário sobre eventos relevantes, como atualização de status ou previsão. |  
| **Sinônimos** | Alerta, Aviso, Mensagem do Sistema |  
| **Autor** | [Enzo Emir](https://github.com/EnzoEmir) |  

</center>

<font size="2"><p style="text-align: center">Fonte: [Enzo Emir](https://github.com/EnzoEmir)</p></font>

---

### L13: Data Visualizada

O léxico L13 utiliza o requisito funcional EN03 (O sistema deve permitir que o usuário visualize a data prevista de liberação dos valores). Esse léxico é detalhado na tabela abaixo:

<font size="3"><p style="text-align: center">Tabela 16: Léxico L13 – Data Visualizada</p></font>

<center>

| L13 | Descrição |  
| :-:       | :-:            |  
| **Termo** | Data Visualizada |  
| **Tipo** | Estado |  
| **Impacto** | - Confirma que o usuário visualizou a informação da previsão.<br> - Pode ser registrado para fins analíticos ou de usabilidade.<br> - Sinaliza que o sistema cumpriu sua função de comunicação. |  
| **Noção** | Estado do sistema após o usuário acessar a previsão de liberação dos valores no aplicativo. |  
| **Sinônimos** | Previsão Acessada, Data Consultada |  
| **Autor** | [Enzo Emir](https://github.com/EnzoEmir) |  

</center>

<font size="2"><p style="text-align: center">Fonte: [Enzo Emir](https://github.com/EnzoEmir)</p></font>

---

## Requisito EN04

---

### L14: Oferecer Canal de Suporte

Os léxicos apresentados a seguir (Tabelas 17 e 18) foram construidos a partir do requisito funcional não implementado que propõe que o aplicativo ofereça um canal de suporte ou chatbot para esclarecer dúvidas dos usuários ([EN04](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Entrevista/#requisitos-funcionais)). Os termos selecionados refletem ações e objetos associados à comunicação entre usuário e sistema, além de aspectos da assistência virtual.


<font size="3"><p style="text-align: center">Tabela 17: Léxico 14 – Oferecer Canal de Suporte (L14)</p></font>


| L14 | Descrição | 
| :-:       | :-:            |
| **Termo** | Oferecer canal de suporte |
| **Tipo** | Verbo |
| **Impacto** | A ação de oferecer o canal permite que o usuário tire dúvidas, melhorando a experiência de uso do aplicativo e promovendo maior autonomia na resolução de problemas. Pode desencadear interações com o chatbot ou direcionar ao atendimento humano. |
| **Noção** | Ocorre quando o sistema disponibiliza um canal automatizado (chatbot) ou humano para atendimento. Esta oferta é feita na interface do app, geralmente acessível pelo menu principal ou pela área de ajuda. |
| **Sinônimos** | Disponibilizar suporte, fornecer assistência |
| **Autor** | [Maria Eduarda](https://github.com/dudaa28) | 


<font size="2"><p style="text-align: center">Fonte: <i>[Maria Eduarda](https://github.com/dudaa28)</i> </p></font>

---

### L15: Canal de Suporte

<font size="3"><p style="text-align: center">Tabela 18: Léxico 15 – Canal de Suporte (L15)</p></font>

| L15 | Descrição | 
| :-:       | :-:            |
| **Termo** | Canal de Suporte |
| **Tipo** | Objeto |
| **Impacto** | Pode ser acessado por diferentes usuários com dúvidas. Permite interações com o sistema por meio de perguntas e respostas automáticas via chatbot ou encaminhamento a atendentes humanos. |
| **Noção** | Trata-se de uma funcionalidade do aplicativo FGTS destinada a esclarecer dúvidas dos usuários, podendo ser composta por um chatbot (atendimento automático) e, eventualmente, por um canal humano de atendimento. |
| **Sinônimos** | Chatbot, atendimento, ajuda, suporte |
| **Autor** | [Maria Eduarda](https://github.com/dudaa28) |


<font size="2"><p style="text-align: center">Fonte: [Maria Eduarda](https://github.com/dudaa28)</p></font>

---

## Requisito ST08

---

Os léxicos listados nas Tabelas 19 a 22 têm como base o requisito funcional não implementado que prevê a possibilidade de ajustar o tamanho das fontes na interface do aplicativo ([ST08](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#requisitos-funcionais)). Os termos foram escolhidos para representar tanto ações quanto objetos e estados associados à personalização da interface e à acessibilidade, considerando a melhoria da experiência para usuários com diferentes perfis.

---

### L16: Ajustar Tamanho da Fonte

<font size="3"><p style="text-align: center">Tabela 19: Léxico 16 – Ajustar Tamanho da Fonte (L16)</p></font>

| L16 | Descrição | 
| :-:       | :-:            |
| **Termo** | Ajustar tamanho da fonte |
| **Tipo** | Verbo |
| **Impacto** | O ajuste do tamanho da fonte modifica a forma como os textos são exibidos na interface do aplicativo, tornando-os mais acessíveis para diferentes perfis de usuários. Pode afetar a disposição dos elementos visuais na tela. |
| **Noção** | Acontece quando o usuário altera a configuração de exibição do texto no aplicativo, selecionando um tamanho de fonte maior ou menor de acordo com sua preferência ou necessidade de acessibilidade. |
| **Sinônimos** | Modificar fonte, alterar tamanho de texto |
| **Autor** | [Maria Eduarda](https://github.com/dudaa28) |

<font size="2"><p style="text-align: center">Fonte: <i>[Maria Eduarda](https://github.com/dudaa28)</i> </p></font>

---

### L17: Tamanho da Fonte

<font size="3"><p style="text-align: center">Tabela 20: Léxico 17 – Tamanho da Fonte (L17)</p></font>

| L17 | Descrição | 
| :-:       | :-:            |
| **Termo** | Tamanho da fonte |
| **Tipo** | Objeto |
| **Impacto** | Influencia diretamente na legibilidade dos textos exibidos na interface. A alteração do tamanho pode melhorar a acessibilidade e usabilidade do aplicativo para usuários com deficiência visual. |
| **Noção** | Parâmetro configurável que define o tamanho em que os textos são exibidos no aplicativo. Está relacionado à acessibilidade e à experiência do usuário. |
| **Sinônimos** | Tamanho do texto, escala da fonte, dimensão da letra |
| **Autor** | [Maria Eduarda](https://github.com/dudaa28) |


<font size="2"><p style="text-align: center">Fonte: <i>[Maria Eduarda](https://github.com/dudaa28)</i> </p></font>

---

### L18: Acessibilidade

<font size="3"><p style="text-align: center">Tabela 21: Léxico 18 – Acessibilidade (L18)</p></font>

| L18 | Descrição | 
| :-:       | :-:            |
| **Termo** | Acessibilidade |
| **Tipo** | Estado |
| **Impacto** | O ajuste de elementos visuais como o tamanho da fonte contribui para um estado mais acessível da interface, facilitando a navegação de pessoas com dificuldades visuais. |
| **Noção** | Condição em que o aplicativo oferece meios para que todos os usuários, independentemente de limitações físicas, possam utilizá-lo de forma efetiva. |
| **Sinônimos** | Inclusão digital, usabilidade ampliada |
| **Autor** | [Maria Eduarda](https://github.com/dudaa28) |


<font size="2"><p style="text-align: center">Fonte: <i>[Maria Eduarda](https://github.com/dudaa28)</i> </p></font>

---

### L19: Interface do Aplicativo

<font size="3"><p style="text-align: center">Tabela 22: Léxico 19 – Interface do Aplicativo (L19)</p></font>

| L19 | Descrição | 
| :-:       | :-:            |
| **Termo** | Interface do aplicativo |
| **Tipo** | Objeto |
| **Impacto** | A interface sofre mudanças visuais quando o tamanho da fonte é ajustado, podendo influenciar no layout, na navegação e na interação com o sistema. |
| **Noção** | Conjunto visual e interativo por onde o usuário acessa funcionalidades do aplicativo, incluindo botões, menus, textos e ícones. |
| **Sinônimos** | Tela do app, aparência visual, front-end |
| **Autor** | [Maria Eduarda](https://github.com/dudaa28) |


<font size="2"><p style="text-align: center">Fonte: <i>[Maria Eduarda](https://github.com/dudaa28)</i> </p></font>

---

## Requisito IS06

---

### L20: Cancelar Solicitação

O léxico L20 utiliza o requisito funcional IS06 (O sistema deve permitir que o usuário cancele um saque solicitado). Esse léxico é detalhado na tabela abaixo:

<font size="3"><p style="text-align: center">Tabela 23: Léxico 20 – Cancelar Solicitação (L20)</p></font>

| L20           | Descrição                                                                                                                                                                     |
| ------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Termo**     | Cancelar Solicitação                                                                                                                                                          |
| **Tipo**      | Verbo                                                                                                                                                                         |
| **Impacto**   | Permite que o usuário interrompa uma solicitação de saque ativa, evitando que ela seja processada ou liberada.                                                                |
| **Noção**     | Ação executada pelo usuário para cancelar um pedido de saque em andamento. O sistema verifica a possibilidade de cancelamento e atualiza o status conforme a ação do usuário. |
| **Sinônimos** | Anular pedido, Revogar solicitação                                                                                                                                            |
| **Autor**     | [Victor Pontual](https://github.com/VictorPontual)                                                                                                                            |

---

### L21: Solicitação de Saque

O léxico L21 utiliza o requisito funcional IS06 (O sistema deve permitir que o usuário cancele um saque solicitado). Esse léxico é detalhado na tabela abaixo:

<font size="3"><p style="text-align: center">Tabela 24: Léxico 21 – Solicitação de Saque (L21)</p></font>

| L21           | Descrição                                                                                                      |
| ------------- | -------------------------------------------------------------------------------------------------------------- |
| **Termo**     | Solicitação de Saque                                                                                           |
| **Tipo**      | Objeto                                                                                                         |
| **Impacto**   | Representa o pedido formal do usuário para saque de valores do FGTS.                                           |
| **Noção**     | Documento digital que contém as informações necessárias para a liberação dos valores solicitados pelo usuário. |
| **Sinônimos** | Pedido de saque, Requisição de saque                                                                           |
| **Autor**     | [Victor Pontual](https://github.com/VictorPontual)                                                             |

---

### L22: Confirmação de Cancelamento

O léxico L22 utiliza o requisito funcional IS06 (O sistema deve permitir que o usuário cancele um saque solicitado). Esse léxico é detalhado na tabela abaixo:

<font size="3"><p style="text-align: center">Tabela 25: Léxico 22 – Confirmação de Cancelamento (L22)</p></font>

| L22           | Descrição                                                                                                                         |
| ------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| **Termo**     | Confirmação de Cancelamento                                                                                                       |
| **Tipo**      | Objeto                                                                                                                            |
| **Impacto**   | Garante que o usuário valide sua intenção de cancelar a solicitação de saque, evitando cancelamentos acidentais.                  |
| **Noção**     | Ato do usuário de confirmar a operação de cancelamento após ser solicitado pelo sistema, assegurando que a ação seja intencional. |
| **Sinônimos** | Validação de cancelamento, Confirmação de ação                                                                                    |
| **Autor**     | [Victor Pontual](https://github.com/VictorPontual)                                                                                |


---

### L23: Solicitação Ativa

O léxico L23 utiliza o requisito funcional IS06 (O sistema deve permitir que o usuário cancele um saque solicitado). Esse léxico é detalhado na tabela abaixo:

<font size="3"><p style="text-align: center">Tabela 26: Léxico 23 – Solicitação Ativa (L23)</p></font>

| L23           | Descrição                                                                                                           |
| ------------- | ------------------------------------------------------------------------------------------------------------------- |
| **Termo**     | Solicitação Ativa                                                                                                   |
| **Tipo**      | Estado                                                                                                              |
| **Impacto**   | Indica que a solicitação de saque está vigente e pode ser modificada ou cancelada pelo usuário.                     |
| **Noção**     | Estado em que a solicitação de saque foi feita e ainda está em processamento, aguardando conclusão ou cancelamento. |
| **Sinônimos** | Pedido em andamento, Solicitação vigente                                                                            |
| **Autor**     | [Victor Pontual](https://github.com/VictorPontual)                                                                  |

---

### L24: Solicitação Cancelada

O léxico L24 utiliza o requisito funcional IS06 (O sistema deve permitir que o usuário cancele um saque solicitado). Esse léxico é detalhado na tabela abaixo:

<font size="3"><p style="text-align: center">Tabela 27: Léxico 24 – Solicitação Cancelada (L24)</p></font>

| L24           | Descrição                                                                                              |
| ------------- | ------------------------------------------------------------------------------------------------------ |
| **Termo**     | Solicitação Cancelada                                                                                  |
| **Tipo**      | Estado                                                                                                 |
| **Impacto**   | Indica que a solicitação de saque foi anulada e não será processada pelo sistema.                      |
| **Noção**     | Estado final em que o pedido de saque foi oficialmente cancelado pelo usuário e registrado no sistema. |
| **Sinônimos** | Pedido cancelado, Requisição anulada                                                                   |
| **Autor**     | [Victor Pontual](https://github.com/VictorPontual)                                                     |

---

### L25: Solicitação Processada

O léxico L25 utiliza o requisito funcional IS06 (O sistema deve permitir que o usuário cancele um saque solicitado). Esse léxico é detalhado na tabela abaixo:

<font size="3"><p style="text-align: center">Tabela 28: Léxico 25 – Solicitação Processada (L25)</p></font>

| L25           | Descrição                                                                                                              |
| ------------- | ---------------------------------------------------------------------------------------------------------------------- |
| **Termo**     | Solicitação Processada                                                                                                 |
| **Tipo**      | Estado                                                                                                                 |
| **Impacto**   | Indica que a solicitação de saque foi analisada e concluída pelo sistema, não podendo mais ser cancelada pelo usuário. |
| **Noção**     | Estado final onde o pedido de saque foi processado e encaminhado para liberação dos valores ou rejeição.               |
| **Sinônimos** | Pedido concluído, Solicitação finalizada                                                                               |
| **Autor**     | [Victor Pontual](https://github.com/VictorPontual)                                                                     |

<font size="2"><p style="text-align: center">Fonte: [Victor Pontual](https://github.com/VictorPontual)</p></font>

---

## Requisito IS07

---

### L26: Filtrar Saques por Tipo

O léxico L26 utiliza o requisito funcional IS07 (O aplicativo deve permitir o filtro dos saques por tipo (ex: aniversário, doença, falecimento)). Esse léxico é detalhado na tabela abaixo:

<font size="3"><p style="text-align: center">Tabela 29: Léxico 26 – Filtrar Saques por Tipo (L26)</p></font>

| L26           | Descrição                                                                                                                                 |
| ------------- | ----------------------------------------------------------------------------------------------------------------------------------------- |
| **Termo**     | Filtrar Saques por Tipo                                                                                                                   |
| **Tipo**      | Verbo                                                                                                                                     |
| **Impacto**   | Permite que o usuário restrinja a visualização dos saques exibidos no histórico com base no tipo (ex.: aniversário, doença, falecimento). |
| **Noção**     | Ação do usuário de selecionar um critério de tipo para que o sistema exiba apenas os saques correspondentes àquela categoria.             |
| **Sinônimos** | Aplicar filtro, Selecionar tipo, Restringir visualização                                                                                  |
| **Autor**     | [Victor Pontual](https://github.com/VictorPontual)                                                                                        |


---

### L27: Lista de Saques

O léxico L27 utiliza o requisito funcional IS07 (O aplicativo deve permitir o filtro dos saques por tipo (ex: aniversário, doença, falecimento)). Esse léxico é detalhado na tabela abaixo:

<font size="3"><p style="text-align: center">Tabela 30: Léxico 27 – Lista de Saques (L27)</p></font>

| L27           | Descrição                                                                                                                              |
| ------------- | -------------------------------------------------------------------------------------------------------------------------------------- |
| **Termo**     | Lista de Saques                                                                                                                        |
| **Tipo**      | Objeto                                                                                                                                 |
| **Impacto**   | Representa o conjunto de registros das solicitações de saque do usuário, possibilitando a consulta e gerenciamento dessas informações. |
| **Noção**     | Coleção organizada dos pedidos de saque efetuados pelo usuário, incluindo detalhes como tipo, valor, data e status de cada saque.      |
| **Sinônimos** | Histórico de saques, Registro de saques                                                                                                |
| **Autor**     | [Victor Pontual](https://github.com/VictorPontual)                                                                                     |


---

### L28: Filtro de Tipo

O léxico L28 utiliza o requisito funcional IS07 (O aplicativo deve permitir o filtro dos saques por tipo (ex: aniversário, doença, falecimento)). Esse léxico é detalhado na tabela abaixo:

<font size="3"><p style="text-align: center">Tabela 31: Léxico 28 – Filtro de Tipo (L28)</p></font>

| L28           | Descrição                                                                                                                           |
| ------------- | ----------------------------------------------------------------------------------------------------------------------------------- |
| **Termo**     | Filtro de Tipo                                                                                                                      |
| **Tipo**      | Objeto                                                                                                                              |
| **Impacto**   | Permite segmentar ou restringir a visualização da lista de saques com base no tipo selecionado pelo usuário.                        |
| **Noção**     | Critério utilizado para classificar e apresentar apenas os saques que pertencem a uma categoria específica (ex: saque-aniversário). |
| **Sinônimos** | Critério de seleção, Opção de filtro                                                                                                |
| **Autor**     | [Victor Pontual](https://github.com/VictorPontual)                                                                                  |

---

### L29: Lista Filtrada

O léxico L29 utiliza o requisito funcional IS07 (O aplicativo deve permitir o filtro dos saques por tipo (ex: aniversário, doença, falecimento)). Esse léxico é detalhado na tabela abaixo:

<font size="3"><p style="text-align: center">Tabela 32: Léxico 29 – Lista Filtrada (L29)</p></font>

| L29           | Descrição                                                                                                                      |
| ------------- | ------------------------------------------------------------------------------------------------------------------------------ |
| **Termo**     | Lista Filtrada                                                                                                                 |
| **Tipo**      | Estado                                                                                                                         |
| **Impacto**   | Representa o estado em que a lista de saques exibe somente os registros que correspondem aos critérios de filtro aplicados.    |
| **Noção**     | Visualização da lista de saques reduzida e organizada conforme a seleção feita pelo usuário para facilitar o acesso e análise. |
| **Sinônimos** | Lista segmentada, Resultado filtrado                                                                                           |
| **Autor**     | [Victor Pontual](https://github.com/VictorPontual)                                                                             |

---

<font size="2"><p style="text-align: center">Fonte: [Victor Pontual](https://github.com/VictorPontual)</p></font>

---

## Requisito IS12

---

### L30: Cadastrar

O léxico L30 utiliza o requisito funcional IS12 (O aplicativo deve permitir o cadastro de mais de uma conta bancária de diferentes instituições financeiras). Esse léxico é detalhado na tabela abaixo:

<font size="3"><p style="text-align: center">Tabela 33: Léxico 30 – Cadastrar (L30)</p></font>

<center>

| L30       | Descrição                                                 |
| :-:       | :-:                                                       |
| **Termo** | Cadastrar                                                 |
| **Tipo**  | Verbo                                                     |
| **Impacto** | <p>Permite que informações sejam registradas no sistema.</p><p>O sistema pode utilizar as informações registradas em funcionalidades futuras.</p><p>O usuário pode acessar as informações registradas posteriormente.</p> |
| **Noção** | <p>Ação do usuário de inserir dados ou informações no sistema para identificação, armazenamento e uso posterior.</p> |
| **Sinônimos** | <p>Registrar, Inserir, Adicionar</p>                   |
| **Autor** | [Danielle Soares](https://github.com/danielle-soaress)  |

</center>

<font size="2"><p style="text-align: center">Fonte: [Danielle Soares](https://github.com/danielle-soaress)</p></font>

---

## Requisito IS09

---

### L31: Exibir informações detalhadas

O L31, apresentado na tabela 34, utiliza o seguinte requisito não implementado: O aplicativo deve exibir informações detalhadas sobre o histórico de movimentações financeiras(<a href ="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#requisitos-funcionais">IS09</a>)

<font size="3"><p style="text-align: center">Tabela 34: Léxico 31 – Exibir informações detalhadas (L31)</p></font>

<center>

| L31 | Descrição | 
| :-:       | :-:            |
| **Termo** | Exibir informações detalhadas | 
| **Tipo** | Verbo | 
| **Impacto** |  O sistema consulta o banco de dados para recuperar os registros relacionados à movimentação financeira selecionada. <br> O sistema abre uma nova aba que apresenta as informações detalhadas.  | 
| **Noção** | Tarefa realizada pelo sistema. <br> Acontece quando o usuário seleciona uma transação no histórico de movimentações financeiras. <br> Sistema verifica se os dados das movimentações financeiras estão registrados. | 
| **Sinônimos** | Mostrar informações detalhada | 
| **Autor** | [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa) | 

</center>

<font size="2"><p style="text-align: center">Fonte: [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa)</p></font>

---

### L32: Informações detalhadas

O L32, apresentado na tabela 35, utiliza o seguinte requisito não implementado: O aplicativo deve exibir informações detalhadas sobre o histórico de movimentações financeiras(<a href ="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#requisitos-funcionais">IS09</a>)


<font size="3"><p style="text-align: center">Tabela 35: Léxico 32 – Informações detalhadas (L32)</p></font>

<center>

| L32 | Descrição | 
| :-:       | :-:            |
| **Termo** | Informações detalhadas | 
| **Tipo** | Objeto | 
| **Impacto** | Podem ser exibidas ao usuário, armazenadas e consultadas. | 
| **Noção** | Conjunto de dados de uma movimentação financeira. <br> São consultadas no histórico de movimentações financeiras. | 
| **Sinônimos** | Dados específicos <br> informações completas | 
| **Autor** | [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa) | 

</center>

<font size="2"><p style="text-align: center">Fonte: [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa)</p></font>

---

### L33: Histórico de movimentações financeiras

O L33, apresentado na tabela 36, utiliza o seguinte requisito não implementado: O aplicativo deve exibir informações detalhadas sobre o histórico de movimentações financeiras(<a href ="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#requisitos-funcionais">IS09</a>)

<font size="3"><p style="text-align: center">Tabela 36: Léxico 33 – Histórico de movimentações financeiras (L33)</p></font>

<center>

| L33 | Descrição | 
| :-:       | :-:            |
| **Termo** | Histórico de movimentações financeiras | 
| **Tipo** | Objeto | 
| **Impacto** | Podem ser exibidas ao usuário, consultado e filtrado por data. | 
| **Noção** | Registros de movimentações financeiras realizadas pelo usuário ao longo do tempo. <br> Pode exibir informações detalhadas das movimentações financeiras. | 
| **Sinônimos** | Extrato, Registro de transações, Lista de movimentações. | 
| **Autor** | [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa) | 

</center>

<font size="2"><p style="text-align: center">Fonte: [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa)</p></font>

---

## Requisito IS10

---

### L34: Filtrar

<center>

O L34, apresentado na tabela 37, utiliza o seguinte requisito não implementado: O aplicativo deve permitir o filtro do extrato por data (mês e ano) 
(<a href ="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#requisitos-funcionais">IS10</a>)

<font size="3"><p style="text-align: center">Tabela 37: Léxico 34 – Filtrar (L34)</p></font>

| L34 | Descrição | 
| :-:       | :-:            |
| **Termo** | Filtrar | 
| **Tipo** | Verbo | 
| **Impacto** | Permite que o usuário restrinja as movimentações exibidas no histórico de movimentações financeiras com base na data(mês e ano). | 
| **Noção** | Tarefa realizada pelo usuário. <br> Acontece quando o usuário seleciona uma data(mês e ano) específico. <br> sistema valida a data selecionada. | 
| **Sinônimos** | Aplicar, Buscar | 
| **Autor** | [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa) | 

</center>

<font size="2"><p style="text-align: center">Fonte: [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa)</p></font>

---

## Requisito IS08

---

### L35: Bloqueado

O léxico L35 utiliza o requisito funcional IS08 (O aplicativo deve fornecer informações sobre saques bloqueados e os motivos do bloqueio). Esse léxico é detalhado na tabela abaixo:

<font size="3"><p style="text-align: center">Tabela 38: Léxico 35 – Bloqueado (L35)</p></font>

<center>

| L35       | Descrição                                                 |
| :-:       | :-:                                                       |
| **Termo** | Bloqueado                                                |
| **Tipo**  | Estado                                                   |
| **Impacto** | <p>A ação ou operação (ex: saque) não pode ser realizada até que o bloqueio seja removido.</p><p>Pode afetar a disponibilidade de recursos ao usuário.</p> |
| **Noção** | <p>Situação em que um recurso ou função está temporariamente indisponível para uso devido a restrições, impedimentos legais, administrativos ou técnicos.</p> |
| **Sinônimos** | <p>Restrito, Suspenso, Inativo</p>                     |
| **Autor** | [Danielle Soares](https://github.com/danielle-soaress)  |

</center>

<font size="2"><p style="text-align: center">Fonte: [Danielle Soares](https://github.com/danielle-soaress)</p></font>

---

## Requisito IS13

---

### L36: Chat

O léxico L36 utiliza o requisito funcional não implementado IS13 (O aplicativo deve permitir que o usuário entre em contato com um assistente via chat). Esse léxico é detalhado na tabela abaixo:

<font size="3"><p style="text-align: center">Tabela 39: Léxico 36 – Chat (L36)</p></font>

<center>

| L36 | Descrição | 
| :-:       | :-:            |
| **Termo** | Chat | 
| **Tipo** | Objeto | 
| **Impacto** | - Permite a comunicação direta entre o usuário e um assistente virtual. <br> - Auxilia na resolução de dúvidas e problemas sem a necessidade de sair do aplicativo. <br> - Pode ser integrado a diferentes partes do sistema para oferecer suporte contextual. | 
| **Noção** | Canal de comunicação textual, em tempo real, por onde o usuário interage com um assistente para obter suporte, tirar dúvidas ou receber orientações. | 
| **Sinônimos** | Conversa, Atendimento Virtual, Suporte via mensagem | 
| **Autor** | [Marcelo Makoto](https://github.com/MM4k) | 

</center>

<font size="2"><p style="text-align: center">Fonte: [Marcelo Makoto](https://github.com/MM4k)</p></font>

---

### L37: Assistente Virtual

O léxico L37 utiliza o requisito funcional não implementado IS13 (O aplicativo deve permitir que o usuário entre em contato com um assistente via chat). Esse léxico é detalhado na tabela abaixo:

<font size="3"><p style="text-align: center">Tabela 40: Léxico 37 – Assistente Virtual (L37)</p></font>

<center>

| L37 | Descrição | 
| :-:       | :-:            |
| **Termo** | Assistente Virtual | 
| **Tipo** | Objeto | 
| **Impacto** | 	- Fornece respostas automáticas e orientações baseadas no contexto do usuário. <br> - Ajuda a reduzir o tempo de espera e a carga sobre o suporte humano. <br> - Pode ser integrado com outras funcionalidades para melhorar a experiência do usuário. | 
| **Noção** | Sistema automatizado que interage com o usuário via chat para fornecer suporte, esclarecer dúvidas e orientar sobre o uso do aplicativo. | 
| **Sinônimos** | Bot, Atendimento Automático, Agente Virtual | 
| **Autor** | [Marcelo Makoto](https://github.com/MM4k) | 

</center>

<font size="2"><p style="text-align: center">Fonte: [Marcelo Makoto](https://github.com/MM4k)</p></font>

---

### L38: Mensagem

O léxico L38 utiliza o requisito funcional não implementado IS13 (O aplicativo deve permitir que o usuário entre em contato com um assistente via chat). Esse léxico é detalhado na tabela abaixo:

<font size="3"><p style="text-align: center">Tabela 41: Léxico 38 – Mensagem (L38)</p></font>

<center>

| L38 | Descrição | 
| :-:       | :-:            |
| **Termo** | Mensagem | 
| **Tipo** | Objeto | 
| **Impacto** | 	- Permite a troca de informações entre usuário e assistente virtual. <br> - É a unidade básica de comunicação no chat. <br> - Pode conter perguntas, respostas, instruções ou links para funcionalidades. | 
| **Noção** | 	Texto enviado ou recebido na interface do chat que representa a comunicação entre o usuário e o assistente. | 
| **Sinônimos** | Texto, Comunicação | 
| **Autor** | [Marcelo Makoto](https://github.com/MM4k) | 

</center>

<font size="2"><p style="text-align: center">Fonte: [Marcelo Makoto](https://github.com/MM4k)</p></font>

---

## Requisito IS14

---

### L39: Buscar

O léxico L39 utiliza o requisito funcional não implementado IS14 (O aplicativo deve disponibilizar um campo de busca para facilitar a localização de funcionalidades). Esse léxico é detalhado na tabela abaixo:

<font size="3"><p style="text-align: center">Tabela 42: Léxico 39 – Buscar (L39)</p></font>

<center>

| L39 | Descrição | 
| :-:       | :-:            |
| **Termo** | Buscar | 
| **Tipo** | Verbo | 
| **Impacto** | - Facilita a localização de funcionalidades e informações dentro do aplicativo. <br> - Melhora a usabilidade ao reduzir o tempo de navegação. <br> - Permite que o usuário acesse diretamente conteúdos relevantes com base em palavras-chave. | 
| **Noção** | Ação de digitar um termo com o objetivo de encontrar funcionalidades ou conteúdos relacionados a ele no sistema. | 
| **Sinônimos** | Pesquisar, Procurar, Localizar | 
| **Autor** | [Marcelo Makoto](https://github.com/MM4k) | 

</center>

<font size="2"><p style="text-align: center">Fonte: [Marcelo Makoto](https://github.com/MM4k))</p></font>

---

### L40: Campo de Busca

O léxico L40 utiliza o requisito funcional não implementado IS14 (O aplicativo deve disponibilizar um campo de busca para facilitar a localização de funcionalidades). Esse léxico é detalhado na tabela abaixo:

<font size="3"><p style="text-align: center">Tabela 43: Léxico 40 – Campo de Busca (L40)</p></font>

<center>

| L40 | Descrição | 
| :-:       | :-:            |
| **Termo** | Campo de Busca | 
| **Tipo** | Objeto | 
| **Impacto** | - Interface que permite ao usuário digitar termos para localizar informações. <br> - Deve ser intuitivo e responsivo para garantir usabilidade. <br> - Facilita a navegação e o acesso a conteúdos. | 
| **Noção** | Área ou elemento da interface do aplicativo onde o usuário insere palavras-chave para realizar consultas no sistema. | 
| **Sinônimos** | Barra de Pesquisa, Caixa de Pesquisa, Pesquisa de Texto | 
| **Autor** | [Marcelo Makoto](https://github.com/MM4k) | 

</center>

<font size="2"><p style="text-align: center">Fonte: [Marcelo Makoto](https://github.com/MM4k))</p></font>

---

### L41: Termo de Pesquisa

O léxico L41 utiliza o requisito funcional não implementado IS14 (O aplicativo deve disponibilizar um campo de busca para facilitar a localização de funcionalidades). Esse léxico é detalhado na tabela abaixo:

<font size="3"><p style="text-align: center">Tabela 44: Léxico 41 – Termo de Pesquisa (L41)</p></font>

<center>

| L41 | Descrição | 
| :-:       | :-:            |
| **Termo** | Termo de Pesquisa | 
| **Tipo** | Objeto | 
| **Impacto** | - Define o conteúdo que o usuário deseja encontrar. <br> - A precisão do termo influencia na relevância dos resultados. <br> - Pode ser ampliado com sugestões para melhorar a busca. | 
| **Noção** | Palavra ou conjunto de palavras digitadas pelo usuário no campo de busca para localizar funcionalidades ou informações. | 
| **Sinônimos** | Palavra-chave, Consulta, Pesquisa | 
| **Autor** | [Marcelo Makoto](https://github.com/MM4k) | 

</center>

<font size="2"><p style="text-align: center">Fonte: [Marcelo Makoto](https://github.com/MM4k))</p></font>

---

## Requisito IS16

---

### L42: Acessar Ajuda

O léxico L42 utiliza o requisito funcional não implementado IS16 (O aplicativo deve conter uma seção de ajuda com orientações sobre o uso do aplicativo). Esse léxico é detalhado na tabela abaixo:

<font size="3"><p style="text-align: center">Tabela 45: Léxico 42 – Acessar Ajuda</p></font>

| L42 | Descrição | 
| :-: | :-: |
| **Termo** | Acessar Ajuda | 
| **Tipo** | Verbo | 
| **Impacto** | - Muda o sistema para uma nova página (offline) | 
| **Noção** | Ação de entrar na página que lista as possíveis dúvidas do usuário. | 
| **Sinônimos** | Entrar na página de ajuda | 
| **Autor** | [Eduardo de Pina](https://github.com/eduardodpms) | 

<font size="2"><p style="text-align: center">Fonte: [Eduardo de Pina](https://github.com/eduardodpms)</p></font>

---

### L43 - Procurar Dúvida

O léxico L43 utiliza o requisito funcional não implementado IS16 (O aplicativo deve conter uma seção de ajuda com orientações sobre o uso do aplicativo). Esse léxico é detalhado na tabela abaixo:

<font size="3"><p style="text-align: center">Tabela 46: Léxico 43 – Procurar Dúvida</p></font>

| L43 | Descrição | 
| :-: | :-: |
| **Termo** | Procurar Dúvida | 
| **Tipo** | Verbo | 
| **Impacto** | - Fornece ao usuário uma noção sobre onde ele pode se informar a respeito do app.<br>- Leva para a página de explicações, na qual o usuário terá acesso a todo o conhecimento que deseja. | 
| **Noção** | Ação de procurar, na lista de dúvidas ou na caixa de busca, a dúvida que se deseja sanar. | 
| **Sinônimos** | Localizar o questionamento, procurar a explicação. | 
| **Autor** | [Eduardo de Pina](https://github.com/eduardodpms) | 

<font size="2"><p style="text-align: center">Fonte: [Eduardo de Pina](https://github.com/eduardodpms)</p></font>

---

## Requisito ST07

---

### L44: Requerer Guia

O léxico L44 utiliza o requisito funcional não implementado ST07 (O aplicativo deve disponibilizar um guia interativo para orientar o usuário durante o processo). Esse léxico é detalhado na tabela abaixo:

<font size="3"><p style="text-align: center">Tabela 47: Léxico 44 – Requerer Guia</p></font>

| L44 | Descrição | 
| :-: | :-: |
| **Termo** | Requerer Guia | 
| **Tipo** | Verbo | 
| **Impacto** | - O sistema inicia um pipeline de orientação ao usuário<br>- A interface se torna mais explicativa e direta.<br>- O usuário compreende que ativou um modo de auxílio para ele. | 
| **Noção** | Ação de solicitar um auxílio do próprio aplicativo na realização de uma ação. | 
| **Sinônimos** | Solicitar ajuda, pedir orientação. | 
| **Autor** | [Eduardo de Pina](https://github.com/eduardodpms) | 

<font size="2"><p style="text-align: center">Fonte: [Eduardo de Pina](https://github.com/eduardodpms)</p></font>

### L45: Seguir Guia

O léxico L45 utiliza o requisito funcional não implementado ST07 (O aplicativo deve disponibilizar um guia interativo para orientar o usuário durante o processo). Esse léxico é detalhado na tabela abaixo:

<font size="3"><p style="text-align: center">Tabela 48: Léxico 45 – Seguir Guia</p></font>

| L45 | Descrição | 
| :-: | :-: |
| **Termo** | Seguir Guia | 
| **Tipo** | Verbo | 
| **Impacto** | - Permite que o usuário acesse, como acessaria sem o guia, todas as funcionalidades.<br>- O usuário aprende como realizar aquela ação sem a ajuda do guia. | 
| **Noção** | Processo de acompanhar a guia fornecida, seguindo os passos e as explicações. | 
| **Sinônimos** | Acompanhar a explicação, trilhar os passos. | 
| **Autor** | [Eduardo de Pina](https://github.com/eduardodpms) | 

<font size="2"><p style="text-align: center">Fonte: [Eduardo de Pina](https://github.com/eduardodpms)</p></font>




## Bibliografia

> SERRANO, Milene; SERRANO, Maurício. Requisitos – Aula 10. UnB, 2025. Disponível em: <[https://aprender3.unb.br/pluginfile.php/3096108/mod_resource/content/1/Aula%2010.pdf](https://aprender3.unb.br/pluginfile.php/3096108/mod_resource/content/1/Aula%2010.pdf)>. Acesso em: 17 de maio 2025. p. 12–20.

## Histórico de Versão

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| :-: | :-: | :-: | :-: | :-: |
| `1.0` | 16/05/2025 | Criação do documento | [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa) | [Danielle Soares](https://github.com/danielle-soaress) |
| `1.1` | 17/05/2025 | Inserção dos léxicos 6 e 9 | [Danielle Soares](https://github.com/danielle-soaress)  | [Marcelo Makoto](https://github.com/MM4k) |
| `1.2` | 17/05/2025 | Adicionando léxicos 1 e 2 | [Enzo Emir](https://github.com/EnzoEmir)  | [Marcelo Makoto](https://github.com/MM4k) |
| `1.3` | 17/05/2025 | Adição dos léxicos 10 e 11 | [Marcelo Makoto](https://github.com/MM4k)  | [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa) |
| `1.4` | 17/05/2025 | Adição dos léxicos 07 e 08 | [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa) | [Marcelo Makoto](https://github.com/MM4k) |
| `1.5` | 17/05/2025 | Adição da introdução e metodologia | [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa) | [Marcelo Makoto](https://github.com/MM4k) |
| `1.6` | 17/05/2025 | Adição de mais léxicos para os requisitos IS13 e IS14 | [Marcelo Makoto](https://github.com/MM4k)  | [Victor Pontual](https://github.com/VictorPontual) |
| `1.7` | 17/05/2025 | Adição de mais léxicos para os requisitos IS06 e IS07 | [Victor Pontual](https://github.com/VictorPontual)  | [Marcelo Makoto](https://github.com/MM4k) |
| `1.8` | 18/05/2025 | Reformulando documento | [Enzo Emir](https://github.com/EnzoEmir) | [Maria Eduarda](https://github.com/dudaa28) |
| `1.9` | 18/05/2025 | Adição de léxicos 14 a 19 | [Maria Eduarda](https://github.com/dudaa28) | [Eduardo de Pina](https://github.com/eduardodpms) |
| `2.0` | 18/05/2025 | Atualização do Documento | [Maria Eduarda](https://github.com/dudaa28) | [Eduardo de Pina](https://github.com/eduardodpms) |
| `2.1` | 18/05/2025 | Adição de léxicos referentes aos requisitos faltantes | [Eduardo de Pina](https://github.com/eduardodpms) | [Marcelo Makoto](https://github.com/MM4k) |
| `2.2` | 18/05/2025 | Mudança de estilo da página | [Marcelo Makoto](https://github.com/MM4k) | [Eduardo de Pina](https://github.com/eduardodpms) |
| `2.3` | 18/05/2025 | Adicionando Hyper Links | [Enzo Emir](https://github.com/EnzoEmir) | - |