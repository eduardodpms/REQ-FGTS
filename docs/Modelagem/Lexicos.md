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
      <td> - </td>
      <td> - </td>
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

## L01: Requisito EN02

## [Consultar Status](#consultar-status)
- **Tipo:** Verbo  
- **Descrição:** Ação de verificar o andamento do processo de saque no aplicativo, incluindo a leitura do status atual e de um comentário explicativo.  
- **Objetos Envolvidos:** [Status do Saque](#status-do-saque), [Comentário Explicativo](#comentário-explicativo)  
- **Estado Resultante:** [Status Visualizado](#status-visualizado)

---

## [Status do Saque](#status-do-saque)
- **Tipo:** Objeto  
- **Descrição:** Informação que indica a etapa atual do processo de saque (ex: Em análise, Aprovado, Efetuado).  
- **Estados Possíveis:** [Saque em Análise](#saque-em-análise), [Saque Aprovado](#saque-aprovado), [Saque Efetuado](#saque-efetuado), [Saque Pendente](#saque-pendente), [Saque Cancelado](#saque-cancelado)

---

## [Comentário Explicativo](#comentário-explicativo)
- **Tipo:** Objeto  
- **Descrição:** Texto complementar que esclarece o [Status do Saque](#status-do-saque) para o usuário com linguagem acessível.  
- **Estados Possíveis:** Atualizado, Desatualizado

---

## [Saque em Análise](#saque-em-análise)
- **Tipo:** Estado  
- **Descrição:** Estado do sistema após a solicitação de saque, indicando que o pedido está sendo avaliado.

---

## [Saque Aprovado](#saque-aprovado)
- **Tipo:** Estado  
- **Descrição:** Estado que indica aprovação do pedido de saque.

---

## [Saque Efetuado](#saque-efetuado)
- **Tipo:** Estado  
- **Descrição:** Estado final do processo, indicando que o valor foi liberado.

---

## [Saque Pendente](#saque-pendente)
- **Tipo:** Estado  
- **Descrição:** Estado que indica que o saque aguarda alguma ação do usuário ou do sistema.

---

## [Saque Cancelado](#saque-cancelado)
- **Tipo:** Estado  
- **Descrição:** Estado que indica que o pedido de saque foi cancelado.

---

## [Status Visualizado](#status-visualizado)
- **Tipo:** Estado  
- **Descrição:** Estado alcançado após o usuário acessar a tela de acompanhamento do saque.

<font size="2"><p style="text-align: center">Fonte: [Enzo Emir](https://github.com/EnzoEmir)</p></font>

## L02: Requisito EN03

## [Visualizar Data Prevista](#visualizar-data-prevista)
- **Tipo:** Verbo  
- **Descrição:** Ação de acessar a previsão de liberação dos valores solicitados para saque.  
- **Objetos Envolvidos:** [Data Prevista](#data-prevista), [Notificação](#notificação)  
- **Estado Resultante:** [Data Visualizada](#data-visualizada)

---

## [Data Prevista](#data-prevista)
- **Tipo:** Objeto  
- **Descrição:** Informação que apresenta ao usuário a data estimada para liberação dos valores.  
- **Estados Possíveis:** Definida, Alterada, Expirada

---

## [Notificação](#notificação)
- **Tipo:** Objeto  
- **Descrição:** Mensagem enviada ao usuário para informar alterações no [Status do Saque](#status-do-saque) ou na [Data Prevista](#data-prevista).  
- **Estados Possíveis:** Enviada, Lida, Pendente

---

## [Data Visualizada](#data-visualizada)
- **Tipo:** Estado  
- **Descrição:** Estado atingido após o usuário acessar a previsão de liberação dos valores.

<font size="2"><p style="text-align: center">Fonte: [Enzo Emir](https://github.com/EnzoEmir)</p></font>

## L03: Trocar pelo termo


<font size="3"><p style="text-align: center">Tabela X: Léxico 03 – Trocar pelo termo (L03)</p></font>

| L03 | Descrição | 
| :-:       | :-:            |
| **Termo** |  | 
| **Tipo** |  | 
| **Impacto** |  | 
| **Noção** |  | 
| **Sinônimos** |  | 
| **Autor** | [Maria Eduarda](https://github.com/dudaa28) | 

<font size="2"><p style="text-align: center">Fonte: [Maria Eduarda](https://github.com/dudaa28)</p></font>

---

## Requisito IS06

## [Cancelar Solicitação](#cancelar-solicitação)

| LXX           | Descrição                                                                                                                                                                     |
| ------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Termo**     | Cancelar Solicitação                                                                                                                                                          |
| **Tipo**      | Verbo                                                                                                                                                                         |
| **Impacto**   | Permite que o usuário interrompa uma solicitação de saque ativa, evitando que ela seja processada ou liberada.                                                                |
| **Noção**     | Ação executada pelo usuário para cancelar um pedido de saque em andamento. O sistema verifica a possibilidade de cancelamento e atualiza o status conforme a ação do usuário. |
| **Sinônimos** | Anular pedido, Revogar solicitação                                                                                                                                            |
| **Autor**     | [Victor Pontual](https://github.com/VictorPontual)                                                                                                                            |

---

## [Solicitação de Saque](#solicitação-de-saque)

| LXX           | Descrição                                                                                                      |
| ------------- | -------------------------------------------------------------------------------------------------------------- |
| **Termo**     | Solicitação de Saque                                                                                           |
| **Tipo**      | Objeto                                                                                                         |
| **Impacto**   | Representa o pedido formal do usuário para saque de valores do FGTS.                                           |
| **Noção**     | Documento digital que contém as informações necessárias para a liberação dos valores solicitados pelo usuário. |
| **Sinônimos** | Pedido de saque, Requisição de saque                                                                           |
| **Autor**     | [Victor Pontual](https://github.com/VictorPontual)                                                             |

---

## [Confirmação de Cancelamento](#confirmação-de-cancelamento)

| LXX           | Descrição                                                                                                                         |
| ------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| **Termo**     | Confirmação de Cancelamento                                                                                                       |
| **Tipo**      | Objeto                                                                                                                            |
| **Impacto**   | Garante que o usuário valide sua intenção de cancelar a solicitação de saque, evitando cancelamentos acidentais.                  |
| **Noção**     | Ato do usuário de confirmar a operação de cancelamento após ser solicitado pelo sistema, assegurando que a ação seja intencional. |
| **Sinônimos** | Validação de cancelamento, Confirmação de ação                                                                                    |
| **Autor**     | [Victor Pontual](https://github.com/VictorPontual)                                                                                |


---

## [Solicitação Ativa](#solicitação-ativa)

| LXX           | Descrição                                                                                                           |
| ------------- | ------------------------------------------------------------------------------------------------------------------- |
| **Termo**     | Solicitação Ativa                                                                                                   |
| **Tipo**      | Estado                                                                                                              |
| **Impacto**   | Indica que a solicitação de saque está vigente e pode ser modificada ou cancelada pelo usuário.                     |
| **Noção**     | Estado em que a solicitação de saque foi feita e ainda está em processamento, aguardando conclusão ou cancelamento. |
| **Sinônimos** | Pedido em andamento, Solicitação vigente                                                                            |
| **Autor**     | [Victor Pontual](https://github.com/VictorPontual)                                                                  |

---

## [Solicitação Cancelada](#solicitação-cancelada)

| LXX           | Descrição                                                                                              |
| ------------- | ------------------------------------------------------------------------------------------------------ |
| **Termo**     | Solicitação Cancelada                                                                                  |
| **Tipo**      | Estado                                                                                                 |
| **Impacto**   | Indica que a solicitação de saque foi anulada e não será processada pelo sistema.                      |
| **Noção**     | Estado final em que o pedido de saque foi oficialmente cancelado pelo usuário e registrado no sistema. |
| **Sinônimos** | Pedido cancelado, Requisição anulada                                                                   |
| **Autor**     | [Victor Pontual](https://github.com/VictorPontual)                                                     |

---

## [Solicitação Processada](#solicitação-processada)

| LXX           | Descrição                                                                                                              |
| ------------- | ---------------------------------------------------------------------------------------------------------------------- |
| **Termo**     | Solicitação Processada                                                                                                 |
| **Tipo**      | Estado                                                                                                                 |
| **Impacto**   | Indica que a solicitação de saque foi analisada e concluída pelo sistema, não podendo mais ser cancelada pelo usuário. |
| **Noção**     | Estado final onde o pedido de saque foi processado e encaminhado para liberação dos valores ou rejeição.               |
| **Sinônimos** | Pedido concluído, Solicitação finalizada                                                                               |
| **Autor**     | [Victor Pontual](https://github.com/VictorPontual)                                                                     |

<font size="2"><p style="text-align: center">Fonte: [Victor Pontual](https://github.com/VictorPontual)</p></font>

## Requisito IS07

## [Filtrar Saques por Tipo](#filtrar-saques-por-tipo)

| LXX           | Descrição                                                                                                                                 |
| ------------- | ----------------------------------------------------------------------------------------------------------------------------------------- |
| **Termo**     | Filtrar Saques por Tipo                                                                                                                   |
| **Tipo**      | Verbo                                                                                                                                     |
| **Impacto**   | Permite que o usuário restrinja a visualização dos saques exibidos no histórico com base no tipo (ex.: aniversário, doença, falecimento). |
| **Noção**     | Ação do usuário de selecionar um critério de tipo para que o sistema exiba apenas os saques correspondentes àquela categoria.             |
| **Sinônimos** | Aplicar filtro, Selecionar tipo, Restringir visualização                                                                                  |
| **Autor**     | [Victor Pontual](https://github.com/VictorPontual)                                                                                        |


---

## [Lista de Saques](#lista-de-saques)

| LXX           | Descrição                                                                                                                              |
| ------------- | -------------------------------------------------------------------------------------------------------------------------------------- |
| **Termo**     | Lista de Saques                                                                                                                        |
| **Tipo**      | Objeto                                                                                                                                 |
| **Impacto**   | Representa o conjunto de registros das solicitações de saque do usuário, possibilitando a consulta e gerenciamento dessas informações. |
| **Noção**     | Coleção organizada dos pedidos de saque efetuados pelo usuário, incluindo detalhes como tipo, valor, data e status de cada saque.      |
| **Sinônimos** | Histórico de saques, Registro de saques                                                                                                |
| **Autor**     | [Victor Pontual](https://github.com/VictorPontual)                                                                                     |


---

## [Filtro de Tipo](#filtro-de-tipo)

| LXX           | Descrição                                                                                                                           |
| ------------- | ----------------------------------------------------------------------------------------------------------------------------------- |
| **Termo**     | Filtro de Tipo                                                                                                                      |
| **Tipo**      | Objeto                                                                                                                              |
| **Impacto**   | Permite segmentar ou restringir a visualização da lista de saques com base no tipo selecionado pelo usuário.                        |
| **Noção**     | Critério utilizado para classificar e apresentar apenas os saques que pertencem a uma categoria específica (ex: saque-aniversário). |
| **Sinônimos** | Critério de seleção, Opção de filtro                                                                                                |
| **Autor**     | [Victor Pontual](https://github.com/VictorPontual)                                                                                  |

---

## [Lista Filtrada](#lista-filtrada)

| LXX           | Descrição                                                                                                                      |
| ------------- | ------------------------------------------------------------------------------------------------------------------------------ |
| **Termo**     | Lista Filtrada                                                                                                                 |
| **Tipo**      | Estado                                                                                                                         |
| **Impacto**   | Representa o estado em que a lista de saques exibe somente os registros que correspondem aos critérios de filtro aplicados.    |
| **Noção**     | Visualização da lista de saques reduzida e organizada conforme a seleção feita pelo usuário para facilitar o acesso e análise. |
| **Sinônimos** | Lista segmentada, Resultado filtrado                                                                                           |
| **Autor**     | [Victor Pontual](https://github.com/VictorPontual)                                                                             |

---

<font size="2"><p style="text-align: center">Fonte: [Victor Pontual](https://github.com/VictorPontual)</p></font>

## L06: Cadastrar

<font size="3"><p style="text-align: center">Tabela X: Léxico 06 – Cadastrar (L06)</p></font>

<center>

| L06       | Descrição                                                 |
| :-:       | :-:                                                       |
| **Termo** | Cadastrar                                                 |
| **Tipo**  | Verbo                                                     |
| **Impacto** | <p>Permite que informações sejam registradas no sistema.</p><p>O sistema pode utilizar as informações registradas em funcionalidades futuras.</p><p>O usuário pode acessar as informações registradas posteriormente.</p> |
| **Noção** | <p>Ação do usuário de inserir dados ou informações no sistema para identificação, armazenamento e uso posterior.</p> |
| **Sinônimos** | <p>Registrar, Inserir, Adicionar</p>                   |
| **Autor** | [Danielle Soares](https://github.com/danielle-soaress)  |

</center>

<font size="2"><p style="text-align: center">Fonte: [Danielle Soares](https://github.com/danielle-soaress)</p></font>

## L07: Exibir informações detalhadas

O sétimo léxico, apresentado na tabela X, utiliza o seguinte requisito não implementado: O aplicativo deve exibir informações detalhadas sobre o histórico de movimentações financeiras(<a href ="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#requisitos-funcionais">RF12</a>)

<font size="3"><p style="text-align: center">Tabela X: Léxico 07 – Exibir informações detalhadas (L07)</p></font>

<center>

| L07 | Descrição | 
| :-:       | :-:            |
| **Termo** | Exibir informações detalhadas | 
| **Tipo** | Verbo | 
| **Impacto** |  O sistema consulta o banco de dados para recuperar os registros relacionados à movimentação financeira selecionada. <br> O sistema abre uma nova aba que apresenta as informações detalhadas.  | 
| **Noção** | Tarefa realizada pelo sistema. <br> Acontece quando o usuário seleciona uma transação no histórico de movimentações financeiras. <br> Sistema verifica se os dados das movimentações financeiras estão registrados. | 
| **Sinônimos** | Mostrar informações detalhada | 
| **Autor** | [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa) | 

</center>

<font size="2"><p style="text-align: center">Fonte: [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa)</p></font>

## L08: Informações detalhadas

O oitavo léxico, apresentado na tabela X, utiliza o seguinte requisito não implementado: O aplicativo deve exibir informações detalhadas sobre o histórico de movimentações financeiras(<a href ="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#requisitos-funcionais">RF12</a>)


<font size="3"><p style="text-align: center">Tabela X: Léxico 08 – Informações detalhadas (L08)</p></font>

<center>

| L08 | Descrição | 
| :-:       | :-:            |
| **Termo** | Informações detalhadas | 
| **Tipo** | Objeto | 
| **Impacto** | Podem ser exibidas ao usuário, armazenadas e consultadas. | 
| **Noção** | Conjunto de dados de uma movimentação financeira. <br> São consultadas no histórico de movimentações financeiras. | 
| **Sinônimos** | Dados específicos <br> informações completas | 
| **Autor** | [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa) | 

</center>

<font size="2"><p style="text-align: center">Fonte: [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa)</p></font>

## L09: Histórico de movimentações financeiras

O nono léxico, apresentado na tabela X, utiliza o seguinte requisito não implementado: O aplicativo deve exibir informações detalhadas sobre o histórico de movimentações financeiras(<a href ="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#requisitos-funcionais">RF12</a>)

<font size="3"><p style="text-align: center">Tabela X: Léxico 09 – Histórico de movimentações financeiras (L09)</p></font>

<center>

| L09 | Descrição | 
| :-:       | :-:            |
| **Termo** | Histórico de movimentações financeiras | 
| **Tipo** | Objeto | 
| **Impacto** | Podem ser exibidas ao usuário, consultado e filtrado por data. | 
| **Noção** | Registros de movimentações financeiras realizadas pelo usuário ao longo do tempo. <br> Pode exibir informações detalhadas das movimentações financeiras. | 
| **Sinônimos** | Extrato, Registro de transações, Lista de movimentações. | 
| **Autor** | [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa) | 

</center>

<font size="2"><p style="text-align: center">Fonte: [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa)</p></font>

## L010: Histórico de movimentações financeiras

<center>

O décimo léxico, apresentado na tabela X, utiliza o seguinte requisito não implementado: O aplicativo deve permitir o filtro do extrato por data (mês e ano) 
(<a href ="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#requisitos-funcionais">RF13</a>)

<font size="3"><p style="text-align: center">Tabela X: Léxico 010 – Filtrar (L010)</p></font>

| L10 | Descrição | 
| :-:       | :-:            |
| **Termo** | Filtrar | 
| **Tipo** | Verbo | 
| **Impacto** | Permite que o usuário restrinja as movimentações exibidas no histórico de movimentações financeiras com base na data(mês e ano). | 
| **Noção** | Tarefa realizada pelo usuário. <br> Acontece quando o usuário seleciona uma data(mês e ano) específico. <br> sistema valida a data selecionada. | 
| **Sinônimos** | Aplicar, Buscar | 
| **Autor** | [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa) | 

</center>

<font size="2"><p style="text-align: center">Fonte: [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa)</p></font>

## L09: Bloqueado


<font size="3"><p style="text-align: center">Tabela X: Léxico 09 – Bloqueado (L09)</p></font>

<center>

| L09       | Descrição                                                 |
| :-:       | :-:                                                       |
| **Termo** | Bloqueado                                                |
| **Tipo**  | Estado                                                   |
| **Impacto** | <p>A ação ou operação (ex: saque) não pode ser realizada até que o bloqueio seja removido.</p><p>Pode afetar a disponibilidade de recursos ao usuário.</p> |
| **Noção** | <p>Situação em que um recurso ou função está temporariamente indisponível para uso devido a restrições, impedimentos legais, administrativos ou técnicos.</p> |
| **Sinônimos** | <p>Restrito, Suspenso, Inativo</p>                     |
| **Autor** | [Danielle Soares](https://github.com/danielle-soaress)  |

</center>

<font size="2"><p style="text-align: center">Fonte: [Danielle Soares](https://github.com/danielle-soaress)</p></font>

## LXX: Chat

O léxico XX utiliza o requisito funcional não implementado IS13 (O aplicativo deve permitir que o usuário entre em contato com um assistente via chat). Esse léxico é detalhado na tabela abaixo:

<font size="3"><p style="text-align: center">Tabela X: Léxico XX – Chat (LXX)</p></font>

<center>

| LXX | Descrição | 
| :-:       | :-:            |
| **Termo** | Chat | 
| **Tipo** | Substantivo | 
| **Impacto** | - Permite a comunicação direta entre o usuário e um assistente virtual. <br> - Auxilia na resolução de dúvidas e problemas sem a necessidade de sair do aplicativo. <br> - Pode ser integrado a diferentes partes do sistema para oferecer suporte contextual. | 
| **Noção** | Canal de comunicação textual, em tempo real, por onde o usuário interage com um assistente para obter suporte, tirar dúvidas ou receber orientações. | 
| **Sinônimos** | Conversa, Atendimento Virtual, Suporte via mensagem | 
| **Autor** | [Marcelo Makoto](https://github.com/MM4k) | 

</center>

<font size="2"><p style="text-align: center">Fonte: [Marcelo Makoto](https://github.com/MM4k)</p></font>

## LXX: Assistente Virtual

O léxico XX utiliza o requisito funcional não implementado IS13 (O aplicativo deve permitir que o usuário entre em contato com um assistente via chat). Esse léxico é detalhado na tabela abaixo:

<font size="3"><p style="text-align: center">Tabela X: Léxico XX – Assistente Virtual (LXX)</p></font>

<center>

| LXX | Descrição | 
| :-:       | :-:            |
| **Termo** | Assistente Virtual | 
| **Tipo** | Substantivo | 
| **Impacto** | 	- Fornece respostas automáticas e orientações baseadas no contexto do usuário. <br> - Ajuda a reduzir o tempo de espera e a carga sobre o suporte humano. <br> - Pode ser integrado com outras funcionalidades para melhorar a experiência do usuário. | 
| **Noção** | Sistema automatizado que interage com o usuário via chat para fornecer suporte, esclarecer dúvidas e orientar sobre o uso do aplicativo. | 
| **Sinônimos** | Bot, Atendimento Automático, Agente Virtual | 
| **Autor** | [Marcelo Makoto](https://github.com/MM4k) | 

</center>

<font size="2"><p style="text-align: center">Fonte: [Marcelo Makoto](https://github.com/MM4k)</p></font>

## LXX: Mensagem

O léxico XX utiliza o requisito funcional não implementado IS13 (O aplicativo deve permitir que o usuário entre em contato com um assistente via chat). Esse léxico é detalhado na tabela abaixo:

<font size="3"><p style="text-align: center">Tabela X: Léxico XX – Mensagem (LXX)</p></font>

<center>

| LXX | Descrição | 
| :-:       | :-:            |
| **Termo** | Mensagem | 
| **Tipo** | Substantivo | 
| **Impacto** | 	- Permite a troca de informações entre usuário e assistente virtual. <br> - É a unidade básica de comunicação no chat. <br> - Pode conter perguntas, respostas, instruções ou links para funcionalidades. | 
| **Noção** | 	Texto enviado ou recebido na interface do chat que representa a comunicação entre o usuário e o assistente. | 
| **Sinônimos** | Texto, Comunicação | 
| **Autor** | [Marcelo Makoto](https://github.com/MM4k) | 

</center>

<font size="2"><p style="text-align: center">Fonte: [Marcelo Makoto](https://github.com/MM4k)</p></font>

## LXX: Buscar

O léxico XX utiliza o requisito funcional não implementado IS14 (O aplicativo deve disponibilizar um campo de busca para facilitar a localização de funcionalidades). Esse léxico é detalhado na tabela abaixo:

<font size="3"><p style="text-align: center">Tabela X: Léxico XX – Buscar (LXX)</p></font>

<center>

| LXX | Descrição | 
| :-:       | :-:            |
| **Termo** | Buscar | 
| **Tipo** | Verbo | 
| **Impacto** | - Facilita a localização de funcionalidades e informações dentro do aplicativo. <br> - Melhora a usabilidade ao reduzir o tempo de navegação. <br> - Permite que o usuário acesse diretamente conteúdos relevantes com base em palavras-chave. | 
| **Noção** | Ação de digitar um termo com o objetivo de encontrar funcionalidades ou conteúdos relacionados a ele no sistema. | 
| **Sinônimos** | Pesquisar, Procurar, Localizar | 
| **Autor** | [Marcelo Makoto](https://github.com/MM4k) | 

</center>

<font size="2"><p style="text-align: center">Fonte: [Marcelo Makoto](https://github.com/MM4k))</p></font>

## LXX: Campo de Busca

O léxico XX utiliza o requisito funcional não implementado IS14 (O aplicativo deve disponibilizar um campo de busca para facilitar a localização de funcionalidades). Esse léxico é detalhado na tabela abaixo:

<font size="3"><p style="text-align: center">Tabela X: Léxico XX – Campo de Busca (LXX)</p></font>

<center>

| LXX | Descrição | 
| :-:       | :-:            |
| **Termo** | Campo de Busca | 
| **Tipo** | Substantivo | 
| **Impacto** | - Interface que permite ao usuário digitar termos para localizar informações. <br> - Deve ser intuitivo e responsivo para garantir usabilidade. <br> - Facilita a navegação e o acesso a conteúdos. | 
| **Noção** | Área ou elemento da interface do aplicativo onde o usuário insere palavras-chave para realizar consultas no sistema. | 
| **Sinônimos** | Barra de Pesquisa, Caixa de Pesquisa, Pesquisa de Texto | 
| **Autor** | [Marcelo Makoto](https://github.com/MM4k) | 

</center>

<font size="2"><p style="text-align: center">Fonte: [Marcelo Makoto](https://github.com/MM4k))</p></font>

## LXX: Termo de Pesquisa

O léxico XX utiliza o requisito funcional não implementado IS14 (O aplicativo deve disponibilizar um campo de busca para facilitar a localização de funcionalidades). Esse léxico é detalhado na tabela abaixo:

<font size="3"><p style="text-align: center">Tabela X: Léxico XX – Termo de Pesquisa (LXX)</p></font>

<center>

| LXX | Descrição | 
| :-:       | :-:            |
| **Termo** | Termo de Pesquisa | 
| **Tipo** | Substantivo | 
| **Impacto** | - Define o conteúdo que o usuário deseja encontrar. <br> - A precisão do termo influencia na relevância dos resultados. <br> - Pode ser ampliado com sugestões para melhorar a busca. | 
| **Noção** | Palavra ou conjunto de palavras digitadas pelo usuário no campo de busca para localizar funcionalidades ou informações. | 
| **Sinônimos** | Palavra-chave, Consulta, Pesquisa | 
| **Autor** | [Marcelo Makoto](https://github.com/MM4k) | 

</center>

<font size="2"><p style="text-align: center">Fonte: [Marcelo Makoto](https://github.com/MM4k))</p></font>

## L12: Trocar pelo termo


<font size="3"><p style="text-align: center">Tabela X: Léxico 12 – Trocar pelo termo (L12)</p></font>

| L12 | Descrição | 
| :-:       | :-:            |
| **Termo** |  | 
| **Tipo** |  | 
| **Impacto** |  | 
| **Noção** |  | 
| **Sinônimos** |  | 
| **Autor** | [Eduardo de Pina](https://github.com/eduardodpms) | 

<font size="2"><p style="text-align: center">Fonte: [Eduardo de Pina](https://github.com/eduardodpms)</p></font>

## L13: Trocar pelo termo


<font size="3"><p style="text-align: center">Tabela X: Léxico 13 – Trocar pelo termo (L13)</p></font>

| L10 | Descrição | 
| :-:       | :-:            |
| **Termo** |  | 
| **Tipo** |  | 
| **Impacto** |  | 
| **Noção** |  | 
| **Sinônimos** |  | 
| **Autor** | [Eduardo de Pina](https://github.com/eduardodpms) | 

<font size="2"><p style="text-align: center">Fonte: [Eduardo de Pina](https://github.com/eduardodpms)</p></font>

## L14: Trocar pelo termo


<font size="3"><p style="text-align: center">Tabela X: Léxico 14 – Trocar pelo termo (L14)</p></font>

| L14 | Descrição | 
| :-:       | :-:            |
| **Termo** |  | 
| **Tipo** |  | 
| **Impacto** |  | 
| **Noção** |  | 
| **Sinônimos** |  | 
| **Autor** | [Maria Eduarda](https://github.com/dudaa28) | 

<font size="2"><p style="text-align: center">Fonte: [Maria Eduarda](https://github.com/dudaa28)</p></font>

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
| `1.7` | 17/05/2025 | Adição de mais léxicos para os requisitos IS06 e IS07 | [Victor Pontual](https://github.com/VictorPontual)  | - |
