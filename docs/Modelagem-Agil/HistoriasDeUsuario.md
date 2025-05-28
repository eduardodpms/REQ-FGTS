#  Histórias de Usuário 

##  Introdução

O presente documento tem como objetivo apresentar as histórias de usuário elaboradas para o desenvolvimento de um aplicativo voltado à gestão e acompanhamento de serviços relacionados ao Fundo de Garantia do Tempo de Serviço (FGTS).

As histórias de usuário são uma técnica fundamental no contexto da Engenharia de Requisitos Ágil, cuja finalidade é capturar as necessidades do usuário de maneira simples, objetiva e centrada no valor entregue. Por meio delas, é possível estabelecer uma comunicação clara entre os stakeholders, promovendo entendimento mútuo e alinhamento sobre as funcionalidades que o sistema deverá oferecer.

Cada história de usuário é construída de forma a responder três perguntas essenciais:  
- **Quem?** — Quem é o usuário ou persona envolvida na interação.  
- **O que?** — Qual é a ação, necessidade ou funcionalidade desejada.  
- **Por que?** — Qual é o valor, objetivo ou benefício buscado por meio daquela ação.

---

##  Metodologia

A elaboração das histórias de usuário deste projeto seguiu uma abordagem centrada no usuário, fundamentada em princípios da Engenharia de Requisitos Ágil e do Design Centrado no Usuário (DCU).

###  Etapas da Metodologia

**Definição das Personas:**  
Foram criadas quatro personas representativas dos usuários do aplicativo FGTS — Lucas, Patrícia, Antônio e Beatriz — além de uma antipersona, Rafael. As personas foram construídas considerando dados como idade, profissão, habilidades digitais, objetivos, dores e expectativas.

**Elicitação dos Requisitos:**  
Para garantir um entendimento abrangente e realista das necessidades dos usuários, foram aplicadas múltiplas técnicas de elicitação de requisitos:  
- **Entrevista:** Conversas diretas com usuários para compreender suas necessidades, expectativas e dificuldades no acesso aos serviços do FGTS.  
- **Introspecção:** Reflexão baseada na própria experiência dos desenvolvedores e idealizadores do projeto, identificando possíveis problemas e melhorias.  
- **Observação:** Análise de como diferentes perfis de usuários interagem com aplicativos semelhantes e como realizam tarefas relacionadas ao FGTS no dia a dia.  
- **Storytelling:** Construção de narrativas que simulam cenários reais de uso do aplicativo, explorando jornadas, dificuldades e expectativas dos usuários.

**Construção das Histórias de Usuário:**  
As histórias de usuário foram elaboradas utilizando o modelo clássico:  
**“Como [persona], quero [ação] para [benefício].”**  
Essa estrutura garante que cada história reflita uma necessidade real do usuário, com clareza no objetivo e no valor entregue.

**Aplicação dos Modelos Ágeis:**  
Todas as histórias de usuário foram estruturadas e avaliadas com base em dois modelos consagrados no desenvolvimento ágil: **INVEST** e **3C’s**.  

- **INVEST (Wake, 2003):**  
Esse modelo estabelece seis critérios fundamentais que garantem a qualidade e a eficácia de uma história de usuário:  
  - **I — Independente:** A história não deve depender de outras para ser desenvolvida, implementada ou testada.  
  - **N — Negociável:** As histórias são flexíveis e abertas a discussões, podendo ser refinadas durante as interações entre a equipe e os stakeholders.  
  - **V — Valiosa:** A história deve gerar valor perceptível e concreto para o usuário final ou para o negócio.  
  - **E — Estimável:** A história deve ser suficientemente clara e bem definida para permitir a estimativa do esforço necessário para sua implementação.  
  - **S — Sucinta (Small):** A história deve ter um tamanho adequado, podendo ser desenvolvida dentro de um ciclo ágil (sprint), evitando ser muito grande ou complexa.  
  - **T — Testável:** Deve possuir critérios de aceitação claros e objetivos, que permitam verificar se a funcionalidade atende às necessidades da persona e aos requisitos definidos.  

- **3C’s (Jeffries, 2001):**  
Esse modelo complementa o INVEST ao enfatizar três elementos essenciais na construção de uma boa história de usuário:  
  - **Card (Cartão):** Representa a história em si, seja em um post-it físico ou em um quadro digital, funcionando como um lembrete do que precisa ser desenvolvido.  
  - **Conversation (Conversa):** Refere-se às discussões colaborativas entre equipe de desenvolvimento, Product Owner e stakeholders, nas quais são esclarecidos os detalhes, as dúvidas e as regras de negócio associadas à história.  
  - **Confirmation (Confirmação):** Corresponde aos critérios de aceitação formalmente definidos, que validam que a história foi corretamente implementada, atendendo às expectativas e às necessidades do usuário.

**Definição dos Critérios de Aceitação:**  
Para cada história, foram definidos critérios claros e objetivos que garantem que a funcionalidade atende às expectativas da persona. Isso permite também verificar se a história foi corretamente implementada.

---

Esta metodologia garantiu que as histórias de usuário fossem elaboradas de forma realista, testável e completamente alinhada às necessidades das personas, criando uma base sólida para o desenvolvimento do aplicativo FGTS.

---

##  Antipersona (Limitação)

- **Rafael Moreira**, agricultor informal, não utiliza serviços digitais. Portanto, o aplicativo não é projetado para atender este perfil, que prefere atendimento presencial e suporte humano direto.

---

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
      <td>Danielle Soares</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>Eduardo de Pina</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>Enzo Emir</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>Leticia Arisa</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>Marcelo Makoto</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>Maria Eduarda</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>Victor Pontual</td>
      <td>-</td>
      <td>-</td>
    </tr>
  </tbody>
</table>

<p style="text-align: center; font-size: 16px;">Fonte: <i>Enzo Emir</i></p>

---

## Sumário


**Requisito RF08 (IS05, EN02):**
- [H01 – Acompanhar Situação do Saque](#história-01--acompanhar-situação-do-saque)
- [H02 – Exibir Status Atualizado do Saque](#história-02--exibir-status-atualizado-do-saque)
- [H03 – Notificações Sobre Andamento](#história-03--notificações-sobre-andamento)

**Requisito RF01 (EN03):**
- [H04 – Informar Datas de Liberação](#história-04--informar-datas-de-liberação)

**Requisito RF17 (IS15):**
- [H05 – Acesso à Seção de Ajuda](#história-05--acesso-à-seção-de-ajuda)

**Requisito RF19 (IS17):**
- [H06 – Solicitação de Ressarcimento do PIS/PASEP](#história-06--solicitação-de-ressarcimento-do-pispasep)

**Requisito RF20 (OB01):**
- [H07 – Login Seguro](#história-07--login-seguro)

---

##  Histórias de Usuário


###  História 01 — Acompanhar Situação do Saque

| Campo                   | Descrição                                                                 |
|-------------------------|---------------------------------------------------------------------------|
| **Requisito**           | RF08 (IS05, EN02)                                                         |
| **Persona**             | Patrícia Nogueira (Técnica de Enfermagem, busca praticidade)              |
| **Desejo / Ação**       | Acompanhar a situação do meu saque do FGTS                                |
| **Objetivo / Benefício**| Saber se está aprovado, em análise ou concluído, sem ir à agência         |
| **Critérios de Aceitação** | - Status exibido claramente (Ex.: “Aguardando análise”, “Aprovado”)  <br> - Mostra possíveis pendências ou exigências  <br> - Atualização automática do status |

---

###  História 02 — Exibir Status Atualizado do Saque

| Campo                   | Descrição                                                                 |
|-------------------------|---------------------------------------------------------------------------|
| **Requisito**           | RF08 (IS05, EN02)                                                         |
| **Persona**             | Lucas Almeida (Jovem tecnólogo, usuário avançado de apps)                 |
| **Desejo / Ação**       | Visualizar o status atualizado do meu saque do FGTS                       |
| **Objetivo / Benefício**| Ter informações precisas e em tempo real sobre o andamento do processo    |
| **Critérios de Aceitação** | - Status sempre atualizado  <br> - Indicação de bloqueios ou pendências  <br> - Feedback visual com ícones ou cores |

---

###  História 03 — Notificações Sobre Andamento

| Campo                   | Descrição                                                                 |
|-------------------------|---------------------------------------------------------------------------|
| **Requisito**           | RF08 (IS05, EN02)                                                         |
| **Persona**             | Beatriz Fernandes (Comerciante, rotina corrida)                           |
| **Desejo / Ação**       | Receber notificações sobre o andamento do meu saque do FGTS               |
| **Objetivo / Benefício**| Ser informada de atualizações sem precisar abrir o app constantemente     |
| **Critérios de Aceitação** | - Notificações push quando houver mudança no status  <br> - Mensagens objetivas (Ex.: “Seu saque foi liberado”)  <br> - Opção de ativar/desativar notificações |

---

###  História 04 — Informar Datas de Liberação

| Campo                   | Descrição                                                                 |
|-------------------------|---------------------------------------------------------------------------|
| **Requisito**           | RF01 (EN03)                                                               |
| **Persona**             | Antônio Ribeiro (Aposentado, baixa autonomia digital)                     |
| **Desejo / Ação**       | Ver as datas previstas para liberação dos valores do FGTS                 |
| **Objetivo / Benefício**| Se organizar financeiramente e pedir ajuda aos filhos, se necessário      |
| **Critérios de Aceitação** | - Exibição da data estimada de liberação  <br> - Alerta caso a data seja alterada  <br> - Informação clara caso a data não esteja definida |

---

###  História 05 — Acesso à Seção de Ajuda

| Campo                   | Descrição                                                                 |
|-------------------------|---------------------------------------------------------------------------|
| **Requisito**           | RF17 (IS15)                                                               |
| **Persona**             | Patrícia Nogueira                                                         |
| **Desejo / Ação**       | Acessar uma seção de ajuda com orientações sobre FGTS e PIS/PASEP         |
| **Objetivo / Benefício**| Esclarecer dúvidas rapidamente, sem precisar de atendimento presencial    |
| **Critérios de Aceitação** | - FAQ com respostas claras  <br> - Explicações sobre regras de saque, prazos e documentação  <br> - Opção de contato com suporte |

---

###  História 06 — Solicitação de Ressarcimento do PIS/PASEP

| Campo                   | Descrição                                                                 |
|-------------------------|---------------------------------------------------------------------------|
| **Requisito**           | RF19 (IS17)                                                               |
| **Persona**             | Lucas Almeida                                                             |
| **Desejo / Ação**       | Solicitar o ressarcimento de valores do PIS/PASEP pelo app                |
| **Objetivo / Benefício**| Evitar filas, economizar tempo e resolver tudo digitalmente              |
| **Critérios de Aceitação** | - Formulário simples, com upload de documentos  <br> - Confirmação do envio  <br> - Acompanhamento do andamento no app |

---

###  História 07 — Login Seguro

| Campo                   | Descrição                                                                 |
|-------------------------|---------------------------------------------------------------------------|
| **Requisito**           | RF20 (OB01)                                                               |
| **Persona**             | Beatriz Fernandes e Antônio Ribeiro                                       |
| **Desejo / Ação**       | Fazer login de forma segura no app                                        |
| **Objetivo / Benefício**| Proteger dados, sem complicações ou esquecimento de senha                 |
| **Critérios de Aceitação** | - Login com biometria, senha ou autenticação de dois fatores (2FA)  <br> - Mensagens claras em caso de erro  <br> - Opção de lembrar acesso ou recuperar senha |


##  Bibliografia

---

##  Histórico de Versão

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| :-: | :-: | :-: | :-: | :-: |
| `1.0` | 27/05/2025 | Adicionando Introdução, Metodologia e Tabela de Participantes | [Enzo Emir](https://github.com/EnzoEmir) | - |
| `1.0` | 28/05/2025 | Adicionando Histórias 1 a 7 | [Enzo Emir](https://github.com/EnzoEmir) | - |