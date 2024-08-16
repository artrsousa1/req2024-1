## Cenário 001 - Criação de Conta Gmail

| **Objetivo** | Permitir que o usuário crie uma nova conta Gmail através do aplicativo |
|--------------|--------------------------------|
| **Contexto** | **Local:** Menu lateral de usuário<br>**Pré-condição:** Ter acesso à internet |
| **Atores** | Usuário |
| **Recursos** | Dispositivo compatível (celular, tablet ou computador) com acesso à Play Store |
| **Episódios** | 1. O usuário abre a Play Store.<br>2. O usuário clica no icone de foto do usuário.<br>3. O usuário clica no botão de fazer login com o google.<br>4. O usuário insere as informações necessárias no formulário.<br> 5. O usuário é redirecionado para a tela inicial logado na nova conta.|
| **Restrições** | Ter conexão com a internet<br>As informações inseridas pelo usuário devem atender |
| **Exceções** | Erro de conexão<br>Informações fornecidas são inválidas<br>Os dados informados estão indisponíveis |

## Cenário 002 - Login com Conta Google Existente

| **Objetivo** | Permitir que o usuário faça login com uma conta Google existente |
|--------------|--------------------------------|
| **Contexto** | **Local:** Menu lateral de usuário<br>**Pré-condição:** Ter acesso à internet e o usuário já possuir uma conta Google |
| **Atores** | Usuário |
| **Recursos** | Dispositivo compatível (celular, tablet ou computador) com acesso à Play Store |
| **Episódios** | 1. O usuário abre o aplicativo deslogado.<br>2. O usuário seleciona a opção "Criar conta Gmail".<br>3. O usuário insere suas credenciais.<br>4. Se os dados forem válidos, o usuário é redirecionado para a tela inicial logado. |
| **Restrições** | Conexão com a internet.<br>Credenciais válidas. |
| **Exceções** | Erro de Conexão<br> Credenciais Incorretas|


## Cenário 003 - Funcionalidade "Esqueci minha senha"

| **Objetivo** | Permitir que o usuário recupere sua senha através da funcionalidade "Esqueci a senha" |
|--------------|--------------------------------|
| **Contexto** | **Local:** Menu lateral de usuário<br>**Pré-condição:** Ter acesso à internet e o usuário já possuir uma conta Google  |
| **Atores** | Usuário |
| **Recursos** | Dispositivo compatível (celular, tablet ou computador) com acesso à Play Store |
| **Episódios** | 1. O usuário abre o aplicativo deslogado<br>2. O usuário seleciona a opção "Esqueci minha senha"<br> 3. O usuário segue os passos para recuperar sua senha<br>4. O Google valida as informações e permite que o usuário redefina sua senha |
| **Restrições** | Necessidade de conexão com a internet.<br>Usuário deve fornecer informações corretas para a recuperação. |
| **Exceções** | Erro de Conexão<br>Falha na Verificação de Identidade |

## Cenário 004 - Remoção de Contas Logadas

| **Objetivo** | Permitir que o usuário remova contas Google logadas no aplicativo |
|--------------|--------------------------------|
| **Contexto** | **Local:** Menu lateral de usuário<br>**Pré-condição:** Ter acesso à internet e o usuário ter várias contas Google logadas no aplicativo |
| **Atores** | Usuário |
| **Recursos** | Dispositivo compatível (celular, tablet ou computador) com acesso à Play Store |
| **Episódios** | 1. O usuário acessa a seção de "Gerenciamento de Contas". <br>2. O usuário seleciona a conta que deseja remover. <br>3. O aplicativo solicita confirmação para a remoção. <br>4. O usuário confirma. <br>5. O aplicativo desloga e remove a conta do dispositivo. |
| **Restrições** | Necessidade de conexão com a internet.<br>Confirmação do usuário para remoção. |
| **Exceções** | Erro de Conexão.<br>Falha ao Deslogar. |


## Cenário 005 - Troca da Conta Principal

| **Objetivo** | Permitir que o usuário troque a conta principal usada no dispositivo |
|--------------|--------------------------------|
| **Contexto** | **Local:** Menu lateral de usuário<br>**Pré-condição:** Ter acesso à internet e o usuário ter mais de uma conta Google logada no dispositivo |
| **Atores** | Usuário |
| **Recursos** | Dispositivo compatível (celular, tablet ou computador) com acesso à Play Store |
| **Episódios** | 1. O usuário acessa a seção de "Gerenciamento de Contas". <br>2. O usuário seleciona a opção "Trocar conta principal". <br>3. O aplicativo exibe as contas logadas. <br>4. O usuário seleciona a nova conta principal. <br>5. O aplicativo confirma a troca e redefine a conta principal. |
| **Restrições** |  Necessidade de conexão com a internet. |
| **Exceções** |  Erro de Conexão<br>Falha ao Redefinir Conta Principal|

## Cenário 006 - Gerenciamento de Dispositivos Vinculados

| **Objetivo** | Permitir que o usuário gerencie os dispositivos vinculados à sua conta Gmail |
|--------------|--------------------------------|
| **Contexto** | **Local:** Menu lateral de usuário <br>**Pré-condição:** O usuário deve estar logado em uma conta Google e ter outros dispositivos vinculados  |
| **Atores** | Usuário |
| **Recursos** | Dispositivo compatível (celular, tablet ou computador) com acesso à Play Store |
| **Episódios** |  |
| **Restrições** | Necessidade de conexão com a internet |
| **Exceções** | Erro de Conexão<br>Falha ao Atualizar Lista de Dispositivos |

## Cenário 007 - Gerenciamento de Aplicativos, Livros e Filmes Vinculados

| **Objetivo**   | Permitir que o usuário gerencie aplicativos, livros e filmes vinculados à sua conta Gmail. |
|----------------|--------------------------------------------------------------------------------------------|
| **Contexto**   | **Local:** Aplicativo móvel <br> **Pré-condição:** O usuário está logado e possui aplicativos, livros ou filmes vinculados à sua conta. |
| **Atores**     | Usuário |
| **Recursos**   | Dispositivo compatível (celular, tablet ou computador) com acesso à Play Store |
| **Episódios**  | 1. O usuário acessa a seção de "Gerenciamento de Aplicativos, Livros e Filmes"<br> 2. O aplicativo exibe uma lista de mídias vinculadas. <br> 3. O usuário visualiza, remove ou atualiza mídias conforme necessário. <br> 4. O aplicativo salva as alterações. |
| **Restrições** | Necessidade de conexão com a internet |
| **Exceções**   | Erro de Conexão<br> Falha ao Atualizar Lista de Mídias |

---

## Cenário 008 - Controle de Histórico de Comentários e Avaliações

| **Objetivo**   | Permitir que o usuário controle o histórico de comentários e avaliações feitos pelo Gmail. |
|----------------|------------------------------------------------------------------------------------------------|
| **Contexto**   | **Local:** Aplicativo móvel <br> **Pré-condição:** O usuário está logado e já fez comentários ou avaliações vinculados à conta. |
| **Atores**     | Usuário |
| **Recursos**   | Dispositivo compatível (celular, tablet ou computador) com acesso à Play Store |
| **Episódios**  | 1. O usuário acessa a seção de "Histórico de Comentários e Avaliações". <br> 2. O aplicativo exibe a lista de comentários e avaliações feitos. <br> 3. O usuário visualiza ou remove comentários/avaliações conforme necessário. <br> 4. O aplicativo salva as alterações. |
| **Restrições** | Necessidade de conexão com a internet |
| **Exceções**   | Erro de Conexão<br> Falha ao Atualizar Lista de Comentários |

---

## Cenário 009 - Manutenção de Formas de Pagamento

| **Objetivo**   | Permitir que o usuário mantenha salvas as formas de pagamento da conta. |
|----------------|-------------------------------------------------------------------------|
| **Contexto**   | **Local:** Aplicativo móvel <br> **Pré-condição:** O usuário está logado e possui formas de pagamento vinculadas à conta. |
| **Atores**     | Usuário |
| **Recursos**   | Dispositivo compatível (celular, tablet ou computador) com acesso à Play Store |
| **Episódios**  | 1. O usuário acessa a seção de "Formas de Pagamento". <br> 2. O aplicativo exibe as formas de pagamento salvas. <br> 3. O usuário adiciona, remove ou atualiza uma forma de pagamento. <br> 4. O aplicativo comunica as alterações aos servidores de pagamento do Google. <br> 5. O aplicativo confirma as alterações. |
| **Restrições** | Necessidade de conexão com a internet |
| **Exceções**   | Erro de Conexão<br> Falha ao Comunicar com Servidores de Pagamento |

---

## Cenário 010 - Configurações Personalizadas para Cada Conta

| **Objetivo**   | Permitir que o usuário personalize configurações específicas para cada conta Google vinculada. |
|----------------|------------------------------------------------------------------------------------------------|
| **Contexto**   | **Local:** Aplicativo móvel <br> **Pré-condição:** O usuário está logado com múltiplas contas Google. |
| **Atores**     | Usuário |
| **Recursos**   | Dispositivo compatível (celular, tablet ou computador) com acesso à Play Store |
| **Episódios**  | 1. O usuário acessa a seção de "Configurações". <br> 2. O aplicativo exibe as configurações disponíveis para a conta atual. <br> 3. O usuário ajusta as configurações conforme necessário. <br> 4. O aplicativo salva as alterações. |
| **Restrições** | Necessidade de conexão com a internet |
| **Exceções**   | Erro de Conexão<br> Falha ao Salvar Configurações |

---

## Cenário 011 - Notificações no App e via Gmail

| **Objetivo**   | Notificar o usuário tanto no aplicativo quanto via Gmail sobre eventos importantes. |
|----------------|------------------------------------------------------------------------------------|
| **Contexto**   | **Local:** Aplicativo móvel <br> **Pré-condição:** O usuário está logado no aplicativo e possui notificações habilitadas. |
| **Atores**     | Usuário |
| **Recursos**   | Dispositivo compatível (celular, tablet ou computador) com acesso à Play Store |
| **Episódios**  | 1. Um evento importante ocorre (ex.: atualização de segurança). <br> 2. O aplicativo gera uma notificação. <br> 3. O usuário recebe a notificação no aplicativo. <br> 4. O usuário também recebe um e-mail de notificação via Gmail. |
| **Restrições** | Necessidade de conexão com a internet, Notificações devem estar habilitadas. |
| **Exceções**   | Erro de Conexão<br> Notificação não Enviada |

---

## Cenário 012 - Gerenciamento de Benefícios e Ferramentas da Play Store

| **Objetivo**   | Permitir que o usuário gerencie os benefícios e ferramentas disponíveis para a Play Store vinculadas ao Gmail. |
|----------------|---------------------------------------------------------------------------------------------------------------|
| **Contexto**   | **Local:** Aplicativo móvel <br> **Pré-condição:** O usuário está logado e tem acesso à Play Store. |
| **Atores**     | Usuário |
| **Recursos**   | Dispositivo compatível (celular, tablet ou computador) com acesso à Play Store |
| **Episódios**  | 1. O usuário acessa a seção de "Benefícios e Ferramentas da Play Store". <br> 2. O aplicativo exibe os benefícios e ferramentas disponíveis. <br> 3. O usuário seleciona ou gerencia benefícios conforme necessário. <br> 4. O aplicativo salva as alterações. |
| **Restrições** | Necessidade de conexão com a internet |
| **Exceções**   | Erro de Conexão<br> Falha ao Atualizar Benefícios |

---

## Cenário 013 - Contato com Suporte

| **Objetivo**   | Permitir que o usuário contate o suporte diretamente pelo aplicativo. |
|----------------|-----------------------------------------------------------------------|
| **Contexto**   | **Local:** Aplicativo móvel <br> **Pré-condição:** O usuário está logado e precisa de assistência. |
| **Atores**     | Usuário |
| **Recursos**   | Dispositivo compatível (celular, tablet ou computador) com acesso à Play Store |
| **Episódios**  | 1. O usuário acessa a seção de "Suporte". <br> 2. O aplicativo exibe as opções de contato com o suporte. <br> 3. O usuário escolhe uma opção de contato (chat, e-mail, telefone). <br> 4. O usuário descreve seu problema. <br> 5. O suporte técnico responde e auxilia o usuário. |
| **Restrições** | Necessidade de conexão com a internet |
| **Exceções**   | Erro de Conexão<br> Falha ao Contatar Suporte |

---

## Cenário 014 - Configurações de Acessibilidade

| **Objetivo**   | Permitir que o usuário ajuste configurações de acessibilidade associadas ao seu perfil. |
|----------------|----------------------------------------------------------------------------------------|
| **Contexto**   | **Local:** Aplicativo móvel <br> **Pré-condição:** O usuário precisa de ajustes de acessibilidade. |
| **Atores**     | Usuário |
| **Recursos**   | IDispositivo compatível (celular, tablet ou computador) com acesso à Play Store |
| **Episódios**  | 1. O usuário acessa a seção de "Acessibilidade". <br> 2. O aplicativo exibe as configurações disponíveis. <br> 3. O usuário ajusta as configurações conforme necessário. <br> 4. O aplicativo salva as alterações. |
| **Restrições** | Necessidade de conexão com a internet |
| **Exceções**   | Erro de Conexão<br> Falha ao Salvar Configurações |



## Cenário 015 - Configurações de Preferências

| **Objetivo**   | Permitir que o usuário ajuste suas preferências no aplicativo. |
|----------------|----------------------------------------------------------------|
| **Contexto**   | **Local:** Aplicativo móvel <br> **Pré-condição:** O usuário está logado e deseja personalizar suas preferências. |
| **Atores**     | Usuário |
| **Recursos**   | Dispositivo compatível (celular, tablet ou computador) com acesso à Play Store |
| **Episódios**  | 1. O usuário acessa a seção de "Preferências". <br> 2. O aplicativo exibe as opções de personalização. <br> 3. O usuário ajusta suas preferências conforme necessário. <br> 4. O aplicativo salva as alterações. |
| **Restrições** | Necessidade de conexão com a internet |
| **Exceções**   | Erro de Conexão<br> Falha ao Salvar Preferências |

