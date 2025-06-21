# Especificação Suplementar - Aplicativo FGTS

## Introdução

Este documento apresenta a **Especificação Suplementar** do aplicativo FGTS, com o objetivo de complementar os requisitos funcionais previamente definidos. Aqui são detalhados os **requisitos não funcionais**, **restrições**, **regras de negócio** e **padrões técnicos** que devem ser observados durante o desenvolvimento do sistema. 

O conteúdo está estruturado conforme o modelo **FURPS+**, utilizado para organizar e classificar os requisitos de qualidade de software.

---

## Metodologia

A elaboração da especificação suplementar seguiu os seguintes passos:

1. **Levantamento dos Requisitos Não Funcionais** por meio da análise dos objetivos do sistema e padrões de qualidade esperados.
2. **Classificação dos Requisitos** segundo o modelo FURPS+, que contempla: Funcionalidade, Usabilidade, Confiabilidade, Desempenho, Suporte e extensões (como restrições e interfaces).
3. **Preenchimento de Tabelas** com os requisitos descritos de forma clara, justificando sua inclusão e indicando prioridade e status.
4. **Consulta à bibliografia técnica**, garantindo conformidade com boas práticas de Engenharia de Software.

<br>

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
      <td> Danielle Soares </td>
      <td> 18/05/2025 </td>
      <td> 23:13 </td>
    </tr>
    <tr>
      <td> Eduardo de Pina </td>
      <td> 18/05/2025 </td>
      <td> 23:13 </td>
    </tr>
    <tr>
      <td> Enzo Emir </td>
      <td> 18/05/2025 </td>
      <td> 23:13 </td>
    </tr>
    <tr>
      <td> Leticia Arisa </td>
      <td> 18/05/2025 </td>
      <td> 23:13 </td>
    </tr>
    <tr>
      <td> Marcelo Makoto </td>
      <td> 18/05/2025 </td>
      <td> 23:13 </td>
    </tr>
    <tr>
      <td> Maria Eduarda </td>
      <td> 18/05/2025 </td>
      <td> 23:13 </td>
    </tr>
    <tr>
      <td> Victor Pontual </td>
      <td> 18/05/2025 </td>
      <td> 23:13 </td>
    </tr>
  </tbody>
</table>

</div>

<font size="2"><p style="text-align: center">Fonte: [Enzo Emir](https://github.com/EnzoEmir)</p></font>

---

## Modelo

Este documento segue o modelo **FURPS+**, organizando os requisitos de software em categorias:

- **F (Functionality):** Funcionalidades e regras de negócio
- **U (Usability):** Usabilidade e acessibilidade
- **R (Reliability):** Confiabilidade e disponibilidade
- **P (Performance):** Desempenho e tempo de resposta
- **S (Supportability):** Manutenibilidade e portabilidade
- **+ (Extensões):** Interfaces, restrições técnicas e legais

---
## <a name="RNF"></a>Requisitos Não Funcionais

| Código  | Categoria        | Requisito Não Funcional                                                                 | Descrição                                                                                 | Justificativa                                                                              | Prioridade | Status       |
|---------|------------------|-----------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------|------------|--------------|
| [IS18](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#IS_RF)   | Compatibilidade  | O aplicativo deve fornecer as mesmas funcionalidades para diferentes plataformas.      | Funcionalidades disponíveis em Android (>= 8.0), iOS (>= 12) e navegadores modernos.      | Garantir a experiência uniforme para todos os usuários, independentemente da plataforma.  | Alta       | Não          |
| [EN08](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Entrevista/#EN_RF)   | Usabilidade      | O processo de login deve ser simplificado.                                              | O acesso deve ser direto, com menos etapas e possível uso de biometria.                  | Reduzir barreiras de acesso ao app e aumentar a adesão dos usuários.                      | Alta       | Não          |
| [EN09](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Entrevista/#EN_RF)   | Confiabilidade   | O sistema deve apresentar informações de forma transparente e confiável.                | As informações exibidas devem ser claras, completas e sempre atualizadas.                 | Evita desconfiança e erros por parte do usuário.                                           | Alta       | Não          |
| [EN10](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Entrevista/#EN_RF)   | Confiabilidade   | Os prazos informados no app devem ser cumpridos fielmente.                              | O sistema deve garantir a entrega dos serviços dentro dos prazos prometidos.             | Atrasos comprometem a credibilidade do sistema.                                            | Alta       | Não          |
| [EN11](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Entrevista/#EN_RF)   | Confiabilidade   | O aplicativo deve ser confiável e evitar falhas ou inconsistências nos processos.       | As funcionalidades devem operar corretamente e de forma previsível.                      | Minimizar erros e retrabalhos que afetam a experiência do usuário.                        | Alta       | Parcialmente |
| [EN12](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Entrevista/#EN_RF)   | Desempenho       | O aplicativo deve funcionar corretamente mesmo com conexão instável.                    | O sistema deve oferecer suporte a operações offline ou tolerância à perda temporária de conexão, garantindo tempo de resposta inferior a 200 ms.   | Muitos usuários acessam o app em locais com conectividade limitada.                       | Média      | Não          |
| [IS19](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#IS_RF)   | Usabilidade      | Os menus devem fornecer informações não repetidas.                                      | O conteúdo dos menus deve ser organizado e único.                                         | Melhora a navegação e evita confusão do usuário.                                           | Média      | Não          |
| [IS20](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#IS_RF)   | Usabilidade      | O aplicativo deve aplicar princípios de usabilidade.                                    | Interfaces devem ser intuitivas, consistentes e centradas no usuário.                    | Garante maior facilidade de uso e aprendizado do sistema.                                 | Alta       | Não          |
| [IS21](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#IS_RF)   | Acessibilidade   | O aplicativo deve aplicar princípios de acessibilidade.                                 | Deve seguir a WCAG 2.1 nível AA, com suporte a leitores de tela e contraste adequado.    | Promove inclusão digital e atende exigências legais.                                       | Alta       | Não          |
| [IS22](https://requisitos-de-software.github.io/2025.1-FGTS/Elicitacao/Tecnicas-de-Elicitacao/Introspeccao/#IS_RF)   | Portabilidade    | O aplicativo deve estar disponível para outras plataformas, como web.                  | Além do app móvel, deve-se ter versão acessível via navegador (ex: Chrome, Firefox).     | Aumenta o alcance do sistema e oferece alternativas de acesso.                            | Média      | Não          |

---

## Bibliografia

> SERRANO, Milene; SERRANO, Maurício. Requisitos – Aula 13. UnB, 2025. Disponível em: <[https://aprender3.unb.br/pluginfile.php/3096118/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf](https://aprender3.unb.br/pluginfile.php/3096108/mod_resource/content/1/Aula%2010.pdf)>. Acesso em: 18 de maio 2025. p. 27–30.



## Histórico de Versões

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| :-: | :-: | :-: | :-: | :-: |
| `1.0` | 16/05/2025 | Criação do documento | [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa) | [Enzo Emir](https://github.com/EnzoEmir)|
| `1.1` | 18/05/2025 | Adição da introdução,metodologia e modelo. |[Enzo Emir](https://github.com/EnzoEmir) |[Maria](https://github.com/dudaa28)|
| `1.2` | 18/05/2025 | Adição da tabela. |[Danielle](https://github.com/danielle-soaress), [Eduardo](https://github.com/eduardodpms), [Enzo](https://github.com/EnzoEmir), [Leticia](https://github.com/Leticia-Arisa-K-Higa), [Marcelo](https://github.com/MM4k), [Maria](https://github.com/dudaa28), [Victor](https://github.com/VictorPontual) |[Danielle](https://github.com/danielle-soaress), [Eduardo](https://github.com/eduardodpms), [Enzo](https://github.com/EnzoEmir), [Leticia](https://github.com/Leticia-Arisa-K-Higa), [Marcelo](https://github.com/MM4k), [Maria](https://github.com/dudaa28), [Victor](https://github.com/VictorPontual)|
| `1.3` | 21/06/2025 | Adição do tempo de resposta do sistema no Desempenho | [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa) | --- |
