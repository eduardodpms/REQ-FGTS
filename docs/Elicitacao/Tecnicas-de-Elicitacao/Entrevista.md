# Entrevista

## Introdução

A entrevista é uma das técnicas mais tradicionais e eficazes de elicitação de requisitos. Nela, os engenheiros de requisitos conduzem conversas com usuários reais ou potenciais para identificar necessidades, expectativas e problemas enfrentados no uso do sistema. A técnica permite capturar tanto requisitos funcionais quanto não funcionais, a partir de relatos concretos e contextuais.

Neste trabalho, foi realizada uma entrevista com um usuário do aplicativo FGTS, buscando compreender sua experiência prática e levantar melhorias possíveis para o sistema.

## Metodologia

A entrevista foi aplicada por **Enzo Emir**, com perguntas organizadas em estrutura de funil (do geral ao específico). As respostas foram registradas manualmente e analisadas posteriormente para a identificação dos requisitos.

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
      <td>Entrevistado (anônimo)</td>
      <td>03/05/2025</td>
      <td>17:30</td>
    </tr>
    <tr>
      <td>Entrevistador: Enzo Emir</td>
      <td>03/05/2025</td>
      <td>17:30</td>
    </tr>
  </tbody>
</table>

</div>

<p style="text-align: center; font-size: 16px;">Fonte: <i>Enzo Emir</i></p>

## Requisitos Elicitados

A seguir, os requisitos elicitados foram organizados em duas categorias: funcionais e não funcionais.

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
      <td><strong>ENx</strong></td>
      <td>Requisito nº x elicitado pela entrevista</td>
    </tr>
  </tbody>
</table>

</div>

<p style="text-align: center; font-size: 16px;">Fonte: <i>Enzo Emir</i></p>

### Requisitos Funcionais

<font size="3"><p style="text-align: center">Tabela 3: Requisitos Funcionais</p></font>

| Código | Requisito Funcional                                                                 | ID    | Implementado |
|:------:|--------------------------------------------------------------------------------------|:-----:|:------------:|
| RF01   | Permitir solicitação de saque por rescisão contratual                              | EN01  | Sim          |
| RF02   | Exibir status comentado e atualizado do processo de saque                          | EN02  | Não          |
| RF03   | Informar claramente as datas previstas para liberação de valores                   | EN03  | Não          |
| RF04   | Oferecer canal de suporte ou chatbot para esclarecer dúvidas                       | EN04  | Não          |



<p style="text-align: center; font-size: 16px;">Fonte: <i>Enzo Emir</i></p>

### Requisitos Não Funcionais

<font size="3"><p style="text-align: center">Tabela 4: Requisitos Não Funcionais</p></font>

| Código  | Requisito Não-Funcional                                                           | ID    | Implementado |
|:-------:|------------------------------------------------------------------------------------|:-----:|:------------:|
| RNF01   | O aplicativo deve manter uma interface simples e de fácil navegação               | EN07  | Sim          |
| RNF02   | O processo de login deve ser simplificado                                         | EN08  | Não          |
| RNF03   | O sistema deve apresentar informações de forma transparente e confiável           | EN09  | Não          |
| RNF04   | Os prazos informados no app devem ser cumpridos fielmente                         | EN10  | Não          |
| RNF05   | O aplicativo deve ser confiável e evitar falhas ou inconsistências nos processos  | EN11  | Parcialmente |

<p style="text-align: center; font-size: 16px;">Fonte: <i>Enzo Emir</i></p>

## Gravação da Elicitação

<p style="text-align: center">
<iframe width="560" height="315" src="https://youtu.be/r9nRinXUWE8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</p>

## Referências

> VAZQUEZ, Carlos Eduardo; SIMÕES, Guilherme Siqueira. *Engenharia de Requisitos: software orientado ao negócio*. Brasport, 2016.  

> SERRANO, Milene; SERRANO, Maurício. *Plano de Ensino FIHC 2023*. Universidade de Brasília. Acesso em: 03/05/2025.

## Histórico de Versões 📅

| Versão | Data       | Descrição                                      | Autor(es)   | Revisor(es) |
|:------:|:----------:|:-----------------------------------------------|:------------|:-----------:|
|  1.0   | 04/05/2025 | Criação da estrutura de entrevista e tabelas   | Enzo Emir   | -           |
