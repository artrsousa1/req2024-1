# Léxico

Refere-se ao conjunto de termos e definições específicos utilizados em um projeto ou domínio. Em engenharia de requisitos, o léxico garante que todos os stakeholders tenham uma compreensão comum dos termos e conceitos empregados nos requisitos. Isso inclui definições de termos técnicos, nomes de entidades e processos, e pode ajudar a evitar ambiguidades e mal-entendidos ao comunicar e documentar requisitos.

Para esta modelagem, utilizamos o seguinte método para definir os termos.

| Categoria | Descrição |
|-----------------|-------|
| Classificação | Sujeito/Estado/Objeto/Verbo |
| Sinônimos | Palavras semelhantes com o mesmo sentido |
| Noção | O que significa o símbolo |
| Impacto | Descreve de ações e de seus efeitos | 

E a descrição das classificação possíveis utilizadas.

| Tipo do símbolo | Noção | Impacto |
|-----------------|-------|-------|
| Sujeito | Entidade (pessoa, sistema, componente) que realiza uma ação no sistema. Pode ser um usuário, um sistema externo, ou um módulo interno do sistema.  | Ações que o sujeito pode realizar |
| Verbo |  Ação ou processo que o sujeito realiza, muitas vezes representando uma funcionalidade ou operação do sistema. Exemplo: "Cadastrar", "Atualizar", "Consultar".  | Quais os refleos daação no ambiente e quais os novos estados decorrentes |
| Objeto |  Entidade sobre a qual a ação do verbo é realizada. Pode ser um dado, um documento, uma tela, ou qualquer outro elemento com o qual o sujeito interage. Exemplo: "Formulário", "Relatório"  | Ações que podem ser aplicadas ao objeto  |
| Estado | Se refere à condição ou situação de um objeto ou sistema em um determinado momento. O "Estado" descreve como algo se encontra em um ponto específico do tempo, geralmente como resultado de uma ação (verbo) ou interação | Identificar outros etsados e ações que podem ocorrer a partir do estado que se descreve |



Então, abaixo estão todos os termos que julgamos interessantes para o projeto.



## Aba

---

|  |  |
| :--- | :-- |
| **Nome**| Aba |
| **Classificação** | Objeto   |
| **Sinônimos** | Tela, página, menu  |
| **Noção** | Elemento da interface gráfica que agrupa conteúdos relacionados |
| **Impactos** |   * O usuário pode interagir com as funcionalidades disponiveis |

## App 

---

|  |  |
| :--- | :-- |
| **Nome**| App | 
| **Classificação** | Objeto   |
| **Sinônimos** | Aplicativo, aplicação  |
| **Noção** |  Software desenvolvido para dispositivos eletrônicos |
| **Impactos** |   * O app pode ser instalado<br>  * O app pode ser desinstalado<br>   * O app pode ser atualizado|

## Atualizar

---

|  |  |
| :--- | :-- |
| **Nome**| Atualizar |
| **Classificação** |   Verbo |
| **Sinônimos** | - |
| **Noção** | Substituir uma versão antiga para uma versão mais nova | 
| **Impactos** |   * O app vai para uma versão mais nova<br>   * Novas funcionalidades<br> * Correções de bugs |




## Barra de pesquisa

---

|  |  |
| :--- | :-- |
| **Nome**| Barra de pesquisa |
| **Classificação** |   Objeto |
| **Sinônimos** | Buscar, lupa, pesquisar |
| **Noção** | A barra de pesquisa é capaz de buscar um conteúdo pelo nome |
| **Impactos** |   * O usuário pode buscarr um app pelo nome |




## Bem avaliados

---

|  |  |
| :--- | :-- |
| **Nome**| Bem avaliados|
| **Classificação** |   Estado |
| **Sinônimos** | Boa avaliação |
| **Noção** | Estado do app que possui muitas boas avaliações dentro da Play Store |
| **Impactos** |   * O app bem avaliado é mais recomendado ao usuário|



## Botão de instalar

---

|  |  |
| :--- | :-- |
| **Nome**| Botão de instalar |
|**Classificação** |   Objeto |
| **Sinônimos** | -  |
| **Noção** |  Botão tipicamente azul na página do aplicativo, que permite ao usuário obter um app|
| **Impactos** |   * O usuário pode clicar no botão de instalar para obter um app |


## Buscar por texto

---

|  |  |
| :--- | :-- |
| **Nome**| Buscar por texto |
| **Classificação** |   Verbo |
| **Sinônimos** | -  |
| **Noção** |  Ao clicar na barra de pesquisa, o usuário pode escolher entre buscar por voz ou por texto. Na busca por texto, o teclado é acionado e o usuário digita o nome do app que procura|
| **Impactos** |   * O usuário pode buscar por texto um app |



## Buscar por voz

---

|  |  |
| :--- | :-- |
| **Nome**| Buscar por voz |
| **Classificação** |  Verbo |
| **Sinônimos** | -  |
| **Noção** |  Ao clicar na barra de pesquisa, o usuário pode escolher entre buscar por voz ou por texto. Na busca por voz, o microfone é acionado e o usuário fala o nome do app que procura|
| **Impactos** |  * O usuário pode buscar por voz um app Em Alta|

## Clicar

---

|  |  |
| :--- | :-- |
| **Nome**| Clicar |
| **Classificação** |  Verbo |
| **Sinônimos** | Apertar, segurar, tocar |
| **Noção** |  Ação do usuário de clicar em um elemento no app, como botões, menus, ícones |
| **Impactos** |  * O usuário pode clicar no botão de instalar para obter um app |



## Descrição do app

---

|  |  |
| :--- | :-- |
| **Nome**| Descrição do app |
| **Classificação** |   Objeto |
| **Sinônimos** | Informações do app |
| **Noção** |  Na página do aplicativo, ficam dispostas diferentes informações úteis ao usuário sobre como o app|funciona, qual seu tamanho, quantas instalações etc. 
| **Impactos** | * O usuário pode encontrar informações essenciais do app na parte de descrição|

## Desinstalar

---

|  |  |
| :--- | :-- |
| **Nome**| Desinstalar                                                                      |
| **Classificação**   | Verbo                                                                            |
| **Sinônimos**       | Retirar, remover, excluir                                                        |
| **Noção**           | Remover um app já instalado no dispositivo                                       |
| **Impactos**        | * O usuário pode clicar no botão de desinstalar para excluir um app<br> * O app vai para uma versão mais nova<br>   * Novas funcionalidades<br> * Correções de bugs                                                              |

## Dispositivo compatível

---

|  |  |
| :--- | :-- |
| **Nome**            | Dispositivo compatível                                                           |
| **Classificação**   | Objeto                                                                           |
| **Sinônimos**       | Aparelho suportado                                                               |
| **Noção**           | Dispositivo eletrônico que é capaz de reconhecer e rodar um app                  |
| **Impactos**        | * O usuário pode instalar e desinstalar apps                                     |

## Em Alta

---

|  |  |
| :--- | :-- |
| **Nome**            | Em Alta                                                                          |
| **Classificação**   | Objeto                                                                           |
| **Sinônimos**       | -                                                                                |
| **Noção**           | Aba responsável por mostrar os apps mais baixados recentemente. Os apps mais atrativos para os usuários |
| **Impactos**        | * O usuário encontra novidades na aba Em Alta                                    |

## Forma de pagamento

---

|  |  |
| :--- | :-- |
| **Nome**            | Forma de pagamento                                                               |
| **Classificação**   | Objeto                                                                           |
| **Sinônimos**       | Método de pagamento                                                              |
| **Noção**           | Modo com o qual o usuário paga pelo app. Pode ser pix, cartão de crédito, boleto etc. |
| **Impactos**        | * O usuário utiliza uma forma de pagamento ao comprar um app                     |

## Novidade

---

|  |  |
| :--- | :-- |
| **Nome**            | Novidade                                                                         |
| **Classificação**   | Objeto                                                                           |
| **Sinônimos**       | Inovação, app novo                                                               |
| **Noção**           | Um aplicativo diferente por sua perspectiva inovadora, nova abordagem, ou algum elemento que desperta interesse do público |
| **Impactos**        | * O usuário encontra novidades na aba Em Alta                                    |



## Permissão

---

|  |  |
| :--- | :-- |
| **Nome**| Permissão |
| **Classificação** |   Verbo |
| **Sinônimos** | Autorização, permitir, licença |
| **Noção** |  Conceder ao app a autorização para acessar determinadas funcionalidades, dados ou recursos do seu dispositivo|
| **Impactos** |   * Permite ao usuário acesso a funcionalidades essenciais do aplicativo |


## Rede

---

|  |  |
| :--- | :-- |
| **Nome**| Rede |
| **Classificação** |   Objeto |
| **Sinônimos** | Internet, conexão |
| **Noção** | Conjunto de dispositivos interconectados que comparilham dados e recursos |
| **Impactos** |   * Acesso à informaçaõ<br>   * Acesso á serviços<br>  * Possibilita instalar app|
| **Impactos** |   * A tela inicial mostra os principais apps<br>  * A tela inicial mostra a barra de pesquisa no topo<br> * A tela inicial mostra novidades |

## Tela inicial

---

|  |  |
| :--- | :-- |
| **Nome**| Tela inicial |
| **Classificação** |   Objeto |
| **Sinônimos** | Página inicial, menu inicial, página principal   |
| **Noção** |  Primeira aba que o usuário visualiza ao clicar na Play Store |
| **Impactos** |    * O usuario pode navegar pelas opções<br>   * O usuário pode buscar por app/jogos<br>   * O usuário pode configurar sua conta |


## Usuário

--- 

|  |  |
| :--- | :-- |
| **Nome**| Usuário |
| **Classificação** | Sujeito   |
| **Sinônimos** |  User |
| **Noção** |  Pessoa que utiliza a Play Store, pessoa que navega e utiliza apps em dispositivos eletrônicos |
| **Impactos** |   * O usuário pode instalar apps<br>  * O usuário pode desinstalar apps<br>   * O usuário pode atualizar apps<br> * O usuário pode avaliar apps<br>   * O usuário pode comprar apps |
 


## Histórico de Versões

| **Versão** | **Data** | **Alterações Principais** | **Autor** |
| :--: | :--: | :--: | :--: | 
| 1.0.0 | 14-08-2024 | Lançamento inicial do léxico | Cecília Quaresma, Hugo Queiroz, Larissa Vieira |
| 1.0.1 | 15-08-2024 | Arrumando arquivo do léxico | Arthur Ribeiro, Carlos Alves e Hugo Queiroz|
| 1.0.2 | 16-08-2024 | Adicionando novas tabelas, a descrição e arrumando os conceitos | Carlos Alves, Cecília Quaresma e Hugo Queiroz|