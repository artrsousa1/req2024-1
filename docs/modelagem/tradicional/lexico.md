# [Léxico](tradicional.md#lexico)

Esta técnica esta definifa em [léxico](tradicional.md#lexico).

## Resultado da técnica

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
| **Noção** | Componente da interface gráfica que organiza e exibe seções de conteúdo relacionadas de forma categorizada, permitindo fácil navegação entre diferentes funcionalidades ou informações dentro do aplicativo |
| **Impactos** |   * O usuário pode interagir com as funcionalidades disponiveis<br> * O usuário pode trocar de aba e explorar diferentes telas do app<br> * O usuário pode visualizar diferentes categorias em cada aba |

## App 

---

|  |  |
| :--- | :-- |
| **Nome**| App | 
| **Classificação** | Objeto   |
| **Sinônimos** | Aplicativo, aplicação  |
| **Noção** |  Aplicação de software desenvolvida especificamente para dispositivos móveis ou eletrônicos, projetada para executar tarefas específicas, oferecer funcionalidades diversas e interagir diretamente com os usuários por meio de uma interface intuitiva. |
| **Impactos** |   * O app pode ser instalado<br>  * O app pode ser desinstalado<br>   * O app pode ser atualizado|

## Atualizar

---

|  |  |
| :--- | :-- |
| **Nome**| Atualizar |
| **Classificação** |   Verbo |
| **Sinônimos** | - |
| **Noção** | Processo de substituição de uma versão anterior de um software ou aplicativo por uma versão mais recente, visando melhorias em desempenho, segurança, correções de erros ou novas funcionalidades, garantindo que o sistema esteja sempre otimizado e atualizado. | 
| **Impactos** |   * O app vai para uma versão mais nova<br>   * Ao atualizar surgem novas funcionalidades<br> * Atualizar leva a correções de bugs |




## Barra de pesquisa

---

|  |  |
| :--- | :-- |
| **Nome**| Barra de pesquisa |
| **Classificação** |   Objeto |
| **Sinônimos** | Buscar, lupa, pesquisar |
| **Noção** | Componente da interface que permite ao usuário localizar rapidamente conteúdos ou funcionalidades específicas inserindo palavras-chave ou nomes, facilitando a navegação dentro do aplicativo. |
| **Impactos** |   * O usuário pode buscar um app pelo nome<br> * A barra de pesquisa aparece no canto inferior da tela inicial|




## Bem avaliados

---

|  |  |
| :--- | :-- |
| **Nome**| Bem avaliados|
| **Classificação** |   Estado |
| **Sinônimos** | Boa avaliação |
| **Noção** |  Estado de um aplicativo na Play Store que apresenta uma alta média de avaliações positivas dos usuários, refletindo satisfação geral com suas funcionalidades, desempenho e experiência de uso. |
| **Impactos** |  * Aplicativos bem avaliados tendem a ser mais recomendados aos usuários pela Play Store.<br>
  * Aplicativos com boas avaliações podem aparecer em listas de destaque, como "Novidades" ou "Recomendados".<br>
  * A classificação de um app depende diretamente do feedback e das avaliações dos usuários, influenciando sua visibilidade e downloads futuros.|



## Botão de instalar

---

|  |  |
| :--- | :-- |
| **Nome**| Botão de instalar |
|**Classificação** |   Objeto |
| **Sinônimos** | -  |
| **Noção** |  Elemento interativo, geralmente azul, localizado na página do aplicativo na Play Store, que permite ao usuário iniciar o processo de download e instalação do app no dispositivo.|
| **Impactos** |   * Ao clicar no botão de instalar, o usuário inicia o download e a instalação do aplicativo no seu dispositivo.<br>
  * O botão de instalar facilita o acesso rápido e intuitivo ao app diretamente pela Play Store. |


## Buscar por texto

---


|  |  |
| :--- | :-- |
| **Nome** | Buscar por texto |
| **Classificação** | Verbo |
| **Sinônimos** | - |
| **Noção** | Ação realizada pelo usuário ao clicar na barra de pesquisa e optar por digitar manualmente o nome do aplicativo que deseja encontrar, utilizando o teclado virtual do dispositivo. |
| **Impactos** | 
  * Permite ao usuário localizar aplicativos específicos digitando diretamente na barra de pesquisa.<br>  * Facilita a busca por apps com nomes conhecidos, oferecendo maior precisão na pesquisa. |




## Buscar por voz

---

|  |  |
| :--- | :-- |
| **Nome** | Buscar por voz |
| **Classificação** | Verbo |
| **Sinônimos** | - |
| **Noção** | Ação realizada pelo usuário ao clicar na barra de pesquisa e optar pela busca por voz, ativando o microfone para falar o nome do aplicativo que deseja encontrar. |
| **Impactos** | 
  * Permite ao usuário localizar aplicativos por meio de comandos de voz, oferecendo uma experiência mais rápida e conveniente. <br> * Facilita a busca por apps, incluindo aqueles em destaque, sem a necessidade de digitação. |


## Clicar

---

|  |  |
| :--- | :-- |
| **Nome** | Clicar |
| **Classificação** | Verbo |
| **Sinônimos** | Tocar, pressionar, selecionar |
| **Noção** | Ação do usuário de interagir com elementos da interface do app, como botões, menus ou ícones, ao tocar na tela ou pressionar o mouse, executando a função associada. |
| **Impactos** | 
  * Permite ao usuário iniciar ações, como instalar um app, abrir menus ou navegar entre diferentes seções do aplicativo.<br>  * A interação por clique é essencial para a navegação e uso das funcionalidades do aplicativo.|



## Descrição do app

---

|  |  |
| :--- | :-- |
| **Nome** | Descrição do app |
| **Classificação** | Objeto |
| **Sinônimos** | Informações do app |
| **Noção** | Seção na página do aplicativo que fornece informações detalhadas sobre o funcionamento do app, seu tamanho, número de instalações, funcionalidades e outras características relevantes para o usuário. |
| **Impactos** | 
  * O usuário pode acessar informações essenciais sobre o aplicativo, facilitando a decisão de download e instalação.<br>* A descrição ajuda a entender as funcionalidades e benefícios do app antes de sua instalação.|


## Desinstalar

---

|  |  |
| :--- | :-- |
| **Nome** | Desinstalar |
| **Classificação** | Verbo |
| **Sinônimos** | Retirar, remover, excluir |
| **Noção** | Ação de remover um aplicativo já instalado do dispositivo, liberando espaço e eliminando o acesso ao app. |
| **Impactos** | 
  * O usuário pode clicar no botão de desinstalar para remover o app do dispositivo.<br>  * A desinstalação libera espaço de armazenamento e pode melhorar o desempenho do dispositivo.<br>* A exclusão do app impede o uso de suas funcionalidades e acesso a atualizações futuras.|

## Dispositivo compatível

---

|  |  |
| :--- | :-- |
| **Nome** | Dispositivo compatível |
| **Classificação** | Objeto |
| **Sinônimos** | Aparelho suportado |
| **Noção** | Dispositivo eletrônico que atende aos requisitos técnicos necessários para reconhecer, instalar e executar um aplicativo corretamente. |
| **Impactos** | 
  * O usuário pode instalar e desinstalar apps de forma adequada no dispositivo.<br>  * A compatibilidade garante que o aplicativo funcione conforme esperado, proporcionando uma experiência de uso adequada.<br>  * Dispositivos compatíveis podem receber atualizações e novas funcionalidades do app, mantendo o software atualizado e funcional.|


## Em Alta

---

|  |  |
| :--- | :-- |
| **Nome** | Em Alta |
| **Classificação** | Objeto |
| **Sinônimos** | - |
| **Noção** | Seção da Play Store que exibe os aplicativos mais baixados e populares no momento, destacando os que estão em alta entre os usuários. |
| **Impactos** | 
  * O usuário pode descobrir novos aplicativos que estão em alta e têm atraído muita atenção recentemente.<br>  * A aba Em Alta ajuda a identificar tendências e aplicativos populares, facilitando a escolha de novos downloads.|

## Forma de pagamento

---

|  |  |
| :--- | :-- |
| **Nome** | Forma de pagamento |
| **Classificação** | Objeto |
| **Sinônimos** | Método de pagamento |
| **Noção** | Modo pelo qual o usuário realiza o pagamento para adquirir um aplicativo, podendo incluir opções como cartão de crédito, débito, boleto, ou outros métodos de pagamento eletrônico como Pix. |
| **Impactos** | 
  * O usuário seleciona uma forma de pagamento para completar a compra do aplicativo.<br>  * A escolha da forma de pagamento pode influenciar a facilidade e a segurança da transação.<br>  * Oferecer várias formas de pagamento pode aumentar a acessibilidade e a satisfação do usuário ao adquirir o app.| 

## Novidade

---

|  |  |
| :--- | :-- |
| **Nome** | Novidade |
| **Classificação** | Objeto |
| **Sinônimos** | Inovação, app novo |
| **Noção** | Aplicativo que se destaca por sua abordagem inovadora, recursos únicos ou elementos que capturam o interesse do público, muitas vezes sendo promovido como uma novidade na Play Store. |
| **Impactos** | 
  * O usuário pode encontrar e explorar novos aplicativos que oferecem funcionalidades inéditas ou abordagens diferentes.<br>  * A presença na aba "Em Alta" ou similar pode aumentar a visibilidade e atratividade do app para novos usuários.<br>  * Novidades podem atrair mais downloads e avaliações, ajudando a construir a reputação e o sucesso do aplicativo.|




## Permissão

---

|  |  |
| :--- | :-- |
| **Nome** | Permissão |
| **Classificação** | Verbo |
| **Sinônimos** | Autorização, permitir, licença |
| **Noção** | Ação de conceder a um aplicativo a autorização necessária para acessar e utilizar certas funcionalidades, dados ou recursos do dispositivo, como câmeras, microfone, ou localização. |
| **Impactos** | 
  * Permite ao aplicativo acessar e usar recursos essenciais, possibilitando o funcionamento completo de suas funcionalidades.<br>  * Concede ao usuário controle sobre quais informações e recursos o aplicativo pode utilizar, impactando a privacidade e a segurança.<br> * A concessão de permissões é fundamental para a operação do aplicativo e a realização de suas funções previstas.|



## Rede

---

|  |  |
| :--- | :-- |
| **Nome** | Rede |
| **Classificação** | Objeto |
| **Sinônimos** | Internet, conexão |
| **Noção** | Conjunto de dispositivos interconectados que compartilham dados e recursos, permitindo comunicação e acesso a informações e serviços online. |
| **Impactos** | 
  * Permite o acesso a informações e serviços disponíveis na internet.<br>  * Facilita a instalação e atualização de aplicativos através de conexões online.<br>  * É essencial para a operação de muitos aplicativos e serviços que dependem de comunicação em tempo real ou acesso a dados remotos.|


## Tela inicial

---

|  |  |
| :--- | :-- |
| **Nome** | Tela inicial |
| **Classificação** | Objeto |
| **Sinônimos** | Página inicial, menu inicial, página principal |
| **Noção** | Primeira aba que o usuário visualiza ao acessar a Play Store, servindo como ponto de partida para explorar aplicativos, jogos e outras funcionalidades. |
| **Impactos** | 
  * O usuário pode navegar pelas diferentes opções e categorias disponíveis na Play Store.<br>  * Facilita a busca por aplicativos e jogos através de uma barra de pesquisa ou seções destacadas.<br>  * Permite ao usuário acessar e configurar sua conta, visualizar novidades e recomendações personalizadas.|



## Usuário

--- 

|  |  |
| :--- | :-- |
| **Nome**        | Usuário |
| **Classificação** | Sujeito   |
| **Sinônimos**     | User, Consumidor, Cliente |
| **Noção**         | Pessoa que utiliza a Play Store para navegar, instalar, desinstalar, atualizar, avaliar e comprar aplicativos em dispositivos eletrônicos. |
| **Impactos**      | * O usuário pode instalar, desinstalar e atualizar aplicativos.<br> * O usuário pode avaliar aplicativos.<br> * O usuário pode realizar compras de aplicativos e conteúdos adicionais.<br> * O usuário pode interagir com desenvolvedores e outros usuários por meio de avaliações e feedback. |


## Histórico de Versões

| **Versão** | **Data** | **Alterações Principais** | **Autor** |
| :--: | :--: | :--: | :--: | 
| 1.0.0 | 14-08-2024 | Lançamento inicial do léxico | Cecília Quaresma, Hugo Queiroz, Larissa Vieira |
| 1.0.1 | 15-08-2024 | Arrumando arquivo do léxico | Arthur Ribeiro, Carlos Alves e Hugo Queiroz|
| 1.0.2 | 16-08-2024 | Adicionando novas tabelas, a descrição e arrumando os conceitos | Carlos Alves, Cecília Quaresma e Hugo Queiroz|
| 1.0.3 | 22-08-2024 | Arrumando doc textual | Carlos Alves e Hugo Queiroz|
| 1.1.0 | 06-09-2024 | Corrigindo o léxico baseado no checklist de análise| Cecília Quaresma e Hugo Queiroz|
