##  Introdução

A rastreabilidade é uma técnica essencial na engenharia de requisitos, fundamental para estabelecer e gerenciar o relacionamento entre requisitos, a arquitetura e a implementação de um sistema. Conforme discutido por Ayão e Leite (2005), diferentes tipos de rastreabilidade são empregados para garantir a completude e a consistência do projeto  <a href="REF1">1</a>. Entre eles, destaca-se a rastreabilidade ***forward-from***, que é caracterizada por ligar os requisitos aos artefatos de desenho e implementação do sistema, assegurando que as especificações iniciais sejam devidamente contempladas nas etapas subsequentes de desenvolvimento. Add commentMore actions

Neste documento, serão apresentados os elos ***forward-from*** dos requisitos funcionais e não funcionais do sistema FGTS. Esta abordagem da pós-rastreabilidade demonstrará como os requisitos evoluem e se relacionam com os artefatos de desenho e implementação.


##  Metodologia

Para a definição de nossa metodologia de rastreabilidade, adotamos como base a proposta de Toranzo, Castro e Mello (2002) <a href="REF2">2</a>. Esta abordagem compreende diversas estratégias fundamentais para o rastreamento de requisitos, começando pela classificação das informações em quatro categorias principais:

- **Ambiental**: Abrange informações originadas do contexto externo onde a organização está inserida, e que podem influenciar o sistema em desenvolvimento. Exemplos incluem leis, objetivos estratégicos e padrões.

- **Organizacional**: Reúne informações diretamente relacionadas à organização, como sua missão, objetivos internos, regras e processos.

- **Gerencial**: Agrega informações que permitem associar tarefas a requisitos, e que são úteis para auxiliar a gerência do projeto. Inclui objetivos gerenciais, tarefas específicas e restrições.

- **Desenvolvimento**: Engloba informações relacionadas aos diversos artefatos gerados no processo de desenvolvimento do sistema, como documentos de requisitos, diagramas e código de programa.

Além da classificação das informações, o meta-modelo de rastreamento de requisitos de Toranzo, Castro e Mello (2002) também identifica diferentes tipos de elos (ou links) que suportam a rastreabilidade. Esses elos representam as relações e as dependências entre os diversos elementos do sistema <a href="REF2">2</a>. Os principais tipos de elos são:

- **Satisfação**: Indica que uma classe de origem tem dependência de satisfação com uma classe de destino.

- **Recurso**: Sugere que uma classe de origem depende de um recurso fornecido por uma classe de destino.

- **Responsabilidade**: Registra a participação, a responsabilidade e a ação de indivíduos sobre artefatos.

- **Representação**: Captura a representação ou modelagem dos requisitos em outras linguagens ou formas.

- **Alocado**: Denota que uma classe de origem está relacionada a uma classe de destino que, por sua vez, representa um subsistema.

- **Agregação**: Indica a composição de elementos, mostrando como partes se juntam para formar um todo.

No presente documento, estão os resultados da aplicação deste modelo de rastreabilidade a todos os [requisitos elicitados](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/), garantindo uma cobertura completa e uma visão abrangente das suas origens, classificações e interconexões ao longo do ciclo de desenvolvimento.

<font size="3"><p style="text-align: center">Tabela 1: Modelo da tabela de rastreabilidade</p></font>

<div align="center">

<table>
  <thead>
    <tr>
      <th>Item da Tabela de Rastreabilidade</th>
      <th>Descrição / Conteúdo</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Apresenta a especificação textual do requisito em questão.</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Classifica o requisito de acordo com as quatro categorias (Ambiental, Organizacional, Gerencial, Desenvolvimento)</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td>Lista os artefatos de origem ou outros elementos que contribuíram para a elicitação ou refinamento do requisito.</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>Detalhamento dos vínculos que o requisito possui a artefatos ou processos subsequentes no desenvolvimento.</td>
    </tr>
    <tr>
      <td><strong>Print</strong></td>
      <td>Coluna reservada para anexos visuais ou evidências, se aplicável.</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: [Danielle Soares](https://github.com/danielle-soaress)</p></font>

##  Cronograma de Participantes

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
      <td> Danielle Soares </td>
      <td> 07/06/2025 </td>
      <td> 19:52 </td>
    </tr>
    <tr>
      <td> Eduardo de Pina </td>
      <td> - </td>
      <td> - </td>
    </tr>
    <tr>
      <td> Enzo Emir </td>
      <td> 08/06/2025 </td>
      <td> 16:42 </td>
    </tr>
    <tr>
      <td> Leticia Arisa </td>
      <td> 07/06/2025 </td>
      <td> 15:54 </td>
    </tr>
    <tr>
      <td> Marcelo Makoto </td>
      <td> 07/06/2025 </td>
      <td> 21:03 </td>
    </tr>
    <tr>
      <td> Maria Eduarda </td>
      <td> 08/06/2025 </td>
      <td> 13:16 </td>
    </tr>
    <tr>
      <td> Victor Pontual </td>
      <td>08/06/2025 </td>
      <td> 15:16 </td>
    </tr>
  </tbody>
</table>

</div>


<font size="2"><p style="text-align: center">Fonte: [Enzo Emir](https://github.com/EnzoEmir) </p></font>

## Sumário

<ul>
  <li>RF03 - Rastreabilidade <a href="#E22">E22</a></li>
  <li>RF02 - Rastreabilidade <a href="#E29">E29</a></li>
  <li>RF04 - Rastreabilidade <a href="#E23">E23</a></li>
  <li>RF05 - Rastreabilidade <a href="#E24">E24</a></li>
  <li>RF10 - Rastreabilidade <a href="#E39">E39</a></li>
  <li>RF11 - Rastreabilidade <a href="#E20">E20</a></li>
  <li>RF12 - Rastreabilidade <a href="#E01">E01</a></li>
  <li>RF13 - Rastreabilidade <a href="#E02">E02</a></li>
  <li>RF14 - Rastreabilidade <a href="#E13">E13</a></li>
  <li>RF15 - Rastreabilidade <a href="#E11">E11</a></li>
  <li>RF16 - Rastreabilidade <a href="#E12">E12</a></li>
  <li>RF21 - Rastreabilidade <a href="#E03">E03</a></li>
  <li>RF22 - Rastreabilidade <a href="#E04">E04</a></li>
  <li>RF23 - Rastreabilidade <a href="#E05">E05</a></li>
  <li>RF25 - Rastreabilidade <a href="#E14">E14</a></li>
  <li>RF26 - Rastreabilidade <a href="#E15">E15</a></li>
  <li>RF27 - Rastreabilidade <a href="#E31">E31</a></li>
  <li>RF28 - Rastreabilidade <a href="#E32">E32</a></li>
  <li>RF30 - Rastreabilidade <a href="#E30">E30</a></li>
  <li>RF31 - Rastreabilidade <a href="#E33">E33</a></li>
  <li>RF32 - Rastreabilidade <a href="#E40">E40</a></li>
  <li>RF33 - Rastreabilidade <a href="#E41">E41</a></li>
  <li>RF34 - Rastreabilidade <a href="#E42">E42</a></li>
  <li>RF35 - Rastreabilidade <a href="#E21">E21</a></li>
  <li>RF36 - Rastreabilidade <a href="#E16">E16</a></li>
  <li>RF39 - Rastreabilidade <a href="#E25">E25</a></li>
  <li>RF40 - Rastreabilidade <a href="#E43">E43</a></li>
  <li>RF41 - Rastreabilidade <a href="#E06">E06</a></li>
  <li>RF42 - Rastreabilidade <a href="#E34">E34</a></li>
  <li>RF08 - Rastreabilidade <a href="#E38">E38</a></li>
  <li>RF01 - Rastreabilidade <a href="#E49">E49</a></li>
  <li>RF17 - Rastreabilidade <a href="#E50">E50</a></li>
  <li>RF19 - Rastreabilidade <a href="#E51">E51</a></li>
  <li>RF20 - Rastreabilidade <a href="#E52">E52</a></li>
  <li>RNF01 - Rastreabilidade <a href="#E26">E26</a></li>
  <li>RNF02 - Rastreabilidade <a href="#E27">E27</a></li>
  <li>RNF04 - Rastreabilidade <a href="#E53">E53</a></li>
  <li>RNF05 - Rastreabilidade <a href="#E07">E07</a></li>
  <li>RNF06 - Rastreabilidade <a href="#E17">E17</a></li>
  <li>RNF07 - Rastreabilidade <a href="#E28">E28</a></li>
  <li>RNF09 - Rastreabilidade <a href="#E54">E54</a></li>
  <li>RNF10 - Rastreabilidade <a href="#E44">E44</a></li>
  <li>RNF11 - Rastreabilidade <a href="#E18">E18</a></li>
  <li>RNF11 - Rastreabilidade <a href="#E36">E36</a></li>
  <li>RNF13 - Rastreabilidade <a href="#E45">E45</a></li>
  <li>RNF15 - Rastreabilidade <a href="#E55">E55</a></li>
  <li>RNF16 - Rastreabilidade <a href="#E08">E08</a></li>
  <li>RNF17 - Rastreabilidade <a href="#E09">E09</a></li>
  <li>RNF18 - Rastreabilidade <a href="#E19">E19</a></li>
  <li>RNF19 - Rastreabilidade <a href="#E37">E37</a></li>
  <li>RNF20 - Rastreabilidade <a href="#E46">E46</a></li>
  <li>RNF21 - Rastreabilidade <a href="#E35">E35</a></li>
  <li>RNF22 - Rastreabilidade <a href="#E10">E10</a></li>
</ul>


## Rastreabilidade Forward From

### <a name="E01"></a> E01 - Rastrebilidade Forward From do requisito RF12

<font size="3"><p style="text-align: center">Tabela 2: E01 - Cartão do Requisito Funcional 12</p></font>

<div align="center">

<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Descrição do requisito </td>
      <td> O aplicativo deve exibir informações detalhadas sobre o histórico de movimentações financeiras </td>
    </tr>
    <tr>
      <td> Categoria </td>
      <td> Desenvolvimento </td>
    </tr>
    <tr>
      <td> Elementos </td>
      <td> <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#RF>RF12</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#IS_RF>IS09</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-I/Cenarios/#C07>Cenário 7</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-I/Diagrama/#UC07>Caso de Uso 7</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-I/Lexicos/#L31>L31</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-I/Lexicos/#L32>L32</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-I/Lexicos/#L33>L33</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/Historias-De-Usuario/#H25>H25</a> </td>
    </tr>
    <tr>
      <td> Elos Forward-from </td>
      <td> 
      Satisfação - O requisito recebeu uma priorização de 0,063 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/First-Things-First>First Things First</a> <br>
      Satisfação - O requisito recebeu prioridade OUT na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/In-or-Out/#RF>In or Out</a><br>
      Satisfação - O requisito recebeu $4 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/100-Test/#Req>$100</a><br>
      Satisfação - O requisito recebeu prioridade média na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/Three-Level-Scale/#RF>Three-Level Scale</a><br>
      Agregação - O requisito é classificado no Épico <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/Product-Backlog/#tema3>E03</a>
      </td>
    </tr>
    <tr>
      <td> Print </td>
      <td> Não implementado </td>
    </tr>
  </tbody>
</table>

</div>

<font size="2"><p style="text-align: center">Fonte: [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa) </p></font>

### <a name="E02"></a> E02 - Rastrebilidade Forward From do requisito RF13

<font size="3"><p style="text-align: center">Tabela 3: E02 - Cartão do Requisito Funcional 13</p></font>

<div align="center">

<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Descrição do requisito </td>
      <td>O aplicativo deve permitir o filtro do extrato por data (mês e ano)</td>
    </tr>
    <tr>
      <td> Categoria </td>
      <td> Desenvolvimento </td>
    </tr>
    <tr>
      <td> Elementos </td>
      <td> <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#RF>RF13</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#IS_RF>IS10</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-I/Cenarios/#C08>Cenário 8</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-I/Diagrama/#UC08>Caso de Uso 8</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-I/Lexicos/#L34>L34</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/Historias-De-Usuario/#H26>H26</a></td>
    </tr>
    <tr>
      <td> Elos Forward-from </td>
      <td> 
      Satisfação - O requisito recebeu uma priorização de 0,246 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/First-Things-First>First Things First</a><br>
      Satisfação - O requisito recebeu prioridade OUT na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/In-or-Out/#RF>In or Out</a><br>
      Satisfação - O requisito recebeu $5 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/100-Test/#Req>$100</a><br>
      Satisfação - O requisito recebeu prioridade baixa na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/Three-Level-Scale/#RF>Three-Level Scale</a><br>
      Agregação - O requisito é classificado no Épico <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/Product-Backlog/#tema3>E03</a>
      </td>
    </tr>
    <tr>
      <td> Print </td>
      <td> Não implementado </td>
    </tr>
  </tbody>
</table>

</div>

<font size="2"><p style="text-align: center">Fonte: [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa) </p></font>

### <a name="E03"></a> E03 - Rastrebilidade Forward From do requisito RF21

<font size="3"><p style="text-align: center">Tabela 4: E03 - Cartão do Requisito Funcional 21</p></font>

<div align="center">

<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Descrição do requisito </td>
      <td>O aplicativo deve apresentar resumo de empregadores anteriores com botão para consultar contas vinculadas ao FGTS</td>
    </tr>
    <tr>
      <td> Categoria </td>
      <td> Desenvolvimento </td>
    </tr>
    <tr>
      <td> Elementos </td>
      <td> <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#RF>RF21</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Observacao/#OB_RF>OB02</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/Historias-De-Usuario/#H27>H27</a></td>
    </tr>
    <tr>
      <td> Elos Forward-from </td>
      <td> 
      Satisfação - O requisito recebeu uma priorização de 0,036 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/First-Things-First>First Things First</a><br>
      Satisfação - O requisito recebeu prioridade OUT na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/In-or-Out/#RF>In or Out</a><br>
      Satisfação - O requisito recebeu $0 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/100-Test/#Req>$100</a><br>
      Satisfação - O requisito recebeu prioridade média na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/Three-Level-Scale/#RF>Three-Level Scale</a><br>
      Agregação - O requisito é classificado no Épico <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/Product-Backlog/#tema6>E06</a>
      </td>
    </tr>
    <tr>
      <td> Print </td>
      <td> - </td>
    </tr>
  </tbody>
</table>

</div>

<font size="2"><p style="text-align: center">Fonte: [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa) </p></font>

### <a name="E04"></a> E04 - Rastrebilidade Forward From do requisito RF22

<font size="3"><p style="text-align: center">Tabela 5: E04 - Cartão do Requisito Funcional 22</p></font>

<div align="center">

<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Descrição do requisito </td>
      <td>O aplicativo deve mostrar o nome completo dos empregadores anteriores</td>
    </tr>
    <tr>
      <td> Categoria </td>
      <td> Desenvolvimento </td>
    </tr>
    <tr>
      <td> Elementos </td>
      <td> <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#RF>RF22</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Observacao/#OB_RF>OB05</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/Historias-De-Usuario/#H28>H28</a></td>
    </tr>
    <tr>
      <td> Elos Forward-from </td>
      <td> 
      Satisfação - O requisito recebeu uma priorização de 0,204 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/First-Things-First>First Things First</a><br>
      Satisfação - O requisito recebeu prioridade OUT na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/In-or-Out/#RF>In or Out</a><br>
      Satisfação - O requisito recebeu $0 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/100-Test/#Req>$100</a><br>
      Satisfação - O requisito recebeu prioridade média na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/Three-Level-Scale/#RF>Three-Level Scale</a><br>
      Agregação - O requisito é classificado no Épico <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/Product-Backlog/#tema6>E06</a>
      </td>
    </tr>
    <tr>
      <td> Print </td>
      <td> - </td>
    </tr>
  </tbody>
</table>

</div>

<font size="2"><p style="text-align: center">Fonte: [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa) </p></font>

### <a name="E05"></a> E05 - Rastrebilidade Forward From do requisito RF23

<font size="3"><p style="text-align: center">Tabela 6: E05 - Cartão do Requisito Funcional 23</p></font>

<div align="center">

<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Descrição do requisito </td>
      <td>O aplicativo deve disponibilizar histórico de saques realizados</td>
    </tr>
    <tr>
      <td> Categoria </td>
      <td> Desenvolvimento </td>
    </tr>
    <tr>
      <td> Elementos </td>
      <td> <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#RF>RF23</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Observacao/#OB_RF>OB06</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/Historias-De-Usuario/#H29>H29</a></td>
    </tr>
    <tr>
      <td> Elos Forward-from </td>
      <td> 
      Satisfação - O requisito recebeu uma priorização de 0,229 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/First-Things-First>First Things First</a><br>
      Satisfação - O requisito recebeu prioridade OUT na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/In-or-Out/#RF>In or Out</a><br>
      Satisfação - O requisito recebeu $6 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/100-Test/#Req>$100</a><br>
      Satisfação - O requisito recebeu prioridade média na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/Three-Level-Scale/#RF>Three-Level Scale</a><br>
      Agregação - O requisito é classificado no Épico <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/Product-Backlog/#tema4>E04</a>
      </td>
    </tr>
    <tr>
      <td> Print </td>
      <td> - </td>
    </tr>
  </tbody>
</table>

</div>

<font size="2"><p style="text-align: center">Fonte: [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa) </p></font>

### <a name="E06"></a> E06 - Rastrebilidade Forward From do requisito RF41

<font size="3"><p style="text-align: center">Tabela 7: E06 - Cartão do Requisito Funcional 41</p></font>

<div align="center">

<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Descrição do requisito </td>
      <td>O aplicativo deve possibilitar o envio de documentos digitalizados (PDF, imagem) para comprovação de situações específicas de saque (ex: doença grave, aposentadoria).</td>
    </tr>
    <tr>
      <td> Categoria </td>
      <td> Desenvolvimento </td>
    </tr>
    <tr>
      <td> Elementos </td>
      <td> <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#RF>RF41</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Brainstroming/#BS_RF>BS03</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/Historias-De-Usuario/#H30)>H30</a></td>
    </tr>
    <tr>
      <td> Elos Forward-from </td>
      <td> 
      Agregação - O requisito é classificado no Épico <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/Product-Backlog/#tema4>E04</a>
      </td>
    </tr>
    <tr>
      <td> Print </td>
      <td> - </td>
    </tr>
  </tbody>
</table>

</div>

<font size="2"><p style="text-align: center">Fonte: [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa) </p></font>

### <a name="E07"></a> E07 - Rastrebilidade Forward From do requisito RNF05

<font size="3"><p style="text-align: center">Tabela 8: E07 - Cartão do Requisito Não Funcional 05</p></font>

<div align="center">

<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Descrição do requisito </td>
      <td>O aplicativo deve ser confiável e evitar falhas ou inconsistências nos processos</td>
    </tr>
    <tr>
      <td> Categoria </td>
      <td> Desenvolvimento </td>
    </tr>
    <tr>
      <td> Elementos </td>
      <td> <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#RNF>RNF05</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Entrevista/#EN_RNF>EN11</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/NFR-Framework/#CE05>Cartão de Especificação 5</a></td>
    </tr>
    <tr>
      <td> Elos Forward-from </td>
      <td> 
      Satisfação - O requisito não funcional recebeu uma priorização de 0,171 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/First-Things-First>First Things First</a><br>
      Satisfação - O requisito não funcional recebeu prioridade IN na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/In-or-Out/#RNF>In or Out</a><br>
      Satisfação - O requisito não funcional recebeu $9 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/100-Test/#Req>$100</a><br>
      Satisfação - O requisito não funcional recebeu prioridade alta na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/Three-Level-Scale/#RNF>Three-Level Scale</a><br>
      Satisfação - O requisito não funcional é satisfeito pelo NFR framework(<a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/NFR-Framework/#CE05>Cartão de Especificação 5</a>)<br>
      Alocação - O requisito não funcional RNF05 foi alocado na categoria de confiabilidade na Especificação Suplementar.
      </td>
    </tr>
  </tbody>
</table>

</div>

<font size="2"><p style="text-align: center">Fonte: [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa) </p></font>

### <a name="E08"></a> E08 - Rastrebilidade Forward From do requisito RNF16

<font size="3"><p style="text-align: center">Tabela 9: E08 - Cartão do Requisito Não Funcional 16</p></font>

<div align="center">

<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Descrição do requisito </td>
      <td>Garantir tempo de resposta de até 1 segundo para o cadastro da conta bancária</td>
    </tr>
    <tr>
      <td> Categoria </td>
      <td> Desenvolvimento </td>
    </tr>
    <tr>
      <td> Elementos </td>
      <td> <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#RNF>RNF16</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#ST_RNF>ST017</a></td>
    </tr>
    <tr>
      <td> Elos Forward-from </td>
      <td> 
      Satisfação - O requisito não funcional recebeu uma priorização de 0,048 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/First-Things-First>First Things First</a><br>
      Satisfação - O requisito não funcional recebeu prioridade Out na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/In-or-Out/#RNF>In or Out</a><br>
      Satisfação - O requisito não funcional recebeu $0 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/100-Test/#Req>$100</a><br>
      Satisfação - O requisito não funcional recebeu prioridade média na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/Three-Level-Scale/#RNF>Three-Level Scale</a>
      </td>
    </tr>
  </tbody>
</table>

</div>

<font size="2"><p style="text-align: center">Fonte: [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa) </p></font>

### <a name="E09"></a> E09 - Rastrebilidade Forward From do requisito RNF17

<font size="3"><p style="text-align: center">Tabela 10: E09 - Cartão do Requisito Não Funcional 17</p></font>

<div align="center">

<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Descrição do requisito </td>
      <td>Garantir tempo de resposta de até 1 segundo para a solicitação de saque</td>
    </tr>
    <tr>
      <td> Categoria </td>
      <td> Desenvolvimento </td>
    </tr>
    <tr>
      <td> Elementos </td>
      <td> <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#RNF>RNF17</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#ST_RNF>ST018</a></td>
    </tr>
    <tr>
      <td> Elos Forward-from </td>
      <td> 
      Satisfação - O requisito não funcional recebeu uma priorização de 0,026 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/First-Things-First>First Things First</a>
      Satisfação - O requisito não funcional recebeu prioridade Out na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/In-or-Out/#RNF>In or Out</a>
      Satisfação - O requisito não funcional recebeu $0 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/100-Test/#Req>$100</a>
      Satisfação - O requisito não funcional recebeu prioridade média na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/Three-Level-Scale/#RNF>Three-Level Scale</a>
      </td>
    </tr>
  </tbody>
</table>

</div>

<font size="2"><p style="text-align: center">Fonte: [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa) </p></font>

### <a name="E10"></a> E10 - Rastrebilidade Forward From do requisito RNF22

<font size="3"><p style="text-align: center">Tabela 11: E10 - Cartão do Requisito Não Funcional 22</p></font>

<div align="center">

<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Descrição do requisito </td>
      <td>A aplicação deve estar em conformidade com diretrizes de acessibilidade, garantindo acesso a pessoas com deficiência visual, auditiva ou motora</td>
    </tr>
    <tr>
      <td> Categoria </td>
      <td> Desenvolvimento </td>
    </tr>
    <tr>
      <td> Elementos </td>
      <td> <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#RNF>RNF22</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#IS_RNF>IS20</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-I/EspecificacaoSuplementar/#RNF>Especificação Suplementar</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/NFR-Framework/#>Cartão de Especificação 6</a><</td>
    </tr>
    <tr>
      <td> Elos Forward-from </td>
      <td> 
      Satisfação - O requisito não funcional é satisfeito pelo NFR framework(<a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/NFR-Framework/#CE06>Cartão de Especificação 6</a>)
      Alocação - O requisito não funcional RNF05 foi alocado na categoria de Acessibilidade na Especificação Suplementar.
      </td>
    </tr>
  </tbody>
</table>

</div>

<font size="2"><p style="text-align: center">Fonte: [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa) </p></font>

### <a name="E11"></a> E11 - Rastrebilidade Forward From do requisito RF15

<font size="3"><p style="text-align: center">Tabela 12: E11 - Cartão do Requisito Funcional 15</p></font>

<div align="center">

<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Descrição do requisito </td>
      <td>O aplicativo deve permitir que o usuário entre em contato com um assistente via chat</td>
    </tr>
    <tr>
      <td> Categoria </td>
      <td> Desenvolvimento </td>
    </tr>
    <tr>
      <td> Elementos </td>
      <td> <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#requisitos-funcionais>RF15</a>, <a href =https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#requisitos-funcionais>IS13</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-I/Cenarios/#cenario-10-contato-com-assistente-via-chat>Cenário 10</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-I/Diagrama/#caso-de-uso-10-is13>Caso de Uso 10</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-I/Lexicos/#l36-chat>L36</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-I/Lexicos/#l37-assistente-virtual>L37</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-I/Lexicos/#l38-mensagem>L38</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/Historias-De-Usuario/#historia-07-assistente-via-chat>H07</a></td>
    </tr>
    <tr>
      <td> Elos Forward-from </td>
      <td> 
      Satisfação - O requisito recebeu uma priorização de 0,047 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/First-Things-First>First Things First</a><br>
      Satisfação - O requisito recebeu prioridade OUT na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/In-or-Out/#RF>In or Out</a><br>
      Satisfação - O requisito recebeu $4 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/100-Test/#Req>$100</a><br>
      Satisfação - O requisito recebeu prioridade baixa na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/Three-Level-Scale/#RF>Three-Level Scale</a><br>
      Agregação - O requisito é classificado no Épico <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/Product-Backlog/#tema-2-saques-e-solicitacoes>E09</a>
      </td>
    </tr>
    <tr>
      <td> Print </td>
      <td> Não implementado </td>
    </tr>
  </tbody>
</table>

</div>

<font size="2"><p style="text-align: center">Fonte: [Marcelo Makoto](https://github.com/MM4k) </p></font>

### <a name="E12"></a> E12 - Rastrebilidade Forward From do requisito RF16

<font size="3"><p style="text-align: center">Tabela 13: E12 - Cartão do Requisito Funcional 16</p></font>

<div align="center">

<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Descrição do requisito </td>
      <td>O aplicativo deve disponibilizar um campo de busca para facilitar a localização de funcionalidades</td>
    </tr>
    <tr>
      <td> Categoria </td>
      <td> Desenvolvimento </td>
    </tr>
    <tr>
      <td> Elementos </td>
      <td> <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#requisitos-funcionais>RF16</a>, <a href =https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#requisitos-funcionais>IS14</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-I/Cenarios/#cenario-11-busca-de-funcionalidades-e-informacoes>Cenário 11</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-I/Diagrama/#caso-de-uso-11-is14>Caso de Uso 11</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-I/Lexicos/#l39-buscar>L39</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-I/Lexicos/#l40-campo-de-busca>L40</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-I/Lexicos/#l41-termo-de-pesquisa>L41</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/Historias-De-Usuario/#historia-08-campo-de-busca>H08</a></td>
    </tr>
    <tr>
      <td> Elos Forward-from </td>
      <td> 
      Satisfação - O requisito recebeu uma priorização de 0,181 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/First-Things-First>First Things First</a><br>
      Satisfação - O requisito recebeu prioridade OUT na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/In-or-Out/#RF>In or Out</a><br>
      Satisfação - O requisito recebeu $4 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/100-Test/#Req>$100</a><br>
      Satisfação - O requisito recebeu prioridade baixa na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/Three-Level-Scale/#RF>Three-Level Scale</a><br>
      Agregação - O requisito é classificado no Épico <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/Product-Backlog/#tema-4-comunicacao-e-suporte>E12</a>
      </td>
    </tr>
    <tr>
      <td> Print </td>
      <td> Não implementado </td>
    </tr>
  </tbody>
</table>

</div>

<font size="2"><p style="text-align: center">Fonte: [Marcelo Makoto](https://github.com/MM4k) </p></font>

### <a name="E13"></a> E13 - Rastrebilidade Forward From do requisito RF14

<font size="3"><p style="text-align: center">Tabela 14: E13 - Cartão do Requisito Funcional 24</p></font>

<div align="center">

<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Descrição do requisito </td>
      <td>O aplicativo deve ter uma aba dedicada à solicitação e acompanhamento de saques</td>
    </tr>
    <tr>
      <td> Categoria </td>
      <td> Desenvolvimento </td>
    </tr>
    <tr>
      <td> Elementos </td>
      <td> <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#requisitos-funcionais>RF24</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Observacao/#requisitos-funcionais>OB07</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/Historias-De-Usuario/#historia-08-campo-de-busca>H08</a></td>
    </tr>
    <tr>
      <td> Elos Forward-from </td>
      <td> 
      Satisfação - O requisito recebeu uma priorização de 0,051 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/First-Things-First>First Things First</a><br>
      Satisfação - O requisito recebeu prioridade OUT na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/In-or-Out/#RF>In or Out</a><br>
      Satisfação - O requisito recebeu $7 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/100-Test/#Req>$100</a><br>
      Satisfação - O requisito recebeu prioridade baixa na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/Three-Level-Scale/#RF>Three-Level Scale</a><br>
      Agregação - O requisito é classificado no Épico <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/Product-Backlog/#tema-2-saques-e-solicitacoes>E04</a>
      </td>
    </tr>
    <tr>
      <td> Print </td>
      <td> - </td>
    </tr>
  </tbody>
</table>

</div>

<font size="2"><p style="text-align: center">Fonte: [Marcelo Makoto](https://github.com/MM4k) </p></font>

### <a name="E14"></a> E14 - Rastrebilidade Forward From do requisito RF25

<font size="3"><p style="text-align: center">Tabela 15: E14 - Cartão do Requisito Funcional 25</p></font>

<div align="center">

<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Descrição do requisito </td>
      <td>O aplicativo deve incluir aba para itens diversos como PIS/PASEP, convocações, sistemática de saque, ajuda, etc.</td>
    </tr>
    <tr>
      <td> Categoria </td>
      <td> Desenvolvimento </td>
    </tr>
    <tr>
      <td> Elementos </td>
      <td> <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#requisitos-funcionais>RF25</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Observacao/#requisitos-funcionais>OB09</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/Historias-De-Usuario/#h10>H10</a></td>
    </tr>
    <tr>
      <td> Elos Forward-from </td>
      <td> 
      Satisfação - O requisito recebeu uma priorização de 0,038 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/First-Things-First>First Things First</a><br>
      Satisfação - O requisito recebeu prioridade OUT na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/In-or-Out/#RF>In or Out</a><br>
      Satisfação - O requisito recebeu $0 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/100-Test/#Req>$100</a><br>
      Satisfação - O requisito recebeu prioridade baixa na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/Three-Level-Scale/#RF>Three-Level Scale</a><br>
      </td>
    </tr>
    <tr>
      <td> Print </td>
      <td> - </td>
    </tr>
  </tbody>
</table>

</div>

<font size="2"><p style="text-align: center">Fonte: [Marcelo Makoto](https://github.com/MM4k) </p></font>

### <a name="E15"></a> E15 - Rastrebilidade Forward From do requisito RF26

<font size="3"><p style="text-align: center">Tabela 16: E15 - Cartão do Requisito Funcional 26</p></font>

<div align="center">

<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Descrição do requisito </td>
      <td>O aplicativo deve exibir um resumo claro dos tipos de saque disponíveis.</td>
    </tr>
    <tr>
      <td> Categoria </td>
      <td> Desenvolvimento </td>
    </tr>
    <tr>
      <td> Elementos </td>
      <td> <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#requisitos-funcionais>RF26</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#requisitos-funcionais>ST02</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/Historias-De-Usuario/#historia-11-resumo-dos-tipos-de-saque>H11</a></td>
    </tr>
    <tr>
      <td> Elos Forward-from </td>
      <td> 
      Satisfação - O requisito recebeu uma priorização de 0,120 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/First-Things-First>First Things First</a><br>
      Satisfação - O requisito recebeu prioridade IN na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/In-or-Out/#RF>In or Out</a><br>
      Satisfação - O requisito recebeu $3 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/100-Test/#Req>$100</a><br>
      Satisfação - O requisito recebeu prioridade alta na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/Three-Level-Scale/#RF>Three-Level Scale</a><br>
      Agregação - O requisito é classificado no Épico <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/Product-Backlog/#tema-2-saques-e-solicitacoes>E04</a>
      </td>
    </tr>
    <tr>
      <td> Print </td>
      <td> - </td>
    </tr>
  </tbody>
</table>

</div>

<font size="2"><p style="text-align: center">Fonte: [Marcelo Makoto](https://github.com/MM4k) </p></font>

### <a name="E16"></a> E16 - Rastrebilidade Forward From do requisito RF36

<font size="3"><p style="text-align: center">Tabela 17: E16 - Cartão do Requisito Funcional 36</p></font>

<div align="center">

<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Descrição do requisito </td>
      <td>O aplicativo deve permitir que o usuário solicite o saque da rescisão</td>
    </tr>
    <tr>
      <td> Categoria </td>
      <td> Desenvolvimento </td>
    </tr>
    <tr>
      <td> Elementos </td>
      <td> <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#requisitos-funcionais>RF36</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#requisitos-funcionais>ST013</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#requisitos-funcionais>ST014</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/Historias-De-Usuario/#historia-12-disponibilidade-de-saque-rescisao>H12</a></td>
    </tr>
    <tr>
      <td> Elos Forward-from </td>
      <td> 
      Agregação - O requisito é classificado no Épico <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/Product-Backlog/#tema-2-saques-e-solicitacoes>E04</a>
      </td>
    </tr>
    <tr>
      <td> Print </td>
      <td> - </td>
    </tr>
  </tbody>
</table>

</div>

<font size="2"><p style="text-align: center">Fonte: [Marcelo Makoto](https://github.com/MM4k) </p></font>

### <a name="E17"></a> E17 - Rastrebilidade Forward From do requisito RNF06

<font size="3"><p style="text-align: center">Tabela 18: E17 - Cartão do Requisito Não Funcional 06</p></font>

<div align="center">

<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Descrição do requisito </td>
      <td>O aplicativo deve funcionar corretamente mesmo com conexão instável</td>
    </tr>
    <tr>
      <td> Categoria </td>
      <td> Desenvolvimento </td>
    </tr>
    <tr>
      <td> Elementos </td>
      <td> <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#requisitos-funcionais>RNF06</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Entrevista/#tabela-4-requisitos-nao-funcionais>EN12</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/NFR-Framework/#cartoes-de-especificacao>Cartão de Especificação 7</a></td>
    </tr>
    <tr>
      <td> Elos Forward-from </td>
      <td> 
      Satisfação - O requisito recebeu uma priorização de 0,085 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/First-Things-First>First Things First</a><br>
      Satisfação - O requisito recebeu prioridade IN na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/In-or-Out/#RF>In or Out</a><br>
      Satisfação - O requisito recebeu $0 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/100-Test/#Req>$100</a><br>
      Satisfação - O requisito recebeu prioridade alta na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/Three-Level-Scale/#RF>Three-Level Scale</a><br>
      </td>
    </tr>
    <tr>
      <td> Print </td>
      <td> - </td>
    </tr>
  </tbody>
</table>

</div>

<font size="2"><p style="text-align: center">Fonte: [Marcelo Makoto](https://github.com/MM4k) </p></font>

### <a name="E18"></a> E18 - Rastrebilidade Forward From do requisito RNF11

<font size="3"><p style="text-align: center">Tabela 19: E18 - Cartão do Requisito Não Funcional 11</p></font>

<div align="center">

<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Descrição do requisito </td>
      <td>O aplicativo deve proporcionar segurança de dados pessoais</td>
    </tr>
    <tr>
      <td> Categoria </td>
      <td> Desenvolvimento </td>
    </tr>
    <tr>
      <td> Elementos </td>
      <td> <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#requisitos-funcionais>RNF11</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#requisitos-nao-funcionais>IS23</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/NFR-Framework/#cartoes-de-especificacao>Cartão de Especificação 8</a></td>
    </tr>
    <tr>
      <td> Elos Forward-from </td>
      <td> 
      Satisfação - O requisito recebeu uma priorização de 0,152 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/First-Things-First>First Things First</a><br>
      Satisfação - O requisito recebeu prioridade IN na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/In-or-Out/#RF>In or Out</a><br>
      Satisfação - O requisito recebeu $5 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/100-Test/#Req>$100</a><br>
      Satisfação - O requisito recebeu prioridade alta na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/Three-Level-Scale/#RF>Three-Level Scale</a><br>
      Agregação - O requisito é classificado no Épico <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/Product-Backlog/#tema-6-seguranca>E13</a>
      </td>
    </tr>
    <tr>
      <td> Print </td>
      <td> - </td>
    </tr>
  </tbody>
</table>

</div>

<font size="2"><p style="text-align: center">Fonte: [Marcelo Makoto](https://github.com/MM4k) </p></font>

### <a name="E19"></a> E19 - Rastrebilidade Forward From do requisito RNF18

<font size="3"><p style="text-align: center">Tabela 20: E19 - Cartão do Requisito Não Funcional 18</p></font>

<div align="center">

<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Descrição do requisito </td>
      <td>Garantir tempo de resposta de até 1 segundo para o processo de login</td>
    </tr>
    <tr>
      <td> Categoria </td>
      <td> Desenvolvimento </td>
    </tr>
    <tr>
      <td> Elementos </td>
      <td> <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#requisitos-funcionais>RNF18</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#requisitos-funcionais>ST019</a></td>
    </tr>
    <tr>
      <td> Elos Forward-from </td>
      <td> 
      Satisfação - O requisito recebeu uma priorização de 0,026 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/First-Things-First>First Things First</a><br>
      Satisfação - O requisito recebeu prioridade OUT na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/In-or-Out/#RF>In or Out</a><br>
      Satisfação - O requisito recebeu $0 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/100-Test/#Req>$100</a><br>
      Satisfação - O requisito recebeu prioridade média na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/Three-Level-Scale/#RF>Three-Level Scale</a><br>
      </td>
    </tr>
    <tr>
      <td> Print </td>
      <td> - </td>
    </tr>
  </tbody>
</table>

</div>

<font size="2"><p style="text-align: center">Fonte: [Marcelo Makoto](https://github.com/MM4k) </p></font>

### <a name="E20"></a> E20 - Rastrebilidade Forward From do requisito RF11

<font size="3"><p style="text-align: center">Tabela 21: E20 - Cartão do Requisito Funcional 11</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Descrição do requisito </td>
      <td>O aplicativo deve fornecer informações sobre saques bloqueados</td>
    </tr>
    <tr>
      <td> Categoria </td>
      <td> Desenvolvimento </td>
    </tr>
    <tr>
      <td> Elementos </td>
      <td> <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#requisitos-funcionais>RF11</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#requisitos-funcionais>IS08</a>, <a href = "https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/Historias-De-Usuario/#historia-13-ver-informacoes-sobre-saques-bloqueados">H13</a></td>
    </tr>
    <tr>
      <td> Elos Forward-from </td>
      <td> 
      Satisfação - O requisito recebeu uma priorização de <b>0,262</b> na técnica <a href = "https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorizacao/First-Things-First">First Things First</a><br>
      Satisfação - O requisito recebeu prioridade <b>IN</b> na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/In-or-Out/#RF>In or Out</a><br>
      Satisfação - O requisito recebeu <b>$5</b> na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/100-Test/#Req>$100</a><br>
      Satisfação - O requisito recebeu prioridade <b>alta</b> na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/Three-Level-Scale/#RF>Three-Level Scale</a><br>
      Agregação - O requisito é classificado no Épico <a href = "https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/Product-Backlog/#tema-1-consulta-e-informacoes-da-conta">E06</a>
      </td>
    </tr>
    <tr>
      <td> Print </td>
      <td> Não implementado </td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: [Danielle Soares](https://github.com/danielle-soaress) </p></font>

### <a name="E21"></a> E21 - Rastrebilidade Forward From do requisito RF35

<font size="3"><p style="text-align: center">Tabela 22: E21 - Cartão do Requisito Funcional 35</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Descrição do requisito </td>
      <td>O aplicativo deve permitir o cadastro de mais de uma conta bancária de diferentes instituições financeiras</td>
    </tr>
    <tr>
      <td> Categoria </td>
      <td> Desenvolvimento </td>
    </tr>
    <tr>
      <td> Elementos </td>
      <td> <a href = "https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#requisitos-funcionais">RF35</a>, <a href = "https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#requisitos-funcionais">IS12</a>, <a href = "https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/Historias-De-Usuario/#historia-13-ver-informacoes-sobre-saques-bloqueados">H14</a></td>
    </tr>
    <tr>
      <td> Elos Forward-from </td>
      <td> 
      Agregação - O requisito é classificado no Épico <a href = "https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/Product-Backlog/#tema-3-contas-bancarias">E08</a>
      </td>
    </tr>
    <tr>
      <td> Print </td>
      <td> Não implementado </td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: [Danielle Soares](https://github.com/danielle-soaress) </p></font>

### <a name="E22"></a> E22 - Rastrebilidade Forward From do requisito RF03

<font size="3"><p style="text-align: center">Tabela 23: E22 - Cartão do Requisito Funcional 3</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Descrição do requisito </td>
      <td>O aplicativo deve permitir consulta ao saldo da conta vinculada do FGTS</td>
    </tr>
    <tr>
      <td> Categoria </td>
      <td> Desenvolvimento </td>
    </tr>
    <tr>
      <td> Elementos </td>
      <td> <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#requisitos-funcionais>RF03</a>, <a href = "https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Entrevista/#tabela-3-requisitos-funcionais">EN05</a>, <a href = "https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/Historias-De-Usuario/#h15">H15</a></td>
    </tr>
    <tr>
      <td> Elos Forward-from </td>
      <td> 
      Satisfação - O requisito recebeu uma priorização de 0,091 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/First-Things-First>First Things First</a><br>
      Satisfação - O requisito recebeu prioridade IN na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/In-or-Out/#RF>In or Out</a><br>
      Satisfação - O requisito recebeu $24 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/100-Test/#Req>$100</a><br>
      Satisfação - O requisito recebeu prioridade média na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/Three-Level-Scale/#RF>Three-Level Scale</a><br>
      Agregação - O requisito é classificado no Épico <a href = "https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/Product-Backlog/#temas-e-epicos">E01</a>
      </td>
    </tr>
    <tr>
      <td> Print </td>
      <td> - </td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: [Danielle Soares](https://github.com/danielle-soaress) </p></font>


### <a name="E23"></a> E23 - Rastrebilidade Forward From do requisito RF04

<font size="3"><p style="text-align: center">Tabela 24: E23 - Cartão do Requisito Funcional 04</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Descrição do requisito </td>
      <td>O aplicativo deve disponibilizar saque Saque-Aniversário</td>
    </tr>
    <tr>
      <td> Categoria </td>
      <td> Desenvolvimento </td>
    </tr>
    <tr>
      <td> Elementos </td>
      <td> <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#requisitos-funcionais>RF04</a>, <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Entrevista/#EN_RF">EN06</a>, <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#ST_RF">ST013</a>, <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#ST_RF">ST014</a>, <a href = "https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/Historias-De-Usuario/#h17">H17</a></td>
    </tr>
    <tr>
      <td> Elos Forward-from </td>
      <td> 
      Satisfação - O requisito recebeu uma priorização de 0,101 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/First-Things-First>First Things First</a><br>
      Satisfação - O requisito recebeu prioridade IN na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/In-or-Out/#RF>In or Out</a><br>
      Satisfação - O requisito recebeu $7 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/100-Test/#Req>$100</a><br>
      Satisfação - O requisito recebeu prioridade alta na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/Three-Level-Scale/#RF>Three-Level Scale</a><br>
      Agregação - O requisito é classificado no Épico <a href = "https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/Product-Backlog/#tema-1-consulta-e-informacoes-da-conta">E04</a>
      </td>
    </tr>
    <tr>
      <td> Print </td>
      <td> - </td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: [Danielle Soares](https://github.com/danielle-soaress) </p></font>


### <a name="E24"></a> E24 - Rastrebilidade Forward From do requisito RF05

<font size="3"><p style="text-align: center">Tabela 25: E24 - Cartão do Requisito Funcional 05</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Descrição do requisito </td>
      <td>O aplicativo deve permitir a atualização dos dados pessoais do usuário</td>
    </tr>
    <tr>
      <td> Categoria </td>
      <td> Desenvolvimento </td>
    </tr>
    <tr>
      <td> Elementos </td>
      <td> <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#requisitos-funcionais>RF05</a>, <a href = "https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#requisitos-funcionais">IS01</a>, <a href = "https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/Historias-De-Usuario/#h16">H16</a></td>
    </tr>
    <tr>
      <td> Elos Forward-from </td>
      <td> 
      Satisfação - O requisito recebeu uma priorização de 0,157 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/First-Things-First>First Things First</a><br>
      Satisfação - O requisito recebeu prioridade IN na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/In-or-Out/#RF>In or Out</a><br>
      Satisfação - O requisito recebeu $6 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/100-Test/#Req>$100</a><br>
      Satisfação - O requisito recebeu prioridade alta na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/Three-Level-Scale/#RF>Three-Level Scale</a><br>
      Agregação - O requisito é classificado no Épico <a href = "https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/Product-Backlog/#temas-e-epicos">E02</a>
      </td>
    </tr>
    <tr>
      <td> Print </td>
      <td> - </td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: [Danielle Soares](https://github.com/danielle-soaress) </p></font>



### <a name="E25"></a> E25 - Rastrebilidade Forward From do requisito RF39

<font size="3"><p style="text-align: center">Tabela 26: E25 - Cartão do Requisito Funcional 39</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Descrição do requisito </td>
      <td>O aplicativo deve possuir comentários detalhados sobre cada status do saque</td>
    </tr>
    <tr>
      <td> Categoria </td>
      <td> Desenvolvimento </td>
    </tr>
    <tr>
      <td> Elementos </td>
      <td> <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#requisitos-funcionais>RF39</a>, <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Entrevista/#EN_RF">EN02</a>, <a href = "https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/Historias-De-Usuario/#h18">H18</a></td>
    </tr>
    <tr>
      <td> Elos Forward-from </td>
      <td> 
      Agregação - O requisito é classificado no Épico <a href = "https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/Product-Backlog/#tema-1-consulta-e-informacoes-da-conta">E04</a>
      </td>
    </tr>
    <tr>
      <td> Print </td>
      <td> - </td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: [Danielle Soares](https://github.com/danielle-soaress) </p></font>

### <a name="E26"></a> E26 - Rastrebilidade Forward From do requisito RNF01

<font size="3"><p style="text-align: center">Tabela 27: E26 - Cartão do Requisito Não Funcional 01</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Descrição do requisito </td>
      <td>A aplicação deve apresentar uma interface simples, com elementos visuais organizados e linguagem acessível, facilitando a navegação.</td>
    </tr>
    <tr>
      <td> Categoria </td>
      <td> Desenvolvimento </td>
    </tr>
    <tr>
      <td> Elementos </td>
      <td> <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#RNF>RNF01</a>, <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Entrevista/#EN_RNF">EN07</a>,
       <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#IS_RNF">IS20</a>,
       <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Observacao/#OB_RNF">OB11</a>,
       <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#ST_RNF">ST01</a>,
       <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#ST_RNF">ST04</a></td>
    </tr>
    <tr>
      <td> Elos Forward-from </td>
      <td> 
      Satisfação - O requisito não funcional recebeu uma priorização de 1,368 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/First-Things-First>First Things First</a><br>
      Satisfação - O requisito não funcional recebeu prioridade IN na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/In-or-Out/#RNF>In or Out</a><br>
      Satisfação - O requisito não funcional recebeu $0 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/100-Test/#Req>$100</a><br>
      Satisfação - O requisito não funcional recebeu prioridade baixa na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/Three-Level-Scale/#RNF>Three-Level Scale</a><br>
      </td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: [Danielle Soares](https://github.com/danielle-soaress) </p></font>

### <a name="E27"></a> E27 - Rastrebilidade Forward From do requisito RNF02

<font size="3"><p style="text-align: center">Tabela 28: E27 - Cartão do Requisito Não Funcional 02</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Descrição do requisito </td>
      <td>O processo de login deve ser simplificado</td>
    </tr>
    <tr>
      <td> Categoria </td>
      <td> Desenvolvimento </td>
    </tr>
    <tr>
      <td> Elementos </td>
      <td> <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#RNF>RNF02</a>, <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Entrevista/#EN_RNF">EN08</a></td>
    </tr>
    <tr>
      <td> Elos Forward-from </td>
      <td> 
      Satisfação - O requisito não funcional recebeu uma priorização de 0,487 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/First-Things-First>First Things First</a><br>
      Satisfação - O requisito não funcional recebeu prioridade OUT na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/In-or-Out/#RNF>In or Out</a><br>
      Satisfação - O requisito não funcional recebeu $0 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/100-Test/#Req>$100</a><br>
      Satisfação - O requisito não funcional recebeu prioridade baixa na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/Three-Level-Scale/#RNF>Three-Level Scale</a><br>
      Satisfação - O requisito não funcional é satisfeito pelo NFR framework(<a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/NFR-Framework/#CE01>Cartão de Especificação 1</a>)<br>
      Alocação - O requisito não funcional RNF05 foi alocado na categoria de usabilidade na Especificação Suplementar.
      </td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: [Danielle Soares](https://github.com/danielle-soaress) </p></font>

### <a name="E28"></a> E28 - Rastrebilidade Forward From do requisito RNF07

<font size="3"><p style="text-align: center">Tabela 29: E28 - Cartão do Requisito Não Funcional 07</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Descrição do requisito </td>
      <td>O aplicativo deve fornecer as mesmas funcionalidades para diferentes plataformas e versões</td>
    </tr>
    <tr>
      <td> Categoria </td>
      <td> Desenvolvimento </td>
    </tr>
    <tr>
      <td> Elementos </td>
      <td> <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#RNF>RNF07</a>, <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#IS_RNF">IS18</a></td>
    </tr>
    <tr>
      <td> Elos Forward-from </td>
      <td> 
      Satisfação - O requisito não funcional recebeu uma priorização de 0,077 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/First-Things-First>First Things First</a><br>
      Satisfação - O requisito não funcional recebeu prioridade IN na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/In-or-Out/#RNF>In or Out</a><br>
      Satisfação - O requisito não funcional recebeu $7 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/100-Test/#Req>$100</a><br>
      Satisfação - O requisito não funcional recebeu prioridade baixa na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/Three-Level-Scale/#RNF>Three-Level Scale</a><br>
      Satisfação - O requisito não funcional é satisfeito pelo NFR framework(<a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/NFR-Framework/#CE02>Cartão de Especificação 2</a>)<br>
      Alocação - O requisito não funcional RNF07 foi alocado na categoria de compatibilidade na Especificação Suplementar.
      </td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: [Danielle Soares](https://github.com/danielle-soaress) </p></font>


### <a name="E29"></a> E29 - Rastrebilidade Forward From do requisito RF02

<font size="3"><p style="text-align: center">Tabela 30: E29 - Cartão do Requisito Funcional 02</p></font>

<div align="center">

<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Descrição do requisito </td>
      <td> O aplicativo deve oferecer canal de suporte ou chatbot para esclarecer dúvidas </td>
    </tr>
    <tr>
      <td> Categoria </td>
      <td> Desenvolvimento </td>
    </tr>
    <tr>
      <td> Elementos </td>
      <td> 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Entrevista/#EN_RF">EN04</a>, 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-I/Diagrama/#UC03">Caso de Uso 3</a>, 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-I/Cenarios/#C03">Cenário 3</a>, 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-I/Lexicos/#L14">L14</a>, 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-I/Lexicos/#L15">L15</a>, 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/Historias-De-Usuario/#H19">H19</a> 
      </td>
    </tr>
    <tr>
      <td> Elos Forward-from </td>
      <td> 
      Satisfação - O requisito recebeu uma priorização de 0,054 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/First-Things-First>First Things First</a> <br>
      Satisfação - O requisito recebeu prioridade OUT na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/In-or-Out/#RF>In or Out</a><br>
      Satisfação - O requisito recebeu $2 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/100-Test/#Req>$100</a><br>
      Satisfação - O requisito recebeu prioridade Baixa na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/Three-Level-Scale/#RF>Three-Level Scale</a><br>
      Agregação - O requisito é classificado no Épico <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/Product-Backlog/#tema3>E09</a>
      </td>
    </tr>
    <tr>
      <td> Print </td>
      <td> Não implementado </td>
    </tr>
  </tbody>
</table>

</div>

<font size="2"><p style="text-align: center">Fonte: [Maria Eduarda](https://github.com/dudaa28) </p></font>


### <a name="E30"></a> E30 - Rastrebilidade Forward From do requisito RF30

<font size="3"><p style="text-align: center">Tabela 31: E30 - Cartão do Requisito Funcional 30</p></font>

<div align="center">

<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Descrição do requisito </td>
      <td> O aplicativo deve permitir o ajuste do tamanho das fontes na interface. </td>
    </tr>
    <tr>
      <td> Categoria </td>
      <td> Desenvolvimento </td>
    </tr>
    <tr>
      <td> Elementos </td>
      <td> 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#requisitos-funcionais">ST08</a>, 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-I/Diagrama/#UC14">Caso de Uso 14</a>, 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-I/Cenarios/#C14">Cenário 14</a>, 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-I/Lexicos/#L16">L16</a>, 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-I/Lexicos/#L17">L17</a>, 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-I/Lexicos/#L18">L18</a>, 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-I/Lexicos/#L19">L19</a>, 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/Historias-De-Usuario/#H20">H20</a> 
      </td>
    </tr>
    <tr>
      <td> Elos Forward-from </td>
      <td> 
      Satisfação - O requisito recebeu uma priorização de 0,365 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/First-Things-First>First Things First</a> <br>
      Satisfação - O requisito recebeu prioridade OUT na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/In-or-Out/#RF>In or Out</a><br>
      Satisfação - O requisito recebeu $2 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/100-Test/#Req>$100</a><br>
      Satisfação - O requisito recebeu prioridade Baixa na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/Three-Level-Scale/#RF>Three-Level Scale</a><br>
      Agregação - O requisito é classificado no Épico <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/Product-Backlog/#tema3>E11</a>
      </td>
    </tr>
    <tr>
      <td> Print </td>
      <td> Não implementado </td>
    </tr>
  </tbody>
</table>

</div>

<font size="2"><p style="text-align: center">Fonte: [Maria Eduarda](https://github.com/dudaa28) </p></font>

### <a name="E31"></a> E31 - Rastrebilidade Forward From do requisito RF27

<font size="3"><p style="text-align: center">Tabela 32: E31 - Cartão do Requisito Funcional 27</p></font>

<div align="center">

<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Descrição do requisito </td>
      <td> O aplicativo deve enviar notificação sobre o andamento do saque. </td>
    </tr>
    <tr>
      <td> Categoria </td>
      <td> Desenvolvimento </td>
    </tr>
    <tr>
      <td> Elementos </td>
      <td> 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#requisitos-funcionais">ST02</a>, 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#requisitos-funcionais">ST09</a>, 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#requisitos-funcionais">ST015</a>, 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/Historias-De-Usuario/#H21">H21</a> 
      </td>
    </tr>
    <tr>
      <td> Elos Forward-from </td>
      <td> 
      Satisfação - O requisito recebeu uma priorização de 0,290 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/First-Things-First>First Things First</a> <br>
      Satisfação - O requisito recebeu prioridade OUT na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/In-or-Out/#RF>In or Out</a><br>
      Satisfação - O requisito recebeu $4 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/100-Test/#Req>$100</a><br>
      Satisfação - O requisito recebeu prioridade Baixa na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/Three-Level-Scale/#RF>Three-Level Scale</a><br>
      Agregação - O requisito é classificado no Épico <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/Product-Backlog/#tema3>E10</a>
      </td>
    </tr>
    <tr>
      <td> Print </td>
      <td> - </td>
    </tr>
  </tbody>
</table>

</div>

<font size="2"><p style="text-align: center">Fonte: [Maria Eduarda](https://github.com/dudaa28) </p></font>

### <a name="E32"></a> E32 - Rastrebilidade Forward From do requisito RF28

<font size="3"><p style="text-align: center">Tabela 33: E32 - Cartão do Requisito Funcional 28</p></font>

<div align="center">

<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Descrição do requisito </td>
      <td> O aplicativo deve permitir a solicitação de saques. </td>
    </tr>
    <tr>
      <td> Categoria </td>
      <td> Desenvolvimento </td>
    </tr>
    <tr>
      <td> Elementos </td>
      <td> 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Entrevista/#tabela-3-requisitos-funcionais">EN01</a>, 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#IS_RF">IS03</a>, 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#requisitos-funcionais">ST06</a>, 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Observacao/#OB_RF">OB03</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/Historias-De-Usuario/">H22</a> 
      </td>
    </tr>
    <tr>
      <td> Elos Forward-from </td>
      <td> 
      Satisfação - O requisito recebeu uma priorização de 0,157 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/First-Things-First>First Things First</a> <br>
      Satisfação - O requisito recebeu prioridade IN na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/In-or-Out/#RF>In or Out</a><br>
      Satisfação - O requisito recebeu $12 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/100-Test/#Req>$100</a><br>
      Satisfação - O requisito recebeu prioridade Alta na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/Three-Level-Scale/#RF>Three-Level Scale</a><br>
      Agregação - O requisito é classificado no Épico <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/Product-Backlog/#tema3>E04</a>
      </td>
    </tr>
    <tr>
      <td> Print </td>
      <td> - </td>
    </tr>
  </tbody>
</table>

</div>

<font size="2"><p style="text-align: center">Fonte: [Maria Eduarda](https://github.com/dudaa28) </p></font>

### <a name="E33"></a> E33 - Rastrebilidade Forward From do requisito RF31

<font size="3"><p style="text-align: center">Tabela 34: E33 - Cartão do Requisito Funcional 31</p></font>

<div align="center">

<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Descrição do requisito </td>
      <td> O aplicativo deve permitir a visualização dos dados da conta bancária cadastrada. </td>
    </tr>
    <tr>
      <td> Categoria </td>
      <td> Desenvolvimento </td>
    </tr>
    <tr>
      <td> Elementos </td>
      <td> 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#requisitos-funcionais">ST010</a>, 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/Historias-De-Usuario/#H23">H23</a> 
      </td>
    </tr>
    <tr>
      <td> Elos Forward-from </td>
      <td> 
      Satisfação - O requisito recebeu uma priorização de 1,096 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/First-Things-First>First Things First</a> <br>
      Satisfação - O requisito recebeu prioridade IN na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/In-or-Out/#RF>In or Out</a><br>
      Satisfação - O requisito recebeu $8 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/100-Test/#Req>$100</a><br>
      Satisfação - O requisito recebeu prioridade Média na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/Three-Level-Scale/#RF>Three-Level Scale</a><br>
      Agregação - O requisito é classificado no Épico <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/Product-Backlog/#tema3>E08</a>
      </td>
    </tr>
    <tr>
      <td> Print </td>
      <td> - </td>
    </tr>
  </tbody>
</table>

</div>

<font size="2"><p style="text-align: center">Fonte: [Maria Eduarda](https://github.com/dudaa28) </p></font>

### <a name="E34"></a> E34 - Rastrebilidade Forward From do requisito RF42

<font size="3"><p style="text-align: center">Tabela 35: E34 - Cartão do Requisito Funcional 42</p></font>

<div align="center">

<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Descrição do requisito </td>
      <td> O aplicativo deve permitir o agendamento de saque futuro FGTS </td>
    </tr>
    <tr>
      <td> Categoria </td>
      <td> Desenvolvimento </td>
    </tr>
    <tr>
      <td> Elementos </td>
      <td> 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Brainstorming/#resultados">BS10</a>, 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/Historias-De-Usuario/#H24">H24</a> 
      </td>
    </tr>
    <tr>
      <td> Elos Forward-from </td>
      <td> 
      Satisfação - O requisito recebeu uma priorização de - na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/First-Things-First>First Things First</a> <br>
      Satisfação - O requisito recebeu prioridade - na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/In-or-Out/#RF>In or Out</a><br>
      Satisfação - O requisito recebeu - na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/100-Test/#Req>$100</a><br>
      Satisfação - O requisito recebeu prioridade - na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/Three-Level-Scale/#RF>Three-Level Scale</a><br>
      Agregação - O requisito é classificado no Épico <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/Product-Backlog/#tema3>E04</a>
      </td>
    </tr>
    <tr>
      <td> Print </td>
      <td> Não implementado </td>
    </tr>
  </tbody>
</table>

</div>

<font size="2"><p style="text-align: center">Fonte: [Maria Eduarda](https://github.com/dudaa28) </p></font>

### <a name="E35"></a> E35 - Rastrebilidade Forward From do requisito RNF21

<font size="3"><p style="text-align: center">Tabela 36: E35 - Cartão do Requisito Não Funcional 21</p></font>

<div align="center">

<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Descrição do requisito </td>
      <td> Os menus devem ser autoexplicativos, com estrutura hierárquica lógica e nomenclatura padronizada </td>
    </tr>
    <tr>
      <td> Categoria </td>
      <td> Desenvolvimento </td>
    </tr>
    <tr>
      <td> Elementos </td>
      <td> 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#IS19">IS19</a>, 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Observacao/#OB11">OB11</a> 
      </td>
    </tr>
    <tr>
      <td> Elos Forward-from </td>
      <td> 
      Satisfação - O requisito recebeu uma priorização de - na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/First-Things-First>First Things First</a> <br>
      Satisfação - O requisito recebeu prioridade - na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/In-or-Out/#RF>In or Out</a><br>
      Satisfação - O requisito recebeu - na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/100-Test/#Req>$100</a><br>
      Satisfação - O requisito recebeu prioridade - na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/Three-Level-Scale/#RF>Three-Level Scale</a><br>
      Agregação - O requisito é classificado no Épico <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/Product-Backlog/#tema3> - </a>
      </td>
    </tr>
    <tr>
      <td> Print </td>
      <td> - </td>
    </tr>
  </tbody>
</table>

</div>

<font size="2"><p style="text-align: center">Fonte: [Maria Eduarda](https://github.com/dudaa28) </p></font>

### <a name="E36"></a> E36 - Rastrebilidade Forward From do requisito RNF12

<font size="3"><p style="text-align: center">Tabela 37: E36 - Cartão do Requisito Não Funcional 12</p></font>

<div align="center">

<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Descrição do requisito </td>
      <td> O aplicativo deve proporcionar agilidade ao acessar as funcionalidades </td>
    </tr>
    <tr>
      <td> Categoria </td>
      <td> Desenvolvimento </td>
    </tr>
    <tr>
      <td> Elementos </td>
      <td> 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#IS24">IS24</a> 
      </td>
    </tr>
    <tr>
      <td> Elos Forward-from </td>
      <td> 
      Satisfação - O requisito recebeu uma priorização de 0,060 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/First-Things-First>First Things First</a> <br>
      Satisfação - O requisito recebeu prioridade IN na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/In-or-Out/#RF>In or Out</a><br>
      Satisfação - O requisito recebeu $0 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/100-Test/#Req>$100</a><br>
      Satisfação - O requisito recebeu prioridade Média na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/Three-Level-Scale/#RF>Three-Level Scale</a><br>
      Agregação - O requisito é classificado no Épico <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/Product-Backlog/#tema3> - </a>
      </td>
    </tr>
    <tr>
      <td> Print </td>
      <td> - </td>
    </tr>
  </tbody>
</table>

</div>

<font size="2"><p style="text-align: center">Fonte: [Maria Eduarda](https://github.com/dudaa28) </p></font>

### <a name="E37"></a> E37 - Rastrebilidade Forward From do requisito RNF19

<font size="3"><p style="text-align: center">Tabela 38: E37 - Cartão do Requisito Não Funcional 19</p></font>

<div align="center">

<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Descrição do requisito </td>
      <td> Saque-aniversário deve atender princípios de acessibilidade </td>
    </tr>
    <tr>
      <td> Categoria </td>
      <td> Desenvolvimento </td>
    </tr>
    <tr>
      <td> Elementos </td>
      <td> 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Entrevista/#EN06">EN06</a> 
      </td>
    </tr>
    <tr>
      <td> Elos Forward-from </td>
      <td> 
      Satisfação - O requisito recebeu uma priorização de - na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/First-Things-First>First Things First</a> <br>
      Satisfação - O requisito recebeu prioridade - na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/In-or-Out/#RF>In or Out</a><br>
      Satisfação - O requisito recebeu - na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/100-Test/#Req>$100</a><br>
      Satisfação - O requisito recebeu prioridade - na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/Three-Level-Scale/#RF>Three-Level Scale</a><br>
      Agregação - O requisito é classificado no Épico <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/Product-Backlog/#tema3> - </a>
      </td>
    </tr>
    <tr>
      <td> Print </td>
      <td> - </td>
    </tr>
  </tbody>
</table>

</div>

<font size="2"><p style="text-align: center">Fonte: [Maria Eduarda](https://github.com/dudaa28) </p></font>

### <a name="E38"></a> E38 - Rastrebilidade Forward From do requisito RF09

<font size="3"><p style="text-align: center">Tabela 39: E38 - Cartão do Requisito Funcional 09</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Descrição do requisito </td>
      <td>O sistema deve permitir que o usuário cancele um saque solicitado</td>
    </tr>
    <tr>
      <td> Categoria </td>
      <td> Desenvolvimento </td>
    </tr>
    <tr>
      <td> Elementos </td>
      <td> <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#RF>RF09</a>, <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#IS_RF">IS06, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-I/Cenarios/#C04>Cenário 4</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-I/Diagrama/#UC04>Caso de Uso 4</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-I/Lexicos/#L20>L20</a>,<a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-I/Lexicos/#L21>L21</a>,<a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-I/Lexicos/#L22>L22</a>,<a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-I/Lexicos/#L23>L23</a>,<a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-I/Lexicos/#L24>L24</a>,<a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-I/Lexicos/#L25>L25</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/Historias-De-Usuario/#H31>H31</a></a></td>
    </tr>
    <tr>
      <td> Elos Forward-from </td>
      <td> 
      Satisfação - O requisito funcional recebeu uma priorização de 0,152 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/First-Things-First>First Things First</a><br>
      Satisfação - O requisito funcional recebeu prioridade IN na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/In-or-Out/#RNF>In or Out</a><br>
      Satisfação - O requisito funcional recebeu $16 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/100-Test/#Req>$100</a><br>
      Satisfação - O requisito funcional recebeu prioridade alta na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/Three-Level-Scale/#RNF>Three-Level Scale</a><br>
      Agregação - O requisito originou-se da Técnica de Introspecção  <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#IS_RF">IS06</a>
      </td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: [Victor Pontual](https://github.com/VictorPontual) </p></font>

### <a name="E39"></a> E39 - Rastrebilidade Forward From do requisito RF10

<font size="3"><p style="text-align: center">Tabela 40: E39 - Cartão do Requisito Funcional 10</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Descrição do requisito </td>
      <td>O aplicativo deve permitir o filtro dos saques por tipo (ex: aniversário, doença, falecimento)</td>
    </tr>
    <tr>
      <td> Categoria </td>
      <td> Desenvolvimento </td>
    </tr>
    <tr>
      <td> Elementos </td>
      <td> <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#RF>RF10</a>, <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#IS_RF">IS07, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-I/Cenarios/#C05>Cenário 5</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-I/Diagrama/#UC05>Caso de Uso 5</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-I/Lexicos/#L26>L26</a>,<a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-I/Lexicos/#L27>L27</a>,<a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-I/Lexicos/#L28>L28</a>,<a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-I/Lexicos/#L29>L29</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/Historias-De-Usuario/#H32>H32</a></a></td>
    </tr>
    <tr>
      <td> Elos Forward-from </td>
      <td>
      Satisfação - O requisito funcional recebeu uma priorização de 0,289 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/First-Things-First>First Things First</a><br>
      Satisfação - O requisito funcional recebeu prioridade OUT na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/In-or-Out/#RNF>In or Out</a><br>
      Satisfação - O requisito funcional recebeu $1 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/100-Test/#Req>$100</a><br>
      Satisfação - O requisito funcional recebeu prioridade baixa na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/Three-Level-Scale/#RNF>Three-Level Scale</a><br>
      Agregação - O requisito originou-se da Técnica de Introspecção  <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#IS_RF">IS07</a>
      </td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: [Victor Pontual](https://github.com/VictorPontual) </p></font>

### <a name="E40"></a> E40 - Rastrebilidade Forward From do requisito RF32

<font size="3"><p style="text-align: center">Tabela 41: E40 - Cartão do Requisito Funcional 32</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Descrição do requisito </td>
      <td>O aplicativo deve oferecer uma interface de login simples.</td>
    </tr>
    <tr>
      <td> Categoria </td>
      <td> Desenvolvimento </td>
    </tr>
    <tr>
      <td> Elementos </td>
      <td> <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#RF>RF32</a>, <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#ST_RF">ST011, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/Historias-De-Usuario/#H33>H33</a></a></td>
    </tr>
    <tr>
      <td> Elos Forward-from </td>
      <td> 
      Satisfação - O requisito funcional recebeu uma priorização de 1,055 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/First-Things-First>First Things First</a><br>
      Satisfação - O requisito funcional recebeu prioridade OUT na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/In-or-Out/#RNF>In or Out</a><br>
      Satisfação - O requisito funcional recebeu $4 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/100-Test/#Req>$100</a><br>
      Satisfação - O requisito funcional recebeu prioridade baixa na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/Three-Level-Scale/#RNF>Three-Level Scale</a><br>
      Agregação - O requisito originou-se da Técnica de Storytelling  <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#ST_RF">ST011</a>
      </td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: [Victor Pontual](https://github.com/VictorPontual) </p></font>

### <a name="E41"></a> E41 - Rastrebilidade Forward From do requisito RF33

<font size="3"><p style="text-align: center">Tabela 42: E41 - Cartão do Requisito Funcional 33</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Descrição do requisito </td>
      <td>O aplicativo deve disponibilizar uma página para escolha da sistemática de saque.</td>
    </tr>
    <tr>
      <td> Categoria </td>
      <td> Desenvolvimento </td>
    </tr>
    <tr>
      <td> Elementos </td>
      <td> <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#RF>RF33</a>, <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#ST_RF">ST012</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/Historias-De-Usuario/#H34>H34</a></td>
    </tr>
    <tr>
      <td> Elos Forward-from </td>
      <td> 
      Satisfação - O requisito funcional recebeu uma priorização de 0,456 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/First-Things-First>First Things First</a><br>
      Satisfação - O requisito funcional recebeu prioridade IN na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/In-or-Out/#RNF>In or Out</a><br>
      Satisfação - O requisito funcional recebeu $6 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/100-Test/#Req>$100</a><br>
      Satisfação - O requisito funcional recebeu prioridade alta na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/Three-Level-Scale/#RNF>Three-Level Scale</a><br>
      Agregação - O requisito originou-se da Técnica de Storytelling  <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#ST_RF">ST012</a>
      </td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: [Victor Pontual](https://github.com/VictorPontual) </p></font>

### <a name="E42"></a> E42 - Rastrebilidade Forward From do requisito RF34

<font size="3"><p style="text-align: center">Tabela 43: E42 - Cartão do Requisito Funcional 34</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Descrição do requisito </td>
      <td>O aplicativo deve exibir o termo de adesão ao usuário no primeiro acesso ao aplicativo</td>
    </tr>
    <tr>
      <td> Categoria </td>
      <td> Desenvolvimento </td>
    </tr>
    <tr>
      <td> Elementos </td>
      <td> <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#RF>RF34</a>, <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#ST_RF">ST016</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/Historias-De-Usuario/#H35>H35</a></td>
    </tr>
    <tr>
      <td> Elos Forward-from </td>
      <td> 
      Satisfação - O requisito funcional recebeu uma priorização de 0,507 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/First-Things-First>First Things First</a><br>
      Satisfação - O requisito funcional recebeu prioridade IN na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/In-or-Out/#RNF>In or Out</a><br>
      Satisfação - O requisito funcional recebeu $0 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/100-Test/#Req>$100</a><br>
      Satisfação - O requisito funcional recebeu prioridade alta na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/Three-Level-Scale/#RNF>Three-Level Scale</a><br>
      Agregação - O requisito originou-se da Técnica de Storytelling  <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#ST_RF">ST016</a>
      </td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: [Victor Pontual](https://github.com/VictorPontual) </p></font>

### <a name="E43"></a> E43 - Rastrebilidade Forward From do requisito RF40

<font size="3"><p style="text-align: center">Tabela 44: E43 - Cartão do Requisito Funcional 40</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Descrição do requisito </td>
      <td>O aplicativo deve enviar notificação ao usuário quando o saque for recebido.</td>
    </tr>
    <tr>
      <td> Categoria </td>
      <td> Desenvolvimento </td>
    </tr>
    <tr>
      <td> Elementos </td>
      <td> <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#RF>RF40</a>, <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#ST_RF">ST015</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/Historias-De-Usuario/#H36>H36</a></td>
    </tr>
    <tr>
      <td> Elos Forward-from </td>
      <td> 
      Agregação - O requisito originou-se da Técnica de Storytelling  <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#ST_RF">ST015</a>
      </td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: [Victor Pontual](https://github.com/VictorPontual) </p></font>

### <a name="E44"></a> E44 - Rastrebilidade Forward From do requisito RNF10

<font size="3"><p style="text-align: center">Tabela 45: E44 - Cartão do Requisito Não Funcional 10</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Descrição do requisito </td>
      <td>O aplicativo deve estar disponível para outras plataformas, como web</td>
    </tr>
    <tr>
      <td> Categoria </td>
      <td> Desenvolvimento </td>
    </tr>
    <tr>
      <td> Elementos </td>
      <td> <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#RNF>RNF10</a>, <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#requisitos-nao-funcionais">IS22</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/NFR-Framework/#cartoes-de-especificacao>Cartão de Especificação 8</a></td>
    </tr>
    <tr>
      <td> Elos Forward-from </td>
      <td>
      Satisfação - O requisito não funcional recebeu uma priorização de 0,095 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/First-Things-First>First Things First</a><br>
      Satisfação - O requisito não funcional recebeu prioridade OUT na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/In-or-Out/#RNF>In or Out</a><br>
      Satisfação - O requisito não funcional recebeu $1 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/100-Test/#Req>$100</a><br>
      Satisfação - O requisito não funcional recebeu prioridade baixa na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/Three-Level-Scale/#RNF>Three-Level Scale</a><br>
      Agregação - O requisito originou-se da Técnica de Instrospecção  <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#requisitos-nao-funcionais">IS22</a>
      </td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: [Victor Pontual](https://github.com/VictorPontual) </p></font>

### <a name="E45"></a> E45 - Rastrebilidade Forward From do requisito RNF13

<font size="3"><p style="text-align: center">Tabela 46: E45 - Cartão do Requisito Não Funcional 13</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Descrição do requisito </td>
      <td>O sistema deve garantir segurança firme com verificação de dados pelo usuário</td>
    </tr>
    <tr>
      <td> Categoria </td>
      <td> Desenvolvimento </td>
    </tr>
    <tr>
      <td> Elementos </td>
      <td> <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#RNF>RNF13</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Observacao/#requisitos-nao-funcionais>OB10</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/NFR-Framework/#cartoes-de-especificacao>Cartão de Especificação 14</a></td>
    </tr>
    <tr>
      <td> Elos Forward-from </td>
      <td> 
      Satisfação - O requisito não funcional recebeu uma priorização de 0,068 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/First-Things-First>First Things First</a><br>
      Satisfação - O requisito não funcional recebeu prioridade IN na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/In-or-Out/#RNF>In or Out</a><br>
      Satisfação - O requisito não funcional recebeu $17 na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/100-Test/#Req>$100</a><br>
      Satisfação - O requisito não funcional recebeu prioridade alta na técnica <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorização/Three-Level-Scale/#RNF>Three-Level Scale</a><br>
      Agregação - O requisito originou-se da Técnica de Observação <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Observacao/#requisitos-nao-funcionais>OB10</a>
      </td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: [Victor Pontual](https://github.com/VictorPontual) </p></font>

### <a name="E46"></a> E46 - Rastrebilidade Forward From do requisito RNF20

<font size="3"><p style="text-align: center">Tabela 47: E46 - Cartão do Requisito Não Funcional 20</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Descrição do requisito </td>
      <td>Saque-rescisão deve atender princípios de acessibilidade</td>
    </tr>
    <tr>
      <td> Categoria </td>
      <td> Desenvolvimento </td>
    </tr>
    <tr>
      <td> Elementos </td>
      <td> <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#RNF>RNF20</a>, <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Entrevista/#EN_RF>EN06</a></td>
    </tr>
    <tr>
      <td> Elos Forward-from </td>
      <td> 
      Agregação - O requisito originou-se da Técnica de Entrevista <a href = https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Entrevista/#EN_RF>EN06</a>
      </td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: [Victor Pontual](https://github.com/VictorPontual) </p></font>

### <a name="E47"></a> E47 - Rastrebilidade Forward From do requisito RF08

<font size="3"><p style="text-align: center">Tabela 48: E47 - Cartão do Requisito Funcional 08</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Descrição do requisito </td>
      <td>O aplicativo deve exibir os status atualizados do saque.</td>
    </tr>
    <tr>
      <td> Categoria </td>
      <td> Desenvolvimento </td>
    </tr>
    <tr>
      <td> Elementos </td>
      <td> 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#rf08">RF08</a>, 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#requisitos-funcionais">IS05</a>, 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Entrevista/#requisitos-funcionais">EN02</a>, 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-II/Historias-De-Usuario/#h01">H01</a>
      </td>
    </tr>
    <tr>
      <td> Elos Forward-from </td>
      <td> 
        Satisfação - O requisito funcional recebeu uma priorização de 0,075 na técnica 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorizacao/First-Things-First/">First Things First</a><br>
        Satisfação - O requisito funcional recebeu prioridade OUT na técnica 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorizacao/In-or-Out/#tabela-1-requisitos-funcionais">In or Out</a><br>
        Satisfação - O requisito funcional recebeu $11 na técnica 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorizacao/100-Test/#aplicacao-da-tecnica">$100</a><br>
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorizacao/Three-Level-Scale/#requisitos-priorizados">Three-Level Scale</a><br>
        Agregação - O requisito originou-se das técnicas de elicitação 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#requisitos-funcionais">IS05</a> e 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Entrevista/#requisitos-funcionais">EN02</a>.
      </td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: [Enzo Emir](https://github.com/EnzoEmir)</p></font>

### <a name="E48"></a> E48 - Rastrebilidade Forward From do requisito RF38

<font size="3"><p style="text-align: center">Tabela 49: E48 - Cartão do Requisito Funcional 38</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Descrição do requisito </td>
      <td>O aplicativo deve notificar o usuário sobre o status do saque solicitado.</td>
    </tr>
    <tr>
      <td> Categoria </td>
      <td> Desenvolvimento </td>
    </tr>
    <tr>
      <td> Elementos </td>
      <td> 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#rf38">RF38</a>, 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#requisitos-funcionais">IS05</a>
      </td>
    </tr>
    <tr>
      <td> Elos Forward-from </td>
      <td> 
        <i>O requisito funcional RF38 não foi priorizado nas técnicas First Things First, In or Out, $100 ou Three-Level Scale.</i><br>
        Agregação - O requisito originou-se da técnica de elicitação 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#requisitos-funcionais">IS05</a>.
      </td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: [Enzo Emir](https://github.com/EnzoEmir)</p></font>

### <a name="E49"></a> E49 - Rastrebilidade Forward From do requisito RF01

<font size="3"><p style="text-align: center">Tabela 50: E49 - Cartão do Requisito Funcional 01</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Descrição do requisito </td>
      <td>O aplicativo deve informar claramente as datas previstas para liberação de valores.</td>
    </tr>
    <tr>
      <td> Categoria </td>
      <td> Desenvolvimento </td>
    </tr>
    <tr>
      <td> Elementos </td>
      <td> 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#rf01">RF01</a>, 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Entrevista/#requisitos-funcionais">EN03</a>
      </td>
    </tr>
    <tr>
      <td> Elos Forward-from </td>
      <td> 
        Satisfação - O requisito funcional recebeu uma priorização de 0,075 na técnica 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorizacao/First-Things-First/">First Things First</a><br>
        Satisfação - O requisito funcional recebeu prioridade OUT na técnica 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorizacao/In-or-Out/#tabela-1-requisitos-funcionais">In or Out</a><br>
        Satisfação - O requisito funcional recebeu $6 na técnica 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorizacao/100-Test/#aplicacao-da-tecnica">$100</a><br>
        Satisfação - O requisito foi classificado como prioridade MÉDIA na técnica 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorizacao/Three-Level-Scale/#requisitos-priorizados">Three-Level Scale</a><br>
        Agregação - O requisito originou-se da técnica de elicitação 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Entrevista/#requisitos-funcionais">EN03</a>.
      </td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: [Enzo Emir](https://github.com/EnzoEmir)</p></font>

### <a name="E50"></a> E50 - Rastrebilidade Forward From do requisito RF17

<font size="3"><p style="text-align: center">Tabela 51: E50 - Cartão do Requisito Funcional 17</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Descrição do requisito </td>
      <td>O aplicativo deve conter uma seção de ajuda com orientações sobre o FGTS e PIS/PAESP.</td>
    </tr>
    <tr>
      <td> Categoria </td>
      <td> Desenvolvimento </td>
    </tr>
    <tr>
      <td> Elementos </td>
      <td> 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#rf17">RF17</a>, 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#requisitos-funcionais">IS15</a>
      </td>
    </tr>
    <tr>
      <td> Elos Forward-from </td>
      <td> 
        Satisfação - O requisito funcional recebeu uma priorização de 0,741 na técnica 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorizacao/First-Things-First/">First Things First</a><br>
        Satisfação - O requisito funcional recebeu prioridade IN na técnica 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorizacao/In-or-Out/#tabela-1-requisitos-funcionais">In or Out</a><br>
        Satisfação - O requisito foi classificado como prioridade MÉDIA na técnica 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorizacao/Three-Level-Scale/#requisitos-priorizados">Three-Level Scale</a><br>
        Agregação - O requisito originou-se da técnica de elicitação 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#requisitos-funcionais">IS15</a>.
      </td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: [Enzo Emir](https://github.com/EnzoEmir)</p></font>


### <a name="E51"></a> E51 - Rastrebilidade Forward From do requisito RF19

<font size="3"><p style="text-align: center">Tabela 52: E51 - Cartão do Requisito Funcional 19</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Descrição do requisito </td>
      <td>O aplicativo deve permitir a solicitação de ressarcimento de valores do PIS/PASEP.</td>
    </tr>
    <tr>
      <td> Categoria </td>
      <td> Desenvolvimento </td>
    </tr>
    <tr>
      <td> Elementos </td>
      <td> 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#rf19">RF19</a>, 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#requisitos-funcionais">IS17</a>
      </td>
    </tr>
    <tr>
      <td> Elos Forward-from </td>
      <td> 
        Satisfação - O requisito funcional recebeu prioridade IN na técnica 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorizacao/In-or-Out/#tabela-1-requisitos-funcionais">In or Out</a><br>
        Satisfação - O requisito funcional recebeu $8 na técnica 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorizacao/100-Test/#aplicacao-da-tecnica">$100</a><br>
        Satisfação - O requisito foi classificado como prioridade ALTA na técnica 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorizacao/Three-Level-Scale/#requisitos-priorizados">Three-Level Scale</a><br>
        Agregação - O requisito originou-se da técnica de elicitação 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#requisitos-funcionais">IS17</a>.
      </td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: [Enzo Emir](https://github.com/EnzoEmir)</p></font>

### <a name="E52"></a> E52 - Rastrebilidade Forward From do requisito RF20

<font size="3"><p style="text-align: center">Tabela 53: E52 - Cartão do Requisito Funcional 20</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Descrição do requisito </td>
      <td>O aplicativo deve permitir login seguro pelo aplicativo.</td>
    </tr>
    <tr>
      <td> Categoria </td>
      <td> Desenvolvimento </td>
    </tr>
    <tr>
      <td> Elementos </td>
      <td> 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#rf20">RF20</a>, 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Observacao/#requisitos-funcionais">OB01</a>
      </td>
    </tr>
    <tr>
      <td> Elos Forward-from </td>
      <td> 
        Satisfação - O requisito funcional recebeu uma priorização de 0,066 na técnica 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorizacao/First-Things-First/">First Things First</a><br>
        Satisfação - O requisito funcional recebeu prioridade IN na técnica 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorizacao/In-or-Out/#tabela-1-requisitos-funcionais">In or Out</a><br>
        Satisfação - O requisito funcional recebeu $21 na técnica 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorizacao/100-Test/#aplicacao-da-tecnica">$100</a><br>
        Satisfação - O requisito foi classificado como prioridade ALTA na técnica 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorizacao/Three-Level-Scale/#requisitos-priorizados">Three-Level Scale</a><br>
        Agregação - O requisito originou-se da técnica de elicitação 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Observacao/#requisitos-funcionais">OB01</a>.
      </td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: [Enzo Emir](https://github.com/EnzoEmir)</p></font>

### <a name="E53"></a> E53 - Rastrebilidade Forward From do requisito RNF04

<font size="3"><p style="text-align: center">Tabela 54: E53 - Cartão do Requisito Não Funcional 04</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Descrição do requisito </td>
      <td>Os prazos informados no app devem ser cumpridos fielmente.</td>
    </tr>
    <tr>
      <td> Categoria </td>
      <td> Qualidade </td>
    </tr>
    <tr>
      <td> Elementos </td>
      <td> 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#rnf04">RNF04</a>, 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Entrevista/#requisitos-nao-funcionais">EN10</a>
      </td>
    </tr>
    <tr>
      <td> Elos Forward-from </td>
      <td> 
        Satisfação - O requisito não funcional recebeu uma priorização de 0,228 na técnica 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorizacao/First-Things-First/">First Things First</a><br>
        Satisfação - O requisito não funcional recebeu prioridade IN na técnica 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorizacao/In-or-Out/#tabela-1-requisitos-funcionais">In or Out</a><br>
        Satisfação - O requisito foi classificado como prioridade ALTA na técnica 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorizacao/Three-Level-Scale/#requisitos-priorizados">Three-Level Scale</a><br>
        Agregação - O requisito originou-se da técnica de elicitação 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Entrevista/#requisitos-nao-funcionais">EN10</a>.
      </td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: [Enzo Emir](https://github.com/EnzoEmir)</p></font>

### <a name="E54"></a> E54 - Rastrebilidade Forward From do requisito RNF09

<font size="3"><p style="text-align: center">Tabela 55: E54 - Cartão do Requisito Não Funcional 09</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Descrição do requisito </td>
      <td>O aplicativo deve aplicar princípios de acessibilidade.</td>
    </tr>
    <tr>
      <td> Categoria </td>
      <td> Qualidade </td>
    </tr>
    <tr>
      <td> Elementos </td>
      <td> 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#rnf09">RNF09</a>, 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#requisitos-nao-funcionais">IS21</a>
      </td>
    </tr>
    <tr>
      <td> Elos Forward-from </td>
      <td> 
        Satisfação - O requisito não funcional recebeu uma priorização de 0,270 na técnica 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorizacao/First-Things-First/">First Things First</a><br>
        Satisfação - O requisito não funcional recebeu prioridade OUT na técnica 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorizacao/In-or-Out/#tabela-1-requisitos-funcionais">In or Out</a><br>
        Satisfação - O requisito foi classificado como prioridade BAIXA na técnica 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorizacao/Three-Level-Scale/#requisitos-priorizados">Three-Level Scale</a><br>
        Agregação - O requisito originou-se da técnica de elicitação 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#requisitos-nao-funcionais">IS21</a>.
      </td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: [Enzo Emir](https://github.com/EnzoEmir)</p></font>

### <a name="E55"></a> E55 - Rastrebilidade Forward From do requisito RNF15

<font size="3"><p style="text-align: center">Tabela 56: E55 - Cartão do Requisito Não Funcional 15</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Descrição do requisito </td>
      <td>As informações devem estar organizadas de forma clara e com terminologia compreensível para o usuário.</td>
    </tr>
    <tr>
      <td> Categoria </td>
      <td> Qualidade </td>
    </tr>
    <tr>
      <td> Elementos </td>
      <td> 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Requisitos-elicitados/#rnf15">RNF15</a>, 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Observacao/#requisitos-nao-funcionais">OB13</a>
      </td>
    </tr>
    <tr>
      <td> Elos Forward-from </td>
      <td> 
        Satisfação - O requisito não funcional recebeu uma priorização de 0,222 na técnica 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorizacao/First-Things-First/">First Things First</a><br>
        Satisfação - O requisito não funcional recebeu prioridade IN na técnica 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorizacao/In-or-Out/#tabela-1-requisitos-funcionais">In or Out</a><br>
        Satisfação - O requisito não funcional recebeu $6 na técnica 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorizacao/100-Test/#aplicacao-da-tecnica">$100</a><br>
        Satisfação - O requisito foi classificado como prioridade MÉDIA na técnica 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Priorizacao/Three-Level-Scale/#requisitos-priorizados">Three-Level Scale</a><br>
        Agregação - O requisito originou-se da técnica de elicitação 
        <a href="https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Observacao/#requisitos-nao-funcionais">OB13</a>.
      </td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: [Enzo Emir](https://github.com/EnzoEmir)</p></font>


## Referências Bibliográficas

> <a name="REF1">1. </a>AYÃO, Miriam; LEITE, Julio. Rastreabilidade de Requisitos. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005. Disponível em: https://www-di.inf.puc-rio.br/~julio/rastre.pdf. Acesso em: 08 de jun. de 2025

> <a name="REF2">2. </a>TORANZO, M.; CASTRO, J; MELLO, E. Uma proposta para melhorar o rastreamento de requisitos. PUC-Rio: Workshop em Engenharia de Requisitos, Rio de Janeiro, 2002. Disponível em: http://wer.inf.puc-rio.br/WERpapers/artigos/artigos_WER02/toranzo.pdf. Acesso em: 08 de jun. de 2025.

<font size="3"><p style="text-align: center">Figura 1: Foto da referência 1</p></font>

<div align="center">
  <img src="./../assets/pos-rastreabilidade/referencias/ref1.png" alt="FIGURA 1">
</div>

<font size="2"><p style="text-align: center">Fonte: [AYÃO, LEITE, 2005](https://www-di.inf.puc-rio.br/~julio/rastre.pdf) </p></font>

<font size="3"><p style="text-align: center">Figura 2: Foto da referência 2</p></font>

<div align="center">
  <img src="./../assets/pos-rastreabilidade/referencias/ref2.png" alt="FIGURA 2">
</div>

<font size="2"><p style="text-align: center">Fonte: [TORANZO, CASTO, MELLO, 2002](http://wer.inf.puc-rio.br/WERpapers/artigos/artigos_WER02/toranzo.pdf) </p></font>

##  Histórico de Versão

| Versão | Data       | Descrição                                 | Autor(es)                                     | Revisor(es) |
|--------|------------|--------------------------------------------|-----------------------------------------------|-------------|
| `1.0`  | 07/06/2025 | Criação da página | [Enzo Emir](https://github.com/EnzoEmir)     | [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa)  |
| `1.1`  | 07/06/2025 | Adição das E01 - E10 | [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa)    | [Marcelo Makoto](https://github.com/MM4k)  |
| `1.2`  | 07/06/2025 | Adição das E11 - E19 | [Marcelo Makoto](https://github.com/MM4k)    | [Danielle Soares](https://github.com/danielle-soaress) |
| `1.3`  | 07/06/2025 | Adição das E20 - E28 | [Danielle Soares](https://github.com/danielle-soaress) | [Maria Eduarda](https://github.com/dudaa28) |
| `1.4`  | 08/06/2025 | Adição das E29 - E37 | [Maria Eduarda](https://github.com/dudaa28) | [Victor Pontual](https://github.com/VictorPontual) |
| `1.5`  | 08/06/2025 | Adição das tabelas E38 - E46 |  [Victor Pontual](https://github.com/VictorPontual)   | [Danielle Soares](https://github.com/danielle-soaress) |
| `1.6`  | 08/06/2025 | Introdução, Metodologia e Referências  | [Danielle Soares](https://github.com/danielle-soaress) | [Enzo Emir](https://github.com/EnzoEmir) |
| `1.7`  | 08/06/2025 | Sumário, melhorando organização da página | [Danielle Soares](https://github.com/danielle-soaress) | [Enzo Emir](https://github.com/EnzoEmir) |
| `1.8`  | 08/06/2025 | Adição das E47 - E55 | [Enzo Emir](https://github.com/EnzoEmir) | - |
