# Brainstorming

## Introdução

O ***brainstorming*** é uma técnica colaborativa amplamente utilizada na engenharia de requisitos para elicitar informações de forma criativa e participativa. Durante uma sessão de *brainstorming*, os participantes são incentivados a compartilhar livremente suas ideias, sem julgamentos, promovendo um ambiente aberto à inovação. Essa dinâmica favorece a identificação de requisitos já existentes e a descoberta de novas necessidades, a partir da troca de experiências e percepções entre os envolvidos no processo. <a href="ref1">1</a>

Neste projeto, o *brainstorming* foi aplicado com o objetivo de levantar requisitos funcionais para o aplicativo do FGTS, permitindo uma visão mais completa e centrada nas necessidades dos usuários. Para enriquecer ainda mais esse processo, foi utilizada a técnica do “computador mágico”, proposta por Cooper (1999), que convida os participantes a imaginar o sistema sem qualquer limitação tecnológica. Isso possibilita uma distinção mais clara entre tarefas (ações intermediárias) e objetivos (condições finais), contribuindo para uma definição mais precisa e eficaz das funcionalidades do sistema.


## Metodologia

A sessão de *brainstorming* para a elicitação de requisitos foi conduzida de forma remota, utilizando a plataforma Discord para comunicação síncrona entre os participantes do grupo. O encontro teve início às 23h10, momento em que todos os integrantes se reuniram com o propósito de colaborar ativamente no levantamento dos requisitos funcionais para o aplicativo do FGTS.

Como apoio visual e organizacional, foi utilizado um arquivo compartilhado na ferramenta Figma, onde foi estruturado um quadro com áreas destinadas a cada participante. Nesses espaços, os membros do grupo registraram suas ideias individualmente, por meio de post-its virtuais, durante um período de 8 minutos cronometrado. Encerrada essa etapa, cada integrante apresentou suas sugestões ao grupo, promovendo uma discussão conjunta sobre os requisitos levantados. Ao final da atividade, os participantes analisaram em conjunto quais requisitos já estavam implementados, quais ainda não haviam sido implementados e quais se destacavam por sua relevância e potencial impacto para o sistema. Essa abordagem garantiu a participação equitativa de todos e favoreceu uma análise crítica e colaborativa das funcionalidades do aplicativo.

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
      <td> Danielle Soares </td>
      <td> 30/05/2025 </td>
      <td> 23:10 </td>
      <td> Discord </td>
    </tr>
    <tr>
      <td> Eduardo de Pina </td>
      <td> 30/05/2025 </td>
      <td> 23:10 </td>
      <td> Discord </td>
    </tr>
    <tr>
      <td> Enzo Emir </td>
      <td> 30/05/2025 </td>
      <td> 23:10   </td>
      <td> Discord </td>
    </tr>
    <tr>
      <td> Leticia Arisa </td>
      <td> 30/05/2025 </td>
      <td> 23:10 </td>
      <td> Discord </td>
    </tr>
    <tr>
      <td> Marcelo Makoto </td>
      <td> 30/05/2025 </td>
      <td> 23:10 </td>
      <td> Discord </td>
    </tr>
    <tr>
      <td> Maria Eduarda </td>
      <td> 30/05/2025 </td>
      <td> 23:10 </td>
      <td> Discord </td>
    </tr>
    <tr>
      <td> Victor Pontual </td>
      <td> 30/05/2025 </td>
      <td> 23:10 </td>
      <td> Discord </td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fonte: [Danielle Soares](https://github.com/danielle-soaress) </p></font>

## Resultados

A seguir, a Figura 1 apresenta o quadro construído durante a sessão de brainstorming já preenchido com as ideias propostas por cada integrante do grupo. 

<font size="3"><p style="text-align: center">Figura 1: Brainstorming</p></font>

<a href="../../../assets/brainstorming/brainstorming.pdf" target="_blank">📄 Ver documento completo</a>

<iframe src="../../../assets/brainstorming/brainstorming.pdf" width="100%" height="450px">
    Este navegador não suporta PDFs. Faça o download <a href="../../../assets/brainstorming/brainstorming.pdf">aqui</a>.
</iframe>

<font size="2"><p style="text-align: center">Fonte: [Danielle Soares](https://github.com/danielle-soaress) </p></font>

## Requisitos Elicitados


Após a sessão de brainstorming, foi possível fazer a elicitação dos requisitos funcionais listados na Tabela 3 e os requisitos não funcionais listados na Tabela 4.

Legenda das Tabelas 3 e 4:

- RFx: Requisito Funcional nºx
- BSx: Requisito nºx elicitado pelo Brainstorming.

<font size="3"><p style="text-align: center">Tabela 2: Requisitos Funcionais Elicitados</p></font>

<a name="BS_RF"></a>

| Código | Requisito Funcional | ID   | Implementado |
| :----: | ------------------- | :--: | :----------: |
| RF01  | O sistema deve disponibilizar canal de denúncia sobre depósitos irregulares | BS01 |      Não        |
| RF02  | O sistema deve disponibilizar um Agendamento de atendimento presencial      | BS02 |       Não       |
| RF03  | O aplicativo deve possibilitar o envio de documentos digitalizados          | BS03 |        Não      |
| RF04  | O aplicativo deve permitir a exportação do extrato em formato PDF           | BS04 |       Não       |
| RF05  | O aplicativo deve oferecer suporte à leitura em voz para conteúdos textuais | BS05 |       Não       |
| RF06  | O sistema deve apresentar uma área com informações sobre direitos trabalhistas e FGTS | BS06 |   Sim    |
| RF07  | O aplicativo do FGTS deve permitir que o usuário faça login com reconhecimento facial | BS07 |    Não  |
| RF08  | O aplicativo do FGTS deve permitir opções de alto contraste no aplicativo   | BS08 |       Não       |
| RF09  | O aplicativo do FGTS deve permitir que o usuário configure as notificações do aplicativo | BS09 |  Sim   |
| RF10  | O aplicativo deve permitir que o usuário realize um agendamento de saque    | BS10 |       Não       |
| RF11  | O aplicativo do FGTS deve permitir que o usuário visualize o extrato de maneira detalhada | BS11 | Sim  |
| RF12  | O aplicativo deve conter uma seção de ajuda com FAQ e caixa de pesquisa     | BS12 |      Sim        |
| RF13  | O sistema deve conter um guia interativo e explicativo para usuários iniciantes | BS13 |      Sim     |
| RF14  | O aplicativo deve conter um chat com um bot para eventuais dúvidas do sistema do FGTS | BS14 |   Sim  |
| RF15  | O sistema deve permitir consulta de saque por empresa empregadora           | BS15 |      Não        |
| RF16  | O sistema deve disponibilizar um acompanhamento em tempo real de solicitações de saques | BS16 |  Sim   |
| RF17  | O sistema deve permitir notificação personalizada sobre direitos e prazos   | BS17 |     Não         |
| RF18  | O usuário deve conseguir realizar o login por meio de biometria             | BS18 |        Não      |
| RF19  | O Sistema deve permitir o visualização do status atual de um saque          | BS19 |      Sim   |
| RF20  | O Sistema deve disponibilizar um extrato detalhado com todas as movimentações finenceiras da conta do FGTS | BS20 | Sim |
| RF21  | O Sistema deve disponibilizar a execução de saques-aniversário              | BS21 |       Sim       |
| RF22  | O Sistema deve disponibilizar a execução de saques-recisão                  | BS22 |       Sim       |

<font size="2"><p style="text-align: center">Fonte: [Danielle Soares](https://github.com/danielle-soaress) </p></font>

## Gravação da Elicitação

<p style="text-align: center">
<iframe width="560" height="315" src="https://www.youtube.com/embed/7E00fdLN2S4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</p>

## Referências Bibliográficas

> <a id="ref1"> 1.</a> VAZQUEZ, Carlos Eduardo; SIMÕES, Guilherme Siqueira. *Engenharia de Requisitos: software orientado ao negócio*. Brasport, 2016.  

## Histórico de Versões 📅

| Versão | Data       | Descrição                                      | Autor(es)   | Revisor(es) |
|:------:|:----------:|:-----------------------------------------------|:------------|:-----------:|
|  `1.0`   | 30/05/2025 | Introdução, Metodologia, Participantes e Requisitos elicitados  | [Danielle Soares](https://github.com/danielle-soaress)   | [Enzo Emir](https://github.com/EnzoEmir) |
|  `1.1`   | 30/05/2025 | Vídeo da elicitação  | [Danielle Soares](https://github.com/danielle-soaress)   | [Maria Eduarda](https://github.com/dudaa28) |
|  `1.2`   | 30/05/2025 | Vídeo da elicitação  | [Danielle Soares](https://github.com/danielle-soaress)   | [Maria Eduarda](https://github.com/dudaa28) |
| `1.3`  | 21/06/2025 | Refinamento na Página | [Maria Eduarda](https://github.com/dudaa28) | [Victor Pontual](https://github.com/VictorPontual) |

