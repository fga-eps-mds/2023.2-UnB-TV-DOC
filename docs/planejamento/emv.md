# EVM Agile

## 1. Introdução

O EVM (Earned Value Management) possibilita a avaliação do progresso de um projeto e a realização de estimativas de resultados esperados. Em contraste com o EVM Tradicional, o EVM Agile trata esforço, tempo e custo em termos de histórias de usuário, sprints, pontos, entre outros.

Visualize a planilha de EVM Agile [aqui](https://docs.google.com/spreadsheets/d/1obPSGECUHMV9HbKNf8G8Lz0dIZXh_AhVI6PILVsY6mg/edit?usp=sharing)

## 2. Métricas EVM

-   **Valor planejado (PV, Planned Value)**: O valor planejado define o trabalho que deve ser realizado e materializa o custo total planejado do projeto a qualquer ponto no tempo.

`PV = custo total do projeto * % de trabalho planejado `

-   **Valor realizado (EV, Earned Value)**: O valor realizado especifica a medida do trabalho já realizada no projeto a qualquer ponto.

`EV = custo total do projeto * % de trabalho realizado`

-   **Custo Real (AC, Actual Cost)**: O custo real representa o custo incorrido em uma atividade durante um tempo específico, devendo ser considerados custos com hardware, infra, material etc. O AC é uma medida cumulativa de todo o custo do projeto desde o início até o fim.

`AC = custo real`

-   **Orçamento na conclusão (BAC, Budget at Completion)**: O BAC representa o custo total de todo o trabalho planejado e a base é o final do projeto.

`BAC = custo total do trabalho`

## 3. Métricas derivadas

A partir das métricas, pode-se calcular as variâncias, os índices de desempenho e as estimativas.

### Variâncias

-   **Variação do custo (CV, Cost Variance)**: É um indicador quantitativo da divergência do que foi planejado no orçamento inicial. Se o CV > 0, o projeto está abaixo do orçamento. Se CV < 0, o projeto está acima do orçamento. Se CV = 0, o projeto está conforme planejado.

`CV = EV - AC`

-   **Variação do prazo (SV, Schedule Variance)**: É um indicador indicativo da divergência do planejado no cronogrma inicial. Se SV > 0, o projeto está adiantado. Se SV < 0, O projeto está atrasado. Se SV = 0, o projeto está conforme o cronograma.

`SV = EV - PV`

### Índices de desempenho

-   **Índice de desempenho do custo (CPI, Cost Performance Index)**: Expressa a relação do valor realizado para o custo real.

`CPI = EV / AC`

-   **Índice de desempenho do prazo (SPI, Schedule Performance Index)**: Expressa a relação do valor realizado para o planejado, por isso mede a eficiencia do tempo.

`SPI = EV / PV`

### Estimativas

-   **Estimativa para terminar**: Custo esperado para terminar o restante do projeto.

`EAC = (BAC - EV) / CPI`

-   **Estimativa na conclusão**: Representa o custo total esperado quando o trabalho for totalmente finalizado.

`EAC = AC + ETC`

## 4. Planilha

<iframe iframe width=100% height=600 src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRYK1CgigWUi-TqvguWAtMHS9s2OVhz8rCk9dqWUJ3n9l88ouDrL5As8z-0mHVMTatrZlSLD_AExVeJ/pubhtml?widget=true&amp;headers=false"></iframe>

## 5. Bibliografia

> Earned Value Management: The Basics Disponível em: https://www.ecosys.net/knowledge/earned-value-management-basics/. Acesso em: 09 dezembro 2023.

## Versionamento

| Data       | Versão | Descrição         | Autor       |
| ---------- | ------ | ----------------- | ----------- |
| 09/10/2023 | 1.0    | Documento inicial | João Victor |
