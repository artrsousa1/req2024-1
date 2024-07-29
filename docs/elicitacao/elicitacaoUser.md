# Fluxo de Usuário
Na reunião realizada com a equipe no início do projeto, foi definida a categoria de fluxo de usuário. É possível verificar essa definição da categoria na [Home](../home/home.md), onde foi estabelecida a operações de entrada e saída na Play Store, desde a criação de um usuário até o remocão e o que fica vinculado e é oferecido a um usuário.

## Rich Picture:
Este é uma versão que tenta representar a Play Store na parte de fluxo de usuário

![alt text](../assets/RP-Fluxousuário.jpg)

*Autores: Carlos Alves & Larissa Vieira*


## Introspecção

A técnica de elicitação de requisitos conhecida como introspecção é um método reflexivo e autônomo utilizado por
analistas de sistemas para identificar e definir os requisitos de um projeto. Baseando-se em sua própria experiência,
conhecimento prévio e intuição, o analista realiza uma auto-reflexão profunda para imaginar como o sistema deve funcionar,
considerando diversos cenários de uso, possíveis problemas e soluções.

## Resultados da técnica

### Funcionalidades Gerais

1. Logar
2. Criar conta do Gmail
3. Autenficar usuários
4. Alterar e recuperar senha
5. Gerenciar as contas na Play Store
    -Trocar de conta
    -Remover conta

### Detalhes do Usuário

6. Mostrar informações do usário
    - Nome
    - Gmail Logado
    - Foto do Gmail
    - Ferramentas google associadas
    - Aplicativos, filmes e livros instaldos
    - Dispositivos logados
    - Formas de pagamento cadastradas

### Configurações personalizadas

7. Notificações
    - No aplicativo
    - No gmail
8. Acessibilidade
    - Cor
    - Atalhos de teclado
    - Leitor de telas
    - Contraste
9. Preferências
    - Atualizações automáticas
    - Abrir vídeos automaticamente
    - Preferências de Dowload
10. Configurações de segurança


### Notificações

28. Notificar usuário pelo Gmail logado

## Requisitos Identificados 

Após a aplicação das técnicas de Introspecção, foi possível identificar algumas necessidades e requisitos da Play Store:

1. O aplicativo deve ser capaz criar um usuário.
2. O aplicativo deve permitir o login de um usuário.
3. O aplicativo deve autenticar a senha ao fazer login.
4. O aplicativo deve fornecer acesso à funcionalidade aletrar e recuperar a senha.
5. O aplicativo deve permitir a saída de um usuário.
6. O aplicativo deve permitir a troca da conta principal utilizada no dispositivo.
7. O aplicativo deve permitir o gerenciamento de dispositivos.
8. O aplicativo deve permitir o gerenciamento de aplicativos, livros e filmes do usuário.
9. O aplicativo deve manter salvas as formas de pagamento do usuário.
10. O aplicativo deve notificar o usuário.
11. O aplicativo deve permitir configurações de acessibilidade associadas ao usuário.
12. O aplicativo deve permitir configurações de preferências associadas ao usuário.
13. O aplicativo deve permitir configurações de segurança associadas ao usuário.


## Observação

Para a elicitação do fluxo de usuário, foi decidido utilizar a técnica de observação. Esta técnica consiste no ato de observar o comportamento dos usuários para entender melhor suas interações e necessidades.

### Participativa
O observador se envolve nas atividades dos usuários, podendo fazer perguntas e interagir. Isso pode ser útil para obter insights mais profundos, mas pode influenciar o comportamento dos usuários.

#### Planejamento:
Foi definido o objetivo de verificar as opções de entrada e sáida de um usuário na Play Store, e as opções fornecidas.

#### Aplicação:

Para esta categoria, utilizamos o aplicativo da Play Store, que já vem instalado em dispositivos Android. Um membro da equipe utilizava o aplicativo enquanto outro observava e sugeria opções de interação. Esse método permitiu captar de forma mais precisa as dificuldades e necessidades dos usuários durante o uso do aplicativo.

1. Foi observado a criação de uma conta;
2. Foi observado o login com uma conta Google já criada;
3. Foi observado a remoção da conta logado;
4. Foi sugerido a interação com o esqueci a senha;
5. Foi Observado as opções de possivel acesso de um usuário após login.


### Passiva
O observador assiste às atividades dos usuários sem interferir ou interagir. Esse tipo de observação ajuda a capturar o comportamento natural dos usuários.

#### Planejamento:
Foi definido o objetivo de verificar as opções de entrada e sáida de um usuário na Play Store, e as opções fornecidas.

#### Aplicação:

Para esta categoria, utilizamos a plataforma Web da Play Store, em um Notebook da DELL com o sistema operacional Linux. Um membro da equipe utilizava o aplicativo enquanto outro observava. Esse método permitiu captar de forma mais precisa as dificuldades e necessidades dos usuários durante o uso do aplicativo.

1. Foi observado o login com uma conta Google já criada;
2. Foi observado a criação de uma conta;
3. Foi observado logar com conta nova
4. Foi observado os dispositivos vínculados ao usuário;
5. Foi observado a interação com o esqueci a senha;
6. Foi observada a alteração da senha;
7. Foi observado a saída do usuário logado;
8. Foi observado a troca de conta;
8. Foi Observado as opções de possivel acesso de um usuário após login.

## Requisitos Identificados

Após a aplicação das técnicas de observação passiva e participativa, foi possível identificar algumas necessidades e requisitos da Play Store:

1. O aplicativo deve ser capaz de fornecer a criação de uma conta Gmail (Google Email).
2. O aplicativo deve permitir o login com uma conta Google já existente.
3. O aplicativo deve autenticar a senha ao fazer login com uma conta.
4. O aplicativo deve fornecer acesso à funcionalidade "esqueci a senha" do Gmail.
5. O aplicativo deve permitir a remoção de contas logadas.
6. O aplicativo deve permitir a troca da conta principal utilizada no dispositivo.
7. O aplicativo deve permitir o gerenciamento de dispositivos vinculados ao Gmail.
8. O aplicativo deve permitir o gerenciamento de aplicativos, livros e filmes vinculados ao Gmail.
9. O aplicativo deve controlar o histórico de comentários e avaliações feitos pelo Gmail.
10. O aplicativo deve manter salvas as formas de pagamento da conta.
11. O aplicativo deve permitir configurações personalizadas para cada conta.
12. O aplicativo deve notificar o usuário tanto no próprio app quanto via Gmail.
13. O aplicativo deve gerenciar os benefícios e ferramentas disponíveis para a Play Store vinculadas ao Gmail.
14. O aplicativo deve permitir que o usuário contate o suporte.


[Vídeo da aplicação da observação participativa para fluxo de usuário - 29/07/2024 ](https://drive.google.com/file/d/14zwl-JOY5CvXEAeKr3mO2CzGhWw1dtTR/view?usp=sharing)

[Vídeo da aplicação da observação passiva  para fluxo de usuário - 29/07/2024 ](https://drive.google.com/file/d/1jvpGFrdahbgO5HJDbDx7uuUIqPxsxPoY/view?usp=sharing)


## Storytelling

Storytelling na elicitação de requisitos é uma técnica que utiliza narrativas para capturar e comunicar os requisitos de um sistema de forma mais clara e envolvente. Em vez de apenas listar especificações técnicas, o storytelling incorpora histórias e cenários que ilustram como o sistema será usado na prática. Isso ajuda a criar um entendimento mais profundo e compartilhado entre as partes interessadas, como desenvolvedores, clientes e usuários finais.

### Primeiro uso

Conta a narrativa de um menino que quer jogar e deseja facilidade na hora de logar na Play Store e comprar Minecraft.

![alt text](../assets/StoryUser.png)
*Autores: Carlos Alves & Larissa Vieira*



É possível fazer login rapidamente se já tiver uma conta Google e ter as formas de pagamento salvas nesta conta. Isso torna a utilização de um celular novo mais rápida, além de permitir o backup das compras e aplicativos instalados em dispositivos anteriores.

## Requisitos Identificados

Após a aplicação das técnicas de Storytelling, foi possível identificar algumas necessidades e requisitos da Play Store:

1. O aplicativo deve permitir a mudança de dispositivos de forma fácil, oferecendo backup e reinstalação de aplicativos, filmes e livros de uma conta Gmail.
2. O aplicativo deve permitir fazer login utilizando uma conta Google já criada.
3. O aplicativo deve salvar as formas de pagamento cadastradas.


# Requisitos elicitados de Fluxo de usuário
Após a análise das técnicas e artefatos gerados neste secção, elicitamos os seguintes requisitos.

| Código | Descrição                                                                                      | Técnica de elicitação |
| ------ | ---------------------------------------------------------------------------------------------- | --------------------- |
| REQ01  | O aplicativo deve ser capaz de fornecer a criação de uma conta Gmail (Google Email).          | Introspecção e Observação         |
| REQ02  | O aplicativo deve permitir o login com uma conta Google já existente.                        | Introspecção, Observação  e Storytelling        |
| REQ03  | O aplicativo deve autenticar a senha ao fazer login com uma conta.                            | Introspecção e Observação          |
| REQ04  | O aplicativo deve fornecer acesso à funcionalidade "esqueci a senha" do Gmail.                | Introspecção e Observação          |
| REQ05  | O aplicativo deve permitir a remoção de contas logadas.                                       | Introspecção e Observação          |
| REQ06  | O aplicativo deve permitir a troca da conta principal utilizada no dispositivo.               | Introspecção e Observação          |
| REQ07  | O aplicativo deve permitir o gerenciamento de dispositivos vinculados ao Gmail.                | Introspecção e Observação          |
| REQ08  | O aplicativo deve permitir o gerenciamento de aplicativos, livros e filmes vinculados ao Gmail. | Introspecção e Observação          |
| REQ09  | O aplicativo deve controlar o histórico de comentários e avaliações feitos pelo Gmail.         | Introspecção e Observação          |
| REQ10  | O aplicativo deve manter salvas as formas de pagamento da conta.                               | Introspecção, Observação e Storytelling         |
| REQ11  | O aplicativo deve permitir configurações personalizadas para cada conta.                      | Introspecção e Observação          |
| REQ12  | O aplicativo deve notificar o usuário tanto no próprio app quanto via Gmail.                  | Introspecção e Observação          |
| REQ13  | O aplicativo deve gerenciar os benefícios e ferramentas disponíveis para a Play Store vinculadas ao Gmail. | Introspecção e Observação          |
| REQ14  | O aplicativo deve permitir que o usuário contate o suporte.                                   | Introspecção e Observação          |
| REQ15  | O aplicativo deve permitir configurações de acessibilidade associadas ao usuário.             | Introspecção          |
| REQ16  | O aplicativo deve permitir configurações de preferências associadas ao usuário.               | Introspecção          |
| REQ17  | O aplicativo deve permitir configurações de segurança associadas ao usuário.                  | Introspecção          |
| REQ18  | O aplicativo deve permitir a mudança de dispositivos de forma fácil, oferecendo backup e reinstalação de aplicativos, filmes e livros de uma conta Gmail. | Storytelling         |



# Histórico de Versões

| Versão | Data       | Alterações Principais                             | Autor        |
|--------|------------|---------------------------------------------------|--------------|
| 1.0.0  | 29-07-2024 | Lançamento inicial da documentação.               | Carlos Alves, Larissa Vieira    |
|1.0.1  | 29-07-2024 | Adicionando técnica de Introspecção    | Carlos Alves, Larissa Vieira    |
|1.0.2  | 29-07-2024 | Adicionando técnica de Observação    | Carlos Alves, Larissa Vieira    |
|1.0.3  | 29-07-2024 | Adicionando técnica de Storytelling    | Carlos Alves, Larissa Vieira    |
|1.0.4  | 29-07-2024 | Concretizando Requisitos de Fluxo de usuário     | Carlos Alves, Larissa Vieira    |












