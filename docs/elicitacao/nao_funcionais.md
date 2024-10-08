# Requisitos não funcionais

Requisitos não funcionais referem-se a como o sistema deve operar. Eles definem as qualidades e restrições que o sistema deve atender.

Devido a abrager todo o sistema nesta aba não utilizaremos as categorias que vem sendo utilizado em todo resto do projeto definidas na [Home](../home/home.md).

## [Brainstorm](tecnicas.md#brainstorming)

Utilizamos a técnica descrita em [brainstorm](tecnicas.md#brainstorming), baseados nas categorias do FURPS e na ISO/IEC 25010. As categorias do FURPS são Funcionalidade, Usabilidade, Confiabilidade, Desempenho e Suportabilidade, e da ISO são Adequação Funcional, Eficiência de Performance, Compatibilidade, Usabilidade, Confiabilidade, Segurança, Manutenibilidade e Portabilidade. Porém, não fizemos os funcionais, pois já foram elicitados em [elictação](../elicitacao/elicitacao.md), e Manutenibilidade porque não temos acesso ao código do app.

![alt text](../assets/imagens/brainstormRNF.jpg)

*Autores: Carlos Alves & Hugo Queiroz*

Caso esteja ruim de ver, veja o resultado do brainstorm: [link](../assets/imagens/brainstorm_nao_func.pdf)

Após a técnica tiramos os requisitos parecidos e classificamos alguns que se qualificavam como funcionais.

## [NFR](../modelagem/GORE/gore.md#nfr-framework)

Em modelagem fizemos um [SIG](../modelagem/GORE/gore.md#nfr-framework) para modelarmos e elicitarmos requisitos não funcionais disponível em [NFR](../modelagem/GORE/nfrFramework.md).


### [Usabilidade](../modelagem/nfrFramework.md#Usabilidade)

| Código | Descrição | Técnica de elicitação |
| ------ | --------- | --------------------- |
| <a name="RNF01"></a> RNF01  | O Sistema deve ter uma hierarquia lógica de estruturação. | Brainstorm, NFR |
| <a name="RNF02"></a> RNF02  | O Sistema deve ser acessível para pessoas com deficiências. | Brainstorm, NFR |
| <a name="RNF03"></a> RNF03  | O Sistema deve ser acessível para pessoas idosas. | Brainstorm, NFR, [Storytelling App](apps.md#storytelling), [Storytelling fluxo de usuário](fluxo_usuario.md#storytelling) |
| <a name="RNF04"></a> RNF04  | O Sistema deve ser consistente e padronizado. | Brainstorm, NFR |
| <a name="RNF05"></a> RNF05  | O Sistema deve permitir descrição por áudio e atalhos de teclado. | Brainstorm, NFR |
| <a name="RNF06"></a> RNF06  | O Sistema deve ter cores contrastantes. | Brainstorm, NFR |
| <a name="RNF07"></a> RNF07  | O Sistema deve permitir configurações de acessibilidade como cor e fonte. | Brainstorm, NFR |
| <a name="RNF08"></a> RNF08  | O sistema deve se adaptar a vários tipos de telas. | Brainstorm, NFR |


### [Confiabilidade](../modelagem/nfrFramework.md#Confiabilidade)

| Código | Descrição | Técnica de elicitação |
| ------ | --------- | --------------------- |
| <a name="RNF09"></a> RNF09  | O sistema deve permitir a recuperação de falhas. | Brainstorm, NFR |
| <a name="RNF10"></a> RNF10  | O sistema deve garantir que os dados dos aplicativos e dos usuários sejam validados e armazenados com precisão para evitar corrupção ou perda de dados. | Brainstorm, NFR |
| <a name="RNF11"></a> RNF11  | O sistema deve prevenir erros. | Brainstorm, NFR |
| <a name="RNF12"></a> RNF12  | O sistema deve ter tolerência para com falhas. | Brainstorm, NFR |
| <a name="RNF13"></a> RNF13  | O sistema deve ficar no ar 24/7. | Brainstorm, NFR |
| <a name="RNF14"></a> RNF14  | O sistema deve realizar atualizações regulares e manutenção para corrigir bugs, melhorar a performance e manter a confiabilidade geral da plataforma. | Brainstorm, NFR |

### [Desempenho](../modelagem/nfrFramework.md#Desempenho)

| Código | Descrição | Técnica de elicitação |
| ------ | --------- | --------------------- |
| <a name="RNF15"></a> RNF15  | O sistema deve ser eficaz em diversos tipos de rede. | Brainstorm, NFR |
| <a name="RNF16"></a> RNF16  | O sistema deve lidar com picos de tráfego e alta demanda sem perder a disponibilidade. | Brainstorm, NFR |
| <a name="RNF17"></a> RNF17  | O sistema deve retornar o objeto de pesquisa rapidamente. | Brainstorm, NFR |
| <a name="RNF18"></a> RNF18  | O sistema deve garantir que as transações de compra e download de aplicativos sejam processadas rapidamente. | Brainstorm, NFR |
| <a name="RNF19"></a> RNF19  | O sistema deve otimizar o tempo de download e instalação de aplicativos. | Brainstorm, NFR |
| <a name="RNF20"></a> RNF20  | O sistema deve otimizar o uso dos recursos (rede, bateria e memória) do dispositivo. | Brainstorm, NFR |

### [Portabilidade](../modelagem/nfrFramework.md#Portabilidade)

| Código | Descrição | Técnica de elicitação |
| ------ | --------- | --------------------- |
| <a name="RNF21"></a> RNF21  | O sistema deve funcionar em qualquer dispositivo Android. | Brainstorm, NFR |
| <a name="RNF22"></a> RNF22  | O sistema deve funcionar bem em diversos navegadores. | Brainstorm, NFR |
| <a name="RNF23"></a> RNF23  | O sistema deve  assegurar que a Play Store funcione de maneira consistente em diferentes dispositivos e sistemas operacionais. | Brainstorm, NFR |

### [Segurança](../modelagem/nfrFramework.md#Segurança)

| Código | Descrição | Técnica de elicitação |
| ------ | --------- | --------------------- |
| <a name="RNF24"></a> RNF24  | O sistema deve ter medidas de segurança para proteger a plataforma contra ataques cibernéticos, malware e outras ameaças. | Brainstorm, NFR |
| <a name="RNF25"></a> RNF25  | O sistema deve garantir que os dados sensíveis do usuário sejam criptografados. | Brainstorm, NFR |
| <a name="RNF26"></a> RNF26  | O sistema deve garantir que as políticas de privacidade da Play Store e dos apps sejam disponibilizadas. | Brainstorm, NFR |
| <a name="RNF27"></a> RNF27  | O sistma deve informar os dados compartilhados com um app. | Brainstorm, NFR |
| <a name="RNF28"></a> RNF28  | O sistema deve seguir a LGPD. | Brainstorm, NFR |

### Requisitos Funcionais

| Código | Descrição | Técnica de elicitação | |
| ------ | --------- | --------------------- | - | 
| REQ01  | O sistema deve fornecer feedbacks para o usuário, como mensagens de erro. | Brainstorm, NFR |
| REQ02  | O sistema deve mostrar a localização do usuário dentro do app. | Brainstorm, NFR |
| REQ03  | O sistema deve mostrar botões para o usuário confirmar suas ações, evitando erros. | Brainstorm, NFR |
| REQ04  | O sistema deve permitir a mudança de idioma. | Brainstorm, NFR |
| REQ05  | O sistema deve ter um menu de ajuda. | Brainstorm, NFR |
| REQ07  | O sistema deve sincronizar dados de forma confiável entre diferentes dispositivos. | Brainstorm, NFR |
| REQ09  | O sistema não deve permitir que cadastrem apps maliciosos (Play protect). | Brainstorm, NFR |
| REQ10  | O sistema deve fornecer uma opção de backup. | Brainstorm, NFR |
| REQ11  | O sistema deve permitir a busca de apps/jogos por voz. | Brainstorm, NFR |


## Histórico de Versões

| **Versão** | **Data** | **Alterações Principais** | **Autor** |
| :--: | :--: | :--: | :--: | 
| 1.0.0 | 15-08-2024 | Lançamento inicial e aplicação do brainstorm | Carlos Alves e Hugo Queiroz |
| 1.0.1 | 16-08-2024 | Revisão dos requisitos e numeração | Carlos Alves, Cecília Quaresma e Hugo Queiroz |
| 1.0.2 | 20-08-2024 | Revisão dos requisitos e modelagem | Arthur Sousa, Carlos Alves, Cecília Quaresma, Larissa Vieira, Lucas Queiroz e Hugo Queiroz |
| 1.0.3 | 21-08-2024 | Ajuste do documento | Carlos Alves |
| 1.0.4 | 21-08-2024 | Adicionando ratreabilidade| Lucas Queiroz, Arthur Sousa, Carlos Alves e Larissa Vieira |