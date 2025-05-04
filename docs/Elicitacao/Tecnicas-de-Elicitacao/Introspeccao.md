# Introspecção


## Introdução

A introspecção é uma técnica muito rica e profunda de elicitação de requisitos. Ela consiste em compreender quais propriedades o sistema deve possuir para ser bem-sucedido, exigindo que o engenheiro de requisitos imagine o que ele gostaria que o sistema fizesse, caso estivesse desempenhando uma tarefa com os recursos disponíveis. Por meio dessa reflexão pessoal e analítica, é possível levantar aspectos essenciais do sistema, mesmo sem a presença direta de usuários ou especialistas.

Dessa forma, os requisitos elicitados a partir da introspecção estão organizados nas Tabelas 3 e 4, categorizados entre requisitos funcionais e não-funcionais.

## Metodologia

O processo de introspecção foi realizado individualmente pelas integrantes Maria Eduarda e Danielle. Por meio de uma chamada foi estudado e compreendido a técnica e logo após, cada uma criou seu próprio cenário e por meio desse cenário foi feita a análise do aplicativo e a elicitação dos requisitos, sendo aplicada a técnica de forma isolada na ferramenta **FIGMA*.Em seguida, categorizamos as elicitações em requisitos funcionais e não-funcionais. Ao final desse processo individual, foi organizado os requisitos resultantes nas Tabelas 3 e 4.

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
      <td>Danielle</td>
      <td>03/05/2023</td>
      <td>14:30</td>
    </tr>
    <tr>
      <td>Maria Eduarda</td>
      <td>03/05/2023</td>
      <td>17:45</td>
    </tr>
  </tbody>
</table>

</div>


<p style="text-align: center; font-size: 16px;">Fonte: <i>Maria Eduarda</i></p>


### <span style="color:blue">Danielle</span>

Durante o processo de introspecção, me coloquei no lugar de uma usuária que busca praticidade para consultar e movimentar seu benefício. Imaginei que o aplicativo ideal deveria permitir ações simples como ver o saldo, realizar saques digitais e acompanhar sua situação com clareza. 

Ao pensar nas dificuldades, percebi a falta de recursos como chat com assistente, filtros por data e múltiplas contas bancárias. Essas ausências me fizeram perceber como funcionalidades básicas são essenciais para uma boa experiência. 

A reflexão mostrou a importância de um sistema que vá além do básico, oferecendo controle real ao usuário.

---

### <span style="color:blue">Maria Eduarda</span>

Ao imaginar meu uso do aplicativo, percebi que funcionalidades como ver o saldo total na tela inicial e acessar o histórico de movimentações são fundamentais. Reflito que a experiência melhora quando o sistema oferece busca por atividade, variedade de bancos e uma ajuda acessível.

Também notei a importância de poder excluir contas e visualizar informações organizadas por ícones e categorias. A introspecção me fez enxergar que um aplicativo útil é aquele que combina clareza, praticidade e autonomia ao usuário desde o primeiro acesso.



Com o objetivo de registrar o estudo e realização da tecnica da introspecção feita em chamada, de forma individual no ambiente **FIGMA** , disponibilizamos o documento completo no link abaixo:

<a href="../../../assets/introspecçao.pdf" target="_blank">📄 Ver documento completo</a>

<iframe src="../../../assets/introspecçao.pdf" width="100%" height="450px">
    Este navegador não suporta PDFs. Faça o download <a href="../../../assets/introspecçao.pdf">aqui</a>.
</iframe>


## Requisitos Elicitados

A seguir, as Tabelas 3 e 4 descrevem os requisitos elicitados, incluindo tanto os que foram implementados quanto os que ainda não foram. Por fim, a Tabela 2 apresenta a legenda das Tabelas 3 e 4.

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
      <td><strong>RFx</strong></td>
      <td>Requisito Funcional nº x</td>
    </tr>
    <tr>
      <td><strong>RNFx</strong></td>
      <td>Requisito Não-Funcional nº x</td>
    </tr>
    <tr>
      <td><strong>ISx</strong></td>
      <td>Requisito nº x elicitado pela introspecção</td>
    </tr>
  </tbody>
</table>

</div>

<p style="text-align: center; font-size: 16px;">Fonte: <i>Danielle</i></p>


### Requisitos Funcionais

<font size="3"><p style="text-align: center">Tabela 3: Requisitos Funcionais</p></font>


| Código | Requisito Funcional | ID | Implementado |
| :-: | - | :-: | :-: |
| RF01  | O aplicativo deve permitir a atualização dos dados pessoais do usuário | IS01 | Sim |
| RF02  | O sistema deve permitir a consulta de dados pessoais do usuário | IS02 | Sim |
| RF03  | O aplicativo deve permitir que o usuário realize saques de forma digital | IS03 | Sim |
| RF04  | O aplicativo deve exibir o saldo disponível e o extrato de depósitos realizados pelo empregador | IS04 | Sim |
| RF05  | O aplicativo deve permitir ao usuário acompanhar a situação de um pedido de saque | IS05 | Sim |
| RF06  | O sistema deve permitir que o usuário cancele um saque solicitado | IS06 | Não |
| RF07  | O aplicativo deve permitir o filtro dos saques por tipo (ex: aniversário, doença, falecimento) | IS07 | Não |
| RF08  | O aplicativo deve fornecer informações sobre saques bloqueados e os motivos do bloqueio | IS08 | Não |
| RF09  | O aplicativo deve exibir informações detalhadas sobre o histórico de movimentações financeiras | IS09 | Não |
| RF10  | O aplicativo deve permitir o filtro do extrato por data (mês e ano). | IS10 | Não |
| RF11  | O aplicativo deve permitir o cadastro de uma conta bancária | IS11 | Sim |
| RF12  | O aplicativo deve permitir o cadastro de mais de uma conta bancária de diferentes instituições financeiras | IS12 | Não |
| RF13  | O aplicativo deve permitir que o usuário entre em contato com um assistente via chat | IS13 | Não |
| RF14  | O aplicativo deve disponibilizar um campo de busca para facilitar a localização de funcionalidades ou informações | IS14 | Não |
| RF15  | O aplicativo deve conter uma seção de ajuda com orientações sobre o FGTS e PIS/PAESP | IS15 | Sim |
| RF16  | O aplicativo deve conter uma seção de ajuda com orientações sobre o uso do aplicativo | IS16 | Não |
| RF17  | O aplicativo deve permitir a solicitação de ressarcimento de valores do PIS/PASEP | IS17 | Sim |

<p style="text-align: center; font-size: 16px;">Fonte: <i>Danielle</i></p>

### Requisitos Não Funcionais


<font size="3"><p style="text-align: center">Tabela 4: Requisitos Não Funcionais</p></font>


| Código  | Requisito Funcional                                                                 | ID    | Implementado |
|:-------:|--------------------------------------------------------------------------------------|:-----:|:------------:|
| RNF01   | O aplicativo deve fornecer as mesmas funcionalidades para diferentes plataformas e versões | IS18 | Não          |
| RNF02   | Os menus devem fornecer informações não repetidas                                   | IS19 | Não          |
| RNF03   | O aplicativo deve aplicar princípios de usabilidade                                 | IS20 | Não          |
| RNF04   | O aplicativo deve aplicar princípios de acessibilidade                              | IS21 | Não          |
| RNF05   | O aplicativo deve estar disponível para outras plataformas, como web                | IS22 | Não          |
| RNF06   | O aplicativo deve proporcionar segurança de dados pessoais                          | IS23 | Sim          |
| RNF07   | O aplicativo deve proporcionar agilidade ao acessar as funcionalidades              | IS24 | Sim          |

<p style="text-align: center; font-size: 16px;">Fonte: <i>Maria Eduarda</i></p>

## Gravação da Elicitação

<p style="text-align: center">
<iframe width="560" height="315" src="https://www.youtube.com/embed/5DNvaRJVY74" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</p>


## Referências

> <a id="REF1" href="#anchor_1">1.</a> SERRANO, Milene; SERRANO, Maurício. Plano de Ensino FIHC 2023. Brasília: Universidade de Brasília, 2023. Disponícel em: <<https://aprender3.unb.br/pluginfile.php/3096086/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf>>. Acesso em: 03/05/2025.

<br>

## Histórico de Versões 📅


| Versão | Data       | Descrição                                           | Autor(es)      | Revisor(es) |
|:------:|:----------:|:----------------------------------------------------|:---------------|:-----------:|
|  1.0   | 03/05/2025 | Requisitos Funcionais e Criação da página           | Danielle       | -           |
|  1.1   | 03/05/2025 | Requisitos Não-Funcionais e Atualização da página   | Maria Eduarda  | -           |


