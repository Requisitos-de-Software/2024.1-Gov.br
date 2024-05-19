# Cenários

## Introdução

Os cenários são uma descrição escrita em linguagem natural de eventos e situações que ocorrem em uma utilização específica de um software. Eles são úteis para compreender as interações entre ambientes e sistemas. Também são particularmente úteis para mostrar como requisitos não funcionais estão relacionados ao funcionamento do sistema.

## Metodologia

Foram criados 10 no total. Seguindo o modelo aprensentado na tabela 1 a seguir:

<p style="text-align: center">Tabela 1 - Modelo dos cenários</p>

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

<p style="text-align: center">Tabela 2 - Cenário 01</p>

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

<p style="text-align: center">Tabela 3 - Cenário 02</p>

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
<br>

<p style="text-align: center">Fonte: <a href=""></a></p>

### Cenário 3: Redefinição de Senha no Aplicativo gov.br

<p style="text-align: center">Tabela 4 - Cenário 03</p>

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

<p style="text-align: center">Fonte: <a href=""></a></p>

### Cenário 4: Acessar Documentos Digitais no Celular

<p style="text-align: center">Tabela 5 - Cenário 04</p>

| Elemento                            | Descrição                      |
| ----------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Objetivo**                            | Descrever o processo de um cidadão acessar seus documentos digitais de forma rápida e segura no aplicativo gov.br, sem a necessidade de apresentar documentos físicos.           |
| **Contexto**                            | O cidadão precisa apresentar um documento digital para comprovar sua identidade ou acessar um serviço público. O cidadão já possui uma conta no gov.br e está conectado à internet em seu smartphone. |
| **Recursos**                            | Smartphone com o aplicativo gov.br instalado. Conexão com a internet.                                                                                                               |
| **Ator**                                | Cidadão                                                                                                           |
| **Episódios**                          | -O cidadão abre o aplicativo gov.br e faz login com seu CPF e senha.<br>-Na tela inicial do aplicativo, o cidadão localiza e clica no botão "Carteira de documentos".<br>-O cidadão visualiza a lista de seus documentos digitais armazenados no aplicativo, incluindo tipo de documento, data de emissão, órgão emissor e status do documento.<br>-O cidadão toca no documento que deseja visualizar ou compartilhar.<br>-O cidadão pode verificar a autenticidade do documento digital utilizando mecanismos como código QR, assinatura digital e histórico de acessos.<br>-O cidadão utiliza o documento digital para comprovar sua identidade ou acessar um serviço público online ou presencial.<br>-O aplicativo armazena os documentos digitais do cidadão de forma segura, utilizando criptografia e outros mecanismos de proteção.<br>-O aplicativo verifica periodicamente se há atualizações disponíveis para os documentos digitais do cidadão.<br>-O aplicativo se integra com outros serviços digitais do governo, permitindo que o cidadão acesse seus documentos digitais de forma centralizada. |
| **Restrições**                        | - O cidadão deve estar conectado à internet para utilizar o aplicativo gov.br.<br>- A disponibilidade de documentos digitais está sujeita à autenticidade e integridade dos documentos armazenados.<br>- A verificação da autenticidade dos documentos depende da implementação de mecanismos de segurança pelo órgão emissor.<br>- O acesso aos documentos digitais pode estar sujeito à autorização do cidadão e às políticas de privacidade do governo.                                        |
| **Exceção**                            | - Se houver falha na autenticação do usuário, o aplicativo deve exibir uma mensagem de erro e oferecer opções de recuperação de conta.<br>- Se ocorrer um erro durante o acesso aos documentos digitais, o aplicativo deve apresentar uma mensagem de falha e orientar o usuário sobre as medidas a serem tomadas.<br>- Se um documento digital não estiver disponível ou não puder ser verificado, o aplicativo deve informar ao usuário sobre a situação e sugerir alternativas.   |
<br>

<p style="text-align: center">Fonte: <a href="https://github.com/esteerlino">Ester Lino</a></p>

### Cenário 5: Agendamento de Visita ao Palácio do Planalto - gov.br

<p style="text-align: center">Tabela 6 - Cenário 05</p>

| Elemento     | Descrição                                                                                                           |
| ------------ |----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Objetivo**     |  Descrever um cenário para agendamento de visita no Palácio do Planalto, utilizando o aplicativo gov.br |
| Contexto     | O cidadãodeseja agendar uma visita ao Palácio do Planalto para conhecer as instalações e saber mais sobre o funcionamento do governo federal. Ele está acessando o aplicativo gov.br em seu smartphone |
| **Recursos**     | Smartphone com acesso à internet<br>Aplicativo gov.br instalado e atualizado<br>Conta gov.br com login e senha. |
| **Ator**         | Cidadão                                                                                                                                                     |
| **Episódios**    | O usuário abre o aplicativo gov.br na tela de login e digita seu CPF e senha.<br>Na barra de pesquisa digita "Agendar"<br>Localiza o serviço "Agendar visita institucional ao Palácio do Planalto"<br>O aplicativo direciona para uma nova página de Apreciação<br>O usuário clica em "Iniciar"<br>O usuário é direcionado para uma tela com a imagem do Palácio do Planalto e clica em "Entrar com GOV.BR"<br>O usuário seleciona o número de visitantes.<br>O usuário seleciona a data da visita<br>O usuário seleciona o horário<br>O usuário seleciona o idioma do evento<br>O usuário concorda com os termos e condições.|
| **Restrições**  | A redefinição de senha no aplicativo gov.br requer acesso à internet.<br> O agendamento só pode ser realizado por meio de uma conta gov.br.<br>O número máximo de visitantes por agendamento é de 5 pessoas.<br>As datas e horários disponíveis para visitação podem variar de acordo com a agenda do Palácio do Planalto.<br>O Palácio do Planalto possui regras de segurança rígidas que devem ser respeitadas por todos os visitantes.  |
| **Exceção**     | Escolas podem solicitar agendamento de visita para grupos de alunos por meio de canais específicos do Palácio do Planalto, como o site oficial ou e-mail.<br>Autoridades, diplomatas e outros convidados oficiais podem agendar visitas por meio de canais diplomáticos ou de contato direto com o cerimonial do Palácio do Planalto.<br>Em casos excepcionais, o Palácio do Planalto pode analisar solicitações de visita fora do horário normal de agendamento ou para grupos com mais de 5 pessoas.  |                                                                               |
<br>

<p style="text-align: center">Fonte: <a href=""></a></p>

### Cenário 6: Consulta do Histórico de Login no Aplicativo gov.br

<p style="text-align: center">Tabela 7 - Cenário 06</p>

| Elemento     | Descrição                                                                                                           |
| ------------ |----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Objetivo**     |  Descrever um cenário detalhado para ilustrar a consulta do histórico de login no aplicativo gov.br, com foco na privacidade |
| Contexto     | O cidadão está acessando o aplicativo gov.br. Ele deseja verificar seu histórico de login para identificar possíveis atividades suspeitas em sua conta. |
| **Recursos**     | Smartphone com acesso à internet<br>Aplicativo gov.br instalado e atualizado<br>Conta gov.br com login e senha. |
| **Ator**         | Cidadão                                                                                                                                                     |
| **Episódios**    | O usuário abre o aplicativo gov.br na tela de login e digita seu CPF e senha.<br>Na tela principal, o cidadão vai até a parte inferior da tela na seção "Minha conta"<br>O cidadão localiza "Privacidade"<br>Nessa seção, o cidadão clica em "Histórico de login"<br>O cidadão pode consultar os acessos do login em relação à data, hora e o serviço relacionado|
| **Restrições**  | A redefinição de senha no aplicativo gov.br requer acesso à internet.<br> O agendamento só pode ser realizado por meio de uma conta gov.br.<br>O histórico de login é armazenado por um período limitado de tempo, definido pelo gov.br. Acessos realizados fora desse período não serão exibidos na lista.  |
| **Exceção**     | O titular da conta gov.br pode solicitar a exclusão de itens específicos do seu histórico de login, desde que não interfiram em investigações legais ou em processos internos do gov.br.<br>Se o cidadão identificar erros no seu histórico de login, como acessos não realizados por ele, deve entrar em contato com o suporte do gov.br para que o problema seja investigado e corrigido.  |
<br>

<p style="text-align: center">Fonte: <a href=""></a></p>

### Cenário 7: Eficiência no Acesso e Agendamento de Serviços - gov.br

<p style="text-align: center">Tabela 8 - Cenário 07</p>

| Elemento           | Descrição                                                                                                                                             |
| ------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Objetivo**           | Descrever como o aplicativo gov.br garante a eficiência no acesso e agendamento de serviços públicos, proporcionando uma experiência rápida, simples e intuitiva para os cidadãos. |
| **Contexto**           | O cidadão busca agilidade e praticidade na resolução de suas necessidades com o governo. O aplicativo gov.br deve ser um canal eficiente para o acesso e agendamento de diversos serviços públicos, como emissão de documentos, consulta de benefícios sociais, agendamento de consultas médicas e outros. |
| **Recursos**           | Smartphone com o aplicativo gov.br instalado, conexão com a internet, banco de dados integrado com os órgãos públicos responsáveis pelos serviços, interface de usuário amigável e intuitiva. |
| **Ator**               | Cidadão                                                                                                                                               |
| **Episódios**         | -O cidadão utiliza a barra de pesquisa do aplicativo gov.br para encontrar rapidamente o serviço desejado. <br>-O cidadão pode navegar facilmente pelo aplicativo, sem precisar de conhecimentos técnicos avançados, e encontrar os serviços desejados de forma rápida e eficiente.<br>-O cidadão utiliza o aplicativo gov.br para agendar o serviço desejado, escolhendo data, hora e local de atendimento, quando disponível.<br>-O cidadão tem acesso a todas as informações necessárias para se preparar para o atendimento e utilizar o serviço de forma correta e eficiente.<br>-O cidadão pode acompanhar o status dos serviços agendados ou em andamento através do aplicativo gov.br, recebendo notificações sobre o andamento do processo. O cidadão tem acesso a informações atualizadas sobre o status dos serviços solicitados, permitindo que ele acompanhe o andamento do processo e se programe de acordo. |
| **Restrições**         | - Disponibilidade de serviços online: Nem todos os serviços públicos estão disponíveis para agendamento online no aplicativo gov.br. - Demanda por serviços: Em alguns casos, a demanda por um serviço específico pode ser alta, o que pode levar a um tempo de espera mais longo para o agendamento.<br>-Falhas técnicas no aplicativo gov.br ou na infraestrutura de comunicação podem afetar o acesso e o agendamento de serviços. |
| **Exceções**           | - Serviços presenciais: Alguns serviços públicos ainda exigem atendimento presencial, mesmo com a disponibilidade da opção online. Nesses casos, o aplicativo gov.br pode fornecer informações sobre os locais de atendimento presencial e orientar o cidadão sobre como realizar o agendamento.<br>-Situações de emergência: Em situações de emergência, o governo poderá priorizar o atendimento de serviços essenciais, podendo haver interrupções temporárias ou ajustes nos serviços disponíveis no aplicativo gov.br. |
<br>

<p style="text-align: center">Fonte: <a href=""></a></p>

### Cenário 8: Manutenção da Integridade de Documentos e Informações - gov.br

<p style="text-align: center">Tabela 9 - Cenário 08</p>

| Elemento              | Descrição                                                                                                                                             |
| --------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Objetivo**              | Descrever como o aplicativo gov.br garante a integridade dos documentos e informações consultadas pelos cidadãos, assegurando a confiabilidade e autenticidade dos dados. |
| **Contexto**              | O cidadão utiliza o aplicativo gov.br para consultar diversos documentos e informações importantes, como certidões, extratos bancários, acompanhamento de benefícios sociais e outros. É fundamental que o cidadão tenha a certeza de que os documentos e informações consultados no aplicativo gov.br são autênticos, íntegros e confiáveis. |
| **Recursos**              | Smartphone com o aplicativo gov.br instalado, conexão segura com a internet, certificados digitais e criptografia para garantir a segurança da comunicação entre o aplicativo e os servidores do governo, mecanismos de validação e verificação dos documentos e informações consultados. |
| **Ator**                  | Cidadão                                                                                                                                               |
| **Episódios**            | <br>-O cidadão utiliza o aplicativo gov.br para consultar um documento ou informação específica, como uma certidão de nascimento ou extrato bancário.<br>-O cidadão tem a certeza de que o documento consultado é autêntico e não foi falsificado ou adulterado. <br>-O cidadão tem a certeza de que as informações consultadas são precisas e confiáveis, refletindo os dados originais armazenados pelo governo. <br>-O cidadão tem fácil acesso ao histórico de consultas e pode consultar novamente os documentos e informações que precisa. <br>O cidadão tem a certeza de que seus dados e informações estão protegidos contra interceptação, espionagem ou adulteração durante a transmissão. |
| **Restrições**            | - Falhas técnicas: Falhas técnicas no aplicativo gov.br ou na infraestrutura de comunicação podem afetar a consulta de documentos e informações. - Erros humanos: Erros humanos na digitação dos dados de consulta podem levar à recuperação de documentos ou informações incorretos. - Tentativas de fraude: Tentativas de fraude por parte de terceiros podem tentar falsificar ou adulterar documentos e informações. |
| **Exceções**              | - Documentos antigos: Documentos antigos que foram digitalizados ou armazenados em formato digital antigo podem não ter os recursos de segurança necessários para garantir sua completa autenticidade e integridade.<br>-Informações que estão em processo de atualização nos sistemas do governo podem estar temporariamente indisponíveis ou apresentar inconsistências.|
<br>

<p style="text-align: center">Fonte: <a href=""></a></p>

### Cenário 9: Acessibilidade Offline - gov.br

<p style="text-align: center">Tabela 10 - Cenário 09</p>

| Elemento      | Descrição                                                                                                                                                                       |
| ------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Objetivo**      | Descrever como o aplicativo gov.br garante a acessibilidade mesmo sem conexão com a internet, permitindo que o cidadão utilize seus serviços de forma offline.                      |
| **Contexto**      | O cidadão está em uma área com sinal de internet instável ou inexistente. O cidadão precisa acessar serviços públicos urgentes, como consulta de extratos bancários, acompanhamento de benefícios sociais ou emissão de certidões. O aplicativo gov.br oferece uma solução para que o cidadão possa utilizar seus serviços mesmo sem conexão com a internet. |
| **Recursos**      | Smartphone com o aplicativo gov.br instalado. Espaço de armazenamento interno do smartphone.                                                                                     |
| **Ator**          | Cidadão                                                                                                                                                                         |
| **Episódios**|   -O cidadão pode selecionar e baixar serviços específicos para uso offline no aplicativo gov.br.<br>-Quando o cidadão está conectado à internet, o aplicativo gov.br sincroniza automaticamente os dados dos serviços baixados para uso offline com a base de dados do governo.<br>Mesmo sem conexão com a internet, o cidadão pode acessar os serviços baixados anteriormente no aplicativo gov.br.<br>-O aplicativo gov.br oferece uma interface intuitiva e menus simples para facilitar a navegação mesmo sem conexão com a internet. <br>-O aplicativo gov.br oferece recursos de acessibilidade para pessoas com deficiência, como narração de tela, compatibilidade com leitores de tela e interfaces adaptadas para diferentes tipos de deficiência.|
| **Restrições**   | -A quantidade de serviços que podem ser baixados para uso offline depende da capacidade de armazenamento interno do smartphone do cidadão.<br>-Os serviços offline só serão atualizados quando o cidadão estiver conectado à internet. É importante que o cidadão sincronize seus dados regularmente para garantir que as informações estejam precisas. <br>-Alguns serviços públicos podem ter funcionalidades complexas que não podem ser totalmente replicadas no modo offline.<br>-No modo offline, o aplicativo gov.br não permite a atualização de dados em tempo real.<br>-O suporte técnico para o aplicativo gov.br no modo offline pode ser limitado. |
| **Exceções**   | -Nem todos os serviços públicos estarão disponíveis para uso offline no aplicativo gov.br.<br>-Alguns serviços podem exigir conexão com a internet por motivos técnicos ou de segurança.<br>-Falhas técnicas no aplicativo gov.br ou no smartphone do cidadão podem afetar a disponibilidade dos serviços offline. <br>-Em caso de desastres naturais que afetem a infraestrutura de telecomunicações, o aplicativo gov.br offline pode ser a única maneira de o cidadão acessar serviços públicos essenciais. |
<br>

<p style="text-align: center">Fonte: <a href=""></a></p>

### Cenário 10: Notificação de Acessos Não Autorizados e Mudanças Críticas na Segurança - gov.br

<p style="text-align: center">Tabela 11 - Cenário 10</p>

| Elemento  | Descrição                                          |
| ---------- | -------------------------------------------------------------------------------------------- |
| **Objetivo**  | Descrever como o aplicativo gov.br notifica os usuários sobre acessos não autorizados em suas contas e alterações críticas nas configurações de segurança, garantindo a proteção de seus dados e a prevenção de fraudes.  |
| **Contexto**  | O cidadão utiliza o aplicativo gov.br para acessar diversos serviços públicos, armazenar documentos importantes e realizar transações online. A segurança das contas dos usuários é fundamental para garantir a proteção de seus dados pessoais e evitar fraudes. O aplicativo gov.br implementa um sistema robusto de notificações para alertar os usuários sobre qualquer atividade suspeita em suas contas.                     |
| **Recursos**  | Smartphone com o aplicativo gov.br instalado, conexão com a internet, endereço de e-mail ou número de telefone celular cadastrados na conta do gov.br.                   |
| **Ator**    | Cidadão                               |
| **Episódios**| Quando o aplicativo gov.br detecta um login não autorizado na conta do cidadão, o sistema envia uma notificação imediata para o e-mail ou número de telefone celular cadastrado. O cidadão é alertado imediatamente sobre o acesso não autorizado, permitindo que ele tome medidas imediatas para proteger sua conta. Tentativa de login não autorizada em uma conta do gov.br. Notificação por e-mail ou SMS informando sobre o acesso não autorizado e orientando o cidadão a tomar as medidas cabíveis. <br>-A notificação por e-mail ou SMS inclui detalhes sobre o acesso não autorizado, como data, hora, local (cidade e país) e dispositivo utilizado. <br>-A notificação por e-mail ou SMS também inclui orientações sobre como o cidadão pode proteger sua conta, como alterar sua senha, ativar a autenticação de dois fatores e revisar as configurações de segurança. <br>-O aplicativo gov.br também notifica o cidadão sobre qualquer mudança crítica na configuração de segurança de sua conta, como a alteração da senha, a ativação da autenticação de dois fatores ou a adição de um novo dispositivo autorizado. <br>-A notificação por e-mail ou SMS inclui um canal de comunicação para que o cidadão possa tirar dúvidas sobre a notificação recebida ou solicitar suporte em caso de problemas com sua conta.|
| **Restrições** | - Dependência de conexão com a internet: O recebimento das notificações depende de o cidadão ter acesso à internet em seu dispositivo móvel ou e-mail. <br>-Em alguns casos, o gov.br poderá solicitar ao cidadão que verifique sua identidade para confirmar a titularidade da conta e garantir a segurança das informações. - Possibilidade de falsos positivos: Em casos raros, o sistema de detecção de acessos não autorizados pode gerar falsos positivos, notificando o cidadão sobre um acesso que, na verdade, foi realizado por ele mesmo. Nesses casos, o cidadão poderá entrar em contato com o suporte do gov.br para esclarecer a situação. |
| **Exceções**  | Falhas técnicas no aplicativo gov.br ou na infraestrutura de comunicação podem afetar o envio das notificações. - Erros humanos: Erros humanos no cadastramento das informações de contato do cidadão podem impedir que ele receba as notificações. <br>-Ações maliciosas de terceiros podem tentar bloquear ou interceptar as notificações enviadas pelo gov.br. |
<br>

<p style="text-align: center">Fonte: <a href=""></a></p>

## Bibliografia

- SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 10. Apresentação Power Point. Disponível em: https://aprender3.unb.br/pluginfile.php/2523091/mod_resource/content/1/Aula%2010.pdf. Acesso em: 06 de maio de 2024.

## Histórico de Versão

| Versão |    Data    |                      Descrição                      |      Autor(es)      | Revisor(es)  |
| :----: | :--------: | :-------------------------------------------------: | :-----------------: | :----------: |
|  1.0   | 06/05/2024 | Versão Inicial | [Henrique Batalha](https://github.com/HeBatalha), [Carlos Gabriel](https://github.com/TheCarlosRamos) | [Arthur Gabriel](https://github.com/ArthurGabrieel) |
|  1.1   | 17/05/2024 | Correção das legendas das tabelas | [Ester Lino](https://github.com/esteerlino) | [Carlos Gabriel](https://github.com/TheCarlosRamos) |
|  1.2   | 18/05/2024 | Definição do cenário 04 | [Ester Lino](https://github.com/esteerlino) | [Henrique Batalha](https://github.com/HeBatalha) |
|  1.3   | 19/05/2024 | Definição do cenário 01 | [Carlos Gabriel](https://github.com/TheCarlosRamos) | [Henrique Batalha](https://github.com/HeBatalha) |
