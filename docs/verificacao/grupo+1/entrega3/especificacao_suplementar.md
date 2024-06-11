# Verificação do Artefato Especificação Suplementar

## Introdução

Este documento apresenta os resultados da verificação por inspeção realizada sobre o artefato [Especificação Suplementar](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/Modelagem/especificacao_suplementar/) elaborado pelo Grupo 5 na disciplina de Requisitos de Software.

## Metodologia

A verificação foi realizada por meio de uma inspeção detalhada, utilizando dois checklists: um geral, aplicável a todos os artefatos, e um específico para o artefato em questão. Cada item dos checklists foi avaliado e, em caso de problemas, foram registradas as respectivas observações na seção de problemas encontrados. A metodologia e o planejamento da verificação foram definidos no documento de Planejamento da Verificação.

## Resultados

## Checklist

Aqui está a tabela convertida para markdown:

| ID  | Descrição                                                                         | Avaliação |
|-----|-----------------------------------------------------------------------------------|-----------|
| 1   | O artefato contém a especificação suplementar completa?                           | Sim       |
| 2   | A especificação suplementar segue o modelo FURPS+?                                | Sim       |
| 3   | O artefato possui um tópico de Funcionalidade com requisitos testáveis?           | Sim       |
| 4   | O artefato possui um tópico de Usabilidade com requisitos testáveis?              | Sim       |
| 5   | Os requisitos facilitam as tarefas realizadas pelos usuários?                     | Sim       |
| 6   | O artefato possui um tópico de Confiabilidade?                                    | Sim       |
| 7   | Os requisitos aumentam a confiabilidade do sistema?                               | Sim       |
| 8   | O artefato especifica o Tempo Médio entre Falhas (MTBF)?                          | Não       |
| 9   | O artefato especifica o Tempo Médio para Reparos (MTTR)?                          | Não       |
| 10  | Os requisitos relacionados à segurança são apresentados?                          | Sim       |
| 11  | O artefato possui um tópico de Desempenho com requisitos testáveis?               | Sim       |
| 12  | Os requisitos sobre tempos de resposta são apresentados com tempos especificados? | Sim       |
| 13  | O artefato especifica tempo de resposta de transação (médio, máximo)?             | Sim       |
| 14  | O artefato especifica taxa de transferência (ex: transações por segundo)?         | Sim       |
| 15  | Os requisitos sobre a disponibilidade são apresentados?                           | Sim       |
| 16  | O artefato possui um tópico de Suportabilidade com requisitos testáveis?          | Sim       |
| 17  | Os sistemas operacionais suportados pelo sistema são apresentados?                | Sim       |
| 18  | O artefato possui um tópico de Restrições de Design com requisitos testáveis?     | Sim       |
| 19  | Os requisitos especificam ou restringem o design do sistema?                      | Sim       |
| 20  | O artefato possui um tópico de Requisitos de Implementação com requisitos testáveis?| Sim     |

Autor: [Arthur Gabriel](https://github.com/ArthurGabrieel) e [Thiago Freitas](https://github.com/thiagorfreitas), 2024.

## Problemas Encontrados
### Lista de Problemas e Análise

- ID 08: O artefato não especifica o Tempo Médio entre Falhas (MTBF).
- ID 09: O artefato não define o Tempo Médio para Reparos (MTTR).

### Solução

- ID 08: Recomenda-se adicionar a métrica MTBF como um Requisito de Confiabilidade.
- ID 09: Recomenda-se incluir o MTTR como um Requisito de Confiabilidade.

## Referências Bibliográficas

1. SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 13. Apresentação Power Point. Disponível em: https://aprender3.unb.br/pluginfile.php/2845007/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf. Acesso em: 10 de junho de 2024.
2. SINESP. [Especificação Suplementar](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/Modelagem/especificacao_suplementar/), FGA, GAMA, 2024. Acesso em: 10 de junho de 2024.

## Histórico de Versões

| Versão | Data       | Descrição          | Autor(es)                                                                 | Revisor(es) |
| ------ | ---------- | ------------------ | ------------------------------------------------------------------------- | ----------- |
| `1.0`  | 10/06/2024 | Criação da página. | [Arthur Gabriel](https://github.com/ArthurGabrieel) e [Thiago Freitas](https://github.com/thiagorfreitas) | [Arthur Gabriel](ArthurGabrieel), [Caio Berg](https://github.com/Caio-bergbjj), [Carlos Gabriel](https://github.com/TheCarlosRamos), [Ester Lino](https://github.com/esteerlino), [Henrique Batalha](https://github.com/HeBatalha), [Isaque Santos](https://github.com/IsaqueSH), [Thiago Freitas](https://github.com/thiagorfreitas) |