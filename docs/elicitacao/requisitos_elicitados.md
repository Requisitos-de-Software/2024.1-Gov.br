# Requisitos Elicitados

## Introdução

Essa página reune todos os requisitos funcionais e não funcionais elicitados usando as técnicas de [análise de documentos](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos), [brainstorm](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) e [storytelling](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling).

## Metodologia

A tabela 1 apresenta os requisitos funcionais e não funcionais, sendo que cada linha contém ID, descrição, um hyperlink de rastreabilidade que direciona à página da(s) técnica(s) que elicitou o requisito em questão e se ele foi implementado ou não.

*Legenda da tabela:*

- RFx: Requisito Funcional nºx
- RNFx: Requisito Não-Funcional nºx
- ADFUx: Requisito nºx elicitado pela Análise de Documentos (Feedbacks dos Usuários)
- ADTUx: Requisito nºx elicitado pela Análise de Documentos (Termo de Uso)
- BSx: Requisito nºx elicitado pelo Brainstorming
- STx: Requisito nºx elicitado pelo Storytelling

## Requisitos funcionais e não funcionais

<p style="text-align: center"><b><a id="tab_1" style="visibility: hidden;"></a>Tabela 1</b> - Requisitos funcionais e não funcionais</p>

|  ID  |                                Descrição                                |                                  Rastreabilidade                                 | Implementado |
|:----:|:-----------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|:-------------:|
| RF01 | O sistema deve possuir uma funcionalidade de reconhecimento facial para autenticação do usuário. | [ADFU01](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Sim |
| RF02 | O sistema deve permitir que os usuários recuperem suas senhas através de métodos seguros e eficientes. | [ADFU02](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Sim |
| RF03 | O sistema deve oferecer verificação em duas etapas como uma camada adicional de segurança para os usuários. | [ADFU03](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Sim |
| RF04 | O sistema deve permitir que os usuários utilizem suas credenciais para acessar diferentes serviços governamentais de forma centralizada. | [ADFU04](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Sim |
| RF05 | O sistema deve facilitar o processo de mudança de celular pelo usuário, permitindo a transferência de segurança e autenticações sem necessidade de cancelar e recriar a conta. | [ADFU05](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Sim |
| RF06 | O sistema deve notificar os usuários de quaisquer acessos não autorizados ou mudanças críticas na segurança de suas contas. | [ADFU06](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Sim |
| RF07 | O sistema deve permitir a autenticação do usuário utilizando métodos como biometria facial e validação biográfica. | [ADTU01](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Sim |
| RF08 | O sistema deve permitir ao usuário acessar, atualizar e excluir seus dados pessoais.                                    | [ADTU02](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Sim |
| RF09 | O sistema deve oferecer funcionalidades para recuperação de conta através de SMS, e-mail ou suporte direto.             | [ADTU03](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Sim |
| RF10 | O sistema deve permitir aos usuários visualizar e gerenciar documentos digitais associados à sua conta.                 | [ADTU04](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Sim |
| RF11 | O sistema deve oferecer uma funcionalidade de Prova de Vida para verificação de beneficiários de programas de previdência ou assistência social. | [ADTU05](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Sim |
| RF12 | O aplicativo deve permitir que os usuários se autentiquem de forma segura, usando credenciais únicas, como CPF e senha | [BS01](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Sim |
| RF13 | O usuário deve ser capaz de logar com as credências do gov.br                                                          | [BS02](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Sim |
| RF14 | O usuário deve conseguir visualizar seus documentos                                                                    | [BS03](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Sim |
| RF15 | O usuário deve conseguir agendar serviços específicos                                                                  | [BS04](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Não |
| RF16 | O usuário deve conseguir emitir/baixar certidões                                                                       | [BS05](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Sim |
| RF17 | O usuário deve conseguir se logar no aplicativo                                                                        | [BS06](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Sim |
| RF18 | O login deve possuir autenticação em dois fatores                                                                      | [BS07](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Sim |
| RF19 | O usuário deve conseguir assinar documentos digitalmente                                                               | [BS08](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Sim |
| RF20 | O usuário deve conseguir se inscrever em concursos públicos                                                            | [BS09](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Não |
| RF21 | O usuário deve conseguir consultar programas do governo                                                                | [BS10](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Não |
| RF22 | O usuário deve conseguir se conectar com o Detran                                                                      | [BS11](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Não |
| RF23 | O usuário deve conseguir se conectar com o NIS                                                                         | [BS12](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Não |
| RF24 | O usuário deve conseguir se conectar com o ID Jovem                                                                    | [BS13](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Não |
| RF25 | O usuário deve conseguir usar o aplicativo para pagar impostos trabalhistas                                            | [BS14](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Não |
| RF26 | O usuário deve conseguir obter o código de acesso                                                                      | [BS15](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Sim |
| RF27 | O aplicativo deve possuir ferramentas de acessibilidade (Alto contraste, aumentar a fonte, audiodescrição)             | [BS16](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Não |
| RF28 | Como usuário, desejo acessar o aplicativo gov.br de forma rápida e intuitiva.  | [ST01](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Sim |
| RF29 | Como usuário, desejo encontrar facilmente o serviço de agendamento na Receita Federal. | [ST02](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) |  Sim |
| RF30 | Como usuário, desejo acessar as funções de assinatura digital para agilizar a assinatura de documentos. | [ST03](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Sim |
| RF31 | Como usuário, desejo agendar atendimentos em órgãos públicos através do aplicativo.            | [ST04](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Não |
| RF32 | Como usuário, desejo consultar informações sobre benefícios sociais através do aplicativo.     | [ST05](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Não |
| RF33 | Como usuário, desejo acessar a função de carteira digital no aplicativo.                      | [ST06](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Não |
| RF34 | Como usuário, desejo continuar recebendo minha aposentadoria através da função de prova de vida. | [ST07](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Não |
| RF35 | Como usuário, desejo uma navegação intuitiva para buscar processos e documentos.               | [ST08](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Sim |
| RF36 | Como usuário, desejo garantir a segurança na transmissão e armazenamento de documentos sensíveis. | [ST09](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Sim |
| RF37 | Como usuário, desejo eficiência no agendamento e acompanhamento de processos.                 | [ST10](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Sim |
| RF38 | Como usuário, desejo receber atualizações relevantes sobre processos e benefícios sociais.    | [ST11](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Sim |
| RF39 | Como usuário, desejo substituir minha carteira física por uma versão digital no aplicativo.   | [ST12](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Não |
| RF40 | Como usuário, desejo acesso rápido aos meus documentos no celular, sem a necessidade de documentos físicos. | [ST13](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Sim |
| RF41 | Como usuário, desejo poder acessar meus documentos mesmo sem conexão com a internet.          | [ST14](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Não |
| RF42 | Como usuário, desejo garantir a privacidade das informações pessoais.                         | [ST15](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Sim |
| RNF01 | O sistema deve ser estável e confiável, funcionando corretamente sem travamentos ou fechamentos inesperados. | [ADFU07](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Sim |
| RNF02 | A interface do sistema deve ser clara e fácil de usar, evitando complexidades desnecessárias que possam confundir os usuários. | [ADFU08](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Sim |
| RNF03 | As funcionalidades críticas, como reconhecimento facial e autenticação, devem ser otimizadas para operar de maneira rápida e eficiente. | [ADFU09](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Sim |
| RNF04 | O sistema deve assegurar o tratamento adequado dos dados sensíveis de acordo com a legislação (LGPD).                     | [ADTU06](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Sim |
| RNF05 | O sistema deve obter consentimento explícito dos usuários para o tratamento de seus dados pessoais.                        | [ADTU07](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Sim |
| RNF06 | O sistema deve ser acessível através de diferentes dispositivos e navegadores.                                             | [ADTU08](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Sim |
| RNF07 | O sistema deve implementar múltiplos níveis de segurança de acesso (bronze, prata, ouro).                                  | [ADTU09](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Sim |
| RNF08 | O sistema deve ser acessível e disponível para todos os usuários, garantindo acessibilidade para usuários com deficiências e oferecendo suporte a múltiplas plataformas e navegadores. | [ADTU10](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Sim |
| RNF09 | O aplicativo deve ser seguro e confiável, protegendo os dados dos usuários                                      | [BS17](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Sim |
| RNF10 | O login deve ser feito de maneira rápida e segura                                                               | [BS18](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Não |
| RNF11 | O aplicativo deve ser acessível a pessoas com deficiência                                                       | [BS19](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Não |
| RNF12 | O aplicativo deve exigir que a senha do usuário possua obrigatoriamente letras, números e caracteres especiais. | [BS20](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Não |
| RNF13 | O aplicativo deve ser intuitivo e fácil de usar                                                                 | [BS21](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Não |
| RNF14 | O aplicativo deve ter boa performance e ser estável                                                             | [BS22](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Não |
| RNF15 | O aplicativo deve ter suporte ao cliente eficiente                                                              | [BS23](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Não |
| RNF16 | Segurança: O aplicativo deve garantir a segurança dos dados pessoais dos usuários.            | [ST16](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling)  | Sim |
| RNF17 | Usabilidade: A interface do aplicativo deve ser simples e fácil de usar.                      | [ST17](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling)  | Sim |
| RNF18 | Eficiência: O aplicativo deve ser rápido no acesso e no agendamento de serviços.               | [ST18](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Sim |
| RNF19 | Acessibilidade: O aplicativo deve ser acessível mesmo sem conexão com a internet.              | [ST19](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Não |
| RNF20 | Confiabilidade: O aplicativo deve manter a integridade dos documentos e informações consultadas. | [ST20](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Sim |
| RNF21 | Atualização: O aplicativo deve manter os usuários informados sobre novidades e atualizações importantes. | [ST21](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Sim |
| RNF22 | Privacidade: Garantir que as informações dos usuários não sejam compartilhadas sem permissão. | [ST22](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling)  | Sim |

<font size="2"><p style="text-align: center"><b>Autora: <a href="https://github.com/esteerlino">Ester Lino</a></p></font>

## Histórico de Versões

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| :----: | :--: | :-------: | :-------: | :---------: |
|  1.0   | 17/04/2024 | Criação da página com os requisitos elicitados | [Ester Lino](https://github.com/esteerlino)  | [Arthur Gabriel](https://github.com/ArthurGabrieel) |
