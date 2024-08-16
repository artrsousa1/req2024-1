# Cenários

O método de cenários é uma técnica eficaz de elicitação e modelagem de requisitos que envolve a criação de narrativas detalhadas sobre como os usuários interagem com o sistema. Esses cenários descrevem situações reais e hipotéticas que capturam as necessidades, expectativas e comportamentos dos usuários.

## Resultado da técnica

Para esta técnica dividimos os requistos priorizados como must em [requisitos elicitados](../elicitacao/elicitacao.md), e cada equipe definida em [projeto](../home/home.md#moscow) ficou resposável por modelar alguns cenários baseados nos requistos divididos.

## Cenário 001 - Buscando app

|  |  |
|--------------|--------------------------------|
| **Objetivo** | Instalar um app pré-determinado |
| **Contexto** | **Local:** Tela inicial da Play Store<br>**Pré-condição:** Saber o nome do app desejado |
| **Atores** | Usuário |
| **Recursos** | Dispositivo compatível (celular, tablet ou computador) com acesso à Play Store |
| **Episódios** | 1. O usuário abre a Play Store.<br>2. O usuário clica na barra de pesquisa.<br>3. O usuário escolhe entre busca por voz ou texto.<br>4. O usuário digita/fala o nome do app desejado.<br>5. O usuário clica no app encontrado.<br>6. O usuário confere as informações principais.<br>7. O usuário clica no botão de instalar.<br>8. O usuário abre o novo app |
| **Restrições** | Digitar o nome do app corretamente.<br>Espaço de armazenamento suficiente.<br>Ter conexão com a internet |
| **Exceções** | O app não está disponível na Play Store.<br>O app não é compatível com o dispositivo.<br>Falha na rede ao instalar |
| **Rastreabilidade** | [REQ01](../elicitacao/elicitacao.md#REQ01) |

---

## Cenário 002 - Buscando app por categoria

|  |  |
|--------------|--------------------------------|
| **Objetivo** | Instalar um app para aprender idiomas |
| **Contexto** | **Local:** Tela inicial da Play Store<br>**Pré-condição:** Ter interesse em aprender idiomas |
| **Atores** | Usuário |
| **Recursos** | Dispositivo compatível (celular, tablet ou computador) com acesso à Play Store |
| **Episódios** | 1. O usuário abre a Play Store.<br>2. O usuário rola pela página principal.<br>3. O usuário encontra a categoria desejada - Educação.<br>4. O usuário procura os apps mais bem avaliados.<br>5. O usuário analisa a descrição do app.<br>6. O usuário instala o app |
| **Restrições** | Espaço de armazenamento suficiente.<br>Ter conexão com a internet |
| **Exceções** | O usuário não se agradou com nenhuma das opções.<br>Falha na rede ao instalar |
| **Rastreabilidade** | [REQ01](../elicitacao/elicitacao.md#REQ01) |

---

## Cenário 003 - Navegando pela Play Store

|  |  |
|--------------|--------------------------------|
| **Objetivo** | Buscar alguma novidade na Play Store |
| **Contexto** | **Local:** Tela inicial da Play Store<br>**Pré-condição:** Interesse em explorar novos apps |
| **Atores** | Usuário |
| **Recursos** | Dispositivo compatível (celular, tablet ou computador) com acesso à Play Store |
| **Episódios** | 1. O usuário abre a Play Store.<br>2. O usuário clica na aba "Em Alta".<br>3. O usuário clica nas primeiras opções de apps.<br>4. O usuário lê a descrição.<br>5. O usuário decide baixar um app para testar |
| **Restrições** | Espaço de armazenamento suficiente.<br>Ter conexão com a internet |
| **Exceções** | Falha na rede ao instalar |
| **Rastreabilidade** | [REQ01](../elicitacao/elicitacao.md#REQ01) |

---

## Cenário 004 - Instalando um jogo/app pago

|  |  |
|--------------|--------------------------------|
| **Objetivo** | Instalar Minecraft |
| **Contexto** | **Local:** Tela do app/jogo<br>**Pré-condição:** Saber o nome do app/jogo |
| **Atores** | Usuário |
| **Recursos** | Dispositivo compatível (celular, tablet ou computador) com acesso à Play Store |
| **Episódios** | 1. O usuário clica no botão de instalar.<br>2. O usuário confirma a forma de pagamento.<br>3. O usuário autoriza a compra.<br>4. O usuário espera o jogo ser instalado |
| **Restrições** | Memória disponível.<br>Bateria suficiente.<br>Forma de pagamento válida.<br>Acesso à internet |
| **Exceções** | Saldo insuficiente na forma de pagamento.<br>Memória insuficiente.<br>Bateria do dispositivo acaba antes da instalação |
| **Rastreabilidade** | [REQ02](../elicitacao/elicitacao.md#REQ02) |

---

## Cenário 005 - Atualizando um jogo/app

|  |  |
|--------------|--------------------------------|
| **Objetivo** | Atualizar o app ou jogo para sua versão mais recente |
| **Contexto** | **Local:** Tela do app/jogo<br>**Pré-condição:** Saber se há atualizações |
| **Atores** | Usuário |
| **Recursos** | Dispositivo compatível (celular, tablet ou computador) com acesso à Play Store |
| **Episódios** | 1. O usuário clica no botão de atualizar.<br>2. O usuário espera o jogo ser atualizado |
| **Restrições** | Memória disponível.<br>Bateria suficiente.<br>Acesso à internet |
| **Exceções** | Memória insuficiente.<br>Bateria do dispositivo acaba antes da instalação.<br>Não ter atualização |
| **Rastreabilidade** | [REQ03](../elicitacao/elicitacao.md#REQ03) |

---

## Cenário 006 - Desinstalar um jogo/app

|  |  |
|--------------|--------------------------------|
| **Objetivo** | Desinstalar o Minecraft |
| **Contexto** | **Local:** Tela do app/jogo<br>**Pré-condição:** Ter o app/jogo já instalado |
| **Atores** | Usuário |
| **Recursos** | Dispositivo compatível (celular, tablet ou computador) com acesso à Play Store |
| **Episódios** | 1. O usuário clica no botão de desinstalar |
| **Restrições** | Bateria suficiente |
| **Exceções** | Bateria do dispositivo acaba antes da remoção |
| **Rastreabilidade** | [REQ04](../elicitacao/elicitacao.md#REQ04) |

---

## Cenário 007 - Pedir Reembolso de um App/Jogo

|  |  |
|--------------|--------------------------------|
| **Objetivo** | Solicitar o reembolso do Minecraft |
| **Contexto** | **Local:** Tela de "Histórico de Compras" na Play Store<br>**Pré-condição:** O app/jogo deve ter sido comprado recentemente e estar dentro do período permitido para solicitação de reembolso |
| **Atores** | Usuário |
| **Recursos** | Dispositivo compatível (celular, tablet ou computador) com acesso à Play Store e conexão à internet |
| **Episódios** | 1. O usuário abre o app da Play Store no dispositivo.<br>2. O usuário acessa o menu e clica em "Pagamentos e assinaturas".<br>3. O usuário seleciona "Histórico de compras".<br>4. O usuário localiza o Minecraft na lista de compras.<br>5. O usuário clica no app/jogo e escolhe a opção "Veja".<br>6. O usuário seleciona o motivo do reembolso e confirma a solicitação.<br>7. A Play Store processa o pedido e notifica o usuário sobre o status do reembolso. |
| **Restrições** | A solicitação deve ser feita dentro do prazo permitido para reembolso (geralmente 48 horas após a compra) |
| **Exceções** | 1. O prazo para solicitar reembolso já expirou.<br>2. A Play Store rejeita o pedido devido a violações das políticas de reembolso. |
| **Rastreabilidade** | [REQ06](../elicitacao/elicitacao.md#REQ06) |

---

## Cenário 008 - Acessar a política de privacidade de um app ou jogo

|  |  |
|--------------|--------------------------------|
| **Objetivo** | Acessar a política de privacidade de um aplicativo ou jogo |
| **Contexto** | **Local:** Tela para instalar app/jogo<br>**Tempo:** Aproximadamente 30 segundos<br>**Pré-condição:** Ter acesso à rede |
| **Atores** | Usuário |
| **Recursos** | Dispositivo compatível (celular, tablet ou computador) com acesso à Play Store |
| **Episódios** | 1. O usuário acessa a Play Store.<br>2. O usuário busca pelo app ou jogo desejado.<br>3. O usuário clica no suporte do app/jogo.<br>4. O usuário clica na opção "Política de Privacidade".<br>5. O sistema exibe a política de privacidade do app ou jogo. |
| **Restrições** | A política de privacidade deve estar disponível em um formato legível. |
| **Exceções** | Não ter o app/jogo, falta de conexão com a rede e política de privacidade não disponível. |
| **Rastreabilidade** | [REQ06](../elicitacao/elicitacao.md#REQ06) |

---

## Cenário 009 - Visualizar os Sistemas Operacionais Compatíveis

|  |  |
|--------------|--------------------------------|
| **Objetivo** | Ver quais sistemas operacionais um app ou jogo pode ser executado. |
| **Contexto** | **Local:** Tela para instalar app/jogo<br>**Tempo:** Aproximadamente 30 segundos<br>**Pré-condição:** Ter acesso à rede e ter o app instalado |
| **Atores** | Usuário |
| **Recursos** | Dispositivo compatível (celular, tablet ou computador) com acesso à Play Store |
| **Episódios** | 1. O usuário acessa a Play Store.<br>2. O usuário busca pelo app ou jogo desejado.<br>3. O usuário clica na página do app ou jogo.<br>4. O usuário visualiza a seção "Sobre" do app.<br>5. O sistema exibe os sistemas operacionais nos quais o app ou jogo pode ser executado. |
| **Restrições** | As informações devem ser precisas e atualizadas. |
| **Exceções** | Falta de conexão com a internet e informações de compatibilidade não disponíveis. |
| **Rastreabilidade** | [REQ07](../elicitacao/elicitacao.md#REQ07) |

---

## Cenário 010 - Visualizar Data de Lançamento de um App ou Jogo

|  |  |
|--------------|--------------------------------|
| **Objetivo** | Visualizar a data de lançamento de um app ou jogo. |
| **Contexto** | **Local:** Tela para instalar app/jogo<br>**Tempo:** Aproximadamente 30 segundos<br>**Pré-condição:** Ter acesso à rede e ter o app instalado |
| **Atores** | Usuário |
| **Recursos** | Dispositivo compatível (celular, tablet ou computador) com acesso à Play Store |
| **Episódios** | 1. O usuário acessa a Play Store.<br>2. O usuário busca pelo app ou jogo desejado.<br>3. O usuário clica na seção "Sobre" do app ou jogo.<br>4. O usuário visualiza a data de lançamento do app ou jogo. |
| **Restrições** | A data deve ser apresentada de forma clara e precisa. |
| **Exceções** | Falta de conexão com a internet e data de lançamento não disponível. |
| **Rastreabilidade** | [REQ08](../elicitacao/elicitacao.md#REQ08) |

---

## Cenário 011 - Mostrar Dados Extraídos pelo App ou Jogo

|  |  |
|--------------|--------------------------------|
| **Objetivo** | Visualizar quais dados um app ou jogo coleta dos usuários. |
| **Contexto** | **Local:** Tela para instalar app/jogo<br>**Tempo:** Aproximadamente 30 segundos<br>**Pré-condições:** O usuário deve estar conectado à internet. |
| **Atores** | Usuário |
| **Recursos** | Dispositivo compatível (celular, tablet ou computador) com acesso à Play Store |
| **Episódios** | 1. O usuário acessa a Play Store.<br>2. O usuário busca pelo app ou jogo desejado.<br>3. O usuário clica na página do app ou jogo.<br>4. O usuário acessa a seção de "Dados Coletados".<br>5. O sistema exibe quais dados são coletados pelo app ou jogo. |
| **Restrições** | As informações devem ser claras e detalhadas. |
| **Exceções** | Falta de conexão com a internet e informações sobre dados coletados não disponíveis. |
| **Rastreabilidade** | [REQ09](../elicitacao/elicitacao.md#REQ09) |

---

## Cenário 012 - Mostrar Permissões do App ou Jogo

|  |  |
|--------------|--------------------------------|
| **Objetivo** | Visualizar quais permissões um app ou jogo possui na máquina do usuário. |
| **Contexto** | **Local:** Tela para instalar app/jogo<br>**Tempo:** Aproximadamente 30 segundos<br>**Pré-condições:** O usuário deve estar conectado à internet. |
| **Atores** | Usuário |
| **Recursos** | Dispositivo compatível (celular, tablet ou computador) com acesso à Play Store |
| **Episódios** | 1. O usuário acessa a Play Store.<br>2. O usuário busca pelo app ou jogo desejado.<br>3. O usuário clica na página do app ou jogo.<br>4. O usuário acessa a seção de "Permissões".<br>5. O sistema exibe quais permissões o app ou jogo solicita. |
| **Restrições** | As permissões devem ser apresentadas de forma clara. |
| **Exceções** | Falta de conexão com a internet.<br>Informações sobre permissões não disponíveis. |
| **Rastreabilidade** | [REQ10](../elicitacao/elicitacao.md#REQ10) |

---

## Cenário 013 - Mostrar Uso dos Dados Extraídos

|  |  |
|--------------|--------------------------------|
| **Objetivo** | Visualizar o que um app ou jogo faz com os dados que coleta dos usuários. |
| **Contexto** | **Local:** Tela para instalar app/jogo<br>**Tempo:** Aproximadamente 30 segundos<br>**Pré-condições:** O usuário deve estar conectado à internet. |
| **Atores** | Usuário |
| **Recursos** | Dispositivo compatível (celular, tablet ou computador) com acesso à Play Store |
| **Episódios** | 1. O usuário acessa a Play Store.<br>2. O usuário busca pelo app ou jogo desejado.<br>3. O usuário clica na página do app ou jogo.<br>4. O usuário acessa a seção de "Uso dos Dados".<br>5. O sistema exibe como os dados coletados são utilizados. |
| **Restrições** | As informações devem ser detalhadas e transparentes. |
| **Exceções** | Falta de conexão com a internet.<br>Informações sobre uso dos dados não disponíveis. |
| **Rastreabilidade** | [REQ11](../elicitacao/elicitacao.md#REQ11) |

## Cenário 014 - Criação de Conta Gmail

|  |  |
|--------------|--------------------------------|
| **Objetivo** | Permitir que o usuário crie uma nova conta Gmail através do aplicativo |
| **Contexto** | **Local:** Menu lateral de usuário<br>**Pré-condição:** Ter acesso à internet |
| **Atores** | Usuário |
| **Recursos** | Dispositivo compatível (celular, tablet ou computador) com acesso à Play Store |
| **Episódios** | 1. O usuário abre a Play Store.<br>2. O usuário clica no icone de foto do usuário.<br>3. O usuário clica no botão de fazer login com o google.<br>4. O usuário insere as informações necessárias no formulário.<br> 5. O usuário é redirecionado para a tela inicial logado na nova conta.|
| **Restrições** | Ter conexão com a internet<br>As informações inseridas pelo usuário devem atender |
| **Exceções** | Erro de conexão<br>Informações fornecidas são inválidas<br>Os dados informados estão indisponíveis |
| **Rastreabilidade** | [REQ19](../elicitacao/elicitacao.md#REQ19) |

## Cenário 015 - Login com Conta Google Existente

|  |  |
|--------------|--------------------------------|
| **Objetivo** | Permitir que o usuário faça login com uma conta Google existente |
| **Contexto** | **Local:** Menu lateral de usuário<br>**Pré-condição:** Ter acesso à internet e o usuário já possuir uma conta Google |
| **Atores** | Usuário |
| **Recursos** | Dispositivo compatível (celular, tablet ou computador) com acesso à Play Store |
| **Episódios** | 1. O usuário abre o aplicativo deslogado.<br>2. O usuário seleciona a opção "Criar conta Gmail".<br>3. O usuário insere suas credenciais.<br>4. Se os dados forem válidos, o usuário é redirecionado para a tela inicial logado. |
| **Restrições** | Conexão com a internet.<br>Credenciais válidas. |
| **Exceções** | Erro de Conexão<br> Credenciais Incorretas|
| **Rastreabilidade** | [REQ14](../elicitacao/elicitacao.md#REQ14) |


## Cenário 016 - Funcionalidade "Esqueci minha senha"

|  |  |
|--------------|--------------------------------|
| **Objetivo** | Permitir que o usuário recupere sua senha através da funcionalidade "Esqueci a senha" |
| **Contexto** | **Local:** Menu lateral de usuário<br>**Pré-condição:** Ter acesso à internet e o usuário já possuir uma conta Google  |
| **Atores** | Usuário |
| **Recursos** | Dispositivo compatível (celular, tablet ou computador) com acesso à Play Store |
| **Episódios** | 1. O usuário abre o aplicativo deslogado<br>2. O usuário seleciona a opção "Esqueci minha senha"<br> 3. O usuário segue os passos para recuperar sua senha<br>4. O Google valida as informações e permite que o usuário redefina sua senha |
| **Restrições** | Necessidade de conexão com a internet.<br>Usuário deve fornecer informações corretas para a recuperação. |
| **Exceções** | Erro de Conexão<br>Falha na Verificação de Identidade |
| **Rastreabilidade** | [REQ31](../elicitacao/elicitacao.md#REQ31) |

## Cenário 017 - Remoção de Contas Logadas

|  |  |
|--------------|--------------------------------|
| **Objetivo** | Permitir que o usuário remova contas Google logadas no aplicativo |
| **Contexto** | **Local:** Menu lateral de usuário<br>**Pré-condição:** Ter acesso à internet e o usuário ter várias contas Google logadas no aplicativo |
| **Atores** | Usuário |
| **Recursos** | Dispositivo compatível (celular, tablet ou computador) com acesso à Play Store |
| **Episódios** | 1. O usuário acessa a seção de "Gerenciamento de Contas". <br>2. O usuário seleciona a conta que deseja remover. <br>3. O aplicativo solicita confirmação para a remoção. <br>4. O usuário confirma. <br>5. O aplicativo desloga e remove a conta do dispositivo. |
| **Restrições** | Necessidade de conexão com a internet.<br>Confirmação do usuário para remoção. |
| **Exceções** | Erro de Conexão.<br>Falha ao Deslogar. |
| **Rastreabilidade** | [REQ16](../elicitacao/elicitacao.md#REQ16) |


## Cenário 018 - Troca da Conta Principal

|  |  |
|--------------|--------------------------------|
| **Objetivo** | Permitir que o usuário troque a conta principal usada no dispositivo |
| **Contexto** | **Local:** Menu lateral de usuário<br>**Pré-condição:** Ter acesso à internet e o usuário ter mais de uma conta Google logada no dispositivo |
| **Atores** | Usuário |
| **Recursos** | Dispositivo compatível (celular, tablet ou computador) com acesso à Play Store |
| **Episódios** | 1. O usuário acessa a seção de "Gerenciamento de Contas". <br>2. O usuário seleciona a opção "Trocar conta principal". <br>3. O aplicativo exibe as contas logadas. <br>4. O usuário seleciona a nova conta principal. <br>5. O aplicativo confirma a troca e redefine a conta principal. |
| **Restrições** |  Necessidade de conexão com a internet. |
| **Exceções** |  Erro de Conexão<br>Falha ao Redefinir Conta Principal|
| **Rastreabilidade** | [REQ17](../elicitacao/elicitacao.md#REQ17) |

## Cenário 019 - Gerenciamento de Dispositivos Vinculados

|  |  |
|--------------|--------------------------------|
| **Objetivo** | Permitir que o usuário gerencie os dispositivos vinculados à sua conta Gmail |
| **Contexto** | **Local:** Menu lateral de usuário <br>**Pré-condição:** O usuário deve estar logado em uma conta Google e ter outros dispositivos vinculados  |
| **Atores** | Usuário |
| **Recursos** | Dispositivo compatível (celular, tablet ou computador) com acesso à Play Store |
| **Episódios** |  |
| **Restrições** | Necessidade de conexão com a internet |
| **Exceções** | Erro de Conexão<br>Falha ao Atualizar Lista de Dispositivos |
| **Rastreabilidade** | [REQ49](../elicitacao/elicitacao.md#REQ49) |

## Cenário 020 - Gerenciamento de Aplicativos, Livros e Filmes Vinculados

|  |  |
|----------------|--------------------------------------------------------------------------------------------|
| **Objetivo**   | Permitir que o usuário gerencie aplicativos, livros e filmes vinculados à sua conta Gmail. |
| **Contexto**   | **Local:** Aplicativo móvel <br> **Pré-condição:** O usuário está logado e possui aplicativos, livros ou filmes vinculados à sua conta. |
| **Atores**     | Usuário |
| **Recursos**   | Dispositivo compatível (celular, tablet ou computador) com acesso à Play Store |
| **Episódios**  | 1. O usuário acessa a seção de "Gerenciamento de Aplicativos, Livros e Filmes"<br> 2. O aplicativo exibe uma lista de mídias vinculadas. <br> 3. O usuário visualiza, remove ou atualiza mídias conforme necessário. <br> 4. O aplicativo salva as alterações. |
| **Restrições** | Necessidade de conexão com a internet |
| **Exceções**   | Erro de Conexão<br> Falha ao Atualizar Lista de Mídias |
| **Rastreabilidade** | [REQ29](../elicitacao/elicitacao.md#REQ29) |


## Cenário 021 - Controle de Histórico de Comentários e Avaliações

|  |  |
|----------------|------------------------------------------------------------------------------------------------|
| **Objetivo**   | Permitir que o usuário controle o histórico de comentários e avaliações feitos pelo Gmail. |
| **Contexto**   | **Local:** Aplicativo móvel <br> **Pré-condição:** O usuário está logado e já fez comentários ou avaliações vinculados à conta. |
| **Atores**     | Usuário |
| **Recursos**   | Dispositivo compatível (celular, tablet ou computador) com acesso à Play Store |
| **Episódios**  | 1. O usuário acessa a seção de "Histórico de Comentários e Avaliações". <br> 2. O aplicativo exibe a lista de comentários e avaliações feitos. <br> 3. O usuário visualiza ou remove comentários/avaliações conforme necessário. <br> 4. O aplicativo salva as alterações. |
| **Restrições** | Necessidade de conexão com a internet |
| **Exceções**   | Erro de Conexão<br> Falha ao Atualizar Lista de Comentários |
| **Rastreabilidade** | [REQ50](../elicitacao/elicitacao.md#REQ50) |


## Cenário 022 - Manutenção de Formas de Pagamento

|  |  |
|----------------|-------------------------------------------------------------------------|
| **Objetivo**   | Permitir que o usuário mantenha salvas as formas de pagamento da conta. |
| **Contexto**   | **Local:** Aplicativo móvel <br> **Pré-condição:** O usuário está logado e possui formas de pagamento vinculadas à conta. |
| **Atores**     | Usuário |
| **Recursos**   | Dispositivo compatível (celular, tablet ou computador) com acesso à Play Store |
| **Episódios**  | 1. O usuário acessa a seção de "Formas de Pagamento". <br> 2. O aplicativo exibe as formas de pagamento salvas. <br> 3. O usuário adiciona, remove ou atualiza uma forma de pagamento. <br> 4. O aplicativo comunica as alterações aos servidores de pagamento do Google. <br> 5. O aplicativo confirma as alterações. |
| **Restrições** | Necessidade de conexão com a internet |
| **Exceções**   | Erro de Conexão<br> Falha ao Comunicar com Servidores de Pagamento |
| **Rastreabilidade** | [REQ18](../elicitacao/elicitacao.md#REQ18) |


## Cenário 023 - Configurações Personalizadas para Cada Conta

|  |  |
|----------------|------------------------------------------------------------------------------------------------|
| **Objetivo**   | Permitir que o usuário personalize configurações específicas para cada conta Google vinculada. |
| **Contexto**   | **Local:** Aplicativo móvel <br> **Pré-condição:** O usuário está logado com múltiplas contas Google. |
| **Atores**     | Usuário |
| **Recursos**   | Dispositivo compatível (celular, tablet ou computador) com acesso à Play Store |
| **Episódios**  | 1. O usuário acessa a seção de "Configurações". <br> 2. O aplicativo exibe as configurações disponíveis para a conta atual. <br> 3. O usuário ajusta as configurações conforme necessário. <br> 4. O aplicativo salva as alterações. |
| **Restrições** | Necessidade de conexão com a internet |
| **Exceções**   | Erro de Conexão<br> Falha ao Salvar Configurações |
| **Rastreabilidade** | [REQ58](../elicitacao/elicitacao.md#REQ58) |


## Cenário 024 - Notificações no App e via Gmail

|  |  |
|----------------|------------------------------------------------------------------------------------|
| **Objetivo**   | Notificar o usuário tanto no aplicativo quanto via Gmail sobre eventos importantes. |
| **Contexto**   | **Local:** Aplicativo móvel <br> **Pré-condição:** O usuário está logado no aplicativo e possui notificações habilitadas. |
| **Atores**     | Usuário |
| **Recursos**   | Dispositivo compatível (celular, tablet ou computador) com acesso à Play Store |
| **Episódios**  | 1. Um evento importante ocorre (ex.: atualização de segurança). <br> 2. O aplicativo gera uma notificação. <br> 3. O usuário recebe a notificação no aplicativo. <br> 4. O usuário também recebe um e-mail de notificação via Gmail. |
| **Restrições** | Necessidade de conexão com a internet, Notificações devem estar habilitadas. |
| **Exceções**   | Erro de Conexão<br> Notificação não Enviada |
| **Rastreabilidade** | [REQ51](../elicitacao/elicitacao.md#REQ51) |


## Cenário 025 - Gerenciamento de Benefícios e Ferramentas da Play Store

|  |  |
|----------------|---------------------------------------------------------------------------------------------------------------|
| **Objetivo**   | Permitir que o usuário gerencie os benefícios e ferramentas disponíveis para a Play Store vinculadas ao Gmail. |
| **Contexto**   | **Local:** Aplicativo móvel <br> **Pré-condição:** O usuário está logado e tem acesso à Play Store. |
| **Atores**     | Usuário |
| **Recursos**   | Dispositivo compatível (celular, tablet ou computador) com acesso à Play Store |
| **Episódios**  | 1. O usuário acessa a seção de "Benefícios e Ferramentas da Play Store". <br> 2. O aplicativo exibe os benefícios e ferramentas disponíveis. <br> 3. O usuário seleciona ou gerencia benefícios conforme necessário. <br> 4. O aplicativo salva as alterações. |
| **Restrições** | Necessidade de conexão com a internet |
| **Exceções**   | Erro de Conexão<br> Falha ao Atualizar Benefícios |
| **Rastreabilidade** | [REQ59](../elicitacao/elicitacao.md#REQ59) |


## Cenário 026 - Contato com Suporte

|  |  |
|----------------|-----------------------------------------------------------------------|
| **Objetivo**   | Permitir que o usuário contate o suporte diretamente pelo aplicativo. |
| **Contexto**   | **Local:** Aplicativo móvel <br> **Pré-condição:** O usuário está logado e precisa de assistência. |
| **Atores**     | Usuário |
| **Recursos**   | Dispositivo compatível (celular, tablet ou computador) com acesso à Play Store |
| **Episódios**  | 1. O usuário acessa a seção de "Suporte". <br> 2. O aplicativo exibe as opções de contato com o suporte. <br> 3. O usuário escolhe uma opção de contato (chat, e-mail, telefone). <br> 4. O usuário descreve seu problema. <br> 5. O suporte técnico responde e auxilia o usuário. |
| **Restrições** | Necessidade de conexão com a internet |
| **Exceções**   | Erro de Conexão<br> Falha ao Contatar Suporte |
| **Rastreabilidade** | [REQ32](../elicitacao/elicitacao.md#REQ32) |


## Cenário 027 - Configurações de Acessibilidade

|  |  |
|----------------|----------------------------------------------------------------------------------------|
| **Objetivo**   | Permitir que o usuário ajuste configurações de acessibilidade associadas ao seu perfil. |
| **Contexto**   | **Local:** Aplicativo móvel <br> **Pré-condição:** O usuário precisa de ajustes de acessibilidade. |
| **Atores**     | Usuário |
| **Recursos**   | IDispositivo compatível (celular, tablet ou computador) com acesso à Play Store |
| **Episódios**  | 1. O usuário acessa a seção de "Acessibilidade". <br> 2. O aplicativo exibe as configurações disponíveis. <br> 3. O usuário ajusta as configurações conforme necessário. <br> 4. O aplicativo salva as alterações. |
| **Restrições** | Necessidade de conexão com a internet |
| **Exceções**   | Erro de Conexão<br> Falha ao Salvar Configurações |
| **Rastreabilidade** | [REQ33](../elicitacao/elicitacao.md#REQ33) |


## Cenário 028 - Configurações de Preferências

|  |  |
|----------------|----------------------------------------------------------------|
| **Objetivo**   | Permitir que o usuário ajuste suas preferências no aplicativo. |
| **Contexto**   | **Local:** Aplicativo móvel <br> **Pré-condição:** O usuário está logado e deseja personalizar suas preferências. |
| **Atores**     | Usuário |
| **Recursos**   | Dispositivo compatível (celular, tablet ou computador) com acesso à Play Store |
| **Episódios**  | 1. O usuário acessa a seção de "Preferências". <br> 2. O aplicativo exibe as opções de personalização. <br> 3. O usuário ajusta suas preferências conforme necessário. <br> 4. O aplicativo salva as alterações. |
| **Restrições** | Necessidade de conexão com a internet |
| **Exceções**   | Erro de Conexão<br> Falha ao Salvar Preferências |
| **Rastreabilidade** | [REQ58](../elicitacao/elicitacao.md#REQ58) |


## Histórico de Versões

| **Versão** | **Data** | **Alterações Principais** | **Autor** |
| :--: | :--: | :--: | :--: | 
| 1.0.0 | 29-07-2024 | Lançamento inicial dos cenarios | Cecília Quaresma e Hugo Queiroz |
| 1.1.0 | 12-08-2024 | Criação dos cenários de 4 a 6 | Cecília Quaresma e Hugo Queiroz |
| 1.1.1 | 14-08-2024 | Criação do cenário 7 | Cecília Quaresma e Hugo Queiroz |
| 1.1.2 | 14-08-2024 | Junção dos cenários | Cecília Quaresma, Hugo Queiroz, Carlos Alves e Larissa Vieira |
| 1.1.3 | 15-08-2024 | Atualizando rastreabilidade | Hugo Queiroz e Carlos Alves |
| 1.1.4 | 15-08-2024 | Criação dos cenários de 14 a 28 | Arthur Ribeiro  |
| 1.1.5 | 15-08-2024 | Atualização da rastreabilidade | Arthur Ribeiro, Hugo Queiroz e Carlos Alves |

