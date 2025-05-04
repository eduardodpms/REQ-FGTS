# Requisitos Elicitados

## Introdução

Essa página tem como objetivo compilar todos os requisitos elicitados com a utilização de técnicas como Entrevista, Introspecção, Observação e Storytelling. Os requisitos serão divididos em duas tabelas, a primeira sendo para requisitos fuincionais e a segunda para requisitos não-funcionais.

### Requisitos funcionais
**Legendas:**

* RFx: Requisito funcional número x
* ENx: Requisito elicitado pela entrevista número x
* INx: Requisito elicitado pela introspecção número x
* OBSx: Requisito elicitado pela observação número x
* STx: Requisito elicitado pelo storytelling número x

<div style="text-align: center">
<p>Tabela 1: Requisitos funcionais</p>
</div>



| Código | Descrição                                                                                                 | Origem |
|--------|-----------------------------------------------------------------------------------------------------------|--------|
| RF01   | Informar claramente as datas previstas para liberação de valores                                         | EN03   |
| RF02   | Oferecer canal de suporte ou chatbot para esclarecer dúvidas                                             | EN04   |
| RF03   | Permitir consulta ao saldo da conta vinculada do FGTS                                                    | EN05   |
| RF04   | “Disponibilizar saque-aniversário”, “Disponibilizar sistemáticas”                                        | EN06, ST013, ST014|
| RF05   | O aplicativo deve permitir a atualização dos dados pessoais do usuário                                   | IS01   |
| RF06   | O sistema deve permitir a consulta de dados pessoais do usuário                                          | IS02   |
| RF07   | “Consultar saldo”, “Exibir extrato por empregador”, “Mostrar saldo disponível”                           | IS04, OB04|
| RF08   | “Acompanhar situação do saque”, “Exibir status atualizado”, “Notificação de andamento”                   | IS05, EN02|
| RF09   | O sistema deve permitir que o usuário cancele um saque solicitado                                        | IS06   |
| RF10   | O aplicativo deve permitir o filtro dos saques por tipo (ex: aniversário, doença, falecimento)           | IS07   |
| RF11   | O aplicativo deve fornecer informações sobre saques bloqueados e os motivos do bloqueio                  | IS08   |
| RF12   | O aplicativo deve exibir informações detalhadas sobre o histórico de movimentações financeiras           | IS09   |
| RF13   | O aplicativo deve permitir o filtro do extrato por data (mês e ano).                                     | IS10   |
| RF14   | “Permitir o cadastro de uma conta bancária”                                                              | IS11, ST05, OB08|
| RF15   | O aplicativo deve permitir que o usuário entre em contato com um assistente via chat                     | IS13   |
| RF16   | O aplicativo deve disponibilizar um campo de busca para facilitar a localização de funcionalidades       | IS14   |
| RF17   | O aplicativo deve conter uma seção de ajuda com orientações sobre o FGTS e PIS/PAESP                     | IS15   |
| RF18   | O aplicativo deve conter uma seção de ajuda com orientações sobre o uso do aplicativo                    | IS16   |
| RF19   | O aplicativo deve permitir a solicitação de ressarcimento de valores do PIS/PASEP                        | IS17   |
| RF20   | Permitir login seguro pelo aplicativo                                                                    | OB01   |
| RF21   | Apresentar resumo de empregadores anteriores com botão para consultar contas vinculadas ao FGTS          | OB02   |
| RF22   | Mostrar nome completo dos empregadores anteriores                                                        | OB05   |
| RF23   | Disponibilizar histórico de saques realizados                                                            | OB06   |
| RF24   | Ter uma aba dedicada à solicitação e acompanhamento de saques                                            | OB07   |
| RF25   | Incluir aba para itens diversos como PIS/PASEP, convocações, sistemática de saque, ajuda, etc.           | OB09   |
| RF26   | Exibir um resumo claro dos tipos de saque disponíveis.                                                   | ST02   |
| RF27   | “Notificar status”, “Notificar saque recebido”, “Enviar notificações”                                    |ST03, ST09, ST015|
| RF28   | Permitir a solicitação de saques                                                                         | EN01, IS03, ST06, OB03|
| RF29   | Disponibilizar um guia interativo para orientar o usuário durante o processo.                            | ST07   |
| RF30   | Permitir o ajuste do tamanho das fontes na interface.                                                    | ST08   |
| RF31   | Permitir a visualização dos dados da conta bancária cadastrada.                                          | ST010  |
| RF32   | Oferecer uma interface de login simples.                                                                 | ST011  |
| RF33   | Disponibilizar uma página para escolha da sistemática de saque.                                          | ST012  |
| RF34   | “Disponibilizar termo de adesão”                                                                         | ST016  |

### Requisitos não-funcionais
**Legendas:**

* RNFx: Requisito não-funcional número x
* ENx: Requisito elicitado pela entrevista número x
* INx: Requisito elicitado pela introspecção número x
* OBSx: Requisito elicitado pela observação número x
* STx: Requisito elicitado pelo storytelling número x

<div style="text-align: center">
<p>Tabela 2: Requisitos não-funcionais</p>
</div>

| Código | Descrição                                                                                                 | Origem |
|--------|-----------------------------------------------------------------------------------------------------------|--------|
| RNF01  | “Interface simples e de fácil navegação”, “menus claros”, “aplicação acessível”                          | EN07, IS20, OB11, ST01, ST04|
| RNF02  | O processo de login deve ser simplificado                                                                | EN08   |
| RNF03  | O sistema deve apresentar informações de forma transparente e confiável                                  | EN09   |
| RNF04  | Os prazos informados no app devem ser cumpridos fielmente                                                | EN10   |
| RNF05  | O aplicativo deve ser confiável e evitar falhas ou inconsistências nos processos                         | EN11   |
| RNF06  | O aplicativo deve funcionar corretamente mesmo com conexão instável                                      | EN12   |
| RNF07  | O aplicativo deve fornecer as mesmas funcionalidades para diferentes plataformas e versões               | IS18   |
| RNF08  | Os menus devem fornecer informações não repetidas                                                        | IS19   |
| RNF09  | O aplicativo deve aplicar princípios de acessibilidade                                                   | IS21   |
| RNF10  | O aplicativo deve estar disponível para outras plataformas, como web                                     | IS22   |
| RNF11  | O aplicativo deve proporcionar segurança de dados pessoais                                               | IS23   |
| RNF12  | O aplicativo deve proporcionar agilidade ao acessar as funcionalidades                                   | IS24   |
| RNF13  | O sistema deve garantir segurança firme com verificação de dados pelo usuário                            | OB10   |
| RNF14  | A aplicação deve exibir notificações ou notícias úteis de forma acessível                                | OB12   |
| RNF15  | As informações devem estar organizadas de forma clara e com terminologia compreensível para o usuário    | OB13   |
| RNF16  | Garantir tempo de resposta de até 1 segundo para o cadastro da conta bancária                            | ST017  |
| RNF17  | Garantir tempo de resposta de até 1 segundo para a solicitação de saque                                  | ST018  |
| RNF18  | Garantir tempo de resposta de até 1 segundo para o processo de login                                     | ST019  |

<br>

## Histórico de Versões 📅

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| :-: | :-: | :-: | :-: | :-: |
| `1.0`  | 04/05 | Criação da página de requisitos elicitados | [Marcelo Makoto](https://github.com/MM4k) | - |
| `1.1`  | 04/05 | Criação da página de requisitos elicitados | [Victor Pontual](https://github.com/VictorPontual) | - |
