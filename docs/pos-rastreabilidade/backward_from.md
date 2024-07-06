
# Backward-From

## Introdução

O Backward-From é uma metodologia de desenvolvimento de software que se diferencia por iniciar com o resultado final desejado em mente. Ao invés de partir de requisitos e funcionalidades pré-definidos, o Backward-From traça um roteiro a partir do que se deseja alcançar, definindo:

Experiência do Usuário: Detalhando como os usuários interagirão com o software, quais funcionalidades serão acessadas e como cada ação trará benefícios para eles.
Validação Contínua: Obtendo feedback dos usuários e stakeholders ao longo do processo, adaptando o software às necessidades e expectativas identificadas.

Ao aliar a rastreabilidade à metodologia Backward-From, as equipes de desenvolvimento podem alcançar um novo patamar de eficiência, qualidade e sucesso em seus projetos. Essa união estratégica garante que o software seja desenvolvido de forma clara, precisa, alinhada às expectativas dos usuários e com foco na entrega de resultados valiosos.

## Metodologia

A metodologia de rastreabilidade de requisitos proposta por Toranzo, é uma abordagem abrangente para mapear e documentar as relações entre requisitos, casos de uso, testes e outros elementos de um projeto de software.
Seu principal objetivo é garantir que cada requisito seja implementado e testado corretamente.

Tipos de elos da Rastreabilidade
Meta-modelo de Toranzo:
Os principais elos de rastreabilidade são:
- Satisfação: classe origem tem dependência de satisfação com a classe
destino.
- Recurso: classe origem tem dependência de recurso com a classe
destino.
- Responsabilidade: registra a participação, responsabilidade e ação de
pessoas sobre artefatos.
- Representação: captura a representação ou modelagem dos requisitos
em outras linguagens.
- Alocado: classe origem está relacionada à classe destino, que
representa um subsistema.
- Agregação: indica “composição” de elementos.

Primeiramente, foi separado em duas tabelas: os requisitos funcionais e não funcionais com as suas informações em relação à sua rastreabilidade e implementação.
Consequentemente, foi criada uma tabela para cada tipo de requisito (RF e RNF) destacando o tipo de elo da rastreabilidade e sua justificativa.

### Descrição: 

- RNFx: Requisito Não-Funcional nºx
- ADFUx: Requisito nºx elicitado pela Análise de Documentos (Feedbacks dos Usuários)
- ADTUx: Requisito nºx elicitado pela Análise de Documentos (Termo de Uso)
- BSx: Requisito nºx elicitado pelo Brainstorming
- STx: Requisito nºx elicitado pelo Storytelling

## Desenvolvimento
### Requisitos Funcionais (RF)

<font><p style="text-align: center">**Tabela 1:** Tabela de requisitos funcionais.</p></font>

|  ID  |                                Descrição                                |                                  Rastreabilidade                                 | Implementado |
|:----:|:-----------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|:------------:|
| RF01 | O sistema deve oferecer reconhecimento facial para autenticação do usuário. | [ADFU01](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Não |
| RF02 | O sistema deve permitir a recuperação de senha por meio de perguntas de segurança e/ou e-mail. | [ADFU02](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) [ADTU03](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Não |
| RF03 | O sistema deve permitir a verificação em duas etapas para maior segurança do login. | [ADFU03](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) [BS03](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Não |
| RF04 | O sistema deve oferecer acesso centralizado a serviços governamentais. | [ADFU04](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Não |
| RF05 | O sistema deve permitir a notificação do usuário em caso de atividades suspeitas em sua conta. | [ADFU06](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Não |
| RF06 | O sistema deve permitir a autenticação biométrica por meio de impressões digitais. | [ADTU01](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Não |
| RF07 | O sistema deve permitir o acesso e gerenciamento de dados pessoais pelo usuário. | [ADTU02](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Não |
| RF08 | O sistema deve oferecer funcionalidades para recuperação de conta através de SMS, e-mail ou suporte direto. | [ADTU03](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Não |
| RF09 | O sistema deve permitir a visualização e gerenciamento de documentos digitais. | [ADTU04](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Não |
| RF10 | O sistema deve permitir a prova de vida para utilização de serviços online. | [ADTU05](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Não |
| RF11 | O aplicativo deve permitir que os usuários se autentiquem de forma segura, usando credenciais únicas, como CPF e senha. | [BS01](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) [BS02](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) [BS06](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Sim |
| RF12 | O usuário deve ser capaz de logar com as credenciais do gov.br. | Igual ao RF11 | Sim |
| RF13 | O usuário deve conseguir visualizar seus documentos. | [BS03](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) [ST13](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Sim |
| RF14 | O usuário deve conseguir agendar serviços específicos. | [BS04](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Não |
| RF15 | O usuário deve conseguir emitir/baixar certidões. | [BS05](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Sim |
| RF16 | O usuário deve conseguir se logar no aplicativo. | Igual ao RF11 | Sim |
| RF17 | O login deve possuir autenticação em dois fatores. | Igual ao RF03 | Sim |
| RF18 | O usuário deve conseguir assinar documentos digitalmente. | [BS08](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) [ST03](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Sim |
| RF19 | O usuário deve conseguir se inscrever em concursos públicos. | [BS09](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Não |
| RF20 | O usuário deve conseguir consultar programas do governo. | [BS10](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) [ST05](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Não |
| RF21 | O usuário deve conseguir se conectar com o Detran. | [BS11](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Não |
| RF22 | O usuário deve conseguir se conectar com o NIS. | [BS12](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Não |
| RF23 | O usuário deve conseguir se conectar com o ID Jovem. | [BS13](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Não |
| RF24 | O usuário deve conseguir usar o aplicativo para pagar impostos trabalhistas. | [BS14](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Não |
| RF25 | O usuário deve conseguir obter o código de acesso. | [BS15](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Sim |
| RF26 | O aplicativo deve possuir ferramentas de acessibilidade (Alto contraste, aumentar a fonte, audiodescrição). | [BS15](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Não |
| RF27 | Como usuário, desejo acessar o aplicativo gov.br de forma rápida e intuitiva. | [ST01](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Sim |
| RF28 | Como usuário, desejo encontrar facilmente o serviço de agendamento na Receita Federal. | [ST02](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Sim |
| RF29 | Como usuário, desejo acessar as funções de assinatura digital para agilizar a assinatura de documentos. | Igual ao RF18 | Sim |
| RF30 | Como usuário, desejo agendar atendimentos em órgãos públicos através do aplicativo. | [ST04](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Não |
| RF31 | Como usuário, desejo consultar informações sobre benefícios sociais através do aplicativo. | Igual ao RF20 | Não |
| RF32 | Como usuário, desejo substituir minha carteira física por uma versão digital no aplicativo. | [ST06](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) [ST12](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Sim |
| RF33 | Como usuário, desejo continuar recebendo minha aposentadoria através da função de prova de vida. | [ST07](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Sim |
| RF34 | Como usuário, desejo uma navegação intuitiva para buscar processos e documentos. | [ST08](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Sim |
| RF35 | Como usuário, desejo garantir a segurança na transmissão e armazenamento de documentos sensíveis. | [ST09](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Sim |
| RF36 | Como usuário, desejo eficiência no agendamento e acompanhamento de processos. | [ST10](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Sim |
| RF37 | Como usuário, desejo receber atualizações relevantes sobre processos e benefícios sociais. | [ST11](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Sim |
| RF38 | Como usuário, desejo substituir minha carteira física por uma versão digital no aplicativo. | Igual ao RF32 | Sim |
| RF39 | Como usuário, desejo acesso rápido aos meus documentos no celular, sem a necessidade de documentos físicos. | Igual ao RF13 | Sim |
| RF40 | Como usuário, desejo poder acessar meus documentos mesmo sem conexão com a internet. | [ST14](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Sim |

<font size="2"><p style="text-align: center"><b>Fonte: <a href="[https://github.com/thiagorfreitas">Thiago Freitas</a></p></font>

### Requisitos Não Funcionais (RNF)

<font><p style="text-align: center">**Tabela 2:** Tabela de requisitos não funcionais.</p></font>

|  Tipo  |                                Descrição                                |                                  Rastreabilidade                                 | Implementado |
|:------:|:-----------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|:------------:|
| RNF01 | O sistema deve ser estável e confiável, funcionando corretamente sem travamentos ou fechamentos inesperados. | [ADFU07](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Sim |
| RNF02 | A interface do sistema deve ser clara e fácil de usar, evitando complexidades desnecessárias que possam confundir os usuários. | [ADFU08](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Sim |
| RNF03 | As funcionalidades críticas, como reconhecimento facial e autenticação, devem ser otimizadas para operar de maneira rápida e eficiente. | [ADFU09](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Sim |
| RNF04 | O sistema deve assegurar o tratamento adequado dos dados sensíveis de acordo com a legislação (LGPD). | [ADTU06](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Sim |
| RNF05 | O sistema deve obter consentimento explícito dos usuários para o tratamento de seus dados pessoais. | [ADTU07](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Sim |
| RNF06 | O sistema deve ser acessível através de diferentes dispositivos e navegadores. | [ADTU08](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Sim |
| RNF07 | O sistema deve implementar múltiplos níveis de segurança de acesso (bronze, prata, ouro). | [ADTU09](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Sim |
| RNF08 | O sistema deve ser acessível e disponível para todos os usuários, garantindo acessibilidade para usuários com deficiências e oferecendo suporte a múltiplas plataformas e navegadores. | [ADTU10](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Sim |
| RNF09 | O aplicativo deve ser seguro e confiável, protegendo os dados dos usuários. | [BS17](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Sim |
| RNF10 | O login deve ser feito de maneira rápida e segura. | [BS18](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Não |
| RNF11 | O aplicativo deve ser acessível a pessoas com deficiência. | [BS19](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Não |
| RNF12 | O aplicativo deve exigir que a senha do usuário possua obrigatoriamente letras, números e caracteres especiais. | [BS20](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Não |
| RNF13 | O aplicativo deve ser intuitivo e fácil de usar. | [BS21](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Não |
| RNF14 | O aplicativo deve ter boa performance e ser estável. | [BS22](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Não |
| RNF15 | O aplicativo deve ter suporte ao cliente eficiente. | [BS23](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Não |
| RNF16 | Segurança: O aplicativo deve garantir a segurança dos dados pessoais dos usuários. | [ST16](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Sim |
| RNF17 | Usabilidade: A interface do aplicativo deve ser simples e fácil de usar. | [ST17](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Sim |
| RNF18 | Eficiência: O aplicativo deve ser rápido no acesso e no agendamento de serviços. | [ST18](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Sim |
| RNF19 | Acessibilidade: O aplicativo deve ser acessível mesmo sem conexão com a internet. | [ST19](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Não |
| RNF20 | Confiabilidade: O aplicativo deve manter a integridade dos documentos e informações consultadas. | [ST20](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Sim |
| RNF21 | Atualização: O aplicativo deve manter os usuários informados sobre novidades e atualizações importantes. | [ST21](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Sim |
| RNF22 | Privacidade: Garantir que as informações dos usuários não sejam compartilhadas sem permissão. | [ST22](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Sim |
<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/TheCarlosRamos">Carlos Gabriel</a></p></font>


## Tabela de rastreamento dos requisitos funcionais
<font><p style="text-align: center">**Tabela 3:** Tabela de rastreamento dos requisitos funcionais.</p></font>

### Tabela de Elos de Rastreabilidade para RF

|   ID   |  Código  |                               Requisito                               |     Tipo de Elo      |                          Justificativa do Elo                          |
|:------:|:--------:|:---------------------------------------------------------------------:|:--------------------:|:-----------------------------------------------------------------------:|
| ELOB01 |  RF01    | O sistema deve oferecer reconhecimento facial para autenticação do usuário. | Recurso | Este requisito depende de recursos tecnológicos avançados para a funcionalidade de reconhecimento facial. |
| ELOB02 |  RF02    | O sistema deve permitir a recuperação de senha por meio de perguntas de segurança e/ou e-mail. | Responsabilidade | Este requisito envolve a responsabilidade de assegurar métodos seguros para recuperação de senha. |
| ELOB03 |  RF03    | O sistema deve permitir a verificação em duas etapas para maior segurança do login. | Recurso | Este requisito depende de recursos adicionais para implementar a verificação em duas etapas. |
| ELOB04 |  RF04    | O sistema deve oferecer acesso centralizado a serviços governamentais. | Agregação | Este requisito agrega múltiplos serviços governamentais sob uma única autenticação. |
| ELOB05 |  RF05    | O sistema deve permitir a notificação do usuário em caso de atividades suspeitas em sua conta. | Satisfação | Este requisito visa satisfazer a necessidade dos usuários de serem informados sobre atividades suspeitas. |
| ELOB06 |  RF06    | O sistema deve permitir a autenticação biométrica por meio de impressões digitais. | Recurso | Este requisito depende de recursos avançados para implementar a autenticação biométrica. |
| ELOB07 |  RF07    | O sistema deve permitir o acesso e gerenciamento de dados pessoais pelo usuário. | Responsabilidade | Este requisito envolve a responsabilidade de gerenciamento de dados pessoais pelos usuários. |
| ELOB08 |  RF08    | O sistema deve oferecer funcionalidades para recuperação de conta através de SMS, e-mail ou suporte direto. | Recurso | Este requisito depende de recursos para implementar múltiplas opções de recuperação de conta. |
| ELOB09 |  RF09    | O sistema deve permitir a visualização e gerenciamento de documentos digitais. | Recurso | Este requisito depende de recursos tecnológicos para visualização e gerenciamento de documentos digitais. |
| ELOB10 |  RF10    | O sistema deve permitir a prova de vida para utilização de serviços online. | Recurso | Este requisito depende de recursos avançados para implementar a funcionalidade de prova de vida. |
| ELOB11 |  RF11    | O aplicativo deve permitir que os usuários se autentiquem de forma segura, usando credenciais únicas, como CPF e senha. | Recurso | Este requisito depende de recursos tecnológicos para implementar uma autenticação segura. |
| ELOB12 |  RF12    | O usuário deve ser capaz de logar com as credenciais do gov.br. | Agregação | Este requisito agrega a funcionalidade de login do gov.br ao sistema. |
| ELOB13 |  RF13    | O usuário deve conseguir visualizar seus documentos. | Recurso | Este requisito depende de recursos tecnológicos para visualização de documentos. |
| ELOB14 |  RF14    | O usuário deve conseguir agendar serviços específicos. | Satisfação | Este requisito visa satisfazer a necessidade do usuário de agendar serviços. |
| ELOB15 |  RF15    | O usuário deve conseguir emitir/baixar certidões. | Recurso | Este requisito depende de recursos tecnológicos para emissão e download de certidões. |
| ELOB16 |  RF16    | O usuário deve conseguir se logar no aplicativo. | Recurso | Este requisito depende de recursos tecnológicos para implementar o login no aplicativo. |
| ELOB17 |  RF17    | O login deve possuir autenticação em dois fatores. | Recurso | Este requisito depende de recursos adicionais para implementar a autenticação em dois fatores. |
| ELOB18 |  RF18    | O usuário deve conseguir assinar documentos digitalmente. | Recurso | Este requisito depende de recursos tecnológicos para a assinatura digital de documentos. |
| ELOB19 |  RF19    | O usuário deve conseguir se inscrever em concursos públicos. | Satisfação | Este requisito visa satisfazer a necessidade do usuário de se inscrever em concursos públicos. |
| ELOB20 |  RF20    | O usuário deve conseguir consultar programas do governo. | Satisfação | Este requisito visa satisfazer a necessidade do usuário de consultar programas governamentais. |
| ELOB21 |  RF21    | O usuário deve conseguir se conectar com o Detran. | Agregação | Este requisito agrega a funcionalidade de conexão com o Detran ao sistema. |
| ELOB22 |  RF22    | O usuário deve conseguir se conectar com o NIS. | Agregação | Este requisito agrega a funcionalidade de conexão com o NIS ao sistema. |
| ELOB23 |  RF23    | O usuário deve conseguir se conectar com o ID Jovem. | Agregação | Este requisito agrega a funcionalidade de conexão com o ID Jovem ao sistema. |
| ELOB24 |  RF24    | O usuário deve conseguir usar o aplicativo para pagar impostos trabalhistas. | Recurso | Este requisito depende de recursos tecnológicos para a funcionalidade de pagamento de impostos trabalhistas. |
| ELOB25 |  RF25    | O usuário deve conseguir obter o código de acesso. | Recurso | Este requisito depende de recursos tecnológicos para a obtenção do código de acesso. |
| ELOB26 |  RF26    | O aplicativo deve possuir ferramentas de acessibilidade (Alto contraste, aumentar a fonte, audiodescrição). | Representação | Este requisito representa a necessidade de funcionalidades de acessibilidade. |
| ELOB27 |  RF27    | Como usuário, desejo acessar o aplicativo gov.br de forma rápida e intuitiva. | Satisfação | Este requisito visa satisfazer a necessidade do usuário de uma navegação rápida e intuitiva. |
| ELOB28 |  RF28    | Como usuário, desejo encontrar facilmente o serviço de agendamento na Receita Federal. | Satisfação | Este requisito visa satisfazer a necessidade do usuário de encontrar facilmente serviços de agendamento. |
| ELOB29 |  RF29    | Como usuário, desejo acessar as funções de assinatura digital para agilizar a assinatura de documentos. | Recurso | Este requisito depende de recursos tecnológicos para a assinatura digital de documentos. |
| ELOB30 |  RF30    | Como usuário, desejo agendar atendimentos em órgãos públicos através do aplicativo. | Satisfação | Este requisito visa satisfazer a necessidade do usuário de agendar atendimentos em órgãos públicos. |
| ELOB31 |  RF31    | Como usuário, desejo consultar informações sobre benefícios sociais através do aplicativo. | Satisfação | Este requisito visa satisfazer a necessidade do usuário de consultar informações sobre benefícios sociais. |
| ELOB32 |  RF32    | Como usuário, desejo substituir minha carteira física por uma versão digital no aplicativo. | Recurso | Este requisito depende de recursos tecnológicos para implementar a carteira digital. |
| ELOB33 |  RF33    | Como usuário, desejo continuar recebendo minha aposentadoria através da função de prova de vida. | Recurso | Este requisito depende de recursos tecnológicos para implementar a função de prova de vida. |
| ELOB34 |  RF34    | Como usuário, desejo uma navegação intuitiva para buscar processos e documentos. | Representação | Este requisito representa a necessidade de uma navegação intuitiva. |
| ELOB35 |  RF35    | Como usuário, desejo garantir a segurança na transmissão e armazenamento de documentos sensíveis. | Satisfação | Este requisito visa satisfazer a necessidade do usuário de segurança na transmissão e armazenamento de documentos sensíveis. |
| ELOB36 |  RF36    | Como usuário, desejo eficiência no agendamento e acompanhamento de processos. | Recurso | Este requisito depende de recursos tecnológicos para eficiência no agendamento e acompanhamento de processos. |
| ELOB37 |  RF37    | Como usuário, desejo receber atualizações relevantes sobre processos e benefícios sociais. | Satisfação | Este requisito visa satisfazer a necessidade do usuário de receber atualizações relevantes. |
| ELOB38 |  RF38    | Como usuário, desejo substituir minha carteira física por uma versão digital no aplicativo. | Recurso | Este requisito depende de recursos tecnológicos para implementar a carteira digital. |
| ELOB39 |  RF39    | Como usuário, desejo acesso rápido aos meus documentos no celular, sem a necessidade de documentos físicos. | Recurso | Este requisito depende de recursos tecnológicos para implementar o acesso rápido a documentos no celular. |
| ELOB40 |  RF40    | Como usuário, desejo poder acessar meus documentos mesmo sem conexão com a internet. | Recurso | Este requisito depende de recursos tecnológicos para implementar o acesso offline a documentos. |

<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/Caio-bergbjj">Caio Berg</a></p></font>

## Tabela de rastreamento dos requisitos não funcionais
<font><p style="text-align: center">**Tabela 4:** Tabela de rastreamento dos requisitos não funcionais.</p></font>

|   ID   |  Código  |                               Requisito                               |     Tipo de Elo      |                          Justificativa do Elo                          |
|:------:|:--------:|:---------------------------------------------------------------------:|:--------------------:|:-----------------------------------------------------------------------:|
| ELOB42 |  RNF01   | O sistema deve ser estável e confiável, funcionando corretamente sem travamentos ou fechamentos inesperados. | Satisfação | Este requisito garante a satisfação dos usuários com a estabilidade do sistema. |
| ELOB43 |  RNF02   | A interface do sistema deve ser clara e fácil de usar, evitando complexidades desnecessárias que possam confundir os usuários. | Representação | Este requisito representa a necessidade de uma interface intuitiva e de fácil uso. |
| ELOB44 |  RNF03   | As funcionalidades críticas, como reconhecimento facial e autenticação, devem ser otimizadas para operar de maneira rápida e eficiente. | Recurso | Este requisito depende dos recursos tecnológicos para garantir a eficiência das funcionalidades críticas. |
| ELOB45 |  RNF04   | O sistema deve assegurar o tratamento adequado dos dados sensíveis de acordo com a legislação (LGPD). | Responsabilidade | Este requisito envolve a responsabilidade de tratamento e proteção dos dados sensíveis conforme a LGPD. |
| ELOB46 |  RNF05   | O sistema deve obter consentimento explícito dos usuários para o tratamento de seus dados pessoais. | Responsabilidade | Este requisito assegura que os usuários concedam permissão para o tratamento de seus dados, sendo uma responsabilidade legal. |
| ELOB47 |  RNF06   | O sistema deve ser acessível através de diferentes dispositivos e navegadores. | Agregação | Este requisito indica a necessidade de compatibilidade com vários dispositivos e navegadores. |
| ELOB48 |  RNF07   | O sistema deve implementar múltiplos níveis de segurança de acesso (bronze, prata, ouro). | Alocado | Este requisito aloca diferentes níveis de segurança ao sistema, garantindo acessos diferenciados. |
| ELOB49 |  RNF08   | O sistema deve ser acessível e disponível para todos os usuários, garantindo acessibilidade para usuários com deficiências e oferecendo suporte a múltiplas plataformas e navegadores. | Representação | Este requisito representa a necessidade de acessibilidade universal. |
| ELOB50 |  RNF09   | O aplicativo deve ser seguro e confiável, protegendo os dados dos usuários. | Satisfação | Este requisito visa a satisfação do usuário com a segurança e confiabilidade do aplicativo. |
| ELOB51 |  RNF10   | O login deve ser feito de maneira rápida e segura. | Satisfação | Este requisito garante a satisfação do usuário com a rapidez e segurança no login. |
| ELOB52 |  RNF11   | O aplicativo deve ser acessível a pessoas com deficiência. | Representação | Este requisito representa a necessidade de inclusão e acessibilidade para todos os usuários. |
| ELOB53 |  RNF12   | O aplicativo deve exigir que a senha do usuário possua obrigatoriamente letras, números e caracteres especiais. | Responsabilidade | Este requisito envolve a responsabilidade de implementar políticas de senha segura. |
| ELOB54 |  RNF13   | O aplicativo deve ser intuitivo e fácil de usar. | Representação | Este requisito representa a necessidade de usabilidade e design intuitivo. |
| ELOB55 |  RNF14   | O aplicativo deve ter boa performance e ser estável. | Satisfação | Este requisito visa garantir a satisfação dos usuários com a performance e estabilidade do aplicativo. |
| ELOB56 |  RNF15   | O aplicativo deve ter suporte ao cliente eficiente. | Responsabilidade | Este requisito envolve a responsabilidade de oferecer suporte adequado aos usuários. |
| ELOB57 |  RNF16   | Segurança: O aplicativo deve garantir a segurança dos dados pessoais dos usuários. | Satisfação | Este requisito visa garantir a satisfação do usuário com a segurança dos dados pessoais. |
| ELOB58 |  RNF17   | Usabilidade: A interface do aplicativo deve ser simples e fácil de usar. | Representação | Este requisito representa a necessidade de uma interface fácil e acessível. |
| ELOB59 |  RNF18   | Eficiência: O aplicativo deve ser rápido no acesso e no agendamento de serviços. | Recurso | Este requisito depende dos recursos tecnológicos para garantir a eficiência do aplicativo. |
| ELOB60 |  RNF19   | Acessibilidade: O aplicativo deve ser acessível mesmo sem conexão com a internet. | Recurso | Este requisito depende de recursos técnicos para permitir a funcionalidade offline. |
| ELOB61 |  RNF20   | Confiabilidade: O aplicativo deve manter a integridade dos documentos e informações consultadas. | Satisfação | Este requisito visa garantir a satisfação dos usuários com a confiabilidade do aplicativo. |
| ELOB62 |  RNF21   | Atualização: O aplicativo deve manter os usuários informados sobre novidades e atualizações importantes. | Satisfação | Este requisito garante a satisfação dos usuários com a comunicação de atualizações importantes. |
| ELOB63 |  RNF22   | Privacidade: Garantir que as informações dos usuários não sejam compartilhadas sem permissão. | Responsabilidade | Este requisito envolve a responsabilidade de proteger a privacidade dos usuários. |

<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/TheCarlosRamos">Carlos Gabriel</a></p></font>

## Modelo de tabelas para Análise de Impacto de Mudanças

<font><p style="text-align: center">**Tabela 5:** Tabela para Análise de Impacto de Mudanças dos requisitos funcionais.</p></font>

| **ID do Requisito** | **Descrição do Requisito**                          | **Descrição da Mudança** | **Componentes Afetados** | **Casos de Uso Afetados** | **Casos de Teste Afetados** | **Ação Necessária** | **Responsável** | **Data da Mudança** | **Status da Mudança** | **Notas Adicionais** |
|--------------------|-----------------------------------------------------|--------------------------|-------------------------|-------------------------|--------------------------|--------------------|-----------------|--------------------|----------------------|----------------------|
| RF01               | Reconhecimento Facial                              |                          |                         |                         |                          |                    |                 |                    |                      |                      |
| RF02               | Recuperação de Senha                               |                          |                         |                         |                          |                    |                 |                    |                      |                      |
| RF03               | Verificação em Duas Etapas                         |                          |                         |                         |                          |                    |                 |                    |                      |                      |
| RF04               | Gerenciamento de Sessões                           |                          |                         |                         |                          |                    |                 |                    |                      |                      |
| RF05               | Registro de Atividades                            |                          |                         |                         |                          |                    |                 |                    |                      |                      |
| RF06               | Segurança de Dados                                 |                          |                         |                         |                          |                    |                 |                    |                      |                      |
| RF07               | Autenticação de Dois Fatores                       |                          |                         |                         |                          |                    |                 |                    |                      |                      |
| RF08               | Interface de Usuário                                |                          |                         |                         |                          |                    |                 |                    |                      |                      |
| RF09               | Integridade dos Dados                              |                          |                         |                         |                          |                    |                 |                    |                      |                      |
| RF10               | Auditoria de Acesso                                 |                          |                         |                         |                          |                    |                 |                    |                      |                      |
| RF11               | Autenticação com Credenciais Únicas                    |                          |                         |                         |                          |                    |                 |                    |                      |                      |
| RF12               | Logar com Credenciais do gov.br                         |                          |                         |                         |                          |                    |                 |                    |                      |                      |
| RF13               | Visualização de Documentos                             |                          |                         |                         |                          |                    |                 |                    |                      |                      |
| RF14               | Agendamento de Serviços                                |                          |                         |                         |                          |                    |                 |                    |                      |                      |
| RF15               | Emissão e Download de Certidões                         |                          |                         |                         |                          |                    |                 |                    |                      |                      |
| RF16               | Logar no Aplicativo                                    |                          |                         |                         |                          |                    |                 |                    |                      |                      |
| RF17               | Autenticação em Dois Fatores                            |                          |                         |                         |                          |                    |                 |                    |                      |                      |
| RF18               | Assinatura Digital de Documentos                        |                          |                         |                         |                          |                    |                 |                    |                      |                      |
| RF19               | Inscrição em Concursos Públicos                         |                          |                         |                         |                          |                    |                 |                    |                      |                      |
| RF20               | Consulta de Programas do Governo                        |                          |                         |                         |                          |                    |                 |                    |                      |                      |
| RF21               | Conexão com o Detran                                    |                          |                         |                         |                          |                    |                 |                    |                      |                      |
| RF22               | Conexão com o NIS                                      |                          |                         |                         |                          |                    |                 |                    |                      |                      |
| RF23               | Conexão com o ID Jovem                                  |                          |                         |                         |                          |                    |                 |                    |                      |                      |
| RF24               | Pagamento de Impostos Trabalhistas                     |                          |                         |                         |                          |                    |                 |                    |                      |                      |
| RF25               | Obter Código de Acesso                                 |                          |                         |                         |                          |                    |                 |                    |                      |                      |
| RF26               | Ferramentas de Acessibilidade                           |                          |                         |                         |                          |                    |                 |                    |                      |                      |
| RF27               | Acesso Intuitivo ao Aplicativo                          |                          |                         |                         |                          |                    |                 |                    |                      |                      |
| RF28               | Encontrar Serviço de Agendamento na Receita Federal    |                          |                         |                         |                          |                    |                 |                    |                      |                      |
| RF29               | Assinatura Digital de Documentos                        |                          |                         |                         |                          |                    |                 |                    |                      |                      |
| RF30               | Agendamento de Atendimentos                            |                          |                         |                         |                          |                    |                 |                    |                      |                      |
| RF31               | Consultar Benefícios Sociais                           |                          |                         |                         |                          |                    |                 |                    |                      |                      |
| RF32               | Substituir Carteira Física por Versão Digital           |                          |                         |                         |                          |                    |                 |                    |                      |                      |
| RF33               | Prova de Vida para Aposentadoria                        |                          |                         |                         |                          |                    |                 |                    |                      |                      |
| RF34               | Navegação Intuitiva para Processos e Documentos         |                          |                         |                         |                          |                    |                 |                    |                      |                      |
| RF35               | Segurança na Transmissão e Armazenamento de Documentos |                          |                         |                         |                          |                    |                 |                    |                      |                      |
| RF36               | Eficiência no Agendamento e Acompanhamento de Processos |                          |                         |                         |                          |                    |                 |                    |                      |                      |
| RF37               | Atualizações Relevantes sobre Processos e Benefícios    |                          |                         |                         |                          |                    |                 |                    |                      |                      |
| RF38               | Substituir Carteira Física por Versão Digital           |                          |                         |                         |                          |                    |                 |                    |                      |                      |
| RF39               | Acesso Rápido aos Documentos no Celular                 |                          |                         |                         |                          |                    |                 |                    |                      |                      |
| RF40               | Acesso Offline aos Documentos                          |                          |                         |                         |                          |                    |                 |                    |                      |                      |

<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/TheCarlosRamos">Carlos Gabriel</a></p></font>


<font><p style="text-align: center">**Tabela 6:** Tabela para Análise de Impacto de Mudanças dos requisitos não funcionais.</p></font>

| **ID do Requisito** | **Descrição do Requisito**                                                     | **Descrição da Mudança** | **Componentes Afetados** | **Casos de Teste Afetados** | **Ação Necessária** | **Responsável** | **Data da Mudança** | **Status da Mudança** | **Notas Adicionais** |
|--------------------|----------------------------------------------------------------------------------|-------------------------|-------------------------|--------------------------|---------------------|-----------------|--------------------|----------------------|----------------------|
| RNF01              | O sistema deve ser estável e confiável, funcionando corretamente sem travamentos ou fechamentos inesperados. |                         |                         |                          |                     |                 |                    |                      |
| RNF02              | A interface do sistema deve ser clara e fácil de usar, evitando complexidades desnecessárias que possam confundir os usuários. |                         |                         |                          |                     |                 |                    |                      |
| RNF03              | As funcionalidades críticas, como reconhecimento facial e autenticação, devem ser otimizadas para operar de maneira rápida e eficiente. |                         |                         |                          |                     |                 |                    |                      |
| RNF04              | O sistema deve assegurar o tratamento adequado dos dados sensíveis de acordo com a legislação (LGPD). |                         |                         |                          |                     |                 |                    |                      |
| RNF05              | O sistema deve obter consentimento explícito dos usuários para o tratamento de seus dados pessoais. |                         |                         |                          |                     |                 |                    |                      |
| RNF06              | O sistema deve ser acessível através de diferentes dispositivos e navegadores. |                         |                         |                          |                     |                 |                    |                      |
| RNF07              | O sistema deve implementar múltiplos níveis de segurança de acesso (bronze, prata, ouro). |                         |                         |                          |                     |                 |                    |                      |
| RNF08              | O sistema deve ser acessível e disponível para todos os usuários, garantindo acessibilidade para usuários com deficiências e oferecendo suporte a múltiplas plataformas e navegadores. |                         |                         |                          |                     |                 |                    |                      |
| RNF09              | O aplicativo deve ser seguro e confiável, protegendo os dados dos usuários. |                         |                         |                          |                     |                 |                    |                      |
| RNF10              | O login deve ser feito de maneira rápida e segura. |                         |                         |                          |                     |                 |                    |                      |
| RNF11              | O aplicativo deve ser acessível a pessoas com deficiência. |                         |                         |                          |                     |                 |                    |                      |
| RNF12              | O aplicativo deve exigir que a senha do usuário possua obrigatoriamente letras, números e caracteres especiais. |                         |                         |                          |                     |                 |                    |                      |
| RNF13              | O aplicativo deve ser intuitivo e fácil de usar. |                         |                         |                          |                     |                 |                    |                      |
| RNF14              | O aplicativo deve ter boa performance e ser estável. |                         |                         |                          |                     |                 |                    |                      |
| RNF15              | O aplicativo deve ter suporte ao cliente eficiente. |                         |                         |                          |                     |                 |                    |                      |
| RNF16              | Segurança: O aplicativo deve garantir a segurança dos dados pessoais dos usuários. |                         |                         |                          |                     |                 |                    |                      |
| RNF17              | Usabilidade: A interface do aplicativo deve ser simples e fácil de usar. |                         |                         |                          |                     |                 |                    |                      |
| RNF18              | Eficiência: O aplicativo deve ser rápido no acesso e no agendamento de serviços. |                         |                         |                          |                     |                 |                    |                      |
| RNF19              | Acessibilidade: O aplicativo deve ser acessível mesmo sem conexão com a internet. |                         |                         |                          |                     |                 |                    |                      |
| RNF20              | Confiabilidade: O aplicativo deve manter a integridade dos documentos e informações consultadas. |                         |                         |                          |                     |                 |                    |                      |
| RNF21              | Atualização: O aplicativo deve manter os usuários informados sobre novidades e atualizações importantes. |                         |                         |                          |                     |                 |                    |                      |
| RNF22              | Privacidade: Garantir que as informações dos usuários não sejam compartilhadas sem permissão. |                         |                         |                          |                     |                 |                    |                      |

<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/TheCarlosRamos">Carlos Gabriel</a></p></font>


## Referência Bibliografia

> [1] Monografia - Miriam Sayão e Julio Prado Leite Disponível em: <https://www.dbd.puc-rio.br/depto_informatica/05_20_sayao.pdf> Acesso em 21 de Junho de 2024

## Histórico de Versão

| Versão  | Data | Descrição | Autor(es) | Revisor(es) |
| -------- | ------ | ------ | ---------- | ---------- |
|1.0 | 21/06/2024 | Criação do Documento | [Carlos Gabriel](https://github.com/TheCarlosRamos) , [Thiago Freitas](https://github.com/thiagorfreitas) |[Caio Berg](https://github.com/Caio-bergbjj)|
|1.1 | 24/06/2024 | Alteração de Elos | [Caio Berg](https://github.com/Caio-bergbjj) | [Carlos Gabriel](https://github.com/TheCarlosRamos) |
|1.2 | 06/07/2024 | Adição dos modelos de tabelas de impácto de mudanças | [Carlos Gabriel](https://github.com/TheCarlosRamos) | [Thiago Freitas](https://github.com/thiagorfreitas), [Caio Berg](https://github.com/Caio-bergbjj) |
