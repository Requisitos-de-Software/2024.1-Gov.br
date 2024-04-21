# MoSCoW

## Introdução

O método MoSCoW é uma técnica de priorização que categoriza os requisitos em quatro tipos de prioridade, ela define a importância de cada tarefa, se deve ser feita ou não.

## Metodologia

O termo MoSCoW é um acrônimo derivado do inglês, onde cada letra maiúscula representa uma das categorias de priorização:

- **Must(Deve ter)**: Representa o maior nível de prioridade. São itens críticos que, se não concluídos, o projeto não se pode ser considerado um sucesso.
- **Should(Deveria ter)**: Representa um nível de prioridade importante, mas não são itens necessários para a entrega nesse momento, ou seja, podem esperar a finalização de itens mais prioritários primeiro.
- **Could(Poderia ter)**: Representa um nível de prioridade menor, ou seja, são desejáveis mas não são necessários. Eles são implementados caso haja a disponiblidade de tempo e de recursos.
- **Won't(Não terá)**: Representa um nível de prioridade menos cŕitico possível, com um menor retorno sobre o investimento ou não tão adequados para serem realizados.

Para a atividade de priorização MoSCoW foi realizada um entrevista com um usuário, onde foram apresentados todos os requisitos já elicitados, e a partir disso cada requisito recebeu seu nível de prioridade de acordo com o usuário entrevistado.

## Resultados

### Legenda 

- **ST** - Storytelling
- **ADFU** - Análise de documentos(feedback usuários)
- **ADTU** - Análise de documentos(Termos de uso)
- **BS** - Brainstorm
- **RF** - Requisitos Funcionais
- **RNF** - Requisitos não Funcionais

<center>

**Tabela 1** - Priorização MoSCoW

</center>

| ID     | Descrição                                                                                                                                                                              | Tipo | Prioridade |
| ------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---- | ---------- |
| ST01   | Como usuário, desejo acessar o aplicativo gov.br de forma rápida e intuitiva.                                                                                                          | RF   | Must       |
| ST02   | Como usuário, desejo encontrar facilmente o serviço de agendamento na Receita Federal.                                                                                                 | RF   | Should     |
| ST03   | Como usuário, desejo acessar as funções de assinatura digital para agilizar a assinatura de documentos.                                                                                | RF   | Should     |
| ST04   | Como usuário, desejo agendar atendimentos em órgãos públicos através do aplicativo.                                                                                                    | RF   | Must       |
| ST05   | Como usuário, desejo consultar informações sobre benefícios sociais através do aplicativo.                                                                                             | RF   | Should     |
| ST06   | Como usuário, desejo acessar a função de carteira digital no aplicativo.                                                                                                               | RF   | Should     |
| ST07   | Como usuário, desejo continuar recebendo minha aposentadoria através da função de prova de vida.                                                                                       | RF   | Must       |
| ST08   | Como usuário, desejo uma navegação intuitiva para buscar processos e documentos.                                                                                                       | RF   | Must       |
| ST09   | Como usuário, desejo garantir a segurança na transmissão e armazenamento de documentos sensíveis.                                                                                      | RF   | Must       |
| ST10   | Como usuário, desejo eficiência no agendamento e acompanhamento de processos.                                                                                                          | RF   | Must       |
| ST11   | Como usuário, desejo receber atualizações relevantes sobre processos e benefícios sociais.                                                                                             | RF   | Should     |
| ST12   | Como usuário, desejo substituir minha carteira física por uma versão digital no aplicativo.                                                                                            | RF   | Should     |
| ST13   | Como usuário, desejo acesso rápido aos meus documentos no celular, sem a necessidade de documentos físicos.                                                                            | RF   | Must       |
| ST14   | Como usuário, desejo poder acessar meus documentos mesmo sem conexão com a internet.                                                                                                   | RF   | Must       |
| ST15   | Como usuário, desejo garantir a privacidade das informações pessoais.                                                                                                                  | RF   | Must       |
| ST16   | Segurança: O aplicativo deve garantir a segurança dos dados pessoais dos usuários.                                                                                                     | RNF  | Must       |
| ST17   | Usabilidade: A interface do aplicativo deve ser simples e fácil de usar.                                                                                                               | RNF  | Must       |
| ST18   | Eficiência: O aplicativo deve ser rápido no acesso e no agendamento de serviços.                                                                                                       | RNF  | Must       |
| ST19   | Acessibilidade: O aplicativo deve ser acessível mesmo sem conexão com a internet.                                                                                                      | RNF  | Must       |
| ST20   | Confiabilidade: O aplicativo deve manter a integridade dos documentos e informações consultadas.                                                                                       | RNF  | Must       |
| ST21   | Atualização: O aplicativo deve manter os usuários informados sobre novidades e atualizações importantes.                                                                               | RNF  | Must       |
| ST22   | Privacidade: Garantir que as informações dos usuários não sejam compartilhadas sem permissão.                                                                                          | RNF  | Must       |
| ADFU01 | O sistema deve possuir uma funcionalidade de reconhecimento facial para autenticação do usuário.                                                                                       | RF   | Could      |
| ADFU02 | O sistema deve permitir que os usuários recuperem suas senhas através de métodos seguros e eficientes.                                                                                 | RF   | Must       |
| ADFU03 | O sistema deve oferecer verificação em duas etapas como uma camada adicional de segurança para os usuários.                                                                            | RF   | Must       |
| ADFU04 | O sistema deve permitir que os usuários utilizem suas credenciais para acessar diferentes serviços governamentais de forma centralizada.                                               | RF   | Could      |
| ADFU05 | O sistema deve facilitar o processo de mudança de celular pelo usuário, permitindo a transferência de segurança e autenticações sem necessidade de cancelar e recriar a conta.         | RF   | Must       |
| ADFU06 | O sistema deve notificar os usuários de quaisquer acessos não autorizados ou mudanças críticas na segurança de suas contas.                                                            | RF   | Must       |
| ADFU07 | O sistema deve ser estável e confiável, funcionando corretamente sem travamentos ou fechamentos inesperados.                                                                           | RNF  | Must       |
| ADFU08 | A interface do sistema deve ser clara e fácil de usar, evitando complexidades desnecessárias que possam confundir os usuários.                                                         | RNF  | Must       |
| ADFU09 | As funcionalidades críticas, como reconhecimento facial e autenticação, devem ser otimizadas para operar de maneira rápida e eficiente.                                                | RNF  | Must       |
| ADTU01 | O sistema deve permitir a autenticação do usuário utilizando métodos como biometria facial e validação biográfica.                                                                     | RF   | Could      |
| ADTU02 | O sistema deve permitir ao usuário acessar, atualizar e excluir seus dados pessoais.                                                                                                   | RF   | Could      |
| ADTU03 | O sistema deve oferecer funcionalidades para recuperação de conta através de SMS, e-mail ou suporte direto.                                                                            | RF   | Could      |
| ADTU04 | O sistema deve permitir aos usuários visualizar e gerenciar documentos digitais associados à sua conta.                                                                                | RF   | Must       |
| ADTU05 | O sistema deve oferecer uma funcionalidade de Prova de Vida para verificação de beneficiários de programas de previdência ou assistência social.                                       | RF   | Could      |
| ADTU06 | O sistema deve assegurar o tratamento adequado dos dados sensíveis de acordo com a legislação (LGPD).                                                                                  | RNF  | Must       |
| ADTU07 | O sistema deve obter consentimento explícito dos usuários para o tratamento de seus dados pessoais.                                                                                    | RNF  | Must       |
| ADTU08 | O sistema deve ser acessível através de diferentes dispositivos e navegadores.                                                                                                         | RNF  | Must       |
| ADTU09 | O sistema deve implementar múltiplos níveis de segurança de acesso (bronze, prata, ouro).                                                                                              | RNF  | Should     |
| ADTU10 | O sistema deve ser acessível e disponível para todos os usuários, garantindo acessibilidade para usuários com deficiências e oferecendo suporte a múltiplas plataformas e navegadores. | RNF  | Must       |
| BS01   | O aplicativo deve permitir que os usuários se autentiquem de forma segura, usando credenciais únicas, como CPF e senha.                                                                | RF   | Must       |
| BS02   | O usuário deve ser capaz de logar com as credências do gov.br.                                                                                                                         | RF   | Must       |
| BS03   | O usuário deve conseguir visualizar seus documentos.                                                                                                                                   | RF   | Must       |
| BS04   | O usuário deve conseguir agendar serviços específicos.                                                                                                                                 | RF   | Must       |
| BS05   | O usuário deve conseguir emitir/baixar certidões.                                                                                                                                      | RF   | Could      |
| BS08   | O usuário deve conseguir se logar no aplicativo.                                                                                                                                       | RF   | Must       |
| BS09   | O login deve possuir autenticação em dois fatores.                                                                                                                                     | RF   | Must       |
| BS10   | O usuário deve conseguir assinar documentos digitalmente.                                                                                                                              | RF   | Should     |
| BS11   | O usuário deve conseguir se inscrever em concursos públicos.                                                                                                                           | RF   | Could      |
| BS12   | O usuário deve conseguir consultar programas do governo.                                                                                                                               | RF   | Should     |
| BS13   | O usuário deve conseguir se conectar com o Detran.                                                                                                                                     | RF   | Should     |
| BS14   | O usuário deve conseguir se conectar com o NIS.                                                                                                                                        | RF   | Should     |
| BS15   | O usuário deve conseguir se conectar com o ID Jovem.                                                                                                                                   | RF   | Should     |
| BS16   | O usuário deve conseguir usar o aplicativo para pagar impostos trabalhistas.                                                                                                           | RF   | Should     |
| BS17   | O usuário deve conseguir obter o código de acesso.                                                                                                                                     | RF   | Should     |
| BS18   | O aplicativo deve possuir ferramentas de acessibilidade (Alto contraste, aumentar a fonte, audiodescrição).                                                                            | RF   | Must       |
| BS19   | O aplicativo deve ser seguro e confiável, protegendo os dados dos usuários.                                                                                                            | RNF  | Must       |
| BS20   | O login deve ser feito de maneira rápida e segura.                                                                                                                                     | RNF  | Must       |
| BS21   | O aplicativo deve ser acessível a pessoas com deficiência.                                                                                                                             | RNF  | Must       |
| BS22   | O aplicativo deve exigir que a senha do usuário possua obrigatoriamente letras, números e caracteres especiais.                                                                        | RNF  | Must       |
| BS23   | O aplicativo deve ser intuitivo e fácil de usar.                                                                                                                                       | RNF  | Must       |
| BS24   | O aplicativo deve ter boa performance e ser estável.                                                                                                                                   | RNF  | Must       |
| BS25   | O aplicativo deve ter suporte ao cliente eficiente.                                                                                                                                    | RNF  | Must       |


<div align="center">
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/IsaqueSH">Isaque Santos</a>, 2024</p></font>
</div>


## Reunião

No dia 21/04/2024, às 10:30, foi conduzida uma reunião com a presença do usuário Pablo, bem como dos membros do grupo [Arthur Gabriel](https://github.com/ArthurGabrieel) e [Isaque Santos](https://github.com/IsaqueSH). Durante o encontro, o usuário Pablo consentiu com os termos de utilização de sua imagem e dados. Na ocasião, foram apresentados todos os requisitos previamente identificados, e cada um recebeu uma classificação de prioridade com base nas informações fornecidas pelo usuário entrevistado. Segue abaixo link para a gravação da reunião:

- [Gravação da Reunião](https://youtu.be/9w48BD_Sl0M)

## Bibliografia

- SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 07: Elicitação, Modelagem e Análise. Apresentação Power Point. Disponível em: https://aprender3.unb.br/pluginfile.php/2692779/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf. Acesso em: 17 de abril de 2024.
- SALES, André Barros. Técnicas de Priorização. Disponível em: https://aprender3.unb.br/course/view.php?id=22688&section=5. Acesso em 17 de abril de 2024.

## Histórico de Versão

| Versão |    Data    |                      Descrição                      |      Autor(es)      | Revisor(es)  |
| :----: | :--------: | :-------------------------------------------------: | :-----------------: | :----------: |
|  1.0   | 20/04/2024 | Versão Inicial | [Arthur Gabriel](https://github.com/ArthurGabrieel), [Isaque Santos](https://github.com/IsaqueSH) | [Ester Lino](https://github.com/esteerlino) |
|  1.1   | 21/04/2024 | Adicionando priorização e link reunião | [Arthur Gabriel](https://github.com/ArthurGabrieel), [Isaque Santos](https://github.com/IsaqueSH) | [Ester Lino](https://github.com/esteerlino) |