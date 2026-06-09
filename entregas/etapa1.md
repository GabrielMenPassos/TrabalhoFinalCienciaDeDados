# Entrega 1 - Escolha e Definição do Problema

O dataset escolhido para este projeto é composto por registros de compras públicas disponibilizados por meio do portal Dados.gov.br. A base contém informações sobre processos de aquisição realizados por órgãos públicos brasileiros, incluindo dados sobre fornecedores vencedores, órgãos contratantes, valores estimados e homologados, quantidades adquiridas e classificação dos itens contratados.

De acordo com a análise preliminar realizada, o conjunto de dados possui mais de 10.000 registros e apresenta atributos numéricos e categóricos suficientes para atender aos requisitos mínimos definidos para o projeto. Entre os principais atributos disponíveis destacam-se:

* Descrição resumida do item;
* Valor unitário estimado;
* Valor unitário homologado;
* Quantidade adquirida;
* Fornecedor vencedor;
* Órgão contratante;
* Código da classe;
* Código do grupo.

Nossa análise será guiada pelas seguintes perguntas:

## Pergunta 1

Quais fatores estão associados a possíveis indícios de irregularidade em compras públicas?

## Pergunta 2

É possível identificar compras públicas com maior risco de comportamento suspeito utilizando técnicas de Machine Learning?

A proposta consiste em utilizar técnicas de análise exploratória e aprendizado de máquina para identificar padrões presentes nos dados. O objetivo não é determinar a existência de fraude ou corrupção, mas identificar características que possam indicar situações atípicas ou que mereçam atenção adicional por parte de órgãos de controle.

Inicialmente serão investigadas as seguintes hipóteses:

## H1

Compras realizadas com baixa concorrência apresentam maior risco de comportamento suspeito.

## H2

Diferenças pequenas entre o valor estimado e o valor homologado podem indicar baixa competitividade no processo licitatório.

## H3

Compras com valores significativamente acima ou abaixo da média de sua categoria apresentam maior probabilidade de serem classificadas como potencialmente suspeitas.

> **Observação:** O escopo final poderá sofrer ajustes após alinhamento com o professor e análise mais aprofundada da qualidade dos dados disponíveis. Também poderão ser incorporadas novas fontes de dados ou atributos derivados durante as próximas etapas do projeto.
