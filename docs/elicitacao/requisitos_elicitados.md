# Requisitos Elicitados

## Introdução

Essa página reune todos os requisitos funcionais e não funcionais elicitados usando as técnicas de [análise de documentos](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos), [brainstorm](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) e [storytelling](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling).

## Metodologia

A tabela 1 apresenta os requisitos funcionais e a tabela 2 apresenta os requisitos não funcionais, sendo que cada linha contém ID, descrição, um hyperlink de rastreabilidade que direciona à página da(s) técnica(s) que elicitou o requisito em questão e se ele foi implementado ou não.

*Legenda da tabela:*

- RFx: Requisito Funcional nºx
- RNFx: Requisito Não-Funcional nºx
- ADFUx: Requisito nºx elicitado pela Análise de Documentos (Feedbacks dos Usuários)
- ADTUx: Requisito nºx elicitado pela Análise de Documentos (Termo de Uso)
- BSx: Requisito nºx elicitado pelo Brainstorming
- STx: Requisito nºx elicitado pelo Storytelling

## Requisitos Elicitados

<details><summary><b>Requisitos Funcionais</b></summary>

<p style="text-align: center"><b><a id="tab_1" style="visibility: hidden;"></a>Tabela 1</b> - Requisitos funcionais</p>

|  Tipo  |                                Descrição                                |                                  Rastreabilidade                                 | Implementado |
|:------:|:-----------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|:------------:|
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

<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/esteerlino">Ester Lino</a></p></font>

</details>

<details><summary>Requisitos Não Funcionais</summary>

<p style="text-align: center"><b><a id="tab_1" style="visibility: hidden;"></a>Tabela 2</b> - Requisitos não funcionais</p>

|  Tipo  |                                Descrição                                |                                  Rastreabilidade                                 | Implementado |
|:------:|:-----------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|:------------:|
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

<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/esteerlino">Ester Lino</a></p></font>

</details>

<br>

## Requisitos Revisados

<details><summary>Clique para expandir</summary>

## Observações

- Em 15 de junho de 2024, foi publicada a Lei nº 14.522/2024, que altera a Lei Geral de Proteção de Dados (LGPD) e reforça as medidas de segurança para proteção de dados pessoais. O sistema gov.br foi atualizado para atender às novas exigências da lei.

## Desenvolvimento

A tabela 3 apresenta os requisitos funcionais que foram revisados e não alterados.

- Significado de "Sim":
Na coluna "Status Anterior": Indica que o requisito já estava implementado no sistema em um momento específico no passado, antes da análise da tabela.
Na coluna "Status Atual": Indica que o requisito continua implementado no sistema e está disponível para uso pelos usuários no momento da análise da tabela.

- Significado de "Não":
Na coluna "Status Anterior": Indica que o requisito não estava implementado no sistema em um momento específico no passado, antes da análise da tabela.
Na coluna "Status Atual": Indica que o requisito ainda não foi implementado no sistema e não está disponível para uso pelos usuários no momento da análise da tabela.

<p style="text-align: center"><b><a id="tab_1" style="visibility: hidden;"></a>Tabela 3</b> - Requisitos funcionais</p>

| ID | Requisito | Status Anterior | Status Atual | Observações |
|---|---|---|---|---|
| RF05 | O sistema deve facilitar o processo de mudança de celular pelo usuário, permitindo a transferência de segurança e autenticações sem necessidade de cancelar e recriar a conta. | Sim | Sim | Funcionalidade já implementada na versão atual do aplicativo. |
| RF12 | O aplicativo deve permitir que os usuários se autentiquem de forma segura, usando credenciais únicas, como CPF e senha. | Sim | Sim | Funcionalidade já implementada na versão atual do aplicativo. |
| RF13 | O usuário deve ser capaz de logar com as credenciais do gov.br. | Sim | Sim | Funcionalidade já implementada na versão atual do aplicativo. |
| RF14 | O usuário deve conseguir visualizar seus documentos. | Sim | Sim | Funcionalidade já implementada na versão atual do aplicativo. |
| RF16 | O usuário deve conseguir emitir/baixar certidões. | Sim | Sim | Funcionalidade já implementada na versão atual do aplicativo. |
| RF17 | O usuário deve conseguir se logar no aplicativo. | Sim | Sim | Funcionalidade já implementada na versão atual do aplicativo. |
| RF18 | O login deve possuir autenticação em dois fatores. | Sim | Sim | Funcionalidade já implementada na versão atual do aplicativo. |
| RF19 | O usuário deve conseguir assinar documentos digitalmente. | Sim | Sim | Funcionalidade já implementada na versão atual do aplicativo. |
| RF26 | O usuário deve conseguir obter o código de acesso. | Sim | Sim | Funcionalidade já implementada na versão atual do aplicativo. |
| RF28 | Como usuário, desejo acessar o aplicativo gov.br de forma rápida e intuitiva. | Sim | Sim | Interface do aplicativo foi aprimorada para facilitar a navegação e o uso. |
| RF29 | Como usuário, desejo encontrar facilmente o serviço de agendamento na Receita Federal. | Sim | Sim | Funcionalidade de busca foi aprimorada para facilitar a localização de serviços específicos. |
| RF30 | Como usuário, desejo acessar as funções de assinatura digital para agilizar a assinatura de documentos. | Sim | Sim | Processo de assinatura digital foi simplificado e otimizado. |
| RF33 | Como usuário, desejo uma navegação intuitiva para buscar processos e documentos. | Sim | Sim | Funcionalidade de busca foi aprimorada para facilitar a localização de processos e documentos. |
| RF34 | Como usuário, desejo garantir a segurança na transmissão e armazenamento de documentos sensíveis. | Sim | Sim | Medidas de segurança foram reforçadas para proteger dados sensíveis. |
| RF35 | Como usuário, desejo poder alterar minhas informações pessoais de forma prática e rápida. | Sim | Sim | Processo de alteração de informações pessoais foi simplificado e otimizado. |
| RF36 | Como usuário, desejo uma opção de ajuda no aplicativo para dúvidas e suporte técnico. | Sim | Sim | Função de ajuda foi implementada no aplicativo, com acesso a FAQs e canais de contato. |
| RF37 | Como usuário, desejo acessar rapidamente a área de agendamento de consultas e serviços públicos. | Sim | Sim | Área de agendamento foi otimizada para facilitar o acesso e a marcação de consultas e serviços. |
| RF38 | Como usuário, desejo poder recuperar minha senha com facilidade. | Sim | Sim | Processo de recuperação de senha foi simplificado e otimizado. |
| RF39 | Como usuário, desejo uma interface clara e de fácil uso no aplicativo gov.br. | Sim | Sim | Interface do aplicativo foi aprimorada para ser mais clara, intuitiva e fácil de usar. |
| RF40 | Como usuário, desejo que o aplicativo gov.br ofereça suporte para biometria. | Sim | Sim | Suporte para biometria foi implementado no aplicativo, permitindo login e autenticação mais seguros. |
| RF41 | Como usuário, desejo acessar o gov.br para facilitar minhas interações com o governo. | Sim | Sim | Aplicativo foi aprimorado para oferecer uma experiência mais completa e facilitar as interações dos usuários. |

<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/TheCarlosRamos">Carlos Gabriel</a>, <a href="https://github.com/HeBatalha">Henrique Batalha</a> e <a href="https://github.com/IsaqueSH">Isaque Santos</a> </p></font>

## Outros requisitos

A tabela 4 apresenta os requisitos funcionais que ainda estão em processo de implementação.

<p style="text-align: center"><b><a id="tab_1" style="visibility: hidden;"></a>Tabela 4</b> - Requisitos funcionais não implementados</p>

| Requisito Funcional | Descrição | Status | Comentários |
|-------------------------|---------------|------------|-----------------|
| RF01 | O sistema deve oferecer reconhecimento facial para autenticação do usuário. | Em desenvolvimento | Funcionalidade em fase de testes e aprimoramento. |
| RF02 | O sistema deve permitir a recuperação de senha por meio de perguntas de segurança e/ou e-mail. | Em desenvolvimento | Funcionalidade em fase de testes e aprimoramento. |
| RF03 | O sistema deve permitir a verificação em duas etapas para maior segurança do login. | Em desenvolvimento | Funcionalidade em fase de testes e aprimoramento. |
| RF04 | O sistema deve oferecer acesso centralizado a serviços governamentais. | Em desenvolvimento | Integrações com outros serviços governamentais em andamento. |
| RF06 | O sistema deve permitir a notificação do usuário em caso de atividades suspeitas em sua conta. | Em desenvolvimento | Funcionalidade em fase de testes e aprimoramento. |
| RF07 | O sistema deve permitir a autenticação biométrica por meio de impressões digitais. | Em desenvolvimento | Funcionalidade em fase de testes e aprimoramento. |
| RF08 | O sistema deve permitir o acesso e gerenciamento de dados pessoais pelo usuário. | Em desenvolvimento | Funcionalidade em fase de testes e aprimoramento. |
| RF09 | O sistema deve permitir a recuperação de conta em caso de perda de acesso. | Em desenvolvimento | Funcionalidade em fase de testes e aprimoramento. |
| RF10 | O sistema deve permitir a visualização e gerenciamento de documentos digitais. | Em desenvolvimento | Funcionalidade em fase de testes e aprimoramento. |
| RF11 | O sistema deve permitir a prova de vida para utilização de serviços online. | Em desenvolvimento | Funcionalidade em fase de testes e aprimoramento. |
| RF15 | O sistema deve atender aos requisitos de segurança da informação, incluindo confidencialidade, integridade e disponibilidade dos dados. | Em desenvolvimento | Implementação de medidas de segurança em andamento. |
| RF20 | O sistema deve ser compatível com diferentes navegadores e sistemas operacionais. | Em desenvolvimento | Testes de compatibilidade em andamento. |
| RF21 | O sistema deve ser acessível a pessoas com deficiência. | Em desenvolvimento | Adequações de acessibilidade em andamento. |
| RF22 | O sistema deve ser integrado com APIs de outros serviços governamentais. | Em desenvolvimento | Integrações em andamento. |
| RF23 | O sistema deve ter logs para registro de atividades e auditoria. | Em desenvolvimento | Implementação de logs em andamento. |
| RF24 | O sistema deve ter backups para garantir a recuperação de dados em caso de falhas. | Em desenvolvimento | Implementação de backups em andamento. |
| RF25 | O sistema deve ter mecanismos de recuperação de falhas para garantir a disponibilidade dos serviços. | Em desenvolvimento | Implementação de mecanismos de recuperação de falhas em andamento. |
| RF27 | O sistema deve ter criptografia de dados para garantir a confidencialidade das informações. | Em desenvolvimento | Implementação de criptografia em andamento. |
| RF31 | O sistema deve atender às legislações e regulamentações aplicáveis. | Em desenvolvimento | Análise de legislações em andamento. |
| RF32 | O sistema deve ter documentação completa e atualizada. | Em desenvolvimento | Elaboração da documentação em andamento. |

<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/TheCarlosRamos">Carlos Gabriel</a>, <a href="https://github.com/HeBatalha">Henrique Batalha</a> e <a href="https://github.com/IsaqueSH">Isaque Santos</a> </p></font>

## Futuro

A tabela 5 apresenta 4 novos requisitos a serem implementados no aplicativo Gov.br.

| ID | Requisito | Status Anterior | Status Atual | Observações |
|---|---|---|---|---|
| RF(novo) | Como usuário, desejo poder consultar informações sobre benefícios sociais. | Não implementado | Prioridade para implementação futura |  Aguardando definição de escopo e prazos. |
| RF(novo) | Como usuário, desejo ter acesso a uma carteira digital integrada para pagamentos. | Não implementado |  Em avaliação de viabilidade técnica e legal. | A implementação depende de aprovações e integrações com instituições financeiras. |
| RF(novo) | O sistema deve atender aos requisitos de acessibilidade WCAG 2.1 para usuários com deficiência. | Não implementado | Prioridade para implementação futura |  Aguardando definição de cronograma e recursos. |
| RF(novo) | O aplicativo deve oferecer suporte a múltiplas línguas. | Não implementado |  Em avaliação de viabilidade e prioridade. | A implementação depende de recursos e definição de quais línguas serão oferecidas. |

<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/TheCarlosRamos">Carlos Gabriel</a>, <a href="https://github.com/HeBatalha">Henrique Batalha</a> e <a href="https://github.com/IsaqueSH">Isaque Santos</a> </p></font>

</details>

<br>

## Histórico de Versões

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| :----: | :--: | :-------: | :-------: | :---------: |
|  1.0   | 17/04/2024 | Criação da página com os requisitos elicitados | [Ester Lino](https://github.com/esteerlino)  | [Arthur Gabriel](https://github.com/ArthurGabrieel) |
|  1.1   | 23/06/2024 | Adição dos requisitos revisados | [Carlos Gabriel](https://github.com/TheCarlosRamos), [Henrique Batalha](https://github.com/HeBatalha), [Isaque Santos](https://github.com/IsaqueSH)   | [Ester Lino](https://github.com/esteerlino) |
|  1.2   | 23/06/2024 | Correções na formatação das tabelas | [Ester Lino](https://github.com/esteerlino) | [Carlos Gabriel](https://github.com/TheCarlosRamos), [Henrique Batalha](https://github.com/HeBatalha), [Isaque Santos](https://github.com/IsaqueSH) |
