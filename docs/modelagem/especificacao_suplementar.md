# Especificação Suplementar

## Introdução

Este documento apresenta a Especificação Suplementar para o projeto GovBR. A Especificação Suplementar é um artefato importante no processo de desenvolvimento de software, pois descreve os requisitos não funcionais do sistema - aqueles que não estão diretamente relacionados com a funcionalidade específica do software, mas com características como desempenho, usabilidade, confiabilidade, entre outros. Esses requisitos são cruciais para garantir a qualidade do software e a satisfação do usuário.

## Metodologia

A metodologia utilizada para a elaboração deste documento é baseada no modelo FURPS+, que é uma técnica eficaz para a coleta e organização de requisitos não funcionais.

FURPS+ é um acrônimo para Funcionalidade, Usabilidade, Confiabilidade, Desempenho e Suporte, que são as principais categorias de requisitos consideradas neste modelo. Além disso, o “+” em FURPS+ representa requisitos adicionais que podem ser relevantes, como restrições de design e requisitos de documentação e ajuda.

Este documento foi estruturado de acordo com as categorias do modelo FURPS+. Cada seção do documento corresponde a uma categoria e apresenta uma descrição detalhada dos requisitos não funcionais relacionados a essa categoria para o aplicativo GovBR.

## FURPS+

### F: Funcionalidade (Functionality)

Os requisitos funcionais foram elicitados na seção de elicitação, [tabela 1](../../elicitacao/requisitos_elicitados.md#tab_1) da página de [requisitos elicitados](../../elicitacao/requisitos_elicitados.md).

### U: Usabilidade (Usability)

<font><p style="text-align: center">**Tabela 1** - Requisitos de Usabilidade.</p></font>

<center>

|  ID   |                                                           Descrição                                                            |
| :---: | :----------------------------------------------------------------------------------------------------------------------------: |
| USA01 | A interface do sistema deve ser clara e fácil de usar, evitando complexidades desnecessárias que possam confundir os usuários. |
| USA02 |                            Usabilidade: A interface do aplicativo deve ser simples e fácil de usar.                            |
| USA03 |                                        O aplicativo deve ser intuitivo e fácil de usar.                                        |
| USA04 |                         Como usuário, desejo acessar o aplicativo gov.br de forma rápida e intuitiva.                          |
| USA05 |                     Como usuário, desejo encontrar facilmente o serviço de agendamento na Receita Federal.                     |
| USA06 |            Como usuário, desejo acessar as funções de assinatura digital para agilizar a assinatura de documentos.             |

</center>

<font size="3"><p style="text-align: center">Fonte: [Thiago Freitas](https://github.com/thiagorfreitas).</p></font>

### R: Confiabilidade (Reliability)

<font><p style="text-align: center">**Tabela 2** - Requisitos de Confiabilidade.</p></font>

<center>

|  ID   |                                                          Descrição                                                          |
| :---: | :-------------------------------------------------------------------------------------------------------------------------: |
| CON01 |        O sistema deve ser estável e confiável, funcionando corretamente sem travamentos ou fechamentos inesperados.         |
| CON02 |              Confiabilidade: O aplicativo deve manter a integridade dos documentos e informações consultadas.               |
| CON03 |                         O aplicativo deve ser seguro e confiável, protegendo os dados dos usuários.                         |
| CON04 | O sistema deve notificar os usuários de quaisquer acessos não autorizados ou mudanças críticas na segurança de suas contas. |
| CON05 |              Como usuário, desejo garantir a segurança na transmissão e armazenamento de documentos sensíveis.              |

</center>

<font size="3"><p style="text-align: center">Fonte: [Ester Lino](https://github.com/esteerlino).</p></font>

### P: Desempenho (Performance)

<font><p style="text-align: center">**Tabela 3** - Requisitos de Desempenho.</p></font>

<center>

| Identificador |                                                                Descrição                                                                |
| :-----------: | :-------------------------------------------------------------------------------------------------------------------------------------: |
|     DES01     | As funcionalidades críticas, como reconhecimento facial e autenticação, devem ser otimizadas para operar de maneira rápida e eficiente. |
|     DES02     |                                          O aplicativo deve ter boa performance e ser estável.                                           |
|     DES03     |                            Eficiência: O aplicativo deve ser rápido no acesso e no agendamento de serviços.                             |

</center>

<font size="3"><p style="text-align: center">Fonte: [Carlos Gabriel](https://github.com/TheCarlosRamos).</p></font>

### S: Suporte (Supportability)

<font><p style="text-align: center">**Tabela 4** - Requisitos de Suportabilidade.</p></font>

<center>

| Identificador |                                                                                       Descrição                                                                                        |
| :-----------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|     SUP01     | O sistema deve ser acessível e disponível para todos os usuários, garantindo acessibilidade para usuários com deficiências e oferecendo suporte a múltiplas plataformas e navegadores. |
|     SUP02     |                                                                  O aplicativo deve ter suporte ao cliente eficiente.                                                                   |
|     SUP03     |                                                    Como usuário, desejo uma navegação intuitiva para buscar processos e documentos.                                                    |
|     SUP04     |                                                     Como usuário, desejo eficiência no agendamento e acompanhamento de processos.                                                      |
|     SUP05     |                                               Como usuário, desejo receber atualizações relevantes sobre processos e benefícios sociais.                                               |

</center>

<font size="3"><p style="text-align: center">Fonte: [Arthur Gabriel](https://github.com/ArthurGabrieel).</p></font>

### +: Restrições de Design

<font><p style="text-align: center">**Tabela 5** - Restrições de Design.</p></font>

<center>

| Identificador |                                                        Descrição                                                        |
| :-----------: | :---------------------------------------------------------------------------------------------------------------------: |
|     RD01      |                O sistema deve implementar múltiplos níveis de segurança de acesso (bronze, prata, ouro).                |
|     RD02      |     O aplicativo deve exigir que a senha do usuário possua obrigatoriamente letras, números e caracteres especiais.     |
|     RD03      | O aplicativo deve permitir que os usuários se autentiquem de forma segura, usando credenciais únicas, como CPF e senha. |

</center>

<font size="3"><p style="text-align: center">Fonte: [Henrique Batalha](https://github.com/HeBatalha).</p></font>

### +: Ajuda e Documentação

<font><p style="text-align: center">**Tabela 6** - Requisitos de Ajuda e Documentação.</p></font>

<center>

| Identificador |                                                Descrição                                                 |
| :-----------: | :------------------------------------------------------------------------------------------------------: |
|     AD01      | Atualização: O aplicativo deve manter os usuários informados sobre novidades e atualizações importantes. |
|     AD02      |      Privacidade: Garantir que as informações dos usuários não sejam compartilhadas sem permissão.       |

</center>

<font size="3"><p style="text-align: center">Fonte: [Isaque Santos](https://github.com/IsaqueSH).</p></font>

### +: Interfaces

<font><p style="text-align: center">**Tabela 7** - Requisitos de Interfaces.</p></font>

<center>

| Identificador |                                               Descrição                                               |
| :-----------: | :---------------------------------------------------------------------------------------------------: |
|     INT01     | O sistema deve assegurar o tratamento adequado dos dados sensíveis de acordo com a legislação (LGPD). |
|     INT02     |  O sistema deve obter consentimento explícito dos usuários para o tratamento de seus dados pessoais.  |
|     INT03     |            O sistema deve ser acessível através de diferentes dispositivos e navegadores.             |

</center>

<font size="3"><p style="text-align: center">Fonte: [Caio Berg](https://github.com/Caio-bergbjj).</p></font>

## Bibliografia

- SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 13. Apresentação Power Point. Disponível em: https://aprender3.unb.br/pluginfile.php/2845007/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf. Acesso em: 19 de maio de 2024.

## Histórico de Versão

| Versão |    Data    | Descrição                                         |                                                                                                                                              Autor(es)                                                                                                                                               |                     Revisor(es)                     |
| :----: | :--------: | :------------------------------------------------ | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------: |
| `1.0`  | 16/05/2024 | Criação do documento                              |                                                                                              [Arthur Gabriel](https://github.com/ArthurGabrieel) e [Thiago Ribeiro](https://github.com/thiagorfreitas)                                                                                               |    [Caio Berg](https://github.com/Caio-bergbjj)     |
| `1.1`  | 19/05/2024 | Definição da Metodologia e Introdução ao trabalho |                                                                                              [Arthur Gabriel](https://github.com/ArthurGabrieel) e [Thiago Ribeiro](https://github.com/thiagorfreitas)                                                                                               |    [Caio Berg](https://github.com/Caio-bergbjj)     |
| `1.2`  | 20/05/2024 | Adição das Tabelas e Requisitos                   | [Arthur Gabriel](https://github.com/ArthurGabrieel), [Caio Berg](https://github.com/Caio-bergbjj), [Isaque Santos](https://github.com/IsaqueSH), [Henrique Batalha](https://github.com/HeBatalha), [Carlos Gabriel](https://github.com/TheCarlosRamos) e [Ester Lino](https://github.com/esteerlino) | [Thiago Freitas](https://github.com/thiagorfreitas) |
