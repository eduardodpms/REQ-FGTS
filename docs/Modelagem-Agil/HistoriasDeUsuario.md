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
    <tr><td align="center">Leticia Arisa</td><td align="center">30/05/2025</td><td align="center">07:22</td></tr>
    <tr><td align="center">Marcelo Makoto</td><td align="center">28/05/2025</td><td align="center">21:50</td></tr>
    <tr><td align="center">Maria Eduarda</td><td align="center">30/05/2025</td><td align="center">00:30</td></tr>
    <tr><td align="center">Victor Pontual</td><td align="center">--/05/2025</td><td align="center">00:00</td></tr>
  </tbody>
</table>
</div>

<p align="center">Fonte: <i>Enzo Emir</i></p>

##  Sumário

**Requisito RF08 (IS05, EN02)**

- [H01 – Acompanhar Situação do Saque](#h01)

- [H02 – Exibir Status Atualizado do Saque](#h02)

- [H03 – Notificações Sobre Andamento](#h03)

**Requisito RF01 (EN03)**

- [H04 – Informar Datas de Liberação](#h04)

**Requisito RF02 (EN04)**

- [H19 – Canal de Suporte/Chatbot](#h19)

**Requisito RF03 (EN05)**

- [H15 – Consulta ao Saldo do FGTS](#h13)

**Requisito RF04 (EN06, ST13, ST14)**

- [H17 – Disponibilizar Saque-Aniversário](#h17)

**Requisito RF05 (IS01)**

- [H16 – Atualização de Dados Pessoais](#h16)

**Requisito RF11 (IS08)**

- [H13 – Ver Informações Sobre Saques Bloqueados](#h13)

**Requisito RF17 (IS15)**

- [H05 – Acesso à Seção de Ajuda](#h05)

**Requisito RF19 (IS17)**

- [H06 – Solicitação de Ressarcimento do PIS/PASEP](#h06)

**Requisito RF20 (OB01)**

- [H07 – Login Seguro](#h07)

**Requisito RF15 (IS13)**

- [H08 – Assistente via chat](#h08)

**Requisito RF16 (IS14)**

- [H09 – Campo de busca](#h09)

**Requisito RF24 (OB07)**

- [H10 – Aba de saque](#h10)

**Requisito RF25 (OB09)**

- [H11 – Aba de itens diversos](#h11)

**Requisito RF26 (ST02)**

- [H12 – Resumo dos tipos de saque](#h12)

**Requisito RF27 (ST02)**

- [H21 – Notificações de Status e SaqueS](#h21)

**Requisito RF28 (IS05, EN02)**

- [H22 – Solicitação de Saques](#h22)

**Requisito RF30 (OB07)**

- [H20 – Ajuste de Tamanho de Fonte](#h20)

**Requisito RF31 (IS08)**

- [H23 – Visualização de Dados Bancários](#h23)

**Requisito RF35 (IS12)**

- [H14 – Cadastro de Múltiplas Contas Bancárias](#h14)

**Requisito RF12 (IS09)**
-[H24 – Visualizar histórico de movimentações financeiras](#h24)

**Requisito RF13 (IS10)**
-[H25 – Filtrar extrato por data](#h25)

**Requisito RF21 (OB02)**
-[H26 – Visualizar empregadores anteriores com botão para consultar contas vinculadas](#h26)

**Requisito RF22 (OB05)**
-[H27 – Visualizar nome completo dos empregadores anteriores](#h27)

**Requisito RF23 (OB06)**
-[H28 –  Visualizar histórico de saques realizados](#h28)

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



###  História 01 — Acompanhar Situação do Saque

| Campo                   | Descrição                                                                 |
|-------------------------|---------------------------------------------------------------------------|
| **Requisito**           | RF08 (IS05, EN02)                                                         |
| **Persona**             | Patrícia Nogueira (Técnica de Enfermagem, busca praticidade)              |
| **Desejo / Ação**       | Acompanhar a situação do meu saque do FGTS                                |
| **Objetivo / Benefício**| Saber se está aprovado, em análise ou concluído, sem ir à agência         |
| **Critérios de Aceitação** | - Status exibido claramente (Ex.: “Aguardando análise”, “Aprovado”)  <br> - Mostra possíveis pendências ou exigências  <br> - Atualização automática do status |


### <a name="h02"></a> História 02 — Exibir Status Atualizado do Saque

| Campo                   | Descrição                                                                 |
|-------------------------|---------------------------------------------------------------------------|
| **Requisito**           | RF08 (IS05, EN02)                                                         |
| **Persona**             | Lucas Almeida (Jovem tecnólogo, usuário avançado de apps)                 |
| **Desejo / Ação**       | Visualizar o status atualizado do meu saque do FGTS                       |
| **Objetivo / Benefício**| Ter informações precisas e em tempo real sobre o andamento do processo    |
| **Critérios de Aceitação** | - Status sempre atualizado  <br> - Indicação de bloqueios ou pendências  <br> - Feedback visual com ícones ou cores |



### <a name="h03"></a> História 03 — Notificações Sobre Andamento

| Campo                   | Descrição                                                                 |
|-------------------------|---------------------------------------------------------------------------|
| **Requisito**           | RF08 (IS05, EN02)                                                         |
| **Persona**             | Beatriz Fernandes (Comerciante, rotina corrida)                           |
| **Desejo / Ação**       | Receber notificações sobre o andamento do meu saque do FGTS               |
| **Objetivo / Benefício**| Ser informada de atualizações sem precisar abrir o app constantemente     |
| **Critérios de Aceitação** | - Notificações push quando houver mudança no status  <br> - Mensagens objetivas (Ex.: “Seu saque foi liberado”)  <br> - Opção de ativar/desativar notificações |



### <a name="h04"></a> História 04 — Informar Datas de Liberação

| Campo                   | Descrição                                                                 |
|-------------------------|---------------------------------------------------------------------------|
| **Requisito**           | RF01 (EN03)                                                               |
| **Persona**             | Antônio Ribeiro (Aposentado, baixa autonomia digital)                     |
| **Desejo / Ação**       | Ver as datas previstas para liberação dos valores do FGTS                 |
| **Objetivo / Benefício**| Se organizar financeiramente e pedir ajuda aos filhos, se necessário      |
| **Critérios de Aceitação** | - Exibição da data estimada de liberação  <br> - Alerta caso a data seja alterada  <br> - Informação clara caso a data não esteja definida |



### <a name="h05"></a> História 05 — Acesso à Seção de Ajuda

| Campo                   | Descrição                                                                 |
|-------------------------|---------------------------------------------------------------------------|
| **Requisito**           | RF17 (IS15)                                                               |
| **Persona**             | Patrícia Nogueira                                                         |
| **Desejo / Ação**       | Acessar uma seção de ajuda com orientações sobre FGTS e PIS/PASEP         |
| **Objetivo / Benefício**| Esclarecer dúvidas rapidamente, sem precisar de atendimento presencial    |
| **Critérios de Aceitação** | - FAQ com respostas claras  <br> - Explicações sobre regras de saque, prazos e documentação  <br> - Opção de contato com suporte |



### <a name="h06"></a> História 06 — Solicitação de Ressarcimento do PIS/PASEP

| Campo                   | Descrição                                                                 |
|-------------------------|---------------------------------------------------------------------------|
| **Requisito**           | RF19 (IS17)                                                               |
| **Persona**             | Lucas Almeida                                                             |
| **Desejo / Ação**       | Solicitar o ressarcimento de valores do PIS/PASEP pelo app                |
| **Objetivo / Benefício**| Evitar filas, economizar tempo e resolver tudo digitalmente              |
| **Critérios de Aceitação** | - Formulário simples, com upload de documentos  <br> - Confirmação do envio  <br> - Acompanhamento do andamento no app |



### <a name="h07"></a> História 07 — Login Seguro

| Campo                   | Descrição                                                                 |
|-------------------------|---------------------------------------------------------------------------|
| **Requisito**           | RF20 (OB01)                                                               |
| **Persona**             | Beatriz Fernandes e Antônio Ribeiro                                       |
| **Desejo / Ação**       | Fazer login de forma segura no app                                        |
| **Objetivo / Benefício**| Proteger dados, sem complicações ou esquecimento de senha                 |
| **Critérios de Aceitação** | - Login com biometria, senha ou autenticação de dois fatores (2FA)  <br> - Mensagens claras em caso de erro  <br> - Opção de lembrar acesso ou recuperar senha |



### <a name="h08"></a> História 08 — Assistente via chat

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



### <a name="h09"></a> História 09 — Campo de busca

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



### <a name="h10"></a> História 10 — Aba de solicitação e acompanhamento de saques

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



### <a name="h11"></a> História 11 — Aba de informações adicionais

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



### <a name="h12"></a> História 12 — Resumo dos tipos de saque

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

### <a name="h13"></a> História 13 — Ver Informações Sobre Saques Bloqueados

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

### <a name="h14"></a> História 14 — Cadastro de Múltiplas Contas Bancárias

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

### <a name="h15"></a> História 15 —  Consulta ao Saldo do FGTS

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

### <a name="h16"></a> História 16 — Atualização de Dados Pessoais

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

### <a name="h17"></a> História 17 — Disponibilizar Saque-Aniversário

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

### <a name="h24"></a> História 18 —  

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


### <a name="h19"></a> História 19 — Canal de Suporte/Chatbot 

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

### <a name="h20"></a> História 20 — Ajuste de Tamanho de Fonte 

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

### <a name="h21"></a> História 21 — Notificações de Status e SaqueS 

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

### <a name="h22"></a> História 22 — Solicitação de Saques

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

### <a name="h23"></a> História 23 — Visualização de Dados Bancários 

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

### <a name="h24"></a> História 24 — Visualização do histórico de movimentações financeiras

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

### <a name="h25"></a> História 25 — Filtrar extrato por data

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

### <a name="h26"></a> História 26 — Visualizar empregadores anteriores com botão para consultar contas vinculadas

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

### <a name="h27"></a> História 27 — Visualizar nome completo dos empregadores anteriores

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

### <a name="h28"></a> História 28 — Visualizar histórico de saques realizados

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

### <a name="h29"></a> História 29 —  

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



##  Bibliografia


##  Histórico de Versão

| Versão | Data       | Descrição                                 | Autor(es)                                     | Revisor(es) |
|--------|------------|--------------------------------------------|-----------------------------------------------|-------------|
| 1.0    | 27/05/2025 | Criação da página | [Enzo Emir](https://github.com/EnzoEmir)     | [Danielle Soares](https://github.com/danielle-soaress)  |
| 1.1    | 27/05/2025 | Adicionando Introdução, Metodologia e Participantes | [Enzo Emir](https://github.com/EnzoEmir)     | [Marcelo Makoto](https://github.com/MM4k) |
| 1.2    | 28/05/2025 | Adicionando Histórias 1 a 7               | [Enzo Emir](https://github.com/EnzoEmir)     | [Marcelo Makoto](https://github.com/MM4k) |
| 1.3    | 28/05/2025 | Adição das Histórias de Usuário 8 a 12               | [Marcelo Makoto](https://github.com/MM4k) | [Danielle Soares](https://github.com/danielle-soaress)  |
| 1.4    | 29/05/2025 | Adição do modelo de tabela | [Danielle Soares](https://github.com/danielle-soaress) | [Maria Eduarda](https://github.com/dudaa28) |
| 1.5    | 30/05/2025 | Adicionando Histórias 13 a 18 | [Danielle Soares](https://github.com/danielle-soaress) | [Maria Eduarda](https://github.com/dudaa28)  |
| 1.6    | 30/05/2025 | Adicionando Histórias 19 a 24 | [Maria Eduarda](https://github.com/dudaa28) | [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa)  |
| 1.7    | 30/05/2025 | Adicionando fonte tabelas | [Maria Eduarda](https://github.com/dudaa28) | [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa)  |
| 1.8    | 30/05/2025 | Atualizando sumário | [Maria Eduarda](https://github.com/dudaa28) | [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa)  |
| 1.9    | 30/05/2025 | Adicionando Histórias 24, 25, 26, 27 e 28 | [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa) | -  |
| 2.0    | 30/05/2025 | Atualizando sumário | [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa)  | - |