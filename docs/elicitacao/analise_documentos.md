# Análise de Documentos

## Introdução

<p align="justify">Este documento é destinado à elicitação e documentação dos requisitos de software para o aplicativo Gov.br, utilizando a técnica de análise de documentos. O Gov.br é uma plataforma integrada que oferece acesso a uma ampla gama de serviços públicos federais, estaduais e municipais.</p>

### Metodologia de Análise de Documentação

Neste projeto, adotamos uma metodologia específica para a análise de documentação com o objetivo de elicitar requisitos a partir de documentos existentes sobre o aplicativo gov.br. O processo foi cuidadosamente estruturado para garantir que todos os aspectos relevantes fossem considerados e que as informações obtidas fossem precisas e úteis para o desenvolvimento do projeto. A seguir, detalhamos os passos específicos que foram seguidos:

#### 1. Seleção de Documentos

Inicialmente, identificamos e reunimos todos os documentos relevantes que pudessem fornecer insights sobre os requisitos do sistema. Para este projeto, os documentos selecionados incluíram:
- **Termos de Uso e Aviso de Privacidade do aplicativo gov.br**: Este documento foi crucial pois continha informações detalhadas sobre as funcionalidades do sistema, os dados tratados pelo aplicativo e as obrigações legais relacionadas à privacidade e proteção de dados.
- **Feedback de Usuários na Play Store**: Comentários de usuários na Play Store foram revisados para entender as percepções dos usuários, problemas comuns e sugestões de melhorias que não estão explicitamente documentadas nos requisitos técnicos formais. 

#### 2. Revisão e Análise

- **Leitura Detalhada**: Cada documento foi lido detalhadamente para extrair informações pertinentes sobre o funcionamento atual do sistema e requisitos potenciais. As sessões de leitura foram seguidas de sessões de anotação onde pontos chave foram destacados.
- **Identificação de Requisitos**: Durante a leitura, identificamos explicitamente requisitos funcionais e não funcionais. Por exemplo, a partir do Termo de Uso e Aviso de Privacidade, extraímos requisitos relacionados à segurança de dados, conformidade legal e funcionalidades específicas do sistema.

#### 3. Documentação dos Requisitos

- **Registro de Requisitos**: Todos os requisitos identificados foram documentados em um formato padronizado. Isso incluiu a descrição do requisito, a fonte do documento onde a informação foi encontrada e qualquer observação relevante que pudesse influenciar a implementação ou teste desses requisitos.
- **Validação**: Os requisitos documentados foram revisados por toda a equipe.

Esta metodologia assegurou que a análise de documentação fosse conduzida de maneira sistemática e que os requisitos elicitados fossem relevantes e alinhados com as necessidades do usuário e os objetivos do sistema.

## Requisitos Elicitados a partir dos Feedbacks dos Usuários

**Requisitos Funcionais (RF)**

| Tipo | Requisito                                                          | Descrição                                                                                                            |
|----|--------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------|
| RF01  | Funcionalidade de Reconhecimento Facial                           | O sistema deve possuir uma funcionalidade de reconhecimento facial para autenticação do usuário.                      |
| RF02  | Suporte para Recuperação de Senha                                 | O sistema deve permitir que os usuários recuperem suas senhas através de métodos seguros e eficientes.                |
| RF03  | Verificação em Duas Etapas                                        | O sistema deve oferecer verificação em duas etapas como uma camada adicional de segurança para os usuários.           |
| RF04  | Funcionalidade de Autenticação Centralizada para Serviços Governamentais | O sistema deve permitir que os usuários utilizem suas credenciais para acessar diferentes serviços governamentais de forma centralizada. |
| RF05  | Processo de Mudança de Celular                                    | O sistema deve facilitar o processo de mudança de celular pelo usuário, permitindo a transferência de segurança e autenticações sem necessidade de cancelar e recriar a conta. |
| RF06  | Notificações de Segurança                                         | O sistema deve notificar os usuários de quaisquer acessos não autorizados ou mudanças críticas na segurança de suas contas. |

**Requisitos Não Funcionais (RNF)**

| Nº | Requisito                             | Descrição                                                                                                        |
|----|---------------------------------------|------------------------------------------------------------------------------------------------------------------|
| RFN01  | Estabilidade do Sistema               | O sistema deve ser estável e confiável, funcionando corretamente sem travamentos ou fechamentos inesperados.     | 
| RFN02  | Interface de Usuário Intuitiva        | A interface do sistema deve ser clara e fácil de usar, evitando complexidades desnecessárias que possam confundir os usuários. |
| RFN03  | Desempenho Acelerado em Funções Críticas | As funcionalidades críticas, como reconhecimento facial e autenticação, devem ser otimizadas para operar de maneira rápida e eficiente. |

---

## Requisitos Elicitados do Termo de Uso

**Requisitos Funcionais**

| Nº | Requisito                                         | Descrição                                                                                                               |
|----|---------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------|
| RF07  | Identificação do Usuário                          | O sistema deve permitir a autenticação do usuário utilizando métodos como biometria facial e validação biográfica.      |
| RF08  | Gerenciamento de Dados do Usuário                 | O sistema deve permitir ao usuário acessar, atualizar e excluir seus dados pessoais.                                    |
| RF09  | Recuperação de Conta                              | O sistema deve oferecer funcionalidades para recuperação de conta através de SMS, e-mail ou suporte direto.             |
| RF10  | Gerenciamento de Documentos Digitais              | O sistema deve permitir aos usuários visualizar e gerenciar documentos digitais associados à sua conta.                 |
| RF11  | Funcionalidade de Prova de Vida                   | O sistema deve oferecer uma funcionalidade de Prova de Vida para verificação de beneficiários de programas de previdência ou assistência social. |

**Requisitos Não Funcionais**

| Nº | Requisito                               | Descrição                                                                                                                 |
|----|-----------------------------------------|---------------------------------------------------------------------------------------------------------------------------|
| RFN04  | Tratamento de Dados Sensíveis           | O sistema deve assegurar o tratamento adequado dos dados sensíveis de acordo com a legislação (LGPD).                     |
| RFN05  | Consentimento para Tratamento de Dados  | O sistema deve obter consentimento explícito dos usuários para o tratamento de seus dados pessoais.                        |
| RFN06  | Suporte a Múltiplas Plataformas         | O sistema deve ser acessível através de diferentes dispositivos e navegadores.                                             |
| RFN07  | Níveis de Segurança de Acesso           | O sistema deve implementar múltiplos níveis de segurança de acesso (bronze, prata, ouro).                                  |
| RFN08  | Disponibilidade e Acessibilidade        | O sistema deve ser acessível e disponível para todos os usuários, garantindo acessibilidade para usuários com deficiências e oferecendo suporte a múltiplas plataformas e navegadores. |


## Bibliografia
> 1. REtraining UFSC Guia. Análise de Documentos . Disponível em: https://retraining.inf.ufsc.br/guia/app/classificacoes/tecnicas-de-elicitacao-de-requisitos/entidades/tecnicas-de-elicitacao-de-requisitos-analise-de-documentos. Acesso em 11 de Abril de 2024.
> 2. Termo de Uso Gov.br .  Disponível em: https://cadastro.acesso.gov.br/termo-de-uso. Acesso em 11 de Abril de 2024.
> 3. Play Store. Comentários Gov.br. Disponível em: https://play.google.com/store/apps/details?id=br.gov.meugovbr&hl=pt_BR&gl=US. Acesso em 11 de Abril de 2024.Disponível


## Histórico de versão

| Versão | Data | Descrição | Responsáveis | Revisor |
| :----: | :--: | :-----------------------------------------------------: | :----------------------------------------------------------------------------------------------: | :----------------------------------------------: |
|  1.0   | 11/04/2024 | Versão inicial  | [Caio Berg](https://github.com/Caio-bergbjj) | [Ester Lino](https://github.com/esteerlino) |