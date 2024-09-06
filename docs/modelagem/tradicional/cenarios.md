# [Cenários](tradicional.md#cenarios)

Esta técnica esta definida em [cenários](tradicional.md#cenarios)

## Resultado da técnica

Para esta técnica dividimos os requistos priorizados como must em [requisitos elicitados](../../elicitacao/elicitacao.md), e cada equipe definida em [projeto](../../home/home.md#moscow) ficou resposável por modelar alguns cenários baseados nos requistos divididos.

## Cenário 001 - Buscando [app](lexico.md#app)

|  |  |
|--------------|--------------------------------|
| **Objetivo** | Encontrar um [app](lexico.md#app) pré-determinado |
| **Contexto** | **Local:** [tela inicial](lexico.md#tela-inicial) da Play Store<br>**Pré-condição:** Saber o nome do [app](lexico.md#app)  desejado |
| **Atores** | [usuário](lexico.md#usuario) |
| **Recursos** | [dispositivo compatível](lexico.md#dispositivo-compatível) (celular, tablet ou computador) com acesso à Play Store |
| **Episódios** | 1. O [usuário](lexico.md#usuario) abre a Play Store.<br>2. O [usuário](lexico.md#usuario) [clica](lexico.md#clicar) na [barra de pesquisa](lexico.md#barra-de-pesquisa).<br>3. O [usuário](lexico.md#usuario) escolhe entre [busca por voz](lexico.md#buscar-por-voz) ou [texto](lexico.md#buscar-por-texto).<br>4. O [usuário](lexico.md#usuario) digita/fala o nome do [app](lexico.md#app)   desejado.<br>5. O [usuário](lexico.md#usuario) [clica](lexico.md#clicar) no [app](lexico.md#app)   encontrado.<br> |
| **Restrições** | Digitar o nome do [app](lexico.md#app)   corretamente.<br>Espaço de armazenamento suficiente.<br>Ter conexão com a internet |
| **Exceções** | O [app](lexico.md#app)   não está disponível na Play Store.<br>O [app](lexico.md#app)   não é compatível com o dispositivo.<br>Falha na [rede](lexico.md#rede)  ao instalar |
| **Rastreabilidade** | [REQ01](../../../elicitacao/elicitacao.md#REQ01) |

---

## Cenário 002 - Buscando [app](lexico.md#app)   por categoria

|  |  |
|--------------|--------------------------------|
| **Objetivo** | Encontrar um [app](lexico.md#app) para aprender idiomas |
| **Contexto** | **Local:** [tela inicial](lexico.md#tela-inicial) da Play Store<br>**Pré-condição:** Ter interesse em aprender idiomas |
| **Atores** | [usuário](lexico.md#usuario) |
| **Recursos** | [dispositivo compatível](lexico.md#dispositivo-compatível) (celular, tablet ou computador) com acesso à Play Store |
| **Episódios** | 1. O [usuário](lexico.md#usuario) abre a Play Store.<br>2. O [usuário](lexico.md#usuario) rola pela página principal.<br>3. O [usuário](lexico.md#usuario) encontra a categoria desejada - Educação.<br>4. O [usuário](lexico.md#usuario) procura os [apps](lexico.md#app)  mais [bem avaliados](lexico.md#bem-avaliados).<br>5. O [usuário](lexico.md#usuario) analisa a [descrição do app](lexico.md#descrição-do-app). |
| **Restrições** | Espaço de armazenamento suficiente.<br>Ter conexão com a internet |
| **Exceções** | O [usuário](lexico.md#usuario) não se agradou com nenhuma das opções.<br>Falha na [rede](lexico.md#rede)  ao instalar |
| **Rastreabilidade** | [REQ01](../../elicitacao/elicitacao.md#REQ01) |

---

## Cenário 003 - Navegando pela Play Store

|  |  |
|--------------|--------------------------------|
| **Objetivo** | Buscar alguma [novidade](lexico.md#novidade) na Play Store |
| **Contexto** | **Local:** [tela inicial](lexico.md#tela-inicial) da Play Store<br>**Pré-condição:** Interesse em explorar novos [apps](lexico.md#app)  |
| **Atores** | [usuário](lexico.md#usuario) |
| **Recursos** | [dispositivo compatível](lexico.md#dispositivo-compatível) (celular, tablet ou computador) com acesso à Play Store |
| **Episódios** | 1. O [usuário](lexico.md#usuario) abre a Play Store.<br>2. O [usuário](lexico.md#usuario) [clica](lexico.md#clicar) na [aba](lexico.md#aba) ["Em Alta"](lexico.md#em-alta).<br>3. O [usuário](lexico.md#usuario) [clica](lexico.md#clicar) nas primeiras opções de [apps](lexico.md#app) .<br>4. O [usuário](lexico.md#usuario) lê a [descrição](lexico.md#descrição-do-app).<br>5. O [usuário](lexico.md#usuario) decide baixar um [app](lexico.md#app)  para testar. |
| **Restrições** | Espaço de armazenamento suficiente.<br>Ter conexão com a internet |
| **Exceções** | Falha na [rede](lexico.md#rede)  ao navegar. <br>O [dispositivo](lexico.md#dispositivo-compativel) trava devido a algum problema externo (consumo de memória, aumento de temperatura, etc) |
| **Rastreabilidade** | [REQ01](../../elicitacao/elicitacao.md#REQ01) |

---

## Cenário 004 - Instalando um jogo/[app](lexico.md#app)  pago

|  |  |
|--------------|--------------------------------|
| **Objetivo** | Instalar Minecraft |
| **Contexto** | **Local:** Tela do [app](lexico.md#app)   /jogo<br>**Pré-condição:** Saber o nome do [app](lexico.md#app) /jogo |
| **Atores** | [usuário](lexico.md#usuario) |
| **Recursos** | [dispositivo compatível](lexico.md#dispositivo-compatível) (celular, tablet ou computador) com acesso à Play Store |
| **Episódios** | 1. O usuário segue os episódios do [cenário 001](#cenário-001---buscando-app). <br> 2. O [usuário](lexico.md#usuario) [clica](lexico.md#clicar) no [botão de instalar](lexico.md#botão-de-instalar).<br>3. O [usuário](lexico.md#usuario) confirma a [forma de pagamento](lexico.md#forma-de-pagamento) .<br>4. O [usuário](lexico.md#usuario) autoriza a compra.<br>5. O [usuário](lexico.md#usuario) espera o jogo ser instalado. |
| **Restrições** | Memória disponível.<br>Bateria suficiente.<br>[forma de pagamento](lexico.md#forma-de-pagamento)  válida.<br>Acesso à internet |
| **Exceções** | Saldo insuficiente na [forma de pagamento](lexico.md#forma-de-pagamento) .<br>Memória insuficiente.<br>Bateria do dispositivo acaba antes da instalação |
| **Rastreabilidade** | [REQ02](../../elicitacao/elicitacao.md#REQ02) |

---

## Cenário 005 - Atualizando um jogo/[app](lexico.md#app)   

|  |  |
|--------------|--------------------------------|
| **Objetivo** | [atualizar](lexico.md#atualizar) o [app](lexico.md#app)     ou jogo para sua versão mais recente |
| **Contexto** | **Local:** Tela do [app](lexico.md#app)   /jogo<br>**Pré-condição:** Saber se há atualizações |
| **Atores** | [usuário](lexico.md#usuario) |
| **Recursos** | [dispositivo compatível](lexico.md#dispositivo-compatível) (celular, tablet ou computador) com acesso à Play Store |
| **Episódios** | 1. O usuário segue os episódios do [cenário 001](#cenário-001---buscando-app).<br>2. O [usuário](lexico.md#usuario) [clica](lexico.md#clicar) no botão de [atualizar](lexico.md#atualizar).<br>3. O [usuário](lexico.md#usuario) espera o jogo ser atualizado. |
| **Restrições** | Memória disponível.<br>Bateria suficiente.<br>Acesso à internet |
| **Exceções** | Memória insuficiente.<br>Bateria do dispositivo acaba antes da instalação.<br>Não ter atualização |
| **Rastreabilidade** | [REQ03](../../elicitacao/elicitacao.md#REQ03) |

---

## Cenário 006 - [desinstalar](lexico.md#desinstalar) um jogo/[app](lexico.md#app)   

|  |  |
|--------------|--------------------------------|
| **Objetivo** | [desinstalar](lexico.md#desinstalar) o Minecraft |
| **Contexto** | **Local:** Tela do [app](lexico.md#app)   /jogo<br>**Pré-condição:** Ter o [app](lexico.md#app)   /jogo já instalado |
| **Atores** | [usuário](lexico.md#usuario) |
| **Recursos** | [dispositivo compatível](lexico.md#dispositivo-compatível) (celular, tablet ou computador) com acesso à Play Store |
| **Episódios** | 1. O [usuário](lexico.md#usuario) abre a Play Store.<br> 2. O [usuário](lexico.md#usuario) segue os episódios do [cenário 001](#cenário-001---buscando-app). 3. O [usuário](lexico.md#usuario) [clica](lexico.md#clicar) no botão de [desinstalar](lexico.md#desinstalar) |
| **Restrições** | Ter um aplicativo instalado no dispositivo.<br>Bateria suficiente |
| **Exceções** | Bateria do dispositivo acaba antes da remoção.<br> O app/jogo foi instalado fora da Play Store e não pode ser removido. |
| **Rastreabilidade** | [REQ04](../../elicitacao/elicitacao.md#REQ04) |

---

## Cenário 007 - Pedir Reembolso de um [app](lexico.md#app)   /Jogo

|  |  |
|--------------|--------------------------------|
| **Objetivo** | Solicitar o reembolso do Minecraft |
| **Contexto** | **Local:** Tela de "Histórico de Compras" na Play Store<br>**Pré-condição:** O [app](lexico.md#app)   /jogo deve ter sido comprado recentemente e estar dentro do período permitido para solicitação de reembolso |
| **Atores** | [usuário](lexico.md#usuario) |
| **Recursos** | [dispositivo compatível](lexico.md#dispositivo-compatível) (celular, tablet ou computador) com acesso à Play Store e conexão à internet |
| **Episódios** | 1. O [usuário](lexico.md#usuario) abre o [app](lexico.md#app)     da Play Store no dispositivo.<br>2. O [usuário](lexico.md#usuario) acessa o menu e [clica](lexico.md#clicar) em "Pagamentos e assinaturas".<br>3. O [usuário](lexico.md#usuario) seleciona "Histórico de compras".<br>4. O [usuário](lexico.md#usuario) localiza o Minecraft na lista de compras.<br>5. O [usuário](lexico.md#usuario) [clica](lexico.md#clicar) no [app](lexico.md#app)   /jogo e escolhe a opção "Veja".<br>6. O [usuário](lexico.md#usuario) seleciona o motivo do reembolso e confirma a solicitação.<br>7. A Play Store processa o pedido e notifica o [usuário](lexico.md#usuario) sobre o status do reembolso. |
| **Restrições** | A solicitação deve ser feita dentro do prazo permitido para reembolso (geralmente 48 horas após a compra).<br> A solicitação não pode ser realizada se o app/jogo já foi reembolsado anteriormente. |
| **Exceções** | 1. O prazo para solicitar reembolso já expirou.<br>2. A Play Store rejeita o pedido devido a violações das políticas de reembolso. |
| **Rastreabilidade** | [REQ06](../../elicitacao/elicitacao.md#REQ06) |

---

## Cenário 008 - Acessar a política de privacidade de um [app](lexico.md#app)     ou jogo

|  |  |
|--------------|--------------------------------|
| **Objetivo** | Acessar a política de privacidade de um aplicativo ou jogo |
| **Contexto** | **Local:** Tela para instalar [app](lexico.md#app)   /jogo<br>**Tempo:** Aproximadamente 30 segundos<br>**Pré-condição:** Ter acesso à [rede](lexico.md#rede)  |
| **Atores** | [usuário](lexico.md#usuario) |
| **Recursos** | [dispositivo compatível](lexico.md#dispositivo-compatível) (celular, tablet ou computador) com acesso à Play Store |
| **Episódios** | 1. O [usuário](lexico.md#usuario) acessa a Play Store.<br>2. O [usuário](lexico.md#usuario) busca pelo [app](lexico.md#app)     ou jogo desejado.<br>3. O [usuário](lexico.md#usuario) [clica](lexico.md#clicar) no suporte do [app](lexico.md#app)   /jogo.<br>4. O [usuário](lexico.md#usuario) [clica](lexico.md#clicar) na opção "Política de Privacidade".<br>5. O sistema exibe a política de privacidade do [app](lexico.md#app)     ou jogo. |
| **Restrições** | A política de privacidade deve estar disponível em um formato legível.<br> É necessária conexão com a internet. |
| **Exceções** | Não ter o [app](lexico.md#app)   /jogo.<br> Falta de conexão com a [rede](lexico.md#rede).<br> Política de privacidade não disponível. |
| **Rastreabilidade** | [REQ06](../../elicitacao/elicitacao.md#REQ06) |

---

## Cenário 009 - Visualizar os Sistemas Operacionais Compatíveis

|  |  |
|--------------|--------------------------------|
| **Objetivo** | Ver quais sistemas operacionais um [app](lexico.md#app)     ou jogo pode ser executado. |
| **Contexto** | **Local:** Tela para instalar [app](lexico.md#app)   /jogo<br>**Tempo:** Aproximadamente 30 segundos<br>**Pré-condição:** Ter acesso à [rede](lexico.md#rede)  e ter o [app](lexico.md#app)     instalado |
| **Atores** | [usuário](lexico.md#usuario) |
| **Recursos** | [dispositivo compatível](lexico.md#dispositivo-compatível) (celular, tablet ou computador) com acesso à Play Store |
| **Episódios** | 1. O [usuário](lexico.md#usuario) acessa a Play Store.<br>2. O [usuário](lexico.md#usuario) busca pelo [app](lexico.md#app)     ou jogo desejado.<br>3. O [usuário](lexico.md#usuario) [clica](lexico.md#clicar) na página do [app](lexico.md#app)     ou jogo.<br>4. O [usuário](lexico.md#usuario) visualiza a seção "Sobre" do [app](lexico.md#app)   .<br>5. O sistema exibe os sistemas operacionais nos quais o [app](lexico.md#app)     ou jogo pode ser executado. |
| **Restrições** | As informações devem ser precisas e atualizadas.<br> É necessária conexão com a internet. |
| **Exceções** | Falta de conexão com a internet.<br> Informações de compatibilidade não disponíveis. |
| **Rastreabilidade** | [REQ07](../../elicitacao/elicitacao.md#REQ07) |

---

## Cenário 010 - Visualizar Data de Lançamento de um [app](lexico.md#app)     ou Jogo

|  |  |
|--------------|--------------------------------|
| **Objetivo** | Visualizar a data de lançamento de um [app](lexico.md#app)     ou jogo. |
| **Contexto** | **Local:** Tela para instalar [app](lexico.md#app)   /jogo<br>**Tempo:** Aproximadamente 30 segundos<br>**Pré-condição:** Ter acesso à [rede](lexico.md#rede)  e ter o [app](lexico.md#app)     instalado |
| **Atores** | [usuário](lexico.md#usuario) |
| **Recursos** | [dispositivo compatível](lexico.md#dispositivo-compatível) (celular, tablet ou computador) com acesso à Play Store |
| **Episódios** | 1. O [usuário](lexico.md#usuario) acessa a Play Store.<br>2. O [usuário](lexico.md#usuario) busca pelo [app](lexico.md#app)     ou jogo desejado.<br>3. O [usuário](lexico.md#usuario) [clica](lexico.md#clicar) na seção "Sobre" do [app](lexico.md#app)     ou jogo.<br>4. O [usuário](lexico.md#usuario) visualiza a data de lançamento do [app](lexico.md#app)     ou jogo. |
| **Restrições** | A data deve ser apresentada de forma clara e precisa. <br> É necessária conexão com a internet. |
| **Exceções** | Falta de conexão com a internet.<br> Data de lançamento não disponível. |
| **Rastreabilidade** | [REQ08](../../elicitacao/elicitacao.md#REQ08) |

---

## Cenário 011 - Mostrar Dados Extraídos pelo [app](lexico.md#app)     ou Jogo

|  |  |
|--------------|--------------------------------|
| **Objetivo** | Visualizar quais dados um [app](lexico.md#app)     ou jogo coleta dos [usuário](lexico.md#usuario). |
| **Contexto** | **Local:** Tela para instalar [app](lexico.md#app)   /jogo<br>**Tempo:** Aproximadamente 30 segundos<br>**Pré-condições:** O [usuário](lexico.md#usuario) deve estar conectado à internet. |
| **Atores** | [usuário](lexico.md#usuario) |
| **Recursos** | [dispositivo compatível](lexico.md#dispositivo-compatível) (celular, tablet ou computador) com acesso à Play Store |
| **Episódios** | 1. O [usuário](lexico.md#usuario) acessa a Play Store.<br>2. O [usuário](lexico.md#usuario) busca pelo [app](lexico.md#app)     ou jogo desejado.<br>3. O [usuário](lexico.md#usuario) [clica](lexico.md#clicar) na página do [app](lexico.md#app)     ou jogo.<br>4. O [usuário](lexico.md#usuario) acessa a seção de "Dados Coletados".<br>5. O sistema exibe quais dados são coletados pelo [app](lexico.md#app)     ou jogo. |
| **Restrições** | As informações devem ser claras e detalhadas.<br> É necessária conexão com a internet. |
| **Exceções** | Falta de conexão com a internet.<br> Informações sobre dados coletados não disponíveis. |
| **Rastreabilidade** | [REQ09](../../elicitacao/elicitacao.md#REQ09) |

---

## Cenário 012 - Mostrar [permissões](lexico.md#permissão)  do [app](lexico.md#app)     ou Jogo

|  |  |
|--------------|--------------------------------|
| **Objetivo** | Visualizar quais [permissões](lexico.md#permissão)  um [app](lexico.md#app)     ou jogo possui na máquina do [usuário](lexico.md#usuario). |
| **Contexto** | **Local:** Tela para instalar [app](lexico.md#app)   /jogo<br>**Tempo:** Aproximadamente 30 segundos<br>**Pré-condições:** O [usuário](lexico.md#usuario) deve estar conectado à internet. |
| **Atores** | [usuário](lexico.md#usuario) |
| **Recursos** | [dispositivo compatível](lexico.md#dispositivo-compatível) (celular, tablet ou computador) com acesso à Play Store |
| **Episódios** | 1. O [usuário](lexico.md#usuario) acessa a Play Store.<br>2. O [usuário](lexico.md#usuario) busca pelo [app](lexico.md#app)     ou jogo desejado.<br>3. O [usuário](lexico.md#usuario) [clica](lexico.md#clicar) na página do [app](lexico.md#app)     ou jogo.<br>4. O [usuário](lexico.md#usuario) acessa a seção de "[permissões](lexico.md#permissão) ".<br>5. O sistema exibe quais [permissões](lexico.md#permissão)  o [app](lexico.md#app)     ou jogo solicita. |
| **Restrições** | O [usuário](lexico.md#usuario) precisa ter acesso a internet. <br>As [permissões](lexico.md#permissão)  devem ser apresentadas de forma clara. |
| **Exceções** | Falta de conexão com a internet.<br>Informações sobre [permissões](lexico.md#permissão)  não disponíveis. |
| **Rastreabilidade** | [REQ10](../../elicitacao/elicitacao.md#REQ10) |

---

## Cenário 013 - Mostrar Uso dos Dados Extraídos

|  |  |
|--------------|--------------------------------|
| **Objetivo** | Visualizar o que um [app](lexico.md#app)     ou jogo faz com os dados que coleta dos [usuário](lexico.md#usuario). |
| **Contexto** | **Local:** Tela para instalar [app](lexico.md#app)   /jogo<br>**Tempo:** Aproximadamente 30 segundos<br>**Pré-condições:** O [usuário](lexico.md#usuario) deve estar conectado à internet. |
| **Atores** | [usuário](lexico.md#usuario) |
| **Recursos** | [dispositivo compatível](lexico.md#dispositivo-compatível) (celular, tablet ou computador) com acesso à Play Store |
| **Episódios** | 1. O [usuário](lexico.md#usuario) acessa a Play Store.<br>2. O [usuário](lexico.md#usuario) busca pelo [app](lexico.md#app)     ou jogo desejado.<br>3. O [&](lexico.md#usuario) [clica](lexico.md#clicar) na página do [app](lexico.md#app)     ou jogo.<br>4. O [usuário](lexico.md#usuario) acessa a seção de "Uso dos Dados".<br>5. O sistema exibe como os dados coletados são utilizados. |
| **Restrições** | O [usuário](lexico.md#usuario) precisa ter acesso a internet. <br>As informações devem ser detalhadas e transparentes. |
| **Exceções** | Falta de conexão com a internet.<br>Informações sobre uso dos dados não disponíveis. |
| **Rastreabilidade** | [REQ11](../../elicitacao/elicitacao.md#REQ11) |

## Cenário 014 - Criação de Conta Gmail

|  |  |
|--------------|--------------------------------|
| **Objetivo** | Permitir que o [usuário](lexico.md#usuario) crie uma nova conta Gmail através do aplicativo |
| **Contexto** | **Local:** Menu lateral de [usuário](lexico.md#usuario)<br>**Pré-condição:** Ter acesso à internet |
| **Atores** | [usuário](lexico.md#usuario) |
| **Recursos** | [dispositivo compatível](lexico.md#dispositivo-compatível) (celular, tablet ou computador) com acesso à Play Store |
| **Episódios** | 1. O [usuário](lexico.md#usuario) abre a Play Store.<br>2. O [usuário](lexico.md#usuario) [clica](lexico.md#clicar) no icone de foto do [usuário](lexico.md#usuario).<br>3. O [usuário](lexico.md#usuario) [clica](lexico.md#clicar) no botão de fazer login com o google.<br>4. O [usuário](lexico.md#usuario) insere as informações necessárias no formulário.<br> 5. O [usuário](lexico.md#usuario) é redirecionado para a [tela inicial](lexico.md#tela-inicial) logado na nova conta.|
| **Restrições** | Ter conexão com a internet<br>As informações inseridas pelo [usuário](lexico.md#usuario) devem atender |
| **Exceções** | Erro de conexão<br>Informações fornecidas são inválidas<br>Os dados informados estão indisponíveis |
| **Rastreabilidade** | [REQ19](../../elicitacao/elicitacao.md#REQ19) |

## Cenário 015 - Login com Conta Google Existente

|  |  |
|--------------|--------------------------------|
| **Objetivo** | Permitir que o [usuário](lexico.md#usuario) faça login com uma conta Google existente |
| **Contexto** | **Local:** Menu lateral de [usuário](lexico.md#usuario)<br>**Pré-condição:** Ter acesso à internet e o [usuário](lexico.md#usuario) já possuir uma conta Google |
| **Atores** | [usuário](lexico.md#usuario) |
| **Recursos** | [dispositivo compatível](lexico.md#dispositivo-compatível) (celular, tablet ou computador) com acesso à Play Store |
| **Episódios** | 1. O [usuário](lexico.md#usuario) abre o aplicativo deslogado.<br>2. O [usuário](lexico.md#usuario) seleciona a opção "Criar conta Gmail".<br>3. O [usuário](lexico.md#usuario) insere suas credenciais.<br>4. Se os dados forem válidos, o [usuário](lexico.md#usuario) é redirecionado para a [tela inicial](lexico.md#tela-inicial) logado. |
| **Restrições** | Conexão com a internet.<br>Credenciais válidas. |
| **Exceções** | Erro de Conexão<br> Credenciais Incorretas |
| **Rastreabilidade** | [REQ14](../../elicitacao/elicitacao.md#REQ14) |


## Cenário 016 - Funcionalidade "Esqueci minha senha"

|  |  |
|--------------|--------------------------------|
| **Objetivo** | Permitir que o [usuário](lexico.md#usuario) recupere sua senha através da funcionalidade "Esqueci a senha" |
| **Contexto** | **Local:** Menu lateral de [usuário](lexico.md#usuario)<br>**Pré-condição:** Ter acesso à internet e o [usuário](lexico.md#usuario) já possuir uma conta Google  |
| **Atores** | [usuário](lexico.md#usuario) |
| **Recursos** | [dispositivo compatível](lexico.md#dispositivo-compatível) (celular, tablet ou computador) com acesso à Play Store |
| **Episódios** | 1. O [usuário](lexico.md#usuario) abre o aplicativo deslogado<br>2. O [usuário](lexico.md#usuario) seleciona a opção "Esqueci minha senha"<br> 3. O [usuário](lexico.md#usuario) segue os passos para recuperar sua senha<br>4. O Google valida as informações e permite que o [usuário](lexico.md#usuario) redefina sua senha |
| **Restrições** | Necessidade de conexão com a internet.<br>[usuário](lexico.md#usuario) deve fornecer informações corretas para a recuperação. |
| **Exceções** | Erro de Conexão<br>Falha na Verificação de Identidade |
| **Rastreabilidade** | [REQ31](../../elicitacao/elicitacao.md#REQ31) |

## Cenário 017 - Remoção de Contas Logadas

|  |  |
|--------------|--------------------------------|
| **Objetivo** | Permitir que o [usuário](lexico.md#usuario) remova contas Google logadas no aplicativo |
| **Contexto** | **Local:** Menu lateral de [usuário](lexico.md#usuario)<br>**Pré-condição:** Ter acesso à internet e o [usuário](lexico.md#usuario) ter várias contas Google logadas no aplicativo |
| **Atores** | [usuário](lexico.md#usuario) |
| **Recursos** | [dispositivo compatível](lexico.md#dispositivo-compatível) (celular, tablet ou computador) com acesso à Play Store |
| **Episódios** | 1. O [usuário](lexico.md#usuario) acessa a seção de "Gerenciamento de Contas". <br>2. O [usuário](lexico.md#usuario) seleciona a conta que deseja remover. <br>3. O aplicativo solicita confirmação para a remoção. <br>4. O [usuário](lexico.md#usuario) confirma. <br>5. O aplicativo desloga e remove a conta do dispositivo. |
| **Restrições** | Necessidade de conexão com a internet.<br>Confirmação do [usuário](lexico.md#usuario) para remoção. |
| **Exceções** | Erro de Conexão.<br>Falha ao Deslogar. |
| **Rastreabilidade** | [REQ16](../../elicitacao/elicitacao.md#REQ16) |


## Cenário 018 - Troca da Conta Principal

|  |  |
|--------------|--------------------------------|
| **Objetivo** | Permitir que o [usuário](lexico.md#usuario) troque a conta principal usada no dispositivo |
| **Contexto** | **Local:** Menu lateral de [usuário](lexico.md#usuario)<br>**Pré-condição:** Ter acesso à internet e o [usuário](lexico.md#usuario) ter mais de uma conta Google logada no dispositivo |
| **Atores** | [usuário](lexico.md#usuario) |
| **Recursos** | [dispositivo compatível](lexico.md#dispositivo-compatível) (celular, tablet ou computador) com acesso à Play Store |
| **Episódios** | 1. O [usuário](lexico.md#usuario) acessa a seção de "Gerenciamento de Contas". <br>2. O [usuário](lexico.md#usuario) seleciona a opção "Trocar conta principal". <br>3. O aplicativo exibe as contas logadas. <br>4. O [usuário](lexico.md#usuario) seleciona a nova conta principal. <br>5. O aplicativo confirma a troca e redefine a conta principal. |
| **Restrições** |  Necessidade de conexão com a internet. <br> O [usuário](lexico.md#usuario) precisa ter pelo menos duas contas logadas em seu dispositivo. |
| **Exceções** |  Erro de Conexão<br>Falha ao Redefinir Conta Principal|
| **Rastreabilidade** | [REQ17](../../elicitacao/elicitacao.md#REQ17) |

## Cenário 019 - Gerenciamento de Dispositivos Vinculados

|  |  |
|--------------|--------------------------------|
| **Objetivo** | Permitir que o [usuário](lexico.md#usuario) gerencie os dispositivos vinculados à sua conta Gmail |
| **Contexto** | **Local:** Menu lateral de [usuário](lexico.md#usuario) <br>**Pré-condição:** O [usuário](lexico.md#usuario) deve estar logado em uma conta Google e ter outros dispositivos vinculados  |
| **Atores** | [usuário](lexico.md#usuario) |
| **Recursos** | [dispositivo compatível](lexico.md#dispositivo-compatível) (celular, tablet ou computador) com acesso à Play Store |
| **Episódios** | 1. O [usuário](lexico.md#usuario) acessa a seção de "Gerenciar apps e dispositivos". <br>2. O [usuário](lexico.md#usuario) seleciona a opção "Sincronizar apps com os dispositivos". <br>3. O aplicativo exibe os dispositivos vinculados. <br>4. O aplicativo sincroniza os apps com dispositivos. |
| **Restrições** | Necessidade de conexão com a internet. <br>Estar conectado à Play Store com a mesma conta em seus dispositivos.|
| **Exceções** | Erro de Conexão<br>Falha ao [atualizar](lexico.md#atualizar) Lista de Dispositivos |
| **Rastreabilidade** | [REQ49](../../elicitacao/elicitacao.md#REQ49) |

## Cenário 020 - Gerenciamento de Aplicativos, Livros e Filmes Vinculados

|  |  |
|----------------|--------------------------------------------------------------------------------------------|
| **Objetivo**   | Permitir que o [usuário](lexico.md#usuario) gerencie aplicativos, livros e filmes vinculados à sua conta Gmail. |
| **Contexto**   | **Local:** Aplicativo móvel <br> **Pré-condição:** O [usuário](lexico.md#usuario) está logado e possui aplicativos, livros ou filmes vinculados à sua conta. |
| **Atores**     | [usuário](lexico.md#usuario) |
| **Recursos**   | [dispositivo compatível](lexico.md#dispositivo-compatível) (celular, tablet ou computador) com acesso à Play Store |
| **Episódios**  | 1. O [usuário](lexico.md#usuario) acessa a seção de "Gerenciamento de Aplicativos, Livros e Filmes"<br> 2. O aplicativo exibe uma lista de mídias vinculadas. <br> 3. O [usuário](lexico.md#usuario) visualiza, remove ou atualiza mídias conforme necessário. <br> 4. O aplicativo salva as alterações. |
| **Restrições** | Necessidade de conexão com a internet<br> Estar logado com a conta do Google |
| **Exceções**   | Erro de Conexão<br> Falha ao [atualizar](lexico.md#atualizar) Lista de Mídias |
| **Rastreabilidade** | [REQ29](../../elicitacao/elicitacao.md#REQ29) |


## Cenário 021 - Controle de Histórico de Comentários e Avaliações

|  |  |
|----------------|------------------------------------------------------------------------------------------------|
| **Objetivo**   | Permitir que o [usuário](lexico.md#usuario) controle o histórico de comentários e avaliações feitos pelo Gmail. |
| **Contexto**   | **Local:** Aplicativo móvel <br> **Pré-condição:** O [usuário](lexico.md#usuario) está logado e já fez comentários ou avaliações vinculados à conta. |
| **Atores**     | [usuário](lexico.md#usuario) |
| **Recursos**   | [dispositivo compatível](lexico.md#dispositivo-compatível) (celular, tablet ou computador) com acesso à Play Store |
| **Episódios**  | 1. O [usuário](lexico.md#usuario) acessa a seção de "Histórico de Comentários e Avaliações". <br> 2. O aplicativo exibe a lista de comentários e avaliações feitos. <br> 3. O [usuário](lexico.md#usuario) visualiza ou remove comentários/avaliações conforme necessário. <br> 4. O aplicativo salva as alterações. |
| **Restrições** | Necessidade de conexão com a internet<br> Estar logado com a conta do Google |
| **Exceções**   | Erro de Conexão<br> Falha ao [atualizar](lexico.md#atualizar) Lista de Comentários |
| **Rastreabilidade** | [REQ50](../../elicitacao/elicitacao.md#REQ50) |


## Cenário 022 - Manutenção de Formas de Pagamento

|  |  |
|----------------|-------------------------------------------------------------------------|
| **Objetivo**   | Permitir que o [usuário](lexico.md#usuario) mantenha salvas as formas de pagamento da conta. |
| **Contexto**   | **Local:** Aplicativo móvel <br> **Pré-condição:** O [usuário](lexico.md#usuario) está logado e possui formas de pagamento vinculadas à conta. |
| **Atores**     | [usuário](lexico.md#usuario) |
| **Recursos**   | [dispositivo compatível](lexico.md#dispositivo-compatível) (celular, tablet ou computador) com acesso à Play Store |
| **Episódios**  | 1. O [usuário](lexico.md#usuario) acessa a seção de "Formas de Pagamento". <br> 2. O aplicativo exibe as formas de pagamento salvas. <br> 3. O [usuário](lexico.md#usuario) adiciona, remove ou atualiza uma [forma de pagamento](lexico.md#forma-de-pagamento) . <br> 4. O aplicativo comunica as alterações aos servidores de pagamento do Google. <br> 5. O aplicativo confirma as alterações. |
| **Restrições** | Necessidade de conexão com a internet<br> Ter as informações dessas formas de pagamento|
| **Exceções**   | Erro de Conexão<br> Falha ao Comunicar com Servidores de Pagamento |
| **Rastreabilidade** | [REQ18](../../elicitacao/elicitacao.md#REQ18) |


## Cenário 023 - Configurações Personalizadas para Cada Conta

|  |  |
|----------------|------------------------------------------------------------------------------------------------|
| **Objetivo**   | Permitir que o [usuário](lexico.md#usuario) personalize configurações específicas para cada conta Google vinculada. |
| **Contexto**   | **Local:** Aplicativo móvel <br> **Pré-condição:** O [usuário](lexico.md#usuario) está logado com múltiplas contas Google. |
| **Atores**     | [usuário](lexico.md#usuario) |
| **Recursos**   | [dispositivo compatível](lexico.md#dispositivo-compatível) (celular, tablet ou computador) com acesso à Play Store |
| **Episódios**  | 1. O [usuário](lexico.md#usuario) acessa a seção de "Configurações". <br> 2. O aplicativo exibe as configurações disponíveis para a conta atual. <br> 3. O [usuário](lexico.md#usuario) ajusta as configurações conforme necessário. <br> 4. O aplicativo salva as alterações. |
| **Restrições** | Necessidade de conexão com a internet<br> Estar na conta desejada |
| **Exceções**   | Erro de Conexão<br> Falha ao Salvar Configurações |
| **Rastreabilidade** | [REQ58](../../elicitacao/elicitacao.md#REQ58) |


## Cenário 024 - Notificações no [app](lexico.md#app)  e via Gmail

|  |  |
|----------------|------------------------------------------------------------------------------------|
| **Objetivo**   | Notificar o [usuário](lexico.md#usuario) tanto no aplicativo quanto via Gmail sobre eventos importantes. |
| **Contexto**   | **Local:** Aplicativo móvel <br> **Pré-condição:** O [usuário](lexico.md#usuario) está logado no aplicativo e possui notificações habilitadas. |
| **Atores**     | [usuário](lexico.md#usuario) |
| **Recursos**   | [dispositivo compatível](lexico.md#dispositivo-compatível) (celular, tablet ou computador) com acesso à Play Store |
| **Episódios**  | 1. Um evento importante ocorre (ex.: atualização de segurança). <br> 2. O aplicativo gera uma notificação. <br> 3. O [usuário](lexico.md#usuario) recebe a notificação no aplicativo. <br> 4. O [usuário](lexico.md#usuario) também recebe um e-mail de notificação via Gmail. |
| **Restrições** | Necessidade de conexão com a internet<br> Notificações devem estar habilitadas. |
| **Exceções**   | Erro de Conexão<br> Notificação não Enviada |
| **Rastreabilidade** | [REQ51](../../elicitacao/elicitacao.md#REQ51) |


## Cenário 025 - Gerenciamento de Benefícios e Ferramentas da Play Store

|  |  |
|----------------|---------------------------------------------------------------------------------------------------------------|
| **Objetivo**   | Permitir que o [usuário](lexico.md#usuario) gerencie os benefícios e ferramentas disponíveis para a Play Store vinculadas ao Gmail. |
| **Contexto**   | **Local:** Aplicativo móvel <br> **Pré-condição:** O [usuário](lexico.md#usuario) está logado e tem acesso à Play Store. |
| **Atores**     | [usuário](lexico.md#usuario) |
| **Recursos**   | [dispositivo compatível](lexico.md#dispositivo-compatível) (celular, tablet ou computador) com acesso à Play Store |
| **Episódios**  | 1. O [usuário](lexico.md#usuario) acessa a seção de "Benefícios e Ferramentas da Play Store". <br> 2. O aplicativo exibe os benefícios e ferramentas disponíveis. <br> 3. O [usuário](lexico.md#usuario) seleciona ou gerencia benefícios conforme necessário. <br> 4. O aplicativo salva as alterações. |
| **Restrições** | Necessidade de conexão com a internet<br> Estar logado com a conta do Google |
| **Exceções**   | Erro de Conexão<br> Falha ao [atualizar](lexico.md#atualizar) Benefícios |
| **Rastreabilidade** | [REQ59](../../elicitacao/elicitacao.md#REQ59) |


## Cenário 026 - Contato com Suporte

|  |  |
|----------------|-----------------------------------------------------------------------|
| **Objetivo**   | Permitir que o [usuário](lexico.md#usuario) contate o suporte diretamente pelo aplicativo. |
| **Contexto**   | **Local:** Aplicativo móvel <br> **Pré-condição:** O [usuário](lexico.md#usuario) está logado e precisa de assistência. |
| **Atores**     | [usuário](lexico.md#usuario) |
| **Recursos**   | [dispositivo compatível](lexico.md#dispositivo-compatível) (celular, tablet ou computador) com acesso à Play Store |
| **Episódios**  | 1. O [usuário](lexico.md#usuario) acessa as suas configurações 2. O [usuário](lexico.md#usuario) acessa a seção de "Suporte" ou "Ajuda e feedback". <br> 3. O aplicativo exibe as opções de contato com o suporte. <br> 4. O [usuário](lexico.md#usuario) escolhe uma opção de contato (chat, e-mail, telefone). <br> 5. O [usuário](lexico.md#usuario) descreve seu problema. <br> 6. O suporte técnico responde e auxilia o [usuário](lexico.md#usuario). |
| **Restrições** | Necessidade de conexão com a internet<br> Estar logado com a conta do Google |
| **Exceções**   | Erro de Conexão<br> Falha ao Contatar Suporte |
| **Rastreabilidade** | [REQ32](../../elicitacao/elicitacao.md#REQ32) |


## Cenário 027 - Configurações de Acessibilidade

|  |  |
|----------------|----------------------------------------------------------------------------------------|
| **Objetivo**   | Permitir que o [usuário](lexico.md#usuario) ajuste configurações de acessibilidade associadas ao seu perfil. |
| **Contexto**   | **Local:** Aplicativo móvel <br> **Pré-condição:** O [usuário](lexico.md#usuario) precisa de ajustes de acessibilidade. |
| **Atores**     | [usuário](lexico.md#usuario) |
| **Recursos**   | I[dispositivo compatível](lexico.md#dispositivo-compatível) (celular, tablet ou computador) com acesso à Play Store |
| **Episódios**  | 1. O [usuário](lexico.md#usuario) acessa a seção de "Acessibilidade". <br> 2. O aplicativo exibe as configurações disponíveis. <br> 3. O [usuário](lexico.md#usuario) ajusta as configurações conforme necessário. <br> 4. O aplicativo salva as alterações. |
| **Restrições** | Necessidade de conexão com a internet<br> Estar logado com a conta conta do Google|
| **Exceções**   | Erro de Conexão<br> Falha ao Salvar Configurações |
| **Rastreabilidade** | [REQ33](../../elicitacao/elicitacao.md#REQ33) |


## Cenário 028 - Configurações de Preferências

|  |  |
|----------------|----------------------------------------------------------------|
| **Objetivo**   | Permitir que o [usuário](lexico.md#usuario) ajuste suas preferências no aplicativo. |
| **Contexto**   | **Local:** Aplicativo móvel <br> **Pré-condição:** O [usuário](lexico.md#usuario) está logado e deseja personalizar suas preferências. |
| **Atores**     | [usuário](lexico.md#usuario) |
| **Recursos**   | [dispositivo compatível](lexico.md#dispositivo-compatível) (celular, tablet ou computador) com acesso à Play Store |
| **Episódios**  | 1. O [usuário](lexico.md#usuario) acessa a seção de "Preferências". <br> 2. O aplicativo exibe as opções de personalização. <br> 3. O [usuário](lexico.md#usuario) ajusta suas preferências conforme necessário. <br> 4. O aplicativo salva as alterações. |
| **Restrições** | Necessidade de conexão com a internet<br> Estar logado com a conta do Google|
| **Exceções**   | Erro de Conexão<br> Falha ao Salvar Preferências |
| **Rastreabilidade** | [REQ58](../../elicitacao/elicitacao.md#REQ58) |


## Histórico de Versões

| **Versão** | **Data** | **Alterações Principais** | **Autor** |
| :--: | :--: | :--: | :--: | 
| 1.0.0 | 29-07-2024 | Lançamento inicial dos cenarios | Cecília Quaresma e Hugo Queiroz |
| 1.1.0 | 12-08-2024 | Criação dos cenários de 4 a 6 | Cecília Quaresma e Hugo Queiroz |
| 1.1.1 | 14-08-2024 | Criação do cenário 7 | Cecília Quaresma e Hugo Queiroz |
| 1.1.2 | 14-08-2024 | Junção dos cenários | Cecília Quaresma, Hugo Queiroz, Carlos Alves e Larissa Vieira |
| 1.1.3 | 15-08-2024 | Atualizando rastreabilidade | Hugo Queiroz e Carlos Alves |
| 1.1.4 | 15-08-2024 | Criação dos cenários de 14 a 28 | Arthur Ribeiro, Hugo Queiroz e Carlos Alves  |
| 1.1.5 | 15-08-2024 | Atualização da rastreabilidade | Arthur Ribeiro, Hugo Queiroz e Carlos Alves |
| 1.2.0 | 21-08-2024 | Adicionando os links para o léxico | Hugo Queiroz e Cecília Quaresma |
| 1.2.1 | 21-08-2024 | Arrumando organização | Hugo Queiroz e Carlos Alves |
| 2.0.0 | 06-09-2024 | Corrigindo cenários com base no checklist de análise | Arthur Ribeiro, Carlos Alves, Cecília Quaresma, Hugo Queiroz, Larissa Vieira e Lucas Queiroz |