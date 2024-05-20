# Casos de Uso

## Introdução

Casos de uso, também conhecidos como diagramas comportamentais na notação UML, é uma ferramenta fundamental na modelagem de sistemas. É útil para a representação gráfica dos requisitos funcionais e para descrever como um sistema interage com os usuários para atingir objetivos específicos. Em outras palavras, os casos de uso detalham um conjunto de ações que um sistema ou conjunto de sistemas deve desempenhar em colaboração com um ou mais usuários externos. Isso facilita a compreensão das funcionalidades esperadas e melhora a comunicação entre desenvolvedores e stakeholders e deve ser claro e objetivo.


## Metodologia

Para a realização deste artefato, será criado um diagrama de casos de uso para representar graficamente a interação entre os atores e os casos de uso do sistema Gov.br. Ele ajudará a descrever as funcionalidades do sistema de forma clara e concisa, destacando quem(atores) pode fazer o quê(casos de uso).

Para a criação do diagrama de casos de uso, primeiro foram identificados os atores do sistema, que são dois: Cidadão e Serviços Governamentais, em seguida, foram analisados todos os casos de uso oferecidos pelo sistema, de forma em que apareciam conforme a realização dos objetivos e tarefas dentro do aplicativo. A partir da identificação dos casos de uso, foi realizada a criação do diagrama usando como ferramenta as plataformas Draw.io e LucidChart.


## Componentes

O diagrama de casos de uso é composto por quatro componentes, sendo eles: Ator, Elipse(caso de uso), Comunicação e Sistema. A tabela abaixo especifica e detalha melhor cada componente:



<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 1:</b> Legenda do diagrama de caso de uso</p></font>

<table>
  <thead>
    <tr>
      <th>Elemento</th>
      <th>Nome</th>
      <th>Função</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><figure class="usecaseElement" style="width: 70%; display: flex;"><img src="assets/Ator.png" alt="Ator"></figure></td>
      <td>Ator</td>
      <td>Representa os usuários ou sistemas externos que interagem com o sistema</td>
    </tr>
    <tr>
      <td><figure class="usecaseElement" style="width: 70%; display: flex;"><img src="assets/Elipse.png" alt="Elipse (Caso de Uso)"></figure></td>
      <td>Elipse (Caso de Uso)</td>
      <td>É uma funcionalidade ou serviço específico que o sistema oferece a seus usuários ou outros sistemas externos(atores). A elipse contém o nome do caso de uso, descrevendo a ação ou processo que o sistema realiza.</td>
    </tr>
    <tr>
      <td><figure class="usecaseElement" style="width: 70%; display: flex;"><img src="assets/Sistema.png" alt="Sistema"></figure></td>
      <td>Sistema</td>
      <td>É representado por um retângulo que delimita todas as funcionalidades que o sistema deve realizar, e define o escopo do sistema mostrando o que está incluído no projeto e como interage com atores externos</td>
    </tr>
    <tr>
      <td><figure class="usecaseElement" style="width: 70%; display: flex;"><img src="assets/Comunicação.png" alt="Comunicação"></figure></td>
      <td>Comunicação</td>
      <td>As comunicações(relacionamentos) são usadas para representar as relações ou interações entre atores e casos de uso</td>
    </tr>
  </tbody>
</table>

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/IsaqueSH">Isaque Santos</a>, 2024</p></font>
</div>

## Diagrama de Casos de Uso

Abaixo o diagrama de casos de uso:

<div align="center">
<font size="3"><p style="text-align: center"><b>Figura 1:</b> Diagrama de caso de uso do aplicativo Gov.br</p></font>

<img src="assets/UseCase.png" class="usecaseElement">

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/IsaqueSH">Isaque Santos</a> e <a href="https://github.com/HeBatalha">Henrique Batalha</a>, 2024</p></font>

</div>

## Especificação dos Casos de Uso

### UC06 - Aumentar nível da conta
| **Nome** | Aumentar nível da conta |
| - | - |
| **Atores** | Cidadão |
| **Frequência de uso** | Baixa |
| **Pré-condições** | PRE01. O cidadão deve estar logado no aplicativo; <br>PRE02. O cidadão deve ter permissão para aumentar o nível da conta. |
| **Fluxo básico** | **FB01.** <ol><li> O cidadão seleciona a opção de aumentar o nível da conta. <li> O sistema exibe os níveis disponíveis e seus benefícios. <li> O cidadão escolhe o nível desejado (bronze, prata ou ouro). <li> O sistema processa a solicitação e atualiza o nível da conta. <li> O sistema confirma a atualização e ajusta os privilégios correspondentes. <li> Fim do caso de uso. </ol> |
| **Fluxos alternativos** | |
| **Fluxos de exceção** | **FE01: Requisitos** <ol> <li> O cidadão seleciona a opção de aumentar o nível da conta. <li> O sistema exibe os níveis disponíveis e seus benefícios. <li> O cidadão escolhe o nível desejado (bronze, prata ou ouro). <li> O usuário não consegue cumprir com as especificações minímas do nível.|
| **Pós-condições** | POS01. A conta do cidadão é atualizada para o nível escolhido. <li> Fim do caso de uso.|
| **Data da criação** | 19/05/2024 |
| **Rastreabilidade** | [ADTU09](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) |

### UC07 - Visualizar documentos
| **Nome** | Visualizar documentos |
| - | - |
| **Atores** | Cidadão |
| **Frequência de uso** | Média |
| **Pré-condições** | PRE01. O cidadão deve estar logado no aplicativo. |
| **Fluxo básico** | **FB01.** <ol><li> O cidadão acessa a seção de documentos. <li> O sistema lista os documentos disponíveis. <li> O cidadão seleciona um documento. <li> O sistema exibe o documento selecionado. <li> Fim do caso de uso. </ol> |
| **Fluxos alternativos** | |
| **Fluxos de exceção** | **FE01: Documento não encontrado** <ol> <li> O cidadão acessa a seção de documentos.<li> O cidadão não encontra o documento desejado. <li> O caso de uso é encerrado. </ol> |
| **Pós-condições** | POS01. Os documentos são exibidos na interface do usuário. |
| **Data da criação** | 19/05/2024 |
| **Rastreabilidade** | [BS03](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm), [ST13](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) e [ADTU04](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) |

### UC08 - Baixar documentos
| **Nome** | Baixar documentos |
| - | - |
| **Atores** | Cidadão |
| **Frequência de uso** | Média |
| **Pré-condições** | PRE01. O cidadão deve estar logado no aplicativo. |
| **Fluxo básico** | **FB01.** <ol><li> O cidadão acessa a seção de documentos. <li> O cidadão seleciona um documento para baixar. <li> O sistema prepara o documento para download. <li> O cidadão confirma o download. <li> O sistema baixa o documento para o dispositivo do cidadão. <li> Fim do caso de uso. </ol> |
| **Fluxos alternativos** | |
| **Fluxos de exceção** | **FE01: Falha no download** <ol><li> O cidadão acessa a seção de documentos.  <li> O cidadão seleciona um documento para baixar. <li> O download falha devido a problemas de conexão. <li> O cidadão tenta novamente. <li> Fim do caso de uso. </ol> |
| **Pós-condições** | POS01. O documento é baixado para o dispositivo do cidadão. |
| **Data da criação** | 19/05/2024 |
| **Rastreabilidade** | [ADTU04](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos)  |

### UC09 - Emitir 2ª via
| **Nome** | Emitir 2ª via |
| - | - |
| **Atores** | Cidadão |
| **Frequência de uso** | Média |
| **Pré-condições** | PRE01. O cidadão deve estar logado no aplicativo. |
| **Fluxo básico** | **FB01.** <ol><li> O cidadão acessa a seção de documentos. <li> O cidadão solicita a emissão da 2ª via de um documento. <li> O sistema verifica os dados do documento original. <li> O sistema gera a 2ª via do documento. <li> O cidadão baixa a 2ª via. <li> Fim do caso de uso. </ol> |
| **Fluxos alternativos** | |
| **Fluxos de exceção** | **FE01: Documento original não encontrado** <ol><li> O sistema não encontra o documento original. <li> O caso de uso é encerrado. </ol> |
| **Pós-condições** | POS01. A segunda via do documento é gerada e disponível para download. |
| **Data da criação** | 19/05/2024 |
| **Rastreabilidade** | [REQ09](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/requisitos_elicitados) |

### UC10 - Agendar Atendimento
| **Nome** | Agendar Atendimento |
| - | - |
| **Atores** | Cidadão |
| **Frequência de uso** | Média |
| **Pré-condições** | PRE01. O cidadão deve estar logado no aplicativo. |
| **Fluxo básico** | **FB01.** <ol><li> O cidadão seleciona a opção de agendamento. <li> O sistema exibe as datas e horários disponíveis. <li> O cidadão escolhe uma data e horário. <li> O sistema confirma o agendamento. <li> Fim do caso de uso. </ol> |
| **Fluxos alternativos** | |
| **Fluxos de exceção** | **FE01: Sem horários disponíveis** <ol><li> O cidadão seleciona a opção de agendamento. <li> Não há horários disponíveis na data escolhida. <li> O cidadão escolhe outra data. <li> Fim do caso de uso. </ol> |
| **Pós-condições** | POS01. O atendimento é agendado e confirmado. |
| **Data da criação** | 19/05/2024 |
| **Rastreabilidade** | [ST04](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) |

### UC11 - Solicitar Prova de Vida
| **Nome** | Solicitar Prova de Vida |
| - | - |
| **Atores** | Cidadão |
| **Frequência de uso** | Baixa |
| **Pré-condições** | PRE01. O cidadão deve estar logado no aplicativo. |
| **Fluxo básico** | **FB01.** <ol><li> O cidadão acessa a seção de histórico de prova de vida. <li> O cidadão solicita a prova de vida. <li> O sistema realiza no aplicativo, através do reconhecimento facial. <li> O sistema confirma a solicitação e valida para o cidadão. <li> Fim do caso de uso. </ol> |
| **Fluxos alternativos** | |
| **Fluxos de exceção** | **FE01: Falha na solicitação** <ol><li> O cidadão solicita a prova de vida.<li> O sistema não consegue validar a solicitação devido a problemas técnicos. <li> O cidadão tenta novamente. <li> Fim do caso de uso. </ol> |
| **Pós-condições** | POS01. A solicitação de prova de vida é registrada. |
| **Data da criação** | 19/05/2024 |
| **Rastreabilidade** | [ADTU05](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/analise_documentos) e [ST07](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) |

### UC12 - Ver Histórico de Prova de Vida
| **Nome** | Ver Histórico de Prova de Vida |
| - | - |
| **Atores** | Cidadão |
| **Frequência de uso** | Média |
| **Pré-condições** | PRE01. O cidadão deve estar logado no aplicativo. |
| **Fluxo básico** | **FB01.** <ol><li> O cidadão acessa a seção de histórico de prova de vida. <li> O sistema exibe o histórico das provas de vida realizadas. <li> Fim do caso de uso. </ol> |
| **Fluxos alternativos** | |
| **Fluxos de exceção** | **FE01: Sem registros** <ol><li> O cidadão acessa a seção de histórico de prova de vida. <li> Não há registros de prova de vida. <li> O caso de uso é encerrado. </ol> |
| **Pós-condições** | POS01. O histórico de prova de vida é exibido. |
| **Data da criação** | 19/05/2024 |
| **Rastreabilidade** |  |

### UC13 - Baixar Certidões
| **Nome** | Baixar Certidões |
| - | - |
| **Atores** | Cidadão |
| **Frequência de uso** | Média |
| **Pré-condições** | PRE01. O cidadão deve estar logado no aplicativo. |
| **Fluxo básico** | **FB01.** <ol><li> O cidadão acessa a seção de certidões. <li> O sistema lista as certidões disponíveis (Certidão de PCD, Certificado de Cad. Único). <li> O cidadão seleciona uma certidão. <li> O sistema prepara o documento para download. <li> O cidadão confirma o download. <li> O sistema baixa a certidão para o dispositivo do cidadão. <li> Fim do caso de uso. </ol> |
| **Fluxos alternativos** | |
| **Fluxos de exceção** | **FE01: Falha no download** <ol><li> O download falha devido a problemas de conexão. <li> O cidadão tenta novamente. <li> Fim do caso de uso. </ol> |
| **Pós-condições** | POS01. A certidão é baixada para o dispositivo do cidadão. |
| **Data da criação** | 19/05/2024 |
| **Rastreabilidade** | [BS05](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm) |

### UC14 - Assinar Documentos Digitalmente
| **Nome** | Assinar Documentos Digitalmente |
| - | - |
| **Atores** | Cidadão |
| **Frequência de uso** | Média |
| **Pré-condições** | PRE01. O cidadão deve estar logado no aplicativo; <br>PRE02. O cidadão deve ter documentos disponíveis para assinatura. |
| **Fluxo básico** | **FB01.** <ol><li> O cidadão acessa a seção de assinatura digital. <li> O cidadão seleciona um documento para assinar. <li> O sistema aplica a assinatura digital ao documento. <li> O sistema salva o documento assinado e o disponibiliza para o cidadão. <li> Fim do caso de uso. </ol> |
| **Fluxos alternativos** | |
| **Fluxos de exceção** | **FE01: Falha na assinatura** <ol><li> O sistema não consegue aplicar a assinatura digital. <li> O cidadão tenta novamente. <li> Fim do caso de uso. </ol> |
| **Pós-condições** | POS01. O documento é assinado digitalmente e salvo. |
| **Data da criação** | 19/05/2024 |
| **Rastreabilidade** | [BS08](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/brainstorm), [ST03](https://requisitos-de-software.github.io/2024.1-Gov.br/#/elicitacao/storytelling) |

## Referências Bibliográficas

- Lucid Software Português. Tutorial de Caso de Uso UML [Recurso eletrônico: vídeo], 2019. Disponível em: https://www.youtube.com/watch?v=ab6eDdwS3rA. Acesso em: 17 de maio de 2024.

## Bibliografia

- SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 10. Apresentação Power Point. Disponível em: https://aprender3.unb.br/pluginfile.php/2523091/mod_resource/content/1/Aula%2010.pdf. Acesso em: 17 de maio de 2024.
- VLC. Casos de Uso. Grupo VLC da disciplina Requisitos de Software, disponível em: https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/casos_de_uso. Acesso em: 17 de maio de 2024.

## Histórico de Versão

| Versão |    Data    |                      Descrição                      |      Autor(es)      | Revisor(es)  |
| :----: | :--------: | :-------------------------------------------------: | :-----------------: | :----------: |
|  1.0   | 17/05/2024 | Versão Inicial | [Caio Berg](https://github.com/Caio-bergbjj), [Isaque Santos](https://github.com/IsaqueSH) | [Arthur Gabriel](https://github.com/ArthurGabrieel) |
|  1.1   | 19/05/2024 | Adição do diagrama de casos de uso e imagens da legenda | [Caio Berg](https://github.com/Caio-bergbjj), [Isaque Santos](https://github.com/IsaqueSH) | [Ester Lino](https://github.com/esteerlino) |
|  1.2   | 19/05/2024 | Adição de especificações de casos de uso | [Caio Berg](https://github.com/Caio-bergbjj), [Isaque Santos](https://github.com/IsaqueSH) | [Henrique Batalha](https://github.com/HeBatalha) |