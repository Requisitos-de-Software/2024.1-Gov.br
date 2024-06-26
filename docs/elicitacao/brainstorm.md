# Brainstorm

## Introdução

O Brainstorm é uma técnica de elicitação que possui uma abordagem mais colaborativa e que envolve os stakeholders de um projeto. Durante a sessão de brainstorm os participantes são incentivados a emitir opiniões e ideias sobre as perguntas feitas pelo mediador de maneira livre e sem críticas ou julgamentos. Essa técnica tem como objetivo identificar requisitos e funcionalidades do projeto.

## Metodologia

O brainstorming foi realizado no dia 16/04/2024, com horário de incío às 14h e o horário de fim às 14:30h. A sessão contou com a participação de 9 usuários do aplicativo Gov.br, com um mediador [Arthur Gabriel](https://github.com/ArthurGabrieel) e uma secretária [Ester Lino](https://github.com/esteerlino). Inicialmente ocorreu uma breve introdução sobre o brainstorm, explicando como funcionaria e quais as recomendações. Em seguida, foi o mediador realizou as 7 perguntas, uma a uma, que guiaram o brainstorm. A cada pergunta os mediadores solicitavam que cada participante informasse suas respostas, ideias e opiniões e quando necessário ocorriam discussões sobre as respostas obtidas.

## Participantes

<font size="3"><b>Tabela 1:</b> - Requisitos Funcionais</font>

|        Nome       |   Função   |
|:-----------------:| :--------: |
| Arthur Gabriel    | Mediador   |
| Ester Lino        | Secretária |
| Bárbara Beatriz   | Usuário    |
| Beatriz Lins      | Usuário    |
| Gabriel Santos    | Usuário    |
| Izabelle Rivas    | Usuário    |
| Jefferson Sena    | Usuário    |
| José Rocha        | Usuário    |
| Oscar de Brito    | Usuário    |
| Pedro Cabeceira   | Usuário    |
| Tiago Albuquerque | Usuário    |

<font size="3"><b>Fonte:</b> <a href="https://github.com/esteerlino">Ester Lino</a>, 2024</font>

## Perguntas e Respostas

1. Quais são as principais funcionalidades que os usuários esperam do aplicativo Gov.br?
    - Acessar documentos<br>
    - Consultar serviços<br>
    - Baixar certidões<br>
    - Se inscrever em concursos públicos<br>
    - Consultar programas do governo<br>
    - Conectar com o Detran<br>
    - Pagar impostos trabalhistas<br>
2. Quais problemas ou desafios os usuários enfrentam ao acessar os serviços do governo online?
    - Falta de clareza nos processos<br>
    - Lentidão<br>
    - Sistema instável<br>
    - Experiência de usuário ruim<br>
    - Dificuldade para fazer autenticação<br>
    - Necessidade de acessos múltiplos com logins separados<br>
    - Falta de automatização nos serviços online
3. Quais informações e serviços específicos os usuários desejam acessar através do aplicativo Gov.br?
    - Acessar a carteira de documentos<br>
    - Logar em outros sistemas do governo<br>
    - Assinar documentos digitalmente<br>
    - Emitir prova de vida<br>
    - Acessar informações pessoais<br>
    - Emitir certidões<br>
    - Pegar código de acesso
4. Quais recursos de segurança e privacidade são essenciais para proteger os dados dos usuários no aplicativo Gov.br?
    - Autenticação por biometria<br>
    - Criptografia dos dados<br>
    - Autenticação em dois fatores<br>
    - Reconhecimento facial na base da Justiça Eleitoral<br>
    - Autenticação por QR Code<br>
    - Gerenciar dispositivos confiáveis<br>
    - Aumentar nível da conta
5. Como podemos garantir que o aplicativo Gov.br seja acessível para pessoas com deficiência?
    - Descrição de áudio<br>
    - Autocontraste<br>
    - Aumentar/diminuir tipografia<br>
    - Atendimento especializado
6. Quais são as características de usabilidade mais importantes para tornar o aplicativo Gov.br intuitivo e fácil de usar?
    - Boa documentação de ajuda<br>
    - Evitar menus de navegação não intuitivos<br>
    - Evitar o uso de termos técnicos para usuários leigos<br>
    - Interface limpa e objetiva<br>
    - Existência de um canal FAQ
    - Chat bot
7. Quais são algumas melhorias que você acredita que influenciaria positivamente a experiência do usuário?
    - Tema escuro<br>
    - Possibilidade de acompanhar o andamento dos processos<br>
    - Centralizar todos os serviços em um único aplicativo<br>
    - Aba de ajuda<br>
    - Melhorar estabilidade do aplicativo<br>
    - Audiodescrição

Na elicitação de requisitos para o aplicativo Gov.br, utilizaremos abreviações para classificar e organizar os requisitos de maneira clara e estruturada. Dois desses códigos frequentemente usados são RF (Requisitos Funcionais) e RNF (Requisitos Não Funcionais). Além disso, cada requisito elicitado terá um ID.

**RF (Requisitos Funcionais):** Representam funcionalidades específicas que o aplicativo deve oferecer, descrevendo as ações que o sistema deve executar em resposta a entradas.

**RNF (Requisitos Não Funcionais):** Englobam aspectos que não estão diretamente relacionados às funcionalidades específicas do aplicativo, mas afetam sua eficiência, usabilidade, segurança e outros atributos.

**ID:** Cada requisito será identificado por um ID composto da seguinte forma: INTXX (onde XX é um número sequencial). Por exemplo, o primeiro requisito funcional seria INT01 e assim por diante.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 1:</b> - Requisitos Funcionais</p></font>
</div>

| ID   | Código | Descrição                                                                                                              | Implementado |
| ---- | ------ | ---------------------------------------------------------------------------------------------------------------------- | ------------ |
| BS01 | RF     | O aplicativo deve permitir que os usuários se autentiquem de forma segura, usando credenciais únicas, como CPF e senha | Sim          |
| BS02 | RF     | O usuário deve ser capaz de logar com as credências do gov.br                                                          | Sim          |
| BS03 | RF     | O usuário deve conseguir visualizar seus documentos                                                                    | Sim          |
| BS04 | RF     | O usuário deve conseguir agendar serviços específicos                                                                  | Não          |
| BS05 | RF     | O usuário deve conseguir emitir/baixar certidões                                                                       | Sim          |
| BS06 | RF     | O usuário deve conseguir se logar no aplicativo                                                                        | Sim          |
| BS07 | RF     | O login deve possuir autenticação em dois fatores                                                                      | Sim          |
| BS08 | RF     | O usuário deve conseguir assinar documentos digitalmente                                                               | Sim          |
| BS09 | RF     | O usuário deve conseguir se inscrever em concursos públicos                                                            | Não          |
| BS10 | RF     | O usuário deve conseguir consultar programas do governo                                                                | Não          |
| BS11 | RF     | O usuário deve conseguir se conectar com o Detran                                                                      | Não          |
| BS12 | RF     | O usuário deve conseguir se conectar com o NIS                                                                         | Não          |
| BS13 | RF     | O usuário deve conseguir se conectar com o ID Jovem                                                                    | Não          |
| BS14 | RF     | O usuário deve conseguir usar o aplicativo para pagar impostos trabalhistas                                            | Não          |
| BS15 | RF     | O usuário deve conseguir obter o código de acesso                                                                      | Sim          |
| BS16 | RF     | O aplicativo deve possuir ferramentas de acessibilidade (Alto contraste, aumentar a fonte, audiodescrição)             | Não          |

<div align="center">
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/ArthurGabrieel">Arthur Gabriel</a>, 2024</p></font>
</div>

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 2:</b> - Requisitos Não Funcionais</p></font>
</div>

| ID   | Código | Descrição                                                                                                       | Implementado |
| ---- | ------ | --------------------------------------------------------------------------------------------------------------- | ------------ |
| BS17 | RNF    | O aplicativo deve ser seguro e confiável, protegendo os dados dos usuários                                      | Sim          |
| BS18 | RNF    | O login deve ser feito de maneira rápida e segura                                                               | Não          |
| BS19 | RNF    | O aplicativo deve ser acessível a pessoas com deficiência                                                       | Não          |
| BS20 | RNF    | O aplicativo deve exigir que a senha do usuário possua obrigatoriamente letras, números e caracteres especiais. | Não          |
| BS21 | RNF    | O aplicativo deve ser intuitivo e fácil de usar                                                                 | Não          |
| BS22 | RNF    | O aplicativo deve ter boa performance e ser estável                                                             | Não          |
| BS23 | RNF    | O aplicativo deve ter suporte ao cliente eficiente                                                              | Não          |

<div align="center">
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/ArthurGabrieel">Arthur Gabriel</a>, 2024</p></font>
</div>

## Gravação do Brainstorm

<iframe width="560" height="315" src="https://www.youtube.com/embed/An-JA1qNe88?si=GcIhPutoWT8cVs0z" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Bibliografia

- SERRANO, Milene, SERRANO, Maurício. Requisitos (Aula 07): Elicitação, Modelagem e Análise. **UnB Gama**, Brasília, 2023. Disponível em: <<https://aprender3.unb.br/pluginfile.php/2580553/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf>>. Acesso em: 14/04/2024.

## Histórico de versão

| Versão | Data | Descrição | Responsáveis | Revisor |
| :----: | :--: | :-----------------------------------------------------: | :----------------------------------------------------------------------------------------------: | :----------------------------------------------: |
|  1.0   | 15/04/2024 | Criação da página  | [Arthur Gabriel](https://github.com/ArthurGabrieel), [Ester Lino](https://github.com/esteerlino) | [Thiago Ribeiro](https://github.com/thiagorfreitas) |
|  1.1   | 16/04/2024 | Adicionando tabelas de requisitos  | [Arthur Gabriel](https://github.com/ArthurGabrieel), [Ester Lino](https://github.com/esteerlino) | [Thiago Ribeiro](https://github.com/thiagorfreitas) |
|  1.2   | 17/04/2024 | Atualizando as informações da página  | [Arthur Gabriel](https://github.com/ArthurGabrieel), [Ester Lino](https://github.com/esteerlino) | [Thiago Ribeiro](https://github.com/thiagorfreitas) |
|  1.3   | 21/04/2024 | Inclusão da gravação do Brainstorm  | [Arthur Gabriel](https://github.com/ArthurGabrieel), [Ester Lino](https://github.com/esteerlino) | [Thiago Ribeiro](https://github.com/thiagorfreitas) |
