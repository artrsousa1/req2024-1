# Documento de Requisitos - APPS

# Histórico de Versões
 
| **Versão** | **Data** | **Alterações Principais** | **Autor** |
| :--: | :--: | :--: | :--: | 
| 1.0.0 | 26-07-2024 | Criação do documento e adicionando requisitos | Cecília Quaresma & Hugo Queiroz |
| 1.0.1 | 29-07-2024 | Adicionando storytelling e altera introspecção | Cecília Quaresma & Hugo Queiroz |

## Introspecção

A técnica de elicitação de requisitos conhecida como introspecção é um método reflexivo e autônomo utilizado por
analistas de sistemas para identificar e definir os requisitos de um projeto. Baseando-se em sua própria experiência,
conhecimento prévio e intuição, o analista realiza uma auto-reflexão profunda para imaginar como o sistema deve funcionar,
considerando diversos cenários de uso, possíveis problemas e soluções.

## Resultados da técnica

### Funcionalidades Gerais

1. Mostrar os aplicativos mais bem avaliados
2. Mostrar os aplicativos mais vendidos
3. Separar aplicativos em categorias
4. Mostrar aplicativos em alta
5. Menu Kids 
    - Separar por idades
    - Aplicativos aprovados por professores

### Detalhes do Aplicativo

6. Mostrar informações detalhadas do aplicativo
    - Informações gerais
    - Fotos
    - Avaliações
    - Aplicativos semelhantes

### Informações Adicionais

7. Mostrar empresa desenvolvedora
8. Nome do aplicativo
9. Indicar se contém propagandas ou compras internas
10. Classificação etária
11. Número de downloads feitos
12. Tamanho do aplicativo
13. Classificação do aplicativo
14. Segurança de dados
    - Dados compartilhados
    - Dados coletados
    - Práticas de segurança
    - Exclusão de dados

### Informações sobre Avaliações

15. Sobre o aplicativo
16. Quantidade de avaliações
17. Mostrar avaliações
18. Permitir avaliação do aplicativo
19. Filtrar avaliações
20. Marcar como inapropriado

### Funcionalidades Personalizadas

21. Recomendar aplicativos de acordo com o perfil do usuário
22. Instalar, desinstalar e atualizar aplicativos
23. Pesquisa de aplicativos
    - Salvar pesquisas recentes
    - Pesquisa por voz

### Funcionalidades de Navegação

24. Histórico de aplicativos
25. Mostrar eventos de um aplicativo
26. Lista de desejos
27. Compartilhar aplicativo

### Notificações e Filtros

28. Notificações de atualização ou aplicativos parecidos
29. Filtrar aplicativos


## Storytelling

Storytelling na elicitação de requisitos é uma técnica que utiliza narrativas para capturar e comunicar os requisitos de um sistema de forma mais clara e envolvente. Em vez de apenas listar especificações técnicas, o storytelling incorpora histórias e cenários que ilustram como o sistema será usado na prática. Isso ajuda a criar um entendimento mais profundo e compartilhado entre as partes interessadas, como desenvolvedores, clientes e usuários finais.

## Resultados da técnica

**Personagens**: Dona Maria é uma senhora aposentada de 75 anos, que deseja baixar o aplicativo do Sabin para conferir os resultados de seus exames. Ela apresenta dificuldades de locomoção, por isso seria mais fácil se pudesse olhar os exames pelo celulaar, ao invés de fazer outra visita ao laboratório.

**Problema**: Dona Maria geralmente pede ajuda aos filhos ou netos para mexer com tecnologia, mas, desta vez, ela está sozinha em casa.


**Cenário 1**:
Ações: Ela abre o celular e busca pela PlayStore. Sua primeira ação é tentar rolar a tela e explorar o aplicativo, sem saber exatamente como fazer. Ela encontra a categoria Saúde e, por acaso, vê o ícone do Sabin e consegue instalar.

**Cenário 2**:
Ações: Ela abre o celular e busca pela PlayStore. Ela observa o símbolo de pesquisa no topo da página e busca pelo Sabin. Ao encontrar o app, ela clica no botão azul de instalar e finaliza seu processo. 


**Possível solução**: O app deveria possuir um tutorial básico para usuários novos, ou usuários com menos experiência com tecnologia, destacando a barra de pesquisa e as abas de categorias recomendadas.

![Exemplo1](storytelling1.png)

## Requisitos elicitados


| Requisito | Descrição | Técnica |
| :--: | :-- | :--: |
| REQ01 | O aplicativo deve ser capaz de mostrar os apps mais bem avaliados | Introspecção |
| REQ02 | O aplicativo deve ser capaz de mostrar os apps mais vendidos | Introspecção |
| REQ03 | O aplicativo deve ser capaz de separar os apps em categorias | Introspecção |
| REQ04 | O aplicativo deve ser capaz de mostrar apps em alta | Introspecção |
| REQ05 | O aplicativo deve ter uma área kids | Introspecção |
| REQ06 | O aplicativo deve mostrar informações relevantes dos apps disponiveis| Introspecção |
| REQ07 | O aplicativo deve recomendar apps de acordo com o perfil do usuário | Introspecção |
| REQ08 | O aplicativo deve permitir Instalar apps | Introspecção |
| REQ09 | O aplicativo deve permitir desinstalar apps | Introspecção |
| REQ10 | O aplicativo deve permitir atualizar apps já instalados | Introspecção |
| REQ11 | O aplicativo deve permitir a pesquisa de apps | Introspecção |
| REQ12 | O aplicativo deve mostrars notificações de atualização e recomendação de apps parecidos | Introspecção |
| REQ13 | O aplicativo deve salvar pesquisas recentes | Introspecção |
| REQ14 | O aplicativo deve manter um histórico de apps já instalados | Introspecção |
| REQ15 | O aplicativo deve permitir a criação de uma lista de desejos | Introspecção |
| REQ16 | O aplicativo deve mostrar eventos de um app | Introspecção |
| REQ17 | O aplicativo deve permitir compartilhar app | Introspecção |
| REQ18 | O aplicativo deve permitir a avaliação de um app | Introspecção |
| REQ19 | O aplicativo deve permitir marcar um app como inapropriado | Introspecção |
| REQ20 | O aplicativo deve ter um tutorial básico para novos usuarios | StoryTelling |
| REQ21 | O aplicativo tem que ser acessível para pessoas idosas | StoryTelling |

