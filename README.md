# TCC: Análise de Sobrevida de Pacientes com Câncer de Mama na Paraíba

Repositório do Trabalho de Conclusão do Curso em Estatística da Universidade de Brasília.

Comparação entre modelos clássicos de análise de sobrevivência (Cox e Modelo de Mistura com Fração de Cura) com modelos baseados em redes neurais (DeepSurv e Redes Neurais com Pseudo-Valores) para análise do tempo de sobrevida de pacientes com câncer de mama no Estado da Paraíba.

## Estrutura do repositório

- dados: pré-processamento e preparação da base de dados.
- ajuste-modelos: implementação dos modelos utilizados na análise principal.
- avaliacao-modelos: cálculo das métricas de desempenho, predições e comparação entre os modelos.
- experimentos-complementares: arquiteturas alternativas, otimização de hiperparâmetros e demais experimentos realizados durante a pesquisa.

## Ambiente de execução

O projeto utiliza duas linguagens:

- R: pré-processamento, análise exploratória, modelos estatísticos e avaliação dos resultados.
- Python: treinamento das redes neurais.

Todos os scripts estão em formato Jupyter Notebook (.ipynb). A primeira célula de cada notebook indica o kernel a ser utilizado (Kernel: R ou Kernel: Python).
