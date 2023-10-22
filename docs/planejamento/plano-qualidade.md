# Plano de Qualidade

## Introdução

A qualidade do produto é fundamental para o sucesso do projeto, satisfazendo interesses de todas as partes envolvidas no projeto. Um código que segue padrões de qualidade adiciona valor e auxilia os desenvolvedores no processo de manutenção do código. 

Projetos desenvolvidos seguindo bons padrões de qualidade oferecem:

- Maior manutenibilidade do código
- Maior confiabilidade
- Maior eficiência

## Objetivo

Este documento tem como objetivo definir as métricas a serem usadas pela equipe no desenvolvimento do projeto, assim como as ferramentas que serão usadas como forma de auxilio da equipe.

## Ferramentas

Algumas ferramentas serão utilizadas pela equipe para facilitar a implementação de políticas a serem seguidas no desenvolvimento do código, permitindo assim um maior controle de qualidade do código a ser desenvolvido. As ferramentas a serem usadas pela equipe são:

### ESLint

O ESLint é uma ferramenta de **análise estática** para a linguagem JavaScript. O funcionamento ocorre da seguinte forma: são estabelecidas regras a serem seguidas durante o processo de desenvolvimento visando aumentar a qualidade de código. Realizando uma varredura do código, o ESLint consegue detectar partes do código que não estejam seguindo boas práticas, orientando os desenvolvedores do problema e como resolver. As regras definidas são customizáveis, permitindo a equipe um maior controle.

### Jasmine

Jasmine é um framework open source para a realização de **testes unitários** a partir de códigos que utilizam da linguagem JavaScript. O Jasmine tem como característica a sua fácil utilização e a independencia de outros frameworks. No projeto utilizaremos o Jasmine para realizar testes no front-end

### TestClient

Ferramenta muito utilizada para testagem do framework FastAPI. Tem como característica ser de fácil utilização. Será usado pela equipe para a realização de **testes unitários** no back-end. 

### Sonarcloud

O Sonarcloud é uma ferramenta comumente utilizada em projetos para realizar o monitoramento e controle da qualidade do código. O funcionamento da ferramenta acontece a partir da varredura do código, realizando coleta de várias métricas e indicadores técnicos. No projeto o Sonarcloud será acionado a cada Pull Request. Tal comportamento permite um maior controle do que será incorporado efetivamente ao produto, já que o não cumprimento das métricas definidas resulta no bloqueio do Pull Request.

## Métricas

As ferramentas mencionadas anteriorment nos fornecerão métricas que permitem uma visão da qualidade do código construido. Exemplos de métrica a serem coletadas:

| Métrica                  | Descrição                                                                                    |
| ------------------------ | -------------------------------------------------------------------------------------------- |
| Tests                    | Quantidade de testes que estão passando e que estão falhando                                 |
| Coverage                 | Cobertura de código, isto é, o quanto do código está sendo testado                           |
| Complexity               | Complexidade ciclomática. Define a complexidade de um programa                               |
| Comment Lines Density    | Densidade (%) de linhas comentadas. Importante para explicação do código desenvolvido        |
| Duplicated Lines density | Densidade (%) de linhas duplicadas                                                           |
| Ncloc                    | Quantidade de linhas de código. Aqui as linhas de código referente a testes é desconsiderado |
| Security Rating          | Avaliação de segurança de falhas e vulnerabilidades                                          |


Abaixo temos os valores a serem usados pela equipe para determinar se os padrões de qualidade estão sendo seguidos:

| Métrica                      | Valor                    |
| ---------------------------- | ------------------------ |
| Tests                        | 100% dos testes passando |
| Coverage                     | acima de 70%             |
| Complexity                   | até 10                   |
| Comment Lines Density (%)    | até 30%                  |
| Duplicated Lines Density (%) | até 5%                   |
| Security Rating              | 0 (A)                    |


## 4. Referências

> Qualidade de Software. Disponível em: https://www.devmedia.com.br/qualidade-de-software-engenharia-de-software-29/18209. Acesso em 18 out. 2023

> ISO/IEC 25010. ISO 25000. Software and data quality. 2011. Disponível em: https://iso25000.com/index.php/en/iso-25000-standards/iso-25010. Acesso em 18 out. 2023

> ENGSOFTMODERNA. Engenharia de Software Moderna. Disponível em: https://engsoftmoderna.info/. Acesso em: 19 out. 2023.

> Jasmine Documentation. Disponível em: https://jasmine.github.io/index.html. Acesso em 19 out. 2023

## Versionamento

| Data       | Versão | Descrição             | Autor            |
|------------|--------|-----------------------|------------------|
| 19/10/2023 | 1.0    | Documento inicial     | Lucas Andrade    |