# First Things First

## Introdução

*First Things First* é uma técnica de gerenciamento de tempo que enfatiza a importância de completar as tarefas mais importantes primeiro. Esta técnica é baseada na ideia de que, para ser eficaz e produtivo, você deve se concentrar nos requisitos que têm o maior impacto em seus objetivos e resultados. Essa abordagem leva em consideração o custo, risco, benefício e penalidade relacionados a cada requisito e dessa forma define a prioridade associada.

## Metodologia

Descrição dos papeis:

- ***Gerente***: Responsável pelo processo e os requisitos mostrados.
- ***Desenvolvedor***: Membro da equipe de desenvolvimento, julga o custo e risco dos requisitos.
- ***Cliente***: Julga o benefício e penalidade dos requisitos.

<center>

**Tabela 1** - Lista de Participantes

| Nome                                                | Papel         |
| --                                                  | --            |
| [Henrique Batalha](https://github.com/HeBatalha)    | Mediador      |
| [Carlos Gabriel](https://github.com/TheCarlosRamos) | Mediador      |
| [Isaque Santos](https://github.com/IsaqueSH)        | Desenvolvedor |
| Doan Filho | Usuário |

**Fonte**: [Henrique Batalha](https://github.com/HeBatalha)

</center>

<br>

Reuniões gravadas:

- Entre um mediador e o desenvolvedor. Realizado em duas partes no dia 14/04/2024: 

<iframe width="460" height="215" src="https://www.youtube.com/embed/AbhOq84xDHg?si=ioeYwkhgkxXGSAcy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

- Entre um mediador e o usuário. Realizado no dia 14/04/2024:

<iframe width="460" height="215" src="https://www.youtube.com/embed/ck6qjMUL5pg?si=LrJ5g1htOfVdEmHg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<br>

Os seguintes passos foram realizados no processo *First Things First*:

**1.** Fazer uma lista de todos os requisitos. Se um requisito B depende de um requisito A, apenas o requisito A será analisado.

**2.** Estimar o benefício que cada requisito representa ao cliente em uma escala de 1 - menos significativo a 9 - mais significativo.

**3.** Estimar a penalidade que não-implementação de cada requisito causará em uma escala de 1 - nenhuma penalidade a 9 - grande penalidade.

**4.** Calcular o valor total: <div style="background-color: #17202A;; padding: 5px;"><center> (Benefício * Peso) + (Penalidade * Peso) </center></div>

**5.** Estimar o custo de implementação de cada requisito em uma escala de 1 - menos custoso a 9 - mais custoso.

**6.** Estimar o grau de risco de cada requisito em uma escala de 1 - menos risco/facilidade a 9 - representa maior dificuldade e viabilidade.

**7.** Calcular a prioridade de cada requisito: <div style="background-color: #17202A;; padding: 5px;"><center>Valor (Custo * Peso + Risco * Peso)</center></div>

**8.** Ordenar a tabela em ordem decrescente de prioridade.

## Resultados

<center>

**Tabela 2** - Resultado da priorização de requisitos


| ID | Benefício<br>Relativo | Penalidade<br>Relativa | Valor<br>total | Valor<br>(%) | Custo<br>Relativo | Custo<br>% | Risco<br>Relativo | Risco<br>% | Prioridade |
|------|--------------------|---------------------|-------------|------------|----------------|------------|----------------|-------------|--------------|
| BS06 | 9 | 9 | 27 | 1,516150297 | 4 | 1,044386423 | 4 | 1,27388535 | 5,084230572 |
| RF06 | 7 | 8 | 22 | 1,186552406 | 4 | 1,044386423 | 4 | 1,27388535 | 4,084753743 |
| RF03 | 8 | 9 | 25 | 1,318391562 | 5 | 1,305483029 | 6 | 1,910828025 | 4,082399473 |
| BS16 | 9 | 9 | 27 | 1,450230719 | 5 | 1,305483029 | 7 | 2,229299363 | 4,080568373 |
| RF05 | 5 | 6 | 16 | 0,8569545155 | 3 | 0,7832898172 | 3 | 0,9554140127 | 3,085695452 |
| RF02 | 6 | 7 | 19 | 0,9887936717 | 4 | 1,044386423 | 4 | 1,27388535 | 3,082399473 |
| RF10 | 6 | 7 | 19 | 0,9887936717 | 4 | 1,044386423 | 3 | 0,9554140127 | 3,082399473 |
| BS20 | 7 | 7 | 21 | 1,120632828 | 4 | 1,044386423 | 3 | 0,9554140127 | 3,080045202 |
| RF11 | 8 | 9 | 25 | 1,252471984 | 6 | 1,566579634 | 5 | 1,592356688 | 3,078279499 |
| RFN02 | 8 | 8 | 24 | 1,252471984 | 5 | 1,305483029 | 4 | 1,27388535 | 3,078279499 |
| BS07 | 8 | 8 | 24 | 1,252471984 | 5 | 1,305483029 | 6 | 1,910828025 | 3,078279499 |
| BS02 | 9 | 9 | 27 | 1,38431114 | 6 | 1,566579634 | 6 | 1,910828025 | 3,076906174 |
| ST06 | 6 | 6 | 18 | 0,9228740936 | 4 | 1,044386423 | 2 | 0,6369426752 | 2,076906174 |
| ST12 | 6 | 6 | 18 | 0,9228740936 | 4 | 1,044386423 | 2 | 0,6369426752 | 2,076906174 |
| RF09 | 7 | 7 | 21 | 1,05471325 | 5 | 1,305483029 | 4 | 1,27388535 | 2,075336661 |
| ST03 | 7 | 7 | 21 | 1,05471325 | 5 | 1,305483029 | 3 | 0,9554140127 | 2,075336661 |
| ST05 | 7 | 7 | 21 | 1,05471325 | 5 | 1,305483029 | 3 | 0,9554140127 | 2,075336661 |
| ST07 | 7 | 7 | 21 | 1,05471325 | 5 | 1,305483029 | 3 | 0,9554140127 | 2,075336661 |
| ST11 | 7 | 7 | 21 | 1,05471325 | 5 | 1,305483029 | 3 | 0,9554140127 | 2,075336661 |
| ST14 | 7 | 7 | 21 | 1,05471325 | 5 | 1,305483029 | 3 | 0,9554140127 | 2,075336661 |
| ST19 | 7 | 7 | 21 | 1,05471325 | 5 | 1,305483029 | 3 | 0,9554140127 | 2,075336661 |
| ST21 | 7 | 7 | 21 | 1,05471325 | 5 | 1,305483029 | 3 | 0,9554140127 | 2,075336661 |
| RF08 | 8 | 8 | 24 | 1,186552406 | 6 | 1,566579634 | 5 | 1,592356688 | 2,074159525 |
| RFN05 | 8 | 8 | 24 | 1,186552406 | 6 | 1,566579634 | 5 | 1,592356688 | 2,074159525 |
| RFN06 | 8 | 9 | 25 | 1,186552406 | 7 | 1,82767624 | 6 | 1,910828025 | 2,074159525 |
| RFN07 | 8 | 9 | 25 | 1,186552406 | 7 | 1,82767624 | 6 | 1,910828025 | 2,074159525 |
| ST02 | 8 | 8 | 24 | 1,186552406 | 6 | 1,566579634 | 4 | 1,27388535 | 2,074159525 |
| ST04 | 8 | 8 | 24 | 1,186552406 | 6 | 1,566579634 | 4 | 1,27388535 | 2,074159525 |
| ST08 | 8 | 8 | 24 | 1,186552406 | 6 | 1,566579634 | 4 | 1,27388535 | 2,074159525 |
| ST10 | 8 | 8 | 24 | 1,186552406 | 6 | 1,566579634 | 4 | 1,27388535 | 2,074159525 |
| ST13 | 8 | 8 | 24 | 1,186552406 | 6 | 1,566579634 | 4 | 1,27388535 | 2,074159525 |
| ST17 | 8 | 8 | 24 | 1,186552406 | 6 | 1,566579634 | 4 | 1,27388535 | 2,074159525 |
| ST18 | 8 | 8 | 24 | 1,186552406 | 6 | 1,566579634 | 4 | 1,27388535 | 2,074159525 |
| ST20 | 8 | 8 | 24 | 1,186552406 | 6 | 1,566579634 | 4 | 1,27388535 | 2,074159525 |
| BS13 | 8 | 8 | 24 | 1,186552406 | 6 | 1,566579634 | 5 | 1,592356688 | 2,074159525 |
| BS21 | 8 | 8 | 24 | 1,186552406 | 6 | 1,566579634 | 4 | 1,27388535 | 2,074159525 |
| BS22 | 8 | 9 | 25 | 1,186552406 | 7 | 1,82767624 | 8 | 2,547770701 | 2,074159525 |
| RF04 | 9 | 9 | 27 | 1,318391562 | 7 | 1,82767624 | 8 | 2,547770701 | 2,073243976 |
| RF07 | 9 | 9 | 27 | 1,318391562 | 7 | 1,82767624 | 6 | 1,910828025 | 2,073243976 |
| RFN01 | 9 | 9 | 27 | 1,318391562 | 7 | 1,82767624 | 6 | 1,910828025 | 2,073243976 |
| ST01 | 9 | 9 | 27 | 1,318391562 | 7 | 1,82767624 | 5 | 1,592356688 | 2,073243976 |
| ST09 | 9 | 9 | 27 | 1,318391562 | 7 | 1,82767624 | 5 | 1,592356688 | 2,073243976 |
| ST15 | 9 | 9 | 27 | 1,318391562 | 7 | 1,82767624 | 5 | 1,592356688 | 2,073243976 |
| ST16 | 9 | 9 | 27 | 1,318391562 | 7 | 1,82767624 | 5 | 1,592356688 | 2,073243976 |
| ST22 | 9 | 9 | 27 | 1,318391562 | 7 | 1,82767624 | 5 | 1,592356688 | 2,073243976 |
| BS01 | 9 | 8 | 26 | 1,318391562 | 6 | 1,566579634 | 4 | 1,27388535 | 2,073243976 |
| BS11 | 9 | 8 | 26 | 1,318391562 | 6 | 1,566579634 | 5 | 1,592356688 | 2,073243976 |
| BS17 | 9 | 9 | 27 | 1,318391562 | 7 | 1,82767624 | 6 | 1,910828025 | 2,073243976 |
| BS18 | 9 | 9 | 27 | 1,318391562 | 7 | 1,82767624 | 5 | 1,592356688 | 2,073243976 |
| BS10 | 6 | 7 | 19 | 0,8569545155 | 6 | 1,566579634 | 7 | 2,229299363 | 1,071412876 |
| RFN03 | 7 | 7 | 21 | 0,9887936717 | 6 | 1,566579634 | 5 | 1,592356688 | 1,070628119 |
| BS05 | 7 | 7 | 21 | 0,9887936717 | 6 | 1,566579634 | 5 | 1,592356688 | 1,070628119 |
| BS08 | 7 | 7 | 21 | 0,9887936717 | 6 | 1,566579634 | 5 | 1,592356688 | 1,070628119 |
| BS14 | 8 | 8 | 24 | 1,120632828 | 7 | 1,82767624 | 5 | 1,592356688 | 1,070039552 |
| BS19 | 8 | 9 | 25 | 1,120632828 | 8 | 2,088772846 | 7 | 2,229299363 | 1,070039552 |
| BS12 | 8 | 7 | 23 | 1,120632828 | 6 | 1,566579634 | 5 | 1,592356688 | 1,070039552 |
| RFN04 | 9 | 9 | 27 | 1,252471984 | 8 | 2,088772846 | 7 | 2,229299363 | 1,069581777 |
| RFN08 | 9 | 9 | 27 | 1,252471984 | 8 | 2,088772846 | 7 | 2,229299363 | 1,069581777 |
| BS03 | 9 | 8 | 26 | 1,252471984 | 7 | 1,82767624 | 6 | 1,910828025 | 1,069581777 |
| BS23 | 9 | 9 | 27 | 1,252471984 | 8 | 2,088772846 | 6 | 1,910828025 | 1,069581777 |
| RF01 | 7 | 8 | 22 | 0,9228740936 | 8 | 2,088772846 | 9 | 2,866242038 | 0,06591957811 |
| BS04 | 8 | 7 | 23 | 1,05471325 | 7 | 1,82767624 | 7 | 2,229299363 | 0,06591957811 |
| BS09 | 8 | 7 | 23 | 1,05471325 | 7 | 1,82767624 | 6 | 1,910828025 | 0,06591957811 |
| BS15 | 8 | 7 | 23 | 1,05471325 | 7 | 1,82767624 | 7 | 2,229299363 | 0,06591957811 |
| TOTAL |  |  | 1517 |  | 383 | 100 | 314 | 100 |  |


**Fonte**: [Carlos Gabriel](https://github.com/TheCarlosRamos)
</center>

### Descrição dos Requisitos Funcionais

<center>

**Tabela 3** - Requisitos Funcionais - Análise de Documentos 
</center>

| ID | Descrição                                                                                                            |
|----|----------------------------------------------------------------------------------------------------------------------|
| RF01  | O sistema deve possuir uma funcionalidade de reconhecimento facial para autenticação do usuário.                      |
| RF02  | O sistema deve permitir que os usuários recuperem suas senhas através de métodos seguros e eficientes.                |
| RF03  | O sistema deve oferecer verificação em duas etapas como uma camada adicional de segurança para os usuários.           |
| RF04  | O sistema deve permitir que os usuários utilizem suas credenciais para acessar diferentes serviços governamentais de forma centralizada. |
| RF05  | O sistema deve facilitar o processo de mudança de celular pelo usuário, permitindo a transferência de segurança e autenticações sem necessidade de cancelar e recriar a conta. |
| RF06  | O sistema deve notificar os usuários de quaisquer acessos não autorizados ou mudanças críticas na segurança de suas contas. |
| RF07  | O sistema deve permitir a autenticação do usuário utilizando métodos como biometria facial e validação biográfica.      |
| RF08  | O sistema deve permitir ao usuário acessar, atualizar e excluir seus dados pessoais.                                    |
| RF09  | O sistema deve oferecer funcionalidades para recuperação de conta através de SMS, e-mail ou suporte direto.             |
| RF10  | O sistema deve permitir aos usuários visualizar e gerenciar documentos digitais associados à sua conta.                 |
| RF11  | O sistema deve oferecer uma funcionalidade de Prova de Vida para verificação de beneficiários de programas de previdência ou assistência social. |

<center>

**Fonte**: [Análise de Documentos](../elicitacao/analise_documentos.md)

<br>

**Tabela 4** - Requisitos Funcionais - Storytelling
</center>

| ID | Descrição                                                                                      |
|---------------|------------------------------------------------------------------------------------------------|
| ST01          | Como usuário, desejo acessar o aplicativo gov.br de forma rápida e intuitiva.                  |
| ST02          | Como usuário, desejo encontrar facilmente o serviço de agendamento na Receita Federal.         |
| ST03          | Como usuário, desejo acessar as funções de assinatura digital para agilizar a assinatura de documentos. |
| ST04          | Como usuário, desejo agendar atendimentos em órgãos públicos através do aplicativo.            |
| ST05          | Como usuário, desejo consultar informações sobre benefícios sociais através do aplicativo.     |
| ST06          | Como usuário, desejo acessar a função de carteira digital no aplicativo.                      |
| ST07          | Como usuário, desejo continuar recebendo minha aposentadoria através da função de prova de vida. |
| ST08          | Como usuário, desejo uma navegação intuitiva para buscar processos e documentos.               |
| ST09          | Como usuário, desejo garantir a segurança na transmissão e armazenamento de documentos sensíveis. |
| ST10          | Como usuário, desejo eficiência no agendamento e acompanhamento de processos.                 |
| ST11          | Como usuário, desejo receber atualizações relevantes sobre processos e benefícios sociais.    |
| ST12          | Como usuário, desejo substituir minha carteira física por uma versão digital no aplicativo.   |
| ST13          | Como usuário, desejo acesso rápido aos meus documentos no celular, sem a necessidade de documentos físicos. |
| ST14          | Como usuário, desejo poder acessar meus documentos mesmo sem conexão com a internet.          |
| ST15          | Como usuário, desejo garantir a privacidade das informações pessoais.                         |

<center>

**Fonte**: [Storytelling](../elicitacao/storytelling.md)

<br>

**Tabela 5** - Requisitos Funcionais - Brainstorm
</center>

| ID   | Descrição                                                                                                              |
| ---- | ---------------------------------------------------------------------------------------------------------------------- |
| BS01 | O aplicativo deve permitir que os usuários se autentiquem de forma segura, usando credenciais únicas, como CPF e senha |
| BS02 | O usuário deve ser capaz de logar com as credências do gov.br                                                          |
| BS03 | O usuário deve conseguir visualizar seus documentos                                                                    |
| BS04 | O usuário deve conseguir agendar serviços específicos                                                                  |
| BS05 | O usuário deve conseguir emitir/baixar certidões                                                                       |
| BS06 | O usuário deve conseguir se logar no aplicativo                                                                        |
| BS07 | O login deve possuir autenticação em dois fatores                                                                      |
| BS08 | O usuário deve conseguir assinar documentos digitalmente                                                               |
| BS09 | O usuário deve conseguir se inscrever em concursos públicos                                                            |
| BS10 | O usuário deve conseguir consultar programas do governo                                                                |
| BS11 | O usuário deve conseguir se conectar com o Detran                                                                      |
| BS12 | O usuário deve conseguir se conectar com o NIS                                                                         |
| BS13 | O usuário deve conseguir se conectar com o ID Jovem                                                                    |
| BS14 | O usuário deve conseguir usar o aplicativo para pagar impostos trabalhistas                                            |
| BS15 | O usuário deve conseguir obter o código de acesso                                                                      |
| BS16 | O aplicativo deve possuir ferramentas de acessibilidade (Alto contraste, aumentar a fonte, audiodescrição)             |

<center>

**Fonte**: [Brainstorm](../elicitacao/brainstorm.md)
</center>

### Descrição dos Requisitos Não Funcionais


<center>

**Tabela 6** - Requisitos Não Funcionais - Análise de Documentos
</center>

| ID | Descrição                                                                                      |
|---------------|------------------------------------------------------------------------------------------------|
| RFN04  | O sistema deve assegurar o tratamento adequado dos dados sensíveis de acordo com a legislação (LGPD).                     |
| RFN05  | O sistema deve obter consentimento explícito dos usuários para o tratamento de seus dados pessoais.                        |
| RFN06  | O sistema deve ser acessível através de diferentes dispositivos e navegadores.                                             |
| RFN07  | O sistema deve implementar múltiplos níveis de segurança de acesso (bronze, prata, ouro).                                  |
| RFN08  | O sistema deve ser acessível e disponível para todos os usuários, garantindo acessibilidade para usuários com deficiências e oferecendo suporte a múltiplas plataformas e navegadores. |

<center>

**Fonte**: [Análise de Documentos](../elicitacao/analise_documentos.md)

<br>

**Tabela 7** - Requisitos Não Funcionais - Storytelling
</center>

| ID | Descrição                                                                                      |
|---------------|------------------------------------------------------------------------------------------------|
| ST16         | Segurança: O aplicativo deve garantir a segurança dos dados pessoais dos usuários.            |
| ST17         | Usabilidade: A interface do aplicativo deve ser simples e fácil de usar.                      |
| ST18         | Eficiência: O aplicativo deve ser rápido no acesso e no agendamento de serviços.               |
| ST19         | Acessibilidade: O aplicativo deve ser acessível mesmo sem conexão com a internet.              |
| ST20         | Confiabilidade: O aplicativo deve manter a integridade dos documentos e informações consultadas. |
| ST21         | Atualização: O aplicativo deve manter os usuários informados sobre novidades e atualizações importantes. |
| ST22         | Privacidade: Garantir que as informações dos usuários não sejam compartilhadas sem permissão. |

<center>

**Fonte**: [Storytelling](../elicitacao/storytelling.md)

<br>

**Tabela 8** - Requisitos  Não Funcionais - Brainstorm
</center>

| ID   | Descrição                                                                                                       |
| ---- | --------------------------------------------------------------------------------------------------------------- |
| BS17 | O aplicativo deve ser seguro e confiável, protegendo os dados dos usuários                                      | 
| BS18 | O login deve ser feito de maneira rápida e segura                                                               |
| BS19 | O aplicativo deve ser acessível a pessoas com deficiência                                                       |
| BS20 | O aplicativo deve exigir que a senha do usuário possua obrigatoriamente letras, números e caracteres especiais. |
| BS21 | O aplicativo deve ser intuitivo e fácil de usar                                                                 |
| BS22 | O aplicativo deve ter boa performance e ser estável                                                             |
| BS23 | O aplicativo deve ter suporte ao cliente eficiente                                                              |

<center>

**Fonte**: [Brainstorm](../elicitacao/brainstorm.md)
</center>

## Bibliografia

- SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 07: Elicitação, Modelagem e Análise. Apresentação Power Point. Disponível em: https://aprender3.unb.br/pluginfile.php/2692779/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf. Acesso em: 13 de abril de 2024.

## Histórico de Versão

| Versão |    Data    |                      Descrição                      |      Autor(es)      | Revisor(es)  |
| :----: | :--------: | :-------------------------------------------------: | :-----------------: | :----------: |
|  1.0   | 13/04/2024 | Versão Inicial | [Henrique Batalha](https://github.com/HeBatalha), [Carlos Gabriel](https://github.com/TheCarlosRamos) | [Arthur Gabriel](https://github.com/ArthurGabrieel) |
|  1.1   | 15/04/2024 | Adição da tabela dos resultados | [Henrique Batalha](https://github.com/HeBatalha), [Carlos Gabriel](https://github.com/TheCarlosRamos) | [Arthur Gabriel](https://github.com/ArthurGabrieel) |
|  1.2   | 15/04/2024 | Adição dos vídeos das entrevistas | [Henrique Batalha](https://github.com/HeBatalha), [Carlos Gabriel](https://github.com/TheCarlosRamos) | [Arthur Gabriel](https://github.com/ArthurGabrieel) |
|  1.3   | 16/04/2024 | Correções no arquivo | [Henrique Batalha](https://github.com/HeBatalha) | [Arthur Gabriel](https://github.com/ArthurGabrieel) |
|  1.4   | 22/04/2024 | Correções no arquivo | [Henrique Batalha](https://github.com/HeBatalha) | [Carlos Gabriel](https://github.com/TheCarlosRamos) |

