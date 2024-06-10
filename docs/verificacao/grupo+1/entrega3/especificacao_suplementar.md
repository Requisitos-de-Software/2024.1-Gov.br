# Verificação do Artefato Especificação Suplementar

## Introdução

Este documento apresenta os resultados da verificação por inspeção realizada sobre o artefato [Especificação Suplementar](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/Modelagem/especificacao_suplementar/) elaborado pelo Grupo 5 na disciplina de Requisitos de Software.

## Metodologia

A verificação foi realizada por meio de uma inspeção detalhada, utilizando dois checklists: um geral, aplicável a todos os artefatos, e um específico para o artefato em questão. Cada item dos checklists foi avaliado e, em caso de problemas, foram registradas as respectivas observações na seção de problemas encontrados. A metodologia e o planejamento da verificação foram definidos no documento de Planejamento da Verificação.

## Resultados

### Checklist para os Itens Gerais

<table>
  <thead>
    <tr>
      <th>ID</th>
      <th>Descrição</th>
      <th>Avaliação</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>O artefato possui um histórico de versão padronizado, incluindo data, descrição, autores e revisores?</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>2</td>
      <td>O artefato inclui bibliografia ou referências bibliográficas?</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>3</td>
      <td>As referências bibliográficas seguem a ordem de citação no texto?</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>4</td>
      <td>Todas as referências bibliográficas são citadas no texto?</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>5</td>
      <td>O artefato possui uma introdução clara e completa?</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>6</td>
      <td>Todas as tabelas possuem legendas e fontes padronizadas?</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>7</td>
      <td>Todas as tabelas são referenciadas no texto?</td>
      <td>Sim</td>
    </tr>
  </tbody>
</table>


Autor: [Arthur Gabriel](https://github.com/ArthurGabrieel), 2024.

## Checklist Específico da Verificação

<table>
  <thead>
    <tr>
      <th>ID</th>
      <th>Descrição</th>
      <th>Avaliação</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>9</td>
      <td>O artefato contém a especificação suplementar completa?</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>10</td>
      <td>A especificação suplementar segue o modelo FURPS+?</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>11</td>
      <td>O artefato possui um tópico de Funcionalidade com requisitos testáveis?</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>12</td>
      <td>O artefato possui um tópico de Usabilidade com requisitos testáveis?</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>13</td>
      <td>Os requisitos facilitam as tarefas realizadas pelos usuários?</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>14</td>
      <td>O artefato possui um tópico de Confiabilidade?</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>15</td>
      <td>Os requisitos aumentam a confiabilidade do sistema?</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>16</td>
      <td>O artefato especifica o Tempo Médio entre Falhas (MTBF)?</td>
      <td>Não</td>
    </tr>
    <tr>
      <td>17</td>
      <td>O artefato especifica o Tempo Médio para Reparos (MTTR)?</td>
      <td>Não</td>
    </tr>
    <tr>
      <td>18</td>
      <td>Os requisitos relacionados à segurança são apresentados?</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>19</td>
      <td>O artefato possui um tópico de Desempenho com requisitos testáveis?</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>20</td>
      <td>Os requisitos sobre tempos de resposta são apresentados com tempos especificados?</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>21</td>
      <td>O artefato especifica tempo de resposta de transação (médio, máximo)?</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>22</td>
      <td>O artefato especifica taxa de transferência (ex: transações por segundo)?</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>23</td>
      <td>Os requisitos sobre a disponibilidade são apresentados?</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>24</td>
      <td>O artefato possui um tópico de Suportabilidade com requisitos testáveis?</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>25</td>
      <td>Os sistemas operacionais suportados pelo sistema são apresentados?</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>26</td>
      <td>O artefato possui um tópico de Restrições de Design com requisitos testáveis?</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>27</td>
      <td>Os requisitos especificam ou restringem o design do sistema?</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td>28</td>
      <td>O artefato possui um tópico de Requisitos de Implementação com requisitos testáveis?</td>
      <td>Sim</td>
    </tr>
  </tbody>
</table>

Autor: [Arthur Gabriel](https://github.com/ArthurGabrieel), 2024.

## Problemas Encontrados
### Lista de Problemas e Análise

- ID 16: O artefato não especifica o Tempo Médio entre Falhas (MTBF).
- ID 17: O artefato não define o Tempo Médio para Reparos (MTTR).

### Solução

- ID 16: Recomenda-se adicionar a métrica MTBF como um Requisito de Confiabilidade.
- ID 17: Recomenda-se incluir o MTTR como um Requisito de Confiabilidade.

## Referências Bibliográficas

1. SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 13. Apresentação Power Point. Disponível em: https://aprender3.unb.br/pluginfile.php/2845007/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf. Acesso em: 10 de junho de 2024.
2. SINESP. [Especificação Suplementar](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/Modelagem/especificacao_suplementar/), FGA, GAMA, 2024. Acesso em: 10 de junho de 2024.

## Histórico de Versões

| Versão | Data       | Descrição          | Autor(es)                                                                 | Revisor(es) |
| ------ | ---------- | ------------------ | ------------------------------------------------------------------------- | ----------- |
| `1.0`  | 10/06/2024 | Criação da página. | [Arthur Gabriel](https://github.com/ArthurGabrieel) e [Thiago Freitas](https://github.com/thiagorfreitas) | [Arthur Gabriel](ArthurGabrieel), [Caio Berg](https://github.com/Caio-bergbjj), [Carlos Gabriel](https://github.com/TheCarlosRamos), [Ester Lino](https://github.com/esteerlino), [Henrique Batalha](https://github.com/HeBatalha), [Isaque Santos](https://github.com/IsaqueSH), [Thiago Freitas](https://github.com/thiagorfreitas) |