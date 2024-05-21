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

As especificações de caso de uso têm o objetivo de detalhar os casos de uso utilizando uma linguagem natural. Elas descrevem de forma precisa como um sistema deve se comportar em resposta a uma solicitação externa, e são fundamentais para a análise de sistemas, garantindo que todos os requisitos funcionais sejam capturados e entendidos claramente. 

A Tabela 2 explicará melhor cada um dos seus elementos:


<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 2:</b> Explicação detalhada sobre os elementos das especificações de casos de uso</p></font>
</div>

| Código caso de uso | Nome do caso de uso |
| --- | --- |
| **Atores** | Os usuários ou sistemas externos que interagem com o caso de uso. |
| **Frequência de uso** | Refere-se à estimativa de quantas vezes ou com que regularidade o caso de uso será executado durante um determinado período de tempo. |
| **Pré-condições** | As condições que devem ser atendidas antes que o caso de uso possa ser realizado.|
| **Fluxo básico** | Trata-se da maneira "padrão" que o ator utilizará a funcionalidade, ou seja, é o que ele tentará realizar, primariamente, sempre que utilizar a funcionalidade. |
| **Fluxos alternativos** | São fluxos que podem ser executados numa funcionalidade a partir da escolha do usuário, e não a partir de erros ou exceções do sistema.|
| **Fluxos de exceção** | Descreve o que ocorre quando um erro ou uma situação excepcional surge durante a execução do caso de uso. |
| **Pós-condições** | Descreve o estado do sistema após a conclusão do caso de uso. |
| **Rastreabilidade** | Ligação do caso de uso com requistos específicos.|

<div align="center">
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/IsaqueSH">Isaque Santos</a>, 2024</p></font>
</div >


### UC01 - Fazer Login


<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 3:</b> Especificação do caso de uso Fazer Login</p></font>
</div>

| UC01 | Fazer login|
| --- | --- |
| **Atores** | Cidadão |
| **Frequência de uso** | Baixa |
| **Pré-condições** | PRE01. O usuário deve estar registrado no sistema. <br>PRE02. Possuir conexão à internet. |
| **Fluxo básico** | <b>FB01. </b> <ol> <li> O usuário chega até a página de login.<li> O sistema apresenta o formulário de login solicitando nome de usuário e senha. <li> O usuário insere seu nome de usuário e senha. <li> O usuário clica no botão "Entrar". <li> O sistema valida as credenciais fornecidas. <li> Se as credenciais são válidas, o sistema cria uma sessão para o usuário. </ol>  |
| **Fluxos alternativos** |  <b>FA01: Lembrar-me</b> <ol> <li> O usuário marca a opção "Lembrar-me" antes de clicar em "Entrar". <li> O sistema armazena informações do usuário para manter a sessão aberta por um período prolongado. <li> O usuário é logado. <li> Fim do caso de uso. </ol> <b> FA02: Esqueci a senha</b> <ol> <li> O usuário clica no link "Esqueci a senha". <li> O sistema redireciona o usuário para a página de recuperação de senha. <li>O usuário é logado. <li>Fim do caso de uso. </ol>  |
| **Fluxos de exceção** | <b>FE01: Dados do login errados </b> <ol> <li> O usuário fornece algum dado do login errado <li> O sistema informa em qual campo está com o dado inválido. </ul> </ol> <b> FE02:Código de validação errado </b> <ol> <li> O usuário fornece o código de validação errado <li> O sistema informa que o código inserido é invalido </ol> |
| **Pós-condições**|POS01. O usuário está autenticado no sistema e tem acesso às funcionalidades permitidas conforme suas permissões. |
| **Data da criação**| 19/05/2024  |
| **Rastreabilidade** | ----- |

<div align="center">
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href=""></a> ,2024</p></font>
</div >


### UC02 - Validar Credenciais


<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 4:</b> Especificação do caso de uso Validar Credenciais</p></font>
</div>

| UC02 | Validar Credenciais|
| --- | --- |
| **Atores** | Cidadão e Sistemas Governamentais |
| **Frequência de uso** | Média |
| **Pré-condições** | PRE01. O usuário deve ter uma conta válida no aplicativo gov.br. <br>PRE02. Possuir conexão à internet.<br>PRE03. O aplicativo gov.br deve estar operacional e acessível. |
| **Fluxo básico** | <b>FB01. </b> <ol> <li> O usuário abre o aplicativo gov.br.<li> O usuário seleciona a opção de verificar suas credenciais. <li> O aplicativo solicita que o usuário insira seu nome de usuário e senha. <li> O usuário insere suas credenciais e confirma. <li> O aplicativo verifica as credenciais fornecidas. <li> Se as credenciais são válidas, o aplicativo exibe uma mensagem de sucesso e permite que o usuário prossiga. </ol>  |
| **Fluxos alternativos** |  <b>FA01: Esqueci minha senha</b> <ol> <li> O usuário seleciona a opção "Esqueci minha senha". <li> O aplicativo solicita que o usuário insira seu e-mail registrado. <li> O usuário insere seu e-mail e confirma. <li> O aplicativo envia um e-mail com instruções para redefinir a senha. </ol> <b> </ol>  |
| **Fluxos de exceção** | <b>FE01: Credenciais inválidas </b> <ol> <li> O aplicativo verifica as credenciais fornecidas. <li> Se as credenciais são inválidas, o aplicativo exibe uma mensagem de erro informando que o nome de usuário ou a senha estão incorretos. </ul> </ol> <ol> |
| **Pós-condições**|POS01.O usuário verifica com sucesso suas credenciais no aplicativo gov.br. <br> POS2. O usuário pode prosseguir para outras ações dentro do aplicativo conforme suas permissões. |
| **Data da criação**| 19/05/2024  |
| **Rastreabilidade** | ----- |

<div align="center">
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href=""></a> ,2024</p></font>
</div >


### UC03 - Emitir Erro de Login


<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 5:</b> Especificação do caso de uso Emitir Erro de Login</p></font>
</div>

| UC03 | Emitir Erro de Login|
| --- | --- |
| **Atores** | Cidadão |
| **Frequência de uso** | Baixa |
| **Pré-condições** | PRE01. O usuário tentou fazer login no aplicativo gov.br. <br>PRE02. As credenciais fornecidas pelo usuário são inválidas.<br>PRE03. O aplicativo gov.br deve estar operacional e acessível. |
| **Fluxo básico** | <b>FB01. </b> <ol> <li> O usuário insere seu nome de usuário e senha no aplicativo gov.br.<li> O aplicativo verifica as credenciais fornecidas. <li> O aplicativo detecta que as credenciais são inválidas. <li> O aplicativo exibe uma mensagem de erro informando que o nome de usuário ou a senha estão incorretos. <li> O aplicativo oferece a opção de tentar fazer login novamente. </ol>  |
| **Fluxos alternativos** | ------ |
| **Fluxos de exceção** | ------ |
| **Pós-condições**|POS01.O usuário recebeu uma mensagem de erro de login no aplicativo gov.br.br. <br> POS2. O usuário pode tentar fazer login novamente com credenciais válidas. |
| **Data da criação**| 19/05/2024  |
| **Rastreabilidade** | ----- |

<div align="center">
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href=""></a> ,2024</p></font>
</div >


### UC04 - Atualizar Dados Pessoais


<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 6:</b> Especificação do caso de uso Atualizar Dados Pessoais</p></font>
</div>

| UC04 | Atualizar Dados Pessoais|
| --- | --- |
| **Atores** | Cidadão |
| **Frequência de uso** | Média |
| **Pré-condições** | PRE01. O usuário está autenticado no aplicativo gov.br. <br>PRE02. Possuir conexão à internet.<br>PRE03. O aplicativo gov.br deve estar operacional e acessível. |
| **Fluxo básico** | <b>FB01. </b> <ol> <li> O usuário acessa a seção de "Dados Pessoais" do aplicativo gov.br.<li> O aplicativo exibe os dados pessoais atuais do usuário. <li> O usuário seleciona a opção de editar os dados pessoais. <li> O aplicativo exibe um formulário com os campos para edição dos dados pessoais. <li> O usuário atualiza os campos desejados.<li> O usuário confirma a atualização dos dados pessoais. <li> O aplicativo valida os dados atualizados. <li> Se os dados são válidos, o aplicativo atualiza os dados pessoais do usuário.<li> O aplicativo exibe uma mensagem de sucesso informando que os dados foram atualizados com sucesso. </ol> |
| **Fluxos alternativos** |  <b>FA01: Cancelar atualização</b> <ol> <li> O usuário decide cancelar a atualização dos dados pessoais. <li> O aplicativo cancela a edição e retorna à visualização dos dados pessoais atuais.</ol> <b> </ol>  |
| **Fluxos de exceção** | <b>FE01:  Dados Inválidos</b> <ol> <li> O aplicativo valida os dados atualizados.<li> Se algum dado é inválido, o aplicativo exibe uma mensagem de erro informando sobre o dado inválido. <li>O aplicativo permite que o usuário corrija o dado inválido e tente atualizar novamente. </ul> </ol> <ol> |
| **Pós-condições**|POS01.Os dados pessoais do usuário foram atualizados com sucesso no aplicativo gov.br. |
| **Data da criação**| 19/05/2024  |
| **Rastreabilidade** | ADTU02, ADTU07, BS17 e ST16 |

<div align="center">
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href=""></a> ,2024</p></font>
</div >


### UC05 - Consultar Benefícios

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 7:</b> Especificação do caso de uso Consultar Benefícios</p></font>
</div>

| UC05 | Consultar Benefícios|
| --- | --- |
| **Atores** | Cidadão e Serviços Governamentais |
| **Frequência de uso** | Alta |
| **Pré-condições** | PRE01. O usuário está autenticado no aplicativo gov.br. <br>PRE02. Possuir conexão à internet.<br>PRE03. O aplicativo gov.br deve estar operacional e acessível. |
| **Fluxo básico** | <b>FB01. </b> <ol> <li> O usuário acessa a seção de "Consultar Benefícios" do aplicativo gov.br.<li> O aplicativo exibe uma lista de benefícios disponíveis para o usuário.<li> O usuário seleciona o benefício que deseja consultar. <li> O aplicativo exibe os detalhes do benefício selecionado, como informações sobre o programa, requisitos, e como solicitar. </ol> |
| **Fluxos alternativos** |  <b>FA01: Benefício Não Encontrado</b> <ol> <li> O usuário não encontra o benefício desejado na lista. <li> O aplicativo oferece a opção de buscar por benefícios específicos. <li> O usuário insere o nome do benefício na barra de busca. <li> O aplicativo exibe os resultados da busca e o usuário seleciona o benefício desejado.</ol> <b> </ol>  |
| **Fluxos de exceção** | <b>FE01:  Problemas de Conexão</b> <ol> <li> O usuário tenta acessar a consulta de benefícios.<li> Se houver problemas de conexão, o aplicativo exibe uma mensagem de erro informando sobre a falha na conexão. <li>O aplicativo sugere que o usuário tente novamente mais tarde. </ul> </ol> <ol> |
| **Pós-condições**|POS01.O usuário obteve informações atualizadas sobre os benefícios disponíveis no aplicativo gov.br. |
| **Data da criação**| 19/05/2024  |
| **Rastreabilidade** | ST05 e ST11 |

<div align="center">
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href=""></a> ,2024</p></font>
</div >


### UC06 - Aumentar nível da conta

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 8:</b> Especificação do caso de uso Aumentar nível da conta</p></font>
</div>

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

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 9:</b> Especificação do caso de uso Visualizar documentos</p></font>
</div>

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

<p style="text-align: center">Fonte: <a href="https://github.com/esteerlino">Ester Lino, 2024</a></p>

### UC08 - Baixar documentos

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 10:</b> Especificação do caso de uso Baixar documentos</p></font>
</div>

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

<p style="text-align: center">Fonte: <a href="https://github.com/esteerlino">Ester Lino, 2024</a></p>

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

## Validação dos Casos de Uso 

<iframe width="560" height="315" src="https://www.youtube.com/embed/wZRdGgvMjjA?si=6PqCsxmw7Uvno0WJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


## Referências Bibliográficas

- Lucid Software Português. Tutorial de Caso de Uso UML [Recurso eletrônico: vídeo], 2019. Disponível em: https://www.youtube.com/watch?v=ab6eDdwS3rA. Acesso em: 17 de maio de 2024.

## Bibliografia

- SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 10. Apresentação Power Point. Disponível em: https://aprender3.unb.br/pluginfile.php/2523091/mod_resource/content/1/Aula%2010.pdf. Acesso em: 17 de maio de 2024.
- VLC. Casos de Uso. Grupo VLC da disciplina Requisitos de Software, disponível em: https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/casos_de_uso. Acesso em: 17 de maio de 2024.
- Economia DF. Casos de Uso. Grupo Economia DF da disciplina Requisitos de Software, disponível em: https://requisitos-de-software.github.io/2023.2-Economia-DF/. Acesso em: 19 de maio de 2024.

## Histórico de Versão

| Versão |    Data    |                      Descrição                      |      Autor(es)      | Revisor(es)  |
| :----: | :--------: | :-------------------------------------------------: | :-----------------: | :----------: |
|  1.0   | 17/05/2024 | Versão Inicial | [Isaque Santos](https://github.com/IsaqueSH) | [Arthur Gabriel](https://github.com/ArthurGabrieel) |
|  1.1   | 19/05/2024 | Adição do diagrama de casos de uso e imagens da legenda | [Isaque Santos](https://github.com/IsaqueSH) | [Ester Lino](https://github.com/esteerlino) |
|  1.2   | 19/05/2024 | Adição de especificações de casos de uso | [Caio Berg](https://github.com/Caio-bergbjj), [Isaque Santos](https://github.com/IsaqueSH) | [Henrique Batalha](https://github.com/HeBatalha) |
|  1.3   | 19/05/2024 | Adição de especificações de casos de uso 1 a 5 | [Caio Berg](https://github.com/Caio-bergbjj), [Isaque Santos](https://github.com/IsaqueSH) | [Carlos Gabriel](https://github.com/TheCarlosRamos) |
|  1.4   | 20/05/2024 | Definição dos casos de uso 7 e 8 | [Ester Lino](https://github.com/esteerlino) | [Isaque Santos](https://github.com/IsaqueSH) |
