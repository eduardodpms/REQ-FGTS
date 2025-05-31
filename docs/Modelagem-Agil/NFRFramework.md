# NFR Framework

## Introdução

No contexto do desenvolvimento de sistemas de software, os [Requisitos Não-Funcionais (RNFs)](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#requisitos-nao-funcionais) desempenham um papel essencial ao definir qualidades e restrições que afetam diretamente a experiência do usuário, a segurança, o desempenho e a conformidade legal dos sistemas. Dentre esses requisitos, destaca-se a necessidade de que os dados sejam tratados em conformidade com legislações específicas de proteção de dados, como etapa indispensável antes da operação de qualquer sistema.

Com o objetivo de representar e analisar de maneira estruturada esses requisitos, este trabalho adota o **NFR Framework**, uma abordagem proposta por **Chung et al. (2000)**. Esse framework permite a modelagem dos RNFs por meio de *softgoals*, objetivos que não possuem critérios de satisfação precisos, mas que são fundamentais para a qualidade do produto. A representação gráfica dos softgoals é feita através de um **grafo SIG (Softgoal Interdependency Graph)**, que explicita suas interdependências, influências e possíveis conflitos.

O presente estudo concentra-se no tratamento de Requisitos Não-Funcionais de Produto do aplicativo **FGTS**, utilizando a notação do **NFR Framework** para expressar os RNFs contidos no catálogo **NFR4ES**. A aplicação desse framework visa apoiar a tomada de decisões no processo de desenvolvimento e evolução do app FGTS, tornando-o mais robusto, seguro e alinhado tanto às necessidades dos usuários quanto ao contexto legal vigente, especialmente no que se refere à proteção de dados e à confiabilidade do sistema.

## SIG - Softgoal Interdependency Graph

O NFR Framework funciona por meio da construção e análise de um grafo chamado **Softgoal Interdependency Graph (SIG)**, que representa graficamente os Requisitos Não-Funcionais (softgoals), suas interdependências, alternativas e justificativas. Esse grafo registra as decisões de desenvolvimento e permite avaliar se os requisitos de alto nível foram atendidos.

### Tipos de SIG

O SIG é dividido em três tipos principais:

- **Softgoals NFR**: representam alternativas técnicas e soluções práticas (como processos, restrições ou estruturas) para atender aos softgoals NFR.

- **Softgoals de Operacionalização**: representa os softgoals e suas interdependências, permitindo identificar conflitos, sinergias e decisões de projeto justificáveis.

- **Softgoals de Afirmação**: trazem justificativas baseadas em características do domínio (como prioridades e carga de trabalho), apoiando decisões, revisões e a rastreabilidade do sistema.

<font size="3"><p style="text-align: center">Figura 1: Tipos de Softgoal</p></font>

<div align="center">
  <img src="./../../assets/NFR/imagem1.png" alt="FIGURA 1">
</div>

<font size="2"><p style="text-align: center">Fonte: [SILVA, 2019](https://aprender3.unb.br/pluginfile.php/3096155/mod_resource/content/2/DISSERTA%C3%87%C3%83O%20Reinaldo%20Ant%C3%B4nio%20da%20Silva.pdf) </p></font>

### Tipos e Interdependências de Softgoals no NFR Framework

- O NFR Framework utiliza três tipos de *softgoals*, representados por diferentes estilos de nuvens:
  - **Softgoals NFR**: nuvens claras
  - **Softgoals de Operacionalização**: nuvens com linhas grossas
  - **Softgoals de Afirmação**: nuvens com linhas tracejadas

- Cada *softgoal NFR* possui um **tipo** (ex: Confiabilidade) e um **tópico** (ex: Infusor), que indicam a parte específica do sistema a que se refere.

- As **interdependências** entre os *softgoals* são classificadas em:
  - **Refinamentos (top-down)**, onde um *softgoal* pai gera filhos mais específicos, podendo ser:
    - **Decomposição de Softgoal NFR**: divide um requisito não-funcional em outros mais específicos
    - **Decomposição de Operacionalização**: refina soluções implementáveis
    - **Decomposição de Afirmação**: detalha justificativas de projeto
    - **Priorização**: refina um *softgoal* destacando sua prioridade

- Essa estrutura ajuda a representar, refinar e justificar requisitos não-funcionais no desenvolvimento de sistemas.

<font size="3"><p style="text-align: center">Figura 2: Tipos e Interdependências de Softgoals no NFR Framework</p></font>

<div align="center">
  <img src="./../../assets/NFR/imagem2.png" alt="FIGURA 2">
</div>

<font size="2"><p style="text-align: center">Fonte: [SILVA, 2019](https://aprender3.unb.br/pluginfile.php/3096155/mod_resource/content/2/DISSERTA%C3%87%C3%83O%20Reinaldo%20Ant%C3%B4nio%20da%20Silva.pdf) </p></font>

### Contribuições e Tipos no NFR Framework

- Durante o refinamento dos *softgoals*, um softgoal descendente pode contribuir positiva ou negativamente, de forma total ou parcial, para a satisfação do *softgoal* ascendente.
- "Satisfação de softgoal" indica que o requisito não-funcional deve ser atendido dentro de limites aceitáveis, não necessariamente de forma absoluta.

- **AND**: todos os descendentes precisam ser satisfeitos para o ascendente ser satisfeito.
- **OR**: algum descendente satisfeito basta para o ascendente ser satisfeito.
- **MAKE (++)**: contribuição altamente positiva; se o descendente for satisfeito, o ascendente será satisfeito.
- **BREAK (--)**: contribuição altamente negativa; se o descendente for satisfeito, o ascendente será negado.
- **HELP (+)**: contribuição parcialmente positiva; satisfação parcial do descendente leva à satisfação parcial do ascendente.
- **HURT (-)**: contribuição parcialmente negativa; satisfação do descendente prejudica parcialmente o ascendente.
- **UNKNOWN (?)**: contribuição desconhecida, pode ser positiva ou negativa.
- **EQUALS**: o descendente só é satisfeito se o ascendente for satisfeito; se o ascendente for negado, o descendente também é negado.
- **SOME**: sinal conhecido (positivo ou negativo), mas grau de contribuição incerto; usado em casos de incerteza entre HELP/MAKE ou HURT/BREAK.

### Procedimento de Avaliação no NFR Framework

- O procedimento de avaliação determina o grau em que os requisitos não funcionais (*softgoals*) são satisfeitos por um conjunto de decisões.
- Cada *softgoal* ou interdependência do *Softgoal Interdependency Graph* (SIG) recebe um rótulo para indicar seu status.
- Tipos de rótulos usados:

    - ✓ **(satisfeito)**: O requisito não funcional é plenamente satisfeito.
    - 𝒲+ **(fracamente satisfeito)**: Satisfação parcial; impacto positivo, mas menos forte que ✓.
    - X **(negado)**: O requisito não é satisfeito e pode até contradizer os objetivos do sistema.
    - 𝒲- **(fracamente negado)**: Negação parcial; impacto negativo, mas mais brando que X.
    - 🗲 **(conflitante)**: Há conflitos entre requisitos; coexistem aspectos positivos e negativos.
    - u **(indeterminado)**: Não há dados suficientes para determinar o impacto entre os requisitos.

- A avaliação começa pelos *softgoals* de nível mais baixo na hierarquia, relacionados a decisões específicas do projeto.
- O procedimento propaga os rótulos hierarquicamente, avaliando o impacto das decisões nos *softgoals* de níveis superiores, até alcançar o topo do SIG.


<font size="3"><p style="text-align: center">Figura 3: Procedimento de Avaliação no NFR Framework</p></font>


<div align="center">
  <img src="./../../assets/NFR/procedimento.png" alt="FIGURA 3">
</div>

<font size="2"><p style="text-align: center">Fonte: [SILVA, 2019](https://aprender3.unb.br/pluginfile.php/3096155/mod_resource/content/2/DISSERTA%C3%87%C3%83O%20Reinaldo%20Ant%C3%B4nio%20da%20Silva.pdf) </p></font>


## Metodologia

Para aplicar o **NFR Framework** ao desenvolvimento do aplicativo, adotamos uma abordagem em etapas estruturadas, com o objetivo de identificar, modelar, analisar e tomar decisões relacionadas aos requisitos não funcionais (softgoals) do sistema. A metodologia compreende as seguintes fases:

### 1. Identificação dos Requisitos Não Funcionais (Softgoals)

Nesta etapa, foram identificados os principais requisitos não funcionais relevantes ao contexto do aplicativo, como:

- Usabilidade  
- Desempenho  
- Segurança  
- Acessibilidade  
- Confiabilidade  

Essa identificação foi baseada em entrevistas com stakeholders, análise de mercado e levantamento de requisitos funcionais relacionados. Os requisitos não funcionais são representados como **softgoals**, que expressam intenções qualitativas sem critérios rígidos de satisfação.

### 2. Modelagem com o NFR Framework

A modelagem foi realizada utilizando a notação proposta por [*Chung et al. (2000)*](https://aprender3.unb.br/pluginfile.php/3096155/mod_resource/content/2/DISSERTA%C3%87%C3%83O%20Reinaldo%20Ant%C3%B4nio%20da%20Silva.pdf), representando os softgoals em uma estrutura hierárquica com relacionamentos de contribuição entre eles. Foram utilizados os seguintes tipos de contribuição:

- **MAKE (++)**
- **HELP (+)**
- **HURT (-)**
- **BREAK (--)**
- **OR**
- **AND**
- **EQUALS**
- **UNKNOWN (?)**
- **SOME**

Também foram especificadas as **operacionalizações**, ou seja, decisões de projeto que implementam cada softgoal.

#### Uso do Cartão de Especificação

Durante essa fase de modelagem, utilizou-se o **Cartão de Especificação** como instrumento de apoio à documentação e análise. Cada cartão foi preenchido com os seguintes elementos:

- Nome do softgoal  
- Descrição do requisito não funcional  
- Alternativas de operacionalização  
- Contribuições com outros softgoals  
- Justificativa das decisões  
- Responsável e data da análise  

O cartão facilitou a **rastreabilidade, clareza e consistência** das informações, além de permitir uma análise comparativa entre alternativas e apoiar a comunicação com os stakeholders durante a modelagem dos requisitos.

### 3. Avaliação dos Softgoals

Após modelar os softgoals e suas contribuições, foi realizado o **procedimento de avaliação**, no qual cada softgoal recebeu um rótulo indicando o grau de satisfação:

- `✓` **Satisfeito**: Requisito não funcional plenamente atendido.  
- `𝒲+` **Fracamente satisfeito**: Satisfação parcial.  
- `X` **Negado**: Requisito contradiz outro.  
- `𝒲-` **Fracamente negado**: Impacto negativo moderado.  
- `🗲` **Conflitante**: Conflito entre requisitos.  
- `u` **Indeterminado**: Impacto incerto ou desconhecido.

A avaliação começou pelos softgoals de nível mais baixo (operacionalizações), subindo até os níveis superiores da hierarquia para analisar o impacto global das decisões.

### 4. Tomada de Decisão

Com base nas análises e rótulos atribuídos, foram tomadas decisões de projeto priorizando alternativas que maximizassem a satisfação dos softgoals mais relevantes. Em casos de conflito entre requisitos (ex: desempenho vs. segurança), foram feitas ponderações com stakeholders para encontrar o melhor compromisso possível.


### 5. Validação

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


<font size="3"><p style="text-align: center">Tabela 4: Participantes</p></font>

<center>
<table border="1" cellpadding="6" cellspacing="0">
  <tr><th colspan="2">Requisito Não Funcional – RNF12</th></tr>
  <tr><td><strong>Classificação</strong></td><td>Usabilidade</td></tr>
  <tr><td><strong>Descrição</strong></td><td>O aplicativo deve proporcionar agilidade ao acessar as funcionalidades.</td></tr>
  <tr><td><strong>Justificativa</strong></td><td>Um acesso rápido melhora a experiência do usuário, reduz o tempo de espera e aumenta a eficiência no uso do aplicativo.</td></tr>
  <tr><td><strong>Origem do Requisito</strong></td><td><a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#requisitos-nao-funcionais">IS24</a></td></tr>
  <tr><td><strong>Critério de Aceitação</strong></td><td>O usuário deve conseguir acessar qualquer funcionalidade em menos de 3 segundos.</td></tr>
  <tr><td><strong>Dependências</strong></td><td>Infraestrutura do sistema, otimização do código</td></tr>
  <tr><td><strong>Prioridade</strong></td><td>4,00</td></tr>
  <tr><td><strong>Conflitos</strong></td><td>Nenhum</td></tr>
  <tr><td><strong>História</strong></td><td>31/05/2025</td></tr>
</table>
</center>

<font size="2"><p style="text-align: center">Fonte: [Maria Eduarda](https://github.com/dudaa28) </p></font>

<font size="3"><p style="text-align: center">Tabela 5: Participantes</p></font>

<center>
<table border="1" cellpadding="6" cellspacing="0">
  <tr><th colspan="2">Requisito Não Funcional – RNF21</th></tr>
  <tr><td><strong>Classificação</strong></td><td>Usabilidade</td></tr>
  <tr><td><strong>Descrição</strong></td><td>Os menus devem ser autoexplicativos, com estrutura hierárquica lógica e nomenclatura padronizada.</td></tr>
  <tr><td><strong>Justificativa</strong></td><td>Menus intuitivos facilitam a navegação do usuário, reduzem o tempo de aprendizado e aumentam a eficiência no uso do aplicativo.</td></tr>
  <tr><td><strong>Origem do Requisito</strong></td><td><a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#IS_RNF">IS19</a>
  <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Observacao/#OB_RNF">OB11</a></td></tr>
  <tr><td><strong>Critério de Aceitação</strong></td><td>O usuário deve ser capaz de encontrar funcionalidades com facilidade, sem precisar acessar mais de três níveis de menu e com nomes consistentes e compreensíveis.</td></tr>
  <tr><td><strong>Dependências</strong></td><td>Design de Interface, Padrões de Navegação</td></tr>
  <tr><td><strong>Prioridade</strong></td><td>3,75S</td></tr>
  <tr><td><strong>Conflitos</strong></td><td>Nenhum</td></tr>
  <tr><td><strong>História</strong></td><td>31/05/2025</td></tr>
</table>
</center>

<font size="2"><p style="text-align: center">Fonte: [Maria Eduarda](https://github.com/dudaa28) </p></font>

---

## Modelagem

## Validação



---

##  Referências Bibliográficas

> 1.</a> SILVA, Reinaldo Antônio da. NFR4ES: um catálogo de requisitos não-funcionais para sistemas embarcados. 2019. 154 f. Dissertação (Mestrado em Ciência da Computação) – Universidade Federal de Pernambuco, Recife, 2019.

> 2.</a> CHUNG, Lawrence; NIXON, Brian A.; YU, Eric; MYLLOPULOS, John. Non-functional requirements in software engineering. Springer Science & Business Media, 2000.

<font size="3"><p style="text-align: center">Figura 4: Foto referência</p></font>

<div align="center">
  <img src="./../../assets/referencias/NFR.png" alt="FIGURA 4">
</div>

<font size="2"><p style="text-align: center">Fonte: [SILVA, 2019](https://aprender3.unb.br/pluginfile.php/3096155/mod_resource/content/2/DISSERTA%C3%87%C3%83O%20Reinaldo%20Ant%C3%B4nio%20da%20Silva.pdf) </p></font>

---

##  Histórico de Versão

| Versão | Data       | Descrição                                 | Autor(es)                                     | Revisor(es) |
|--------|------------|--------------------------------------------|-----------------------------------------------|-------------|
| 1.0    | 28/05/2025 | Criação da página | [Marcelo Makoto](https://github.com/MM4k) | - |
| 1.1    | 31/05/2025 | Cartões de Especificação RNF02 e RNF07 | [Danielle Soares](https://github.com/danielle-soaress) | [Maria Eduarda](https://github.com/dudaa28) |
| 1.2    | 31/05/2025 | Atualização da Página | [Maria Eduarda](https://github.com/dudaa28) | - |
| 1.3    | 31/05/2025 | Cartões de Especificação RNF12 e RNF21 | [Maria Eduarda](https://github.com/dudaa28) | - |