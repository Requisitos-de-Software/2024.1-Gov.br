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

### Cenário 1: Agendamento de Atendimento em Órgão Público - gov.br

<p style="text-align: center">Tabela 2 - Cenário 01</p>

| Elemento    | Descrição                                                                                       |
| ----------- | ----------------------------------------------------------------------------------------------- |
| **Objetivo**   | Descrever o processo de um cidadão agendar um atendimento em um órgão público através do aplicativo gov.br. |
| **Contexto**    | O cidadão está em casa e precisa agendar um atendimento presencial para resolver um problema com seu CPF. O cidadão já possui uma conta no gov.br e está conectado à internet. O órgão público desejado oferece agendamento online através do gov.br. |
| **Recursos**    | Smartphone com o aplicativo gov.br instalado. Conexão com a internet.                          |
| **Ator**        | Cidadão                                                                                         |
| **Episódios**   | -O cidadão abre o aplicativo gov.br e faz login com seu CPF e senha. <br>-Na tela inicial, o cidadão seleciona a opção "Agendar Atendimento". <br>-O cidadão digita o nome do órgão público que deseja agendar o atendimento. <br>-O aplicativo apresenta uma lista de serviços disponíveis para agendamento no órgão público selecionado. <br>-O cidadão seleciona o serviço desejado e informa a data e horário preferidos para o atendimento. <br>-O aplicativo verifica a disponibilidade de horários para o serviço e data selecionados. <br>-Se houver horários disponíveis, o cidadão escolhe o horário desejado e confirma o agendamento. <br>-O aplicativo exibe uma mensagem de confirmação com o número do protocolo do agendamento, data, horário, local do atendimento e documentos necessários. <br>-O cidadão pode salvar a confirmação do agendamento em seu smartphone ou imprimi-la. |
| **Restrições**  | - O cidadão só pode agendar atendimentos para serviços que estejam disponíveis para agendamento online. - O cidadão não pode agendar atendimentos para datas e horários indisponíveis. - O cidadão precisa apresentar o número do protocolo do agendamento no dia do atendimento. |
| **Exceção**     | - Se o serviço desejado não estiver disponível para agendamento online, o aplicativo exibirá uma mensagem informando ao cidadão que o agendamento deve ser feito presencialmente. - Se o cidadão tentar agendar um atendimento para uma data e horário indisponíveis, o aplicativo exibirá uma mensagem informando que o horário escolhido não está disponível e sugerirá outros horários. |
<br>

<p style="text-align: center">Fonte: <a href=""></a></p>

### Cenário 2: Busca Intuitiva de Processos e Documentos - gov.br

<p style="text-align: center">Tabela 3 - Cenário 02</p>

| Elemento     | Descrição                                                                                                           |
| ------------ |----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Objetivo**     | Descrever o processo de um cidadão buscar processos e documentos de forma intuitiva no aplicativo gov.br, utilizando recursos de pesquisa avançada e personalização. |
| Contexto     | O cidadão está em casa e precisa consultar o andamento de um processo que ele já deu entrada ou baixar um documento relacionado a um serviço público. O cidadão já possui uma conta no gov.br e está conectado à internet. |
| **Recursos**     | Smartphone com o aplicativo gov.br instalado. Conexão com a internet.                                                                                        |
| **Ator**         | Cidadão                                                                                                                                                     |
| **Episódios**    | -O usuário abre o aplicativo gov.br e faz login com seu CPF e senha. <br>Na tela inicial do aplicativo, o usuário localiza e toca no botão "Buscar Processos e Documentos". <br>Na tela de busca, o cidadão escolhe entre as opções de pesquisa disponíveis, como número do protocolo, CPF/CNPJ, assunto, palavras-chave, órgão responsável, data, filtros adicionais e pesquisa por voz.<br>O usuário pode acessar seu histórico de buscas para facilitar consultas recorrentes.<br>O usuário pode combinar diferentes métodos de busca e utilizar operadores lógicos para refinar os resultados da pesquisa.<br>O usuário inicia a pesquisa tocando no botão "Buscar". <br>O aplicativo apresenta uma lista de resultados relevantes ordenados por critérios como data de atualização, relevância ou status do processo.<br>O usuário seleciona um resultado da lista para visualizar detalhes.<br>O aplicativo exibe uma tela com informações completas sobre o processo ou documento escolhido, incluindo histórico do processo, documentos disponíveis e informações de contato do órgão responsável.<br>O usuário pode salvar suas preferências de busca para uma experiência mais personalizada. |
| **Restrições**  | - O cidadão deve estar conectado à internet para utilizar o aplicativo gov.br.<br>- Os processos e documentos disponíveis para consulta devem estar dentro do escopo do sistema gov.br.<br>- A utilização de filtros e operadores lógicos está sujeita à disponibilidade de recursos no aplicativo.<br>- A precisão e relevância dos resultados da pesquisa podem variar dependendo da qualidade dos dados e da eficácia dos algoritmos de busca. |
| **Exceção**     | - Se houver falha na autenticação do usuário, o aplicativo deve exibir uma mensagem de erro e oferecer opções de recuperação de conta.<br>- Se ocorrer um erro durante a busca, o aplicativo deve apresentar uma mensagem de falha na pesquisa e sugerir tentar novamente mais tarde.<br>- Se os resultados da pesquisa forem inconsistentes ou incompletos, o aplicativo deve oferecer opções de feedback para que o usuário possa reportar o problema. |
<br>

<p style="text-align: center">Fonte: <a href=""></a></p>

### Cenário 3: Eficiência no Agendamento e Acompanhamento de Processos - gov.br

<p style="text-align: center">Tabela 4 - Cenário 03</p>

| Elemento      | Descrição                                                                                           |
| --------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Objetivo**              | Descrever o processo de um cidadão agendar e acompanhar processos de forma eficiente e transparente através do aplicativo gov.br.                                            |
| **Contexto**             | O cidadão precisa dar entrada em um novo processo ou consultar o andamento de um processo em andamento. O cidadão já possui uma conta no gov.br e está conectado à internet. |
| **Recursos**              | Smartphone com o aplicativo gov.br instalado. Conexão com a internet.                                                                                                        |
| **Ator**                  | Cidadão            |
| **Episódios**             | -O cidadão abre o aplicativo gov.br e faz login com seu CPF e senha.<br>-Na tela inicial do aplicativo, o cidadão localiza e toca no botão "Agendar Processos".<br>-Na tela de agendamento, o cidadão escolhe entre as opções de iniciar um novo processo ou consultar um processo em andamento.<br>-O cidadão preenche o formulário de agendamento com as informações necessárias para iniciar o processo, como dados pessoais, documentos comprobatórios e detalhes do serviço solicitado.<br>-O aplicativo verifica se as informações inseridas pelo cidadão estão corretas e completas.<br>-O cidadão revisa as informações inseridas e confirma o agendamento do processo.<br>-O cidadão acessa a tela de acompanhamento de processos para verificar o status de seu processo em andamento.<br>-O cidadão seleciona um processo específico na lista de acompanhamento e visualiza seu histórico de eventos.<br>-O cidadão configura suas preferências de notificação para receber alertas sobre o andamento do processo. |
| **Restrições**           | - O cidadão deve estar conectado à internet para utilizar o aplicativo gov.br.<br>- Os processos disponíveis para agendamento e acompanhamento devem estar dentro do escopo do sistema gov.br.<br>- A precisão e atualização das informações sobre o andamento do processo dependem da disponibilidade de dados fornecidos pelo órgão responsável.<br>- A disponibilidade de notificações está sujeita à configuração e autorização do usuário.          |
| **Exceção**              | - Se houver falha na autenticação do usuário, o aplicativo deve exibir uma mensagem de erro e oferecer opções de recuperação de conta.<br>- Se ocorrer um erro durante o agendamento do processo, o aplicativo deve apresentar uma mensagem de falha e permitir ao usuário tentar novamente.<br>- Se o processo não puder ser acompanhado devido a problemas técnicos ou de integração com sistemas externos, o aplicativo deve informar ao usuário sobre a indisponibilidade temporária do serviço.                                                                                                                                                          |
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

### Cenário 5: Segurança na Transmissão e Armazenamento de Documentos Sensíveis - gov.br

<p style="text-align: center">Tabela 6 - Cenário 05</p>

| Elemento                                 | Descrição          |
| ---------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Objetivo**                                 | Descrever os mecanismos de segurança utilizados pelo aplicativo gov.br para garantir a confidencialidade, integridade e disponibilidade de documentos sensíveis durante a transmissão e armazenamento.    |
| **Contexto**                                 | O cidadão precisa transmitir e armazenar documentos sensíveis, como certidões de nascimento e casamento, comprovantes de renda e declarações fiscais, através do aplicativo gov.br. O cidadão tem a expectativa de que seus documentos sejam protegidos contra acesso não autorizado, perda ou roubo.           |
| **Recursos**                                 | Smartphone com o aplicativo gov.br instalado. Conexão com a internet segura.    |
| **Ator**                                     | Cidadão        |
| **Episódios**                               |  -O aplicativo gov.br criptografa todos os dados transmitidos entre o dispositivo do cidadão e os servidores do governo, utilizando protocolos de criptografia robustos como TLS 1.3 e AES 256.<br>-Os documentos sensíveis do cidadão são armazenados em servidores do governo com alto nível de segurança, protegidos por firewalls, mecanismos de autenticação multifator e outras medidas de segurança física e lógica.<br>-O aplicativo gov.br permite que o cidadão defina permissões de acesso granular para seus documentos sensíveis, controlando quem pode visualizar, baixar ou compartilhar os documentos.<br>-O aplicativo gov.br registra todas as atividades relacionadas aos documentos sensíveis, incluindo quem acessou, quando e de qual dispositivo.<br>-O aplicativo gov.br notifica o cidadão em caso de atividades suspeitas relacionadas aos seus documentos sensíveis, como logins de dispositivos desconhecidos ou tentativas de acesso não autorizadas.<br>-O aplicativo gov.br recebe atualizações frequentes de segurança para corrigir vulnerabilidades e proteger contra novas ameaças cibernéticas. <br>-O governo disponibiliza informações claras e transparentes sobre as práticas de segurança utilizadas para proteger os documentos sensíveis dos cidadãos no aplicativo gov.br. |
| **Restrições**                              | - O acesso aos documentos sensíveis está sujeito à autenticação do cidadão e às políticas de privacidade do governo.<br>- A transmissão segura dos dados depende de uma conexão com a internet segura por parte do cidadão.<br>- O armazenamento seguro dos documentos depende da implementação de medidas de segurança pelos servidores do governo.                                                                                                                                 |
| **Exceção**                                 | - Se ocorrer uma falha na transmissão dos dados criptografados, o aplicativo deve exibir uma mensagem de erro e orientar o cidadão sobre as medidas a serem tomadas.<br>- Se houver uma violação de segurança nos servidores do governo, o aplicativo deve notificar imediatamente o cidadão sobre o incidente e as medidas de proteção adotadas.                                                                               |
<br>

<p style="text-align: center">Fonte: <a href=""></a></p>

### Cenário 6: Garantia da Privacidade das Informações Pessoais - gov.br

<p style="text-align: center">Tabela 7 - Cenário 06</p>

| Elemento                                     | Descrição                                                                                                                                                                                                                         |
| -------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Objetivo**                                     | Descrever as medidas implementadas pelo aplicativo gov.br para garantir a privacidade das informações pessoais dos cidadãos, de acordo com a Lei Geral de Proteção de Dados Pessoais (LGPD).                                         |
| **Contexto**                                     | O cidadão utiliza o aplicativo gov.br para acessar diversos serviços públicos e fornecer informações pessoais, como nome, endereço, CPF, RG e dados bancários. O cidadão tem o direito de saber como seus dados são coletados, utilizados e armazenados, e de controlar o compartilhamento de suas informações.                                       |
| **Recursos**                                     | Smartphone com o aplicativo gov.br instalado. Conexão com a internet.                                                                                                                                                            |
| **Ator**                                         | Cidadão                                                                                                                                                                                                                           |
| **Episódios**                                   | -O aplicativo gov.br coleta apenas os dados pessoais que são estritamente necessários para a prestação dos serviços solicitados pelo cidadão.<br>-Os dados pessoais coletados pelo aplicativo gov.br são armazenados em servidores seguros com alto nível de proteção, de acordo com as melhores práticas de segurança da informação.<br>-O aplicativo gov.br só compartilha os dados pessoais do cidadão com outros órgãos públicos ou entidades privadas quando estritamente necessário para a prestação do serviço solicitado, mediante o consentimento expresso do cidadão.<br>-O cidadão pode solicitar, a qualquer momento, o acesso, a retificação ou a exclusão de seus dados pessoais armazenados no aplicativo gov.br.<br>-O aplicativo gov.br implementa medidas de segurança para proteger os dados pessoais do cidadão contra fraudes, acessos não autorizados e uso indevido.<br>-O aplicativo gov.br disponibiliza um canal de comunicação para que o cidadão possa tirar dúvidas, apresentar reclamações ou exercer seus direitos relacionados à proteção de dados pessoais.<br>-O governo disponibiliza informações sobre suas políticas de privacidade, explicando como os dados pessoais dos cidadãos são coletados, utilizados e armazenados.                                                                                                                                                                                                                   |
| **Restrições**                                  | - A eficácia das medidas de proteção de dados depende da conformidade com as disposições da Lei Geral de Proteção de Dados Pessoais (LGPD) e outras regulamentações aplicáveis.<br>- A disponibilidade dos serviços pode estar sujeita à coleta de dados necessários para a prestação dos mesmos, conforme exigido por lei ou regulamentação.<br>- O compartilhamento de dados pessoais pode ser necessário em certas circunstâncias, como cumprimento de obrigações legais ou execução de contratos.<br>- O acesso, a retificação e a exclusão de dados pessoais podem estar sujeitos a requisitos legais ou regulatórios, limitações técnicas ou períodos de retenção de dados.                                |
| **Exceção**                                     | - Se ocorrer uma violação de dados pessoais, o aplicativo gov.br deve notificar imediatamente o cidadão afetado e as autoridades competentes, conforme exigido pela LGPD e outras regulamentações aplicáveis.<br>- Se um cidadão não puder acessar, retificar ou excluir seus dados pessoais devido a problemas técnicos ou de sistema, o aplicativo gov.br deve fornecer um mecanismo alternativo para que o cidadão exerça seus direitos de privacidade.                                                                                                                                                                                                                                 |
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