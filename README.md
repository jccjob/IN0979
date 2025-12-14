# IN0979
# Author: João Job
# 14 de dezembro de 2025
Conteúdo para construção do artigo referente ao Mining Challenge  do https://2026.msrconf.org/ para a disciplina IR0979 - Tópicos avançados em Engenharia de Software 2 (Mineração de repositório de software) do CIn - Centro de Informática da UFPE - Universidade Federal de Pernambuco.

# Descrição dos arquivos:

dataset_PR_filtrado.xlsx: dataset final com todas as informações utilizadas para a construção do artigo.

Arquivos *.omv: arquivos contendo os scripts utilizados na ferramente https://cloud.jamovi.org/ para realização dos testes estatísticos

pr_dominancia.xlsx: tabela intermediária utilizada para classificação das pr_id e o tipo de natureza crítica dominante (mandatório ou neutro)

pr_review_comments.xlsx: tabela contendo os cometários das review, classificação entre o tipo de agente (humano ou bot) a qual pr_id se refere e o status da PR.

pr_review_comments_classificado.xlsx: tabela contendo os cometários de revisão e classificados quanto a natureza critica, tipo comentário (bug, design, crítico, estilo, teste etc) e o rank de classificação por criticidade (1, 2 e 3).

v3-Classificação_review_pr.ipynb: código fonte utilizado para auxiliar na classificação dos comentários das PRs
