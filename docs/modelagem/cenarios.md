# Cenários

## Introdução

Os cenários são uma descrição escrita em linguagem natural de eventos e situações que ocorrem em uma utilização específica de um software. Eles são úteis para compreender as interações entre ambientes e sistemas. Também são particularmente úteis para mostrar como requisitos não funcionais estão relacionados ao funcionamento do sistema.

## Metodologia

Foram criados 07 cenários no total, seguindo o modelo aprensentado na tabela 1. As tabelas de 2 a 8 correspondem aos cenários definidos pelos membros do grupo.

<font><p style="text-align: center">**Tabela 1** - Modelo dos cenários</p></font>

| Elemento           | Descrição                                                                                                                                             |
| ------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Objetivo**           | Proposito do cenário. |
| **Contexto**           | Condições do inicio do cenário, tempo e local. |
| **Recursos**           | Recursos que o ator dispõe. |
| **Ator**               | Sujeito principal do cenário. |
| **Episódios**         | Acontecimentos, eventos e ações do cenário. |
| **Restrições**         | Restriçõe e limitações que podem afetar os episódios. |
| **Exceções**           | Condições ou acontecimentos que podem impossibilitar o cenário |

<p style="text-align: center">Fonte: <a href="https://github.com/TheCarlosRamos">Carlos Gabriel</a> e <a href="https://github.com/HeBatalha">Henrique Batalha</a></p>

## Cenários criados

### Cenário 1: Consulta de CPF - gov.br

<font><p style="text-align: center">**Tabela 2** - Cenário 01</p></font>

| Elemento    | Descrição                                                                                       |
| ----------- | ----------------------------------------------------------------------------------------------- |
| **Objetivo**   | Descrever o processo de um cidadão consultar CPF no aplicativo Gov.br. |
| **Contexto**    | O cidadão brasileiro deseja consultar seu CPF através do aplicativo gov.br. Ele está em casa, acessando o aplicativo em seu smartphone |
| **Recursos**    | Smartphone com o aplicativo Gov.br instalado. Conexão com a internet.                          |
| **Ator**        | Cidadão                                                                                         |
| **Episódios**   | O cidadão acessa a opção "Serviços" no aplicativo Gov.br<br>Busca pela opção "Consulta de CPF".<br>O aplicativo direciona o cidadão para a página de consulta de CPF.<br>O cidadão digita seu número de CPF e sua data de nascimento.<br>O cidadão confirma a ação e obtem os dados. |
| **Restrições**  | Para consultar o CPF, o cidadão precisa ter acesso à internet e um smartphone com o aplicativo gov.br instalado.<br>O CPF digitado deve ser válido e estar associado ao usuário logado no aplicativo.<br>O aplicativo pode apresentar instabilidade ou falhas de conexão em momentos específicos, afetando a consulta do CPF. |
| **Exceção**     | Se o CPF digitado for inválido ou não estiver associado ao usuário logado, o aplicativo exibirá uma mensagem de erro informando o problema.<br>Em caso de falhas de conexão, o aplicativo tentará reconectar-se automaticamente.<br>Se a falha persistir, o cidadão poderá tentar novamente mais tarde. |
<br>
<p style="text-align: center">Fonte: <a href="https://github.com/TheCarlosRamos">Carlos Gabriel</a></p>

### Cenário 2:  Simulação de Aposentadoria - gov.br

<font><p style="text-align: center">**Tabela 3** - Cenário 02</p></font>

| Elemento     | Descrição                                                                                                           |
| ------------ |----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Objetivo**     | Descrever um cenário para ilustrar a simulação de aposentadoria no aplicativo Gov.br para os cidadãos. |
| Contexto     | O cidadão está em casa e está curioso para saber quando poderá se aposentar e quanto receberá de benefício. O cidadão já possui uma conta no gov.br e está conectado à internet. |
| **Recursos**     | Aplicativo gov.br instalado e atualizado.<br>Conta gov.br com login e senha.<br>Dados cadastrais atualizados no INSS, incluindo tempo de contribuição e histórico de salários. |
| **Ator**         | Cidadão                                                                                                                                                     |
| **Episódios**    | O usuário abre o aplicativo gov.br e faz login com seu CPF e senha.<br>O usuário localiza a barra de pesquisa e digita "Aposentadoria"<br> O usuário localiza a opção "Simular Aposentadoria" e clica.<br>O aplicativo direciona o cidadão para uma página da calculadora do INSS e o cidadão clica em "Iniciar"<br>O cidadão localiza a opção "Simular aposentadoria".<br>O cidadão ajusta os dados com o empregador e o tempo de serviço.<br>O cidadão clica em "Recalcular" e obtém os dados  |
| **Restrições**  | A simulação para quem só possui contribuição depois de 13/11/2019 ainda está em desenvolvimento.<br>A simulação de aposentadoria no aplicativo gov.br requer acesso à internet.  |
| **Exceção**     | A simulação pode apresentar resultados imprecisos ou incompletos se os dados cadastrais do cidadão no INSS estiverem desatualizados ou incorretos.<br>A legislação previdenciária brasileira é complexa e pode sofrer alterações ao longo do tempo. |
<br>

<p style="text-align: center">Fonte: <a href="https://github.com/ArthurGabrieel">Arthur Gabriel</a></p>

### Cenário 3: Redefinição de Senha no Aplicativo gov.br

<font><p style="text-align: center">**Tabela 4** - Cenário 03</p></font>

| Elemento     | Descrição                                                                                                           |
| ------------ |----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Objetivo**     |  Descrever um cenário para ilustrar o processo de redefinição de senha do gov.br |
| Contexto     | O cidadão, em casa, acessa o aplicativo gov.br em seu smartphone. Ele esqueceu sua senha e precisa redefini-la para entrar em sua conta. |
| **Recursos**     | Smartphone com acesso à internet<br>Aplicativo gov.br instalado e atualizado<br>Endereço de e-mail cadastrado na conta gov.br ou número de celular associado. |
| **Ator**         | Cidadão                                                                                                                                                     |
| **Episódios**    | O usuário abre o aplicativo gov.br na tela de login e digita seu CPF.<br>O usuário localiza a opção "Esqueci minha senha" <br>O usuário localiza a opção "Fazer reconhecimento facial" e clica.<br>O aplicativo direciona o cidadão para uma página de recuperação onde pede para que o cidadão posicione o rosto na área delimitada para validar o reconhecimento facial.<br>A página mostra que será enviado um código para o e-mail cadastrado<br>O cidadão abre o e-mail, localiza o código e digita no espaço da página de recuperação.<br>A página de recuperação pede a nova senha e a confirmação. Feito isso, a senha será redefinida. |
| **Restrições**  | A redefinição de senha no aplicativo gov.br requer acesso à internet.<br>O link enviado por e-mail ou SMS para redefinição de senha possui um tempo de validade limitado.<br>Se o cidadão digitar um endereço de e-mail ou número de celular incorreto ou desatualizado, não receberá o link de redefinição.  |
| **Exceção**     | Se a conta do cidadão for bloqueada por tentativas excessivas de login incorretos, a redefinição de senha pelo aplicativo não estará disponível.<br>Se o cidadão alterar seu número de celular ou endereço de e-mail cadastrado na conta gov.br, precisará atualizar esses dados no perfil da sua conta. |
<br>

<p style="text-align: center">Fonte: <a href="https://github.com/Caio-bergbjj">Caio Berg</a></p>

### Cenário 4: Consulta de CNPJ - gov.br

<font><p style="text-align: center">**Tabela 5** - Cenário 04</p></font>

| Elemento    | Descrição                                                                                       |
| ----------- | ----------------------------------------------------------------------------------------------- |
| **Objetivo**   | Descrever o processo de um cidadão consultar CNPJ no aplicativo Gov.br.Ele precisa consultar os dados cadastrais de uma empresa com a qual pretende fazer negócio e verificar se a empresa está em situação regular junto à Receita Federal. |
| **Contexto**    | O cidadão brasileiro deseja consultar CNPJ através do aplicativo gov.br. Ele está em casa, acessando o aplicativo em seu smartphone |
| **Recursos**    | Smartphone com o aplicativo Gov.br instalado. Conexão com a internet.                          |
| **Ator**        | Cidadão                                                                                         |
| **Episódios**   | O cidadão acessa a opção "Serviços" no aplicativo Gov.br<br>Busca pela opção "Consulta de CNPJ".<br>O aplicativo direciona o cidadão para a página de consulta de CNPJ.<br>O cidadão preenche o tipo de pesquisa<br>Preenche a situação cadastral<br>Preenche a UF<br>CNPJ (completo)<br>O cidadão clica em PESQUISAR |
| **Restrições**  | Para consultar o CNPJ, o cidadão precisa ter acesso à internet e um smartphone com o aplicativo gov.br instalado.<br>Se o número do CNPJ digitado estiver incorreto ou se a empresa não estiver cadastrada na base de dados da Receita Federal, o aplicativo exibirá uma mensagem de erro e a consulta não será realizada. |
| **Exceção**     | Em alguns casos, o aplicativo gov.br pode permitir a consulta de CNPJ por meio da razão social ou nome fantasia da empresa, desde que as informações sejam digitadas corretamente e a empresa esteja cadastrada na base de dados da Receita Federal.<br>Órgãos públicos federais, estaduais e municipais podem ter acesso a informações adicionais sobre empresas, como dados fiscais e societários, mediante convênios específicos com a Receita Federal. |
<br>

<p style="text-align: center">Fonte: <a href="https://github.com/esteerlino">Ester Lino</a></p>

### Cenário 5: Agendamento de Visita ao Palácio do Planalto - gov.br

<font><p style="text-align: center">**Tabela 6** - Cenário 05</p></font>

| Elemento     | Descrição                                                                                                           |
| ------------ |----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Objetivo**     |  Descrever um cenário para agendamento de visita no Palácio do Planalto, utilizando o aplicativo gov.br |
| Contexto     | O cidadão deseja agendar uma visita ao Palácio do Planalto para conhecer as instalações e saber mais sobre o funcionamento do governo federal. Ele está acessando o aplicativo gov.br em seu smartphone |
| **Recursos**     | Smartphone com acesso à internet<br>Aplicativo gov.br instalado e atualizado<br>Conta gov.br com login e senha. |
| **Ator**         | Cidadão                                                                                                                                                     |
| **Episódios**    | O usuário abre o aplicativo gov.br na tela de login e digita seu CPF e senha.<br>Na barra de pesquisa digita "Agendar"<br>Localiza o serviço "Agendar visita institucional ao Palácio do Planalto"<br>O aplicativo direciona para uma nova página de Apreciação<br>O usuário clica em "Iniciar"<br>O usuário é direcionado para uma tela com a imagem do Palácio do Planalto e clica em "Entrar com GOV.BR"<br>O usuário seleciona o número de visitantes.<br>O usuário seleciona a data da visita<br>O usuário seleciona o horário<br>O usuário seleciona o idioma do evento<br>O usuário concorda com os termos e condições.|
| **Restrições**  | O agendamento no aplicativo gov.br requer acesso à internet.<br> O agendamento só pode ser realizado por meio de uma conta gov.br.<br>O número máximo de visitantes por agendamento é de 5 pessoas.<br>As datas e horários disponíveis para visitação podem variar de acordo com a agenda do Palácio do Planalto.<br>O Palácio do Planalto possui regras de segurança rígidas que devem ser respeitadas por todos os visitantes.  |
| **Exceção**     | Escolas podem solicitar agendamento de visita para grupos de alunos por meio de canais específicos do Palácio do Planalto, como o site oficial ou e-mail.<br>Autoridades, diplomatas e outros convidados oficiais podem agendar visitas por meio de canais diplomáticos ou de contato direto com o cerimonial do Palácio do Planalto.<br>Em casos excepcionais, o Palácio do Planalto pode analisar solicitações de visita fora do horário normal de agendamento ou para grupos com mais de 5 pessoas.  |                                                                               |
<br>

<p style="text-align: center">Fonte: <a href="https://github.com/IsaqueSH">Isaque Santos</a></p>

### Cenário 6: Consulta do Histórico de Login no Aplicativo gov.br

<font><p style="text-align: center">**Tabela 7** - Cenário 06</p></font>

| Elemento     | Descrição                                                                                                           |
| ------------ |----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Objetivo**     |  Descrever um cenário detalhado para ilustrar a consulta do histórico de login no aplicativo gov.br, com foco na privacidade |
| Contexto     | O cidadão está acessando o aplicativo gov.br. Ele deseja verificar seu histórico de login para identificar possíveis atividades suspeitas em sua conta. |
| **Recursos**     | Smartphone com acesso à internet<br>Aplicativo gov.br instalado e atualizado<br>Conta gov.br com login e senha. |
| **Ator**         | Cidadão                                                                                                                                                     |
| **Episódios**    | O usuário abre o aplicativo gov.br na tela de login e digita seu CPF e senha.<br>Na tela principal, o cidadão vai até a parte inferior da tela na seção "Minha conta"<br>O cidadão localiza "Privacidade"<br>Nessa seção, o cidadão clica em "Histórico de login"<br>O cidadão pode consultar os acessos do login em relação à data, hora e o serviço relacionado|
| **Restrições**  | A consulta do histórico no aplicativo gov.br requer acesso à internet.<br> A consulta só pode ser realizado por meio de uma conta gov.br.<br>O histórico de login é armazenado por um período limitado de tempo, definido pelo gov.br. Acessos realizados fora desse período não serão exibidos na lista.  |
| **Exceção**     | O titular da conta gov.br pode solicitar a exclusão de itens específicos do seu histórico de login, desde que não interfiram em investigações legais ou em processos internos do gov.br.<br>Se o cidadão identificar erros no seu histórico de login, como acessos não realizados por ele, deve entrar em contato com o suporte do gov.br para que o problema seja investigado e corrigido.  |
<br>

<p style="text-align: center">Fonte: <a href="https://github.com/thiagorfreitas">Thiago Freitas</a></p>

### Cenário 7: Consulta dos Termos de Uso do Aplicativo gov.br

<font><p style="text-align: center">**Tabela 8** - Cenário 07</p></font>

| Elemento     | Descrição                                                                                                           |
| ------------ |----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Objetivo**     |  Descrever um cenário para consulta dos termos de uso do aplicativo gov.br |
| Contexto     | O cidadão está está acessando o aplicativo gov.br pela primeira vez em seu smartphone. Ele deseja se familiarizar com os termos de uso da plataforma antes de criar sua conta e começar a utilizar os serviços disponíveis. |
| **Recursos**     | Smartphone com acesso à internet<br>Aplicativo gov.br instalado e atualizado<br>Conta gov.br com login e senha. |
| **Ator**         | Cidadão                                                                                                                                                     |
| **Episódios**    | O usuário abre o aplicativo gov.br na tela de login e digita seu CPF e senha.<br>Na tela principal, o cidadão vai até a parte inferior da ela, onde tem as funcionalidades. <br>O cidadão localiza "Menu" e clica.<br>Abre uma barra lateral com a versão do aplicativo e o Termo de uso.<br>O aplicativo direciona o cidadão para uma nova tela com o Termo de uso e aviso de privacidade<br>O cidadão identifica o termo de suas seções|
| **Restrições**  | A consulta dos termos de uso no aplicativo gov.br requer acesso à internet.  |
| **Exceção**     | O gov.br pode atualizar os termos de uso periodicamente para atender a novas necessidades legais ou regulatórias.<br> Os termos de uso do aplicativo gov.br também devem estar disponíveis em outros canais, como no site oficial do gov.br<br>  |
<br>

<p style="text-align: center">Fonte: <a href="https://github.com/HeBatalha">Henrique Batalha</a></p>

## Bibliografia

- SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 10. Apresentação Power Point. Disponível em: https://aprender3.unb.br/pluginfile.php/2523091/mod_resource/content/1/Aula%2010.pdf. Acesso em: 06 de maio de 2024.

## Histórico de Versão

| Versão |    Data    |                      Descrição                      |      Autor(es)      | Revisor(es)  |
| :----: | :--------: | :-------------------------------------------------: | :-----------------: | :----------: |
|  1.0   | 06/05/2024 | Versão Inicial | [Henrique Batalha](https://github.com/HeBatalha), [Carlos Gabriel](https://github.com/TheCarlosRamos) | [Arthur Gabriel](https://github.com/ArthurGabrieel) |
|  1.1   | 17/05/2024 | Correção das legendas das tabelas | [Ester Lino](https://github.com/esteerlino) | [Carlos Gabriel](https://github.com/TheCarlosRamos) |
|  1.2   | 18/05/2024 | Definição do cenário 04 | [Ester Lino](https://github.com/esteerlino) | [Henrique Batalha](https://github.com/HeBatalha) |
|  1.3   | 19/05/2024 | Definição do cenário 01 | [Carlos Gabriel](https://github.com/TheCarlosRamos) | [Henrique Batalha](https://github.com/HeBatalha) |
|  1.4   | 19/05/2024 | Definição do cenário 07 | [Henrique Batalha](https://github.com/HeBatalha) | [Carlos Gabriel](https://github.com/TheCarlosRamos) |
|  1.5  | 20/05/2024 | Atualização dos cenários  | [Arthur Gabriel](https://github.com/ArthurGabrieel), [Caio Berg](https://github.com/Caio-bergbjj), [Carlos Gabriel](https://github.com/TheCarlosRamos), [Ester Lino](https://github.com/esteerlino), [Henrique Batalha](https://github.com/HeBatalha), [Isaque Santos](https://github.com/IsaqueSH), [Thiago Freitas](https://github.com/thiagorfreitas) | [Carlos Gabriel](https://github.com/TheCarlosRamos)  |
