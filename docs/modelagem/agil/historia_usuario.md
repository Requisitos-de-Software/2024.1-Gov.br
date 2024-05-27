# Introdução

# Metodologia


# Histórias de Usuário
## História de Usuário EU_001_Consultar Documentos

| História de Usuário                                                                | Tema                   | Critérios de Aceitação                                            | Prioridade | (DI)  | Persona                      | Histórias Impactadas     |
| ---------------------------------------------------------------------------------- | ---------------------- | ----------------------------------------------------------------- | ---------- | ----- | ---------------------------- | ------------------------ |
| Eu, como cidadão, desejo consultar documentos para verificar informações pessoais. | Consulta de Documentos | - O sistema deve permitir a seleção e visualização de documentos. | Alta       | Baixa | Ana, estudante universitária | EU_006_Listar Documentos |

## História de Usuário EU_002_Upload de Documentos

| História de Usuário                                                                                  | Tema                 | Critérios de Aceitação                                                  | Prioridade | (DI)  | Persona                      | Histórias Impactadas        |
| ---------------------------------------------------------------------------------------------------- | -------------------- | ----------------------------------------------------------------------- | ---------- | ----- | ---------------------------- | --------------------------- |
| Eu, como cidadão, desejo enviar documentos para análise para completar minha solicitação de serviço. | Upload de Documentos | - O sistema deve permitir upload e validação de formatos de documentos. | Alta       | Baixa | Ana, estudante universitária | EU_001_Consultar Documentos |

## História de Usuário EU_003_Editar Informações de Documentos

| História de Usuário                                                                             | Tema                 | Critérios de Aceitação                                                           | Prioridade | (DI)  | Persona                    | Histórias Impactadas        |
| ----------------------------------------------------------------------------------------------- | -------------------- | -------------------------------------------------------------------------------- | ---------- | ----- | -------------------------- | --------------------------- |
| Eu, como cidadão, desejo editar informações de documentos previamente submetidos na plataforma. | Edição de Documentos | - O sistema deve permitir a edição de informações com atualização em tempo real. | Média      | Baixa | Carlos, viajante frequente | EU_002_Upload de Documentos |

## História de Usuário EU_004_Acessar Serviços de Saúde

| História de Usuário                                                                | Tema                       | Critérios de Aceitação                                                 | Prioridade | (DI)  | Persona                      | Histórias Impactadas        |
| ---------------------------------------------------------------------------------- | -------------------------- | ---------------------------------------------------------------------- | ---------- | ----- | ---------------------------- | --------------------------- |
| Eu, como cidadão, desejo acessar serviços de saúde disponibilizados na plataforma. | Acesso a Serviços de Saúde | - O sistema deve mostrar serviços disponíveis e permitir agendamentos. | Alta       | Baixa | Maria, profissional de saúde | EU_008_Cancelar Agendamento |

## História de Usuário EU_005_Renovação de Documentos

| História de Usuário                                                                                                | Tema                    | Critérios de Aceitação                                                    | Prioridade | (DI)  | Persona                    | Histórias Impactadas        |
| ------------------------------------------------------------------------------------------------------------------ | ----------------------- | ------------------------------------------------------------------------- | ---------- | ----- | -------------------------- | --------------------------- |
| Eu, como cidadão, desejo renovar documentos como carteira de identidade ou passaporte diretamente pela plataforma. | Renovação de Documentos | - O sistema deve permitir a renovação com opções de pagamento integradas. | Alta       | Média | Carlos, viajante frequente | EU_001_Consultar Documentos |

## História de Usuário EU_006_Listar Documentos

| História de Usuário                                                                                            | Tema                | Critérios de Aceitação                                                                  | Prioridade | (DI)  | Persona                      | Histórias Impactadas        |
| -------------------------------------------------------------------------------------------------------------- | ------------------- | --------------------------------------------------------------------------------------- | ---------- | ----- | ---------------------------- | --------------------------- |
| Eu, como cidadão, desejo listar todos os documentos disponíveis para entender quais estão acessíveis para mim. | Lista de Documentos | - O sistema deve apresentar uma lista completa de documentos disponíveis para consulta. | Média      | Baixa | Ana, estudante universitária | EU_001_Consultar Documentos |

## História de Usuário EU_007_Revisar Informações de Perfil

| História de Usuário                                                                                                  | Tema              | Critérios de Aceitação                                                                            | Prioridade | (DI)  | Persona                    | Histórias Impactadas    |
| -------------------------------------------------------------------------------------------------------------------- | ----------------- | ------------------------------------------------------------------------------------------------- | ---------- | ----- | -------------------------- | ----------------------- |
| Eu, como cidadão, desejo revisar e corrigir informações em meu perfil para garantir que meus dados estejam corretos. | Revisão de Perfil | - O sistema deve permitir visualização e edição de informações pessoais com verificação de dados. | Alta       | Média | Carlos, viajante frequente | EU_006_Edição de Perfil |

## História de Usuário EU_008_Cancelar Agendamento

| História de Usuário                                                                              | Tema                        | Critérios de Aceitação                                                           | Prioridade | (DI)  | Persona                      | Histórias Impactadas        |
| ------------------------------------------------------------------------------------------------ | --------------------------- | -------------------------------------------------------------------------------- | ---------- | ----- | ---------------------------- | --------------------------- |
| Eu, como cidadão, desejo cancelar um agendamento prévio para evitar compromissos desnecessários. | Cancelamento de Agendamento | - O sistema deve permitir cancelamento de agendamentos com confirmação imediata. | Alta       | Baixa | Maria, profissional de saúde | EU_003_Agendamento de Saúde |

## História de Usuário EU_009_Atualizar Contatos de Emergência

| História de Usuário                                                                           | Tema                   | Critérios de Aceitação                                                           | Prioridade | (DI) | Persona                   | Histórias Impactadas |
| --------------------------------------------------------------------------------------------- | ---------------------- | -------------------------------------------------------------------------------- | ---------- | ---- | ------------------------- | -------------------- |
| Eu, como cidadão, desejo atualizar meus contatos de emergência para garantir minha segurança. | Contatos de Emergência | - O sistema deve permitir adição e remoção de contatos de emergência facilmente. | Média      | Alta | João, administrador de TI | Nenhuma              |

## História de Usuário EU_010_Alterar Senha de Acesso

| História de Usuário                                                                            | Tema               | Critérios de Aceitação                                                        | Prioridade | (DI)  | Persona                      | Histórias Impactadas |
| ---------------------------------------------------------------------------------------------- | ------------------ | ----------------------------------------------------------------------------- | ---------- | ----- | ---------------------------- | -------------------- |
| Eu, como cidadão, desejo alterar minha senha de acesso para manter a segurança da minha conta. | Segurança da Conta | - O sistema deve permitir a alteração de senha com verificações de segurança. | Alta       | Baixa | Maria, profissional de saúde | Nenhuma              |

## História de Usuário EU_011_Solicitar Nova Certidão

| História de Usuário                                                                                           | Tema                     | Critérios de Aceitação                                                                              | Prioridade | (DI)  | Persona                      | Histórias Impactadas     |
| ------------------------------------------------------------------------------------------------------------- | ------------------------ | --------------------------------------------------------------------------------------------------- | ---------- | ----- | ---------------------------- | ------------------------ |
| Eu, como cidadão, desejo solicitar uma nova certidão de nascimento para regularizar minha documentação civil. | Solicitação de Certidões | - O sistema deve permitir a solicitação e o pagamento de novas certidões de forma simples e segura. | Alta       | Baixa | Ana, estudante universitária | EU_006_Listar Documentos |

## História de Usuário EU_012_Visualizar Notificações de Pagamento

| História de Usuário                                                                                                       | Tema                     | Critérios de Aceitação                                                                    | Prioridade | (DI) | Persona                    | Histórias Impactadas           |
| ------------------------------------------------------------------------------------------------------------------------- | ------------------------ | ----------------------------------------------------------------------------------------- | ---------- | ---- | -------------------------- | ------------------------------ |
| Eu, como cidadão, desejo visualizar notificações de pagamento para gerenciar minhas pendências financeiras com o governo. | Gerenciamento Financeiro | - O sistema deve fornecer um painel de notificações de pagamentos pendentes e realizados. | Média      | Alta | Carlos, viajante frequente | EU_010_Alterar Senha de Acesso |

## História de Usuário EU_013_Responder Pesquisas de Satisfação

| História de Usuário                                                                                              | Tema                 | Critérios de Aceitação                                                                               | Prioridade | (DI)  | Persona                      | Histórias Impactadas |
| ---------------------------------------------------------------------------------------------------------------- | -------------------- | ---------------------------------------------------------------------------------------------------- | ---------- | ----- | ---------------------------- | -------------------- |
| Eu, como cidadão, desejo responder pesquisas de satisfação para contribuir com a melhoria dos serviços públicos. | Feedback de Serviços | - O sistema deve disponibilizar pesquisas de satisfação de forma periódica e registrar as respostas. | Baixa      | Média | Maria, profissional de saúde | Nenhuma              |

## História de Usuário EU_014_Consultar Calendário de Eventos

| História de Usuário                                                                                                        | Tema             | Critérios de Aceitação                                                                                          | Prioridade | (DI)  | Persona                   | Histórias Impactadas |
| -------------------------------------------------------------------------------------------------------------------------- | ---------------- | --------------------------------------------------------------------------------------------------------------- | ---------- | ----- | ------------------------- | -------------------- |
| Eu, como cidadão, desejo consultar o calendário de eventos públicos para planejar minha participação em atividades locais. | Acesso a Eventos | - O sistema deve oferecer um calendário atualizado de eventos públicos com opções de filtragem por data e tipo. | Baixa      | Baixa | João, administrador de TI | Nenhuma              |

## História de Usuário EU_015_Registrar Queixas e Reclamações

| História de Usuário                                                                                                              | Tema                | Critérios de Aceitação                                                                                                   | Prioridade | (DI) | Persona                      | Histórias Impactadas                     |
| -------------------------------------------------------------------------------------------------------------------------------- | ------------------- | ------------------------------------------------------------------------------------------------------------------------ | ---------- | ---- | ---------------------------- | ---------------------------------------- |
| Eu, como cidadão, desejo registrar queixas e reclamações sobre serviços públicos para que medidas corretivas possam ser tomadas. | Registro de Queixas | - O sistema deve permitir o registro de queixas de forma anônima ou identificada, garantindo resposta ou acompanhamento. | Alta       | Alta | Ana, estudante universitária | EU_013_Responder Pesquisas de Satisfação |