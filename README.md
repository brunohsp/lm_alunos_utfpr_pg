# Análise de Desistência nos Cursos de BCC e ADS da UTFPR-PG

## Descrição

Este projeto faz parte das atividades acadêmicas da graduação em Ciência da Computação na Universidade Tecnológica Federal do Paraná, campus Ponta Grossa (UTFPR-PG). O principal objetivo é analisar o dataset fornecido para entender as causas do grande número de desistências nos cursos de Bacharelado em Ciência da Computação (BCC) e Análise e Desenvolvimento de Sistemas (ADS).

Além disso, o projeto visa aplicar modelos de aprendizado de máquina para prever alunos que têm alta probabilidade de desistência, ajudando a instituição a tomar medidas preventivas.

## Estrutura do Dataset

O arquivo Excel contém as seguintes planilhas:

1. **Relacao_Alunos**: Informações básicas sobre os alunos.
2. **Historico**: Histórico acadêmico dos alunos.
3. **Questionario_socioEconomico**: Respostas a um questionário socioeconômico aplicado aos alunos.

### Relacao_Alunos

Esta planilha contém dados demográficos e de identificação dos alunos, como:
- Matrícula
- Nome
- Curso
- Data de ingresso
- Situação atual (ativo, desistente, etc.)

### Historico

Esta planilha contém o histórico acadêmico dos alunos, incluindo:
- Matrícula
- Código da disciplina
- Nome da disciplina
- Nota
- Semestre
- Situação na disciplina (aprovado, reprovado, etc.)

### Questionario_socioEconomico

Esta planilha contém dados coletados a partir de um questionário socioeconômico, incluindo:
- Matrícula
- Informações sobre renda familiar
- Nível de escolaridade dos pais
- Condições de moradia
- Acesso a recursos educacionais (internet, computador, etc.)

## Objetivos do Projeto

1. **Análise Exploratória de Dados (EDA)**: Investigar o dataset para identificar padrões e correlações que possam indicar as causas da desistência nos cursos de BCC e ADS.
2. **Modelagem Preditiva**: Aplicar modelos de aprendizado de máquina para prever quais alunos têm maior probabilidade de desistir, utilizando os dados disponíveis.
3. **Recomendações**: Propor ações baseadas nos insights obtidos para reduzir a taxa de desistência nos cursos.

## Ferramentas Utilizadas

- Python e bibliotecas como Pandas, Scikit-learn, Matplotlib, e Seaborn para análise de dados e modelagem.
- Jupyter Notebooks para documentação e execução interativa de código.
- Ferramentas de versionamento de código, como Git e GitHub, para colaboração e controle de versões.
