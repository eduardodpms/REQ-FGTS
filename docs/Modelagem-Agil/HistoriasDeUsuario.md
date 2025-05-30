#  Histórias de Usuário 

##  Introdução

O presente documento tem como objetivo apresentar as histórias de usuário elaboradas para o desenvolvimento de um aplicativo voltado à gestão e acompanhamento de serviços relacionados ao Fundo de Garantia do Tempo de Serviço (FGTS).

As histórias de usuário são uma técnica fundamental no contexto da Engenharia de Requisitos Ágil, cuja finalidade é capturar as necessidades do usuário de maneira simples, objetiva e centrada no valor entregue. Por meio delas, é possível estabelecer uma comunicação clara entre os stakeholders, promovendo entendimento mútuo e alinhamento sobre as funcionalidades que o sistema deverá oferecer.

Cada história de usuário é construída de forma a responder três perguntas essenciais:  

- **Quem?** — Quem é o usuário ou persona envolvida na interação.  

- **O que?** — Qual é a ação, necessidade ou funcionalidade desejada.  

- **Por que?** — Qual é o valor, objetivo ou benefício buscado por meio daquela ação.

##  Metodologia

A elaboração das histórias de usuário deste projeto seguiu uma abordagem centrada no usuário, fundamentada em princípios da Engenharia de Requisitos Ágil e do Design Centrado no Usuário (DCU).

Esta metodologia garantiu que as histórias de usuário fossem elaboradas de forma realista, testável e completamente alinhada às necessidades das personas, criando uma base sólida para o desenvolvimento do aplicativo FGTS.

###  Etapas da Metodologia

**1. Definição das Personas e Antipersonas** 

Foram criadas quatro personas representativas dos usuários do aplicativo FGTS — Lucas, Patrícia, Antônio e Beatriz — além de uma antipersona, Rafael. As personas foram construídas considerando dados como idade, profissão, habilidades digitais, objetivos, dores e expectativas.

**2. Elicitação dos Requisitos** 

Para garantir um entendimento abrangente e realista das necessidades dos usuários, foram aplicadas múltiplas técnicas de elicitação de requisitos:

- **Entrevista:** Conversas diretas com usuários para compreender suas necessidades, expectativas e dificuldades no acesso aos serviços do FGTS.

- **Introspecção:** Reflexão baseada na própria experiência dos desenvolvedores e idealizadores do projeto, identificando possíveis problemas e melhorias.

- **Observação:** Análise de como diferentes perfis de usuários interagem com aplicativos semelhantes e como realizam tarefas relacionadas ao FGTS no dia a dia.

- **Storytelling:** Construção de narrativas que simulam cenários reais de uso do aplicativo, explorando jornadas, dificuldades e expectativas dos usuários.

**3. Construção das Histórias de Usuário**  

As histórias de usuário foram escritas seguindo o modelo clássico:

> **Como [usuário], quero [ação], para [atingir um objetivo].**

Essa estrutura ajuda a garantir que cada história represente uma necessidade real do usuário, deixando claro o objetivo e o valor gerado pela funcionalidade.

**4. Aplicação dos Modelos Ágeis**  

Todas as histórias de usuário foram estruturadas e avaliadas com base em dois modelos consagrados no desenvolvimento ágil: **INVEST** e **3C’s**.

**INVEST (Wake, 2003):** Esse modelo estabelece seis critérios fundamentais que garantem a qualidade e a eficácia de uma história de usuário:

- **I — Independente:** A história não deve depender de outras para ser desenvolvida, implementada ou testada.

- **N — Negociável:** As histórias são flexíveis e abertas a discussões, podendo ser refinadas durante as interações entre a equipe e os stakeholders.

- **V — Valiosa:** A história deve gerar valor perceptível e concreto para o usuário final ou para o negócio.

- **E — Estimável:** A história deve ser suficientemente clara e bem definida para permitir a estimativa do esforço necessário para sua implementação.

- **S — Sucinta (Small):** A história deve ter um tamanho adequado, podendo ser desenvolvida dentro de um ciclo ágil (sprint), evitando ser muito grande ou complexa.

- **T — Testável:** Deve possuir critérios de aceitação claros e objetivos, que permitam verificar se a funcionalidade atende às necessidades da persona e aos requisitos definidos.  

**3C’s (Jeffries, 2001):** Esse modelo complementa o INVEST ao enfatizar três elementos essenciais na construção de uma boa história de usuário:

- **Card (Cartão):** Representa a história em si, seja em um post-it físico ou em um quadro digital, funcionando como um lembrete do que precisa ser desenvolvido.

- **Conversation (Conversa):** Refere-se às discussões colaborativas entre equipe de desenvolvimento, Product Owner e stakeholders, nas quais são esclarecidos os detalhes, as dúvidas e as regras de negócio associadas à história.

- **Confirmation (Confirmação):** Corresponde aos critérios de aceitação formalmente definidos, que validam que a história foi corretamente implementada, atendendo às expectativas e às necessidades do usuário.

**5. Definição dos Critérios de Aceitação:**  
Para cada história, foram definidos critérios claros e objetivos que garantem que a funcionalidade atende às expectativas da persona. Isso permite também verificar se a história foi corretamente implementada.


##  Antipersona (Limitação)

- **Rafael Moreira**, agricultor informal, não utiliza serviços digitais. Portanto, o aplicativo não é projetado para atender este perfil, que prefere atendimento presencial e suporte humano direto.

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
    <tr><td align="center">Leticia Arisa</td><td align="center">--/05/2025</td><td align="center">00:00</td></tr>
    <tr><td align="center">Marcelo Makoto</td><td align="center">28/05/2025</td><td align="center">21:50</td></tr>
    <tr><td align="center">Maria Eduarda</td><td align="center">--/05/2025</td><td align="center">00:00</td></tr>
    <tr><td align="center">Victor Pontual</td><td align="center">--/05/2025</td><td align="center">00:00</td></tr>
  </tbody>
</table>
</div>

<p align="center">Fonte: <i>Enzo Emir</i></p>

##  Sumário

**Requisito RF08 (IS05, EN02):**
- [H01 – Acompanhar Situação do Saque](#h01)
- [H02 – Exibir Status Atualizado do Saque](#h02)
- [H03 – Notificações Sobre Andamento](#h03)

**Requisito RF01 (EN03):**
- [H04 – Informar Datas de Liberação](#h04)

**Requisito RF03 (EN05):**
- [H04 – Informar Datas de Liberação](#h04)

**Requisito RF04 (EN06, ST13, ST14):**
- [H04 – Informar Datas de Liberação](#h04)

**Requisito RF05 (IS01):**
- [H04 – Informar Datas de Liberação](#h04)

**Requisito RF11 (IS08):**
- [H04 – Informar Datas de Liberação](#h04)

**Requisito RF17 (IS15):**
- [H05 – Acesso à Seção de Ajuda](#h05)

**Requisito RF19 (IS17):**
- [H06 – Solicitação de Ressarcimento do PIS/PASEP](#h06)

**Requisito RF20 (OB01):**
- [H07 – Login Seguro](#h07)

**Requisito RF15 (IS13):**
- [H08 – Assistente via chat](#h08)

**Requisito RF16 (IS14):**
- [H09 – Campo de busca](#h09)

**Requisito RF24 (OB07):**
- [H10 – Aba de saque](#h10)

**Requisito RF25 (OB09):**
- [H11 – Aba de itens diversos](#h11)

**Requisito RF26 (ST02):**
- [H12 – Resumo dos tipos de saque](#h12)

**Requisito RF35 (IS12):**
- [H04 – Informar Datas de Liberação](#h04)

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

---


### <a name="h01"></a> História 01 — Acompanhar Situação do Saque

| Campo                   | Descrição                                                                 |
|-------------------------|---------------------------------------------------------------------------|
| **Requisito**           | RF08 (IS05, EN02)                                                         |
| **Persona**             | Patrícia Nogueira (Técnica de Enfermagem, busca praticidade)              |
| **Desejo / Ação**       | Acompanhar a situação do meu saque do FGTS                                |
| **Objetivo / Benefício**| Saber se está aprovado, em análise ou concluído, sem ir à agência         |
| **Critérios de Aceitação** | - Status exibido claramente (Ex.: “Aguardando análise”, “Aprovado”)  <br> - Mostra possíveis pendências ou exigências  <br> - Atualização automática do status |


---

### <a name="h01"></a> História 01 — Acompanhar Situação do Saque

| Campo                   | Descrição                                                                 |
|-------------------------|---------------------------------------------------------------------------|
| **Requisito**           | RF08 (IS05, EN02)                                                         |
| **Persona**             | Patrícia Nogueira (Técnica de Enfermagem, busca praticidade)              |
| **Desejo / Ação**       | Acompanhar a situação do meu saque do FGTS                                |
| **Objetivo / Benefício**| Saber se está aprovado, em análise ou concluído, sem ir à agência         |
| **Critérios de Aceitação** | - Status exibido claramente (Ex.: “Aguardando análise”, “Aprovado”)  <br> - Mostra possíveis pendências ou exigências  <br> - Atualização automática do status |


---

### <a name="h01"></a> História 01 — Acompanhar Situação do Saque

| Campo                   | Descrição                                                                 |
|-------------------------|---------------------------------------------------------------------------|
| **Requisito**           | RF08 (IS05, EN02)                                                         |
| **Persona**             | Patrícia Nogueira (Técnica de Enfermagem, busca praticidade)              |
| **Desejo / Ação**       | Acompanhar a situação do meu saque do FGTS                                |
| **Objetivo / Benefício**| Saber se está aprovado, em análise ou concluído, sem ir à agência         |
| **Critérios de Aceitação** | - Status exibido claramente (Ex.: “Aguardando análise”, “Aprovado”)  <br> - Mostra possíveis pendências ou exigências  <br> - Atualização automática do status |

---

### <a name="h02"></a> História 02 — Exibir Status Atualizado do Saque

| Campo                   | Descrição                                                                 |
|-------------------------|---------------------------------------------------------------------------|
| **Requisito**           | RF08 (IS05, EN02)                                                         |
| **Persona**             | Lucas Almeida (Jovem tecnólogo, usuário avançado de apps)                 |
| **Desejo / Ação**       | Visualizar o status atualizado do meu saque do FGTS                       |
| **Objetivo / Benefício**| Ter informações precisas e em tempo real sobre o andamento do processo    |
| **Critérios de Aceitação** | - Status sempre atualizado  <br> - Indicação de bloqueios ou pendências  <br> - Feedback visual com ícones ou cores |

---

### <a name="h03"></a> História 03 — Notificações Sobre Andamento

| Campo                   | Descrição                                                                 |
|-------------------------|---------------------------------------------------------------------------|
| **Requisito**           | RF08 (IS05, EN02)                                                         |
| **Persona**             | Beatriz Fernandes (Comerciante, rotina corrida)                           |
| **Desejo / Ação**       | Receber notificações sobre o andamento do meu saque do FGTS               |
| **Objetivo / Benefício**| Ser informada de atualizações sem precisar abrir o app constantemente     |
| **Critérios de Aceitação** | - Notificações push quando houver mudança no status  <br> - Mensagens objetivas (Ex.: “Seu saque foi liberado”)  <br> - Opção de ativar/desativar notificações |

---

### <a name="h04"></a> História 04 — Informar Datas de Liberação

| Campo                   | Descrição                                                                 |
|-------------------------|---------------------------------------------------------------------------|
| **Requisito**           | RF01 (EN03)                                                               |
| **Persona**             | Antônio Ribeiro (Aposentado, baixa autonomia digital)                     |
| **Desejo / Ação**       | Ver as datas previstas para liberação dos valores do FGTS                 |
| **Objetivo / Benefício**| Se organizar financeiramente e pedir ajuda aos filhos, se necessário      |
| **Critérios de Aceitação** | - Exibição da data estimada de liberação  <br> - Alerta caso a data seja alterada  <br> - Informação clara caso a data não esteja definida |

---

### <a name="h05"></a> História 05 — Acesso à Seção de Ajuda

| Campo                   | Descrição                                                                 |
|-------------------------|---------------------------------------------------------------------------|
| **Requisito**           | RF17 (IS15)                                                               |
| **Persona**             | Patrícia Nogueira                                                         |
| **Desejo / Ação**       | Acessar uma seção de ajuda com orientações sobre FGTS e PIS/PASEP         |
| **Objetivo / Benefício**| Esclarecer dúvidas rapidamente, sem precisar de atendimento presencial    |
| **Critérios de Aceitação** | - FAQ com respostas claras  <br> - Explicações sobre regras de saque, prazos e documentação  <br> - Opção de contato com suporte |

---

### <a name="h06"></a> História 06 — Solicitação de Ressarcimento do PIS/PASEP

| Campo                   | Descrição                                                                 |
|-------------------------|---------------------------------------------------------------------------|
| **Requisito**           | RF19 (IS17)                                                               |
| **Persona**             | Lucas Almeida                                                             |
| **Desejo / Ação**       | Solicitar o ressarcimento de valores do PIS/PASEP pelo app                |
| **Objetivo / Benefício**| Evitar filas, economizar tempo e resolver tudo digitalmente              |
| **Critérios de Aceitação** | - Formulário simples, com upload de documentos  <br> - Confirmação do envio  <br> - Acompanhamento do andamento no app |

---

### <a name="h07"></a> História 07 — Login Seguro

| Campo                   | Descrição                                                                 |
|-------------------------|---------------------------------------------------------------------------|
| **Requisito**           | RF20 (OB01)                                                               |
| **Persona**             | Beatriz Fernandes e Antônio Ribeiro                                       |
| **Desejo / Ação**       | Fazer login de forma segura no app                                        |
| **Objetivo / Benefício**| Proteger dados, sem complicações ou esquecimento de senha                 |
| **Critérios de Aceitação** | - Login com biometria, senha ou autenticação de dois fatores (2FA)  <br> - Mensagens claras em caso de erro  <br> - Opção de lembrar acesso ou recuperar senha |

---

### <a name="h08"></a> História 08 — Assistente via chat

| Campo                   | Descrição                                                                                   |
|-------------------------|---------------------------------------------------------------------------------------------|
| **Requisito**           | RF15 (IS13)                                                                                 |
| **Persona**             | Antônio Ribeiro (Aposentado, baixa autonomia digital)                                       |
| **Desejo / Ação**       | Permitir que minha filha tire dúvidas no aplicativo usando um chat                          |
| **Objetivo / Benefício**| Conseguir ajuda com os procedimentos sem precisar ir até a Caixa                            |
| **Critérios de Aceitação** | - Acesso fácil ao botão de chat  <br> - Atendimento humanizado ou por IA com linguagem simples <br> - Histórico de conversas acessível e contínuo |

<font size="2"><p style="text-align: center">Fonte: [Marcelo Makoto](https://github.com/MM4k)</p></font>

---

### <a name="h09"></a> História 09 — Campo de busca

| Campo                   | Descrição                                                                                   |
|-------------------------|---------------------------------------------------------------------------------------------|
| **Requisito**           | RF16 (IS14)                                                                                 |
| **Persona**             | Lucas Almeida (Técnico em redes, domínio de apps e finanças)                                |
| **Desejo / Ação**       | Buscar rapidamente funções como extrato ou sistemática de saque                             |
| **Objetivo / Benefício**| Acessar diretamente o que preciso sem navegar por várias telas                              |
| **Critérios de Aceitação** | - Campo de busca disponível no topo da tela  <br> - Sugestões automáticas conforme digitação <br> - Resultados exibidos de forma clara e navegável |

<font size="2"><p style="text-align: center">Fonte: [Marcelo Makoto](https://github.com/MM4k)</p></font>

---

### <a name="h10"></a> História 10 — Aba de saque

| Campo                   | Descrição                                                                                   |
|-------------------------|---------------------------------------------------------------------------------------------|
| **Requisito**           | RF24 (OB07)                                                                                 |
| **Persona**             | Patrícia Nogueira (Técnica de Enfermagem, busca praticidade)                                |
| **Desejo / Ação**       | Ter uma aba só para ver e pedir saques do FGTS                                              |
| **Objetivo / Benefício**| Conseguir fazer tudo relacionado ao saque de forma simples e rápida                         |
| **Critérios de Aceitação** | - Aba destacada com ícone intuitivo  <br> - Permite solicitar saque e ver andamento <br> - Informações de saque organizadas em uma só tela |

<font size="2"><p style="text-align: center">Fonte: [Marcelo Makoto](https://github.com/MM4k)</p></font>

---

### <a name="h11"></a> História 11 — Aba de itens diversos

| Campo                   | Descrição                                                                                   |
|-------------------------|---------------------------------------------------------------------------------------------|
| **Requisito**           | RF25 (OB09)                                                                                 |
| **Persona**             | Beatriz Fernandes (Comerciante, uso moderado de apps)                                       |
| **Desejo / Ação**       | Acessar informações como PIS, regras do FGTS e ajuda sem complicação                        |
| **Objetivo / Benefício**| Entender outras funcionalidades do app sem perder tempo procurando                         |
| **Critérios de Aceitação** | - Aba com título e ícone claros (Ex.: “Mais opções”)  <br> - Tópicos organizados por categorias <br> - Explicações curtas e visuais |

<font size="2"><p style="text-align: center">Fonte: [Marcelo Makoto](https://github.com/MM4k)</p></font>

---

### <a name="h12"></a> História 12 — Resumo dos tipos de saque

| Campo                   | Descrição                                                                                   |
|-------------------------|---------------------------------------------------------------------------------------------|
| **Requisito**           | RF26 (ST02)                                                                                 |
| **Persona**             | Lucas Almeida (Técnico em redes, domínio de apps e finanças)                                |
| **Desejo / Ação**       | Ver um resumo dos tipos de saque disponíveis no app                                         |
| **Objetivo / Benefício**| Escolher com clareza entre saque-aniversário ou por rescisão                                |
| **Critérios de Aceitação** | - Tabela ou cards explicando os tipos de saque  <br> - Comparação entre regras e prazos <br> - Link direto para alterar a sistemática escolhida |

<font size="2"><p style="text-align: center">Fonte: [Marcelo Makoto](https://github.com/MM4k)</p></font>

### <a name="h13"></a> História 13 — Ver Informações Sobre Saques Bloqueados

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

### <a name="h14"></a> História 14 — Cadastro de Múltiplas Contas Bancárias

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

### <a name="h15"></a> História 15 —  Consulta ao Saldo do FGTS

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

### <a name="h16"></a> História 16 — Atualização de Dados Pessoais

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

### <a name="h17"></a> História 17 — Disponibilizar Saque-Aniversário

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

---

##  Bibliografia

---

##  Histórico de Versão

| Versão | Data       | Descrição                                 | Autor(es)                                     | Revisor(es) |
|--------|------------|--------------------------------------------|-----------------------------------------------|-------------|
| 1.0    | 27/05/2025 | Criação da página | [Enzo Emir](https://github.com/EnzoEmir)     | [Danielle Soares](https://github.com/danielle-soaress)  |
| 1.1    | 27/05/2025 | Adicionando Introdução, Metodologia e Participantes | [Enzo Emir](https://github.com/EnzoEmir)     | [Marcelo Makoto](https://github.com/MM4k) |
| 1.2    | 28/05/2025 | Adicionando Histórias 1 a 7               | [Enzo Emir](https://github.com/EnzoEmir)     | [Marcelo Makoto](https://github.com/MM4k) |
| 1.3    | 28/05/2025 | Adição das Histórias de Usuário 8 a 12               | [Marcelo Makoto](https://github.com/MM4k) | [Danielle Soares](https://github.com/danielle-soaress)  |
| 1.4    | 29/05/2025 | Adição do modelo de tabela | [Danielle Soares](https://github.com/danielle-soaress) | -  |
| 1.5    | 30/05/2025 | Adicionando Histórias 13 a 18 | [Danielle Soares](https://github.com/danielle-soaress) | -  |

