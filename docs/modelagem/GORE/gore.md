# GORE

Esta secção é destinada as técnicas de modelagem GORE que é orientação a meta, e a explicação das técnicas utilizadas.

Sendo cada pasta destinada a uma das técnicas utilizadas, e os artefato gerados para cada uma das categorias definidas na [Home](../../home/home.md) e seus [requistos elicitados](../../elicitacao/elicitacao.md).

## Explicação de GORE

GORE (ou "Goal-Oriented Requirements Engineering") é um modelo de engenharia de requisitos focado em "Orientação a Metas". É uma abordagem usada para capturar, analisar e gerenciar requisitos de sistemas com base nas metas e objetivos dos stakeholders. A ideia central é que os requisitos devem estar alinhados com as metas e objetivos que o sistema ou projeto pretende atingir, garantindo que o produto final atenda às necessidades e expectativas dos stakeholders.

## Técnicas

### NFR Framework

A técnica NFR Framework (Non-Functional Requirements Framework) é uma abordagem estruturada para a elicitação, modelagem, análise e documentação de requisitos não-funcionais (NFRs) em um projeto de software. Requisitos não-funcionais são aqueles que definem os atributos de qualidade do sistema, como desempenho, segurança, usabilidade, confiabilidade, entre outros. Esses requisitos complementam os requisitos funcionais, que especificam o que o sistema deve fazer.

Neste framework utiliza-se o Softgoal Interdependency Graph (SIG):

Que é um gráfico que é utilizado para representar as metas flexíveis que se deseja alcançar e os recursos necessários para atingi-las. Para isso, ele adota a seguinte notação:

| Nome              | Descrição                                                                                                           | Ícone                                                            |
|-------------------|---------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------|
| **Softgoal**        | Característica abstrata, a qual se deseja considerar na análise, visando saber se a mesma será cumprida ou não cumprida, ou seja, escolhida ou não escolhida para ser implementada.                                     | ![nuvem](../../assets/imagens/nuvem01.png)  |
| **Operationalization** | Forma concreta de viabilizar ou não as características abstratas. Aqui, no fundo, são funcionalidades! | ![nuvem](../../assets/imagens/nuvem00.png)             |
| **Argumentation**  | Anotações que podem ser acrescentadas ao modelo, argumentando algo sobre um ponto específico da modelagem. Escrita em linguagem natural.                        | ![nuvem](../../assets/imagens/nuvem02.png)                    |
| **Contributions**      | Usadas para representar as relações ou interações entre nuvens                                   | ![setas](../../assets/imagens/NFRsetas.png)                         |

### Istar

A técnica i* (iStar ou i*) é um framework usado na engenharia de requisitos para modelar e analisar sistemas organizacionais, focando em atores (indivíduos ou sistemas) e suas interações. Ele permite entender as metas, intenções, e dependências entre os atores, facilitando a identificação de requisitos funcionais e não funcionais com base nos objetivos estratégicos da organização. A técnica i* é útil para capturar o contexto social e organizacional no qual um sistema será implementado.


## Histórico de Versões

| **Versão** | **Data** | **Alterações Principais** | **Autor** |
| :--: | :--: | :--: | :--: | 
| 1.0.0 | 21-08-2024 | Lançamento inicial  | Carlos Alves |
| 1.0.1 | 03-09-2024 | Adicionando técnicas  | Carlos Alves |