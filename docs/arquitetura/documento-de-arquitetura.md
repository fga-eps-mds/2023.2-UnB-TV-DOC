# Documento de Arquitetura

## 1. Introdução


Este documento detalha a estrutura do software de um projeto que incorpora Angular para o frontend. Ele é composto por quatro microsserviços desenvolvidos com FastAPI, um gateway em Node para facilitar a comunicação entre esses serviços e um banco de dados PostgreSQL, além de consumir a API do EduPlay para acessar os vídeos e programas ao vivo. A estrutura projetada tem foco na escalabilidade, resiliência e alto desempenho. Baseia-se no conceito de microsserviços, onde componentes distintos funcionam como serviços autônomos, interagindo por meio de interfaces claramente estabelecidas. Este é um esboço da arquitetura em um nível geral:

![Arquitetura](../assets/arquitetura.svg)
<figcaption style="text-align: center !important">
    Fonte: Próprio autor
  </figcaption>
</figure>

## 2. Tecnologias

### 2.1. Angular

Angular é empregado como a principal tecnologia de frontend neste projeto, proporcionando uma interface de usuário interativa e responsiva. Sua arquitetura robusta e recursos avançados de bidirectional data binding facilitam a gestão eficiente dos estados da interface, enquanto sua integração com os microsserviços via HTTP garante uma comunicação fluida e eficiente. Angular também contribui para uma manutenção mais fácil e um desenvolvimento ágil, graças à sua estrutura modular e ao extenso ecossistema de ferramentas.

### 2.2. FastAPI

FastAPI é utilizado neste projeto para desenvolver quatro microsserviços, destacando-se por sua alta performance e facilidade de uso. Este framework de Python permite a construção rápida de APIs eficientes, com recursos automáticos de documentação interativa e validação de dados. A escolha do FastAPI apoia a arquitetura de microsserviços do projeto, proporcionando uma comunicação ágil e confiável entre os diferentes serviços, além de facilitar a escalabilidade e manutenção do sistema.

### 2.3. PostgreSQL

No projeto, o PostgreSQL é utilizado como o sistema de gerenciamento de banco de dados, oferecendo uma solução robusta e confiável para armazenamento e recuperação de dados. Sua escolha deve-se à sua performance elevada, suporte a transações complexas e compatibilidade com os padrões SQL. Além disso, o PostgreSQL é conhecido por sua extensibilidade e forte conformidade com ACID, garantindo a integridade e a segurança dos dados. Essas características o tornam uma escolha adequada para gerenciar as informações críticas e assegurar a eficiência na manipulação de dados no contexto do projeto.

# 2. Representação arquitetural

## 2.1. Diagrama de Relações

O Diagrama de Relações é uma representação gráfica que ilustra como os componentes do sistema se comunicam e interagem. Nesse tipo de diagrama, você pode destacar as conexões e dependências entre os diferentes microserviços, o frontend e o backend do sistema. Isso ajuda a visualizar a arquitetura de software e entender como as partes se relacionam.

![diagramaRelacoes](/docs/arquitetura/Imagens/diagramaDeRelacao.jpg)

O estilo arquitetural apresentado acima, adota uma abordagem em que uma aplicação é dividida em unidades menores, chamadas de microsserviços, que funcionam de maneira autônoma com baixo acoplamento. Esses microsserviços podem interagir entre si geralmente por meio de APIs e são organizados com base em funções de negócios específicas.

## 2.2. Representação dos serviços

Ao criar um diagrama de relações de um sistema, é importante fornecer detalhes suficientes para representar com precisão a arquitetura do sistema e como os diferentes componentes se conectam.

-   Frontend: Representação da interface do usuário, como páginas da web, aplicativos móveis ou qualquer outra forma de interação com o usuário.

-   Backend: Representado pelos servidores, aplicativos e serviços que processam solicitações vindas do frontend, realizam lógica de negócios e interagem com o banco de dados.

-   Microserviços: Cada microserviço é representado separadamente no diagrama, destacando as funções específicas que eles desempenham.

-   Comunicações: As setas e linhas conectando os elementos indicam as interações e comunicações entre o frontend, o backend e os microserviços.

-   Gateway: Responsável para realizar a interface do usuário com os demais serviços da aplicação, provendo autenticação e autorização.

-   Usuário: Serviço de usuário é responsável por gerenciar os usuários da aplicação.

-   EduPlay: Serviço de stream responsável por gerenciar os videos da aplicação.

-   Notificação: Serviço de notificação é responsável por gerenciar os notificações da aplicação.



## 4. Visão lógica

### 4.1. Diagrama de pacote Front-end

![frontend](./Imagens/FrontEnd%20pacote.png)

### 4.2. Diagrama de pacote Back-end

![backend](./Imagens/BackEnd.png)

### 4.3. Diagrama de implantação

![diagrama-de-implantacao](./Imagens/DiagramaImplantacao.png)

### 4.4. Diagrama de classe

#### 4.4.1. Microsserviço de usuário

![diagrama-de-classes](./Imagens/diagramaDeClasse-User.png)

## 5. Referências Bibliográficas

CREATELY. O Guia Fácil de Diagramas de Implantação UML. Disponível em: https://creately.com/blog/pt/diagrama/tutorial-do-diagrama-de-implantacao.

Geekhunter. O que são microsserviços e como funcionam?. Disponível em: https://blog.geekhunter.com.br/arquitetura-de-microsservicos-x-arquitetura-monolitica/.

## 6. Histórico de versão

| **Data**   | **Descrição**                                    | **Autore(es)**    |
| ---------- | ------------------------------------------------ | ----------------- |
| 22/10/2023 | Adição do documento                              | Sávio             |
| 22/10/2023 | Adiciona diagrama de classes e demais alterações | Gabrielle Ribeiro |
