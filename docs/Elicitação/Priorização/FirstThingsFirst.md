# First Things First

## Introdução

*First Things First* é uma técnica de gerenciamento de tempo que enfatiza a importância de completar as tarefas mais importantes primeiro. Esta técnica é baseada na ideia de que, para ser eficaz e produtivo, você deve se concentrar nos requisitos que têm o maior impacto em seus objetivos e resultados. Essa abordagem leva em consideração o custo, risco, benefício e penalidade relacionados a cada requisito e dessa forma define a prioridade associada.

## Metodologia

Descrição dos papeis:

- ***Gerente***: Responsável pelo processo e os requisitos mostrados.
- ***Desenvolvedor***: Membro da equipe de desenvolvimento, julga o custo e risco dos requisitos.
- ***Cliente***: Julga o benefício e penalidade dos requisitos.

<center>

**Tabela 1** - Lista de Participantes

| Nome                                                | Papel         |
| --                                                  | --            |
| [Henrique Batalha](https://github.com/HeBatalha)    | Mediador      |
| [Carlos Gabriel](https://github.com/TheCarlosRamos) | Mediador      |
| [Isaque Santos](https://github.com/IsaqueSH)        | Desenvolvedor |
| Doan Filho | Usuário |

**Fonte**: [Henrique Batalha](https://github.com/HeBatalha)

</center>

<br>

Reuniões gravadas:

- Entre um mediador e o desenvolvedor. Realizado em duas partes no dia 14/04/2024: 

<iframe width="460" height="215" src="https://www.youtube.com/embed/AbhOq84xDHg?si=ioeYwkhgkxXGSAcy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

- Entre um mediador e o usuário. Realizado no dia 14/04/2024:

<iframe width="460" height="215" src="https://www.youtube.com/embed/ck6qjMUL5pg?si=LrJ5g1htOfVdEmHg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<br>

Os seguintes passos foram realizados no processo *First Things First*:

**1.** Fazer uma lista de todos os requisitos. Se um requisito B depende de um requisito A, apenas o requisito A será analisado.

**2.** Estimar o benefício que cada requisito representa ao cliente em uma escala de 1 - menos significativo a 9 - mais significativo.

**3.** Estimar a penalidade que não-implementação de cada requisito causará em uma escala de 1 - nenhuma penalidade a 9 - grande penalidade.

**4.** Calcular o valor total: <div style="background-color: #17202A;; padding: 5px;"><center> (Benefício * Peso) + (Penalidade * Peso) </center></div>

**5.** Estimar o custo de implementação de cada requisito em uma escala de 1 - menos custoso a 9 - mais custoso.

**6.** Estimar o grau de risco de cada requisito em uma escala de 1 - menos risco/facilidade a 9 - representa maior dificuldade e viabilidade.

**7.** Calcular a prioridade de cada requisito: <div style="background-color: #17202A;; padding: 5px;"><center>Valor (Custo * Peso + Risco * Peso)</center></div>

**8.** Ordenar a tabela em ordem decrescente de prioridade.

## Resultados

<center>

**Tabela 2** - Resultado da priorização de requisitos


| ID | Benefício<br>Relativo | Penalidade<br>Relativa | Valor<br>total | Valor<br>(%) | Custo<br>Relativo | Custo<br>% | Risco<br>Relativo | Risco<br>% | Prioridade |
|------|--------------------|---------------------|-------------|------------|----------------|------------|----------------|-------------|--------------|
| ST16 | 9                  | 9                   | 27          | 2,089864159| 7              | 2,928870293| 5              | 2,702702703 | 2,116103564  |
| ST15 | 9                  | 9                   | 27          | 2,089864159| 7              | 2,928870293| 5              | 2,702702703 | 2,116103564  |
| ST09 | 9                  | 9                   | 27          | 2,089864159| 7              | 2,928870293| 5              | 2,702702703 | 2,116103564  |
| ST01 | 9                  | 9                   | 27          | 2,089864159| 7              | 2,928870293| 5              | 2,702702703 | 2,116103564  |
| RNF01| 9                  | 9                   | 27          | 2,089864159| 7              | 2,928870293| 6              | 3,243243243 | 2,116103564  |
| RNF04| 9                  | 9                   | 27          | 1,985370951| 8              | 3,347280335| 7              | 3,783783784 | 1,110298386  |
| RF04 | 9                  | 9                   | 27          | 2,089864159| 7              | 2,928870293| 8              | 4,324324324 | 2,116103564  |
| ST22 | 9                  | 9                   | 27          | 2,089864159| 7              | 2,928870293| 5              | 2,702702703 | 2,116103564  |
| ST10 | 8                  | 8                   | 24          | 1,880877743| 6              | 2,510460251| 4              | 2,162162162 | 2,117554859  |
| ST20 | 8                  | 8                   | 24          | 1,880877743| 6              | 2,510460251| 4              | 2,162162162 | 2,117554859  |
| ST18 | 8                  | 8                   | 24          | 1,880877743| 6              | 2,510460251| 4              | 2,162162162 | 2,117554859  |
| ST08 | 8                  | 8                   | 24          | 1,880877743| 6              | 2,510460251| 4              | 2,162162162 | 2,117554859  |
| ST04 | 8                  | 8                   | 24          | 1,880877743| 6              | 2,510460251| 4              | 2,162162162 | 2,117554859  |
| ST02 | 8                  | 8                   | 24          | 1,880877743| 6              | 2,510460251| 4              | 2,162162162 | 2,117554859  |
| RNF08| 9                  | 9                   | 27          | 1,985370951| 8              | 3,347280335| 7              | 3,783783784 | 1,110298386  |
| RNF06| 8                  | 9                   | 25          | 1,880877743| 7              | 2,928870293| 6              | 3,243243243 | 2,117554859  |
| RNF07| 8                  | 9                   | 25          | 1,880877743| 7              | 2,928870293| 6              | 3,243243243 | 2,117554859  |
| RF03 | 8                  | 9                   | 25          | 2,089864159| 5              | 2,092050209| 6              | 3,243243243 | 4,13061651   |
| RF11 | 8                  | 9                   | 25          | 1,985370951| 6              | 2,510460251| 5              | 2,702702703 | 3,124085684  |
| RF08 | 8                  | 8                   | 24          | 1,880877743| 6              | 2,510460251| 5              | 2,702702703 | 2,117554859  |
| RNF02| 8                  | 8                   | 24          | 1,985370951| 5              | 2,092050209| 4              | 2,162162162 | 3,124085684  |
| RNF05| 8                  | 8                   | 24          | 1,880877743| 6              | 2,510460251| 5              | 2,702702703 | 2,117554859  |
| RNF03| 7                  | 7                   | 21          | 1,567398119| 6              | 2,510460251| 5              | 2,702702703 | 1,111957009  |
| RF09 | 7                  | 7                   | 21          | 1,671891327| 5              | 2,092050209| 4              | 2,162162162 | 2,119420809  |
| RNF01| 9                  | 9                   | 27          | 2,089864159| 7              | 2,928870293| 6              | 3,243243243 | 2,116103564  |
| RNF04| 9                  | 9                   | 27          | 1,985370951| 8              | 3,347280335| 7              | 3,783783784 | 1,110298386  |
| RF06 | 7                  | 8                   | 22          | 1,880877743| 4              | 1,673640167| 4              | 2,162162162 | 4,13434841   |
| RF01 | 7                  | 8                   | 22          | 1,462904911| 8              | 3,347280335| 9              | 4,864864865 | 0,1044932079 |
| RF07 | 9                  | 9                   | 27          | 2,089864159| 7              | 2,928870293| 6              | 3,243243243 | 2,116103564  |
| ST17 | 8                  | 8                   | 24          | 1,880877743| 6              | 2,510460251| 4              | 2,162162162 | 2,117554859  |
| ST13 | 8                  | 8                   | 24          | 1,880877743| 6              | 2,510460251| 4              | 2,162162162 | 2,117554859  |
| ST11 | 7                  | 7                   | 21          | 1,671891327| 5              | 2,092050209| 3              | 1,621621622 | 2,119420809  |
| ST21 | 7                  | 7                   | 21          | 1,671891327| 5              | 2,092050209| 3              | 1,621621622 | 2,119420809  |
| ST19 | 7                  | 7                   | 21          | 1,671891327| 5              | 2,092050209| 3              | 1,621621622 | 2,119420809  |
| ST07 | 7                  | 7                   | 21          | 1,671891327| 5              | 2,092050209| 3              | 1,621621622 | 2,119420809  |
| ST05 | 7                  | 7                   | 21          | 1,671891327| 5              | 2,092050209| 3              | 1,621621622 | 2,119420809  |
| ST03 | 7                  | 7                   | 21          | 1,671891327| 5              | 2,092050209| 3              | 1,621621622 | 2,119420809  |
| ST14 | 7                  | 7                   | 21          | 1,671891327| 5              | 2,092050209| 3              | 1,621621622 | 2,119420809  |
| ST12 | 6                  | 6                   | 18          | 1,462904911| 4              | 1,673640167| 2              | 1,081081081 | 2,121908743  |
| ST06 | 6                  | 6                   | 18          | 1,462904911| 4              | 1,673640167| 2              | 1,081081081 | 2,121908743  |
| RF10 | 6                  | 7                   | 19          | 1,567398119| 4              | 1,673640167| 3              | 1,621621622 | 3,13061651   |
| RF02 | 6                  | 7                   | 19          | 1,567398119| 4              | 1,673640167| 4              | 2,162162162 | 3,13061651   |
| RF05 | 5                  | 6                   | 16          | 1,358411703| 3              | 1,255230126| 3              | 1,621621622 | 3,13584117   |
| TOTAL|                    |                     | 957         |            | 239            | 100        |   185          | 100         |              |

**Fonte**: [Carlos Gabriel](https://github.com/TheCarlosRamos)
</center>


## Bibliografia

- SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 07: Elicitação, Modelagem e Análise. Apresentação Power Point. Disponível em: https://aprender3.unb.br/pluginfile.php/2692779/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf. Acesso em: 13 de abril de 2024.

## Histórico de Versão

| Versão |    Data    |                      Descrição                      |      Autor(es)      | Revisor(es)  |
| :----: | :--------: | :-------------------------------------------------: | :-----------------: | :----------: |
|  1.0   | 13/04/2024 | Versão Inicial | [Henrique Batalha](https://github.com/HeBatalha), [Carlos Gabriel](https://github.com/TheCarlosRamos) | [Arthur Gabriel](https://github.com/ArthurGabrieel) |
|  1.1   | 15/04/2024 | Adição da tabela dos resultados | [Henrique Batalha](https://github.com/HeBatalha), [Carlos Gabriel](https://github.com/TheCarlosRamos) | [Arthur Gabriel](https://github.com/ArthurGabrieel) |
|  1.2   | 16/04/2024 | Adição dos vídeos das entrevistas | [Henrique Batalha](https://github.com/HeBatalha), [Carlos Gabriel](https://github.com/TheCarlosRamos) | [Arthur Gabriel](https://github.com/ArthurGabrieel) |

