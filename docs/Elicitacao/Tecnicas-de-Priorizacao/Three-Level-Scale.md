# Three-Level Scale

## Introdução

A técnica de priorização Three-Level Scale é uma abordagem comum para organizar requisitos em três categorias: alta, média e baixa prioridade. Essa classificação facilita a tomada de decisão e o planejamento de entregas, mas depende de um entendimento comum entre as partes interessadas sobre o que cada nível representa. Essa técnica é útil por sua simplicidade e clareza, além de exigir menos esforço do que métodos mais complexos de priorização.

## Metodologia

A aplicação da técnica Three-Level Scale utiliza dois critérios principais para avaliar cada requisito:

1. Importância: O quanto o requisito contribui para os objetivos de negócio.

2. Urgência: A necessidade de implementar o requisito no curto prazo.

A partir da combinação desses critérios, os requisitos foram classificados da seguinte forma:

1. Alta Prioridade: Requisitos importantes e urgentes, geralmente exigidos pelo cliente na próxima entrega ou por obrigações contratuais. Devem ser tratados com prioridade máxima.

2. Média Prioridade: Requisitos importantes mas não urgentes, que os clientes precisam, mas podem aguardar uma versão futura.

3. Baixa Prioridade: Requisitos nem importantes nem urgentes, que podem ser adiados ou até eliminados.

4. Descartáveis: Requisitos que parecem urgentes por pressões políticas, mas não são importantes de fato. Esses devem ser evitados, pois não agregam valor ao produto.

Dessa maneira, os requisitos podem ser priorizados de maneira relativamente fácil e rápido, tornando a técnica de priorização Three-Level Scale eficiente.

## Requisitos priorizados
**Legendas:**

* RFx: Requisito Funcional número x
* RNFx: Requisito Não Funcional número x
* ENx: Requisito elicitado pela entrevista número x
* INx: Requisito elicitado pela introspecção número x
* OBSx: Requisito elicitado pela observação número x
* STx: Requisito elicitado pelo storytelling número x

<div style="text-align: center">
<p>Tabela 1: Requisitos Funcionais</p>
</div>

| Código | Descrição                                                                                                 | Origem | Priorização |
|--------|-----------------------------------------------------------------------------------------------------------|--------|-------------|
| RF01   | Informar claramente as datas previstas para liberação de valores                                         | EN03   |      média        |
| RF02   | Oferecer canal de suporte ou chatbot para esclarecer dúvidas                                             | EN04   | baixa           |
| RF03   | Permitir consulta ao saldo da conta vinculada do FGTS                                                    | EN05   | média             |
| RF04   | “Disponibilizar saque-aniversário”, “Disponibilizar sistemáticas”                                        | EN06, ST013, ST014| alta             |
| RF05   | O aplicativo deve permitir a atualização dos dados pessoais do usuário                                   | IS01   |  alta            |
| RF06   | O sistema deve permitir a consulta de dados pessoais do usuário                                          | IS02   | alta              |
| RF07   | “Consultar saldo”, “Exibir extrato por empregador”, “Mostrar saldo disponível”                           | IS04, OB04|  alta            |
| RF08   | “Acompanhar situação do saque”, “Exibir status atualizado”, “Notificação de andamento”                   | IS05, EN02| média             |
| RF09   | O sistema deve permitir que o usuário cancele um saque solicitado                                        | IS06   |  alta            |
| RF10   | O aplicativo deve permitir o filtro dos saques por tipo (ex: aniversário, doença, falecimento)           | IS07   |  baixa           |
| RF11   | O aplicativo deve fornecer informações sobre saques bloqueados e os motivos do bloqueio                  | IS08   |  alta            |
| RF12   | O aplicativo deve exibir informações detalhadas sobre o histórico de movimentações financeiras           | IS09   |  média            |
| RF13   | O aplicativo deve permitir o filtro do extrato por data (mês e ano).                                     | IS10   | baixa             |
| RF14   | “Permitir o cadastro de uma conta bancária”                                                              | IS11, ST05, OB08| alta             |
| RF15   | O aplicativo deve permitir que o usuário entre em contato com um assistente via chat                     | IS13   | baixo             |
| RF16   | O aplicativo deve disponibilizar um campo de busca para facilitar a localização de funcionalidades       | IS14   |baixa              |
| RF17   | O aplicativo deve conter uma seção de ajuda com orientações sobre o FGTS e PIS/PAESP                     | IS15   |média              |
| RF18   | O aplicativo deve conter uma seção de ajuda com orientações sobre o uso do aplicativo                    | IS16   |baixa              |
| RF19   | O aplicativo deve permitir a solicitação de ressarcimento de valores do PIS/PASEP                        | IS17   |alta              |
| RF20   | Permitir login seguro pelo aplicativo                                                                    | OB01   |alta            |
| RF21   | Apresentar resumo de empregadores anteriores com botão para consultar contas vinculadas ao FGTS          | OB02   |média              |
| RF22   | Mostrar nome completo dos empregadores anteriores                                                        | OB05   |média            |
| RF23   | Disponibilizar histórico de saques realizados                                                            | OB06   |média              |
| RF24   | Ter uma aba dedicada à solicitação e acompanhamento de saques                                            | OB07   |baixa              |
| RF25   | Incluir aba para itens diversos como PIS/PASEP, convocações, sistemática de saque, ajuda, etc.           | OB09   |baixa             |
| RF26   | Exibir um resumo claro dos tipos de saque disponíveis.                                                   | ST02   |alta              |
| RF27   | “Notificar status”, “Notificar saque recebido”, “Enviar notificações”                                    |ST03, ST09, ST015| baixa             |
| RF28   | Permitir a solicitação de saques                                                                         | EN01, IS03, ST06, OB03|alta              |
| RF29   | Disponibilizar um guia interativo para orientar o usuário durante o processo.                            | ST07   |baixa              |
| RF30   | Permitir o ajuste do tamanho das fontes na interface.                                                    | ST08   |baixa              |
| RF31   | Permitir a visualização dos dados da conta bancária cadastrada.                                          | ST010  |média             |
| RF32   | Oferecer uma interface de login simples.                                                                 | ST011  |baixa              |
| RF33   | Disponibilizar uma página para escolha da sistemática de saque.                                          | ST012  |alta              |
| RF34   | “Disponibilizar termo de adesão”                                                                         | ST016  |alta              |

<div style="text-align: center">
<p>Tabela 2: Requisitos Não Funcionais</p>
</div>

| Código | Descrição                                                                                                 | Origem | Prioridade |
|--------|-----------------------------------------------------------------------------------------------------------|--------|------------|
| RNF01  | “Interface simples e de fácil navegação”, “menus claros”, “aplicação acessível”                          | EN07, IS20, OB11, ST01, ST04|baixa|
| RNF02  | O processo de login deve ser simplificado                                                                | EN08   |baixa|
| RNF03  | O sistema deve apresentar informações de forma transparente e confiável                                  | EN09   |alta|
| RNF04  | Os prazos informados no app devem ser cumpridos fielmente                                                | EN10   |alta|
| RNF05  | O aplicativo deve ser confiável e evitar falhas ou inconsistências nos processos                         | EN11   |alta|
| RNF06  | O aplicativo deve funcionar corretamente mesmo com conexão instável                                      | EN12   |alta|
| RNF07  | O aplicativo deve fornecer as mesmas funcionalidades para diferentes plataformas e versões               | IS18   |alta|
| RNF08  | Os menus devem fornecer informações não repetidas                                                        | IS19   |média|
| RNF09  | O aplicativo deve aplicar princípios de acessibilidade                                                   | IS21   |baixa|
| RNF10  | O aplicativo deve estar disponível para outras plataformas, como web                                     | IS22   |baixa|
| RNF11  | O aplicativo deve proporcionar segurança de dados pessoais                                               | IS23   |alta|
| RNF12  | O aplicativo deve proporcionar agilidade ao acessar as funcionalidades                                   | IS24   |média|
| RNF13  | O sistema deve garantir segurança firme com verificação de dados pelo usuário                            | OB10   |alta|
| RNF14  | A aplicação deve exibir notificações ou notícias úteis de forma acessível                                | OB12   |baixa|
| RNF15  | As informações devem estar organizadas de forma clara e com terminologia compreensível para o usuário    | OB13   |média|
| RNF16  | Garantir tempo de resposta de até 1 segundo para o cadastro da conta bancária                            | ST017  |média|
| RNF17  | Garantir tempo de resposta de até 1 segundo para a solicitação de saque                                  | ST018  |média|
| RNF18  | Garantir tempo de resposta de até 1 segundo para o processo de login                                     | ST019  |média|

## Bibliografia

> <a id="REF1" href="#anchor_1">1.</a> WIEGERS, Karl; BEATTY, Joy. Software Requirements. 3rd ed. Redmond: Microsoft Press, 2013. Cap. 16, p. 319.

<br>

## Histórico de Versões 📅

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| :-: | :-: | :-: | :-: | :-: |
| `1.0`  | 04/05 | Criação das seções de Introdução, Metodologia e Requisitos priorizados | [Marcelo Makoto](https://github.com/MM4k) | - |
| `1.1`  | 04/05 | Correções de texto | [Marcelo Makoto](https://github.com/MM4k) | - |
