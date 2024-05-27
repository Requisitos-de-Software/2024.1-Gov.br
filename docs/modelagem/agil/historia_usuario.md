# Introdução

As histórias do usuário são resumos curtos de funcionalidades vistas pelo ponto de vista do usuário final. Seu objetivo principal é explicar como uma tarefa ou funcionalidade específica pode beneficiar o cliente ou usuário do sistema. Essas histórias oferecem uma visão organizada e centrada nas necessidades do usuário, assegurando que o software desenvolvido satisfaça as exigências do cliente e entregue um produto final de valor.

# Objetivo

O propósito das histórias de usuário no aplicativo Gov.br é identificar e transmitir as necessidades dos usuários de forma clara e direta. Elas são fundamentais para priorizar funcionalidades, manter o foco no valor para o usuário, facilitar a comunicação entre a equipe de desenvolvimento e definir critérios para verificar quando uma funcionalidade está concluída. Em resumo, as histórias de usuário garantem que o aplicativo satisfaça as expectativas dos usuários e ofereça funcionalidades valiosas e pertinentes.

# Metodologia

Durante o projeto foram elicitados os requisitos do sistema por meio de entrevistas com o cliente e análise de documentos. Com base nessas informações, foram definidas as histórias de usuário, que descrevem as funcionalidades desejadas do aplicativo Gov.br. Para garantir a qualidade e a eficácia das histórias, foram seguidas as diretrizes estabelecidas neste documento, incluindo a definição de critérios de aceitação, prioridades e dificuldades de implementação.

Dessa forma, as funcionalidades foram documentadas de maneira ágil e padronizada, alinhadas com as especificações definidas no Backlog. Por fim, realizou-se uma validação do documento em uma reunião com o representante do cliente no projeto, assegurando a conformidade com as necessidades do usuário.

# Padrão de História de Usuário

Ao escrever as histórias de usuário para este projeto, é crucial seguir as diretrizes especificadas neste documento. Para modelar as histórias de usuário de forma consistente, devemos incluir as seguintes informações:

- ID: Este é o identificador único das histórias de usuário. Os IDs estão presentes nos títulos das histórias, que foram organizadas em toggles.

- História de Usuário: Cada história de usuário deve seguir a estrutura "Eu, como [usuário], desejo [realizar algo] para que [alcance algum objetivo]".

- Tema: É importante indicar a qual tema ou categoria a está relacionada, proporcionando um contexto mais amplo.

- Critérios de Aceitação: Aqui, devemos listar um conjunto de atributos ou condições que uma funcionalidade deve atender para ser considerada "aceita" ou concluída com sucesso.

- Prioridade: A prioridade ajuda a determinar o nível de importância da história de usuário no projeto. Pode ser classificada como alta, média ou baixa, levando em consideração fatores como o valor para o usuário, facilidade de implementação, dependências técnicas e restrições de prazo.

- Dificuldade de Implementação (DI): Essa métrica está relacionada à dificuldade de implementar a funcionalidade e pode ser categorizada como baixa, média ou alta.

# Histórias de Usuário

## HSU01 - Consultar Documentos

| História de Usuário                                                                | Tema                   | Critérios de Aceitação                                            | Prioridade | (DI)  | Persona                      | Histórias Impactadas     |
| ---------------------------------------------------------------------------------- | ---------------------- | ----------------------------------------------------------------- | ---------- | ----- | ---------------------------- | ------------------------ |
| Eu, como cidadão, desejo consultar documentos para verificar informações pessoais. | Consulta de Documentos | - O sistema deve permitir a seleção e visualização de documentos. | Alta       | Baixa | Ana, estudante universitária | HSU06 - Listar Documentos |

## HSU02 - Upload de Documentos

| História de Usuário                                                                                  | Tema                 | Critérios de Aceitação                                                  | Prioridade | (DI)  | Persona                      | Histórias Impactadas        |
| ---------------------------------------------------------------------------------------------------- | -------------------- | ----------------------------------------------------------------------- | ---------- | ----- | ---------------------------- | --------------------------- |
| Eu, como cidadão, desejo enviar documentos para análise para completar minha solicitação de serviço. | Upload de Documentos | - O sistema deve permitir upload e validação de formatos de documentos. | Alta       | Baixa | Ana, estudante universitária | HSU01 - Consultar Documentos |

## HSU03 - Editar Informações de Documentos

| História de Usuário                                                                             | Tema                 | Critérios de Aceitação                                                           | Prioridade | (DI)  | Persona                    | Histórias Impactadas        |
| ----------------------------------------------------------------------------------------------- | -------------------- | -------------------------------------------------------------------------------- | ---------- | ----- | -------------------------- | --------------------------- |
| Eu, como cidadão, desejo editar informações de documentos previamente submetidos na plataforma. | Edição de Documentos | - O sistema deve permitir a edição de informações com atualização em tempo real. | Média      | Baixa | Carlos, viajante frequente | HSU02 - Upload de Documentos |

## HSU04 - Acessar Serviços de Saúde

| História de Usuário                                                                | Tema                       | Critérios de Aceitação                                                 | Prioridade | (DI)  | Persona                      | Histórias Impactadas        |
| ---------------------------------------------------------------------------------- | -------------------------- | ---------------------------------------------------------------------- | ---------- | ----- | ---------------------------- | --------------------------- |
| Eu, como cidadão, desejo acessar serviços de saúde disponibilizados na plataforma. | Acesso a Serviços de Saúde | - O sistema deve mostrar serviços disponíveis e permitir agendamentos. | Alta       | Baixa | Maria, profissional de saúde | HSU08 - Cancelar Agendamento |

## HSU05 - Renovação de Documentos

| História de Usuário                                                                                                | Tema                    | Critérios de Aceitação                                                    | Prioridade | (DI)  | Persona                    | Histórias Impactadas        |
| ------------------------------------------------------------------------------------------------------------------ | ----------------------- | ------------------------------------------------------------------------- | ---------- | ----- | -------------------------- | --------------------------- |
| Eu, como cidadão, desejo renovar documentos como carteira de identidade ou passaporte diretamente pela plataforma. | Renovação de Documentos | - O sistema deve permitir a renovação com opções de pagamento integradas. | Alta       | Média | Carlos, viajante frequente | HSU01 - Consultar Documentos |

## HSU06 - Listar Documentos

| História de Usuário                                                                                            | Tema                | Critérios de Aceitação                                                                  | Prioridade | (DI)  | Persona                      | Histórias Impactadas        |
| -------------------------------------------------------------------------------------------------------------- | ------------------- | --------------------------------------------------------------------------------------- | ---------- | ----- | ---------------------------- | --------------------------- |
| Eu, como cidadão, desejo listar todos os documentos disponíveis para entender quais estão acessíveis para mim. | Lista de Documentos | - O sistema deve apresentar uma lista completa de documentos disponíveis para consulta. | Média      | Baixa | Ana, estudante universitária | HSU01 - Consultar Documentos |

## HSU07 - Revisar Informações de Perfil

| História de Usuário                                                                                                  | Tema              | Critérios de Aceitação                                                                            | Prioridade | (DI)  | Persona                    | Histórias Impactadas    |
| -------------------------------------------------------------------------------------------------------------------- | ----------------- | ------------------------------------------------------------------------------------------------- | ---------- | ----- | -------------------------- | ----------------------- |
| Eu, como cidadão, desejo revisar e corrigir informações em meu perfil para garantir que meus dados estejam corretos. | Revisão de Perfil | - O sistema deve permitir visualização e edição de informações pessoais com verificação de dados. | Alta       | Média | Carlos, viajante frequente | HSU06 - Edição de Perfil |

## HSU08 - Cancelar Agendamento

| História de Usuário                                                                              | Tema                        | Critérios de Aceitação                                                           | Prioridade | (DI)  | Persona                      | Histórias Impactadas        |
| ------------------------------------------------------------------------------------------------ | --------------------------- | -------------------------------------------------------------------------------- | ---------- | ----- | ---------------------------- | --------------------------- |
| Eu, como cidadão, desejo cancelar um agendamento prévio para evitar compromissos desnecessários. | Cancelamento de Agendamento | - O sistema deve permitir cancelamento de agendamentos com confirmação imediata. | Alta       | Baixa | Maria, profissional de saúde | HSU03 - Agendamento de Saúde |

## HSU09 - Atualizar Contatos de Emergência

| História de Usuário                                                                           | Tema                   | Critérios de Aceitação                                                           | Prioridade | (DI) | Persona                   | Histórias Impactadas |
| --------------------------------------------------------------------------------------------- | ---------------------- | -------------------------------------------------------------------------------- | ---------- | ---- | ------------------------- | -------------------- |
| Eu, como cidadão, desejo atualizar meus contatos de emergência para garantir minha segurança. | Contatos de Emergência | - O sistema deve permitir adição e remoção de contatos de emergência facilmente. | Média      | Alta | João, administrador de TI | Nenhuma              |

## HSU10 - Alterar Senha de Acesso

| História de Usuário                                                                            | Tema               | Critérios de Aceitação                                                        | Prioridade | (DI)  | Persona                      | Histórias Impactadas |
| ---------------------------------------------------------------------------------------------- | ------------------ | ----------------------------------------------------------------------------- | ---------- | ----- | ---------------------------- | -------------------- |
| Eu, como cidadão, desejo alterar minha senha de acesso para manter a segurança da minha conta. | Segurança da Conta | - O sistema deve permitir a alteração de senha com verificações de segurança. | Alta       | Baixa | Maria, profissional de saúde | Nenhuma              |

## HSU11 - Solicitar Nova Certidão

| História de Usuário                                                                                           | Tema                     | Critérios de Aceitação                                                                              | Prioridade | (DI)  | Persona                      | Histórias Impactadas     |
| ------------------------------------------------------------------------------------------------------------- | ------------------------ | --------------------------------------------------------------------------------------------------- | ---------- | ----- | ---------------------------- | ------------------------ |
| Eu, como cidadão, desejo solicitar uma nova certidão de nascimento para regularizar minha documentação civil. | Solicitação de Certidões | - O sistema deve permitir a solicitação e o pagamento de novas certidões de forma simples e segura. | Alta       | Baixa | Ana, estudante universitária | HSU06 - Listar Documentos |

## HSU12 - Visualizar Notificações de Pagamento

| História de Usuário                                                                                                       | Tema                     | Critérios de Aceitação                                                                    | Prioridade | (DI) | Persona                    | Histórias Impactadas           |
| ------------------------------------------------------------------------------------------------------------------------- | ------------------------ | ----------------------------------------------------------------------------------------- | ---------- | ---- | -------------------------- | ------------------------------ |
| Eu, como cidadão, desejo visualizar notificações de pagamento para gerenciar minhas pendências financeiras com o governo. | Gerenciamento Financeiro | - O sistema deve fornecer um painel de notificações de pagamentos pendentes e realizados. | Média      | Alta | Carlos, viajante frequente | HSU10 - Alterar Senha de Acesso |

## HSU13 - Responder Pesquisas de Satisfação

| História de Usuário                                                                                              | Tema                 | Critérios de Aceitação                                                                               | Prioridade | (DI)  | Persona                      | Histórias Impactadas |
| ---------------------------------------------------------------------------------------------------------------- | -------------------- | ---------------------------------------------------------------------------------------------------- | ---------- | ----- | ---------------------------- | -------------------- |
| Eu, como cidadão, desejo responder pesquisas de satisfação para contribuir com a melhoria dos serviços públicos. | Feedback de Serviços | - O sistema deve disponibilizar pesquisas de satisfação de forma periódica e registrar as respostas. | Baixa      | Média | Maria, profissional de saúde | Nenhuma              |

## HSU14 - Consultar Calendário de Eventos

| História de Usuário                                                                                                        | Tema             | Critérios de Aceitação                                                                                          | Prioridade | (DI)  | Persona                   | Histórias Impactadas |
| -------------------------------------------------------------------------------------------------------------------------- | ---------------- | --------------------------------------------------------------------------------------------------------------- | ---------- | ----- | ------------------------- | -------------------- |
| Eu, como cidadão, desejo consultar o calendário de eventos públicos para planejar minha participação em atividades locais. | Acesso a Eventos | - O sistema deve oferecer um calendário atualizado de eventos públicos com opções de filtragem por data e tipo. | Baixa      | Baixa | João, administrador de TI | Nenhuma              |

## HSU15 - Registrar Queixas e Reclamações

| História de Usuário                                                                                                              | Tema                | Critérios de Aceitação                                                                                                   | Prioridade | (DI) | Persona                      | Histórias Impactadas                     |
| -------------------------------------------------------------------------------------------------------------------------------- | ------------------- | ------------------------------------------------------------------------------------------------------------------------ | ---------- | ---- | ---------------------------- | ---------------------------------------- |
| Eu, como cidadão, desejo registrar queixas e reclamações sobre serviços públicos para que medidas corretivas possam ser tomadas. | Registro de Queixas | - O sistema deve permitir o registro de queixas de forma anônima ou identificada, garantindo resposta ou acompanhamento. | Alta       | Alta | Ana, estudante universitária | HSU13 - Responder Pesquisas de Satisfação |

## HSU16 - Login no Sistema
Tabela 2: Exemplo de tabela de História de Usuário

| História de Usuário                                                                                         | Tema                    | Critérios de Aceitação                                                                                               | Prioridade | (DI)  | Persona                      | Histórias Impactadas |
| ----------------------------------------------------------------------------------------------------------- | ----------------------- | -------------------------------------------------------------------------------------------------------------------- | ---------- | ----- | ---------------------------- | -------------------- |
| Eu, como usuário registrado, desejo fazer login para acessar minha conta e utilizar os serviços do sistema. | Autenticação de Usuário | - O sistema deve validar as credenciais do usuário.<br>- Deve haver uma mensagem de erro para credenciais inválidas. | Alta       | Baixa | Ana, estudante universitária | Nenhuma              |

## HSU17 - Recuperação de Senha
Tabela 2: Exemplo de tabela de História de Usuário

| História de Usuário                                                                                         | Tema                    | Critérios de Aceitação                                                                                                                          | Prioridade | (DI)  | Persona                    | Histórias Impactadas    |
| ----------------------------------------------------------------------------------------------------------- | ----------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | ----- | -------------------------- | ----------------------- |
| Eu, como usuário que esqueceu a senha, desejo recuperar minha senha para poder acessar novamente o sistema. | Gerenciamento de Senhas | - O sistema deve permitir solicitar a redefinição de senha através de e-mail.<br>- Deve fornecer instruções claras para a redefinição de senha. | Alta       | Média | Carlos, viajante frequente | HS16 - Login no Sistema |

Estas histórias são fundamentais para garantir que os usuários tenham acesso contínuo e seguro ao sistema, permitindo a autenticação e a recuperação de acesso quando necessário. 

## Bibliografia

1. DIOGO. Guia definitivo para Histórias de Usuário - Product Management. YouTube, 26 mai. 2024. Disponível em: <https://www.youtube.com/watch?v=pLJ3LxR292w>.

## Histórico de Versão

| Versão |    Data    | Descrição            |                                                 Autor(es)                                                 |                 Revisor(es)                  |
| :----: | :--------: | :------------------- | :-------------------------------------------------------------------------------------------------------: | :------------------------------------------: |
|  1.0   | 16/05/2024 | Criação do documento | [Arthur Gabriel](https://github.com/ArthurGabrieel), [Caio Berg](https://github.com/Caio-bergbjj),[Thiago Freitas](https://github.com/thiagorfreitas)  , [Henrique Batalha](https://github.com/HeBatalha), [Carlos Gabriel](https://github.com/TheCarlosRamos) e [Ester Lino](https://github.com/esteerlino) | [Arthur Gabriel](https://github.com/ArthurGabrieel) |
