# Plano de Riscos

## 1. Introdução

O Desenvolvimento de Software, assim como qualquer atividade, envolve riscos.
Quando falamos de riscos estamos falando de situações que atrapalham o processo de desenvolvimento da equipe. Assim, é importante identificar os riscos, realizar o seu detalhamento, as probabilidades que ocorra, o impacto provocado por ele e, finalmente, como agir caso tal situação ocorra.

## 2. Categorias

Para melhor organizar o nosso **Plano de Riscos** foram estabelecidas as seguintes categorias de riscos:

- Organizacional: relacionados a falta de recursos humanos e/ou tecnológicos,
- Gerencial: riscos que envolvem o tempo de produção do projeto.
- Técnicos: inclui riscos relacionados à tecnologia, como problemas de compatibilidade de plataformas, falhas de hardware ou software
- Externo: esta categoria engloba riscos que estão além do controle direto da equipe.

## 3. Análise qualitativa e quantitativa 

Foram estabelecidas algumas métricas para ajudar na melhor priorização de cada risco. O registro da probabilidade será realizado a cada sprint, onde os membros poderão relatar como eles vêem a probabilidade de uma tal risco acontecer. Abaixo estão as métricas utilizadas, uma breve explicação de cada uma e os valores possíveis:

### 3.1: Probabilidade

A probabilidade é o risco de um risco identificado acontecer

| Probabilidade | Explicação                                  | Valor |
|---------------|---------------------------------------------|-------|
| Muito Baixo   | Chance muito baixa de acontecer (1% - 20%)  | 1     |
| Baixo         | Chance baixa de acontecer (21% - 40%)       | 2     |
| Médio         | Chance média de acontecer (41% - 60%)       | 3     |
| Alto          | Chance alta de acontecer (61% - 80%)        | 4     |
| Muito Alto    | Chance muito alta de acontecer (81% - 100%) | 5     |

### 3.2: Impacto

O impacto causado caso tal situação ocorra

| Impacto       |              Explicação             | Valor |
|---------------|:-----------------------------------:|:-----:|
| Muito Baixo   |    Quase sem impactos ao projeto    |   1   |
| Baixo         |      Pequeno impacto ao projeto     |   2   |
| Médio         | Representa algum impacto ao projeto |   3   |
| Alto          |  Compromete o andamento do projeto  |   4   |
| Muito Alto    |  Inviabiliza o andamento do projeto |   5   |

### 3.3: PROBABILIDADE x IMPACTO

Consiste no calculo da multiplicação do valor obtido em Probabilidade com o valor obtido em Impacto (P x I)

| P x I       | Muito Baixo | Baixo | Médio | Alto | Muito Alto |
|-------------|:-----------:|:-----:|:-----:|:----:|:----------:|
| Muito Baixo |      1      |   2   |   3   |   4  |      5     |
| Baixo       |      2      |   4   |   6   |   8  |     10     |
| Média       |      3      |   6   |   9   |  12  |     15     |
| Alto        |      4      |   8   |   12  |  16  |     20     |
| Muito Alto  |      5      |   10  |   15  |  20  |     25     |

### 3.4 Prioridade

Com o calculo obtido na etapa anterior é possível elaborar um plano de priorização. Esse plano permite a equipe a melhor se organizar caso um risco ocorra.  

| Prioridade  | Intervalo |
|-------------|:---------:|
| Muito Baixo |   1 a 5   |
| Baixo       |   6 a 10  |
| Média       |  11 a 15  |
| Alto        |  16 a 20  |
| Muito Alto  |  21 a 25  |

## 4. Riscos Registrados

Foram registrados os seguintes riscos:

<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTb_DbZnBtkP9daWd_HEbxXYFqyqnS31LqkcZHF7QwTGXjvg20lLPupjLvRoECSj4Jceq8v6n82NgW3/pubhtml?single=false&widget=true&headers=false" style="width: 800px; height: 650px; border: none;border-radius: 10px;box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);"></iframe>

## 5. Resultado

Usando o calculo descrito em 3.3: PROBABILIDADE x IMPACTO foi feito o cálculo do risco a cada sprint. O resultado obtido foi o seguinte:

<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vSgLG5-okULpZo84ikb8BWkpz0DJB1_93TW3cY5upP0qtIIA1rOf23K8qGCQ8RyWJUVxzgBFhCVu0Ad/pubhtml?single=false&widget=true&headers=false" style="width: 800px; height: 650px; border: none;border-radius: 10px;box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);"></iframe>

## Referências

> [1] Saiba mais sobre o gerenciamento de riscos do PMBOK. Disponível em: https://www.projectbuilder.com.br/blog/saiba-mais-sobre-o-gerenciamento-de-riscos-do-pmbok/. Acesso em: 03 out 2023.

> [2] EQUIPE ALECTRION 2023-1. Análise de riscos. Disponível em: https://fga-eps-mds.github.io/2023-1-Alectrion-DOC/plano-riscos/. Acesso em: 03 out 2023.

> [3] Gerência de riscos em desenvolvimento de software. Disponível em: https://www.devmedia.com.br/gerencia-de-riscos-em-desenvolvimento-de-software/28506. Acesso em: 03 out 2023.