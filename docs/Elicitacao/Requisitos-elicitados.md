# Requisitos Elicitados

## Introdução

Essa página tem como objetivo compilar todos os requisitos elicitados com a utilização de técnicas como Entrevista, Introspecção, Observação e Storytelling. Os requisitos serão divididos em duas tabelas, a primeira sendo para requisitos fuincionais e a segunda para requisitos não-funcionais.

## Participantes

<font size="3"><p style="text-align: center">Tabela 1: Participantes</p></font>

<div align="center">
<table>
  <thead>
    <tr>
      <th>Nome</th>
      <th>Data</th>
      <th>Hora</th>
      <th>Local</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="https://github.com/danielle-soaress">Danielle Soares</a></td>
      <td>04/05/2025</td>
      <td>16:20</td>
      <td>Discord</td>
    </tr>
    <tr>
      <td><a href="https://github.com/eduardodpms">Eduardo de Pina</a></td>
      <td>04/05/2025</td>
      <td>16:20</td>
      <td>Discord</td>
    </tr>
    <tr>
      <td><a href="https://github.com/EnzoEmir">Enzo Emir</a></td>
      <td>04/05/2025</td>
      <td>16:20</td>
      <td>Discord</td>
    </tr>
    <tr>
      <td><a href="https://github.com/Leticia-Arisa-K-Higa">Leticia Arisa</a></td>
      <td>04/05/2025</td>
      <td>16:20</td>
      <td>Discord</td>
    </tr>
    <tr>
      <td><a href="https://github.com/MM4k">Marcelo Makoto</a></td>
      <td>04/05/2025</td>
      <td>16:20</td>
      <td>Discord</td>
    </tr>
    <tr>
      <td><a href="https://github.com/dudaa28">Maria Eduarda</span></a></td>
      <td>04/05/2025</td>
      <td>16:20</td>
      <td>Discord</td>
    </tr>
    <tr>
      <td><a href="https://github.com/VictorPontual">Victor Pontual</a></td>
      <td>04/05/2025</td>
      <td>16:20</td>
      <td>Discord</td>
    </tr>
  </tbody>
</table>
</div>


<font size="2"><p style="text-align: center">Fonte: [Maria Eduarda](https://github.com/dudaa28) </p></font>

### <a name="RF"></a> Requisitos funcionais
**Legendas:**

* RFx: Requisito funcional número x
* ENx: Requisito elicitado pela entrevista número x
* INx: Requisito elicitado pela introspecção número x
* OBSx: Requisito elicitado pela observação número x
* STx: Requisito elicitado pelo storytelling número x

<div style="text-align: center">
<p>Tabela 1: Requisitos funcionais</p>
</div>

| Código | Versão | Descrição | Origem |Testabilidade |
|--------| ------ |-----------|--------|---------------|
| RF01 | 1.0 | O aplicativo deve informar claramente as datas previstas para liberação de valores | [EN03](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Entrevista/#EN_RF) |Testável |
| RF02 | 1.0 | O aplicativo deve oferecer canal de suporte ou chatbot para esclarecer dúvidas | [EN04](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Entrevista/#EN_RF) |Testável |
| RF03 | 1.0 | O aplicativo deve permitir consulta ao saldo da conta vinculada do FGTS | [EN05](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Entrevista/#EN_RF) |Testável |
| RF04 | 1.0 | O aplicativo deve disponibilizar saque Saque-Aniversário | [ST014](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#ST_RF) |Testável |
| RF05 | 1.0 | O aplicativo deve permitir a atualização dos dados pessoais do usuário | [IS01](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#IS_RF) |Testável |
| RF06 | 1.0 | O sistema deve permitir a consulta de dados pessoais do usuário | [IS02](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#IS_RF) |Testável |
| RF07 | 1.0 | O aplicativo deve permitir que o usuário visualize o extrato detalhado de movimentações financeiras | [IS04](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#IS_RF) |Testável |
| RF08 | 1.0 | O aplicativo deve exibir os status atualizado do saque | [IS05](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#IS_RF) |Testável |
| RF09 | 1.0 | O sistema deve permitir que o usuário cancele um saque solicitado | [IS06](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#IS_RF) |Testável |
| RF10 | 1.0 | O aplicativo deve permitir o filtro dos saques por tipo (ex: aniversário, doença, falecimento) | [IS07](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#IS_RF) |Testável |
| RF11 | 1.0 | O aplicativo deve fornecer informações sobre saques bloqueados. | [IS08](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#IS_RF) |Testável |
| RF12 | 1.0 | O aplicativo deve exibir informações detalhadas sobre o histórico de movimentações financeiras | [IS09](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#IS_RF) |Testável |
| RF13 | 1.0 | O aplicativo deve permitir o filtro do extrato por data (mês e ano) | [IS10](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#IS_RF) |Testável |
| RF14 | 1.0 | O aplicativo deve permitir o cadastro de uma conta bancária | [IS11](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#IS_RF), [ST05](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#ST_RF), [OB08](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Observacao/#OB_RF) |Testável |
| RF15 | 1.0 | O aplicativo deve permitir que o usuário entre em contato com um assistente via chat | [IS13](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#IS_RF) |Testável |
| RF16 | 1.0 | O aplicativo deve disponibilizar um campo de busca para facilitar a localização de funcionalidades | [IS14](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#IS_RF) |Testável |
| RF17 | 1.0 | O aplicativo deve conter uma seção de ajuda com orientações sobre o FGTS e PIS/PAESP | [IS15](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#IS_RF) |Testável |
| RF18 | 1.0 | O aplicativo deve conter uma seção de ajuda com orientações sobre o uso do aplicativo | [IS16](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#IS_RF) |Testável |
| RF19 | 1.0 | O aplicativo deve permitir a solicitação de ressarcimento de valores do PIS/PASEP | [IS17](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#IS_RF) |Testável |
| RF20 | 1.0 | O aplicativo deve permitir login seguro pelo aplicativo | [OB01](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Observacao/#OB_RF) |Testável |
| RF21 | 1.0 | O aplicativo deve apresentar resumo de empregadores anteriores com botão para consultar contas vinculadas ao FGTS | [OB02](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Observacao/#OB_RF) |Testável |
| RF22 | 1.0 | O aplicativo deve mostrar o nome completo dos empregadores anteriores | [OB05](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Observacao/#OB_RF) |Testável |
| RF23 | 1.0 | O aplicativo deve disponibilizar histórico de saques realizados | [OB06](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Observacao/#OB_RF) |Testável |
| RF24 | 1.0 | O aplicativo deve ter uma aba dedicada à solicitação e acompanhamento de saques | [OB07](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Observacao/#OB_RF) |Testável |
| RF25 | 1.0 | O aplicativo deve incluir aba para itens diversos como PIS/PASEP, convocações, sistemática de saque, ajuda, etc. | [OB09](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Observacao/#OB_RF) |Testável |
| RF26 | 1.0 | O aplicativo deve exibir um resumo claro dos tipos de saque disponíveis. | [ST02](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#ST_RF) |Não Testável |
| RF27 | 1.0 | O aplicativo deve enviar notificação sobre o andamento do saque.  | [ST03](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#ST_RF), [ST09](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#ST_RF), [ST015](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#ST_RF) |Testável |
| RF28 | 1.0 | O aplicativo deve permitir a solicitação de saques | [EN01](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Entrevista/#EN_RF), [IS03](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#IS_RF), [ST06](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#ST_RF), [OB03](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Observacao/#OB_RF) |Testável |
| RF29 | 1.0 | O aplicativo deve disponibilizar um guia interativo para orientar o usuário durante o processo. | [ST07](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#ST_RF) |Testável |
| RF30 | 1.0 | O aplicativo deve permitir o ajuste do tamanho das fontes na interface. | [ST08](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#ST_RF) |Testável |
| RF31 | 1.0 | O aplicativo deve permitir a visualização dos dados da conta bancária cadastrada. | [ST010](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#ST_RF) |Testável |
| RF32 | 1.0 | O aplicativo deve oferecer uma interface de login simples. | [ST011](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#ST_RF) |Não Testável |
| RF33 | 1.0 | O aplicativo deve disponibilizar uma página para escolha da sistemática de saque. | [ST012](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#ST_RF) |Testável |
| RF34 | 1.0 | O aplicativo deve exibir o termo de adesão ao usuário no primeiro acesso ao aplicativo | [ST016](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#ST_RF) |Testável |
| RF35 | 1.0 | O aplicativo deve permitir o cadastro de mais de uma conta bancária de diferentes instituições financeiras | [IS12](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#IS_RF) |Testável |
| RF36 | 1.0 | O aplicativo deve permitir que o usuário solicite o saque da rescisão  | [ST014](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#requisitos-elicitados), [ST013](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#ST_RF) |Testável |
| RF37 | 1.0 | O aplicativo deve permitir que o usuário consulte seu saldo disponível para saque.| [OB04](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Observacao/#OB_RF) |Testável |
| RF38 | 1.0 | O aplicativo deve notificar o usuário sobre o status do saque solicitado | [IS05](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#IS_RF) |Testável |
| RF39 | 1.0 | O aplicativo deve possuir comentários detalhados sobre cada status do saque.| [EN02](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Entrevista/#EN_RF)  |Não Testável |
| RF40 | 1.0 | O aplicativo deve enviar notificação ao usuário quando o saque for recebido. | [ST015](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#requisitos-elicitados) |Testável |
| RF41 |  1.0 | O aplicativo deve possibilitar o envio de documentos digitalizados (PDF, imagem) para comprovação de situações específicas de saque (ex: doença grave, aposentadoria). | [BS03](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Brainstorming/#BS_RF)|Testável |
| RF42 | 1.0 | O aplicativo deve permitir o agendamento de saque futuro. | [BS10](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Brainstorming/#BS_RF) |Testável |

<p style="text-align: center; font-size: 10pt;">Fonte: <a href="https://github.com/VictorPontual">Victor Pontual</a> e <a href="https://github.com/EnzoEmir">Enzo Emir</a></p>

___
### <a name="RNF"></a> Requisitos não-funcionais
**Legendas:**

* RNFx: Requisito não-funcional número x
* ENx: Requisito elicitado pela entrevista número x
* INx: Requisito elicitado pela introspecção número x
* OBSx: Requisito elicitado pela observação número x
* STx: Requisito elicitado pelo storytelling número x

<div style="text-align: center">
<p>Tabela 2: Requisitos não-funcionais</p>
</div>

| Código | Versão | Descrição | Origem | Testabilidade |
|------|----------|-----------|--------|---------------|
| RNF01  | 1.0 | A aplicação deve apresentar uma interface simples, com elementos visuais organizados e linguagem acessível, facilitando a navegação. | [EN07](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Entrevista/#EN_RNF), [IS20](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#IS_RNF), [OB11](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Observacao/#OB_RNF), [ST01](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#ST_RNF), [ST04](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#ST_RNF) | Não Testável |
| RNF02  | 1.0 | O processo de login deve ser simplificado                                                             | [EN08](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Entrevista/#EN_RNF)| Não Testável |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| RNF03  | 1.0 | O sistema deve apresentar informações de forma transparente e confiável                               | [EN09](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Entrevista/#EN_RNF)| Não Testável |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| RNF04  | 1.0 | Os prazos informados no app devem ser cumpridos fielmente                                             | [EN10](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Entrevista/#EN_RNF)| Testável |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| RNF05  | 1.0 | O aplicativo deve ser confiável e evitar falhas ou inconsistências nos processos                      | [EN11](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Entrevista/#EN_RNF)| Testável |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| RNF06  | 1.0 | O aplicativo deve funcionar corretamente mesmo com conexão instável                                   | [EN12](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Entrevista/#EN_RNF)| Testável |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| RNF07  | 1.0 | O aplicativo deve fornecer as mesmas funcionalidades para diferentes plataformas e versões            | [IS18](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#IS_RNF)| Testável |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| RNF08  | 1.0 | Os menus devem fornecer informações não repetidas                                                     | [IS19](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#IS_RNF)| Testável |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| RNF09  | 1.0 | O aplicativo deve aplicar princípios de acessibilidade                                                | [IS21](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#IS_RNF)| Testável |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| RNF10  | 1.0 | O aplicativo deve estar disponível para outras plataformas, como web                                  | [IS22](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#IS_RNF)| Testável |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| RNF11  | 1.0 | O aplicativo deve proporcionar segurança de dados pessoais                                            | [IS23](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#IS_RNF)| Testável |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| RNF12  | 1.0 | O aplicativo deve proporcionar agilidade ao acessar as funcionalidades                                | [IS24](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#IS_RNF)| Não Testável |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| RNF13  | 1.0 | O sistema deve garantir segurança firme com verificação de dados pelo usuário                         | [OB10](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Observacao/#OB_RNF)| Testável |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| RNF14  | 1.0 | A aplicação deve exibir notificações ou notícias úteis de forma acessível                             | [OB12](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Observacao/#OB_RNF)| Não Testável |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| RNF15  | 1.0 | As informações devem estar organizadas de forma clara e com terminologia compreensível para o usuário | [OB13](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Observacao/#OB_RNF)| Não Testável |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| RNF16  | 1.0 | Garantir tempo de resposta de até 1 segundo para o cadastro da conta bancária                         | [ST017](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#ST_RNF)| Testável |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| RNF17  | 1.0 | Garantir tempo de resposta de até 1 segundo para a solicitação de saque                               | [ST018](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#ST_RNF)| Testável |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| RNF18  | 1.0 | Garantir tempo de resposta de até 1 segundo para o processo de login                                  | [ST019](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Storytelling/#ST_RNF)| Testável |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| RNF19  | 1.0 | Saque-aniversário deve atender princípios de acessibilidade                                           | [EN06](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Entrevista/#EN_RF)| Testável |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| RNF20  | 1.0 | Saque-rescisão deve atender princípios de acessibilidade                                              | [EN06](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Entrevista/#EN_RF)| Testável |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| RNF21  | 1.0 | Os menus devem ser autoexplicativos, com estrutura hierárquica lógica e nomenclatura padronizada      | [IS19](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#IS_RNF), [OB11](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Observacao/#OB_RNF)| Não Testável |                                                                                                                                                                                                                                                                                                                                                              |
| RNF22  | 1.0 | A aplicação deve estar em conformidade com diretrizes de acessibilidade, garantindo acesso a pessoas com deficiência visual, auditiva ou motora | [IS20](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#IS_RNF)| Testável |                                                         |

<p style="text-align: center; font-size: 10pt;">Fonte: <a href="https://github.com/VictorPontual">Victor Pontual</a> e <a href="https://github.com/EnzoEmir">Enzo Emir</a></p>

## Bibliografia

> <a id="REF1" href="#anchor_1">1.</a> SOARES, Danielle; et al. Requisitos de Software - 2025.1-FGTS. Disponível em: https://requisitos-de-software.github.io/2025.1-FGTS/. Acesso em: 24 abr. 2025.


<br>

## Histórico de Versões 📅

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| :-: | :-: | :-: | :-: | :-: |
| `1.0`  | 04/05/2025 | Criação da página de requisitos elicitados | [Marcelo Makoto](https://github.com/MM4k) | [Maria Eduarda](https://github.com/dudaa28) |
| `1.1`  | 04/05/2025 | Adição das tabelas de requisitos elicitados | [Victor Pontual](https://github.com/VictorPontual) | [Maria Eduarda](https://github.com/dudaa28) |
| `1.2`  | 17/05/2025 | Adição do requisito RF35 | [Danielle Soares](https://github.com/danielle-soaress) | [Eduardo de Pina](https://github.com/eduardodpms) |
| `1.3`  | 17/05/2025 | Adição de links de rastreabilidade aos requisitos | [Danielle Soares](https://github.com/danielle-soaress) | [Eduardo de Pina](https://github.com/eduardodpms) |
| `1.4`  | 30/05/2025 | Destruncamento de requisitos | [Victor Pontual](https://github.com/VictorPontual) [Danielle Soares](https://github.com/danielle-soaress) [Enzo Emir](https://github.com/EnzoEmir) | [Marcelo Makoto](https://github.com/MM4k) |
| `1.5`  | 30/05/2025 | Elicitação dos requisitos 41 e 42 | [Danielle Soares](https://github.com/danielle-soaress) | [Eduardo de Pina](https://github.com/eduardodpms) |
| `1.6`  | 30/05/2025 | Aprimoramento das descrições dos requisitos | [Danielle Soares](https://github.com/danielle-soaress) |  [Enzo Emir](https://github.com/EnzoEmir) |
| `1.7`  | 31/05/2025 | Atualizando links de rastreabilidade | [Danielle Soares](https://github.com/danielle-soaress) | [Enzo Emir](https://github.com/EnzoEmir) |
| `1.8`  | 20/06/2025 | Adicionando Testabilidade dos requisitos | [Enzo Emir](https://github.com/EnzoEmir) | [Marcelo Makoto](https://github.com/MM4k) |
| `1.9`  | 21/06/2025 | Refinamento na Página | [Maria Eduarda](https://github.com/dudaa28) | [Marcelo Makoto](https://github.com/MM4k) |
| `2.0`  | 21/06/2025 | Adição de versões dos requisitos | [Marcelo Makoto](https://github.com/MM4k) | [Enzo Emir](https://github.com/EnzoEmir) |
| `2.1` | 22/06/2025 | Adição de revisores | [Victor Pontual](https://github.com/VictorPontual) | [Marcelo Makoto](https://github.com/MM4k) |