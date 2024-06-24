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
- Epx: Épico nºx
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
| RF04 | [Cenário 2] [Cenário 4] [Cenário 5] | [UC02] [UC05] [UC07] [UC10] | - | [L15] | [EP02] | [T02] | [HSU04] [HSU08] | - | Em desenvolvimento  |
| RF05 | [Cenário 6] | - | [CON04*] | - | - | - | - | [NFR1*] | Em desenvolvimento |
| RF06 | - | [UC06] | [RD01*] | [L08] | - | - | - | [NFR06*] | Em desenvolvimento |
| RF07 | - | [UC04] | - | [L03] | [EP03] | [T03] | [HSU07] [HSU09] | - | Em desenvolvimento |
| RF08 | - | - | - | - | - | - | - | - | - |
| RF09 | [Cenário 1] | [UC07] [UC08] [UC09] | - | [L02] [L04] [L06] [L10] [L14] | [EP01] | [T01] | [HSU01] [HSU02] [HSU03] [HSU05] [HSU06] [HSU10] | - | Em desenvolvimento |
| RF10 | - | [UC11] [UC12] | - | - | - | - | - | - | Em desenvolvimento |
| RF11 | - | [UC01] [UC02] [UC03] | - | [L01] [L05] | [EP04] | [T04] | [HSU14] | - | Sim |
| RF12 | - | - | - | - | - | - | - | - | - |
| RF13 | - | [UC07] | - | [L04] [L10] | [EP01] | [T01] | [HSU01] [HSU06] | - | - |
| RF14 | [Cenário 5] | [UC10] | [USA05] [DES03] [SUP04] | [L15] | [EP02] |[T02] | [HSU08] | [NFR03] [NFR04] [NFR05] | Em desenvolvimento |
| RF15 | - | [UC13] | - | [L10] | [EP01] | [T01] | [HSU10] | - |  | 
| RF16 | - | - | - | - | - | - | - | - | - |
| RF17 | - | - | - | - | - | - | - | - | - |
| RF18 | - | [UC14] | [USA06] | [L06] | [EP01] | [T01] | [HSU03] | [NFR05] | Sim |
| RF19 | Não utilizado | - | - | - | - | - | - | - | - |
| RF20 | - | [UC05] | - | - | - | - | - | - | - |
| RF21 | - | [UC13] | - | - | - | - | - | - | Em desenvolvimento  |
| RF22 | * |  |  |  |  |  |  |  |  |
| RF23 | * |  |  |  |  |  |  |  |  |
| RF24 |  |  |  |  |  |  |  |  |  |
| RF25 | * |  |  |  |  |  |  |  |  |
| RF26 |  |  |  |  |  |  |  |  |  |
| RF27 | * |  |  |  |  |  |  |  |  |
| RF28 | * |  |  |  |  |  |  |  |  |
| RF29 | * |  |  |  |  |  |  |  |  |
| RF30 |  |  |  |  |  |  |  |  |  |
| RF31 |  |  |  |  |  |  |  |  |  |
| RF32 | * |  |  |  |  |  |  |  |  |
| RF33 | * |  |  |  |  |  |  |  |  |
| RF34 | * |  |  |  |  |  |  |  |  |
| RF35 | * |  |  |  |  |  |  |  |  |
| RF36 | * |  |  |  |  |  |  |  |  |
| RF37 | - | - | - | - | - | - | - | - | - |
| RF38 |  |  |  |  |  |  |  |  |  |
| RF39 | - | - | - | - | - | - | - | - | - |
| RF40 | * |  |  |  |  |  |  |  |  |
| RF41 |  |  |  |  |  |  |  |  |  |
| RF42 |  |  |  |  |  |  |  |  |  |
| RF43 |  |  |  |  |  |  |  |  |  |
| RF44 |  |  |  |  |  |  |  |  |  |

<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/ArthurGabrieel">Arthur Gabriel</a>, <a href="https://github.com/esteerlino">Ester Lino</a>, <a href="https://github.com/HeBatalha">Henrique Batalha</a> e <a href="https://github.com/IsaqueSH">Isaque Santos</a> </p></font>

### Requisitos Não Funcionais (RNF)

<font><p style="text-align: center">**Tabela 2:** Requisitos não funcionais.</p></font>

|  ID  | Cenário | Caso de Uso | Especificação Suplementar | Léxico | Épico | Tema | História de Usuário | NFR Framework | Implementação |
|:----:|:-------:|:-----------:|:-------------------------:|:------:|:-----:|:----:|:-------------------:|:-------------:|:-------------:|
| RNF01 | - | - | [CON01] | - | - | - | - | [NFR01] | Sim |
| RNF02 | - | - | [USA01] | - | - | - | - | [NFR05] | Sim |
| RNF03 | - | - | [DES01] | - | - | - | - | [NFR03] | Sim |
| RNF04 | - | - | [INT01] | - | - | - | - | - | Sim |
| RNF05 | - | - | [INT02] | - | - | - | - | - | Sim |
| RNF06 | - | - | [INT03] | - | - | - | - | - | Sim |
| RNF07 | - | - | [RD01 ] | - | - | - | - | [NFR06] | Sim |
| RNF08 | - | - | [SUP01] | - | - | - | - | [NFR04] | Sim |
| RNF09 | - | - | [CON03] | - | - | - | - | [NFR05] | Sim |
| RNF10 | NÃO UTILIZADO |  |  |  |  |  |  |  |  |
| RNF11 | - | - | - | - | - | - | - | - | - |
| RNF12 | - | - | [RD02 ] | - | - | - | - | [NFR06] | Não |
| RNF13 | - | - | [USA03] | - | - | - | - | [NFR05] | Não |
| RNF14 | - | - | [DES02] | - | - | - | - | [NFR03] | Não |
| RNF15 | - | - | [SUP02] | - | - | - | - | [NFR04] | Não |
| RNF16 | - | - | - | - | - | - | - | - | - |
| RNF17 | - | - | [USA02] | - | - | - | - | [NFR05] | Sim |
| RNF18 | - | - | [DES03] | - | - | - | - | [NFR03] | Sim |
| RNF19 | NÃO UTILIZADO |  |  |  |  |  |  |  |  |
| RNF20 | - | - | [CON02] | - | - | - | - | [NFR01] | Sim |
| RNF21 | - | - | [AD01 ] | - | - | - | - | [NFR02] | Sim |
| RNF22 | - | - | [AD02 ] | - | - | - | - | [NFR02] | Sim |

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
|   ELO47   |   RNF01   | [HSU14](/modelagem/agil/historia_usuario.md) | [UC03](/modelagem/casos_de_uso.md) |       -       | [CON01](/modelagem/agil/nfr_framework.md)  |   RF01    |
|   ELO48   |   RNF02   | [HSU01](/modelagem/agil/historia_usuario.md) |                 -                  |       -       | [USA01](/modelagem/agil/nfr_framework.md)  |   RF02    |
|   ELO49   |   RNF03   | [HSU14](/modelagem/agil/historia_usuario.md) |                 -                  |       -       | [DES01](/modelagem/agil/nfr_framework.md)  |   RF07    |
|   ELO50   |   RNF04   | [HSU01](/modelagem/agil/historia_usuario.md) |                 -                  |       -       | [CON04](/modelagem/agil/nfr_framework.md)  |   RF06    |
|   ELO51   |   RNF05   | [HSU01](/modelagem/agil/historia_usuario.md) |                 -                  |       -       | [CON05](/modelagem/agil/nfr_framework.md)  |   RF08    |
|   ELO52   |   RNF06   | [HSU07](/modelagem/agil/historia_usuario.md) |                 -                  |       -       | [PORT02](/modelagem/agil/nfr_framework.md) |   RF09    |
|   ELO53   |   RNF07   | [HSU14](/modelagem/agil/historia_usuario.md) | [UC06](/modelagem/casos_de_uso.md) |       -       |  [RD01](/modelagem/agil/nfr_framework.md)  |   RF10    |
|   ELO54   |   RNF08   | [HSU01](/modelagem/agil/historia_usuario.md) |                 -                  |       -       | [PORT01](/modelagem/agil/nfr_framework.md) |   RF11    |
|   ELO55   |   RNF09   | [HSU14](/modelagem/agil/historia_usuario.md) |                 -                  |       -       | [CON03](/modelagem/agil/nfr_framework.md)  |   RF12    |
|   ELO56   |   RNF10   | [HSU14](/modelagem/agil/historia_usuario.md) |                 -                  |       -       | [DES03](/modelagem/agil/nfr_framework.md)  |   RF13    |
|   ELO57   |   RNF11   | [HSU07](/modelagem/agil/historia_usuario.md) |                 -                  |       -       | [PORT01](/modelagem/agil/nfr_framework.md) |   RF27    |
|   ELO58   |   RNF12   | [HSU09](/modelagem/agil/historia_usuario.md) |                 -                  |       -       |  [RD02](/modelagem/agil/nfr_framework.md)  |   RF14    |
|   ELO59   |   RNF13   | [HSU01](/modelagem/agil/historia_usuario.md) |                 -                  |       -       | [USA03](/modelagem/agil/nfr_framework.md)  |   RF28    |
|   ELO60   |   RNF14   | [HSU01](/modelagem/agil/historia_usuario.md) |                 -                  |       -       | [DES02](/modelagem/agil/nfr_framework.md)  |   RF15    |
|   ELO61   |   RNF15   | [HSU07](/modelagem/agil/historia_usuario.md) |                 -                  |       -       | [SUP02](/modelagem/agil/nfr_framework.md)  |   RF29    |
|   ELO62   |   RNF16   | [HSU09](/modelagem/agil/historia_usuario.md) |                 -                  |       -       | [CON02](/modelagem/agil/nfr_framework.md)  |   RF30    |
|   ELO63   |   RNF17   | [HSU01](/modelagem/agil/historia_usuario.md) |                 -                  |       -       | [USA02](/modelagem/agil/nfr_framework.md)  |   RF31    |
|   ELO64   |   RNF18   | [HSU01](/modelagem/agil/historia_usuario.md) |                 -                  |       -       | [DES03](/modelagem/agil/nfr_framework.md)  |   RF32    |
|   ELO65   |   RNF19   | [HSU01](/modelagem/agil/historia_usuario.md) |                 -                  |       -       | [PORT01](/modelagem/agil/nfr_framework.md) |   RF41    |
|   ELO66   |   RNF20   | [HSU01](/modelagem/agil/historia_usuario.md) |                 -                  |       -       | [CON02](/modelagem/agil/nfr_framework.md)  |   RF42    |
|   ELO67   |   RNF21   | [HSU01](/modelagem/agil/historia_usuario.md) |                 -                  |       -       |  [AD01](/modelagem/agil/nfr_framework.md)  |   RF38    |
|   ELO68   |   RNF22   | [HSU01](/modelagem/agil/historia_usuario.md) |                 -                  |       -       |  [AD02](/modelagem/agil/nfr_framework.md)  |   RF36    |

<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/ArthurGabrieel">Arthur Gabriel</a>, <a href="https://github.com/esteerlino">Ester Lino</a>, <a href="https://github.com/HeBatalha">Henrique Batalha</a> e <a href="https://github.com/IsaqueSH">Isaque Santos</a> </p></font>

## Referência Bibliografia

- Monografia - Miriam Sayão e Julio Prado Leite. Disponível em: <https://www.dbd.puc-rio.br/depto_informatica/05_20_sayao.pdf> Acesso em 22 de Junho de 2024

## Histórico de Versão

| Versão  | Data | Descrição | Autor(es) | Revisor(es) |
| -------- | ------ | ------ | ---------- | ---------- |
| 1.0 | 22/06/2024 | Criação do Documento | [Ester Lino](https://github.com/esteerlino) | [Isaque Santos](https://github.com/IsaqueSH) |
