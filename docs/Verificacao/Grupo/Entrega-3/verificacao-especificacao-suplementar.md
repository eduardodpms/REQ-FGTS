# Verificação da Especificação Suplementar

## Introdução

A verificação do artefato de **Especificação Suplementar** teve como principal objetivo avaliar se o documento atende aos requisitos mínimos de qualidade esperados para esta etapa do projeto, com foco específico na categorização dos requisitos não funcionais segundo o modelo **FURPS+**.

A inspeção foi conduzida com base na técnica formal proposta por **Fagan**, utilizando uma checklist estruturada e seguindo as diretrizes de qualidade definidas no [planejamento de verificação](https://requisitos-de-software.github.io/2025.1-FGTS/Verificacao/Grupo/Entrega-2/planejamento-verificacao-entrega-2/).

Além da análise objetiva de cada item da lista de verificação, foram feitas observações qualitativas sobre clareza, completude e coerência geral do artefato.

## Objetivo

O objetivo deste documento é relatar os resultados da verificação realizada sobre o artefato de [Especificação Suplementar](https://requisitos-de-software.github.io/2025.1-FGTS/Modelagem-I/EspecificacaoSuplementar/) na versão 1.4 de data **22/06/2025**, referente à Etapa 2 do [projeto](https://github.com/Requisitos-de-Software/2025.1-FGTS).

## Metodologia

A avaliação seguiu as checklists definidas previamente no planejamento da equipe, com cada item sendo marcado como **Sim**, **Não** ou **Incompleto**, além da possibilidade de inclusão de observações específicas. Prints de tela foram utilizados como evidência para cada item avaliado.

---

## Cronograma e Participantes

Nesta verificação, o integrante **Victor Pontual** atuou como avaliador, enquanto **Enzo Emir** foi o revisor responsável. Abaixo, segue o registro dos participantes:

<font size="3"><p style="text-align: center">Tabela 1: Participantes</p></font>

<div align="center">

<table>
  <thead>
    <tr>
      <th>Nome</th>
      <th>Função</th>
      <th>Data</th>
      <th>Hora</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> <a href="https://github.com/VictorPontual">Victor Pontual</a> </td>
      <td> Avaliador </td>
      <td> 22/06/2025 </td>
      <td> 16:40 </td>
    </tr>
    <tr>
      <td> <a href="https://github.com/EnzoEmir">Enzo Emir</a> </td>
      <td> Revisor </td>
      <td> 22/06/2025 </td>
      <td> 17:00 </td>
    </tr>
  </tbody>
</table>


</div>

<font size="2"><p style="text-align: center">Fonte: [Victor Pontual](https://github.com/VictorPontual)</p></font>

---

## Inspeção

###  **Itens Gerais**

| Item | Avaliação | Observação | Print | Autor |
| ----- | :---: | :---: | :---: | :---: |
| 01   | Sim       | O artefato contém referências bibliográficas adequadas.                | ![Bibliografia](https://github.com/Requisitos-de-Software/2025.1-FGTS/blob/main/docs/assets/EspecificacaoSuplementar/bibliografia.png?raw=true) | [Victor Pontual](https://github.com/VictorPontual)
| 02   | Sim       | Existe um histórico de versões, com id, descrição e autoria.           | ![Histórico](https://github.com/Requisitos-de-Software/2025.1-FGTS/blob/main/docs/assets/EspecificacaoSuplementar/historico.png?raw=true)       | [Victor Pontual](https://github.com/VictorPontual)
| 03   | Sim       | As tabelas e imagens possuem legendas e fontes corretamente indicadas. | ![Tabelas](https://github.com/Requisitos-de-Software/2025.1-FGTS/blob/main/docs/assets/EspecificacaoSuplementar/tabelas.png?raw=true)           | [Victor Pontual](https://github.com/VictorPontual)
| 04   | Sim       | Há uma introdução contextualizando o artefato.                         | ![Introdução](https://github.com/Requisitos-de-Software/2025.1-FGTS/blob/main/docs/assets/EspecificacaoSuplementar/introducao.png?raw=true)     | [Victor Pontual](https://github.com/VictorPontual)
| 05   | Sim       | O texto utiliza linguagem formal e técnica.                            | ![Linguagem](https://github.com/Requisitos-de-Software/2025.1-FGTS/blob/main/docs/assets/EspecificacaoSuplementar/introducao.png?raw=true)       | [Victor Pontual](https://github.com/VictorPontual)
| 06   | Sim       | Há coerência entre os elementos gráficos e o conteúdo textual.         | ![Coerência](https://github.com/Requisitos-de-Software/2025.1-FGTS/blob/main/docs/assets/EspecificacaoSuplementar/coerencia.png?raw=true)       | [Victor Pontual](https://github.com/VictorPontual)

---

### **Itens Específicos sobre a Especificação Suplementar**

| Item | Avaliação | Observação | Print | Autor |
| ----- | :---: | :---: | :---: | :---: |
| 01   | Sim       | O documento segue a estrutura baseada no modelo FURPS+.                  | ![Coerência](https://github.com/Requisitos-de-Software/2025.1-FGTS/blob/main/docs/assets/EspecificacaoSuplementar/coerencia.png?raw=true)               | [Victor Pontual](https://github.com/VictorPontual)
| 02   | Sim       | Há definição de requisitos de tempo de resposta na seção de desempenho.  | ![Desempenho](https://github.com/Requisitos-de-Software/2025.1-FGTS/blob/main/docs/assets/EspecificacaoSuplementar/desempenho.png?raw=true)       | [Victor Pontual](https://github.com/VictorPontual)
| 03   | Não      | Foram definidos os ambientes e plataformas de execução do aplicativo.    |           | [Victor Pontual](https://github.com/VictorPontual)
| 04   | não       | Todos os requisitos não funcionais descritos são testáveis/verificáveis. | ![Testabilidade](https://github.com/Requisitos-de-Software/2025.1-FGTS/blob/main/docs/assets/EspecificacaoSuplementar/testabilidade.png?raw=true) | [Victor Pontual](https://github.com/VictorPontual)

## Análise de Resultados

Durante a verificação da **Especificação Suplementar**, foram identificadas **duas não conformidades principais**:

* **Item 03:** O documento não traz uma descrição clara dos **ambientes e plataformas de execução** (ex: sistema operacional, navegadores suportados, dispositivos compatíveis).

* **Item 04:** Alguns **requisitos não funcionais** apresentados não estão formulados de maneira **testável ou verificável**, o que dificulta sua validação futura.

Apesar dessas pendências, o artefato apresenta pontos positivos como boa estrutura, uso correto do modelo **FURPS+**, além de clareza na seção de desempenho.


## Correção Recomendada

Para garantir a conformidade total com a checklist, recomenda-se:

1. **Incluir uma seção dedicada aos ambientes e plataformas de execução**, informando de forma explícita quais dispositivos, sistemas ou navegadores o software deve suportar.

2. **Reformular os requisitos não funcionais que não são testáveis**, utilizando padrões de redação que permitam medições claras (exemplo: tempo máximo de resposta em segundos, limites de uso de memória, padrões de segurança, etc).





## Acompanhamento

A verificação foi realizada por **Victor Pontual** e revisada por **Enzo Emir**.

O artefato **permanecerá em acompanhamento até que as correções sugeridas sejam implementadas**. Após a atualização, uma **nova rodada de verificação** deverá ser conduzida para assegurar que os itens não conformes foram devidamente resolvidos.

Essa etapa reforça a importância de tratar com atenção requisitos não funcionais, especialmente no que diz respeito à sua **testabilidade e ambiente de execução**, garantindo maior segurança e rastreabilidade para as fases seguintes do projeto.

## Referências Bibliográficas

> <a id="RP1" href="#TEC1">1.</a> SERRANO, Milene; SERRANO, Maurício. Requisitos – Aula 13. UnB, 2025. Disponível em: <[https://aprender3.unb.br/pluginfile.php/3096118/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf](https://aprender3.unb.br/pluginfile.php/3096108/mod_resource/content/1/Aula%2010.pdf)>. Acesso em: 18 de maio 2025. p. 27–30.

---

## Histórico de Versões

| Versão | Data       | Descrição                         | Autor          | Revisor   |
| ------ | ---------- | --------------------------------- | -------------- | --------- |
| `1.0`    | 22/06/2025 | Criação e verificação do artefato | [Victor Pontual](https://github.com/VictorPontual) | [Enzo Emir](https://github.com/EnzoEmir) |
| `1.1` | 26/06/2025 | Adicionando autor na tabela | [Enzo Emir](https://github.com/EnzoEmir) | [Victor Pontual](https://github.com/VictorPontual) |