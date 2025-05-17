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

## L04: Trocar pelo termo


<font size="3"><p style="text-align: center">Tabela X: Léxico 04 – Trocar pelo termo (L04)</p></font>

| L04 | Descrição | 
| :-:       | :-:            |
| **Termo** |  | 
| **Tipo** |  | 
| **Impacto** |  | 
| **Noção** |  | 
| **Sinônimos** |  | 
| **Autor** | [Victor Pontual](https://github.com/VictorPontual) | 

<font size="2"><p style="text-align: center">Fonte: [Victor Pontual](https://github.com/VictorPontual)</p></font>

## L05: Trocar pelo termo


<font size="3"><p style="text-align: center">Tabela X: Léxico 05 – Trocar pelo termo (L05)</p></font>

| L05 | Descrição | 
| :-:       | :-:            |
| **Termo** |  | 
| **Tipo** |  | 
| **Impacto** |  | 
| **Noção** |  | 
| **Sinônimos** |  | 
| **Autor** | [Victor Pontual](https://github.com/VictorPontual) | 

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

## L10: Chat


<font size="3"><p style="text-align: center">Tabela X: Léxico 10 – Chat (L10)</p></font>

<center>

| L10 | Descrição | 
| :-:       | :-:            |
| **Termo** | Chat | 
| **Tipo** | Substantivo | 
| **Impacto** | - Permite a comunicação direta entre o usuário e um assistente virtual. <br> - Auxilia na resolução de dúvidas e problemas sem a necessidade de sair do aplicativo. <br> - Pode ser integrado a diferentes partes do sistema para oferecer suporte contextual. | 
| **Noção** | Canal de comunicação textual, em tempo real, por onde o usuário interage com um assistente para obter suporte, tirar dúvidas ou receber orientações. | 
| **Sinônimos** | Conversa, Atendimento Virtual, Suporte via mensagem | 
| **Autor** | [Marcelo Makoto](https://github.com/MM4k) | 

</center>

<font size="2"><p style="text-align: center">Fonte: [Marcelo Makoto](https://github.com/MM4k)</p></font>

## L11: Buscar


<font size="3"><p style="text-align: center">Tabela X: Léxico 11 – Buscar (L11)</p></font>

<center>

| L11 | Descrição | 
| :-:       | :-:            |
| **Termo** | Buscar | 
| **Tipo** | Verbo | 
| **Impacto** | - Facilita a localização de funcionalidades e informações dentro do aplicativo. <br> - Melhora a usabilidade ao reduzir o tempo de navegação. <br> - Permite que o usuário acesse diretamente conteúdos relevantes com base em palavras-chave. | 
| **Noção** | Ação de digitar um termo com o objetivo de encontrar funcionalidades ou conteúdos relacionados a ele no sistema. | 
| **Sinônimos** | Pesquisar, Procurar, Localizar | 
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
| `1.4` | 17/05/2025 | Adição dos léxicos 07 e 08 | [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa) | - |
| `1.5` | 17/05/2025 | Adição da introdução e metodologia | [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa) | - |