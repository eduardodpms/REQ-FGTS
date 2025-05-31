# NFR Framework

## Introdução

O desenvolvimento de sistemas de software requer uma abordagem sistemática para identificar e tratar requisitos que não se restringem apenas à funcionalidade do sistema, mas também a atributos de qualidade e restrições operacionais. Tais requisitos, denominados Requisitos Não-Funcionais (RNFs), desempenham papel essencial na definição da qualidade global do produto. Contudo, a elicitação e especificação adequada desses requisitos são frequentemente negligenciadas ou tratadas de forma imprecisa.

Diante disso, o NFR Framework, proposto por Chung et al. (2000), surge como uma abordagem estruturada e incremental voltada para a representação, análise e documentação de RNFs. Ele permite a modelagem de interdependências entre softgoals (objetivos qualitativos), facilitando a rastreabilidade, o refinamento e a justificativa das decisões de projeto, sendo adotado como base no projeto para a construção do catálogo NFR4ES.

## Metodologia

Esta seção descreve a metodologia adotada para a modelagem dos Requisitos Não-Funcionais (RNFs) do aplicativo FGTS, utilizando como base o NFR Framework, conforme estruturado por Chung et al. (2000) e aplicado na dissertação de Silva (2019). O objetivo é garantir uma abordagem sistemática para identificar, estruturar e justificar decisões relacionadas à qualidade do sistema, com foco nas necessidades reais dos usuários, representados por personas.

A metodologia foi dividida em três fases principais: **Levantamento Inicial**, **Modelagem com o NFR Framework**, e **Validação**.

**1. Levantamento Inicial**

Inicialmente, foi realizado um levantamento dos RNFs desejados pelos usuários do aplicativo FGTS, com base em:

- Análise das personas construídas (Lucas, Patrícia, Antônio e Beatriz).

- Extração dos requisitos implícitos e explícitos contidos nas histórias de usuário já formuladas.

- Consulta a boas práticas de design de aplicações financeiras governamentais, como usabilidade, segurança e acessibilidade.

Essa fase teve como objetivo reunir um conjunto preliminar de softgoals a serem modelados, refletindo preocupações como: "navegação simples", "login seguro", "resposta rápida", "acesso off-line", entre outros.

**2. Modelagem com o NFR Framework**

A segunda fase consistiu na aplicação do NFR Framework como mecanismo de modelagem e representação dos RNFs. Essa fase seguiu os seguintes passos:

- **Identificação de Softgoals**: cada RNF relevante foi representado como um softgoal, ou seja, um objetivo qualitativo que o sistema deve alcançar, como Segurança, Desempenho, Usabilidade e Acessibilidade.

- **Refinamento dos Softgoals**: os softgoals foram decompostos em subsoftgoals mais específicos, por exemplo:

    - Usabilidade → Interface clara, Feedback imediato, Poucas etapas por tarefa.

- **Operacionalização**: para cada softgoal, foram identificadas ações concretas do sistema que contribuem positivamente ou negativamente para sua realização, como “autenticação por biometria” ou “layout adaptado para idosos”.

- **Construção do SIG (Softgoal Interdependency Graph)**: foi elaborado um grafo com as interdependências entre os softgoals e suas contribuições, permitindo identificar conflitos, sinergias e decisões de projeto justificáveis.

**3. Validação**

Por fim, a validação da modelagem seguiu duas frentes:

- Rastreabilidade com as histórias de usuário: verificou-se se os softgoals contemplam os desejos e expectativas expressas por cada persona.

- Análise de cobertura: analisou-se se os principais atributos de qualidade exigidos para um app público financeiro (como disponibilidade, desempenho e segurança) foram devidamente modelados.

Essa validação permite garantir que os RNFs não sejam apenas documentados, mas também rastreáveis, justificáveis e compatíveis com os requisitos funcionais do aplicativo.

---

### Tabela 1: Participantes

<center>

| Nome             | Data | Hora |
|------------------|------|------|
| Danielle Soares  | -    | -    |
| Eduardo de Pina  | -    | -    |
| Enzo Emir        | -    | -    |
| Leticia Arisa    | -    | -    |
| Marcelo Makoto   | -    | -    |
| Maria Eduarda    | -    | -    |
| Victor Pontual   | -    | -    |

</center>

<font size="2"><p style="text-align: center">Fonte: [Marcelo Makoto](https://github.com/MM4k)</p></font>

---

## Levantamento Inicial



---

## Cartões de Especificação

<font size="3"><p style="text-align: center">Tabela 2: Participantes</p></font>

<center>
<table border="1" cellpadding="6" cellspacing="0">
  <tr><th colspan="2">Requisito Não Funcional – RNF02</th></tr>
  <tr><td><strong>Classificação</strong></td><td>Usabilidade</td></tr>
  <tr><td><strong>Descrição</strong></td><td>O processo de login deve ser simplificado.</td></tr>
  <tr><td><strong>Justificativa</strong></td><td>Um login simples melhora a experiência do usuário, reduz a frustração e torna o acesso ao aplicativo mais eficiente.</td></tr>
  <tr><td><strong>Origem do Requisito</strong></td><td><a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Entrevista/#EN_RNF">EN08</a></td></tr>
  <tr><td><strong>Critério de Aceitação</strong></td><td>O usuário deve conseguir realizar o login com no máximo duas etapas, sem a necessidade de preencher dados excessivos.</td></tr>
  <tr><td><strong>Dependências</strong></td><td>Sistema de autenticação</td></tr>
  <tr><td><strong>Prioridade</strong></td><td>3,25</td></tr>
  <tr><td><strong>Conflitos</strong></td><td>Nenhum</td></tr>
  <tr><td><strong>História</strong></td><td>31/05/2025</td></tr>
</table>
</center>

<font size="2"><p style="text-align: center">Fonte: [Danielle Soares](https://github.com/danielle-soaress) </p></font>

<font size="3"><p style="text-align: center">Tabela 3: Participantes</p></font>

<center>
<table border="1" cellpadding="6" cellspacing="0">
  <tr><th colspan="2">Requisito Não Funcional – RNF08</th></tr>
  <tr><td><strong>Classificação</strong></td><td>Portabilidade</td></tr>
  <tr><td><strong>Descrição</strong></td><td>O aplicativo deve fornecer as mesmas funcionalidades para diferentes plataformas e versões.</td></tr>
  <tr><td><strong>Justificativa</strong></td><td>Garantir a consistência da experiência do usuário, independentemente do dispositivo ou sistema operacional utilizado.</td></tr>
  <tr><td><strong>Origem do Requisito</strong></td><td><a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#IS_RNF"> IS18</a></td></tr>
  <tr><td><strong>Critério de Aceitação</strong></td><td>As funcionalidades disponíveis devem ser idênticas em todas as versões do aplicativo para Android, iOS e Web.</td></tr>
  <tr><td><strong>Dependências</strong></td><td>Frameworks multiplataforma, compatibilidade entre sistemas</td></tr>
  <tr><td><strong>Prioridade</strong></td><td>4,40</td></tr>
  <tr><td><strong>Conflitos</strong></td><td>Pode haver limitações específicas em versões mais antigas de sistemas operacionais.</td></tr>
  <tr><td><strong>História</strong></td><td>31/05/2025</td></tr>
</table>
</center>

<font size="2"><p style="text-align: center">Fonte: [Danielle Soares](https://github.com/danielle-soaress) </p></font>

---

## Modelagem

## Validação



---

##  Bibliografia

> 1.</a> SILVA, Reinaldo Antônio da. NFR4ES: um catálogo de requisitos não-funcionais para sistemas embarcados. 2019. 154 f. Dissertação (Mestrado em Ciência da Computação) – Universidade Federal de Pernambuco, Recife, 2019.

> 2.</a> CHUNG, Lawrence; NIXON, Brian A.; YU, Eric; MYLLOPULOS, John. Non-functional requirements in software engineering. Springer Science & Business Media, 2000.

---

##  Histórico de Versão

| Versão | Data       | Descrição                                 | Autor(es)                                     | Revisor(es) |
|--------|------------|--------------------------------------------|-----------------------------------------------|-------------|
| 1.0    | 28/05/2025 | Criação da página | [Marcelo Makoto](https://github.com/MM4k) | - |
| 1.1    | 28/05/2025 | Cartões de Especificação RN02 e RN07 | [Danielle Soares](https://github.com/danielle-soaress) | - |