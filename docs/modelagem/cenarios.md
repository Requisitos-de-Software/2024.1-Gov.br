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

| Elemento     | Descrição                                                                                       | Ligação com Léxicos                                                                                                                 |
|--------------|-------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| Objetivo     | Consultar CPF no aplicativo Gov.br                                                              | [Gov.br](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#govbr), [CPF](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#cpf)                                                                                          |
| Contexto     | Cidadão em casa, acessando o aplicativo em seu smartphone                                        | [Cidadão](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#cidadão), [Smartphone](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#smartphone), [Aplicativo](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#aplicativo)                                             |
| Recursos     | Smartphone com o aplicativo Gov.br instalado. Conexão com a internet                             | [Smartphone](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#smartphone), [Aplicativo Gov.br](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#aplicativo-govbr), [Internet](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#internet)                              |
| Ator         | Cidadão                                                                                         | [Cidadão](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#cidadão)                                                                                                    |
| Episódios    | Acessa "Serviços", busca "Consulta de CPF", digita CPF e data de nascimento, confirma ação, obtém dados | [Serviços](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#serviços), [Consulta de CPF](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#consulta-de-cpf), [CPF](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#cpf), [Data de nascimento](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#data-de-nascimento)     |
| Restrições   | Acesso à internet, smartphone com aplicativo instalado, CPF válido                               | [Internet](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#internet), [Aplicativo Gov.br](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#aplicativo-govbr), [CPF](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#cpf)                                             |
| Exceções     | CPF inválido, falhas de conexão                                                                  | [CPF](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#cpf), [Falhas de conexão](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#falhas-de-conexão)    
<br>
<p style="text-align: center">Fonte: <a href="https://github.com/TheCarlosRamos">Carlos Gabriel</a></p>

### Cenário 2:  Simulação de Aposentadoria - gov.br

<font><p style="text-align: center">**Tabela 3** - Cenário 02</p></font>

| Elemento     | Descrição                                                                                       | Ligação com Léxicos                                                                                                                 |
|--------------|-------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| Objetivo     | Simular aposentadoria no aplicativo Gov.br                                                      | [Aposentadoria](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#aposentadoria), [Gov.br](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#govbr)                                                                     |
| Contexto     | Cidadão em casa, curioso sobre aposentadoria                                                    | [Cidadão](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#cidadão), [Aposentadoria](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#aposentadoria)                                                                  |
| Recursos     | Aplicativo Gov.br, conta Gov.br, dados do INSS                                                  | [Aplicativo Gov.br](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#aplicativo-govbr), [Conta Gov.br](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#conta-govbr), [INSS](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#inss)                                    |
| Ator         | Cidadão                                                                                         | [Cidadão](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#cidadão)                                                                                                    |
| Episódios    | Abre o aplicativo, faz login, pesquisa "Aposentadoria", ajusta dados, recalcula                 | [Aplicativo Gov.br](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#aplicativo-govbr), [Login](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#login), [Aposentadoria](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#aposentadoria)                              |
| Restrições   | Simulação em desenvolvimento, necessidade de acesso à internet                                  | [Simulação](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#simulação), [Internet](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#internet)                                                                        |
| Exceções     | Dados cadastrais desatualizados, alterações na legislação previdenciária                        | [Dados cadastrais](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#dados-cadastrais), [Legislação previdenciária](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#legislação-previdenciária)                        |
<br>

<p style="text-align: center">Fonte: <a href="https://github.com/ArthurGabrieel">Arthur Gabriel</a></p>

### Cenário 3: Redefinição de Senha no Aplicativo gov.br

<font><p style="text-align: center">**Tabela 4** - Cenário 03</p></font>

| Elemento     | Descrição                                                                                       | Ligação com Léxicos                                                                                                                 |
|--------------|-------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| Objetivo     | Redefinir senha do Gov.br                                                                       | [Senha](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#senha), [Gov.br](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#govbr)                                                                                      |
| Contexto     | Cidadão em casa, esqueceu a senha                                                               | [Cidadão](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#cidadão), [Senha](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#senha)                                                                                   |
| Recursos     | Smartphone com internet, aplicativo Gov.br, e-mail ou celular cadastrado                        | [Smartphone](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#smartphone), [Internet](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#internet), [Aplicativo Gov.br](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#aplicativo-govbr), [E-mail](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#e-mail), [Celular](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#celular) |
| Ator         | Cidadão                                                                                         | [Cidadão](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#cidadão)                                                                                                    |
| Episódios    | Abre o aplicativo, seleciona “Esqueci minha senha”, segue o processo de redefinição               | [Aplicativo Gov.br](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#aplicativo-govbr), [Esqueci minha senha](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#esqueci-minha-senha), [Redefinição de senha](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#redefinição-de-senha) |
| Restrições   | Acesso à internet, conta Gov.br, e-mail ou celular válido                                       | [Internet](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#internet), [Conta Gov.br](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#conta-govbr), [E-mail](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#e-mail), [Celular](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#celular)           |
| Exceções     | E-mail ou celular não cadastrado, falha no processo de recuperação                              | [E-mail](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#e-mail), [Celular](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#celular), [Falha no processo de recuperação](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#falha-no-processo-de-recuperação) |
<br>

<p style="text-align: center">Fonte: <a href="https://github.com/Caio-bergbjj">Caio Berg</a></p>

### Cenário 4: Consulta de CNPJ - gov.br

<font><p style="text-align: center">**Tabela 5** - Cenário 04</p></font>

| Elemento     | Descrição                                                                                       | Ligação com Léxicos                                                                                                                 |
|--------------|-------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| Objetivo     | Acessar histórico de login no aplicativo Gov.br                                                | [Histórico de Login](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#histórico-de-login), [Gov.br](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#govbr)                                                                 |
| Contexto     | Cidadão deseja verificar seus logins recentes                                                    | [Cidadão](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#cidadão), [Histórico de Login](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#histórico-de-login)                                          |
| Recursos     | Aplicativo Gov.br, conta Gov.br                                                                   | [Aplicativo Gov.br](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#aplicativo-govbr), [Conta Gov.br](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#conta-govbr)                                         |
| Ator         | Cidadão                                                                                         | [Cidadão](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#cidadão)                                                                                                    |
| Episódios    | Abre o aplicativo, faz login, vai em "Configurações", seleciona "Histórico de Login", visualiza detalhes | [Aplicativo Gov.br](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#aplicativo-govbr), [Login](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#login), [Configurações](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#configurações), [Histórico de Login](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#histórico-de-login)    |
| Restrições   | Acesso à internet, conta Gov.br, dados precisos e atualizados                                    | [Internet](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#internet), [Conta Gov.br](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#conta-govbr), [Dados](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#dados)                                               |
| Exceções     | Histórico vazio, login não reconhecido                                                          | [Histórico vazio](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#histórico-vazio), [Login não reconhecido](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#login-não-reconhecido)                                                             |
<br>

<p style="text-align: center">Fonte: <a href="https://github.com/esteerlino">Ester Lino</a></p>

### Cenário 5: Agendamento de Visita ao Palácio do Planalto - gov.br

<font><p style="text-align: center">**Tabela 6** - Cenário 05</p></font>


| Elemento     | Descrição                                                                                       | Ligação com Léxicos                                                                                                                 |
|--------------|-------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| Objetivo     | Solicitar auxílio emergencial através do aplicativo Gov.br                                     | [Auxílio Emergencial](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#auxílio-emergencial), [Gov.br](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#govbr)                                                                    |
| Contexto     | Cidadão busca assistência financeira temporária durante a crise                                  | [Cidadão](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#cidadão), [Auxílio Emergencial](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#auxílio-emergencial)                                                      |
| Recursos     | Aplicativo Gov.br, dados pessoais e financeiros                                                | [Aplicativo Gov.br](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#aplicativo-govbr), [Dados Pessoais](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#dados-pessoais), [Dados Financeiros](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#dados-financeiros)     |
| Ator         | Cidadão                                                                                         | [Cidadão](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#cidadão)                                                                                                    |
| Episódios    | Abre o aplicativo, faz login, vai para "Auxílio Emergencial", preenche formulário e solicita     | [Aplicativo Gov.br](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#aplicativo-govbr), [Login](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#login), [Auxílio Emergencial](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#auxílio-emergencial), [Formulário](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#formulário) |
| Restrições   | Requisitos de elegibilidade, acesso à internet                                                  | [Elegibilidade](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#elegibilidade), [Internet](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#internet)                                                                      |
| Exceções     | Documentação incompleta, não atende aos requisitos                                              | [Documentação](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#documentação), [Requisitos](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#requisitos)                                                                     |                                                                             |
<br>

<p style="text-align: center">Fonte: <a href="https://github.com/IsaqueSH">Isaque Santos</a></p>

### Cenário 6: Consulta do Histórico de Login no Aplicativo gov.br

<font><p style="text-align: center">**Tabela 7** - Cenário 06</p></font>

| Elemento     | Descrição                                                                                       | Ligação com Léxicos                                                                                                                |
|--------------|-------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| Objetivo     | Solicitar auxílio emergencial através do aplicativo Gov.br                                     | [Auxílio Emergencial](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#auxílio-emergencial), [Gov.br](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#govbr)                                                                    |
| Contexto     | Cidadão busca assistência financeira temporária durante a crise                                  | [Cidadão](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#cidadão), [Auxílio Emergencial](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#auxílio-emergencial)                                                      |
| Recursos     | Aplicativo Gov.br, dados pessoais e financeiros                                                | [Aplicativo Gov.br](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#aplicativo-govbr), [Dados Pessoais](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#dados-pessoais), [Dados Financeiros](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#dados-financeiros)     |
| Ator         | Cidadão                                                                                         | [Cidadão](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#cidadão)                                                                                                    |
| Episódios    | Abre o aplicativo, faz login, vai para "Auxílio Emergencial", preenche formulário e solicita     | [Aplicativo Gov.br](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#aplicativo-govbr), [Login](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#login), [Auxílio Emergencial](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#auxílio-emergencial), [Formulário](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#formulário) |
| Restrições   | Requisitos de elegibilidade, acesso à internet                                                  | [Elegibilidade](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#elegibilidade), [Internet](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#internet)                                                                      |
| Exceções     | Documentação incompleta, não atende aos requisitos                                              | [Documentação](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#documentação), [Requisitos](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#requisitos)                                                                     |
<br>

<p style="text-align: center">Fonte: <a href="https://github.com/thiagorfreitas">Thiago Freitas</a></p>

### Cenário 7: Consulta dos Termos de Uso do Aplicativo gov.br

<font><p style="text-align: center">**Tabela 8** - Cenário 07</p></font>

| Elemento     | Descrição                                                                                       | Ligação com Léxicos                                                                                                                |
|--------------|-------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| Objetivo     | Atualizar dados cadastrais no aplicativo Gov.br                                                 | [Dados Cadastrais](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#dados-cadastrais), [Gov.br](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#govbr)                                                                       |
| Contexto     | Cidadão precisa atualizar suas informações pessoais                                              | [Cidadão](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#cidadão), [Dados Cadastrais](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#dados-cadastrais)                                                                        |
| Recursos     | Aplicativo Gov.br, acesso à internet, dados atuais a serem atualizados                           | [Aplicativo Gov.br](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#aplicativo-govbr), [Internet](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#internet), [Dados](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#dados)                                       |
| Ator         | Cidadão                                                                                         | [Cidadão](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#cidadão)                                                                                                    |
| Episódios    | Abre o aplicativo, faz login, acessa "Atualização de Dados", altera informações, confirma mudanças | [Aplicativo Gov.br](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#aplicativo-govbr), [Login](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#login), [Atualização de Dados](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#atualização-de-dados) |
| Restrições   | Dados válidos e atualizados, acesso à internet                                                   | [Dados](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#dados), [Internet](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#internet)                                                                               |
| Exceções     | Dados inconsistentes, falhas na atualização                                                      | [Dados inconsistentes](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#dados-inconsistentes), [Falhas na atualização](https://github.com/Requisitos-de-Software/2024.1-Gov.br/blob/main/docs/modelagem/lexicos.md#falhas-na-atualização)                                                   |
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
|  1.6   | 06/07/2024 | Correções no artefato | [Carlos Gabriel](https://github.com/TheCarlosRamos) | [Henrique Batalha](https://github.com/HeBatalha),  |
