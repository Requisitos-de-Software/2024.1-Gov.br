# Léxicos

## Introdução

O léxico, na Engenharia de Requisitos, tem como finalidade definir termos e expressões específicas de um domínio de aplicação. Ele assegura que todos compreendam os significados e impactos dos termos utilizados, facilitando a comunicação entre o usuário e o sistema. Ao padronizar esses termos, o léxico permite uma interação precisa e eficaz em todas as fases do desenvolvimento e uso do software.

## Metodologia

A metodologia utilizada para a elaboração deste artefato foi a LAL - Léxico Ampliado da Linguagem. Essa técnica permite identificar cada símbolo e descrevê-lo a partir da definição da noção e do impacto dele. Na tabela 1 é possível visualizar cada tipo de léxico e como definir os conceitos necessários para cada um deles.

<p style="text-align: center"><b><a id="tab_1" style="visibility: hidden;"></a>Tabela 1</b> - Léxicos segundo a LAL</p>

|  Tipo de símbolo | Noção | Impacto |
|:----------------:|:-----:|:-------:|
|      Verbo       | Quem realiza, quando acontece e quais os procedimentos. | Quais os reflexos da ação no ambiente e os novos estados decorrentes. |
|      Objeto      | Definir o objeto e identificar outros objetos com os quais ele está relacionado. | Ações que podem ser aplicadas ao objeto |
|      Estado      | O que significa e quais ações levaram a esse estado. | Identificar estados e ações que podem ocorrer a partir do estado que se descreve. |

<figcaption align="center">Fonte: <a href="https://github.com/esteerlino">Ester Lino</a></figcaption>

## Léxicos

A seguir são apresentadas as tabelas de 2 a 4, que apresentam, respectivamente os léxicos do tipo: <br>

- Verbo
- Objeto
- Estado.

### Léxicos do tipo Verbo

<p style="text-align: center"><b><a id="tab_1" style="visibility: hidden;"></a>Tabela 2</b> - Léxicos do tipo Verbo</p>

|  ID  |  Símbolo  |  Noção  |  Impacto  |  Sinônimo(s)  |  Autor(a)  |
|:----:|:---------:|:-------:|:---------:|:-----------:|:----------:|
| **L01** | Acessar o aplicativo | O [**usuário**]() acessa o [**aplicativo**]() Gov.br ou suas funcionalidades/[**serviços**]() através do login. | Permite ao [**usuário**]() utilizar as funcionalidades/[**serviços**]() disponíveis no [**aplicativo**](). | Entrar, logar |  |
| **L02** | Consultar dados | O [**usuário**]() verifica informações de [**documentos**]() e [**serviços**]() disponíveis no [**aplicativo**](). | Permite que o [**usuário**]() verifique informações importantes de maneira rápida. | Verificar, conferir | [Ester Lino](https://github.com/esteerlino)  | 
| **L03** | Editar perfil | O [**usuário**]() modifica suas informações pessoais ou dados relevantes. | Assegura que os dados do [**usuário**]() estejam sempre corretos e atualizados. | Modificar, alterar, atualizar |  |
| **L04** | Baixar arquivos | Quando o [**usuário**]() tranfere [**documentos**]() ou comprovantes para o dispositivo móvel. | Permite o [**acesso**]() offline dos [**documentos**]() e comprovantes. | Transferir, download |  |
| **L05** | Autenticar | Confirmar a identidade do [**usuário**]() ao [**acessar**]()[**serviços**]() restritos ou sensíveis. | Garante a segurança e privacidade das transações realizadas no [**aplicativo**](). | Validar, certificar  |  |
| **L06** | Assinar documentos | O [**usuário**]() inclui uma assinatura digital em um [**documento**]() utilizando o [**aplicativo**](). | Facilita a oficialização de [**documentos**]() e transações de forma segura e legal. | Firmar, ratificar  |  |
| **L07**   | Gerar código de acesso | Quando o [**usuário**]()cria um código temporário para [**acessar**]() de maneira segura as funcionalidades/[**serviços**]() do [**aplicativo**](). | Proporciona uma camada adicional de segurança para [**acessar**]() recursos sensíveis. |  Criar chave  |  |
| **L08**   | Aumentar nível de acesso | Quando o [**usuário**]()solicita a elevação do nível de [**acesso**]() para utilizar funcionalidades/[**serviços**]() mais avançados ou sensíveis. | Permite ao [**usuário**]() [**acessar**]() [**serviços**]() que necessitam de um nível mais alto de [**autenticação**](). |  Ampliar acesso, subir de nível  | [Ester Lino](https://github.com/esteerlino) |

<figcaption align="center">Fonte: <a href="https://github.com/esteerlino">Ester Lino</a></figcaption>

### Léxicos do tipo Objeto

<p style="text-align: center"><b><a id="tab_1" style="visibility: hidden;"></a>Tabela 3</b> - Léxicos do tipo Objeto</p>

|  ID  |  Símbolo  |  Noção  |  Impacto  |  Sinônimo(s)  |  Autor(a)  |
|:----:|:---------:|:-------:|:---------:|:-----------:|:----------:|
| **L09** | Usuário | Pessoa que utiliza o [**aplicativo**]() Gov.br para [**acessar**]() [**serviços**]() e informações oferecidas pelo governo. | Permite que o [**aplicativo**]() seja utilizado, que aja interação com os [**serviços**]() disponíveis. | Cliente, cidadão | [Ester Lino](https://github.com/esteerlino) |
| **L10** | Documento | Arquivo digital(CPF, CNPJ, CNH...) disponibilizado pelo [**aplicativo**]() e acessado pelo [**usuário**](). | Centraliza [**documentos**]() importantes em um único local, facilitando o [**acesso**]() e o gerenciamento por parte do [**usuário**](). | Arquivo, Comprovante |  | 
| **L11** | Serviço | Funcionalidades oferecidas pelo [**aplicativo**](), como emissão de documentos, consulta a processos... | Aumenta a facilidade e eficiÊncia de [**acesso**]() a [**serviços**]() do governo. | Recurso, funcionalidade |  |
| **L12** | Aplicativo | Software desenvolvido para dispositivos móveis para acessar [**serviços**]() governamentais. | Proporciona ao [**usuário**]() [**acesso**]() fácil e rápido aos [**serviços**]()públicos. | Programa, software |  |
| **L13** | Perfil | Conjunto de informações pessoais do [**usuário**]() armazenadas no [**aplicativo**](). | Facilita a atualização de dados pessoais. | Conta, cadastro  |  |
| **L14** | Carteira de documentos | Funcionalidade do [**aplicativo**]() que armazena digitalmente diversos [**documentos**]() pessoais do [**usuário**](), como RG, CPF, CNH e outros.. | Centraliza e organiza os [**documentos**]() importantes em um único local, facilitando o [**acesso**](). | Porta-documentos digital, Pasta de documentos  |  |
| **L15**   | Agendamento | Funcionalidade que permite ao [**usuário**]() marcar datas e horários para [**serviços**]() específicos oferecidos pelo governo. | Facilita o planejamento e a organização do [**usuário**](), evitando filas e espera desnecessárias. |  Reserva, compromisso  |  |

<figcaption align="center">Fonte: <a href="https://github.com/esteerlino">Ester Lino</a></figcaption>

### Léxicos do tipo Estado

<p style="text-align: center"><b><a id="tab_1" style="visibility: hidden;"></a>Tabela 3</b> - Léxicos do tipo Estado</p>

|  ID  |  Símbolo  |  Noção  |  Impacto  |  Sinônimo(s)  |  Autor(a)  |
|:----:|:---------:|:-------:|:---------:|:-----------:|:----------:|
| **L16** | Aguarde | Situação temporária enquanto o [**aplicativo**]() processa informações ou solicitações do [**usuário**](). | Informa o [**usuário**]() que deve aguardar até que o processo seja concluído. | Carregando, processando |  |
| **L17** | Atualizado com sucesso | Condição dos dados ou informações que foram recentemente modificados ou confirmados no [**aplicativo**](). | Assegura que as informações utilizadas pelo [**usuário**]() sejam precisas e atuais. | Modificado, alterado |  | 
| **L18** | Autenticado | Estado de um [**usuário**]() que teve sua identidade verificada e confirmada pelo [**aplicativo**](). | Garante o [**acesso**]() seguro a funcionalidades e informações restritas. | Verificado, validado, certificado |  |
| **L19** | Habilitada | Condição que indica que uma medida de segurança adicional está ativada na conta do [**usuário**](), aumentando a proteção contra [**acessos**]() não autorizados. | Reforça a segurança das informações pessoais e dos dados sensíveis do [**usuário**](), prevenindo fraudes e invasões. | Ativada  | [Ester Lino](https://github.com/esteerlino) |
| **L20** | Não foi possível recuperar ou emitir | Indica uma falha ou impossibilidade de realizar uma ação ou processo específico dentro do [**aplicativo**](), geralmente acompanhada de uma explicação sobre o motivo do erro. | Pode resultar em frustração para o [**usuário**]() e exigir intervenção para resolver o problema. | Falha, erro  |  |
| **L21** | Foto não carregada | Estado que indica que a foto de [**perfil**]() ou algum outro tipo de imagem não foi carregada corretamente na interface do [**usuário**](). | Pode afetar a experiência do [**usuário**]() ao visualizar ou compartilhar informações que requerem uma imagem. | Imagem não carregada |  |
| **L22**   | Novo | Estado que indica que um item/funcionalidade foi recentemente criado ou adicionado ao [**aplicativo**](), mas que ainda não foi totalmente utilizado ou processado. | Geralmente é um estado inicial que requer ações adicionais ou confirmação para ser completamente integrado ou utilizado pelo [**usuário**](). | Recém-criado, Criado recentemente  |  |

<figcaption align="center">Fonte: <a href="https://github.com/esteerlino">Ester Lino</a></figcaption>

## Bibliografia

- SERRANO, Milene, SERRANO, Maurício. Requisitos (Aula 10): Elicitação, Modelagem e Análise. **UnB Gama**, Brasília, 2023. Disponível em: <<https://aprender3.unb.br/pluginfile.php/2845027/mod_resource/content/1/Aula%2010.pdf>>. Acesso em: 19/05/2024.

## Histórico de versão

| Versão | Data | Descrição | Responsáveis | Revisor |
| :----: | :--: | :-----------------------------------------------------: | :----------------------------------------------------------------------------------------------: | :----------------------------------------------: |
|  1.0   | 19/05/2024 | Versão inicial do documento  | [Ester Lino](https://github.com/esteerlino) | [Carlos Gabriel](https://github.com/TheCarlosRamos) |
|  1.1  | 20/05/2024 | Atualização dos léxicos  | [Ester Lino](https://github.com/esteerlino) | [Thiago Freitas](https://github.com/thiagorfreitas) |
