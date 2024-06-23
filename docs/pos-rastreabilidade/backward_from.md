
# Backward-From

## Introdução

O Backward-From é uma metodologia de desenvolvimento de software que se diferencia por iniciar com o resultado final desejado em mente. Ao invés de partir de requisitos e funcionalidades pré-definidos, o Backward-From traça um roteiro a partir do que se deseja alcançar, definindo:

Experiência do Usuário: Detalhando como os usuários interagirão com o software, quais funcionalidades serão acessadas e como cada ação trará benefícios para eles.
Validação Contínua: Obtendo feedback dos usuários e stakeholders ao longo do processo, adaptando o software às necessidades e expectativas identificadas.

Ao aliar a rastreabilidade à metodologia Backward-From, as equipes de desenvolvimento podem alcançar um novo patamar de eficiência, qualidade e sucesso em seus projetos. Essa união estratégica garante que o software seja desenvolvido de forma clara, precisa, alinhada às expectativas dos usuários e com foco na entrega de resultados valiosos.

## Metodologia

A metodologia de rastreabilidade de requisitos proposta por Toranzo, é uma abordagem abrangente para mapear e documentar as relações entre requisitos, casos de uso, testes e outros elementos de um projeto de software.
Seu principal objetivo é garantir que cada requisito seja implementado e testado corretamente.

Tipos de Elos da Rastreabilidade
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

Primeiramente, foi separado em duas tabelas: os requisitos funcionais e não funcionais com as suas informações emrelação à sua rastreabilidade e implementação.
Consequentemente, foi criada uma tabela com os requisitos destacando o tipo de elo da rastreabilidade, sua justificativa e a ligação.

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
|:------:|:-----------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|:------------:|
| RF01   | O sistema deve possuir uma funcionalidade de reconhecimento facial para autenticação do usuário. | [ADFU01](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Sim |
| RF02   | O sistema deve permitir que os usuários recuperem suas senhas através de métodos seguros e eficientes. | [ADFU02](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Sim |
| RF03   | O sistema deve oferecer verificação em duas etapas como uma camada adicional de segurança para os usuários. | [ADFU03](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Sim |
| RF04   | O sistema deve permitir que os usuários utilizem suas credenciais para acessar diferentes serviços governamentais de forma centralizada. | [ADFU04](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Sim |
| RF05   | O sistema deve facilitar o processo de mudança de celular pelo usuário, permitindo a transferência de segurança e autenticações sem necessidade de cancelar e recriar a conta. | [ADFU05](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Sim |
| RF06   | O sistema deve notificar os usuários de quaisquer acessos não autorizados ou mudanças críticas na segurança de suas contas. | [ADFU06](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Sim |
| RF07   | O sistema deve permitir a autenticação do usuário utilizando métodos como biometria facial e validação biográfica. | [ADTU01](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Sim |
| RF08   | O sistema deve permitir ao usuário acessar, atualizar e excluir seus dados pessoais. | [ADTU02](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Sim |
| RF09   | O sistema deve oferecer funcionalidades para recuperação de conta através de SMS, e-mail ou suporte direto. | [ADTU03](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Sim |
| RF10   | O sistema deve permitir aos usuários visualizar e gerenciar documentos digitais associados à sua conta. | [ADTU04](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Sim |
| RF11   | O sistema deve oferecer uma funcionalidade de Prova de Vida para verificação de beneficiários de programas de previdência ou assistência social. | [ADTU05](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Sim |
| RF12   | O aplicativo deve permitir que os usuários se autentiquem de forma segura, usando credenciais únicas, como CPF e senha. | [BS01](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Sim |
| RF13   | O usuário deve ser capaz de logar com as credenciais do gov.br. | [BS02](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Sim |
| RF14   | O usuário deve conseguir visualizar seus documentos. | [BS03](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Sim |
| RF15   | O usuário deve conseguir agendar serviços específicos. | [BS04](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Não |
| RF16   | O usuário deve conseguir emitir/baixar certidões. | [BS05](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Sim |
| RF17   | O usuário deve conseguir se logar no aplicativo. | [BS06](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Sim |
| RF18   | O login deve possuir autenticação em dois fatores. | [BS07](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Sim |
| RF19   | O usuário deve conseguir assinar documentos digitalmente. | [BS08](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Sim |
| RF20   | O usuário deve conseguir se inscrever em concursos públicos. | [BS09](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Não |
| RF21   | O usuário deve conseguir consultar programas do governo. | [BS10](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Não |
| RF22   | O usuário deve conseguir se conectar com o Detran. | [BS11](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Não |
| RF23   | O usuário deve conseguir se conectar com o NIS. | [BS12](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Não |
| RF24   | O usuário deve conseguir se conectar com o ID Jovem. | [BS13](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Não |
| RF25   | O usuário deve conseguir usar o aplicativo para pagar impostos trabalhistas. | [BS14](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Não |
| RF26   | O usuário deve conseguir obter o código de acesso. | [BS15](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Sim |
| RF27   | O aplicativo deve possuir ferramentas de acessibilidade (Alto contraste, aumentar a fonte, audiodescrição). | [BS16](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Não |
| RF28   | Como usuário, desejo acessar o aplicativo gov.br de forma rápida e intuitiva. | [ST01](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Sim |
| RF29   | Como usuário, desejo encontrar facilmente o serviço de agendamento na Receita Federal. | [ST02](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Sim |
| RF30   | Como usuário, desejo acessar as funções de assinatura digital para agilizar a assinatura de documentos. | [ST03](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Sim |
| RF31   | Como usuário, desejo agendar atendimentos em órgãos públicos através do aplicativo. | [ST04](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Não |
| RF32   | Como usuário, desejo consultar informações sobre benefícios sociais através do aplicativo. | [ST05](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Não |
| RF33   | Como usuário, desejo acessar a função de carteira digital no aplicativo. | [ST06](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Não |
| RF34   | Como usuário, desejo continuar recebendo minha aposentadoria através da função de prova de vida. | [ST07](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Não |
| RF35   | Como usuário, desejo uma navegação intuitiva para buscar processos e documentos. | [ST08](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Sim |
| RF36   | Como usuário, desejo garantir a segurança na transmissão e armazenamento de documentos sensíveis. | [ST09](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Sim |
| RF37   | Como usuário, desejo poder alterar minhas informações pessoais de forma prática e rápida. | [ST10](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Sim |
| RF38   | Como usuário, desejo uma opção de ajuda no aplicativo para dúvidas e suporte técnico. | [ST11](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Sim |
| RF39   | Como usuário, desejo acessar rapidamente a área de agendamento de consultas e serviços públicos. | [ST12](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Sim |
| RF40   | Como usuário, desejo poder recuperar minha senha com facilidade. | [ST13](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Sim |
| RF41   | Como usuário, desejo uma interface clara e de fácil uso no aplicativo gov.br. | [ST14](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Sim |
| RF42   | Como usuário, desejo que o aplicativo gov.br ofereça suporte para biometria. | [ST15](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Sim |
| RF43   | Como usuário, desejo acessar o gov.br para facilitar minhas interações com o governo. | [ST16](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) | Sim |


### Requisitos Não Funcionais (RNF)

<font><p style="text-align: center">**Tabela 2:** Tabela de requisitos não funcionais.</p></font>


|  ID  |                                Descrição                                |                                  Rastreabilidade                                 | Implementado |
|:------:|:-----------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|:------------:|
| RNF01  | O sistema deve estar disponível 99.9% do tempo para garantir a acessibilidade dos usuários. | [ADFU07](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Sim |
| RNF02  | O sistema deve garantir a segurança e privacidade dos dados dos usuários, conforme a Lei Geral de Proteção de Dados (LGPD). | [ADFU08](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Sim |
| RNF03  | O sistema deve ser compatível com diferentes dispositivos e sistemas operacionais (Android, iOS, etc.). | [ADTU06](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Sim |
| RNF04  | O sistema deve proporcionar uma interface intuitiva e amigável, facilitando a navegação do usuário. | [ADTU07](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Sim |
| RNF05  | O sistema deve responder de forma eficiente, com tempo de resposta inferior a 2 segundos para qualquer ação do usuário. | [ADTU08](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Sim |
| RNF06  | O sistema deve suportar um alto número de acessos simultâneos sem perda de desempenho. | [ADTU09](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Sim |
| RNF07  | O sistema deve seguir padrões de acessibilidade, como WCAG 2.1, para garantir que pessoas com deficiência possam utilizá-lo. | [ADTU10](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Não |
| RNF08  | O sistema deve permitir a integração com APIs de serviços governamentais externos de forma segura e eficiente. | [ADTU11](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Sim |
| RNF09  | O sistema deve fornecer logs detalhados de acesso e operações realizadas, para fins de auditoria e monitoramento. | [ADTU12](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Sim |
| RNF10  | O sistema deve ser escalável, permitindo a adição de novos serviços e funcionalidades sem grandes reestruturações. | [ADTU13](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Sim |
| RNF11  | O sistema deve realizar backups diários dos dados dos usuários para evitar perda de informações. | [ADTU14](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Sim |
| RNF12  | O sistema deve ser capaz de recuperar-se automaticamente de falhas, garantindo a continuidade do serviço. | [ADTU15](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) | Sim |
| RNF13  | O sistema deve utilizar algoritmos de criptografia atualizados para proteger dados sensíveis durante a transmissão e armazenamento. | [BS17](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Sim |
| RNF14  | O sistema deve garantir a conformidade com as regulamentações locais e internacionais de proteção de dados. | [BS18](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Sim |
| RNF15  | O sistema deve suportar várias línguas para atender a usuários de diferentes regiões do Brasil. | [BS19](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Não |
| RNF16  | O sistema deve fornecer atualizações regulares e automáticas para melhorar a segurança e as funcionalidades. | [BS20](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Sim |
| RNF17  | O sistema deve ser compatível com diversas versões de navegadores e sistemas operacionais. | [BS21](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Sim |
| RNF18  | O sistema deve ser documentado de forma completa e clara para facilitar a manutenção e a futura expansão. | [BS22](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Sim |
| RNF19  | O sistema deve ser desenvolvido seguindo boas práticas de engenharia de software, como testes automatizados e integração contínua. | [BS23](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Sim |
| RNF20  | O sistema deve garantir que a autenticação seja realizada em tempo real para evitar acessos não autorizados. | [BS24](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) | Sim |



## Tabela de rastreamento dos requisitos funcionais
<font><p style="text-align: center">**Tabela 3:** Tabela de rastreamento dos requisitos funcionais.</p></font>

| ID | Requisito | Tipo de Elo | Justificativa do Elo | Ligações |
|---|---|---|---|---|
| RF01 | O sistema deve possuir uma funcionalidade de reconhecimento facial para autenticação do usuário. | **Representação, Responsabilidade** | A autenticação facial oferece maior segurança e comodidade para o usuário. | - |
| RF02 | O sistema deve permitir que os usuários recuperem suas senhas através de métodos seguros e eficientes. | **Representação, Responsabilidade** | A recuperação de senha é crucial para garantir o acesso do usuário ao sistema em caso de esquecimento da senha. | - |
| RF03 | O sistema deve oferecer verificação em duas etapas como uma camada adicional de segurança para os usuários. | **Representação, Responsabilidade** | A verificação em duas etapas aumenta a segurança do sistema, dificultando acessos não autorizados. | - |
| RF04 | O sistema deve permitir que os usuários utilizem suas credenciais para acessar diferentes serviços governamentais de forma centralizada. | **Representação, Responsabilidade** | A autenticação centralizada facilita o acesso do usuário a diversos serviços, sem a necessidade de criar várias contas. | - |
| RF05 | O sistema deve facilitar o processo de mudança de celular pelo usuário, permitindo a transferência de segurança e autenticações sem necessidade de cancelar e recriar a conta. | **Representação, Responsabilidade** | A mudança de celular deve ser um processo simples e seguro para o usuário, preservando seus dados e autenticações. | - |
| RF06 | O sistema deve notificar os usuários de quaisquer acessos não autorizados ou mudanças críticas na segurança de suas contas. | **Representação, Responsabilidade** | As notificações alertam o usuário sobre atividades suspeitas em sua conta, permitindo que ele tome medidas cabíveis. | - |
| RF07 | O sistema deve permitir a autenticação do usuário utilizando métodos como biometria facial e validação biográfica. | **Representação, Responsabilidade** | A autenticação biométrica oferece maior segurança e comodidade para o usuário, além de evitar a digitação de senhas. | RF01 |
| RF08 | O sistema deve permitir ao usuário acessar, atualizar e excluir seus dados pessoais. | **Representação, Responsabilidade** | O usuário tem o direito de controlar seus dados pessoais, podendo acessá-los, atualizá-los ou excluí-los. | - |
| RF09 | O sistema deve oferecer funcionalidades para recuperação de conta através de SMS, e-mail ou suporte direto. | **Representação, Responsabilidade** | O usuário deve ter diversas opções para recuperar sua conta em caso de esquecimento da senha ou bloqueio da conta. | RF02 |
| RF10 | O sistema deve permitir aos usuários visualizar e gerenciar documentos digitais associados à sua conta. | **Representação, Responsabilidade** | O acesso e gerenciamento de documentos digitais facilitam a vida do usuário, permitindo que ele armazene e consulte documentos importantes de forma segura. | - |
| RF11 | O sistema deve oferecer uma funcionalidade de Prova de Vida para verificação de beneficiários de programas de previdência ou assistência social. | **Representação, Responsabilidade** | A Prova de Vida garante a autenticidade do beneficiário e evita fraudes em programas sociais. | - |
| RF12 | O aplicativo deve permitir que os usuários se autentiquem de forma segura, usando credenciais únicas, como CPF e senha. | **Representação, Responsabilidade** | A autenticação segura do aplicativo garante o acesso autorizado do usuário e protege seus dados. | RF04, RF17 |
| RF13 | O usuário deve ser capaz de logar com as credenciais do gov.br. | **Alocado** | A integração com o gov.br facilita o login do usuário, permitindo que ele utilize suas credenciais existentes. | RF12 |
| RF14 | O usuário deve conseguir visualizar seus documentos. | **Representação, Responsabilidade** | A visualização de documentos é essencial para que o usuário possa consultar e gerenciar seus documentos importantes. | RF10 |
| RF15 | O usuário deve conseguir agendar serviços específicos. | **Representação, Responsabilidade** | O agendamento de serviços online facilita o acesso do usuário aos serviços públicos e evita filas. | - |
| RF16 | O usuário deve conseguir emitir/baixar certidões. | **Representação, Responsabilidade** | A emissão e download de certidões online proporcionam praticidade e agilidade para o usuário. | - |
| RF17 | O usuário deve conseguir se logar no aplicativo. | **Alocado** | O login é uma funcionalidade central do aplicativo, permitindo o acesso do usuário ao sistema. | RF12 |
| RF18 | O login deve possuir autenticação em dois fatores. | Representação, Responsabilidade | A autenticação em dois fatores aumenta a segurança do login, dificultando acessos não autorizados. | RF12 |
| RF19 | O usuário deve conseguir assinar documentos digitalmente. | Representação, Responsabilidade | A assinatura digital agiliza processos e evita a necessidade de impressão e assinatura física de documentos. | - |
| RF20 | O usuário deve conseguir se inscrever em concursos públicos. | Representação, Responsabilidade | A inscrição online em concursos públicos facilita o acesso do usuário e torna o processo mais transparente. | - |
| RF21 | O usuário deve conseguir consultar programas do governo. | Representação, Responsabilidade | A consulta a programas do governo facilita o acesso do usuário a informações sobre benefícios e serviços públicos. | - |
| RF22 | O usuário deve conseguir se conectar com o Detran. | Alocado | A integração com o Detran permite ao usuário acessar serviços do Detran diretamente pelo aplicativo. | - |
| RF23 | O usuário deve conseguir se conectar com o NIS. | Alocado | A integração com o NIS permite ao usuário acessar serviços do NIS diretamente pelo aplicativo. | - |
| RF24 | O usuário deve conseguir se conectar com o ID Jovem. | Alocado | A integração com o ID Jovem permite ao usuário acessar serviços relacionados ao ID Jovem diretamente pelo aplicativo. | - |
| RF25 | O usuário deve conseguir usar o aplicativo para pagar impostos trabalhistas. | Representação, Responsabilidade | O pagamento de impostos online facilita a vida do usuário e agiliza o processo. | - |
| RF26 | O usuário deve conseguir obter o código de acesso. | Representação, Responsabilidade | O código de acesso é necessário para realizar diversas ações no sistema, como a recuperação de senha. | RF02, RF09 |
| RF27 | O aplicativo deve possuir ferramentas de acessibilidade (Alto contraste, aumentar a fonte, audiodescrição). | Responsabilidade | A implementação de ferramentas de acessibilidade (alto contraste, aumento da fonte, audiodescrição) garante que o aplicativo seja acessível a todos os usuários, incluindo aqueles com deficiências visuais ou auditivas. | - |
| RF28 | Como usuário, desejo acessar o aplicativo gov.br de forma rápida e intuitiva. | Representação | Este requisito representa o desejo do usuário de ter um acesso rápido e intuitivo ao aplicativo. É importante documentar este desejo para que a equipe de desenvolvimento possa considerar a usabilidade do aplicativo durante o processo de design e desenvolvimento. | - |
| RF29 | Como usuário, desejo encontrar facilmente o serviço de agendamento na Receita Federal. | Representação, Responsabilidade | Este requisito representa o desejo do usuário de encontrar facilmente o serviço de agendamento na Receita Federal. A funcionalidade de agendamento deve ser fácil de encontrar e usar, e deve estar integrada ao sistema da Receita Federal. | RF15 (Agendamento de serviços específicos) |
| RF30 | Como usuário, desejo acessar as funções de assinatura digital para agilizar a assinatura de documentos. | Representação, Responsabilidade | Este requisito representa o desejo do usuário de ter acesso às funções de assinatura digital para agilizar a assinatura de documentos. A funcionalidade de assinatura digital deve ser segura, fácil de usar e integrada ao sistema de assinatura digital do governo. | RF19 (Assinar documentos digitalmente) |
| RF31 | Como usuário, desejo agendar atendimentos em órgãos públicos através do aplicativo. | Responsabilidade, Representação | **Responsabilidade:** Módulo de agendamento de atendimentos é responsável por implementar a funcionalidade. <br/>**Representação:** A funcionalidade de agendamento deve estar disponível na interface do aplicativo para que o usuário possa pesquisar, selecionar e agendar atendimentos em órgãos públicos. | - |
| RF32 | Como usuário, desejo consultar informações sobre benefícios sociais através do aplicativo. | Responsabilidade, Representação | **Responsabilidade:** Módulo de consulta de benefícios sociais é responsável por implementar a funcionalidade. <br/>**Representação:** A funcionalidade de consulta de benefícios deve estar disponível na interface do aplicativo para que o usuário possa pesquisar e obter informações sobre seus benefícios sociais. | RF21 (Consultar programas do governo) |
| RF33 | Como usuário, desejo acessar a função de carteira digital no aplicativo. | Responsabilidade, Representação | **Responsabilidade:** Módulo de carteira digital é responsável por implementar a funcionalidade. <br/>**Representação:** A funcionalidade de carteira digital deve estar disponível na interface do aplicativo para que o usuário possa armazenar e gerenciar seus documentos digitais, como carteira de identidade, CPF e cartões de pagamento. | - |
| RF34 | Como usuário, desejo continuar recebendo minha aposentadoria através da função de prova de vida. | Responsabilidade, Representação | **Responsabilidade:** Módulo de Prova de Vida é responsável por implementar a funcionalidade. <br/>**Representação:** A funcionalidade de Prova de Vida deve estar disponível na interface do aplicativo para que os beneficiários aposentados possam realizar a prova de vida de forma remota e segura. | RF11 (Prova de Vida) |
| RF35 | Como usuário, desejo uma navegação intuitiva para buscar processos e documentos. | Representação | **Representação:** A interface de busca deve ser intuitiva e permitir que o usuário encontre facilmente processos e documentos relevantes utilizando filtros e palavras-chave. | - |
| RF36 | Como usuário, desejo garantir a segurança na transmissão e armazenamento de documentos sensíveis. | Responsabilidade | **Responsabilidade:** Módulo de segurança da informação é responsável por implementar medidas de segurança para proteger os dados dos usuários. | - |
| RF37 | Como usuário, desejo poder alterar minhas informações pessoais de forma prática e rápida. | Responsabilidade, Representação | **Responsabilidade:** Módulo de gerenciamento de dados pessoais é responsável por implementar a funcionalidade de edição de dados. <br/>**Representação:** A funcionalidade de edição de dados pessoais deve estar disponível na interface do aplicativo para que o usuário possa atualizar suas informações de forma prática e rápida. | RF08 (Acessar, atualizar e excluir dados pessoais) |
| RF38 | Como usuário, desejo uma opção de ajuda no aplicativo para dúvidas e suporte técnico. | Responsabilidade, Representação | **Responsabilidade:** Módulo de suporte ao usuário é responsável por implementar a funcionalidade de ajuda. <br/>**Representação:** A funcionalidade de ajuda deve estar disponível na interface do aplicativo para que o usuário possa encontrar respostas para suas dúvidas, acessar tutoriais ou entrar em contato com o suporte técnico. | - |
| RF39 | Como usuário, desejo acessar rapidamente a área de agendamento de consultas e serviços públicos. | Representação | **Representação:** A área de agendamento de consultas e serviços públicos deve ser facilmente acessível na interface do aplicativo, permitindo que o usuário visualize e acesse rapidamente a funcionalidade de agendamento. | RF15 (Agendamento de serviços específicos) |
| RF40 | Como usuário, desejo poder recuperar minha senha com facilidade. | Responsabilidade, Representação | **Responsabilidade:** Módulo de recuperação de senha é responsável por implementar a funcionalidade. <br/>**Representação:** A funcionalidade de recuperação de senha deve estar disponível na interface do aplicativo e permitir que o usuário recupere sua senha através de métodos seguros, como email, SMS ou perguntas de segurança. | RF02 (Recuperar senhas) , RF09 (Recuperação de conta) |
| RF41 | Como usuário, desejo uma interface clara e de fácil uso no aplicativo gov.br. | Representação | **Representação:** A interface do aplicativo deve ser clara, intuitiva e visualmente agradável, utilizando elementos gráficos e de texto que facilitem a navegação e o uso das funcionalidades. | - |
| RF42 | Como usuário, desejo que o aplicativo gov.br ofereça suporte para biometria. | Responsabilidade, Representação | **Responsabilidade:** Módulo de autenticação biométrica é responsável por implementar o suporte à biometria. <br/>**Representação:** O aplicativo deve oferecer a opção de utilizar biometria, como reconhecimento facial ou digital, para autenticação e acesso às funcionalidades. | - |
| RF43 | Como usuário, desejo acessar o gov.br para facilitar minhas interações com o governo. | Representação | **Representação:** O aplicativo gov.br deve centralizar o acesso a diversos serviços públicos, permitindo que o usuário realize diversas tarefas de forma online, como agendar consultas, emitir documentos, consultar benefícios e acessar informações de órgãos públicos. | RF01 (Reconhecimento facial para autenticação) |



## Tabela de rastreamento dos requisitos não funcionais
<font><p style="text-align: center">**Tabela 4:** Tabela de rastreamento dos requisitos não funcionais.</p></font>

| Código | Requisito | Tipo de Elo | Justificativa do Elo | Ligações |
|---|---|---|---|---|
| RNF01 | Disponibilidade de 99.9% | Satisfação | A disponibilidade de 99.9% (ADFU07) é crucial para atender à necessidade de acessibilidade dos usuários (RNF01). | ADFU07 |
| RNF02 | Segurança e Privacidade de Dados | Satisfação | A segurança e privacidade dos dados (ADFU08) são essenciais para cumprir a Lei Geral de Proteção de Dados (LGPD) (RNF02). | ADFU08, LGPD |
| RNF03 | Compatibilidade com Dispositivos e Sistemas Operacionais | Satisfação | A compatibilidade com diferentes dispositivos e sistemas operacionais (ADTU06) garante que o sistema atenda à necessidade de acessibilidade em diversas plataformas (RNF03). | ADTU06 |
| RNF04 | Interface Intuitiva e Amigável | Satisfação | Uma interface intuitiva e amigável (ADTU07) facilita a navegação do usuário, proporcionando uma boa experiência (RNF04). | ADTU07 |
| RNF05 | Tempo de Resposta Inferior a 2 Segundos | Satisfação | Um tempo de resposta inferior a 2 segundos (ADTU08) garante a eficiência do sistema e evita frustrações do usuário (RNF05). | ADTU08 |
| RNF06 | Suporte a Alto Número de Acessos Simultâneos | Satisfação | O suporte a um alto número de acessos simultâneos (ADTU09) garante a escalabilidade do sistema e sua capacidade de atender à demanda (RNF06). | ADTU09 |
| RNF07 | Implementação de Padrões de Acessibilidade | Alocado | A implementação de padrões de acessibilidade (ADTU10) está relacionada à classe de software que gerencia a interface do usuário (RNF07). | ADTU10 |
| RNF08 | Integração com APIs de Serviços Governamentais | Satisfação | A integração com APIs de serviços governamentais (ADTU11) permite que o sistema atenda à necessidade de interoperabilidade com outros serviços públicos (RNF08). | ADTU11 |
| RNF09 | Fornecimento de Logs Detalhados | Satisfação | O fornecimento de logs detalhados (ADTU12) permite auditoria e monitoramento, garantindo a segurança e confiabilidade do sistema (RNF09). | ADTU12 |
| RNF10 | Escalabilidade do Sistema | Satisfação | A escalabilidade do sistema (ADTU13) permite a adição de novos serviços e funcionalidades sem grandes reestruturações, atendendo à necessidade de crescimento (RNF10). | ADTU13 |
| RNF11 | Backups Diários | Satisfação | A realização de backups diários (ADTU14) evita a perda de informações valiosas dos usuários, garantindo a segurança e a confiabilidade do sistema (RNF11). | ADTU14 |
| RNF12 | Recuperação Automática de Falhas | Satisfação | A capacidade de recuperação automática de falhas (ADTU15) garante a continuidade do serviço e evita interrupções que prejudicariam os usuários (RNF12). | ADTU15 |
| RNF13 | Algoritmos de Criptografia Atualizados | Satisfação | A utilização de algoritmos de criptografia atualizados (BS17) protege dados sensíveis durante a transmissão e armazenamento, garantindo a segurança do sistema (RNF13). | BS17 |
| RNF14 | Conformidade com Regulamentações de Proteção de Dados | Satisfação | A conformidade com regulamentações de proteção de dados (BS18) garante que o sistema esteja em conformidade com as leis e proteja os dados dos usuários (RNF14). | BS18, LGPD |
| RNF15 | Suporte a Várias Línguas | Alocado | O suporte a várias línguas (BS19) está relacionado à classe de software que gerencia a interface do usuário e a localização (RNF15). | BS19 |
| RNF16 | Atualizações Regulares e Automáticas | Satisfação | As atualizações regulares e automáticas (BS20) melhoram a segurança e as funcionalidades do sistema, atendendo às necessidades dos usuários e garantindo a competitividade do sistema (RNF16). | BS20 |
| RNF17 | Compatibilidade com Navegadores e Sistemas Operacionais | Satisfação | A compatibilidade com diversas versões de navegadores e sistemas operacionais (BS21) garante a acessibilidade do sistema em diferentes plataformas (RNF17). | BS21 |
| RNF18 | Documentação Completa e Clara | Satisfação | A documentação completa e clara (BS22) facilita a manutenção e a futura expansão do sistema, garantindo sua longevidade e capacidade de adaptação às mudanças (RNF18). | BS22 |
| RNF19 | Desenvolvimento Seguindo Boas Práticas | Satisfação | O desenvolvimento seguindo boas práticas de engenharia de software (BS23) garante a qualidade, confiabilidade e robustez do sistema, reduzindo custos de manutenção e falhas (RNF19). | BS23 |
| RNF20 | Autenticação em Tempo Real | Satisfação | A autenticação em tempo real (BS24) evita acessos não autorizados e garante a segurança do sistema e dos dados dos usuários (RNF20). | BS24 |

## Referência Bibliografia

> [1] Monografia - Miriam Sayão e Julio Prado Leite Disponível em: <https://www.dbd.puc-rio.br/depto_informatica/05_20_sayao.pdf> Acesso em 21 de Junho de 2024

## Histórico de Versão

| Versão  | Data | Descrição | Autor(es) | Revisor(es) |
| -------- | ------ | ------ | ---------- | ---------- |
|1.0 | 21/06/2024 | Criação do Documento | [Carlos Gabriel](https://github.com/TheCarlosRamos) , [Thiago Freitas](https://github.com/thiagorfreitas) |[Caio Berg](https://github.com/Caio-bergbjj)|
