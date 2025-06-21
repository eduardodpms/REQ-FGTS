# Entrevista

## Introdução

A entrevista é uma das técnicas mais tradicionais e eficazes de elicitação de requisitos. Nela, os engenheiros de requisitos conduzem conversas com usuários reais ou potenciais para identificar necessidades, expectativas e problemas enfrentados no uso do sistema. A técnica permite capturar tanto requisitos funcionais quanto não funcionais, a partir de relatos concretos e contextuais.

Neste trabalho, foi realizada uma entrevista com um usuário do aplicativo FGTS, buscando compreender sua experiência prática e levantar melhorias possíveis para o sistema.

## Metodologia

A entrevista foi aplicada por **Enzo Emir e Eduardo de Pina**, com perguntas organizadas em estrutura de funil (do geral ao específico). As respostas foram registradas manualmente e analisadas posteriormente para a identificação dos requisitos.

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
      <td>Entrevistado 1: Vicente</td>
      <td>03/05/2025</td>
      <td>17:30</td>
    </tr>
    <tr>
      <td>Entrevistador: Enzo Emir</td>
      <td>03/05/2025</td>
      <td>17:30</td>
    </tr>
    <tr>
      <td>Entrevistado 2: Nildete da Silva</td>
      <td>04/05/2025</td>
      <td>15:00</td>
    </tr>
    <tr>
      <td>Entrevistador: Enzo Emir e Eduardo de Pina</td>
      <td>04/05/2025</td>
      <td>15:00</td>
    </tr>
  </tbody>
</table>

</div>


<p style="text-align: center; font-size: 16px;">Fonte: <i>Enzo Emir e Eduardo de Pina</i></p>

</details> <details> <summary><strong> O Porque da Participação</strong></summary>

A participação do entrevistado 1 (Vicente) e da entrevistada 2 (Nildete), ambos usuários-chave, foi de importância fundamental para o processo de elicitação de requisitos. Como especialistas em suas próprias rotinas e desafios diários, eles trouxeram à tona as necessidades reais e as dores do negócio que o sistema precisa resolver. Essa perspectiva direta permitiu não apenas identificar funcionalidades essenciais, mas também compreender os requisitos não funcionais críticos para a usabilidade e aceitação da solução.

O envolvimento deles é vital porque garante que o software seja construído com base em informações precisas e no uso prático, evitando suposições e desenvolvimentos desalinhados com a realidade. Ao validar ideias e fornecer feedback desde as etapas iniciais, Vicente e Nildete contribuíram diretamente para reduzir retrabalhos futuros e minimizar o risco de entregar um produto que não atenda às expectativas. Em suma, a presença deles na entrevista assegurou que o projeto se mantenha focado em criar uma solução verdadeiramente útil e eficaz para seus futuros usuários.

</details>

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

#### Tabela 3: Requisitos Funcionais

<a name="EN_RF"></a>

| Código | Requisito Funcional                                                                 | ID    | Implementado |
|:------:|--------------------------------------------------------------------------------------|:-----:|:------------:|
| RF01   | O aplicativo deve permitir solicitação de saque por rescisão contratual                              | EN01  | Sim          |
| RF02   | O aplicativo deve exibir status comentado e atualizado do processo de saque                          | EN02  | Não          |
| RF03   | O aplicativo deve informar claramente as datas previstas para liberação de valores                   | EN03  | Não          |
| RF04   | O aplicativo deve oferecer canal de suporte ou chatbot para esclarecer dúvidas                       | EN04  | Não          |
| RF05   | O aplicativo deve permitir consulta ao saldo da conta vinculada do FGTS                              | EN05  | Sim          |
| RF06   | O aplicativo deve disponibilizar funcionalidade acessível para saque-aniversário                     | EN06  | Sim          |

**Fonte:** *Enzo Emir e Eduardo de Pina*

---

### Requisitos Não Funcionais

#### Tabela 4: Requisitos Não Funcionais

<a name="EN_RNF"></a>

| Código  | Requisito Não-Funcional                                                           | ID    | Implementado |
|:-------:|------------------------------------------------------------------------------------|:-----:|:------------:|
| RNF01   | O aplicativo deve manter uma interface simples e de fácil navegação               | EN07  | Sim          |
| RNF02   | O processo de login deve ser simplificado                                         | EN08  | Não          |
| RNF03   | O sistema deve apresentar informações de forma transparente e confiável           | EN09  | Não          |
| RNF04   | Os prazos informados no app devem ser cumpridos fielmente                         | EN10  | Não          |
| RNF05   | O aplicativo deve ser confiável e evitar falhas ou inconsistências nos processos  | EN11  | Parcialmente |
| RNF06   | O aplicativo deve funcionar corretamente mesmo com conexão instável               | EN12  | Não          |

**Fonte:** *Enzo Emir e Eduardo de Pina*


## Gravação da Elicitação

<p style="text-align: center">
<iframe width="560" height="315" src="https://youtube.com/embed/r9nRinXUWE8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</p>
<p style="text-align: center">
<iframe width="560" height="315" src="https://youtube.com/embed/_trr3zNFNu8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</p>

<a href="../../../assets/Entrevista.pdf" target="_blank">📄 Ver documento completo</a>

## Bibliografia

> 1.</a> VAZQUEZ, Carlos Eduardo; SIMÕES, Guilherme Siqueira. *Engenharia de Requisitos: software orientado ao negócio*. Brasport, 2016.  

> 2.</a> SERRANO, Milene; SERRANO, Maurício. Plano de Ensino FIHC 2023. Brasília: Universidade de Brasília, 2023. Disponícel em: <<https://aprender3.unb.br/pluginfile.php/3096086/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf>>. Acesso em: 03/05/2025.

## Histórico de Versões 📅

| Versão | Data       | Descrição                                      | Autor(es)   | Revisor(es) |
|:------:|:----------:|:-----------------------------------------------|:------------|:-----------:|
|  `1.0`   | 04/05/2025 | Criação da estrutura de entrevista e tabelas   | [Enzo Emir](https://github.com/EnzoEmir)   | [Marcelo Makoto](https://github.com/MM4k) |
|  `1.1`   | 04/05/2025 | Criação da estrutura de entrevista e tabelas   | [Enzo Emir](https://github.com/EnzoEmir), [Eduardo de Pina](https://github.com/eduardodpms)  | [Marcelo Makoto](https://github.com/MM4k)           |
|  `1.2`   | 04/05/2025 | Correção dos links dos vídeos   | [Marcelo Makoto](https://github.com/MM4k)   | [Maria](https://github.com/dudaa28) |
| `1.3`  | 06/05/2025 | Correção da formatação dos requisitos elicitados. | [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa) | [Enzo Emir](https://github.com/EnzoEmir) |
| `1.4` | 17/05/2025 | Adição de âncoras | [Danielle Soares](https://github.com/danielle-soaress) | [Eduardo de Pina](https://github.com/eduardodpms) |
| `1.5`  | 17/05/2025 | Corrigindo bug nas tabelas | [Danielle Soares](https://github.com/danielle-soaress) | [Eduardo de Pina](https://github.com/eduardodpms) |
| `1.6`  | 21/06/2025 | Refinamento na Página | [Maria Eduarda](https://github.com/dudaa28) | - |
