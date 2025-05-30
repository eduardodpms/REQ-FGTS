# Backlog

## Introdução

O *Product Backlog* representa o registro contínuo e priorizado de todos os requisitos e funcionalidades do projeto que prometem agregar valor comercial para o cliente <a id="anchor_1" href="#REF1">1</a>. Assim, este artefato é dinâmico, permitindo que novos itens sejam incluídos a qualquer momento, o que facilita a incorporação de mudanças e novas ideias. Além disso, a gestão e a redefinição das prioridades no backlog são responsabilidade do gerente de produto _(Product Owner)_, que o avalia regularmente para otimizar o fluxo de trabalho. <a id="anchor_2" href="#REF2">2</a>

## Metodologia

A construção do nosso *Product Backlog* teve início com as reuniões realizadas juntamente ao *Product Owner* (PO). Durante esses encontros, o PO apresentava as funcionalidades esperadas para o sistema, enquanto os membros da equipe registravam as informações e levantavam dúvidas com o objetivo de refinar o entendimento. A partir dessas interações, as funcionalidades foram modeladas em Histórias de Usuário, utilizando a estrutura "Como um [tipo de usuário], eu desejo [ação] para [benefício]". Para cada história elaborada, foram definidos critérios de aceitação bem delineados, os quais orientaram o desenvolvimento e a validação das entregas.

Com as histórias devidamente documentadas, o PO procedeu à sua priorização segundo a abordagem Three Level Scale, categorizando-as conforme o impacto no produto: Alta, Média ou Baixa prioridade. Em seguida, as histórias foram organizadas de forma hierárquica em temas e épicos, adotando uma estrutura amplamente utilizada em abordagens ágeis como o Scrum e o SAFe (Scaled Agile Framework). Neste documento, foi utilizado o padrão Tema → Épico → Histórias de Usuário, conforme descrito pelos autores Milene Serrano e Maurício Serrano <a id="anchor_2" href="#REF2">2</a>. Essa estruturação permite uma visão macro do escopo do projeto, facilita o alinhamento de expectativas entre os envolvidos e orienta o planejamento das etapas subsequentes. Por fim, o detalhamento individual de cada história de usuário pode ser consultado diretamente no respectivo artefato vinculado.

<font size="3"><p style="text-align: center">Tabela 1: Participantes</p></font>

<center>
    <table>
    <thead>
        <tr>
        <th>Participante</th>
        <th>Função</th>
        </tr>
    </thead>
    <tbody>
        <tr>
        <td>Danielle Soares</td>
        <td></td>
        </tr>
        <tr>
        <td>Eduardo de Pina</td>
        <td></td>
        </tr>
        <tr>
        <td>Enzo Emir</td>
        <td></td>
        </tr>
        <tr>
        <td>Leticia Arisa</td>
        <td></td>
        </tr>
        <tr>
        <td>Marcelo Makoto</td>
        <td></td>
        </tr>
        <tr>
        <td>Maria Eduarda</td>
        <td></td>
        </tr>
        <tr>
        <td>Victor Pontual</td>
        <td></td>
        </tr>
    </tbody>
    </table>
</center>

<font size="2"><p style="text-align: center">Fonte: [Danielle Soares](https://github.com/danielle-soaress)</p></font>

---

## Temas

Após a análise e organização dos requisitos coletados para o aplicativo FGTS, foi possível agrupá-los em cinco grandes temas. Esses temas representam o nível mais alto de abstração e refletem as áreas principais de funcionalidade do sistema, facilitando a visualização geral das demandas. São eles:

- **Tema 1:** Gestão de Conta e Dados Pessoais

- **Tema 2:** Consulta e Acompanhamento de Saldo e Saques

- **Tema 3:** Interface e Usabilidade

- **Tema 4:** Comunicação e Suporte

- **Tema 5:** Funcionalidades Complementares


## Épicos

Para detalhar os temas, os requisitos foram desmembrados em épicos — agrupamentos de funcionalidades que representam grandes blocos de trabalho, com um nível intermediário de especificação. Abaixo, estão todos os épicos utilizados:

### Tema 1: Consulta e Informações da Conta

- **E01 - Consulta de saldo e extrato**  
  *Eu, como usuário, desejo consultar o saldo da conta vinculada e visualizar extratos detalhados para acompanhar meus recursos.*

- **E02 - Consulta de dados pessoais**  
  *Eu, como usuário, desejo visualizar e atualizar meus dados pessoais para manter as informações atualizadas.*

- **E03 - Histórico de movimentações financeiras**  
  *Eu, como usuário, desejo acessar o histórico completo de movimentações financeiras para controle e transparência.*

### Tema 2: Saques e Solicitações

- **E04 - Solicitação e acompanhamento de saques**  
  *Eu, como usuário, desejo solicitar saques e acompanhar o status para gerenciar meus recursos.*

- **E05 - Cancelamento e filtro de saques**  
  *Eu, como usuário, desejo cancelar solicitações de saque e filtrar os saques por tipo e data para facilitar o controle.*

- **E06 - Informação sobre bloqueios e motivos**  
  *Eu, como usuário, desejo ser informado sobre saques bloqueados e seus motivos para entender impedimentos.*

- **E07 - Guias e ajuda para o processo de saque**  
  *Eu, como usuário, desejo contar com guias interativos e seções de ajuda para facilitar a solicitação dos saques.*

### Tema 3: Contas Bancárias

- **E08 - Cadastro e gerenciamento de contas bancárias**  
  *Eu, como usuário, desejo cadastrar e gerenciar múltiplas contas bancárias para facilitar o recebimento dos valores.*

### Tema 4: Comunicação e Suporte

- **E09 - Suporte via chat e canal de atendimento**  
  *Eu, como usuário, desejo ter acesso a suporte via chatbot ou assistente para esclarecer dúvidas rapidamente.*

- **E10 - Notificações e avisos**  
  *Eu, como usuário, desejo receber notificações sobre o status dos saques e outras atualizações importantes.*

### Tema 5: Usabilidade e Acessibilidade

- **E11 - Personalização da interface**  
  *Eu, como usuário, desejo ajustar o tamanho das fontes e utilizar uma interface simples para melhorar a experiência.*

- **E12 - Busca e navegação**  
  *Eu, como usuário, desejo dispor de um campo de busca e navegação clara para encontrar funcionalidades facilmente.*


---

## Backlog

<font size="3"><p style="text-align: center">Tabela 2: Backlog</p></font>

<table border="1" cellpadding="4" cellspacing="0">
  <thead>
    <tr>
      <th>Tema</th>
      <th>Épico</th>
      <th>História de Usuário</th>
      <th>ID</th>
      <th>Prioridade</th>
      <th>Origem</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="11">Consulta e Informações da Conta</td>
      <td>Consulta de saldo e extrato</td>
      <td></td>
      <td>RF03</td>
      <td></td>
      <td>EN05</td>
    </tr>
    <tr>
      <td>Consulta de saldo e extrato</td>
      <td></td>
      <td>RF07</td>
      <td></td>
      <td>IS04, OB04</td>
    </tr>
    <tr>
      <td>Consulta de dados pessoais</td>
      <td></td>
      <td>RF05</td>
      <td></td>
      <td>IS01</td>
    </tr>
    <tr>
      <td>Consulta de dados pessoais</td>
      <td></td>
      <td>RF06</td>
      <td></td>
      <td>IS02</td>
    </tr>
    <tr>
      <td>Consulta de histórico de movimentações</td>
      <td></td>
      <td>RF12</td>
      <td></td>
      <td>IS09</td>
    </tr>
    <tr>
      <td>Consulta de histórico de movimentações</td>
      <td></td>
      <td>RF13</td>
      <td></td>
      <td>IS10</td>
    </tr>
    <tr>
      <td>Consulta de histórico de movimentações</td>
      <td></td>
      <td>RF23</td>
      <td></td>
      <td>OB06</td>
    </tr>
    <tr>
      <td>Informação sobre saques e bloqueios</td>
      <td></td>
      <td>RF11</td>
      <td></td>
      <td>IS08</td>
    </tr>
    <tr>
      <td>Informação sobre saques e bloqueios</td>
      <td></td>
      <td>RF01</td>
      <td></td>
      <td>EN03</td>
    </tr>
    <tr>
      <td>Resumo e detalhes sobre saques</td>
      <td></td>
      <td>RF21</td>
      <td></td>
      <td>OB02</td>
    </tr>
    <tr>
      <td>Resumo e detalhes sobre saques</td>
      <td></td>
      <td>RF22</td>
      <td></td>
      <td>OB05</td>
    </tr>
    <tr>
      <td rowspan="9">Saques e Solicitações</td>
      <td>Solicitação de saque e acompanhamento</td>
      <td></td>
      <td>RF04</td>
      <td></td>
      <td>EN06, ST013, ST014</td>
    </tr>
    <tr>
      <td>Solicitação de saque e acompanhamento</td>
      <td></td>
      <td>RF08</td>
      <td></td>
      <td>IS05, EN02</td>
    </tr>
    <tr>
      <td>Solicitação de saque e acompanhamento</td>
      <td></td>
      <td>RF28</td>
      <td></td>
      <td>EN01, IS03, ST06, OB03</td>
    </tr>
    <tr>
      <td>Solicitação de saque e acompanhamento</td>
      <td></td>
      <td>RF07</td>
      <td></td>
      <td>IS04, OB04</td>
    </tr>
    <tr>
      <td>Cancelamento e filtro de saques</td>
      <td></td>
      <td>RF09</td>
      <td></td>
      <td>IS06</td>
    </tr>
    <tr>
      <td>Cancelamento e filtro de saques</td>
      <td></td>
      <td>RF10</td>
      <td></td>
      <td>IS07</td>
    </tr>
    <tr>
      <td>Guias e ajuda para saque</td>
      <td></td>
      <td>RF17</td>
      <td></td>
      <td>IS15</td>
    </tr>
    <tr>
      <td>Guias e ajuda para saque</td>
      <td></td>
      <td>RF18</td>
      <td></td>
      <td>IS16</td>
    </tr>
    <tr>
      <td>Guias e ajuda para saque</td>
      <td></td>
      <td>RF29</td>
      <td></td>
      <td>ST07</td>
    </tr>
    <tr>
      <td rowspan="3">Contas Bancárias</td>
      <td>Cadastro e gerenciamento de contas bancárias</td>
      <td></td>
      <td>RF14</td>
      <td></td>
      <td>IS11, ST05, OB08</td>
    </tr>
    <tr>
      <td>Cadastro e gerenciamento de contas bancárias</td>
      <td></td>
      <td>RF31</td>
      <td></td>
      <td>ST010</td>
    </tr>
    <tr>
      <td>Cadastro e gerenciamento de contas bancárias</td>
      <td></td>
      <td>RF35</td>
      <td></td>
      <td>IS12</td>
    </tr>
    <tr>
      <td rowspan="3">Comunicação e Suporte</td>
      <td>Suporte via chat e canais de atendimento</td>
      <td></td>
      <td>RF02</td>
      <td></td>
      <td>EN04</td>
    </tr>
    <tr>
      <td>Suporte via chat e canais de atendimento</td>
      <td></td>
      <td>RF15</td>
      <td></td>
      <td>IS13</td>
    </tr>
    <tr>
      <td>Notificações e avisos</td>
      <td></td>
      <td>RF27</td>
      <td></td>
      <td>ST03, ST09, ST015</td>
    </tr>
    <tr>
      <td rowspan="6">Usabilidade e Acessibilidade</td>
      <td>Personalização e acessibilidade da interface</td>
      <td></td>
      <td>RF30</td>
      <td></td>
      <td>ST08</td>
    </tr>
    <tr>
      <td>Busca e navegação</td>
      <td></td>
      <td>RF16</td>
      <td></td>
      <td>IS14</td>
    </tr>
    <tr>
      <td>Login e segurança</td>
      <td></td>
      <td>RF20</td>
      <td></td>
      <td>OB01</td>
    </tr>
    <tr>
      <td>Login e segurança</td>
      <td></td>
      <td>RF32</td>
      <td></td>
      <td>ST011</td>
    </tr>
    <tr>
      <td>Outros itens diversos</td>
      <td></td>
      <td>RF25</td>
      <td></td>
      <td>OB09</td>
    </tr>
    <tr>
      <td>Guias e ajuda geral</td>
      <td></td>
      <td>RF34</td>
      <td></td>
      <td>ST016</td>
    </tr>
  </tbody>
</table>

<font size="2"><p style="text-align: center">Fonte: [Danielle Soares](https://github.com/danielle-soaress)</p></font>


---

## Validação



---

##  Bibliografia

> <a id="REF1" href="#anchor_1">1.</a>  PRESSMAN, Roger S.; MAXIM, Bruce R.. Engenharia de software: uma abordagem profissional. 8 Porto Alegre: AMGH, 2016, 940 p.

> <a id="REF1" href="#anchor_2">2.</a>  SERRANO, Milene; SERRANO, Maurício. Requisitos – Aula 15. UnB, 2025. Disponível em: https://aprender3.unb.br/pluginfile.php/3096144/mod_resource/content/1/Requisitos%20-%20Aula%2015a.pdf. Acesso em: 30 de maio 2025.


---

##  Histórico de Versão

| Versão | Data       | Descrição                                 | Autor(es)                                     | Revisor(es) |
|--------|------------|--------------------------------------------|-----------------------------------------------|-------------|
| 1.0    | 30/05/2025 | Introdução, Metodologia e Backlog | [Danielle Soares](https://github.com/danielle-soaress) | - |