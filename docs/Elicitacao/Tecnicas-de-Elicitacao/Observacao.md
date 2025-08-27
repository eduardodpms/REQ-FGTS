# Observação

## Introdução

A observação é uma técnica de elicitação direta que permite captar comportamentos, dificuldades e práticas reais dos usuários em seu contexto de uso <a href="#REF1">1</a> . Ao contrário das entrevistas, a observação permite perceber ações implícitas, que muitas vezes não são relatadas verbalmente, e registrar de forma detalhada o fluxo de interação.

Neste trabalho, foi realizada uma **sessão de observação do aplicativo FGTS**, com foco na navegação e nos recursos acessados por um usuário durante o uso espontâneo da aplicação.

## Metodologia

A primeira sessão de observação foi conduzida por Eduardo de Pina, com base em uma gravação de interação da usuária Maria Eduarda utilizando o aplicativo FGTS. A observação foi não participativa, de forma que os observadores assumiram uma postura passiva, permitindo captar o uso espontâneo do sistema.

Durante a análise da gravação, Victor Pontual foi responsável por registrar os requisitos elicitados a partir do comportamento da usuária. A sessão ocorreu no dia 04 de maio de 2025 e teve duração aproximada de 30 minutos.

A segunda sessão de observação foi conduzida por Maria Eduarda e Enzo Emir, com base na observação do usuário 2 (Anônimo), de maneira presencial. A observação foi participativa, de forma que os observadores assumiram uma postura ativa, interagindo com o usuário em determinados momentos do processo. Nessa sessão, os dois observadores tomaram notas enquanto conduziram a técnica de elicitação.

<font size="3"><p style="text-align: center">Tabela 1: Participantes da Técnica</p></font>

<div align="center">

<div align="center">
  <table>
    <thead>
      <tr>
        <th colspan="5"></th>
      </tr>
      <tr>
        <th>Sessão</th>
        <th>Nome</th>
        <th>Data</th>
        <th>Hora</th>
        <th>Local</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td rowspan="2"><strong>Sessão 1</strong></td>
        <td>Eduardo de Pina</td>
        <td>04/05/2023</td>
        <td>17:00</td>
        <td>Discord</td>
      </tr>
      <tr>
        <td>Victor Pontual</td>
        <td>04/05/2023</td>
        <td>18:40</td>
        <td>Discord</td>
      </tr>
      <tr>
        <td rowspan="2"><strong>Sessão 2</strong></td>
        <td>Enzo Emir</td>
        <td>26/06/2025</td>
        <td>14:00</td>
        <td>UnB - Campus Gama</td>
      </tr>
      <tr>
        <td>Maria Eduarda</td>
        <td>26/06/2025</td>
        <td>14:00</td>
        <td>UnB - Campus Gama</td>
      </tr>
    </tbody>
  </table>
</div>

</div>


<p style="text-align: center; font-size: 16px;">Fonte: Autores</p>

<font size="3"><p style="text-align: center">Tabela 2: Detalhes da Observação</p></font>

<div align="center">

<table>
  <thead>
    <tr>
      <th>Nome do Usuário Observado</th>
      <th>Data</th>
      <th>Hora</th>
      <th>Local</th>
      <th>Observador</th>
      <th>Anotador de Requisitos</th>
      <th>Meio de Observação</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Maria Eduarda</td>
      <td>26/06/2025</td>
      <td>14:00</td>
      <td>UnB - Campus Gama</td>
      <td>Eduardo de Pina</td>
      <td>Victor Pontual</td>
      <td>Gravação de Interação</td>
    </tr>
    <tr>
      <td>Anônimo</td>
      <td>26/05/2025</td>
      <td>14:26</td>
      <td>Discord</td>
      <td>Enzo Emir, Maria Eduarda</td>
      <td>Enzo Emir, Maria Eduarda</td>
      <td>Presencial</td>
    </tr>
  </tbody>

</table>

</div>


<p style="text-align: center; font-size: 16px;">Fonte: Autores</p>

---

## Requisitos Elicitados

As funcionalidades observadas foram organizadas a seguir como possíveis **Requisitos Funcionais (RF)** ou **Não Funcionais (RNF)**. O código **EOx** indica que a origem é observação.

<font size="3"><p style="text-align: center">Tabela 2: Legenda</p></font>

<div align="center">

<table>
  <thead>
    <tr>
      <th>Código</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>RFx</td>
      <td>Requisito Funcional nº x</td>
    </tr>
    <tr>
      <td>RNFx</td>
      <td>Requisito Não-Funcional nº x</td>
    </tr>
    <tr>
      <td>EOx</td>
      <td>Requisito nº x elicitado por observação</td>
    </tr>
  </tbody>
</table>

</div>


<p style="text-align: center; font-size: 16px;">Fonte: <i>Enzo Emir</i></p>

---

### Requisitos Funcionais

<font size="3"><p style="text-align: center">Tabela 3: Requisitos Funcionais</p></font>

<a name="OB_RF"></a>

| Código | Requisito Funcional                                                                             | ID   | Implementado |
| ------ | ----------------------------------------------------------------------------------------------- | ---- | :----------: |
| RF05   | O aplicativo deve permitir login seguro                                                           | OB01 |      Sim     |
| RF06   | O aplicativo deve apresentar resumo de empregadores anteriores com botão para consultar contas vinculadas ao FGTS | OB02 |      Sim     |
| RF07   | O aplicativo deve permitir solicitação de saque com justificativa selecionável                                    | OB03 |      Sim     |
| RF08   | O aplicativo deve exibir extrato do FGTS por empregador individual                                                | OB04 |      Sim     |
| RF09   | O aplicativo deve mostrar nome completo dos empregadores anteriores                                               | OB05 |      Sim     |
| RF10   | O aplicativo deve disponibilizar histórico de saques realizados                                                   | OB06 |      Sim     |
| RF11   | O aplicativo deve ter uma aba dedicada à solicitação e acompanhamento de saques                                   | OB07 |      Sim     |
| RF12   | O aplicativo deve possibilitar configuração de conta bancária para depósito e visualização de termos do FGTS      | OB08 |      Sim     |
| RF13   | O aplicativo deve incluir aba para itens diversos como PIS/PASEP, convocações, sistemática de saque, ajuda, etc.  | OB09 |      Sim     |

---

### Requisitos Não Funcionais

<font size="3"><p style="text-align: center">Tabela 4: Requisitos Não Funcionais</p></font>

<a name="OB_RNF"></a>

| Código | Requisito Não-Funcional                                                                               | ID   | Implementado |
| ------ | ----------------------------------------------------------------------------------------------------- | ---- | :----------: |
| RNF06  | O sistema deve garantir segurança firme com verificação de dados pelo usuário                         | OB10 |      Sim     |
| RNF07  | A interface deve ser dividida em abas específicas com funções bem segmentadas                         | OB11 |      Sim     |
| RNF08  | A aplicação deve exibir notificações ou notícias úteis de forma acessível                             | OB12 |      Sim     |
| RNF09  | As informações devem estar organizadas de forma clara e com terminologia compreensível para o usuário | OB13 |      Sim     |

---

## Registro Visual da Observação

<p style="text-align: center">Figura 1 – Print da anotação feita durante a observação da usuária Maria Eduarda</p> <div align="center"> <img src="https://github.com/eduardodpms/REQ-FGTS/blob/de360069d904511f4ce44b321816e0403384e92c/docs/assets/observa%C3%A7%C3%A3o/notasDeObserva%C3%A7%C3%A3o.jpg?raw=true" width="500px"/> </div> <p style="text-align: center; font-size: 16px;">Fonte: <i>Victor Pontual (anotações registradas durante a observação)</i></p>

## Gravação

<p style="text-align: center">
<iframe width="560" height="315" src="https://youtube.com/embed/Ih51yK-A90c?si=yIwT0zeufa5ZDdIv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</p>

<p style="text-align: center">
<iframe width="560" height="315" src="https://youtube.com/embed/w4cJ_Tountw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</p>



## Referências Bibliográficas

> <a id="REF1">1.</a> VAZQUEZ, Carlos Eduardo; SIMÕES, Guilherme Siqueira. Engenharia de Requisitos: software orientado ao negócio. Brasport, 2016.

---

## Histórico de Versões 📅

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
|:-:|:-:|:-:|:-:|:-:|
| `1.0` | 04/05/2025 | Documento de elicitação com base em observação | [Victor Pontual](https://github.com/VictorPontual) | [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa)  |
| `1.1` | 17/05/2025 | Adição de âncoras e correção dos IDs de rastreabilidade | [Danielle Soares](https://github.com/danielle-soaress) | [Eduardo de Pina](https://github.com/eduardodpms) |
| `1.2` | 17/05/2025 | Corrigindo bug nas tabelas | [Danielle Soares](https://github.com/danielle-soaress) | [Eduardo de Pina](https://github.com/eduardodpms) |
| `1.3` | 21/05/2025 | Alteração no texto da Metodologia | [Danielle Soares](https://github.com/danielle-soaress) | [Maria Eduarda](https://github.com/dudaa28) |
| `1.4` | 21/05/2025 | Referências bibliográficas no texto | [Danielle Soares](https://github.com/danielle-soaress) | [Enzo Emir](https://github.com/EnzoEmir) |
| `1.5` | 22/06/2025 | Adição de revisores | [Victor Pontual](https://github.com/VictorPontual) | [Marcelo Makoto](https://github.com/MM4k) |
| `1.5` | 22/06/2025 | Adição de revisores | [Victor Pontual](https://github.com/VictorPontual) | [Marcelo Makoto](https://github.com/MM4k) |
| `1.6`  | 28/06/2025 | Elicitação Presencial e Atualizção do Texto | [Danielle Soares](https://github.com/danielle-soaress) | [Enzo Emir](https://github.com/EnzoEmir) |
| `1.7`  | 28/06/2025 | Atualizando tabela | [Danielle Soares](https://github.com/danielle-soaress) | [Enzo Emir](https://github.com/EnzoEmir) |