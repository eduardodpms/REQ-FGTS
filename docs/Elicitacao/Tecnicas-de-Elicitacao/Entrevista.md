# Entrevista

## Introdução

A entrevista é uma das técnicas mais tradicionais e eficazes de elicitação de requisitos. Nela, os engenheiros de requisitos conduzem conversas com usuários reais ou potenciais para identificar necessidades, expectativas e problemas enfrentados no uso do sistema. A técnica permite capturar tanto requisitos funcionais quanto não funcionais, a partir de relatos concretos e contextuais.

Neste trabalho, foi realizada uma entrevista com um usuário do aplicativo FGTS, buscando compreender sua experiência prática e levantar melhorias possíveis para o sistema.

## Metodologia

A entrevista foi aplicada por **Enzo Emir, Eduardo de Pina, Davielle Soares, Letícia Arisa e Maria Eduarda**. O objetivo principal desta série de entrevistas foi compreender a experiência, expectativas e dificuldades dos usuários ao interagir com o aplicativo FGTS. As respostas foram registradas manualmente e analisadas posteriormente para a identificação dos requisitos.

Para a coleta de dados, utilizamos entrevistas semiestruturadas, seguindo o modelo funil. Esta abordagem permitiu flexibilidade para explorar as respostas dos participantes, enquanto um roteiro pré-definido garantiu que todos os tópicos essenciais fossem abordados. O modelo funil iniciou com perguntas mais amplas para entender o contexto geral do usuário e gradualmente focou em questões mais específicas sobre o uso e a experiência com o aplicativo. As entrevistas foram realizadas individualmente e gravadas com a autorização dos participantes, para posterior transcrição e análise detalhada.


<font size="3"><p style="text-align: center">Tabela 1: Participantes</p></font>

<div align="center">

<table>
  <thead>
    <tr>
      <th colspan="6"></th>
    </tr>
    <tr>
      <th>Entrevista</th>
      <th>Papel</th>
      <th>Nome</th>
      <th>Data</th>
      <th>Hora</th>
      <th>Local</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="2"><strong>Entrevista 1</strong></td>
      <td>Entrevistado</td>
      <td>Usuário</td>
      <td>03/05/2025</td>
      <td>17:30</td>
      <td>Remota (Discord)</td>
    </tr>
    <tr>
      <td>Entrevistadores</td>
      <td>Enzo Emir</td>
      <td>03/05/2025</td>
      <td>17:30</td>
      <td>Remota (Discord)</td>
    </tr>
    <tr>
      <td rowspan="2"><strong>Entrevista 2</strong></td>
      <td>Entrevistado</td>
      <td>Usuário</td>
      <td>04/05/2025</td>
      <td>15:00</td>
      <td>Remota (Discord)</td>
    </tr>
    <tr>
      <td>Entrevistador</td>
      <td>Enzo Emir e Eduardo de Pina</td>
      <td>04/05/2025</td>
      <td>15:00</td>
      <td>Remota (Discord)</td>
    </tr>
    <tr>
      <td rowspan="2"><strong>Entrevista 3</strong></td>
      <td>Entrevistado</td>
      <td>Davi</td>
      <td>26/06/2025</td>
      <td>9:20</td>
      <td>UnB Campus Gama</td>
    </tr>
    <tr>
      <td>Entrevistadoras</td>
      <td>Danielle Soares, Maria Eduarda e Letícia Arisa</td>
      <td>26/06/2025</td>
      <td>9:20</td>
      <td>UnB Campus Gama</td>
    </tr>
  </tbody>
</table>

</div>


<p style="font-size: 10pt; text-align: center;">Fonte: Autores</p>

</details> <details> <summary><strong> O Porque da Participação</strong></summary>

A participação dos entrevistados Vicente (Entrevistado 1), Nildete (Entrevistado 2) e Davi (Entrevistado 3) foi de importância fundamental para o processo de elicitação de requisitos. Como usuários-chave e especialistas em suas próprias rotinas e desafios diários, eles trouxeram à tona as necessidades reais e as dores do negócio que o sistema precisa resolver. Essa perspectiva direta permitiu não apenas identificar funcionalidades essenciais, mas também compreender os requisitos não funcionais críticos para a usabilidade e aceitação da solução.

O envolvimento deles é vital porque garante que o software seja construído com base em informações precisas e no uso prático, evitando suposições e desenvolvimentos desalinhados com a realidade. Ao validar ideias e fornecer feedback desde as etapas iniciais, Vicente, Nildete e Davi contribuíram diretamente para reduzir retrabalhos futuros e minimizar o risco de entregar um produto que não atenda às expectativas. Em suma, a presença deles na entrevista assegurou que o projeto se mantenha focado em criar uma solução verdadeiramente útil e eficaz para seus futuros usuários.

</details>

## Roteiro da Entrevistas

As entrevistas foram divididas em blocos temáticos para facilitar a coleta de informações sobre diferentes aspectos da experiência do usuário.

### Bloco 1: Perfil do Usuário

1.  Você já utilizou o aplicativo do FGTS? Com que frequência?
2.  Qual foi o principal motivo para usar o app na última vez?
3.  Como você conheceu o aplicativo?

### Bloco 2: Uso e Experiência com o Aplicativo

4.  Como foi sua experiência de login?
5.  Quais funcionalidades do aplicativo você já utilizou (ex: consulta de saldo, saque-aniversário, extrato)?
6.  Como você avalia a facilidade de uso do aplicativo? (Escala: muito difícil a muito fácil)
7.  Houve alguma funcionalidade difícil de encontrar ou usar? Qual?
8.  Você já teve alguma falha ou erro durante o uso? Poderia descrever?

### Bloco 3: Expectativas e Opiniões

9.  O que você mais gosta no aplicativo?
10. O que mais te incomoda ou gostaria que fosse diferente?
11. Se você pudesse sugerir uma melhoria ou nova funcionalidade, qual seria?
12. Você já precisou recorrer a outro meio (ex: site, agência) por não conseguir resolver algo pelo app?

### Encerramento

13. Em uma palavra, como você descreveria sua experiência geral com o aplicativo?
14. Você recomendaria o uso do app para outra pessoa? Por quê?


## Respostas Obtidas

<font size="3"><p style="text-align: center">Tabela 2: Respostas obtidas</p></font>

|Pergunta|Entrevistado 1|Entrevistado 2|Entrevistado 3|
|:---|:---|:---|:---|
|**1. Você já utilizou o aplicativo do FGTS? Com que frequência?**|Utiliza o aplicativo sempre que precisa, desde que começou a trabalhar (2018).|Sim, utilizo sempre que preciso.|Utilizou uma vez.|
|**2. Qual foi o principal motivo para usar o app na última vez?**|Sacar dinheiro do FGTS (saque-aniversário).|Acompanhar o extrato do FGTS e os valores liberados e receber o saque-aniversário.|Para utilizar o saque de aniversário (com o pai dele).|
|**3. Como você conheceu o aplicativo?**|Pelo trabalho (empregador).|Conheci o aplicativo através de notícias e pela mídia quando comecei a trabalhar.|Conheceu a partir do pai dele.|
|**4. Como foi sua experiência de login?**|Teve dificuldade inicial com o login por conta do cadastro, que era "bem burocrático e travava bastante".|Minha experiência de login foi razoável. O aplicativo travou algumas vezes, mas no geral deu certo. Tive que tentar algumas vezes para entrar.|Achou ela tranquila.|
|**5. Quais funcionalidades do aplicativo você já utilizou?**|Usou para solicitar o saque do FGTS e ver extrato.|As funcionalidades que eu mais utilizo são a consulta de saldo, o extrato do FGTS e a funcionalidade de sacar o FGTS quando liberado.|Utilizou o saque-aniversário.|
|**6. Como você avalia a facilidade de uso do aplicativo?**|Considera fácil de usar.|Em uma escala de 1 a 5, sendo 5 muito fácil, eu avaliaria com 4. Não é muito fácil por conta das travadas e porque algumas informações são um pouco escondidas.|Achou ele simples.|
|**7. Houve alguma funcionalidade difícil de encontrar ou usar? Qual?**|Não.|Sim, algumas informações são um pouco difíceis de encontrar, principalmente quando a gente quer detalhes de onde o dinheiro tá indo, o que está sendo debitado. Parece que eles escondem um pouco as informações.|Observou que faltam alguns fatores, mas nada que seja "realmente uma falta de alguma funcionalidade". Achou "coisa".|
|**8. Você já teve alguma falha ou erro durante o uso? Poderia descrever?**|Sim, o aplicativo travava bastante e não cumpria os prazos de saque informados. Teve que ir na agência duas vezes, mesmo com a data do saque definida no app.|Sim, o aplicativo trava bastante quando a internet está ruim. Ele não consegue carregar as informações e tem que fechar o aplicativo e abrir de novo. Ele demora para carregar.|Não teve nenhuma falha.|
|**9. O que você mais gosta no aplicativo?**|A praticidade de não precisar ir a uma agência.|O que eu mais gosto é que ele é prático e rápido. Consigo resolver as coisas de forma fácil pelo celular.|A facilidade dele.|
|**10. O que mais te incomoda ou gostaria que fosse diferente?**|A falta de transparência nos processos e a informação enganosa sobre prazos.|O que mais me incomoda são as travadas e a falta de clareza nas informações, principalmente sobre como o dinheiro está sendo gerenciado e descontado.|Acha que poderia ter biometria (digital), pois falta um pouco de transparência.|
|**11. Se você pudesse sugerir uma melhoria ou nova funcionalidade, qual seria?**|Um canal de suporte eficiente dentro do app ou um assistente virtual que resolva problemas e dê feedback sobre prazos.|Uma tela mais intuitiva para quem não tem muito conhecimento em banco. Gostaria de uma seção de "Perguntas Frequentes" mais completa e uma área de "ajuda" que explicasse onde cada valor está indo.|Além da biometria, gostaria de algum status comentando como é que tá o processo ou uma notificação que indicasse isso.|
|**12. Você já precisou recorrer a outro meio por não conseguir resolver algo pelo app?**|Sim, teve que ir à agência duas vezes porque o dinheiro não caiu na data prometida pelo app.|Sim, precisei ir na agência quando o aplicativo não liberava o saque em uma situação específica, ou quando alguma informação não estava batendo.|Não, conseguiu fazer tudo pelo aplicativo.|
|**13. Em uma palavra, como você descreveria sua experiência geral com o aplicativo?**|Frustrante.|Inconsistente.|Tranquilo.|
|**14. Você recomendaria o uso do app para outra pessoa? Por quê?**|Não, pelo fato de não cumprir o prometido em relação aos prazos.|Sim, mas com ressalvas. Recomendo pela praticidade em situações básicas, mas alertaria sobre as travadas e a falta de clareza em certas informações, indicando que pode ser necessário ir à agência em casos mais complexos.|Sim, porque "é bem mais fácil utilizar o aplicativo do que numa agência, por exemplo".|

<p style="font-size: 10pt; text-align: center;">Fonte: Autores</p>


## Análise das Respostas

## Análise das Respostas – Entrevista sobre o Aplicativo FGTS

Esta análise consolida os requisitos funcionais e não funcionais, bem como os problemas identificados, com base nas três entrevistas realizadas com usuários do aplicativo FGTS.

### Requisitos Funcionais Sugeridos

Os usuários identificaram e reforçaram a necessidade das seguintes funcionalidades no aplicativo FGTS:

* **Consulta de Saque por Rescisão Contratual:** A necessidade dessa funcionalidade é confirmada, visto que usuários, como o entrevistado 3, utilizaram o aplicativo para fins de saque.
* **Login Acessível, com Redução de Complexidade:** A experiência com o login apresenta variações. Enquanto um relato apontou dificuldades, outro descreveu sua experiência como *"tranquila"*. Isso sugere que, a complexidade possa ser um ponto de atenção para alguns, portanto é sempre válido buscar a otimização contínua para garantir acessibilidade a todos.
* **Sistema de Notificações Claras e Confiáveis:** Houve uma forte demanda por transparência no andamento dos processos. Isso evidencia que o aplicativo atual não oferece clareza suficiente sobre as etapas e datas, gerando incerteza para o usuário.
* **Cumprimento de Prazos Informados no Aplicativo:** Observou-se uma divergência nas experiências. Enquanto um usuário teve que recorrer a meios externos devido ao não cumprimento de prazos prometidos pelo aplicativo, outro usuário precisou ir a outros canais. Isso indica que a questão dos prazos pode ser inconsistente ou refletir em mais um ponto de otimização para garantir acessibilidade a todos.
* **Canal de Suporte para Dúvidas ou Inconsistências:** A falta de transparência nos processos, destacada pela necessidade de status e notificações, pode ser mitigada com a oferta de explicações automáticas ou canais de ajuda dentro do próprio aplicativo, evitando que o usuário precise buscar informações fora.
* **Consulta de Saldo do FGTS:** Fundamental para que os usuários acompanhem suas contas, esta funcionalidade é essencial e deve ser mantida de forma otimizada.
* **Saque-Aniversário com Acesso Facilitado:** Os usuários utilizaram essa funcionalidade, o que reforça a sua relevância e a necessidade de que seja **facilmente localizável e intuitiva** dentro do aplicativo.

### Problemas Identificados

Os principais problemas identificados no uso do aplicativo FGTS são:

* **Falta de Transparência nos Processos:** Este é um problema recorrente. Usuários expressam a dificuldade em entender o que está acontecendo "no *backend*" do processo. A ausência de um **status claro** ou **notificações** sobre o andamento das solicitações é uma lacuna que afeta a experiência do usuário.
* **Descompasso entre o que o App Promete (Datas) e o que Acontece na Prática:** O enfrentamento dessa dificuldade pelos usuários indica uma perda de confiança no aplicativo quando as informações apresentadas não correspondem à realidade.


### Requisitos Não Funcionais (Qualidade)

A avaliação da qualidade do aplicativo FGTS, com base nas entrevistas, aponta para os seguintes requisitos não funcionais:

* **Usabilidade:** Este é um **ponto forte** do aplicativo. Os usuários o descrevem como **"simples"** e sua experiência geral como **"tranquila"**, recomendando o uso por ser bem mais fácil utilizar o aplicativo do que ir em uma agência. É crucial manter e aprimorar essa facilidade de uso.
* **Confiabilidade:** A necessidade de **status e notificações** para acompanhar processos destaca a importância de melhorar a **confiabilidade da comunicação** dentro do aplicativo, mesmo que as funcionalidades operem sem falhas técnicas. O usuário precisa confiar que as informações sobre o andamento e prazos são precisas.
* **Acessibilidade:** O entrevistado 3 sugeriu a inclusão de **biometria (digital)** para aprimorar a segurança e a rapidez do acesso ao aplicativo, tornando o processo de login mais prático e acessível à todos.
* **Desempenho em Condições de Rede Instável:** Um dos usuários anteriores atribuiu problemas de uso à conexão com a internet, indicando a necessidade de o aplicativo funcionar bem mesmo com variações de rede.

Essa análise final oferece uma visão abrangente sobre a experiência dos usuários entrevistados com o aplicativo FGTS, destacando áreas onde o aplicativo já se destaca e onde melhorias são necessárias para otimizar a satisfação do usuário.


## Requisitos Elicitados

A seguir, os requisitos elicitados foram organizados em duas categorias: funcionais e não funcionais.

<font size="3"><p style="text-align: center">Tabela 3: Legenda</p></font>

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

<p style="font-size: 10pt; text-align: center;">Fonte: Autores</p>


### Requisitos Funcionais

#### Tabela 4: Requisitos Funcionais

<a name="EN_RF"></a>

| Código | Requisito Funcional                                                                 | ID    | Implementado |
|:------:|--------------------------------------------------------------------------------------|:-----:|:------------:|
| RF01   | O aplicativo deve permitir solicitação de saque por rescisão contratual                              | EN01  | Sim          |
| RF02   | O aplicativo deve exibir status comentado e atualizado do processo de saque                          | EN02  | Não          |
| RF03   | O aplicativo deve informar claramente as datas previstas para liberação de valores                   | EN03  | Não          |
| RF04   | O aplicativo deve oferecer canal de suporte ou chatbot para esclarecer dúvidas                       | EN04  | Não          |
| RF05   | O aplicativo deve permitir consulta ao saldo da conta vinculada do FGTS                              | EN05  | Sim          |
| RF06   | O aplicativo deve disponibilizar funcionalidade acessível para saque-aniversário                     | EN06  | Sim          |

<p style="font-size: 10pt; text-align: center;">Fonte: Autores</p>

---

### Requisitos Não Funcionais

#### Tabela 5: Requisitos Não Funcionais

<a name="EN_RNF"></a>

| Código  | Requisito Não-Funcional                                                           | ID    | Implementado |
|:-------:|------------------------------------------------------------------------------------|:-----:|:------------:|
| RNF01   | O aplicativo deve manter uma interface simples e de fácil navegação               | EN07  | Sim          |
| RNF02   | O processo de login deve ser simplificado                                         | EN08  | Não          |
| RNF03   | O sistema deve apresentar informações de forma transparente e confiável           | EN09  | Não          |
| RNF04   | Os prazos informados no app devem ser cumpridos fielmente                         | EN10  | Não          |
| RNF05   | O aplicativo deve ser confiável e evitar falhas ou inconsistências nos processos  | EN11  | Parcialmente |
| RNF06   | O aplicativo deve funcionar corretamente mesmo com conexão instável               | EN12  | Não          |

<p style="font-size: 10pt; text-align: center;">Fonte: Autores</p>


## Gravação da Elicitação

<p style="text-align: center">
<iframe width="560" height="315" src="https://youtube.com/embed/r9nRinXUWE8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</p>

<p style="text-align: center">
<iframe width="560" height="315" src="https://youtube.com/embed/_trr3zNFNu8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</p>

<p style="text-align: center">
<iframe width="560" height="315" src="https://youtube.com/embed/VC4grOHBQJ8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</p>


<!--<a href="../../../assets/Entrevista.pdf" target="_blank">📄 Ver documento completo</a>-->

## Bibliografia

> 1.</a> VAZQUEZ, Carlos Eduardo; SIMÕES, Guilherme Siqueira. *Engenharia de Requisitos: software orientado ao negócio*. Brasport, 2016.  

> 2.</a> SERRANO, Milene; SERRANO, Maurício. Plano de Ensino FIHC 2023. Brasília: Universidade de Brasília, 2023. Disponícel em: <<https://aprender3.unb.br/pluginfile.php/3096086/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf>>. Acesso em: 03/05/2025.

## Histórico de Versões 📅

| Versão | Data       | Descrição                                      | Autor(es)   | Revisor(es) |
|:------:|:----------:|:-----------------------------------------------|:------------|:-----------:|
|  `1.0`   | 04/05/2025 | Criação da estrutura de entrevista e tabelas   | [Enzo Emir](https://github.com/EnzoEmir)   | [Marcelo Makoto](https://github.com/MM4k) |
|  `1.1`   | 04/05/2025 | Criação da estrutura de entrevista e tabelas   | [Enzo Emir](https://github.com/EnzoEmir), [Eduardo de Pina](https://github.com/eduardodpms)  | [Marcelo Makoto](https://github.com/MM4k)           |
|  `1.2`   | 04/05/2025 | Correção dos links dos vídeos   | [Marcelo Makoto](https://github.com/MM4k)   | [Maria Eduarda](https://github.com/dudaa28) |
| `1.3`  | 06/05/2025 | Correção da formatação dos requisitos elicitados. | [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa) | [Enzo Emir](https://github.com/EnzoEmir) |
| `1.4` | 17/05/2025 | Adição de âncoras | [Danielle Soares](https://github.com/danielle-soaress) | [Eduardo de Pina](https://github.com/eduardodpms) |
| `1.5`  | 17/05/2025 | Corrigindo bug nas tabelas | [Danielle Soares](https://github.com/danielle-soaress) | [Eduardo de Pina](https://github.com/eduardodpms) |
| `1.6`  | 21/06/2025 | Refinamento na Página | [Maria Eduarda](https://github.com/dudaa28) | [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa) |
| `1.7`  | 28/06/2025 | Elicitação Presencial e Atualizção do Texto | [Danielle Soares](https://github.com/danielle-soaress) | -- |
| `1.8`  | 28/06/2025 | Atualizando tabela | [Danielle Soares](https://github.com/danielle-soaress) | -- |
