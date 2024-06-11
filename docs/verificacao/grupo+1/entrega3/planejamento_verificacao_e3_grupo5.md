# Planejamento da Verificação da Especificação Suplementar do Grupo 5

## Introdução

A verificação desempenha um papel crucial para garantir a qualidade, confiabilidade e robustez no processo de desenvolvimento de software. Através da verificação, é possível identificar e corrigir falhas, erros e inconsistências desde as etapas iniciais do desenvolvimento, prevenindo problemas mais sérios que podem surgir posteriormente e gerar custos adicionais. Dessa forma, este documento apresenta o planejamento da verificação dos seguintes artefatos produzido pelo [Grupo 5](https://github.com/Requisitos-de-Software/2024.1-Sinesp_Cidadao): [Cenários](https://github.com/Requisitos-de-Software/2024.1-Sinesp_Cidadao/blob/main/docs/Modelagem/Cenarios.md), [Léxico](https://github.com/Requisitos-de-Software/2024.1-Sinesp_Cidadao/blob/main/docs/Modelagem/Lexico.md), [Caso de Uso](https://github.com/Requisitos-de-Software/2024.1-Sinesp_Cidadao/blob/main/docs/Modelagem/Casos_De_uso.md) e [Especificação Suplementar](https://github.com/Requisitos-de-Software/2024.1-Sinesp_Cidadao/blob/main/docs/Modelagem/especificacao_suplementar.md) 


## Metodologia

Para garantir a qualidade dos artefatos do Grupo 5, empregaremos a metodologia de Inspeção idealizada por [Fagan](#ancora2). Essa técnica estruturada, aclamada por sua meticulosidade, visa a revisão profunda de códigos e demais elementos do software. Com a Inspeção de Fagan, o foco principal reside na identificação e correção minuciosa de falhas durante as etapas iniciais do desenvolvimento. Essa abordagem proativa contribui significativamente para a redução de custos e otimização do tempo, além de elevar a confiabilidade e robustez do software final.

A metodologia se destaca por seus pilares fundamentais:

- Sistematização: A inspeção segue um conjunto de etapas rígidas e bem definidas, garantindo uniformidade e consistência no processo de revisão.
- Rigor: A análise meticulosa dos artefatos busca detectar falhas de diversas naturezas, desde erros simples até falhas complexas e sutis.
- Detecção Precoce: A identificação de defeitos nas fases iniciais do desenvolvimento minimiza o retrabalho e os custos, otimizando o cronograma do projeto.
- Aprimoramento Contínuo: As falhas encontradas servem como base para o aperfeiçoamento contínuo dos processos e da qualidade do software como um todo.

Vantagens da Inspeção de Fagan:

- Maior qualidade do software
- Redução de custos
- Otimização do tempo
- Maior confiabilidade e robustez do software
- Detecção precoce de erros
- Melhoria dos processos de desenvolvimento


### Participantes

Os responsáveis por essa verificação são os integrantes do [Grupo 4](https://github.com/Requisitos-de-Software/2024.1-Gov.br): [Arthur Gabriel](https://github.com/ArthurGabrieel), [Caio Berg](https://github.com/Caio-bergbjj), [Carlos Gabriel](https://github.com/TheCarlosRamos), [Ester Lino](https://github.com/esteerlino), [Henrique Batalha](https://github.com/HeBatalha), [Isaque Santos](https://github.com/IsaqueSH) e [Thiago Freitas](https://github.com/thiagorfreitas).

### Objetos de Verificação

Os artefatos alvo dessa verificação são:

[Cenários](https://github.com/Requisitos-de-Software/2024.1-Sinesp_Cidadao/blob/main/docs/Modelagem/Cenarios.md)
 
[Léxico](https://github.com/Requisitos-de-Software/2024.1-Sinesp_Cidadao/blob/main/docs/Modelagem/Lexico.md)

[Caso de Uso](https://github.com/Requisitos-de-Software/2024.1-Sinesp_Cidadao/blob/main/docs/Modelagem/Casos_De_uso.md) 

[Especificação Suplementar](https://github.com/Requisitos-de-Software/2024.1-Sinesp_Cidadao/blob/main/docs/Modelagem/especificacao_suplementar.md) 



<center>

**Tabela 1** - Cronograma do planejamento da verificação dos artefatos.

| N°  | Compromisso                                           | Responsável             | Data       |
| --- | ----------------------------------------------------- | ----------------------- | ---------- |
| 01  | Página com o planejamento da verificação da entrega 03| Carlos                  | 10/06/2024 |
| 02  | Casos de uso                                          | Caio e Isaque           | 10/06/2024 |
| 03  | Léxicos                                               | Ester                   | 10/06/2024 |
| 04  | Especificação Suplementar                             | Arthur e Thiago         | 10/06/2024 |
| 05  | Cenários                                              | Carlos e Henrique       | 10/06/2024 |


Fonte: [Carlos Gabriel](https://github.com/TheCarlosRamos)

</center>

## Checklists

As checklists foram construídas levando em conta os padrões esperados para os artefatos que estão disponíveis nas referências bibliográficas.

<center>

**Tabela 2** - Checklist para os Itens Gerais.




| ID  | Descrição                                                                                              | Avaliação | Observação | Referência |
| --- | ------------------------------------------------------------------------------------------------------ | --------- | ----------- | ---------- |
| 1   | O artefato possui introdução?                                                                          |           |             |[1](#ancora1)|
| 2   | O artefato possui referência bibliográfica?                                                            |           |             |[1](#ancora1)|
| 3   | O artefato possui histórico de versão com o id e descrição das versões, data, autores e revisores?     |           |             |            |
| 4   | As tabelas e imagens possuem legendas e fontes padronizadas?                                           |           |             |[1](#ancora1)|
| 5   | As tabelas são referenciadas no texto?                                                                 |           |             |[1](#ancora1)|


Fonte: [Carlos Gabriel](https://github.com/TheCarlosRamos)

</center>

## ALéxicos

<font><p style="text-align: center">**Tabela 2:** Checklist para a verificação dos Léxicos.</p></font>

| Número | Ponto | Rastreabilidade |
| :----: | :---: | :-------------: |
| 1 | Os léxicos definem os usuários da aplicação? | [3](#ref3) |
| 2 | Os léxicos utilizam a estrutura verbo, objeto, estado e/ou sujeito? | [3](#ref3) |
| 3 | Existem ligações entre os léxicos, atravpes de hiperlinks?| [3](#ref3) |
| 4 | Cada léxico contém classificação, noção, impacto e sinônimos? | [3](#ref3) |
| 5 | A noção e o impacto de cada léxico estão corretos? | [3](#ref3) |
| 5 | A classificação de cada léxico está correta? | [3](#ref3) |

<div align="center">Autor(a): <a href="https://github.com/esteerlino">Ester Lino</a></div>

## Referências Bibliográficas

<a id="ref1"></a>
1. Normas ABNT: 2023. Disponível em: <a href="https://www.normasabnt.org/normas-abnt-2023/">https://www.normasabnt.org/normas-abnt-2023/</a>. Acesso em: 09 de Junho de 2024.

<a id="ref2"></a>
2. FAGAN, Michael E. Design and Code Inspections to Reduce Errors in Program Development. 1976.

<a id="ref3"></a>
3. Sayão, M.; Carvalho, G. R. de. Construção do léxico de aplicações. In: INTERNATIONAL JOINT CONFERENCE IBERAMIA/SBIA/SBRN, 4., 2006, Ribeirão Preto. Proceedings of the International Joint Conference IBERAMIA/SBIA/SBRN 2006 - 4th Workshop in Information and Human Language Technology (TIL’2006). Ribeirão Preto: 2006. p. 1-12.

## Histórico de versão

| Versão | Data | Descrição | Responsáveis | Revisor |
| :----: | :--: | :-----------------------------------------------------: | :----------------------------------------------------------------------------------------------: | :----------------------------------------------: |
|  1.0   | 09/06/2024 | Versão inicial do documento  | [Carlos Gabriel](https://github.com/TheCarlosRamos) | [Arthur Gabriel](ArthurGabrieel), [Caio Berg](https://github.com/Caio-bergbjj), [Ester Lino](https://github.com/esteerlino), [Henrique Batalha](https://github.com/HeBatalha), [Isaque Santos](https://github.com/IsaqueSH), [Thiago Freitas](https://github.com/thiagorfreitas)  |
|  1.1  | 10/06/2024 | Checklist de Léxicos  | [Ester Lino](https://github.com/esteerlino) | [Arthur Gabriel](ArthurGabrieel), [Caio Berg](https://github.com/Caio-bergbjj), [Ester Lino](https://github.com/esteerlino), [Henrique Batalha](https://github.com/HeBatalha), [Isaque Santos](https://github.com/IsaqueSH), [Thiago Freitas](https://github.com/thiagorfreitas)  |

