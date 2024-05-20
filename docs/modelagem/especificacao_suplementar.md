# Especificação Suplementar

## Introdução
Este documento apresenta a Especificação Suplementar para o projeto GovBR. A Especificação Suplementar é um artefato importante no processo de desenvolvimento de software, pois descreve os requisitos não funcionais do sistema - aqueles que não estão diretamente relacionados com a funcionalidade específica do software, mas com características como desempenho, usabilidade, confiabilidade, entre outros. Esses requisitos são cruciais para garantir a qualidade do software e a satisfação do usuário.

## Metodologia
A metodologia utilizada para a elaboração deste documento é baseada no modelo FURPS+, que é uma técnica eficaz para a coleta e organização de requisitos não funcionais.

FURPS+ é um acrônimo para Funcionalidade, Usabilidade, Confiabilidade, Desempenho e Suporte, que são as principais categorias de requisitos consideradas neste modelo. Além disso, o “+” em FURPS+ representa requisitos adicionais que podem ser relevantes, como restrições de design e requisitos de documentação e ajuda.

Este documento foi estruturado de acordo com as categorias do modelo FURPS+. Cada seção do documento corresponde a uma categoria e apresenta uma descrição detalhada dos requisitos não funcionais relacionados a essa categoria para o aplicativo GovBR.

## FURPS+

### F: Funcionalidade (Functionality)

| Identificador | Descrição |
|:-------------:|:---------:|
| RF01 | O sistema deve possuir uma funcionalidade de reconhecimento facial para autenticação do usuário. |
| RF02 | O sistema deve permitir que os usuários recuperem suas senhas através de métodos seguros e eficientes. |
| RF03 | O sistema deve oferecer verificação em duas etapas como uma camada adicional de segurança para os usuários. |
| RF04 | O sistema deve permitir que os usuários utilizem suas credenciais para acessar diferentes serviços governamentais de forma centralizada. |
| RF05 | O sistema deve facilitar o processo de mudança de celular pelo usuário, permitindo a transferência de segurança e autenticações sem necessidade de cancelar e recriar a conta. |
| RF06 | O sistema deve notificar os usuários de quaisquer acessos não autorizados ou mudanças críticas na segurança de suas contas. |
| RF07 | O sistema deve permitir a autenticação do usuário utilizando métodos como biometria facial e validação biográfica. |
| RF08 | O sistema deve permitir ao usuário acessar, atualizar e excluir seus dados pessoais. |
| RF09 | O sistema deve oferecer funcionalidades para recuperação de conta através de SMS, e-mail ou suporte direto. |
| RF10 | O sistema deve permitir aos usuários visualizar e gerenciar documentos digitais associados à sua conta. |

### U: Usabilidade (Usability)

| Identificador | Descrição |
|:-------------:|:---------:|
| USA01 | A interface do sistema deve ser clara e fácil de usar, evitando complexidades desnecessárias que possam confundir os usuários. |
| USA02 | Usabilidade: A interface do aplicativo deve ser simples e fácil de usar. |
| USA03 | O aplicativo deve ser intuitivo e fácil de usar. |
| USA04 | Como usuário, desejo acessar o aplicativo gov.br de forma rápida e intuitiva. |
| USA05 | Como usuário, desejo encontrar facilmente o serviço de agendamento na Receita Federal. |
| USA06 | Como usuário, desejo acessar as funções de assinatura digital para agilizar a assinatura de documentos. |

### R: Confiabilidade (Reliability)

| Identificador | Descrição |
|:-------------:|:---------:|
| CON01 | O sistema deve ser estável e confiável, funcionando corretamente sem travamentos ou fechamentos inesperados. |
| CON02 | Confiabilidade: O aplicativo deve manter a integridade dos documentos e informações consultadas. |
| CON03 | O aplicativo deve ser seguro e confiável, protegendo os dados dos usuários. |
| CON04 | O sistema deve notificar os usuários de quaisquer acessos não autorizados ou mudanças críticas na segurança de suas contas. |
| CON05 | Como usuário, desejo garantir a segurança na transmissão e armazenamento de documentos sensíveis. |

### P: Desempenho (Performance)

| Identificador | Descrição |
|:-------------:|:---------:|
| DES01 | As funcionalidades críticas, como reconhecimento facial e autenticação, devem ser otimizadas para operar de maneira rápida e eficiente. |
| DES02 | O aplicativo deve ter boa performance e ser estável. |
| DES03 | Eficiência: O aplicativo deve ser rápido no acesso e no agendamento de serviços. |

### S: Suporte (Supportability)

| Identificador | Descrição |
|:-------------:|:---------:|
| SUP01 | O sistema deve ser acessível e disponível para todos os usuários, garantindo acessibilidade para usuários com deficiências e oferecendo suporte a múltiplas plataformas e navegadores. |
| SUP02 | O aplicativo deve ter suporte ao cliente eficiente. |
| SUP03 | Como usuário, desejo uma navegação intuitiva para buscar processos e documentos. |
| SUP04 | Como usuário, desejo eficiência no agendamento e acompanhamento de processos. |
| SUP05 | Como usuário, desejo receber atualizações relevantes sobre processos e benefícios sociais. |

### +: Restrições de Design

| Identificador | Descrição |
|:-------------:|:---------:|
| RD01 | O sistema deve implementar múltiplos níveis de segurança de acesso (bronze, prata, ouro). |
| RD02 | O aplicativo deve exigir que a senha do usuário possua obrigatoriamente letras, números e caracteres especiais. |
| RD03 | O aplicativo deve permitir que os usuários se autentiquem de forma segura, usando credenciais únicas, como CPF e senha. |

### +: Ajuda e Documentação

| Identificador | Descrição |
|:-------------:|:---------:|
| AD01 | Atualização: O aplicativo deve manter os usuários informados sobre novidades e atualizações importantes. |
| AD02 | Privacidade: Garantir que as informações dos usuários não sejam compartilhadas sem permissão. |

### +: Interfaces

| Identificador | Descrição |
|:-------------:|:---------:|
| INT01 | O sistema deve assegurar o tratamento adequado dos dados sensíveis de acordo com a legislação (LGPD). |
| INT02 | O sistema deve obter consentimento explícito dos usuários para o tratamento de seus dados pessoais. |
| INT03 | O sistema deve ser acessível através de diferentes dispositivos e navegadores. |

## Bibliografia

- SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 13. Apresentação Power Point. Disponível em: https://aprender3.unb.br/pluginfile.php/2845007/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf. Acesso em: 19 de maio de 2024.

## Histórico de Versão

| Versão |    Data    | Descrição                                |                                                 Autor(es)                                                 |                 Revisor(es)                  |
| :----: | :--------: | :--------------------------------------- | :-------------------------------------------------------------------------------------------------------: | :------------------------------------------: |
| `1.0`  | 16/05/2024 | Criação do documento | [Arthur Gabriel](https://github.com/ArthurGabrieel) e [Thiago Ribeiro](https://github.com/thiagorfreitas) | [Caio Berg](https://github.com/Caio-bergbjj) |
| `1.1`  | 19/05/2024 | Definição da Metodologia e Introdução ao trabalho | [Arthur Gabriel](https://github.com/ArthurGabrieel) e [Thiago Ribeiro](https://github.com/thiagorfreitas) | [Caio Berg](https://github.com/Caio-bergbjj) |