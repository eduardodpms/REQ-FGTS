# First Things First (FTF)

## Introdução

Depois de fazer a elicitação dos requisitos utilizando as técnicas de Entrevista, Introspecção, Observação e Storytelling, é necessário priorizá-los para determinar o grau de importância de cada requisito para o sistema. Com isso em mente, foram utilizadas quatro técnicas de priorização, mas nesta seção será explicada apenas a técnica First Things First (FTF).

## Metodologia (FTF)

A técnica de priorização **First Things First** segue um processo no qual é necessário levantar alguns dados, como benefícios, custos e riscos de cada requisito. Com esses dados, os requisito são organizados em ordem de prioridade, do mais importante para o menos importante. O passo a passo do processo é explicado a seguir<a id="REF1" href="#anchor_1">1.</a>:

1. **Criar uma planilha listando todos os requisitos**

    Depois de elicitar todos os requisitos utilizando as técnicas mencionadas anteriormente, foi criada uma planilha listando todos os requisitos identificados.
    
2. **Estimar o benefício relativo de cada requisito para o stakeholder, em uma escala de 1 a 9, onde 1 é o menos significativo e 9 o mais significativo**

    Com a ajuda do usuário, foi estimado o benefício relativo de cada requisito, classificando-os em uma escala de 1 a 9.

3. **Estimar a penalidade que os interessados sofreriam se o requisito não fosse implementado, também de 1 a 9**

    Neste passo, foi estimada a penalidade dos requisitos, ou seja, o quanto o negócio seria impactado negativamente caso o requisito não fosse implementado. Mesmo que o benefício para o cliente seja baixo, a ausência do requisito pode acarretar uma grande penalidade. A escala utilizada segue a mesma lógica do passo anterior.

4. **Criar uma coluna "Valor Total", somando (Benefício Relativo_ \* _Peso Relativo + Penalidade Relativa_ \* _Peso Relativo_), onde os pesos são respectivamente 1 e 0,5.**

    Após coletar os dados de benefício e penalidade relativos, foi criada a coluna “Valor Total” na planilha.

5. **Estimar o custo relativo de implementação de cada requisito, de 1 a 9**

    Em seguida, foi estimado o custo necessário para implementar cada requisito, utilizando a mesma escala.

6. **Estimar o grau relativo de risco de cada requisito, em uma escala de 1 a 9**

    Também foi avaliado o risco associado à implementação de cada requisito, considerando o nível de dificuldade.

7. **Calcular a prioridade de cada requisito usando a fórmula: valor % / (custo % *_Peso custo + riscos % *_ Peso Risco), onde os pesos de custo e risco são, respectivamente, 1 e 0,5**

    Com todos os dados coletados, foi utilizada a fórmula acima para calcular a prioridade de cada requisito.

8. **Ordenar a lista em ordem decrescente**

    Por fim, os requisitos foram ordenados de forma decrescente, de modo que os requisitos no topo da lista tenham maior prioridade e os últimos, menor prioridade.

## Requisitos

<div style="text-align:justify">A Figura 1 a seguir contém a priorização dos Requisitos elicitados.</div>

Legenda: 

- ST: Requisitos de StoryTelling
- IS: Requisitos de Introspecção
- OB: Requisitos da Observação
- EN: Requisitos da Entrevista

<img src="https://github.com/Requisitos-de-Software/2025.1-FGTS/tree/main/docs/assets/First-Things-First.pdf" align="center">

<div style="text-align:center"> Figura 1: Priorização dos requisitos de acordo com método First Things First</div>

## Gravação

## Referências

> REQUISITOS DE SOFTWARE. *Aplicativo – VLC (2023.1)*. Disponível em: <<https://requisitos-de-software.github.io/2023.1-VLC/#/README>>. Acesso em: 03/05/2025.

> <a id="REF1" href="#anchor_1">1.</a> SERRANO, Milene; SERRANO, Maurício. Plano de Ensino FIHC 2023. Brasília: Universidade de Brasília, 2023. Disponícel em: <<https://aprender3.unb.br/pluginfile.php/3096086/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf>>. Acesso em: 03/05/2025.


<br>

## Histórico de Versões 📅

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| :-: | :-: | :-: | :-: | :-: |
| `1.0`  | 03/05 | Criação da aba First Things First | [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa), [Enzo Emir] (https://github.com/EnzoEmir) | - |
