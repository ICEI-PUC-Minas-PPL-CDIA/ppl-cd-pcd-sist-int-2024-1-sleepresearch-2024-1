# Artefatos Relativos à Coleta e Preparação de Dados
Este diretório contém artefatos relacionados à modelagem de dados do projeto, incluindo dados brutos, transformados e enriquecidos, além de resultados intermediários e finais.

## Dados Brutos

### `Student Stress Factors.csv` dados brutos sobre fatores de estresse em estudantes, incluindo:

- Qualidade do sono
- Dores de cabeça
- Desempenho acadêmico
- Carga de estudo
- Atividades extracurriculares
- Níveis de estresse

### `Student_Performance.csv` dados brutos sobre o desempenho dos estudantes, incluindo:

- Horas de estudo
- Notas anteriores
- Participação em atividades extracurriculares
- Horas de sono
- Número de simulados praticados
- Índice de desempenho
- Dados Transformados e Resultados Intermediários

### Tabela final: 

**performance_data_Index_convertido_por_faixas.csv** Similar ao performance_data_convertido_por_faixas.csv, mas com a seguinte diferença:

- performance_index foi convertido para um valor categórico de faixa numérico.

### Tabelas teste:

**performance_data_converted.csv** versão do Student_Performance.csv com as seguintes transformações:


- A coluna Extracurricular Activities foi convertida para valores numéricos (0 para "Não" e 1 para "Sim").
- performance_index foi transformado de `float` para `int`.

**performance_data_convertido_por_faixas.csv** Versão do performance_data_converted.csv com as seguintes transformações:

- As variáveis numéricas foram discretizadas em faixas.

**performance_data_convertido_por_faixas_sem_Previous.csv** Versão do performance_data_convertido_por_faixas.csv com as seguintes transformações:

- A coluna Previous Scores foi removida.