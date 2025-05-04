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
| RF01   | Permitir solicitação de saque por rescisão contratual                                                    | EN01   |
| RF02   | Exibir status comentado e atualizado do processo de saque                                                | EN02   |
| RF03   | Informar claramente as datas previstas para liberação de valores                                         | EN03   |
| RF04   | Oferecer canal de suporte ou chatbot para esclarecer dúvidas                                             | EN04   |
| RF05   | Permitir consulta ao saldo da conta vinculada do FGTS                                                    | EN05   |
| RF06   | Disponibilizar funcionalidade acessível para saque-aniversário                                           | EN06   |
| RF07   | O aplicativo deve permitir a atualização dos dados pessoais do usuário                                   | IS01   |
| RF08   | O sistema deve permitir a consulta de dados pessoais do usuário                                          | IS02   |
| RF09   | O aplicativo deve permitir que o usuário realize saques de forma digital                                 | IS03   |
| RF10   | O aplicativo deve exibir o saldo disponível e o extrato de depósitos realizados pelo empregador          | IS04   |
| RF11   | O aplicativo deve permitir ao usuário acompanhar a situação de um pedido de saque                        | IS05   |
| RF12   | O sistema deve permitir que o usuário cancele um saque solicitado                                        | IS06   |
| RF13   | O aplicativo deve permitir o filtro dos saques por tipo (ex: aniversário, doença, falecimento)           | IS07   |
| RF14   | O aplicativo deve fornecer informações sobre saques bloqueados e os motivos do bloqueio                  | IS08   |
| RF15   | O aplicativo deve exibir informações detalhadas sobre o histórico de movimentações financeiras           | IS09   |
| RF16   | O aplicativo deve permitir o filtro do extrato por data (mês e ano).                                     | IS10   |
| RF17   | O aplicativo deve permitir o cadastro de uma conta bancária                                              | IS11   |
| RF18   | O aplicativo deve permitir o cadastro de mais de uma conta bancária de diferentes instituições financeiras | IS12 |
| RF19   | O aplicativo deve permitir que o usuário entre em contato com um assistente via chat                     | IS13   |
| RF20   | O aplicativo deve disponibilizar um campo de busca para facilitar a localização de funcionalidades       | IS14   |
| RF21   | O aplicativo deve conter uma seção de ajuda com orientações sobre o FGTS e PIS/PAESP                     | IS15   |
| RF22   | O aplicativo deve conter uma seção de ajuda com orientações sobre o uso do aplicativo                    | IS16   |
| RF23   | O aplicativo deve permitir a solicitação de ressarcimento de valores do PIS/PASEP                        | IS17   |
| RF24   | Permitir login seguro pelo aplicativo                                                                     | EO01   |
| RF25   | Apresentar resumo de empregadores anteriores com botão para consultar contas vinculadas ao FGTS         | EO02   |
| RF26   | Permitir solicitação de saque com justificativa selecionável                                             | EO03   |
| RF27   | Exibir extrato do FGTS por empregador individual                                                         | EO04   |
| RF28   | Mostrar nome completo dos empregadores anteriores                                                        | EO05   |
| RF29   | Disponibilizar histórico de saques realizados                                                             | EO06   |
| RF30   | Ter uma aba dedicada à solicitação e acompanhamento de saques                                            | EO07   |
| RF31   | Possibilitar configuração de conta bancária para depósito e visualização de termos do FGTS               | EO08   |
| RF32   | Incluir aba para itens diversos como PIS/PASEP, convocações, sistemática de saque, ajuda, etc.           | EO09   |
| RF33   | Páginas com poucos botões para facilitar o acesso.                                                       | ST01   |
| RF34   | Exibir um resumo claro dos tipos de saque disponíveis.                                                   | ST02   |
| RF35   | Enviar notificações sobre o status das solicitações de saque.                                            | ST03   |
| RF36   | Utilizar termos e ícones familiares aos usuários.                                                        | ST04   |
| RF37   | Permitir o cadastro de conta bancária                                                                    | ST05   |
| RF38   | Permitir a solicitação de saques.                                                                        | ST06   |
| RF39   | Disponibilizar um guia interativo para orientar o usuário durante o processo.                            | ST07   |
| RF40   | Permitir o ajuste do tamanho das fontes na interface.                                                    | ST08   |
| RF41   | Enviar notificações sobre o andamento da solicitação de saque.                                           | ST09   |
| RF42   | Permitir a visualização dos dados da conta bancária cadastrada.                                          | ST010  |
| RF43   | Oferecer uma interface de login simples.                                                                 | ST011  |
| RF44   | Disponibilizar uma página para escolha da sistemática de saque.                                          | ST012  |
| RF45   | Incluir a opção de saque no modelo ‘Saque-aniversário’.                                                  | ST013  |
| RF46   | Incluir a opção de saque no modelo ‘Saque-rescisão’.                                                     | ST014  |
| RF47   | Enviar notificação ao usuário quando o saque for recebido.                                               | ST015  |
| RF48   | Disponibilizar termo de adesão.                                                                          | ST016  |

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
| RNF01  | O aplicativo deve manter uma interface simples e de fácil navegação                                      | EN07   |
| RNF02  | O processo de login deve ser simplificado                                                                | EN08   |
| RNF03  | O sistema deve apresentar informações de forma transparente e confiável                                  | EN09   |
| RNF04  | Os prazos informados no app devem ser cumpridos fielmente                                                | EN10   |
| RNF05  | O aplicativo deve ser confiável e evitar falhas ou inconsistências nos processos                         | EN11   |
| RNF06  | O aplicativo deve funcionar corretamente mesmo com conexão instável                                      | EN12   |
| RNF07  | O aplicativo deve fornecer as mesmas funcionalidades para diferentes plataformas e versões               | IS18   |
| RNF08  | Os menus devem fornecer informações não repetidas                                                        | IS19   |
| RNF09  | O aplicativo deve aplicar princípios de usabilidade                                                      | IS20   |
| RNF10  | O aplicativo deve aplicar princípios de acessibilidade                                                   | IS21   |
| RNF11  | O aplicativo deve estar disponível para outras plataformas, como web                                     | IS22   |
| RNF12  | O aplicativo deve proporcionar segurança de dados pessoais                                               | IS23   |
| RNF13  | O aplicativo deve proporcionar agilidade ao acessar as funcionalidades                                   | IS24   |
| RNF14  | O sistema deve garantir segurança firme com verificação de dados pelo usuário                            | EO10   |
| RNF15  | A interface deve ser dividida em abas específicas com funções bem segmentadas                            | EO11   |
| RNF16  | A aplicação deve exibir notificações ou notícias úteis de forma acessível                                | EO12   |
| RNF17  | As informações devem estar organizadas de forma clara e com terminologia compreensível para o usuário    | EO13   |
| RNF18  | Garantir tempo de resposta de até 1 segundo para o cadastro da conta bancária                            | ST017  |
| RNF19  | Garantir tempo de resposta de até 1 segundo para a solicitação de saque                                  | ST018  |
| RNF20  | Garantir tempo de resposta de até 1 segundo para o processo de login                                     | ST019  |

<br>

## Histórico de Versões 📅

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| :-: | :-: | :-: | :-: | :-: |
| `1.0`  | 04/05 | Criação da página de requisitos elicitados | [Marcelo Makoto](https://github.com/MM4k) | - |
| `1.1`  | 04/05 | Criação da página de requisitos elicitados | [Victor Pontual](https://github.com/VictorPontual) | - |
