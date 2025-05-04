# Observação

## Introdução

A observação é uma técnica de elicitação direta que permite captar comportamentos, dificuldades e práticas reais dos usuários em seu contexto de uso. Ao contrário das entrevistas, a observação permite perceber ações implícitas, que muitas vezes não são relatadas verbalmente, e registrar de forma detalhada o fluxo de interação.

Neste trabalho, foi realizada uma **sessão de observação do aplicativo FGTS**, com foco na navegação e nos recursos acessados por um usuário durante o uso espontâneo da aplicação.

## Metodologia

A sessão de observação foi conduzida por Eduardo de Pina, com base em uma gravação de interação da usuária Maria Eduarda utilizando o aplicativo FGTS. A observação foi não participativa, permitindo captar o uso espontâneo do sistema.

Durante a análise da gravação, Victor Pontual foi responsável por registrar os requisitos elicitados a partir do comportamento da usuária. A sessão ocorreu no dia 04 de maio de 2025 e teve duração aproximada de 30 minutos.

<font size="3"><p style="text-align: center">Tabela 1: Detalhes da Observação</p></font>

<div align="center">
  
| Nome da Usuária Observada | Data       | Hora  | Observador      | Anotador de Requisitos | Meio de Observação    |
| ------------------------- | ---------- | ----- | --------------- | ---------------------- | --------------------- |
| Maria Eduarda             | 04/05/2025 | 14:26 | Eduardo de Pina | Victor Pontual         | Gravação de Interação |

</div>

<p style="text-align: center; font-size: 16px;">Fonte: <i>Enzo Emir</i></p>

---

## Requisitos Elicitados

As funcionalidades observadas foram organizadas a seguir como possíveis **Requisitos Funcionais (RF)** ou **Não Funcionais (RNF)**. O código **EOx** indica que a origem é observação.

<font size="3"><p style="text-align: center">Tabela 2: Legenda</p></font>

<div align="center">

| Código | Descrição                               |
| ------ | --------------------------------------- |
| RFx    | Requisito Funcional nº x                |
| RNFx   | Requisito Não-Funcional nº x            |
| EOx    | Requisito nº x elicitado por observação |

</div>

<p style="text-align: center; font-size: 16px;">Fonte: <i>Enzo Emir</i></p>

---

### Requisitos Funcionais

<font size="3"><p style="text-align: center">Tabela 3: Requisitos Funcionais</p></font>

| Código | Requisito Funcional                                                                             | ID   | Implementado |
| ------ | ----------------------------------------------------------------------------------------------- | ---- | :----------: |
| RF05   | Permitir login seguro pelo aplicativo                                                           | EO01 |      Sim     |
| RF06   | Apresentar resumo de empregadores anteriores com botão para consultar contas vinculadas ao FGTS | EO02 |      Sim     |
| RF07   | Permitir solicitação de saque com justificativa selecionável                                    | EO03 |      Sim     |
| RF08   | Exibir extrato do FGTS por empregador individual                                                | EO04 |      Sim     |
| RF09   | Mostrar nome completo dos empregadores anteriores                                               | EO05 |      Sim     |
| RF10   | Disponibilizar histórico de saques realizados                                                   | EO06 |      Sim     |
| RF11   | Ter uma aba dedicada à solicitação e acompanhamento de saques                                   | EO07 |      Sim     |
| RF12   | Possibilitar configuração de conta bancária para depósito e visualização de termos do FGTS      | EO08 |      Sim     |
| RF13   | Incluir aba para itens diversos como PIS/PASEP, convocações, sistemática de saque, ajuda, etc.  | EO09 |      Sim     |

---

### Requisitos Não Funcionais

<font size="3"><p style="text-align: center">Tabela 4: Requisitos Não Funcionais</p></font>

| Código | Requisito Não-Funcional                                                                               | ID   | Implementado |
| ------ | ----------------------------------------------------------------------------------------------------- | ---- | :----------: |
| RNF06  | O sistema deve garantir segurança firme com verificação de dados pelo usuário                         | EO10 |      Sim     |
| RNF07  | A interface deve ser dividida em abas específicas com funções bem segmentadas                         | EO11 |      Sim     |
| RNF08  | A aplicação deve exibir notificações ou notícias úteis de forma acessível                             | EO12 |      Sim     |
| RNF09  | As informações devem estar organizadas de forma clara e com terminologia compreensível para o usuário | EO13 |      Sim     |

---

## Registro Visual da Observação

<p style="text-align: center">Figura 1 – Print da anotação feita durante observação espontânea</p>

<div align="center">
<img src="attachment:file-BwKihfJWGgTVCR9Z3wTwfq" width="500px"/>
</div>

---

## Referências

> VAZQUEZ, Carlos Eduardo; SIMÕES, Guilherme Siqueira. Engenharia de Requisitos: software orientado ao negócio. Brasport, 2016.

---

## Histórico de Versões 📅

| Versão | Data       | Descrição                                      | Autor(es) | Revisor(es)    |
| ------ | ---------- | ---------------------------------------------- | --------- | -------------- |
| 1.0    | 04/05/2025 | Documento de elicitação com base em observação | Victor Pontual Guedes Arruda Nóbrega |  |
