# Caso de uso


## Diagrama de caso de uso

## versão 01

![alt text](../assets/imagens/Caso%20de%20uso%20-%20Play%20Store%20-%20Page%201%20Caso%20de%20Uso.png)

*Autores: Carlos Alves, Cecília Quaresma, Hugo Queiroz & Larissa Vieira*

## Especificação de caso de uso

### Visualizar app/jogo

| **Descrição**      | O usuário deseja buscar/visualizar apps/jogos |
|--------------------|------------------------------------------------------|
| **Ator(es)**       | usuário e a Play Store                                   |
| **Pré-Requisitos** | Possuir a Play Store e ter rede     |
| **Fluxo Principal** |
| 1. usuário abre a Play Store. |
| 2. A Play Store exibe uma tela inicial  |
| 3. Asuário usa a barra de pesquisa para procurar o app/jogo [FA01](#FA01) [FA02](#FA02) [FE01](#FE01)|
| 4. Asuário clica no icone do app/jogo|
| **Fluxo Alternativo** |
| <a name="FA01"></a>**FA01: O usuário usa as categorias** |
| 1. Após abrir a tela inicial o usuário vai pelas categorias disponíveis. |
| 2. O Usuário clica na categoria desejada.[FA01.1](#FA01.1)|
| 3. A play Store mostra os apps/jogos daquela categoria. |
| 4. O usuário segue o fluxo principal |
| <a name="FA01.1"></a>**FA01.1: O usuário usa a aba categorias** |
| 1. Após abrir a tela inicial o cliente busca a aba "categorias". |
| 2. O usuario escolhe a categoria desejada. |
| 3. O usuário navega buscando o app/jogo. |
| 4. O usuário segue o fluxo principal. |
| <a name="FA02"></a>**FA02: O usuário acha na tela inicial** |
| 1. Após abrir a tela inicial o usuário acha a o app/jogo na tela inicial |
| 2. O usuário segue o fluxo principal. |
| **Fluxo de Exceção** |
| <a name="FE01"></a>**FE01: O app/jogo não está disponível na Play Store** |
| 1. Após o usuário buscar o jogo o jogo desejado não aparece na play store |
| 2. O usuário vai ter que observar os motivos de não ter achado. |
| 3. O usuário reinicia o fluxo principal se achar o erro. |


### Instalar aplicativos


| **Descrição**      | O usuário deseja instalar em seu dispositivo apps/jogos |
|--------------------|------------------------------------------------------|
| **Ator(es)**       | usuário e a Play Store                                   |
| **Pré-Requisitos** | Possuir a Play Store, ter rede, espaço suficiente e bateria     |
| **Fluxo Principal** |
| 1. Usuário segue o [fluxo de visualizar app](#visualizar-appjogo). |
| 2. O usuário clica no botão de "instalar" [FE02](#FE02) [FE03](#FE03) [FE04](#FE04)|
| 3. usuário aguarda a instalação do app/jogo no seu dispositivo |
| **Fluxo de Exceção** |
| <a name="FE02"></a>**FE02: Falha na rede** |
| 1. A Play Store para a instalação |
| 2. A Play Store fica esperando da conexão voltar. |
| <a name="FE03"></a>**FE02: O dispositivo acaba a bateria na instalação** |
| 1. Após o iniciar a instalação o dispositivo acaba a bateria |
| 2. O usuário coloca o dispositivo para carregar. |
| 3. O usuário reinicia o fluxo principal. |
| <a name="FE04"></a>**FE01: O dispositivo não está com espaço suficiente** |
| 1. Após o iniciar a instalação a paly store informa que não tem espaço disponível |
| 2. O usuário soluciona o problema para continuar e retoma o fluxo principal. |


### Atualizar Aplicativos


| **Descrição**      | O usuário deseja atualizar apps/jogos em seu dispositivo |
|--------------------|------------------------------------------------------|
| **Ator(es)**       | usuário e a Play Store                                   |
| **Pré-Requisitos** | Possuir a Play Store, ter rede, espaço suficiente e bateria |
| **Fluxo Principal** |
| 1. O usuário segue o [fluxo de visualizar app](#visualizar-appjogo). [FA03](#FA03) |
| 2. O usuário clica no botão de "Atualizar" [FE05](#FE05) [FE06](#FE06) [FE07](#FE07)|
| 3. O usuário aguarda a atualização do app/jogo no seu dispositivo |
| **Fluxo Alternativo** |
| <a name="FA03"></a>**FA03: O usuário usa a página de gerenciar apps e dispositivos** |
| 1. Após abrir a tela inicial, o usuário vai clica na sua conta. |
| 2. O usuário clica em "gerenciar apps e dispositivos".|
| 3. O usuário clica em "Gerenciar". |
| 4. O usuário escolhe a opção "Atualizações disponíveis" |
| 5. O usuário escolhe os apps/jogos que deseja atualizar |
| 6. O usuário clica no botão de atualizar |
| **Fluxo de Exceção** |
| <a name="FE05"></a>**FE05: Falha na rede** |
| 1. A Play Store para a atualização |
| 2. A Play Store fica esperando da conexão voltar. |
| <a name="FE06"></a>**FE06: O dispositivo acaba a bateria na atualização** |
| 1. Após o iniciar a atualização o dispositivo acaba a bateria |
| 2. O usuário coloca o dispositivo para carregar. |
| 3. O usuário reinicia o fluxo principal. |
| <a name="FE07"></a>**FE07: O dispositivo não está com espaço suficiente** |
| 1. Após o iniciar a atualização a play store informa que não tem espaço disponível |
| 2. O usuário soluciona o problema para continuar e retoma o fluxo principal. |


### Desinstalar aplicativos


| **Descrição**      | O usuário deseja desinstalar em seu dispositivo apps/jogos |
|--------------------|------------------------------------------------------|
| **Ator(es)**       | usuário e a Play Store                                   |
| **Pré-Requisitos** | Possuir a Play Store e ter bateria|
| **Fluxo Principal** |
| 1. Usuário segue o [fluxo de visualizar app](#visualizar-appjogo) [FA04](#FA04). |
| 2. O usuário clica no botão de "Desinstalar" [FE08](#FE08)|
| 3. usuário aguarda a Desinstalação do app/jogo no seu dispositivo |
| **Fluxo Alternativo** |
| <a name="FA04"></a>atualização**FA04: O usuário usa a página de gerenciar apps e dispositivos** |
| 1. Após abrir a tela inicial, o usuário vai clica na sua conta. |
| 2. O usuário clica em "gerenciar apps e dispositivos".|
| 3. O usuário clica em "Gerenciar". |
| 5. O usuário escolhe os apps/jogos que deseja desinstalar |
| 6. O usuário clica no botão da lixeira para desintalar |
| **Fluxo de Exceção** |
| <a name="FE08"></a>**FE08: O dispositivo acaba a bateria na Desinstalação** |
| 1. Após o iniciar a Desinstalação o dispositivo acaba a bateria |
| 2. O usuário coloca o dispositivo para carregar. |
| 3. O usuário reinicia o fluxo principal. |


### Avaliar aplicativos

| **Descrição**      | O usuário deseja avaliar apps/jogos |
|--------------------|------------------------------------------------------|
| **Ator(es)**       | usuário e a Play Store                                   |
| **Pré-Requisitos** | Possuir a Play Store, ter rede e ter bateria|
| **Fluxo Principal** |
| 1. Usuário segue o [fluxo de visualizar app](#visualizar-appjogo) [FE05](#FE05) |
| 2. O usuário clica na quantidade des estrelas [FE08](#FE08)|
| 3. O usuário preenche os campos permitidos |
| 4. O usuário clica em postar |
| **Fluxo Alternativo** |
| <a name="FA05"></a>atualização**FA05: O usuário já está na página do app/jogo** |
| 1. O usuário segue o fluxo principal. |
| **Fluxo de Exceção** |
| <a name="FE09"></a>**FE09: Falha na rede** |
| 1. Após o iniciar a avaliação o dispositivo desconecta da rede|
| 2. A Play Store fica esperando da conexão voltar. |
| <a name="FE10"></a>**FE10: O dispositivo acaba a bateria na atualização** |
| 1. Após o iniciar a avaliação o dispositivo acaba a bateria |
| 2. O usuário coloca o dispositivo para carregar. |
| 3. O usuário reinicia o fluxo principal. |


## Histórico de Versões
 
| **Versão** | **Data** | **Alterações Principais** | **Autor** |
| :--: | :--: | :--: | :--: | 
| 1.0.0 | 14-08-2024 | Criação do documento | Carlos Alves, Cecília Quaresma, Hugo Queiroz e Larissa Vieira|
| 1.0.1 | 14-08-2024 | Adicionando diagrama | Carlos Alves, Cecília Quaresma, Hugo Queiroz e Larissa Vieira|
| 1.0.2 | 15-08-2024 | Adicionando especificação de caso de uso | Carlos Alves e Hugo Queiroz|