# Three Level Scale

## Introdução

O Three Level Scale é uma técnica que consiste em classificar os requisitos de acordo com sua importância ou urgência. Para isso ela categoriza em três níveis de prioridade distintas: alta, média e baixa.

## Metodologia

A priorização por essa técnica foi realizada por um membro da equipe, que guiou a sessão e um usuário, responsável por classificar os requisitos em algumas das três categorias. As categorias de prioridade foram elaboradas de acordo com a urgência e importância de cada requisito, seguindo a legenda a seguir:

- **Alta prioridade:** requisitos importantes e urgentes. Geralmente têm um impacto significativo e imediato nas metas ou objetivos prioritários. Requisitos nessa categoria devem ser tratados o mais rápido possível.
- **Média prioridade:** requisitos importantes, mas não urgentes. Eles podem ter um impacto significativo a longo prazo ou contribuir para metas secundárias. ERequisitos nessa categoria devem ser tratados em um prazo razoável.
- **Baixa prioridade:** requisitos nem importantes, nem urgentes. Eles geralmente têm um impacto menor ou são tarefas opcionais que podem ser adiadas. Requisitos nessa categoria podem ser tratados quando houver tempo disponível.

## Participantes

A sessão de priorização foi realizada no dia 22/04/2024, com horário de incío às 13:30h e o horário de fim às 14h. A sessão contou com a participação da usuária do aplicativo Gov.br, Beatriz Lins e de uma mediadora, [Ester Lino](https://github.com/esteerlino). Inicialmente ocorreu uma breve explicação sobre a priorização e em seguida, a mediadora pontou cada requisito e solicitou que a usuária classificasse de acordo com as categorias disponíveis. 

## Resultados

*Legenda da tabela:*

- RFx: Requisito Funcional nºx
- RNFx: Requisito Não-Funcional nºx
- ADFUx: Requisito nºx elicitado pela Análise de Documentos (Feedbacks dos Usuários)
- ADTUx: Requisito nºx elicitado pela Análise de Documentos (Termo de Uso)
- BSx: Requisito nºx elicitado pelo Brainstorming
- STx: Requisito nºx elicitado pelo Storytelling

<p style="text-align: center"><b><a id="tab_1" style="visibility: hidden;"></a>Tabela 1</b> - Requisitos funcionais e não funcionais</p>

|  Tipo  | Descrição | Rastreabilidade | Prioridade |
|:------:|:---------:|:---------------:|:----------:|
| RF01 | O sistema deve possuir uma funcionalidade de reconhecimento facial para autenticação do usuário. | [ADFU01](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Baixa |
| RF02 | O sistema deve permitir que os usuários recuperem suas senhas através de métodos seguros e eficientes. | [ADFU02](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Alta |
| RF03 | O sistema deve oferecer verificação em duas etapas como uma camada adicional de segurança para os usuários. | [ADFU03](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Média |
| RF04 | O sistema deve permitir que os usuários utilizem suas credenciais para acessar diferentes serviços governamentais de forma centralizada. | [ADFU04](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) |  Média |
| RF05 | O sistema deve facilitar o processo de mudança de celular pelo usuário, permitindo a transferência de segurança e autenticações sem necessidade de cancelar e recriar a conta. | [ADFU05](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Média |
| RF06 | O sistema deve notificar os usuários de quaisquer acessos não autorizados ou mudanças críticas na segurança de suas contas. | [ADFU06](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) |  Alta |
| RF07 | O sistema deve permitir a autenticação do usuário utilizando métodos como biometria facial e validação biográfica. | [ADTU01](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Baixa |
| RF08 | O sistema deve permitir ao usuário acessar, atualizar e excluir seus dados pessoais.                                    | [ADTU02](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Alta |
| RF09 | O sistema deve oferecer funcionalidades para recuperação de conta através de SMS, e-mail ou suporte direto.             | [ADTU03](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Média |
| RF10 | O sistema deve permitir aos usuários visualizar e gerenciar documentos digitais associados à sua conta.                 | [ADTU04](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Alta |
| RF11 | O sistema deve oferecer uma funcionalidade de Prova de Vida para verificação de beneficiários de programas de previdência ou assistência social. | [ADTU05](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Média |
| RF12 | O aplicativo deve permitir que os usuários se autentiquem de forma segura, usando credenciais únicas, como CPF e senha | [BS01](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Alta |
| RF13 | O usuário deve ser capaz de logar com as credências do gov.br                                                          | [BS02](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Alta |
| RF14 | O usuário deve conseguir visualizar seus documentos                                                                    | [BS03](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Alta |
| RF15 | O usuário deve conseguir agendar serviços específicos                                                                  | [BS04](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Média |
| RF16 | O usuário deve conseguir emitir/baixar certidões                                                                       | [BS05](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Média |
| RF17 | O usuário deve conseguir se logar no aplicativo                                                                        | [BS06](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Alta |
| RF18 | O login deve possuir autenticação em dois fatores                                                                      | [BS07](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Média |
| RF19 | O usuário deve conseguir assinar documentos digitalmente                                                               | [BS08](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Alta |
| RF20 | O usuário deve conseguir se inscrever em concursos públicos                                                            | [BS09](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Baixa |
| RF21 | O usuário deve conseguir consultar programas do governo                                                                | [BS10](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Média |
| RF22 | O usuário deve conseguir se conectar com o Detran                                                                      | [BS11](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Média |
| RF23 | O usuário deve conseguir se conectar com o NIS                                                                         | [BS12](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Média |
| RF24 | O usuário deve conseguir se conectar com o ID Jovem                                                                    | [BS13](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Média |
| RF25 | O usuário deve conseguir usar o aplicativo para pagar impostos trabalhistas                                            | [BS14](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Baixa |
| RF26 | O usuário deve conseguir obter o código de acesso                                                                      | [BS15](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Alta |
| RF27 | O aplicativo deve possuir ferramentas de acessibilidade (Alto contraste, aumentar a fonte, audiodescrição)             | [BS16](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Baixa |
| RF28 | Como usuário, desejo acessar o aplicativo gov.br de forma rápida e intuitiva.  | [ST01](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Alta |
| RF29 | Como usuário, desejo encontrar facilmente o serviço de agendamento na Receita Federal. | [ST02](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Baixa |
| RF30 | Como usuário, desejo acessar as funções de assinatura digital para agilizar a assinatura de documentos. | [ST03](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Alta |
| RF31 | Como usuário, desejo agendar atendimentos em órgãos públicos através do aplicativo.            | [ST04](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Média |
| RF32 | Como usuário, desejo consultar informações sobre benefícios sociais através do aplicativo.     | [ST05](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Média |
| RF33 | Como usuário, desejo acessar a função de carteira digital no aplicativo.                      | [ST06](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Baixa |
| RF34 | Como usuário, desejo continuar recebendo minha aposentadoria através da função de prova de vida. | [ST07](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Média |
| RF35 | Como usuário, desejo uma navegação intuitiva para buscar processos e documentos.               | [ST08](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Alta |
| RF36 | Como usuário, desejo garantir a segurança na transmissão e armazenamento de documentos sensíveis. | [ST09](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Alta |
| RF37 | Como usuário, desejo eficiência no agendamento e acompanhamento de processos.                 | [ST10](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Alta |
| RF38 | Como usuário, desejo receber atualizações relevantes sobre processos e benefícios sociais.    | [ST11](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Baixa |
| RF39 | Como usuário, desejo substituir minha carteira física por uma versão digital no aplicativo.   | [ST12](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Média |
| RF40 | Como usuário, desejo acesso rápido aos meus documentos no celular, sem a necessidade de documentos físicos. | [ST13](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Alta |
| RF41 | Como usuário, desejo poder acessar meus documentos mesmo sem conexão com a internet.          | [ST14](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Média |
| RF42 | Como usuário, desejo garantir a privacidade das informações pessoais.                         | [ST15](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Alta |
| RNF01 | O sistema deve ser estável e confiável, funcionando corretamente sem travamentos ou fechamentos inesperados. | [ADFU07](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Alta |
| RNF02 | A interface do sistema deve ser clara e fácil de usar, evitando complexidades desnecessárias que possam confundir os usuários. | [ADFU08](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) |  Alta |
| RNF03 | As funcionalidades críticas, como reconhecimento facial e autenticação, devem ser otimizadas para operar de maneira rápida e eficiente. | [ADFU09](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Média |
| RNF04 | O sistema deve assegurar o tratamento adequado dos dados sensíveis de acordo com a legislação (LGPD).                     | [ADTU06](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Alta |
| RNF05 | O sistema deve obter consentimento explícito dos usuários para o tratamento de seus dados pessoais.                        | [ADTU07](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Alta |
| RNF06 | O sistema deve ser acessível através de diferentes dispositivos e navegadores.                                             | [ADTU08](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Média |
| RNF07 | O sistema deve implementar múltiplos níveis de segurança de acesso (bronze, prata, ouro).                                  | [ADTU09](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Baixa |
| RNF08 | O sistema deve ser acessível e disponível para todos os usuários, garantindo acessibilidade para usuários com deficiências e oferecendo suporte a múltiplas plataformas e navegadores. | [ADTU10](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) |  Baixa |
| RNF09 | O aplicativo deve ser seguro e confiável, protegendo os dados dos usuários                                      | [BS17](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Alta |
| RNF10 | O login deve ser feito de maneira rápida e segura                                                               | [BS18](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Alta |
| RNF11 | O aplicativo deve ser acessível a pessoas com deficiência                                                       | [BS19](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Média |
| RNF12 | O aplicativo deve exigir que a senha do usuário possua obrigatoriamente letras, números e caracteres especiais. | [BS20](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Média |
| RNF13 | O aplicativo deve ser intuitivo e fácil de usar                                                                 | [BS21](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Alta |
| RNF14 | O aplicativo deve ter boa performance e ser estável                                                             | [BS22](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Alta |
| RNF15 | O aplicativo deve ter suporte ao cliente eficiente                                                              | [BS23](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Média |
| RNF16 | Segurança: O aplicativo deve garantir a segurança dos dados pessoais dos usuários.            | [ST16](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling)  |Alta  |
| RNF17 | Usabilidade: A interface do aplicativo deve ser simples e fácil de usar.                      | [ST17](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling)  | Alta |
| RNF18 | Eficiência: O aplicativo deve ser rápido no acesso e no agendamento de serviços.               | [ST18](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Alta |
| RNF19 | Acessibilidade: O aplicativo deve ser acessível mesmo sem conexão com a internet.              | [ST19](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) |  Média |
| RNF20 | Confiabilidade: O aplicativo deve manter a integridade dos documentos e informações consultadas. | [ST20](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) |  Alta |
| RNF21 | Atualização: O aplicativo deve manter os usuários informados sobre novidades e atualizações importantes. | [ST21](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Baixa |
| RNF22 | Privacidade: Garantir que as informações dos usuários não sejam compartilhadas sem permissão. | [ST22](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling)  | Alta |

<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/esteerlino">Ester Lino</a></p></font>

## Gravação da reunião

<iframe width="560" height="315" src="https://www.youtube.com/embed/wZRdGgvMjjA?si=6PqCsxmw7Uvno0WJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Bibliografia

- WIEGERS, Karl; BEATTY, Joy.Software Requirements (Developer Best Practices), 3rd Edition, Microsoft Press, 2013.

## Histórico de versão

| Versão | Data | Descrição | Responsáveis | Revisor |
| :----: | :--: | :-----------------------------------------------------: | :----------------------------------------------------------------------------------------------: | :----------------------------------------------: |
|  1.0   | 22/04/2024 | Criação da página  | [Ester Lino](https://github.com/esteerlino) | [Carlos Gabriel](https://github.com/TheCarlosRamos) |
|  1.1   | 22/04/2024 | Incluído o vídeo da sessão de priorização | [Ester Lino](https://github.com/esteerlino) | [Carlos Gabriel](https://github.com/TheCarlosRamos) |

