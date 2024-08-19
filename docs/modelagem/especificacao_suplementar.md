# Especificação Suplementar

A Especificação Suplementar é um documento que complementa a especificação de requisitos de um sistema, descrevendo requisitos que não são funcionais ou que não se encaixam diretamente nas funcionalidades principais do sistema. Esses requisitos são muitas vezes chamados de requisitos não funcionais ou requisitos de qualidade, e podem incluir aspectos como usabilidade, confiabilidade, segurança, desempenho, restrições legais, e compatibilidade.


## Aplicação

Para esta técnica, dividimos nas categorias baseadas na FURPS e na ISO/IEC 25010, e incluímos os requisitos não funcionais dessas áreas, elicitados através de [brainstorm](../elicitacao/nao_funcionais.md): 

- Usabilidade
- Confiabilidade
- Desempenho
- Portabilidade
- Segurança
- Design

## Usabilidade

Facilidade com que os usuários conseguem utilizar um sistema ou software para atingir seus objetivos.

| Requisito      | Descrição                                                                                                                 |
| -------------- | ------------------------------------------------------------------------------------------------------------------------- |
| [RNF](../elicitacao/nao_funcional#RNF) | O app deve fornecer feedbacks para o usuário como mensagens de erro.                                                      |
| [RNF](../elicitacao/nao_funcional#RNF) | O app deve ter a hierarquia lógica das ideias.                                                                            |
| [RNF](../elicitacao/nao_funcional#RNF) | O app deve mostrar a localização do usuário dentro do app.                                                                |
| [RNF](../elicitacao/nao_funcional#RNF) | O app deve ser acessível para pessoas com deficiências visuais.                                                           | 
| [RNF](../elicitacao/nao_funcional#RNF) | O app deve mostrar botões para o usuário confirmar suas ações, evitando erros.                                            |
| [RNF](../elicitacao/nao_funcional#RNF) | O app deve permitir a mudança de idioma.                                                                                  |
| [RNF](../elicitacao/nao_funcional#RNF) | O app deve ser acessível para pessoas idosas.                                                                             |
| [RNF](../elicitacao/nao_funcional#RNF) | O app deve ser consistente e padronizado.                                                                                 |
| [RNF](../elicitacao/nao_funcional#RNF) | O app deve ter um menu de ajuda.                                                                                          | 
| [RNF](../elicitacao/nao_funcional#RNF) | O app deve permitir descrição por áudio e atalhos de teclado.                                                             | 
| [RNF](../elicitacao/nao_funcional#RNF) | O app deve ter cores contrastantes.                                                                                       | 
| [RNF](../elicitacao/nao_funcional#RNF) | O app deve permitir configurações de acessibilidade como cor e fonte.                                                     | 
| [RNF](../elicitacao/nao_funcional#RNF) | O app deve informar o status do sistema.                                                                                  | 


## Confiabilidade

Capacidade de um sistema ou software de funcionar de maneira consistente e correta, sem falhas, durante um período específico.

| Requisito      | Descrição                                                                                                                 |
| -------------- | ------------------------------------------------------------------------------------------------------------------------- |
| [RNF](../elicitacao/nao_funcional#RNF) | O app deve permitir a recuperação de falhas.                                                                              |
| [RNF](../elicitacao/nao_funcional#RNF) | O sistema deve rodar no browser.                                                                                          |
| [RNF](../elicitacao/nao_funcional#RNF) | Sincronizar dados de forma confiável entre diferentes dispositivos.                                                       |
| [RNF](../elicitacao/nao_funcional#RNF) | Garantir que os dados dos aplicativos e dos usuários sejam validados e armazenados com precisão para evitar corrupção ou perda de dados. |
| [RNF](../elicitacao/nao_funcional#RNF) | O sistema deve prevenir erros.                                                                                            |
| [RNF](../elicitacao/nao_funcional#RNF) | O sistema deve ficar no ar 24/7.                                                                                          |
| [RNF](../elicitacao/nao_funcional#RNF) | Realizar atualizações regulares e manutenção para corrigir bugs, melhorar a performance e manter a confiabilidade geral da plataforma. |


## Desempenho

Medida da eficiência com que um sistema ou software realiza suas tarefas, incluindo velocidade de processamento e uso de recursos.


| Requisito      | Descrição                                                                                                               |
| -------------- | ------------------------------------------------------------------------------------------------------------------------- |
| [RNF](../elicitacao/nao_funcional#RNF) | O sistema deve ser eficaz em qualquer tipo de rede.                                                                       |
| [RNF](../elicitacao/nao_funcional#RNF) | O sistema deve se adaptar a todo tipo de tela.                                                                            |
| [RNF](../elicitacao/nao_funcional#RNF) | Lidar com picos de tráfego e alta demanda.                                                                                |
| [RNF](../elicitacao/nao_funcional#RNF) | O sistema deve carregar o conteúdo das páginas de forma rápida.                                                           |
| [RNF](../elicitacao/nao_funcional#RNF) | O sistema deve retornar o objeto de pesquisa rapidamente.                                                                 |
| [RNF](../elicitacao/nao_funcional#RNF) | Garantir que as transações de compra e download de aplicativos sejam processadas rapidamente.                             |
| [RNF](../elicitacao/nao_funcional#RNF) | Otimizar o tempo de download e instalação de aplicativos.                                                                 |


## Portabilidade

Capacidade de um sistema ou software de ser utilizado em diferentes ambientes ou plataformas sem a necessidade de grandes modificações.


| Requisito      | Descrição                                                                                                              | 
| -------------- | ------------------------------------------------------------------------------------------------------------------------- |
| [RNF](../elicitacao/nao_funcional#RNF) | O aplicativo deve funcionar em qualquer dispositivo Android.                                                              |
| [RNF](../elicitacao/nao_funcional#RNF) | O sistema deve funcionar bem em qualquer navegador.                                                                       |
| [RNF](../elicitacao/nao_funcional#RNF) | Assegurar que a Play Store funcione de maneira consistente em diferentes dispositivos e sistemas operacionais.            |


## Segurança

Proteção de um sistema ou software contra ameaças, garantindo integridade, confidencialidade e disponibilidade dos dados.


| Requisito      | Descrição                                                                                                               |
| -------------- | ------------------------------------------------------------------------------------------------------------------------- |
| [RNF](../elicitacao/nao_funcional#RNF) | Implementar medidas de segurança para proteger a plataforma contra ataques cibernéticos, malware e outras ameaças.        |
| [RNF](../elicitacao/nao_funcional#RNF) | Criptografar dados sensíveis do usuário.                                                                                  |
| [RNF](../elicitacao/nao_funcional#RNF) | Detectar comportamentos maliciosos de apps.                                                                               |
| [RNF](../elicitacao/nao_funcional#RNF) | Não deve permitir que cadastrem apps maliciosos.                                                                          |
| [RNF](../elicitacao/nao_funcional#RNF) | Garantir que as políticas de privacidade da Play Store e dos apps sejam garantidas.                                       |
| [RNF](../elicitacao/nao_funcional#RNF) | O usuário deve saber sobre os dados compartilhados com um app.                                                            |
| [RNF](../elicitacao/nao_funcional#RNF) | O sistema deve seguir a LGPD.                                                                                             |


## Design

Concepção visual e estrutural de um sistema ou software, que impacta a aparência, a funcionalidade e a experiência do usuário.


### Identidade Visual da Google Play Store

A identidade visual da Google Play Store é essencial para manter a consistência da marca e garantir uma experiência de usuário coesa. Abaixo estão os elementos chave da identidade visual da Play Store.

#### Logotipo

O logotipo da Google Play Store é um ícone que combina uma forma triangular e colorida com o nome "Play Store". O ícone é composto por um triângulo de cores variadas que representa a diversidade de conteúdos disponíveis na plataforma.

- **Logotipo Principal**: 
<div style="text-align: center; font-size: 150px;">
    <img src="https://cdn.mos.cms.futurecdn.net/Q2oLsPvoGLpzWuDqZgzANH-650-80.jpg.webp"  width="200px"/>
</div>

#### Cores

A paleta de cores da Google Play Store é vibrante e moderna, refletindo a diversidade e a energia da plataforma. As principais cores incluem:

- **Primária**: 
<div style="text-align: center; font-size: 150px;">
    <span style="color: #4285F4;">&#9679;</span> <!-- Blue -->
    <span style="color: #EA4335;">&#9679;</span> <!-- Red -->
    <span style="color: #FBBC05;">&#9679;</span> <!-- Yellow -->
    <span style="color: #34A853;">&#9679;</span> <!-- Green -->
</div>


#### Tipografia

A tipografia utilizada pela Google Play Store é simples e legível, refletindo a clareza e a acessibilidade da plataforma. A fonte primária é:

- **Fonte Principal**: Roboto

#### Ícones e Botões

Os ícones e botões na Google Play Store são projetados para serem intuitivos e fáceis de usar. Eles geralmente apresentam um design limpo e cores contrastantes para garantir visibilidade e facilidade de navegação.

- **Ícones**: 

![Ícone da Play Store](../assets/imagens/icones.jpeg) 

![Ícone da Play Store](../assets/imagens/icones2.jpeg) 

#### Uso da Identidade Visual

- **Uso do Logotipo**: O logotipo deve ser exibido em tamanho adequado e em contraste com o fundo para garantir a legibilidade.
- **Paleta de Cores**: Use as cores da paleta de forma consistente para criar uma experiência visual coesa.
- **Tipografia**: Use a fonte Roboto para manter a clareza e a consistência textual.


## Histórico de Versões

| **Versão** | **Data** | **Alterações Principais** | **Autor** |
| :--: | :--: | :--: | :--: | 
| 1.0.0 | 15-08-2024 | Lançamento inicial da especificação | Arthur Ribeiro, Carlos Alves e Hugo Queiroz,  |
| 1.0.1 | 16-08-2024 | Arrumando o especificação | Carlos Alves, Cecília Quaresma e Hugo Queiroz,  |
