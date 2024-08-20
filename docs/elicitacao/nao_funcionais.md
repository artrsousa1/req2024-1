# Requisitos não funcionais

## [Brainstorm](tecnicas.md#brainstorming)

Utilizamos a técnica descrita em [brainstorm](tecnicas.md#brainstorming), baseados nas categorias do FURPS e na ISO/IEC 25010. As categorias do FURPS são Funcionalidade, Usabilidade, Confiabilidade, Desempenho e Suportabilidade, e da ISO são Adequação Funcional, Eficiência de Performance, Compatibilidade, Usabilidade, Confiabilidade, Segurança, Manutenibilidade e Portabilidade. Porém, não fizemos os funcionais, pois já foram elicitados em [elictação](../elicitacao/elicitacao.md), e Manutenibilidade porque não temos acesso ao código do app.

![alt text](../assets/imagens/brainstorm<a name="RNF"></a> RNF.jpg)

*Autores: Carlos Alves & Hugo Queiroz*

Caso esteja ruim de ver, veja o resultado do brainstorm: [link](../assets/imagens/brainstorm_nao_func.pdf)

Após a técnica tiramos os requisitos parecidos e classificamos alguns que se qualificavam como funcionias.

### Usabilidade

| Código | Descrição | Técnica de elicitação |
| ------ | --------- | --------------------- |
| <a name="RNF01"></a> RNF01  | O Sistema deve ter a hierarquia lógica das ideias. | Brainstorm |
| <a name="RNF02"></a> RNF02  | O Sistema deve ser acessível para pessoas com deficiências. | Brainstorm |
| <a name="RNF03"></a> RNF03  | O Sistema deve ser acessível para pessoas idosas. | Brainstorm |
| <a name="RNF04"></a> RNF04  | O Sistema deve ser consistente e padronizado. | Brainstorm |
| <a name="RNF05"></a> RNF05  | O Sistema deve permitir descrição por áudio e atalhos de teclado. | Brainstorm |
| <a name="RNF06"></a> RNF06  | O Sistema deve ter cores contrastantes. | Brainstorm |
| <a name="RNF07"></a> RNF07  | O Sistema deve permitir configurações de acessibilidade como cor e fonte. | Brainstorm |
| <a name="RNF08"></a> RNF08  | O sistema deve se adaptar a todo tipo de tela. | Brainstorm |


<!--iFrame de Usabilidade-->

<iframe width="768" height="432" src="https://miro.com/app/live-embed/uXjVKnuPv_U=/?moveToViewport=-1380,-539,4654,2341&embedId=227573380221" frameborder="0" scrolling="no" allow="fullscreen; clipboard-read; clipboard-write" allowfullscreen></iframe>

<!--iFrame de Desempenho-->

<iframe width="768" height="432" src="https://miro.com/app/live-embed/uXjVKnulZUk=/?moveToViewport=-2700,-847,4654,2341&embedId=795896470252" frameborder="0" scrolling="no" allow="fullscreen; clipboard-read; clipboard-write" allowfullscreen></iframe>

<!--iFrame de Confiabilidade-->

<iframe width="768" height="432" src="https://miro.com/app/live-embed/uXjVKnv71KM=/?moveToViewport=-3911,-572,4654,2341&embedId=579818778436" frameborder="0" scrolling="no" allow="fullscreen; clipboard-read; clipboard-write" allowfullscreen></iframe>

<!--iFrame de Segurança-->

<iframe width="768" height="432" src="https://miro.com/app/live-embed/uXjVKoNUl54=/?moveToViewport=-5053,-958,4654,2341&embedId=282149109656" frameborder="0" scrolling="no" allow="fullscreen; clipboard-read; clipboard-write" allowfullscreen></iframe>

<!--iFrame de Portabilidade-->

<iframe width="768" height="432" src="https://miro.com/app/live-embed/uXjVKnuJcj4=/?moveToViewport=-3084,-573,2178,1095&embedId=248809276064" frameborder="0" scrolling="no" allow="fullscreen; clipboard-read; clipboard-write" allowfullscreen></iframe>


### Confiabilidade

| Código | Descrição | Técnica de elicitação |
| ------ | --------- | --------------------- |
| <a name="RNF09"></a> RNF09  | O sistema deve permitir a recuperação de falhas. | Brainstorm |
| <a name="RNF10"></a> RNF10  | O sistema deve garantir que os dados dos aplicativos e dos usuários sejam validados e armazenados com precisão para evitar corrupção ou perda de dados. | Brainstorm |
| <a name="RNF11"></a> RNF11  | O sistema deve prevenir erros. | Brainstorm |
| <a name="RNF11"></a> RNF11  | O sistema deve realizar a prevenção de falhas. | Brainstorm |
| <a name="RNF12"></a> RNF12  | O sistema deve ficar no ar 24/7. | Brainstorm |
| <a name="RNF13"></a> RNF13  | O sistema deve realizar atualizações regulares e manutenção para corrigir bugs, melhorar a performance e manter a confiabilidade geral da plataforma. | Brainstorm |

### Desempenho

| Código | Descrição | Técnica de elicitação |
| ------ | --------- | --------------------- |
| <a name="RNF14"></a> RNF14  | O sistema deve ser eficaz em qualquer tipo de rede. | Brainstorm |
| <a name="RNF15"></a> RNF15  | O sistema deve lidar com picos de tráfego e alta demanda. | Brainstorm |
| <a name="RNF16"></a> RNF16  | O sistema deve retornar o objeto de pesquisa rapidamente. | Brainstorm |
| <a name="RNF17"></a> RNF17  | O sistema deve garantir que as transações de compra e download de aplicativos sejam processadas rapidamente. | Brainstorm |
| <a name="RNF18"></a> RNF18  | O sistema deve otimizar o tempo de download e instalação de aplicativos. | Brainstorm |
| <a name="RNF18"></a> RNF18  | O sistema deve otimizar o uso dos recursos (rede, bateria,memória...) do dispositivo. | Brainstorm |

## Portabilidade

| Código | Descrição | Técnica de elicitação |
| ------ | --------- | --------------------- |
| <a name="RNF19"></a> RNF19  | O aplicativo deve funcionar em qualquer dispositivo Android. | Brainstorm |
| <a name="RNF20"></a> RNF20  | O sistema deve funcionar bem em qualquer navegador. | Brainstorm |
| <a name="RNF21"></a> RNF21  | O sistema deve  assegurar que a Play Store funcione de maneira consistente em diferentes dispositivos e sistemas operacionais. | Brainstorm |

### Segurança

| Código | Descrição | Técnica de elicitação |
| ------ | --------- | --------------------- |
| <a name="RNF22"></a> RNF22  | Implementar medidas de segurança para proteger a plataforma contra ataques cibernéticos, malware e outras ameaças. | Brainstorm |
| <a name="RNF23"></a> RNF23  | Criptografar dados sensíveis do usuário. | Brainstorm |
| <a name="RNF24"></a> RNF24  | Garantir que as políticas de privacidade da Play Store e dos apps sejam garantidas. | Brainstorm |
| <a name="RNF25"></a> RNF25  | O usuário deve saber sobre os dados compartilhados com um app. | Brainstorm |
| <a name="RNF26"></a> RNF26  | O sistema deve seguir a LGPD. | Brainstorm |

### Requisitos Funcionais

| Código | Descrição | Técnica de elicitação |
| ------ | --------- | --------------------- |
| REQ01  | O sistema deve fornecer feedbacks para o usuário, como mensagens de erro. | Brainstorm |
| REQ02  | O sistema deve mostrar a localização do usuário dentro do app. | Brainstorm |
| REQ03  | O sistema deve mostrar botões para o usuário confirmar suas ações, evitando erros. | Brainstorm |
| REQ04  | O sistema deve permitir a mudança de idioma. | Brainstorm |
| REQ05  | O sistema deve ter um menu de ajuda. | Brainstorm |
| REQ07  | O sistema deve sincronizar dados de forma confiável entre diferentes dispositivos. | Brainstorm |
| REQ09  | O sistema deve comportamentos maliciosos de apps. | Brainstorm |
| REQ10  | O sistema não deve permitir que cadastrem apps maliciosos. | Brainstorm |

## Histórico de Versões

| **Versão** | **Data** | **Alterações Principais** | **Autor** |
| :--: | :--: | :--: | :--: | 
| 1.0.0 | 15-08-2024 | Lançamento inicial e aplicação do brainstorm | Carlos Alves e Hugo Queiroz |
| 1.0.1 | 16-08-2024 | Revisão dos requisitos e numeração | Carlos Alves, Cecília Quaresma e Hugo Queiroz |