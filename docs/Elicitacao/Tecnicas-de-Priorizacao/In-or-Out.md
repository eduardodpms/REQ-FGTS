# In or Out

## Introdução

A técnica de priorização **In or Out** é uma abordagem binária e objetiva, onde os requisitos são classificados como **essenciais (IN)** ou **dispensáveis (OUT)**. Ela é especialmente útil quando o tempo é limitado ou quando é necessário tomar decisões rápidas em conjunto com os stakeholders. Essa classificação direta ajuda a evitar ambiguidades e garante que apenas os requisitos cruciais sejam priorizados na próxima iteração de desenvolvimento.

## Metodologia

Durante a aplicação da técnica **In or Out**, os membros da equipe de requisitos analisaram cada funcionalidade proposta com base nos seguintes critérios:

1. **Valor essencial para o usuário final:** o requisito é crítico para a experiência do usuário?
2. **Obrigatoriedade legal ou contratual:** o requisito é exigido por regulação ou contrato?
3. **Impacto direto na funcionalidade central do sistema:** sua ausência compromete o uso do sistema?

Caso a resposta fosse afirmativa para qualquer um dos pontos acima, o requisito foi classificado como **IN**. Caso contrário, foi considerado **OUT**.

Requisitos classificados como **OUT** foram justificados com base em sua não essencialidade ou por se tratarem de melhorias de experiência, que podem ser postergadas.

## Requisitos priorizados

**Legendas:**

* RFx: Requisito Funcional número x
* RNFx: Requisito Não Funcional número x
* ENx: Requisito elicitado pela entrevista número x
* INx: Requisito elicitado pela introspecção número x
* OBSx: Requisito elicitado pela observação número x
* STx: Requisito elicitado pelo storytelling número x

### Tabela 1: Requisitos Funcionais

| Código | Descrição                                                                                                 | Origem                     | Prioridade | Justificativa                               |
|--------|-----------------------------------------------------------------------------------------------------------|----------------------------|------------|----------------------------------------------|
| RF01   | Informar claramente as datas previstas para liberação de valores                                          | EN03                       | OUT        | É bom saber mas não é necessário.            |
| RF02   | Oferecer canal de suporte ou chatbot para esclarecer dúvidas                                              | EN04                       | OUT        | É bom mas não é necessário.                  |
| RF03   | Permitir consulta ao saldo da conta vinculada do FGTS                                                     | EN05                       | IN         |                                              |
| RF04   | “Disponibilizar saque-aniversário”, “Disponibilizar sistemáticas”                                         | EN06, ST013, ST014         | IN         |                                              |
| RF05   | O aplicativo deve permitir a atualização dos dados pessoais do usuário                                    | IS01                       | IN         |                                              |
| RF06   | O sistema deve permitir a consulta de dados pessoais do usuário                                           | IS02                       | IN         |                                              |
| RF07   | “Consultar saldo”, “Exibir extrato por empregador”, “Mostrar saldo disponível”                            | IS04, OB04                 | IN         |                                              |
| RF08   | “Acompanhar situação do saque”, “Exibir status atualizado”, “Notificação de andamento”                    | IS05, EN02                 | OUT        | É bom saber mas não é necessário.            |
| RF09   | O sistema deve permitir que o usuário cancele um saque solicitado                                         | IS06                       | IN         |                                              |
| RF10   | O aplicativo deve permitir o filtro dos saques por tipo (ex: aniversário, doença, falecimento)            | IS07                       | OUT        | É qualidade de vida                          |
| RF11   | O aplicativo deve fornecer informações sobre saques bloqueados e os motivos do bloqueio                   | IS08                       | IN         |                                              |
| RF12   | O aplicativo deve exibir informações detalhadas sobre o histórico de movimentações financeiras            | IS09                       | OUT        | É qualidade de vida                          |
| RF13   | O aplicativo deve permitir o filtro do extrato por data (mês e ano)                                       | IS10                       | OUT        | É qualidade de vida                          |
| RF14   | “Permitir o cadastro de uma conta bancária”                                                               | IS11, ST05, OB08           | IN         |                                              |
| RF15   | O aplicativo deve permitir que o usuário entre em contato com um assistente via chat                      | IS13                       | OUT        | É qualidade de vida                          |
| RF16   | O aplicativo deve disponibilizar um campo de busca para facilitar a localização de funcionalidades        | IS14                       | OUT        | É qualidade de vida                          |
| RF17   | O aplicativo deve conter uma seção de ajuda com orientações sobre o FGTS e PIS/PAESP                      | IS15                       | IN         |                                              |
| RF18   | O aplicativo deve conter uma seção de ajuda com orientações sobre o uso do aplicativo                     | IS16                       | OUT        | É qualidade de vida                          |
| RF19   | O aplicativo deve permitir a solicitação de ressarcimento de valores do PIS/PASEP                         | IS17                       | IN         |                                              |
| RF20   | Permitir login seguro pelo aplicativo                                                                     | OB01                       | IN         |                                              |
| RF21   | Apresentar resumo de empregadores anteriores com botão para consultar contas vinculadas ao FGTS          | OB02                       | OUT        | É bom mas não é necessário.                  |
| RF22   | Mostrar nome completo dos empregadores anteriores                                                        | OB05                       | OUT        | É bom mas não é necessário.                  |
| RF23   | Disponibilizar histórico de saques realizados                                                            | OB06                       | OUT        | É qualidade de vida                          |
| RF24   | Ter uma aba dedicada à solicitação e acompanhamento de saques                                            | OB07                       | OUT        | É qualidade de vida                          |
| RF25   | Incluir aba para itens diversos como PIS/PASEP, convocações, sistemática de saque, ajuda, etc.            | OB09                       | OUT        | É qualidade de vida                          |
| RF26   | Exibir um resumo claro dos tipos de saque disponíveis                                                     | ST02                       | IN         |                                              |
| RF27   | “Notificar status”, “Notificar saque recebido”, “Enviar notificações”                                    | ST03, ST09, ST015          | OUT        | É qualidade de vida                          |
| RF28   | Permitir a solicitação de saques                                                                         | EN01, IS03, ST06, OB03     | IN         |                                              |
| RF29   | Disponibilizar um guia interativo para orientar o usuário durante o processo                             | ST07                       | OUT        | É qualidade de vida                          |
| RF30   | Permitir o ajuste do tamanho das fontes na interface                                                     | ST08                       | OUT        | É qualidade de vida                          |
| RF31   | Permitir a visualização dos dados da conta bancária cadastrada                                          | ST010                      | IN         |                                              |
| RF32   | Oferecer uma interface de login simples                                                                  | ST011                      | OUT        | É qualidade de vida                          |
| RF33   | Disponibilizar uma página para escolha da sistemática de saque                                           | ST012                      | IN         |                                              |
| RF34   | “Disponibilizar termo de adesão”                                                                         | ST016                      | IN         |                                              |


### Tabela 2: Requisitos Não Funcionais


| Código  | Descrição                                                                                               | Origem                             | Prioridade | Justificativa                             |
|---------|---------------------------------------------------------------------------------------------------------|------------------------------------|------------|--------------------------------------------|
| RNF01   | “Interface simples e de fácil navegação”, “menus claros”, “aplicação acessível”                        | EN07, IS20, OB11, ST01, ST04       | OUT        |                                            |
| RNF02   | O processo de login deve ser simplificado                                                              | EN08                               | OUT        |                                            |
| RNF03   | O sistema deve apresentar informações de forma transparente e confiável                                | EN09                               | IN         |                                            |
| RNF04   | Os prazos informados no app devem ser cumpridos fielmente                                              | EN10                               | IN         |                                            |
| RNF05   | O aplicativo deve ser confiável e evitar falhas ou inconsistências nos processos                       | EN11                               | IN         |                                            |
| RNF06   | O aplicativo deve funcionar corretamente mesmo com conexão instável                                    | EN12                               | IN         |                                            |
| RNF07   | O aplicativo deve fornecer as mesmas funcionalidades para diferentes plataformas e versões             | IS18                               | IN         |                                            |
| RNF08   | Os menus devem fornecer informações não repetidas                                                      | IS19                               | OUT        | É uma boa prática.                         |
| RNF09   | O aplicativo deve aplicar princípios de acessibilidade                                                 | IS21                               | OUT        | É qualidade de vida                        |
| RNF10   | O aplicativo deve estar disponível para outras plataformas, como web                                   | IS22                               | OUT        | É bom mas não é necessário.                |
| RNF11   | O aplicativo deve proporcionar segurança de dados pessoais                                            | IS23                               | IN         |                                            |
| RNF12   | O aplicativo deve proporcionar agilidade ao acessar as funcionalidades                                 | IS24                               | IN         |                                            |
| RNF13   | O sistema deve garantir segurança firme com verificação de dados pelo usuário                          | OB10                               | IN         |                                            |
| RNF14   | A aplicação deve exibir notificações ou notícias úteis de forma acessível                              | OB12                               | OUT        | É qualidade de vida                        |
| RNF15   | As informações devem estar organizadas de forma clara e com terminologia compreensível para o usuário | OB13                               | IN         |                                            |
| RNF16   | Garantir tempo de resposta de até 1 segundo para o cadastro da conta bancária                          | ST017                              | OUT        | É bom mas não é necessário.                |
| RNF17   | Garantir tempo de resposta de até 1 segundo para a solicitação de saque                                | ST018                              | OUT        | É bom mas não é necessário.                |
| RNF18   | Garantir tempo de resposta de até 1 segundo para o processo de login                                  | ST019                              | OUT        | É bom mas não é necessário.                |

## Gravação

<p style="text-align: center">
<iframe width="560" height="315" src="https://youtube.com/embed/k4DjZhRIiK4?si=SREsx3YvMQTnJs0S" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</p>



## Referências

> 1.</a> WIEGERS, Karl; BEATTY, Joy. *Software Requirements*. 3. ed. Redmond: Microsoft Press, 2013. Cap. 16, p. 319.

## Histórico de Versões 🗓️

| Versão | Data       | Descrição                        | Autor(es)                      | Revisor(es) |
| ------ | ---------- | -------------------------------- | ------------------------------ | ----------- |
| 1.0    | 04/05/2025 | Criação da priorização In or Out | [Victor Pontual](https://github.com/VictorPontual), [Enzo Emir](https://github.com/EnzoEmir) | [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa)         |
