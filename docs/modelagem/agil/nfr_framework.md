# NFR Framework

## Introdução

O NFR(Non-Functional Requirements) Framework é uma abordagem muito importante no desenvolvimento de software e sistemas, pois é utilizado para selecionar, organizar, analisar e gerenciar requisitos não funcionais em projetos de software. Diferentemente dos requisitos funcionais, que descrevem o que o sistema deve fazer, os requisitos não funcionais descrevem como o sistema deve se comportar, incluindo aspectos como desempenho, segurança, usabilidade, confiabilidade e escalabilidade, e são fundamentais para o sucesso de um sistema de software, especificando os critérios de qualidade que o sistema deve atender, além das funcionalidades básicas. 

O framework utiliza o conceito de softgoal, que defini-se como um objetivo que descreve uma qualidade desejada ou um requisito não funcional do sistema. Diferente dos objetivos funcionais, que têm critérios de satisfação claros e específicos, os softgoals são mais subjetivos e podem não ter uma definição precisa de quando estão totalmente satisfeitos. Os softgoals representam os requisitos não funcionais, e podem estar inter-relacionados, expressando a influência de um softgoal em outro. O Framework também possui um método de análise qualitativa para decidir os status dos softgoals, dado que outros softgoals relacionados foram ou não satisfeitos.

O NFR Framework funciona através da construção e revisão incremental de um Softgoal Interdependency Graph(SIG), ou Gráfico de Interdependência de Softgoals. Este gráfico registra as considerações dos desenvolvedores sobre os softgoals e suas interdependências, armazenando graficamente as decisões de desenvolvimento, incluindo Requisitos Não-Funcionais, alternativas e justificativas. Os SIGs armazenam um registro completo das decisões de desenvolvimento e da lógica do projeto de forma gráfica e concisa.

Os softgoals podem ser divididos em três tipos, sendo eles:

- Softgoals NFR: representam os Requisitos Não-Funcionais e podem estar inter-relacionados, organizados em catálogos e apresentados de forma hierárquica durante o desenvolvimento do projeto.

- Softgoals de Operacionalização: Representam abordagens de implementação para atender aos softgoals NFR ou outros softgoals de operacionalização. Essas abordagens englobam operações, processos, representações de dados, estruturas e restrições no sistema alvo, visando atender às necessidades indicadas pelos softgoals NFR e de operacionalização.

- Softgoals de Afirmação: permitem que as características do domínio, como prioridades e carga de trabalho, sejam consideradas e refletidas no processo de tomada de decisão. Eles justificam a priorização, refinamento e seleção de componentes dos softgoals, facilitando a revisão, a justificação e a mudança do sistema, além de melhorar a rastreabilidade.

O procedimento de avaliação verifica o grau de satisfação dos requisitos não funcionais por um conjunto de decisões, determinando se cada softgoal ou interdependência do SIG foi satisfatoriamente atendido. Para isso, são atribuídos rótulos como "satisfeito", "fracamente satisfeito", "negado", "fracamente negado", "conflitante" e "indeterminado". A análise dos softgoals de nível mais baixo na hierarquia de um SIG envolve decisões sobre aceitar ou negar alternativas no projeto. Essas decisões geram um conjunto inicial de rótulos, que são utilizados pelo procedimento de avaliação para determinar o impacto das decisões nos softgoals em níveis hierárquicos mais altos. Esse processo é repetido até chegar aos softgoals no nível mais alto do SIG.


## Metodologia 

## Bibliografia

-  SILVA, Reinaldo Antônio da. NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. Universidade Federal de Pernambuco, 2019. Disponível em: https://aprender3.unb.br/pluginfile.php/2845051/mod_resource/content/2/DISSERTA%C3%87%C3%83O%20Reinaldo%20Ant%C3%B4nio%20da%20Silva.pdf. Acesso em: 26 de maio de 2024.

## Histórico de Versão


| Versão |    Data    |                      Descrição                      |      Autor(es)      | Revisor(es)  |
| :----: | :--------: | :-------------------------------------------------: | :-----------------: | :----------: |
|  1.0  | 26/05/2024 | Versão Inicial  | [Carlos Gabriel](https://github.com/TheCarlosRamos), [Henrique Batalha](https://github.com/HeBatalha) e [Isaque Santos](https://github.com/IsaqueSH) | [Henrique Batalha](https://github.com/HeBatalha) |
