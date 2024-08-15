# Cenários

O método de cenários é uma técnica eficaz de elicitação e modelagem de requisitos que envolve a criação de narrativas detalhadas sobre como os usuários interagem com o sistema. Esses cenários descrevem situações reais e hipotéticas que capturam as necessidades, expectativas e comportamentos dos usuários.

## Resultado da técnica

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

## Histórico de Versões

| **Versão** | **Data** | **Alterações Principais** | **Autor** |
| :--: | :--: | :--: | :--: | 
| 1.0.0 | 29-07-2024 | Lançamento inicial dos cenarios | Cecília Quaresma e Hugo Queiroz |
| 1.1.0 | 12-08-2024 | Criação dos cenários de 4 a 6 | Cecília Quaresma e Hugo Queiroz |
| 1.1.1 | 14-08-2024 | Criação do cenário 7 | Cecília Quaresma e Hugo Queiroz |
| 1.1.2 | 14-08-2024 | Junção dos cenários | Cecília Quaresma, Hugo Queiroz, Carlos Alves e Larissa Vieira |
| 1.1.3 | 15-08-2024 | Atualizando rastreabilidade | Hugo Queiroz e Carlos Alves |


