# Forward-From

## Introdução

A rastreabilidade de requisitos é fundamental no desenvolvimento de sistemas de software, garantindo que as origens e as implicações dos requisitos sejam claras ao longo do ciclo de vida do sistema.

Este artefato apresenta a aplicação do método Forward-from, que estabelece conexões entre os requisitos e os artefatos de design e implementação, contribuindo para a garantia da qualidade e alinhamento com as necessidades do cliente.

A rastreabilidade é crucial para a validação, correção de defeitos e verificação de alocação de requisitos, assegurando que a implementação final atenda aos requisitos acordados.

## Metodologia

A metodologia de rastreabilidade de requisitos proposta por Toranzo, é uma abordagem abrangente para mapear e documentar as relações entre requisitos, casos de uso, testes e outros elementos de um projeto de software.
Seu principal objetivo é garantir que cada requisito seja implementado e testado corretamente.

Tipos de Elos da Rastreabilidade, segundo o meta-modelo de Toranzo:

- Satisfação: classe origem tem dependência de satisfação com a classe destino.
- Recurso: classe origem tem dependência de recurso com a classe destino.
- Responsabilidade: registra a participação, responsabilidade e ação de pessoas sobre artefatos.
- Representação: captura a representação ou modelagem dos requisitos em outras linguagens.
- Alocado: classe origem está relacionada à classe destino, que representa um subsistema.
- Agregação: indica “composição” de elementos.

### Legenda

- RFx: Requisito Funcional nºx
- RNFx: Requisito Não-Funcional nºx
- Cx: Cenário nºx
- UCx: Caso de Uso nºx
- ESx: Especificação Suplementar nºx
- Lx: Léxico nºx
- EPx: Épico nºx
- Tx: Tema nºx
- HSx: Histária de Usuário nºx
- NFRx: NFR Framework nºx

## Desenvolvimento

Nas tabelas 1 e 2 são apresentados os requisitos funcionais e não funcionais elicitados e revisados, assim como a rastreabilidade das técnicas de modelagem usadas para cada um. Já a tabela 3 e 4 mostram os elos de rastreabilidade entre o requisitos - funcionais e não funcionais - e os artefatos criados durante a modelagem.

### Requisitos Funcionais (RF)

<font><p style="text-align: center">**Tabela 1:** Requisitos funcionais.</p></font>

|  ID  | Cenário | Caso de Uso | Especificação Suplementar | Léxico | Épico | Tema | História de Usuário | NFR Framework | Implementação |
|:----:|:-------:|:-----------:|:-------------------------:|:------:|:-----:|:----:|:-------------------:|:-------------:|:-------------:|
| RF01 | [Cenário 3](modelagem/cenarios.md#cenário-3-redefinição-de-senha-no-aplicativo-govbr) | - | [DES01*](modelagem/especificacao_suplementar.md#p-desempenho-performance) | [L05](modelagem/lexicos.md#léxicos-do-tipo-verbo) | [EP04](modelagem/agil/backlog.md#Épicos) | [T04](modelagem/agil/backlog.md#temas) | [HSU14](modelagem/agil/backlog.md#histórias-de-usuário) | [NFR03*](modelagem/agil/nfr_framework.md#nfr03-portabilidade) | Em desenvolvimento |
| RF02 | [Cenário 3](modelagem/cenarios.md#cenário-3-redefinição-de-senha-no-aplicativo-govbr) | [UC02](modelagem/casos_de_uso.md#uc02-validar-credenciais) | - | - | [EP04](modelagem/agil/backlog.md#Épicos) | [T04](modelagem/agil/backlog.md#temas) | [HSU15](modelagem/agil/backlog.md#histórias-de-usuário) | - | Em desenvolvimento |
| RF03 | Não utilizado | - | - | - | - | - | - | - | Em desenvolvimento |
| RF04 | [Cenário 2](modelagem/cenarios.md#cenário-2-simulação-de-aposentadoria-govbr) [Cenário 4](modelagem/cenarios.md#cenário-4-consulta-de-cnpj-govbr) [Cenário 5](modelagem/cenarios.md#cenário-5-agendamento-de-visita-ao-palácio-do-planalto-govbr) | [UC02](modelagem/casos_de_uso.md#uc02-validar-credenciais) [UC05](modelagem/casos_de_uso.md#uc05-consultar-benefícios) [UC07](modelagem/casos_de_uso.md#uc07-visualizar-documentos) [UC10](modelagem/casos_de_uso.md#uc10-agendar-atendimento) | - | [L15](modelagem/lexicos.md#léxicos-do-tipo-objeto) | [EP02](modelagem/agil/backlog.md#Épicos) | [T02](modelagem/agil/backlog.md#temas) | [HSU04](modelagem/agil/backlog.md#histórias-de-usuário) [HSU08](modelagem/agil/backlog.md#histórias-de-usuário) | - | Em desenvolvimento  |
| RF05 | [Cenário 6](modelagem/cenarios.md#cenário-6-consulta-do-histórico-de-login-no-aplicativo-govbr) | - | [CON04*](modelagem/especificacao_suplementar.md#r-confiabilidade-reliability) | - | - | - | - | [NFR1*](modelagem/agil/nfr_framework.md#nfr1-confiabilidade) | Em desenvolvimento |
| RF06 | - | [UC06](modelagem/casos_de_uso.md#uc06-aumentar-nível-da-conta) | [RD01*](modelagem/especificacao_suplementar.md#-restrições-de-design) | [L08](modelagem/lexicos.md#léxicos-do-tipo-verbo) | - | - | - | [NFR06*](modelagem/agil/nfr_framework.md#nfr06-restrição-de-design) | Em desenvolvimento |
| RF07 | - | [UC04](modelagem/casos_de_uso.md#uc04-atualizar-dados-pessoais) | - | [L03](modelagem/lexicos.md#léxicos-do-tipo-verbo) | [EP03](modelagem/agil/backlog.md#Épicos) | [T03](modelagem/agil/backlog.md#temas) | [HSU07](modelagem/agil/backlog.md#histórias-de-usuário) [HSU09](modelagem/agil/backlog.md#histórias-de-usuário) | - | Em desenvolvimento |
| RF08 | - | - | - | - | - | - | - | - | - |
| RF09 | [Cenário 1](modelagem/cenarios.md#cenário-1-consulta-de-cpf-govbr) | [UC07](modelagem/casos_de_uso.md#uc07-visualizar-documentos) [UC08](modelagem/casos_de_uso.md#uc08-baixar-documentos) [UC09](modelagem/casos_de_uso.md#uc09-emitir-2ª-via) | - | [L02](modelagem/lexicos.md#léxicos-do-tipo-verbo) [L04](modelagem/lexicos.md#léxicos-do-tipo-verbo) [L06](modelagem/lexicos.md#léxicos-do-tipo-verbo) [L10](modelagem/lexicos.md#léxicos-do-tipo-objeto) [L14](modelagem/lexicos.md#léxicos-do-tipo-objeto) | [EP01](modelagem/agil/backlog.md#Épicos) | [T01](modelagem/agil/backlog.md#temas) | [HSU01](modelagem/agil/backlog.md#histórias-de-usuário) [HSU02](modelagem/agil/backlog.md#histórias-de-usuário) [HSU03](modelagem/agil/backlog.md#histórias-de-usuário) [HSU05](modelagem/agil/backlog.md#histórias-de-usuário) [HSU06](modelagem/agil/backlog.md#histórias-de-usuário) [HSU10](modelagem/agil/backlog.md#histórias-de-usuário) | - | Em desenvolvimento |
| RF10 | - | [UC11](modelagem/casos_de_uso.md#uc11-solicitar-prova-de-vida) [UC12](modelagem/casos_de_uso.md#uc12-ver-histórico-de-prova-de-vida) | - | - | - | - | - | - | Em desenvolvimento |
| RF11 | - | [UC01](modelagem/casos_de_uso.md#uc01-fazer-login) [UC02](modelagem/casos_de_uso.md#uc02-validar-credenciais) [UC03](modelagem/casos_de_uso.md#uc03-emitir-erro-de-login) | - | [L01](modelagem/lexicos.md#léxicos-do-tipo-verbo) [L05](modelagem/lexicos.md#léxicos-do-tipo-verbo) | [EP04](modelagem/agil/backlog.md#Épicos) | [T04](modelagem/agil/backlog.md#temas) | [HSU14](modelagem/agil/backlog.md#histórias-de-usuário) | - | Sim |
| RF12 | - | - | - | - | - | - | - | - | - |
| RF13 | - | [UC07](modelagem/casos_de_uso.md#uc07-visualizar-documentos) | - | [L04](modelagem/lexicos.md#léxicos-do-tipo-verbo) [L10](modelagem/lexicos.md#léxicos-do-tipo-objeto) | [EP01](modelagem/agil/backlog.md#Épicos) | [T01](modelagem/agil/backlog.md#temas) | [HSU01](modelagem/agil/backlog.md#histórias-de-usuário) [HSU06](modelagem/agil/backlog.md#histórias-de-usuário) | - | - |
| RF14 | [Cenário 5](modelagem/cenarios.md#cenário-5-agendamento-de-visita-ao-palácio-do-planalto-govbr) | [UC10](modelagem/casos_de_uso.md#uc10-agendar-atendimento) | [USA05](modelagem/especificacao_suplementar.md#u-usabilidade-usability) [DES03](modelagem/especificacao_suplementar.md#p-desempenho-performance) [SUP04](modelagem/especificacao_suplementar.md#s-suporte-supportability) | [L15](modelagem/lexicos.md#léxicos-do-tipo-objeto) | [EP02](modelagem/agil/backlog.md#Épicos) |[T02](modelagem/agil/backlog.md#temas) | [HSU08](modelagem/agil/backlog.md#histórias-de-usuário) | [NFR03](modelagem/agil/nfr_framework.md#nfr03-portabilidade) [NFR04](modelagem/agil/nfr_framework.md#nfr04-desempenho-performance) [NFR05](modelagem/agil/nfr_framework.md#nfr05-usabilidade) | Em desenvolvimento |
| RF15 | - | [UC13](modelagem/casos_de_uso.md#uc13-baixar-certidões) | - | [L10](modelagem/lexicos.md#léxicos-do-tipo-objeto) | [EP01](modelagem/agil/backlog.md#Épicos) | [T01](modelagem/agil/backlog.md#temas) | [HSU10](modelagem/agil/backlog.md#histórias-de-usuário) | - |  | 
| RF16 | - | - | - | - | - | - | - | - | - |
| RF17 | - | - | - | - | - | - | - | - | - |
| RF18 | - | [UC14](modelagem/casos_de_uso.md#uc14-assinar-documentos-digitalmente) | [USA06](modelagem/especificacao_suplementar.md#u-usabilidade-usability) | [L06](modelagem/lexicos.md#léxicos-do-tipo-verbo) | [EP01](modelagem/agil/backlog.md#Épicos) | [T01](modelagem/agil/backlog.md#temas) | [HSU03](modelagem/agil/backlog.md#histórias-de-usuário) | [NFR05](modelagem/agil/backlog.md#histórias-de-usuário) | Sim |
| RF19 | Não utilizado | - | - | - | - | - | - | - | - |
| RF20 | - | [UC05](modelagem/casos_de_uso.md#uc05-consultar-benefícios) | - | - | - | - | - | - | - |
| RF21 | - | [UC13](modelagem/casos_de_uso.md#uc13-baixar-certidões) | - | - | - | - | - | - | Em desenvolvimento  |
| RF22 | - | [UC13](modelagem/casos_de_uso.md#uc13-baixar-certidões) | - | - | - | - | - | - | - |
| RF23 | Não utilizado | - | - | - | - | - | - | - | - |
| RF24 | Não utilizado | - | - | - | - | - | - | - | - |
| RF25 | - | - | - | [L07](modelagem/lexicos.md#léxicos-do-tipo-verbo) | - | - | - | - | - |
| RF26 | - | - | [SUP01](modelagem/especificacao_suplementar.md#s-suporte-supportability) | - | - | - | - | [NFR04](modelagem/agil/nfr_framework.md#nfr04-desempenho-performance) | Em desenvolvimento |
| RF27 | - | - | [USA03](modelagem/especificacao_suplementar.md#u-usabilidade-usability) [USA04](modelagem/especificacao_suplementar.md#u-usabilidade-usability) | - | - | - | - | [NFR03](modelagem/agil/nfr_framework.md#nfr03-portabilidade) [NFR04](modelagem/agil/nfr_framework.md#nfr04-desempenho-performance) [NFR05](modelagem/agil/nfr_framework.md#nfr05-usabilidade) | - |
| RF28 | - | [UC10](modelagem/casos_de_uso.md#uc10-agendar-atendimento) | [USA05](modelagem/especificacao_suplementar.md#u-usabilidade-usability) | [L05](modelagem/lexicos.md#léxicos-do-tipo-verbo) | - | - | - | [NFR03](modelagem/agil/nfr_framework.md#nfr03-portabilidade) [NFR04](modelagem/agil/nfr_framework.md#nfr04-desempenho-performance) [NFR05](modelagem/agil/nfr_framework.md#nfr05-usabilidade) | - |
| RF29 | - | [UC14](modelagem/casos_de_uso.md#uc14-assinar-documentos-digitalmente) | [USA06](modelagem/especificacao_suplementar.md#u-usabilidade-usability) | [L06](modelagem/lexicos.md#léxicos-do-tipo-verbo) | - | - | - | [NFR05](modelagem/agil/nfr_framework.md#nfr05-usabilidade) | - |
| RF30 | - | [UC10](modelagem/casos_de_uso.md#uc10-agendar-atendimento) | [USA05](modelagem/especificacao_suplementar.md#u-usabilidade-usability) | [L05](modelagem/lexicos.md#léxicos-do-tipo-verbo) | - | - | - | [NFR03](modelagem/agil/nfr_framework.md#nfr03-portabilidade) [NFR04](modelagem/agil/nfr_framework.md#nfr04-desempenho-performance) [NFR05](modelagem/agil/nfr_framework.md#nfr05-usabilidade) | - |
| RF31 | [Cenário 2](modelagem/cenarios.md#cenário-2-simulação-de-aposentadoria-govbr) | [UC05](modelagem/casos_de_uso.md#uc05-consultar-benefícios) | [SUP05](modelagem/especificacao_suplementar.md#s-suporte-supportability) | - | - | - | - | [NFR04](modelagem/agil/nfr_framework.md#nfr04-desempenho-performance) | - |
| RF32 | - | [UC14](modelagem/casos_de_uso.md#uc14-assinar-documentos-digitalmente) | [USA06](modelagem/especificacao_suplementar.md#u-usabilidade-usability) | [L06](modelagem/lexicos.md#léxicos-do-tipo-verbo) [L10](modelagem/lexicos.md#léxicos-do-tipo-objeto) [L14](modelagem/lexicos.md#léxicos-do-tipo-objeto) | - | - | - | [NFR05](modelagem/agil/nfr_framework.md#nfr05-usabilidade) | - |
| RF33 | [Cenário 2](modelagem/cenarios.md#cenário-2-simulação-de-aposentadoria-govbr) | [UC11](modelagem/casos_de_uso.md#uc11-solicitar-prova-de-vida) | - | - | - | - | - | - | - |
| RF34 | - | - | - | - | - | - | - | - | - |
| RF35 | - | - | [CON04](modelagem/especificacao_suplementar.md#r-confiabilidade-reliability) [CON05](modelagem/especificacao_suplementar.md#r-confiabilidade-reliability) | [L05](modelagem/lexicos.md#léxicos-do-tipo-verbo) [L07](modelagem/lexicos.md#léxicos-do-tipo-verbo) [L19](modelagem/lexicos.md#léxicos-do-tipo-estado) | - | - | - | [NFR01](modelagem/agil/nfr_framework.md#nfr1-confiabilidade) [NFR06](modelagem/agil/nfr_framework.md#nfr06-restrição-de-design) | - |
| RF36 | - | [UC10](modelagem/casos_de_uso.md#uc10-agendar-atendimento) | [USA05](modelagem/especificacao_suplementar.md#u-usabilidade-usability) | [L05](modelagem/lexicos.md#léxicos-do-tipo-verbo) | - | - | - | [NFR03](modelagem/agil/nfr_framework.md#nfr03-portabilidade) [NFR04](modelagem/agil/nfr_framework.md#nfr04-desempenho-performance) [NFR05](modelagem/agil/nfr_framework.md#nfr05-usabilidade) | - |
| RF37 | - | - | - | - | - | - | - | - | - |
| RF38 |  |  |  |  |  |  |  |  |  |
| RF39 | - | - | - | - | - | - | - | - | - |
| RF40 | Não utilizado | - | - | - | - | - | - | - | - |
| RF41 | - | - | - | - | - | - | - | - | - |
| RF42 | - | - | - | - | - | - | - | - | - |
| RF43 | - | - | - | - | - | - | - | - | - |
| RF44 | - | - | - | - | - | - | - | - | - |

<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/ArthurGabrieel">Arthur Gabriel</a>, <a href="https://github.com/esteerlino">Ester Lino</a>, <a href="https://github.com/HeBatalha">Henrique Batalha</a> e <a href="https://github.com/IsaqueSH">Isaque Santos</a> </p></font>

### Requisitos Não Funcionais (RNF)

<font><p style="text-align: center">**Tabela 2:** Requisitos não funcionais.</p></font>

|  ID  | Cenário | Caso de Uso | Especificação Suplementar | Léxico | Épico | Tema | História de Usuário | NFR Framework | Implementação |
|:----:|:-------:|:-----------:|:-------------------------:|:------:|:-----:|:----:|:-------------------:|:-------------:|:-------------:|
| RNF01 | - | - | [CON01](modelagem/especificacao_suplementar.md#r-confiabilidade-reliability) | - | - | - | - | [NFR01](modelagem/agil/nfr_framework.md#nfr1-confiabilidade) | Sim |
| RNF02 | - | - | [USA01](modelagem/especificacao_suplementar.md#u-usabilidade-usability) | - | - | - | - | [NFR05](modelagem/agil/nfr_framework.md#nfr05-usabilidade) | Sim |
| RNF03 | - | - | [DES01](modelagem/especificacao_suplementar.md#p-desempenho-performance) | - | - | - | - | [NFR03](modelagem/agil/nfr_framework.md#nfr03-portabilidade) | Sim |
| RNF04 | - | - | [INT01](modelagem/especificacao_suplementar.md#-interfaces) | - | - | - | - | - | Sim |
| RNF05 | - | - | [INT02](modelagem/especificacao_suplementar.md#-interfaces)  | - | - | - | - | - | Sim |
| RNF06 | - | - | [INT03](modelagem/especificacao_suplementar.md#-interfaces)  | - | - | - | - | - | Sim |
| RNF07 | - | - | [RD01 ](modelagem/especificacao_suplementar.md#-restrições-de-design) | - | - | - | - | [NFR06](modelagem/agil/nfr_framework.md#nfr06-restrição-de-design) | Sim |
| RNF08 | - | - | [SUP01](modelagem/especificacao_suplementar.md#s-suporte-supportability) | - | - | - | - | [NFR04](modelagem/agil/nfr_framework.md#nfr04-desempenho-performance) | Sim |
| RNF09 | - | - | [CON03](modelagem/especificacao_suplementar.md#r-confiabilidade-reliability) | - | - | - | - | [NFR05](modelagem/agil/nfr_framework.md#nfr05-usabilidade) | Sim |
| RNF10 | NÃO UTILIZADO |  |  |  |  |  |  |  |  |
| RNF11 | - | - | - | - | - | - | - | - | - |
| RNF12 | - | - | [RD02 ](modelagem/especificacao_suplementar.md#-restrições-de-design) | - | - | - | - | [NFR06](modelagem/agil/nfr_framework.md#nfr06-restrição-de-design) | Não |
| RNF13 | - | - | [USA03](modelagem/especificacao_suplementar.md#u-usabilidade-usability) | - | - | - | - | [NFR05](modelagem/agil/nfr_framework.md#nfr05-usabilidade) | Não |
| RNF14 | - | - | [DES02](modelagem/especificacao_suplementar.md#p-desempenho-performance) | - | - | - | - | [NFR03](modelagem/agil/nfr_framework.md#nfr03-portabilidade) | Não |
| RNF15 | - | - | [SUP02](modelagem/especificacao_suplementar.md#s-suporte-supportability) | - | - | - | - | [NFR04](modelagem/agil/nfr_framework.md#nfr04-desempenho-performance) | Não |
| RNF16 | - | - | - | - | - | - | - | - | - |
| RNF17 | - | - | [USA02](modelagem/especificacao_suplementar.md#u-usabilidade-usability) | - | - | - | - | [NFR05](modelagem/agil/nfr_framework.md#nfr05-usabilidade) | Sim |
| RNF18 | - | - | [DES03](modelagem/especificacao_suplementar.md#p-desempenho-performance) | - | - | - | - | [NFR03](modelagem/agil/nfr_framework.md#nfr03-portabilidade) | Sim |
| RNF19 | NÃO UTILIZADO |  |  |  |  |  |  |  |  |
| RNF20 | - | - | [CON02](modelagem/especificacao_suplementar.md#r-confiabilidade-reliability) | - | - | - | - | [NFR01](modelagem/agil/nfr_framework.md#nfr1-confiabilidade) | Sim |
| RNF21 | - | - | [AD01 ](modelagem/especificacao_suplementar.md#-ajuda-e-documentação) | - | - | - | - | [NFR02](modelagem/agil/nfr_framework.md#nfr02-ajuda-e-documentação) | Sim |
| RNF22 | - | - | [AD02 ](modelagem/especificacao_suplementar.md#-ajuda-e-documentação) | - | - | - | - | [NFR02](modelagem/agil/nfr_framework.md#nfr02-ajuda-e-documentação) | Sim |

<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/ArthurGabrieel">Arthur Gabriel</a>, <a href="https://github.com/esteerlino">Ester Lino</a>, <a href="https://github.com/HeBatalha">Henrique Batalha</a> e <a href="https://github.com/IsaqueSH">Isaque Santos</a> </p></font>

</details>

### Elos - Requisitos Funcionais

<font><p style="text-align: center">**Tabela 3:** Elos dos requisitos funcionais</p></font>

| Nº do Elo | Requisito |                                                                                       Satisfação                                                                                       |              Recurso               | Representação |                     Alocação                     | Agregação |
| :-------: | :-------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :--------------------------------: | :-----------: | :----------------------------------------------: | :-------: |
|   ELO01   |   RF01    |                                                                      [HSU14](/modelagem/agil/historia_usuario.md)                                                                      | [UC01](/modelagem/casos_de_uso.md) |       -       |    [CON01](/modelagem/agil/nfr_framework.md)     |     -     |
|   ELO02   |   RF02    |                                                                      [HSU15](/modelagem/agil/historia_usuario.md)                                                                      | [UC02](/modelagem/casos_de_uso.md) |       -       |    [CON02](/modelagem/agil/nfr_framework.md)     |     -     |
|   ELO03   |   RF03    |                                                                                           -                                                                                            | [UC02](/modelagem/casos_de_uso.md) |       -       |    [CON03](/modelagem/agil/nfr_framework.md)     |     -     |
|   ELO04   |   RF04    |                                                                                           -                                                                                            |                 -                  |       -       |    [CON04](/modelagem/agil/nfr_framework.md)     |     -     |
|   ELO05   |   RF05    |                                                                                           -                                                                                            |                 -                  |       -       |    [CON05](/modelagem/agil/nfr_framework.md)     |     -     |
|   ELO06   |   RF06    |                                                                      [HSU10](/modelagem/agil/historia_usuario.md)                                                                      | [UC02](/modelagem/casos_de_uso.md) |       -       |    [CON04](/modelagem/agil/nfr_framework.md)     |     -     |
|   ELO07   |   RF07    |                                                                                           -                                                                                            | [UC01](/modelagem/casos_de_uso.md) |       -       |    [DES01](/modelagem/agil/nfr_framework.md)     |     -     |
|   ELO08   |   RF08    |                                                                                           -                                                                                            | [UC04](/modelagem/casos_de_uso.md) |       -       |    [DES02](/modelagem/agil/nfr_framework.md)     |     -     |
|   ELO09   |   RF09    |                                                                      [HSU15](/modelagem/agil/historia_usuario.md)                                                                      | [UC02](/modelagem/casos_de_uso.md) |       -       |    [DES03](/modelagem/agil/nfr_framework.md)     |     -     |
|   ELO10   |   RF10    | [HSU01](/modelagem/agil/historia_usuario.md), [HSU02](/modelagem/agil/historia_usuario.md), [HSU03](/modelagem/agil/historia_usuario.md), [HSU06](/modelagem/agil/historia_usuario.md) | [UC07](/modelagem/casos_de_uso.md) |       -       |    [DES04](/modelagem/agil/nfr_framework.md)     |     -     |
|   ELO11   |   RF11    |                                                                                           -                                                                                            | [UC11](/modelagem/casos_de_uso.md) |       -       |    [DES01](/modelagem/agil/nfr_framework.md)     |     -     |
|   ELO12   |   RF12    |                                                                                           -                                                                                            | [UC01](/modelagem/casos_de_uso.md) |       -       |     [RD03](/modelagem/agil/nfr_framework.md)     |     -     |
|   ELO13   |   RF13    |                                                                      [HSU14](/modelagem/agil/historia_usuario.md)                                                                      | [UC01](/modelagem/casos_de_uso.md) |       -       |     [RD01](/modelagem/agil/nfr_framework.md)     |     -     |
|   ELO14   |   RF14    |                                                                      [HSU01](/modelagem/agil/historia_usuario.md)                                                                      | [UC07](/modelagem/casos_de_uso.md) |       -       |    [DES03](/modelagem/agil/nfr_framework.md)     |     -     |
|   ELO15   |   RF15    |                                                                                           -                                                                                            | [UC10](/modelagem/casos_de_uso.md) |       -       |    [DES04](/modelagem/agil/nfr_framework.md)     |     -     |
|   ELO16   |   RF16    |                                                                      [HSU10](/modelagem/agil/historia_usuario.md)                                                                      | [UC07](/modelagem/casos_de_uso.md) |       -       |    [DES01](/modelagem/agil/nfr_framework.md)     |     -     |
|   ELO17   |   RF17    |                                                                                           -                                                                                            | [UC01](/modelagem/casos_de_uso.md) |       -       | [CON02, DES01](/modelagem/agil/nfr_framework.md) |     -     |
|   ELO18   |   RF18    |                                                                                           -                                                                                            | [UC13](/modelagem/casos_de_uso.md) |       -       |    [DES01](/modelagem/agil/nfr_framework.md)     |     -     |
|   ELO19   |   RF19    |                                                                                           -                                                                                            | [UC14](/modelagem/casos_de_uso.md) |       -       |    [USA01](/modelagem/agil/nfr_framework.md)     |     -     |
|   ELO20   |   RF20    |                                                                                           -                                                                                            |                 -                  |       -       |     [AD01](/modelagem/agil/nfr_framework.md)     |     -     |
|   ELO21   |   RF21    |                                                                                           -                                                                                            |                 -                  |       -       |     [AD02](/modelagem/agil/nfr_framework.md)     |     -     |
|   ELO22   |   RF22    |                                                                                           -                                                                                            |                 -                  |       -       |    [CON03](/modelagem/agil/nfr_framework.md)     |     -     |
|   ELO23   |   RF23    |                                                                                           -                                                                                            |                 -                  |       -       |    [CON05](/modelagem/agil/nfr_framework.md)     |     -     |
|   ELO24   |   RF24    |                                                                                           -                                                                                            |                 -                  |       -       |    [CON04](/modelagem/agil/nfr_framework.md)     |     -     |
|   ELO25   |   RF25    |                                                                                           -                                                                                            |                 -                  |       -       |    [CON05](/modelagem/agil/nfr_framework.md)     |     -     |
|   ELO26   |   RF26    |                                                                      [HSU14](/modelagem/agil/historia_usuario.md)                                                                      | [UC01](/modelagem/casos_de_uso.md) |       -       |    [DES03](/modelagem/agil/nfr_framework.md)     |     -     |
|   ELO27   |   RF27    |                                                                                           -                                                                                            |                 -                  |       -       |    [USA01](/modelagem/agil/nfr_framework.md)     |     -     |
|   ELO28   |   RF28    |                                                                                           -                                                                                            |                 -                  |       -       |    [USA02](/modelagem/agil/nfr_framework.md)     |     -     |
|   ELO29   |   RF29    |                                                                                           -                                                                                            |                 -                  |       -       |    [USA03](/modelagem/agil/nfr_framework.md)     |     -     |
|   ELO30   |   RF30    |                                                                                           -                                                                                            | [UC14](/modelagem/casos_de_uso.md) |       -       |    [USA04](/modelagem/agil/nfr_framework.md)     |     -     |
|   ELO31   |   RF31    |                                                                                           -                                                                                            |                 -                  |       -       |    [USA05](/modelagem/agil/nfr_framework.md)     |     -     |
|   ELO32   |   RF32    |                                                                                           -                                                                                            | [UC10](/modelagem/casos_de_uso.md) |       -       |    [USA06](/modelagem/agil/nfr_framework.md)     |     -     |
|   ELO33   |   RF33    |                                                                                           -                                                                                            |                 -                  |       -       |     [AD01](/modelagem/agil/nfr_framework.md)     |     -     |
|   ELO34   |   RF34    |                                                                                           -                                                                                            |                 -                  |       -       |     [AD02](/modelagem/agil/nfr_framework.md)     |     -     |
|   ELO35   |   RF35    |                                                                                           -                                                                                            |                 -                  |       -       |    [CON03](/modelagem/agil/nfr_framework.md)     |     -     |
|   ELO36   |   RF36    |             -              |    -    |       -       | [CON04](/modelagem/agil/nfr_framework.md) |    -      |
|   ELO37   |   RF37    |             -              |  [UC10](/modelagem/casos_de_uso.md)   |       -       | [DES01](/modelagem/agil/nfr_framework.md) |    -    |
|   ELO38   |   RF38    |             -              |  [UC07](/modelagem/casos_de_uso.md)   |       -       | [USA06](/modelagem/agil/nfr_framework.md) |    -      |
|   ELO39   |   RF39    |             -              |  [UC07](/modelagem/casos_de_uso.md)   |       -       | [CON02](/modelagem/agil/nfr_framework.md) |    -      |
|   ELO40   |   RF40    |             -              |    -    |       -       | [DES01](/modelagem/agil/nfr_framework.md) |    -      |
|   ELO41   |   RF41    |             -              |    -    |       -       | [DES02](/modelagem/agil/nfr_framework.md) |    -      |
|   ELO42   |   RF42    |             -              |    -    |       -       | [CON05](/modelagem/agil/nfr_framework.md) |    -      |

<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/ArthurGabrieel">Arthur Gabriel</a>, <a href="https://github.com/esteerlino">Ester Lino</a>, <a href="https://github.com/HeBatalha">Henrique Batalha</a> e <a href="https://github.com/IsaqueSH">Isaque Santos</a> </p></font>

## Elos - Requisitos Não Funcionais

<font><p style="text-align: center">**Tabela 4:** Elos dos requisitos não funcionais</p></font>

| Nº do Elo | Requisito |                  Satisfação                  |              Recurso               | Representação |                  Alocação                  | Agregação |
| :-------: | :-------: | :------------------------------------------: | :--------------------------------: | :-----------: | :----------------------------------------: | :-------: |
|   ELO47   |   RNF01   |                    -                         | [UC03](/modelagem/casos_de_uso.md) |       -       | [CON01](/modelagem/agil/nfr_framework.md)  |   RF01    |
|   ELO48   |   RNF02   |                    -                         |                 -                  |       -       | [USA01](/modelagem/agil/nfr_framework.md)  |   RF02    |
|   ELO49   |   RNF03   | [HSU14](/modelagem/agil/historia_usuario.md) |                 -                  |       -       | [DES01](/modelagem/agil/nfr_framework.md)  |   RF07    |
|   ELO50   |   RNF04   |                    -                         |                 -                  |       -       | [CON04](/modelagem/agil/nfr_framework.md)  |   RF06    |
|   ELO51   |   RNF05   |                    -                         |                 -                  |       -       | [CON05](/modelagem/agil/nfr_framework.md)  |   RF08    |
|   ELO52   |   RNF06   |                       -                      |                 -                  |       -       | [PORT02](/modelagem/agil/nfr_framework.md) |   RF09    |
|   ELO53   |   RNF07   |                     -                        | [UC06](/modelagem/casos_de_uso.md) |       -       |  [RD01](/modelagem/agil/nfr_framework.md)  |   RF10    |
|   ELO54   |   RNF08   |                    -                         |                 -                  |       -       | [PORT01](/modelagem/agil/nfr_framework.md) |   RF11    |
|   ELO55   |   RNF09   |                      -                       |                 -                  |       -       | [CON03](/modelagem/agil/nfr_framework.md)  |   RF12    |
|   ELO56   |   RNF10   | [HSU14](/modelagem/agil/historia_usuario.md) |                 -                  |       -       | [DES03](/modelagem/agil/nfr_framework.md)  |   RF13    |
|   ELO57   |   RNF11   |                       -                      |                 -                  |       -       | [PORT01](/modelagem/agil/nfr_framework.md) |   RF27    |
|   ELO58   |   RNF12   | [HSU09](/modelagem/agil/historia_usuario.md) |                 -                  |       -       |  [RD02](/modelagem/agil/nfr_framework.md)  |   RF14    |
|   ELO59   |   RNF13   |                    -                         |                 -                  |       -       | [USA03](/modelagem/agil/nfr_framework.md)  |   RF28    |
|   ELO60   |   RNF14   |                  -                           |                 -                  |       -       | [DES02](/modelagem/agil/nfr_framework.md)  |   RF15    |
|   ELO61   |   RNF15   |                       -                      |                 -                  |       -       | [SUP02](/modelagem/agil/nfr_framework.md)  |   RF29    |
|   ELO62   |   RNF16   |                       -                      |                 -                  |       -       | [CON02](/modelagem/agil/nfr_framework.md)  |   RF30    |
|   ELO63   |   RNF17   |                       -                      |                 -                  |       -       | [USA02](/modelagem/agil/nfr_framework.md)  |   RF31    |
|   ELO64   |   RNF18   |                       -                      |                 -                  |       -       | [DES03](/modelagem/agil/nfr_framework.md)  |   RF32    |
|   ELO65   |   RNF19   |                       -                      |                 -                  |       -       | [PORT01](/modelagem/agil/nfr_framework.md) |   RF41    |
|   ELO66   |   RNF20   |                       -                      |                 -                  |       -       | [CON02](/modelagem/agil/nfr_framework.md)  |   RF42    |
|   ELO67   |   RNF21   |                       -                      |                 -                  |       -       |  [AD01](/modelagem/agil/nfr_framework.md)  |   RF38    |
|   ELO68   |   RNF22   |                       -                      |                 -                  |       -       |  [AD02](/modelagem/agil/nfr_framework.md)  |   RF36    |

<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/ArthurGabrieel">Arthur Gabriel</a>, <a href="https://github.com/esteerlino">Ester Lino</a>, <a href="https://github.com/HeBatalha">Henrique Batalha</a> e <a href="https://github.com/IsaqueSH">Isaque Santos</a> </p></font>

## Bibliografia

- Monografia - Miriam Sayão e Julio Prado Leite. Disponível em: <https://www.dbd.puc-rio.br/depto_informatica/05_20_sayao.pdf> Acesso em 22 de Junho de 2024

## Histórico de Versão

| Versão  | Data | Descrição | Autor(es) | Revisor(es) |
| -------- | ------ | ------ | ---------- | ---------- |
| 1.0 | 22/06/2024 | Criação do Documento | [Ester Lino](https://github.com/esteerlino) | [Isaque Santos](https://github.com/IsaqueSH) |
