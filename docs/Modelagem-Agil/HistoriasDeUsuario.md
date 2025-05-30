#  Histórias de Usuário 

##  Introdução

O presente documento tem como objetivo apresentar as histórias de usuário elaboradas para o desenvolvimento de um aplicativo voltado à gestão e ao acompanhamento de serviços relacionados ao Fundo de Garantia do Tempo de Serviço (FGTS).

As histórias de usuário são uma técnica fundamental na Engenharia de Requisitos Ágil, utilizadas para representar funcionalidades, resultados ou características desejadas no software. Elas são criadas a partir da escuta ativa das necessidades dos usuários e servem como guia para o desenvolvimento. Cada história recebe uma prioridade com base no seu valor de negócio, facilitando o planejamento incremental do sistema <a id="REF1">1</a>.

Cada história de usuário é construída de forma a responder três perguntas essenciais:  

- **Quem?** — Quem é o usuário ou persona envolvida na interação.  

- **O que?** — Qual é a ação, necessidade ou funcionalidade desejada.  

- **Por que?** — Qual é o valor, objetivo ou benefício buscado por meio daquela ação.

##  Metodologia

A elaboração das histórias de usuário deste projeto seguiu uma abordagem centrada no usuário, fundamentada em princípios da Engenharia de Requisitos Ágil e do Design Centrado no Usuário (DCU) <a href="#REF2">2</a>. Esta metodologia garantiu que as histórias de usuário fossem elaboradas de forma realista, testável e completamente alinhada às necessidades das personas, criando uma base sólida para o desenvolvimento do aplicativo FGTS.

### Construção das Histórias de Usuário

As histórias de usuário foram escritas seguindo o modelo clássico:

> **Como [usuário], quero [ação], para [atingir um objetivo].**

Essa estrutura ajuda a garantir que cada história represente uma necessidade real do usuário, deixando claro o objetivo e o valor gerado pela funcionalidade.

### Aplicação dos Modelos Ágeis

Todas as histórias de usuário foram estruturadas e avaliadas com base em dois modelos amplamente reconhecidos no contexto do desenvolvimento ágil:  **INVEST** e **3C’s**.

**INVEST (Wake, 2003) <a href="#anchor_3">3</a>:** Esse modelo estabelece seis critérios fundamentais que garantem a qualidade e a eficácia de uma história de usuário:

- **I — Independente:** A história não deve depender de outras para ser desenvolvida, implementada ou testada.

- **N — Negociável:** As histórias são flexíveis e abertas a discussões, podendo ser refinadas durante as interações entre a equipe e os stakeholders.

- **V — Valiosa:** A história deve gerar valor perceptível e concreto para o usuário final ou para o negócio.

- **E — Estimável:** A história deve ser suficientemente clara e bem definida para permitir a estimativa do esforço necessário para sua implementação.

- **S — Sucinta (Small):** A história deve ter um tamanho adequado, podendo ser desenvolvida dentro de um ciclo ágil (sprint), evitando ser muito grande ou complexa.

- **T — Testável:** Deve possuir critérios de aceitação claros e objetivos, que permitam verificar se a funcionalidade atende às necessidades da persona e aos requisitos definidos.  

**3C’s (Jeffries, 2001) <a href="#anchor_4">4</a>:** Complementando o modelo INVEST, os 3C’s enfatizam três elementos centrais para a formulação e validação de uma história de usuário eficaz:

- **Card (Cartão):** Representa a história em si, seja em um post-it físico ou em um quadro digital, funcionando como um lembrete do que precisa ser desenvolvido.

- **Conversation (Conversa):** Refere-se às discussões colaborativas entre equipe de desenvolvimento, Product Owner e stakeholders, nas quais são esclarecidos os detalhes, as dúvidas e as regras de negócio associadas à história.

- **Confirmation (Confirmação):** Corresponde aos critérios de aceitação formalmente definidos, que validam que a história foi corretamente implementada, atendendo às expectativas e às necessidades do usuário.

### Definição dos Critérios de Aceitação:

Para cada história de usuário, foram estabelecidos critérios de aceitação claros, objetivos e verificáveis. Esses critérios funcionam como referência para confirmar se a funcionalidade entregue atende aos requisitos previamente acordados e, sobretudo, às expectativas do usuário.

### Participantes


<font size="3"><p style="text-align: center">Tabela 1: Participantes</p></font>

<div align="center">

<table>
  <thead>
    <tr>
      <th align="center">Nome</th>
      <th align="center">Data</th>
      <th align="center">Hora</th>
    </tr>
  </thead>
  <tbody>
    <tr><td align="center">Danielle Soares</td><td align="center">30/05/2025</td><td align="center">00:05</td></tr>
    <tr><td align="center">Eduardo de Pina</td><td align="center">--/05/2025</td><td align="center">00:00</td></tr>
    <tr><td align="center">Enzo Emir</td><td align="center">--/05/2025</td><td align="center">00:00</td></tr>
    <tr><td align="center">Leticia Arisa</td><td align="center">30/05/2025</td><td align="center">07:22</td></tr>
    <tr><td align="center">Marcelo Makoto</td><td align="center">28/05/2025</td><td align="center">21:50</td></tr>
    <tr><td align="center">Maria Eduarda</td><td align="center">30/05/2025</td><td align="center">00:30</td></tr>
    <tr><td align="center">Victor Pontual</td><td align="center">--/05/2025</td><td align="center">00:00</td></tr>
  </tbody>
</table>
</div>

<p align="center">Fonte: <i>Enzo Emir</i></p>

## Sumário

**Requisito RF08 (IS05, EN02)**

- [H01 – Acompanhar Situação do Saque](#h01)
- [H02 – Notificações Sobre Andamento](#h02)

**Requisito RF01 (EN03)**

- [H03 – Informar Datas de Liberação](#h03)

**Requisito RF02 (EN04)**

- [H04 – Canal de Suporte/Chatbot](#h04)

**Requisito RF03 (EN05)**

- [H05 – Consulta ao Saldo do FGTS](#h05)

**Requisito RF04 (EN06, ST13, ST14)**

- [H06 – Disponibilizar Saque-Aniversário](#h06)

**Requisito RF05 (IS01)**

- [H07 – Atualização de Dados Pessoais](#h07)

**Requisito RF11 (IS08)**

- [H08 – Ver Informações Sobre Saques Bloqueados](#h08)

**Requisito RF17 (IS15)**

- [H09 – Acesso à Seção de Ajuda](#h09)

**Requisito RF19 (IS17)**

- [H10 – Solicitação de Ressarcimento do PIS/PASEP](#h10)

**Requisito RF20 (OB01)**

- [H11 – Login Seguro](#h11)

**Requisito RF15 (IS13)**

- [H12 – Assistente via chat](#h12)

**Requisito RF16 (IS14)**

- [H13 – Campo de busca](#h13)

**Requisito RF24 (OB07)**

- [H14 – Aba de saque](#h14)

**Requisito RF25 (OB09)**

- [H15 – Aba de itens diversos](#h15)

**Requisito RF26 (ST02)**

- [H16 – Resumo dos tipos de saque](#h16)

**Requisito RF27 (ST02)**

- [H17 – Notificações de Status e Saques](#h17)

**Requisito RF28 (IS05, EN02)**

- [H18 – Solicitação de Saques](#h18)

**Requisito RF30 (OB07)**

- [H19 – Ajuste de Tamanho de Fonte](#h19)

**Requisito RF31 (IS08)**

- [H20 – Visualização de Dados Bancários](#h20)

**Requisito RF35 (IS12)**

- [H21 – Cadastro de Múltiplas Contas Bancárias](#h21)

**Requisito RF12 (IS09)**

- [H22 – Visualizar histórico de movimentações financeiras](#h22)

**Requisito RF13 (IS10)**

- [H23 – Filtrar extrato por data](#h23)

**Requisito RF21 (OB02)**

- [H24 – Visualizar empregadores anteriores com botão para consultar contas vinculadas](#h24)

**Requisito RF22 (OB05)**

- [H25 – Visualizar nome completo dos empregadores anteriores](#h25)

**Requisito RF23 (OB06)**

- [H26 – Visualizar histórico de saques realizados](#h26)

---

##  Histórias de Usuário

A tabela [2](#tabela-modelo) será utilizada como modelo para a elaboração das histórias de usuário do projeto. Ela padroniza os principais elementos necessários, como a descrição da necessidade, critérios de aceitação, prioridade, status de validação, entre outros. O objetivo é garantir consistência, rastreabilidade e clareza em todas as histórias documentadas.

<p align="center">Tabela 2: <i>Modelo para História de Usuário.</i></p>
<a name="tabela-modelo"></a>
<div align="center">
<table>
  <thead>
    <tr>
      <th><strong>Item</strong></th>
      <th><strong>Descrição</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>ID</td>
      <td>USx</td>
    </tr>
    <tr>
      <td>Rastreabilidade</td>
      <td>Código do requisito</td>
    </tr>
    <tr>
      <td>Tema</td>
      <td>Título</td>
    </tr>
    <tr>
      <td>Descrição</td>
      <td>Eu, como <em>[tipo de usuário]</em>, desejo <em>[ação desejada]</em> para <em>[objetivo]</em></td>
    </tr>
    <tr>
      <td>Critérios de Aceitação</td>
      <td>- [Critério 1] <br> - [Critério 2]</td>
    </tr>
    <tr>
      <td>Prioridade Usuário</td>
      <td>Alta, Média, Baixa</td>
    </tr>
    <tr>
      <td>Status</td>
      <td>Se a história foi validada ou não pelo usuário</td>
    </tr>
  </tbody>
</table>
</div>
<p align="center">Fonte: <i>Danielle Soares</i></p>



### <a name="h01"></a> História 01 — Acompanhar Situação do Saque

| **Item**                 | **Descrição**                                                                 |
|--------------------------|------------------------------------------------------------------------------|
| **ID**                   | US01                                                                         |
| **Rastreabilidade**      | RF08 (IS05, EN02)                                                             |
| **Tema**                 | Acompanhar Situação do Saque                                                 |
| **Descrição**            | Eu, como técnica de enfermagem, desejo acompanhar a situação do meu saque do FGTS para saber se está aprovado, em análise ou concluído, sem ir à agência. |
| **Critérios de Aceitação** | - Status exibido claramente (Ex.: “Aguardando análise”, “Aprovado”)  <br> - Mostra possíveis pendências ou exigências  <br> - Atualização automática do status |
| **Prioridade Usuário**   | Alta                                                                          |
| **Status**               | Não Validada                                                                  |

<font size="2"><p style="text-align: center">Fonte: [Enzo Emir](https://github.com/EnzoEmir)</p></font>

### <a name="h02"></a> História 02 — Notificações Sobre Andamento

| **Item**                 | **Descrição**                                                                 |
|--------------------------|------------------------------------------------------------------------------|
| **ID**                   | US03                                                                         |
| **Rastreabilidade**      | RF08 (IS05, EN02)                                                             |
| **Tema**                 | Notificações Sobre Andamento                                                 |
| **Descrição**            | Eu, como comerciante, desejo receber notificações sobre o andamento do meu saque do FGTS para ser informada de atualizações sem precisar abrir o app constantemente. |
| **Critérios de Aceitação** | - Notificações push quando houver mudança no status  <br> - Mensagens objetivas (Ex.: “Seu saque foi liberado”)  <br> - Opção de ativar/desativar notificações |
| **Prioridade Usuário**   | Alta                                                                          |
| **Status**               | Não Validada                                                                  |

<font size="2"><p style="text-align: center">Fonte: [Enzo Emir](https://github.com/EnzoEmir)</p></font>

### <a name="h03"></a> História 03 — Informar Datas de Liberação

| **Item**                 | **Descrição**                                                                 |
|--------------------------|------------------------------------------------------------------------------|
| **ID**                   | US04                                                                         |
| **Rastreabilidade**      | RF01 (EN03)                                                                   |
| **Tema**                 | Informar Datas de Liberação                                                  |
| **Descrição**            | Eu, como aposentado, desejo ver as datas previstas para liberação dos valores do FGTS para me organizar financeiramente e pedir ajuda aos filhos, se necessário. |
| **Critérios de Aceitação** | - Exibição da data estimada de liberação  <br> - Alerta caso a data seja alterada  <br> - Informação clara caso a data não esteja definida |
| **Prioridade Usuário**   | Alta                                                                          |
| **Status**               | Não Validada                                                                  |

<font size="2"><p style="text-align: center">Fonte: [Enzo Emir](https://github.com/EnzoEmir)</p></font>

### <a name="h04"></a> História 04 — Acesso à Seção de Ajuda

| **Item**                 | **Descrição**                                                                 |
|--------------------------|------------------------------------------------------------------------------|
| **ID**                   | US05                                                                         |
| **Rastreabilidade**      | RF17 (IS15)                                                                   |
| **Tema**                 | Acesso à Seção de Ajuda                                                       |
| **Descrição**            | Eu, como técnica de enfermagem, desejo acessar uma seção de ajuda com orientações sobre FGTS e PIS/PASEP para esclarecer dúvidas rapidamente, sem precisar de atendimento presencial. |
| **Critérios de Aceitação** | - FAQ com respostas claras  <br> - Explicações sobre regras de saque, prazos e documentação  <br> - Opção de contato com suporte |
| **Prioridade Usuário**   | Média                                                                         |
| **Status**               | Não Validada                                                                  |

<font size="2"><p style="text-align: center">Fonte: [Enzo Emir](https://github.com/EnzoEmir)</p></font>

### <a name="h05"></a> História 05 — Solicitação de Ressarcimento do PIS/PASEP

| **Item**                 | **Descrição**                                                                 |
|--------------------------|------------------------------------------------------------------------------|
| **ID**                   | US06                                                                         |
| **Rastreabilidade**      | RF19 (IS17)                                                                   |
| **Tema**                 | Solicitação de Ressarcimento do PIS/PASEP                                    |
| **Descrição**            | Eu, como jovem tecnólogo, desejo solicitar o ressarcimento de valores do PIS/PASEP pelo app para evitar filas, economizar tempo e resolver tudo digitalmente. |
| **Critérios de Aceitação** | - Formulário simples, com upload de documentos  <br> - Confirmação do envio  <br> - Acompanhamento do andamento no app |
| **Prioridade Usuário**   | Alta                                                                          |
| **Status**               | Não Validada                                                                  |

<font size="2"><p style="text-align: center">Fonte: [Enzo Emir](https://github.com/EnzoEmir)</p></font>

### <a name="h06"></a> História 06 — Login Seguro

| **Item**                 | **Descrição**                                                                 |
|--------------------------|------------------------------------------------------------------------------|
| **ID**                   | US07                                                                         |
| **Rastreabilidade**      | RF20 (OB01)                                                                   |
| **Tema**                 | Login Seguro                                                                 |
| **Descrição**            | Eu, como usuária com pouca autonomia digital (ou comerciante ocupada), desejo fazer login de forma segura no app para proteger meus dados, sem complicações ou esquecimento de senha. |
| **Critérios de Aceitação** | - Login com biometria, senha ou autenticação de dois fatores (2FA)  <br> - Mensagens claras em caso de erro  <br> - Opção de lembrar acesso ou recuperar senha |
| **Prioridade Usuário**   | Alta                                                                          |
| **Status**               | Não Validada                                                                  |

<font size="2"><p style="text-align: center">Fonte: [Enzo Emir](https://github.com/EnzoEmir)</p></font>



### <a name="h07"></a> História 07 — Assistente via chat

<font size="3"><p style="text-align: center">Tabela 10: História de assistente via chat</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th><strong>Item</strong></th>
      <th><strong>Descrição</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>ID</td>
      <td><a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#requisitos-funcionais">RF15</a></td>
    </tr>
    <tr>
      <td>Rastreabilidade</td>
      <td><a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#requisitos-funcionais">IS13</a></td>
    </tr>
    <tr>
      <td>Tema</td>
      <td>Atendimento via chat</td>
    </tr>
    <tr>
      <td>Descrição</td>
      <td>Eu, como aposentado com baixa autonomia digital, desejo que minha filha possa usar um chat no app para tirar dúvidas e resolver problemas, para que não precisemos ir até a agência.</td>
    </tr>
    <tr>
      <td>Critérios de Aceitação</td>
      <td>- O botão de acesso ao chat deve estar visível e acessível na tela principal. <br> - O chat deve aceitar linguagem natural e ter respostas claras, com possibilidade de atendimento humano. <br> - O histórico das conversas deve ficar salvo para consultas futuras.</td>
    </tr>
    <tr>
      <td>Prioridade Usuário</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Status</td>
      <td>A validar pelo usuário</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: [Marcelo Makoto](https://github.com/MM4k)</p></font>



### <a name="h08"></a> História 08 — Campo de busca

<font size="3"><p style="text-align: center">Tabela 11: História de campo de busca</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th><strong>Item</strong></th>
      <th><strong>Descrição</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>ID</td>
      <td><a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#requisitos-funcionais">RF16</a></td>
    </tr>
    <tr>
      <td>Rastreabilidade</td>
      <td><a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#requisitos-funcionais">IS14</a></td>
    </tr>
    <tr>
      <td>Tema</td>
      <td>Campo de busca</td>
    </tr>
    <tr>
      <td>Descrição</td>
      <td>Eu, como usuário avançado que domina tecnologia, desejo buscar rapidamente funcionalidades como extrato ou saque, para navegar de forma mais eficiente no aplicativo.</td>
    </tr>
    <tr>
      <td>Critérios de Aceitação</td>
      <td>- Campo de busca disponível no topo da tela ou menu. <br> - Resultados sugeridos enquanto o usuário digita. <br> - Funcionalidade acessível com poucas interações.</td>
    </tr>
    <tr>
      <td>Prioridade Usuário</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Status</td>
      <td>A validar pelo usuário</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: [Marcelo Makoto](https://github.com/MM4k)</p></font>



### <a name="h09"></a> História 09 — Aba de solicitação e acompanhamento de saques

<font size="3"><p style="text-align: center">Tabela 12: História de aba de solicitação e acompanhamento de saques</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th><strong>Item</strong></th>
      <th><strong>Descrição</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>ID</td>
      <td><a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#requisitos-funcionais">RF24</a></td>
    </tr>
    <tr>
      <td>Rastreabilidade</td>
      <td><a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Observacao/#requisitos-funcionais">OB07</a></td>
    </tr>
    <tr>
      <td>Tema</td>
      <td>Aba de solicitação e acompanhamento de saques</td>
    </tr>
    <tr>
      <td>Descrição</td>
      <td>Eu, como técnica de enfermagem que busca praticidade, desejo acessar uma aba exclusiva para solicitação e acompanhamento de saques, para saber se o dinheiro foi liberado sem complicação.</td>
    </tr>
    <tr>
      <td>Critérios de Aceitação</td>
      <td>- Aba visível com ícone descritivo (ex.: “Saques”). <br> - Exibe etapas do processo: solicitado, em análise, aprovado, concluído. <br> - Possibilidade de iniciar um novo pedido de saque.</td>
    </tr>
    <tr>
      <td>Prioridade Usuário</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Status</td>
      <td>A validar pelo usuário</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: [Marcelo Makoto](https://github.com/MM4k)</p></font>



### <a name="h10"></a> História 10 — Aba de informações adicionais

<font size="3"><p style="text-align: center">Tabela 13: História de aba de informações adicionais</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th><strong>Item</strong></th>
      <th><strong>Descrição</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>ID</td>
      <td><a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#requisitos-funcionais">RF25</a></td>
    </tr>
    <tr>
      <td>Rastreabilidade</td>
      <td><a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Observacao/#requisitos-funcionais">OB09</a></td>
    </tr>
    <tr>
      <td>Tema</td>
      <td>Aba de informações adicionais</td>
    </tr>
    <tr>
      <td>Descrição</td>
      <td>Eu, como comerciante que evita processos longos, desejo acessar uma aba com informações como PIS/PASEP, sistemática de saque e ajuda, para entender melhor meus direitos sem perder tempo.</td>
    </tr>
    <tr>
      <td>Critérios de Aceitação</td>
      <td>- Aba identificada com título e ícone compreensíveis (ex.: “Mais opções”). <br> - Itens organizados por categorias. <br> - Explicações em formato visual e direto.</td>
    </tr>
    <tr>
      <td>Prioridade Usuário</td>
      <td>Média</td>
    </tr>
    <tr>
      <td>Status</td>
      <td>A validar pelo usuário</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: [Marcelo Makoto](https://github.com/MM4k)</p></font>



### <a name="h11"></a> História 11 — Resumo dos tipos de saque

<font size="3"><p style="text-align: center">Tabela 14: História de resumo dos tipos de saque</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th><strong>Item</strong></th>
      <th><strong>Descrição</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>ID</td>
      <td><a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#requisitos-funcionais">RF26</a></td>
    </tr>
    <tr>
      <td>Rastreabilidade</td>
      <td><a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#requisitos-funcionais">ST02</a></td>
    </tr>
    <tr>
      <td>Tema</td>
      <td>Resumo dos tipos de saque</td>
    </tr>
    <tr>
      <td>Descrição</td>
      <td>Eu, como usuário que controla ativamente suas finanças, desejo visualizar um resumo dos tipos de saque disponíveis, para escolher a melhor opção para meu perfil.</td>
    </tr>
    <tr>
      <td>Critérios de Aceitação</td>
      <td>- Cards ou tabelas explicando os tipos (aniversário, rescisão, calamidade etc.). <br> - Destaque para prazos, regras e vantagens de cada tipo. <br> - Link direto para alterar a sistemática de saque.</td>
    </tr>
    <tr>
      <td>Prioridade Usuário</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Status</td>
      <td>A validar pelo usuário</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: [Marcelo Makoto](https://github.com/MM4k)</p></font>

### <a name="h12"></a> História 12 — Ver Informações Sobre Saques Bloqueados

<font size="3"><p style="text-align: center">Tabela 15: História de bloqueio de saque</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th><strong>Item</strong></th>
      <th><strong>Descrição</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>ID</td>
      <td>RF11</td>
    </tr>
    <tr>
      <td>Rastreabilidade</td>
      <td> <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#IS_RF">IS08</a></td>
    <tr>
      <td>Tema</td>
      <td>Ver Informações Sobre Saques Bloqueados</td>
    </tr>
    <tr>
      <td>Descrição</td>
      <td>Eu, como <em>beneficiário do FGTS</em>, desejo <em>visualizar informações sobre meus saques bloqueados e os respectivos motivos do bloqueio</em> para <em> entender minha situação e buscar a regularização, se possível.</em></td>
    </tr>
    <tr>
      <td>Critérios de Aceitação</td>
      <td>- O sistema deve exibir uma lista clara dos saques que estão bloqueados. <br> - Para cada saque bloqueado, o sistema deve apresentar o motivo específico do bloqueio.<br> - O usuário deve conseguir acessar essa informação de forma intuitiva dentro do aplicativo. </td>
    </tr>
    <tr>
      <td>Prioridade Usuário</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Status</td>
      <td>A ser validado pelo usuário</td>
    </tr>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: [Danielle Soares](https://github.com/danielle-soaress)</p></font>

### <a name="h13"></a> História 13 — Cadastro de Múltiplas Contas Bancárias

<font size="3"><p style="text-align: center">Tabela 16: História de cadastro de contas bancárias</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th><strong>Item</strong></th>
      <th><strong>Descrição</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>ID</td>
      <td>RF35</td>
    </tr>
    <tr>
      <td>Rastreabilidade</td>
      <td> <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#IS_RF">IS12</a></td>
    <tr>
      <td>Tema</td>
      <td>Cadastro de Múltiplas Contas Bancárias</td>
    </tr>
    <tr>
      <td>Descrição</td>
      <td>Eu, como <em>beneficiário do FGTS</em>, desejo <em>cadastrar mais de uma conta bancária de diferentes instituições financeiras</em> para <em>ter flexibilidade na hora de receber meus saques e benefícios.</em></td>
    </tr>
    <tr>
      <td>Critérios de Aceitação</td>
      <td>- O sistema deve permitir a adição de novas contas bancárias. <br> - O usuário deve conseguir cadastrar contas de diferentes instituições financeiras. <br> - O sistema deve validar os dados da conta bancária no momento do cadastro. <br> - O usuário deve poder visualizar e gerenciar todas as contas cadastradas.</td>
    </tr>
    <tr>
      <td>Prioridade Usuário</td>
      <td>Média</td>
    </tr>
    <tr>
      <td>Status</td>
      <td>A ser validado pelo usuário</td>
    </tr>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: [Danielle Soares](https://github.com/danielle-soaress)</p></font>

### <a name="h14"></a> História 14 —  Consulta ao Saldo do FGTS

<font size="3"><p style="text-align: center">Tabela 17: História de consulta ao saldo do FGTS</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th><strong>Item</strong></th>
      <th><strong>Descrição</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>ID</td>
      <td>RF03</td>
    </tr>
    <tr>
      <td>Rastreabilidade</td>
      <td> <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Entrevista/#EN_RF">EN05</a></td>
    <tr>
      <td>Tema</td>
      <td>Consulta ao Saldo do FGTS</td>
    </tr>
    <tr>
      <td>Descrição</td>
      <td>Eu, como <em>beneficiário do FGTS</em>, desejo <em>consultar o saldo da minha conta vinculada do FGTS</em> para <em>acompanhar minhas economias e planejar meus próximos passos.</em></td>
    </tr>
    <tr>
      <td>Critérios de Aceitação</td>
      <td>- O sistema deve exibir o saldo atualizado da conta vinculada do FGTS. <br> - O saldo deve ser apresentado de forma clara e visível na tela principal ou em seção dedicada. <br> - O usuário deve conseguir acessar essa informação de forma rápida e segura.</td>
    </tr>
    <tr>
      <td>Prioridade Usuário</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Status</td>
      <td>A ser validado pelo usuário</td>
    </tr>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: [Danielle Soares](https://github.com/danielle-soaress)</p></font>

### <a name="h15"></a> História 15 — Atualização de Dados Pessoais

<font size="3"><p style="text-align: center">Tabela 18: História de atualização de dados pessoais</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th><strong>Item</strong></th>
      <th><strong>Descrição</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>ID</td>
      <td>RF05</td>
    </tr>
    <tr>
      <td>Rastreabilidade</td>
      <td> <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#IS_RF">IS01</a></td>
    <tr>
      <td>Tema</td>
      <td>Atualização de Dados Pessoais</td>
    </tr>
    <tr>
      <td>Descrição</td>
      <td>Eu, como <em>usuário do aplicativo FGTS</em>, desejo <em>atualizar meus dados pessoais</em> para <em>manter minhas informações corretas e atualizadas no sistema.</em></td>
    </tr>
    <tr>
      <td>Critérios de Aceitação</td>
      <td>- O sistema deve permitir a edição de dados como endereço, telefone e e-mail. <br> - As alterações devem ser salvas e refletidas imediatamente após a confirmação do usuário. <br> - O sistema deve garantir a segurança dos dados pessoais durante o processo de atualização. <br> - O usuário deve ser notificado sobre a conclusão da atualização.</td>
    </tr>
    <tr>
      <td>Prioridade Usuário</td>
      <td>Média</td>
    </tr>
    <tr>
      <td>Status</td>
      <td>A ser validado pelo usuário</td>
    </tr>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: [Danielle Soares](https://github.com/danielle-soaress)</p></font>

### <a name="h16"></a> História 16 — Disponibilizar Saque-Aniversário

<font size="3"><p style="text-align: center">Tabela 19: História de disponibilização de saque-aniversário</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th><strong>Item</strong></th>
      <th><strong>Descrição</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>ID</td>
      <td>RF04</td>
    </tr>
    <tr>
      <td>Rastreabilidade</td>
      <td> <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Entrevista/#EN_RF">EN06</a>, <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#ST_RF">ST013</a>, <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#ST_RF">ST014</a></td>
    <tr>
      <td>Tema</td>
      <td>Disponibilizar Saque-Aniversário</td>
    </tr>
    <tr>
      <td>Descrição</td>
      <td>Eu, como <em>beneficiário do FGTS</em>, desejo <em>utilizar a funcionalidade de saque-aniversário de forma acessível</em>, para <em>poder sacar o valor disponível sem barreiras de uso.</em></td>
    </tr>
    <tr>
      <td>Critérios de Aceitação</td>
      <td>- O sistema deve apresentar a opção de saque-aniversário de forma clara e visível. <br> - A funcionalidade deve ser navegável e operável por meio de teclado e leitores de tela. <br> - O aplicativo deve fornecer feedback visual e auditivo adequado durante o processo de saque. <br> - As informações sobre o valor disponível para saque e as datas devem ser de fácil compreensão.</td>
    </tr>
    <tr>
      <td>Prioridade Usuário</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Status</td>
      <td>A ser validado pelo usuário</td>
    </tr>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: [Danielle Soares](https://github.com/danielle-soaress)</p></font>

### <a name="h17"></a> História 17 —  

<font size="3"><p style="text-align: center">Tabela 20: História de</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th><strong>Item</strong></th>
      <th><strong>Descrição</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>USx (número de identificação)</td>
      <td>RF11</td>
    </tr>
    <tr>
      <td>Rastreabilidade</td>
      <td> <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#IS_RF">IS08</a></td>
    <tr>
      <td>Tema</td>
      <td>Título</td>
    </tr>
    <tr>
      <td>Descrição</td>
      <td>Eu, como <em>[tipo de usuário]</em>, desejo <em>[ação desejada]</em> para <em>[objetivo]</em></td>
    </tr>
    <tr>
      <td>Critérios de Aceitação</td>
      <td>- [Critério 1] <br> - [Critério 2]</td>
    </tr>
    <tr>
      <td>Prioridade Usuário</td>
      <td>Alta, Média, Baixa</td>
    </tr>
    <tr>
      <td>Status</td>
      <td>Se a história foi validada ou não pelo usuário</td>
    </tr>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: </p></font>


### <a name="h18"></a> História 18 — Canal de Suporte/Chatbot 

<font size="3"><p style="text-align: center">Tabela 21: História de Canal de Suporte/Chatbot</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th><strong>Item</strong></th>
      <th><strong>Descrição</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>ID</td>
      <td><a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#requisitos-funcionais">RF02</a></td>
    </tr>
    <tr>
      <td>Rastreabilidade</td>
      <td> <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Entrevista/#requisitos-funcionais">EN04</a></td>
    <tr>
      <td>Tema</td>
      <td>Suporte ao Usuário</td>
    </tr>
    <tr>
      <td>Descrição</td>
      <td>Eu, como usuário do aplicativo, desejo ter acesso a um canal de suporte ou chatbot para esclarecer minhas dúvidas de forma rápida e eficiente.</td>
    </tr>
    <tr>
      <td>Critérios de Aceitação</td>
      <td>- O usuário deve conseguir iniciar uma conversa com o chatbot a qualquer momento. <br> - O chatbot deve ser capaz de responder a perguntas frequentes sobre o uso do aplicativo. <br> - O usuário deve ter a opção de ser direcionado a um atendente humano caso o chatbot não consiga resolver sua dúvida. <br> - O canal de suporte deve estar disponível em horários comerciais para atendimento humano.</td>
    </tr>
    <tr>
      <td>Prioridade Usuário</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Status</td>
      <td>A validar pelo usuário</td>
    </tr>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: [Maria Eduarda](https://github.com/dudaa28)</p></font>

### <a name="h19"></a> História 19 — Ajuste de Tamanho de Fonte 

<font size="3"><p style="text-align: center">Tabela 22: História de ajuste de tamanho de fonte</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th><strong>Item</strong></th>
      <th><strong>Descrição</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>ID</td>
      <td><a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#requisitos-funcionais">RF30</a></td>
    </tr>
    <tr>
      <td>Rastreabilidade</td>
      <td> <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#requisitos-funcionais">ST08</a></td>
    <tr>
      <td>Tema</td>
      <td>Acessibilidade</td>
    </tr>
    <tr>
      <td>Descrição</td>
      <td>Eu, como usuário, desejo poder ajustar o tamanho das fontes na interface para melhorar a legibilidade e personalizar minha experiência de uso.</td>
    </tr>
    <tr>
      <td>Critérios de Aceitação</td>
      <td>- O usuário deve conseguir encontrar a opção de ajuste de tamanho de fonte nas configurações. <br>  - O aplicativo deve oferecer pelo menos três opções de tamanho de fonte (Pequena, Média, Grande). <br>  - O tamanho da fonte deve ser aplicado de forma consistente em toda a interface do aplicativo. <br> - O ajuste deve ser salvo e persistir entre as sessões de uso. </td>
    </tr>
    <tr>
      <td>Prioridade Usuário</td>
      <td>Média</td>
    </tr>
    <tr>
      <td>Status</td>
      <td>A validar pelo usuário</td>
    </tr>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: [Maria Eduarda](https://github.com/dudaa28)</p></font>

### <a name="h20"></a> História 20 — Notificações de Status e SaqueS 

<font size="3"><p style="text-align: center">Tabela 23: História de notificações de status e saque</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th><strong>Item</strong></th>
      <th><strong>Descrição</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>ID</td>
      <td><a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#requisitos-funcionais">RF27</a></td>
    </tr>
    <tr>
      <td>Rastreabilidade</td>
      <td> <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#ST_RF">ST03</a>
      <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#ST_RF">ST09</a>
      <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#ST_RF">ST015</a></td>
    <tr>
      <td>Tema</td>
      <td>Notificações do sistema</td>
    </tr>
    <tr>
      <td>Descrição</td>
      <td>Eu, como usuário do sistema FGTS, desejo receber notificações sobre o status da solicitação e confirmação de saque para acompanhar o andamento e ter confirmação das ações realizadas.</td>
    </tr>
    <tr>
      <td>Critérios de Aceitação</td>
      <td>- O sistema deve notificar automaticamente o usuário quando o status da solicitação mudar.  <br> - O sistema deve notificar o usuário quando o saque for efetivado. <br> - As notificações devem ser enviadas via aplicativo e/ou e-mail cadastrado. </td>
    </tr>
    <tr>
      <td>Prioridade Usuário</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Status</td>
      <td>A validar pelo usuário</td>
    </tr>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: [Maria Eduarda](https://github.com/dudaa28)</p></font>

### <a name="h21"></a> História 21 — Solicitação de Saques

<font size="3"><p style="text-align: center">Tabela 24: História de solicitação de saques</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th><strong>Item</strong></th>
      <th><strong>Descrição</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> ID</td>
      <td><a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#requisitos-funcionais">RF28</a></td>
    </tr>
    <tr>
      <td>Rastreabilidade</td>
      <td> <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Entrevista/#tabela-3-requisitos-funcionais">EN01</a>
      <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#IS_RF">IS03</a>
      <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#ST_RF">ST06</a>
      <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Observacao/#OB_RF">OB03</a></td>
    <tr>
      <td>Tema</td>
      <td>Solicitação de Saque</td>
    </tr>
    <tr>
      <td>Descrição</td>
      <td>Eu, como trabalhador com direito ao FGTS, desejo solicitar saques através do sistema para acessar meus recursos de forma prática e segura.</td>
    </tr>
    <tr>
      <td>Critérios de Aceitação</td>
      <td>- O sistema deve permitir que o usuário visualize as opções disponíveis de saque.  <br> - O sistema deve permitir a solicitação diretamente pela plataforma.</td>
    </tr>
    <tr>
      <td>Prioridade Usuário</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Status</td>
      <td>A validar pelo usuário</td>
    </tr>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: [Maria Eduarda](https://github.com/dudaa28)</p></font>

### <a name="h22"></a> História 22 — Visualização de Dados Bancários 

<font size="3"><p style="text-align: center">Tabela 25: História de visualização de dados bancários</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th><strong>Item</strong></th>
      <th><strong>Descrição</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>ID</td>
      <td><a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#requisitos-funcionais">RF31</a></td>
    </tr>
    <tr>
      <td>Rastreabilidade</td>
      <td> <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#ST_RF">ST010</a></td>
    <tr>
      <td>Tema</td>
      <td>Visualização de dados bancários</td>
    </tr>
    <tr>
      <td>Descrição</td>
      <td>Eu, como usuário do sistema FGTS, desejo visualizar os dados da conta bancária cadastrada para verificar se as informações estão corretas.</td>
    </tr>
    <tr>
      <td>Critérios de Aceitação</td>
      <td>- O sistema deve exibir os dados da conta bancária cadastrada no perfil do usuário.  <br>- Os dados devem estar atualizados e legíveis ao usuário.</td>
    </tr>
    <tr>
      <td>Prioridade Usuário</td>
      <td>Média</td>
    </tr>
    <tr>
      <td>Status</td>
      <td>A validar pelo usuário</td>
    </tr>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: [Maria Eduarda](https://github.com/dudaa28)</p></font>

### <a name="h23"></a> História 23 — Visualização do histórico de movimentações financeiras

<font size="3"><p style="text-align: center">Tabela 26: História de visualização do histórico de movimentação financeira</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th><strong>Item</strong></th>
      <th><strong>Descrição</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>ID</td>
      <td><a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#requisitos-funcionais">RF12</a></td>
    </tr>
    <tr>
      <td>Rastreabilidade</td>
      <td> <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#IS_RF">IS09</a></td>
    <tr>
      <td>Tema</td>
      <td>Visualização do histórico de movimentação financeira</td>
    </tr>
    <tr>
      <td>Descrição</td>
      <td>Eu, como usuário do sistema FGTS, desejo visualizar o histórico das movimentações financeiras para que eu possa acompanhar e controlar melhor minhas transações.</td>
    </tr>
    <tr>
      <td>Critérios de Aceitação</td>
      <td>- O sistema deve apresentar uma lista cronológica das movimentações financeiras. <br> - O histórico deve estar acessível na página "Movimentações".</td>
    </tr>
    <tr>
      <td>Prioridade Usuário</td>
      <td>Média</td>
    </tr>
    <tr>
      <td>Status</td>
      <td>A validar pelo usuário</td>
    </tr>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa)</p></font>

### <a name="h24"></a> História 24 — Filtrar extrato por data

<font size="3"><p style="text-align: center">Tabela 27: História de filtrar o extrato por data</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th><strong>Item</strong></th>
      <th><strong>Descrição</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>ID</td>
      <td><a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#requisitos-funcionais">RF13</a></td>
    </tr>
    <tr>
      <td>Rastreabilidade</td>
      <td> <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#IS_RF">IS10</a></td>
    <tr>
      <td>Tema</td>
      <td>Filtrar extrato por data</td>
    </tr>
    <tr>
      <td>Descrição</td>
      <td>Eu, como usuário do sistema FGTS, desejo filtrar o extrato por data para encontrar movimentações em períodos específicos.</td>
    </tr>
    <tr>
      <td>Critérios de Aceitação</td>
      <td>- O sistema deve permitir ao usuário selecionar um intervalo de datas para filtragem. <br> - Apenas movimentações dentro do período selecionado devem ser exibidas <br> - A filtragem deve estar disponível na página "Movimentações".</td>
    </tr>
    <tr>
      <td>Prioridade Usuário</td>
      <td>Baixa</td>
    </tr>
    <tr>
      <td>Status</td>
      <td>A validar pelo usuário</td>
    </tr>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa)</p></font>

### <a name="h25"></a> História 25 — Visualizar empregadores anteriores com botão para consultar contas vinculadas

<font size="3"><p style="text-align: center">Tabela 28: História de visualizar  empregadores anteriores com botão para consultar contas vinculadas</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th><strong>Item</strong></th>
      <th><strong>Descrição</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>ID</td>
      <td><a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#requisitos-funcionais">RF21</a></td>
    </tr>
    <tr>
      <td>Rastreabilidade</td>
      <td> <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Observacao">OB02</a></td>
    <tr>
      <td>Tema</td>
      <td>Visualizar empregadores anteriores com botão para consultar contas vinculadas</td>
    </tr>
    <tr>
      <td>Descrição</td>
      <td>Eu, como usuário do sistema FGTS, desejo visualizar um resumo dos meus empregadores anteriores com o botão de consultar contas vinculadas.</td>
    </tr>
    <tr>
      <td>Critérios de Aceitação</td>
      <td>- O sistema deve exibir uma lista com os empregadores anteriores do usuário. <br> - A interface deve ser clara e acessível tanto em dispositivos móveis quanto em desktops.</td>
    </tr>
    <tr>
      <td>Prioridade Usuário</td>
      <td>Média</td>
    </tr>
    <tr>
      <td>Status</td>
      <td>A validar pelo usuário</td>
    </tr>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa)</p></font>

### <a name="h26"></a> História 26 — Visualizar nome completo dos empregadores anteriores

<font size="3"><p style="text-align: center">Tabela 29: História de visualizar  nome completo dos empregadores anteriores</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th><strong>Item</strong></th>
      <th><strong>Descrição</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>ID</td>
      <td><a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#requisitos-funcionais">RF22</a></td>
    </tr>
    <tr>
      <td>Rastreabilidade</td>
      <td> <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Observacao">OB05</a></td>
    <tr>
      <td>Tema</td>
      <td>Visualizar nome completo dos empregadores anteriores</td>
    </tr>
    <tr>
      <td>Descrição</td>
      <td>Eu, como usuário do sistema FGTS, desejo visualizar o nome completo dos meus empregadores anteriores para facilitar a identificação correta de cada vínculo empregatício.</td>
    </tr>
    <tr>
      <td>Critérios de Aceitação</td>
      <td>- O sistema deve exibir o nome completo (razão social) de cada empregador anterior. <br> - Os nomes devem estar completos, sem abreviações.<br> - A informação deve ser exibida de forma legível e organizada na interface.</td>
    </tr>
    <tr>
      <td>Prioridade Usuário</td>
      <td>Média</td>
    </tr>
    <tr>
      <td>Status</td>
      <td>A validar pelo usuário</td>
    </tr>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa)</p></font>

### <a name="h27"></a> História 27 — Visualizar histórico de saques realizados

<font size="3"><p style="text-align: center">Tabela 30: História de visualizar histórico de saques realizados</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th><strong>Item</strong></th>
      <th><strong>Descrição</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>ID</td>
      <td><a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#requisitos-funcionais">RF23</a></td>
    </tr>
    <tr>
      <td>Rastreabilidade</td>
      <td> <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Observacao">OB06</a></td>
    <tr>
      <td>Tema</td>
      <td>Visualizar histórico de saques realizados</td>
    </tr>
    <tr>
      <td>Descrição</td>
      <td>Eu, como usuário do sistema FGTS, desejo visualizar o histórico de saques realizados para acompanhar e controlar os valores retirados da minha conta.</td>
    </tr>
    <tr>
      <td>Critérios de Aceitação</td>
      <td>- O sistema deve exibir uma lista com todos os saques realizados pelo usuário. <br> - Cada saque deve apresentar data, valor e motivo (quando disponível).<br> - As informações devem estar organizadas de forma cronológica.</td>
    </tr>
    <tr>
      <td>Prioridade Usuário</td>
      <td>Média</td>
    </tr>
    <tr>
      <td>Status</td>
      <td>A validar pelo usuário</td>
    </tr>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa)</p></font>

### <a name="h28"></a> História 28 —  

<font size="3"><p style="text-align: center">Tabela 31: História de</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th><strong>Item</strong></th>
      <th><strong>Descrição</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>USx (número de identificação)</td>
      <td>RF11</td>
    </tr>
    <tr>
      <td>Rastreabilidade</td>
      <td> <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#IS_RF">IS08</a></td>
    <tr>
      <td>Tema</td>
      <td>Título</td>
    </tr>
    <tr>
      <td>Descrição</td>
      <td>Eu, como <em>[tipo de usuário]</em>, desejo <em>[ação desejada]</em> para <em>[objetivo]</em></td>
    </tr>
    <tr>
      <td>Critérios de Aceitação</td>
      <td>- [Critério 1] <br> - [Critério 2]</td>
    </tr>
    <tr>
      <td>Prioridade Usuário</td>
      <td>Alta, Média, Baixa</td>
    </tr>
    <tr>
      <td>Status</td>
      <td>Se a história foi validada ou não pelo usuário</td>
    </tr>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: [Maria Eduarda](https://github.com/dudaa28)</p></font>

## Referências

> <a id="REF1" href="#anchor_1">1.</a>  PRESSMAN, Roger S.; MAXIM, Bruce R.. Engenharia de software: uma abordagem profissional. 8 Porto Alegre: AMGH, 2016, 940 p.

> <a id="REF2" href="#anchor_2">2.</a>  SERRANO, Milene; SERRANO, Maurício. Requisitos – Aula 15. UnB, 2025. Disponível em: https://aprender3.unb.br/pluginfile.php/3096144/mod_resource/content/1/Requisitos%20-%20Aula%2015a.pdf. Acesso em: 30 de maio 2025.

> <a id="REF3" href="#anchor_3">3.</a> WAKE, Bill. INVEST in Good Stories, and SMART Tasks. Disponível em: https://xp123.com/articles/invest-in-good-stories-and-smart-tasks/. Acesso em: 30 maio 2025.

> <a id="REF4" href="#anchor_4">4.</a> JEFFRIES, Ron. The Three ‘C’s Revisited. Disponível em: https://ronjeffries.com/articles/019-01ff/3cs-revisited/. Acesso em: 30 maio 2025.

##  Bibliografia


##  Histórico de Versão

| Versão | Data       | Descrição                                 | Autor(es)                                     | Revisor(es) |
|--------|------------|--------------------------------------------|-----------------------------------------------|-------------|
| 1.0    | 27/05/2025 | Criação da página | [Enzo Emir](https://github.com/EnzoEmir)     | [Danielle Soares](https://github.com/danielle-soaress)  |
| 1.1    | 27/05/2025 | Adicionando Introdução, Metodologia e Participantes | [Enzo Emir](https://github.com/EnzoEmir)     | [Marcelo Makoto](https://github.com/MM4k) |
| 1.2    | 28/05/2025 | Adicionando Histórias 1 a 6               | [Enzo Emir](https://github.com/EnzoEmir)     | [Marcelo Makoto](https://github.com/MM4k) |
| 1.3    | 28/05/2025 | Adição das Histórias de Usuário 7 a 11               | [Marcelo Makoto](https://github.com/MM4k) | [Danielle Soares](https://github.com/danielle-soaress)  |
| 1.4    | 29/05/2025 | Adição do modelo de tabela | [Danielle Soares](https://github.com/danielle-soaress) | [Maria Eduarda](https://github.com/dudaa28) |
| 1.5    | 30/05/2025 | Adicionando Histórias 12 a 17 | [Danielle Soares](https://github.com/danielle-soaress) | [Maria Eduarda](https://github.com/dudaa28)  |
| 1.6    | 30/05/2025 | Adicionando Histórias 18 a 22 | [Maria Eduarda](https://github.com/dudaa28) | [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa)  |
| 1.7    | 30/05/2025 | Adicionando fonte tabelas | [Maria Eduarda](https://github.com/dudaa28) | [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa)  |
| 1.8    | 30/05/2025 | Atualizando sumário | [Maria Eduarda](https://github.com/dudaa28) | [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa)  |
| 1.9    | 30/05/2025 | Adicionando Histórias 23, 24, 25, 26 e 27 | [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa) | -  |
| 2.0    | 30/05/2025 | Atualizando sumário | [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa)  | - |