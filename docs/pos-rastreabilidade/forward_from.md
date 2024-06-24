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
| RF03 | - | - | - | [L01](modelagem/lexicos.md#léxicos-do-tipo-verbo) | [EP04](modelagem/agil/backlog.md#Épicos) | [T04](modelagem/agil/backlog.md#temas) | [HSU14](modelagem/agil/backlog.md#histórias-de-usuário) | - | Em desenvolvimento |
| RF04 | - | [UC01] | - | [L01] | [EP04] | [T05] | [HSU14] | - | Em desenvolvimento |
| RF05 | [Cenário 6] | - | [CON04*] | - | - | - | - | [NFR1*] | Em desenvolvimento |
| RF06 | - | [UC06] | [RD01*] | [L08] | - | - | - | [NFR06*] | Em desenvolvimento |
| RF07 | - | [UC04] | - | [L03] | [EP03] | [T03] | [HSU07] [HSU09] | - | Em desenvolvimento |
| RF08 | [Cenário 3] | - | - | - | [EP04] | [T04] | [HSU14] [HSU15] | - | Sim |
| RF09 | [Cenário 1] | [UC07] [UC08] [UC09] | - | [L02] [L04] [L06] [L10] [L14] | [EP01] | [T01] | [HSU01] [HSU02] [HSU03] [HSU05] [HSU06] [HSU10] | - | Em desenvolvimento |
| RF10 | - | [UC11] [UC12] | - | - | - | - | - | - | Em desenvolvimento |
| RF11 | - | [UC01] [UC02] [UC03] | - | [L01] [L05] | [EP04] | [T04] | [HSU14] | - | Sim |
| RF12 | - | - | - | - | - | - | - | - | - |
| RF13 | - | - | - | - | - | - | - | - | - |
| RF14 |  |  |  |  |  |  |  |  |  |
| RF15 | - | [UC08] [UC09] [UC13] | - |  |  |  |  |  |  | 
| RF16 | - | - | - | - | - | - | - | - | - |
| RF17 | - | - | - | - | - | - | - | - | - |
| RF18 | - | [UC14] | [USA06] | [L06] | [EP01] | [T01] | [HSU03] | [NFR05] | Sim |
| RF19 |  |  |  |  |  |  |  |  |  |
| RF20 |  |  |  |  |  |  |  |  |  |
| RF21 | [Cenário 2] [Cenário 4] [Cenário 5] | [UC02] [UC05] [UC07] [UC10] | - | [L15] | [EP02] | [T02] | [HSU04] [HSU08] | - | Em desenvolvimento  |
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

| Nº do Elo | Requisito | Satisfação | Recurso | Representação | Alocação | Agregação |
| :-------: | :-------: | :--------: | :-----: | :-----------: | :------: | :-------: |
|   ELO01   |   RF01    |   HSU14    |  UC01   |               |  NFR03   |   RF07    |
|   ELO02   |   RF02    |   HSU15    |  UC02   |               |  NFR06   |   RF09    |
|   ELO03   |   RF03    |            |  UC02   |               |  NFR01   |   RF18    |
|   ELO04   |   RF04    |            |         |               |  NFR01   |           |
|   ELO05   |   RF05    |            |         |               |  NFR01   |   RF08    |
|   ELO06   |   RF06    |   HSU10    |  UC02   |               |  NFR01   |   RF42    |
|   ELO07   |   RF07    |            |  UC01   |               |  NFR01   |   RF01    |
|   ELO08   |   RF08    |            |  UC04   |               |  NFR02   |   RF04    |
|   ELO09   |   RF09    |   HSU15    |  UC02   |               |  NFR06   |   RF02    |
|   ELO10   |   RF10    |HSU01, HSU02, HSU03, HSU06|  UC07   |    |  NFR02   |   RF14    |
|   ELO11   |   RF11    |            |  UC11   |               |  NFR01   |           |
|   ELO12   |   RF12    |            |  UC01   |               |  NFR03   |           |
|   ELO13   |   RF13    |   HSU14    |  UC01   |               |  NFR03   |   RF01    |
|   ELO14   |   RF14    |   HSU01     |  UC07   |               |  NFR02   |   RF10    |
|   ELO15   |   RF15    |            |  UC10   |               |  NFR03   |           |
|   ELO16   |   RF16    |   HSU10    |  UC07   |               |  NFR01   |           |
|   ELO17   |   RF17    |            |  UC01   |               |  NFR03   | RF01, RF13|
|   ELO18   |   RF18    |            |  UC13   |               |  NFR06   |   RF03    |
|   ELO19   |   RF19    |            |  UC14   |               |  NFR03   |   RF30       |
|   ELO20   |   RF20    |            |         |               |  NFR01   |           |
|   ELO21   |   RF21    |            |         |               |  NFR02   |           |
|   ELO22   |   RF22    |            |         |               |  NFR02   |           |
|   ELO23   |   RF23    |            |         |               |  NFR02   |           |
|   ELO24   |   RF24    |            |         |               |  NFR02   |           |
|   ELO25   |   RF25    |            |         |               |  NFR01   |           |
|   ELO26   |   RF26    |   HSU14    |  UC01   |               |  NFR01   |           |
|   ELO27   |   RF27    |            |         |               |  NFR02   |           |
|   ELO28   |   RF28    |            |         |               |  NFR03   |           |
|   ELO29   |   RF29    |            |         |               |  NFR03   |           |
|   ELO30   |   RF30    |            |  UC14   |               |  NFR03   |    RF19   |
|   ELO31   |   RF31    |            |         |               |  NFR03   |   RF30    |
|   ELO32   |   RF32    |            |   UC10  |               |  NFR03   |RF37       |
|   ELO33   |   RF33    |            |         |               |  NFR03   |           |
|   ELO34   |   RF34    |            |         |               |  NFR03   |           |
|   ELO35   |   RF35    |            |         |               |  NFR02   |           |
|   ELO36   |   RF36    |            |         |               |  NFR01   |           |
|   ELO37   |   RF37    |            |  UC10   |               |  NFR02   |    RF32   |
|   ELO38   |   RF38    |            |  UC07   |               |  NFR01   |           |
|   ELO39   |   RF39    |            |  UC07   |               |  NFR02   |           |
|   ELO40   |   RF40    |            |         |               |  NFR01   |           |
|   ELO41   |   RF41    |            |         |               |  NFR01   |           |
|   ELO42   |   RF42    |            |         |               |  NFR02   |           |

<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/ArthurGabrieel">Arthur Gabriel</a>, <a href="https://github.com/esteerlino">Ester Lino</a>, <a href="https://github.com/HeBatalha">Henrique Batalha</a> e <a href="https://github.com/IsaqueSH">Isaque Santos</a> </p></font>

## Elos - Requisitos Não Funcionais

<font><p style="text-align: center">**Tabela 4:** Elos dos requisitos não funcionais</p></font>

| Nº do Elo | Requisito | Satisfação | Recurso | Representação | Alocação | Agregação |
|:---------:|:---------:|:----------:|:-------:|:-------------:|:--------:|:---------:|
|   ELO47   |   RNF01   |            |         |               |          |           |
|   ELO48   |   RNF02   |            |         |               |          |           |
|   ELO49   |   RNF03   |            |         |               |          |           |
|   ELO50   |   RNF04   |            |         |               |          |           |
|   ELO51   |   RNF05   |            |         |               |          |           |
|   ELO52   |   RNF06   |            |         |               |          |           |
|   ELO53   |   RNF07   |            |         |               |          |           |
|   ELO54   |   RNF08   |            |         |               |          |           |
|   ELO55   |   RNF09   |            |         |               |          |           |
|   ELO56   |   RNF10   |            |         |               |          |           |
|   ELO57   |   RNF11   |            |         |               |          |           |
|   ELO58   |   RNF12   |            |         |               |          |           |
|   ELO59   |   RNF13   |            |         |               |          |           |
|   ELO60   |   RNF14   |            |         |               |          |           |
|   ELO61   |   RNF15   |            |         |               |          |           |
|   ELO62   |   RNF16   |            |         |               |          |           |
|   ELO63   |   RNF17   |            |         |               |          |           |
|   ELO64   |   RNF18   |            |         |               |          |           |
|   ELO65   |   RNF19   |            |         |               |          |           |
|   ELO66   |   RNF20   |            |         |               |          |           |
|   ELO67   |   RNF21   |            |         |               |          |           |
|   ELO68   |   RNF22   |            |         |               |          |           |

<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/ArthurGabrieel">Arthur Gabriel</a>, <a href="https://github.com/esteerlino">Ester Lino</a>, <a href="https://github.com/HeBatalha">Henrique Batalha</a> e <a href="https://github.com/IsaqueSH">Isaque Santos</a> </p></font>

## Referência Bibliografia

- Monografia - Miriam Sayão e Julio Prado Leite. Disponível em: <https://www.dbd.puc-rio.br/depto_informatica/05_20_sayao.pdf> Acesso em 22 de Junho de 2024

## Histórico de Versão

| Versão  | Data | Descrição | Autor(es) | Revisor(es) |
| -------- | ------ | ------ | ---------- | ---------- |
| 1.0 | 22/06/2024 | Criação do Documento | [Ester Lino](https://github.com/esteerlino) | [Isaque Santos](https://github.com/IsaqueSH) |
