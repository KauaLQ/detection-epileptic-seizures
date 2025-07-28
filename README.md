<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=0F690F&height=120&section=header"/>

# Detecção de Crises Epilépticas em EEG com Recursive Least Squares (RLS)

[![DOI](https://img.shields.io/badge/DOI-10.5281%2Fexemplo.1234567-darkgreen)](https://doi.org/10.5281/zenodo.1234567)

Este repositório apresenta o resultado final do projeto de pesquisa e iniciação científica (PIBIC), denominado **"Detecção de crises epilépticas em EEG por meio de técnicas de Recursive Least Squares (RLS) e machine learning"**, que teve como participantes:

* **Tiago dos Santos Façanha** – Orientador
* **Kauã Lima de Queiroz** – Autor
* **Luana Stefany Moura dos Santos** – Coautora

## Sobre o Projeto

O objetivo deste projeto foi desenvolver uma abordagem leve e eficiente para **detecção automática de crises epilépticas** em sinais de EEG multicanal utilizando um algoritmo adaptativo modificado: o **degenerate RLS** (Recursive Least Squares com configuração degenerada).

A metodologia foi testada com sinais reais do banco de dados **CHB-MIT Scalp EEG**, contendo registros de pacientes pediátricos com epilepsia resistente a medicamentos. A técnica aplicada se destaca por sua **baixa complexidade computacional**, sendo ideal para uso em **sistemas embarcados e contextos com recursos limitados**, ao mesmo tempo que alcança **alta acurácia (>96%)** em diversos pacientes.

## Principais Características

* Algoritmo **degenerate RLS** com ordem zero e fator de esquecimento λ = 2
* Detecção de crises com base na **energia do erro adaptativo**
* Validação multicanal para **redução de falsos positivos**
* Avaliação com métricas padrão: **F1-score, precisão, revocação e acurácia**
* Código modular e compatível com Google Colab (execução em nuvem)
* Implementado em **Python**, utilizando bibliotecas como `numpy`, `scipy`, `mne` e `scikit-learn`

## Resultados

* F1-score médio: **0.96**
* Tempo de execução (por registro de EEG): **50 segundos a 3min45s**
* Desempenho robusto mesmo sem uso de aprendizado supervisionado

Comparado com métodos mais complexos que utilizam SVM, MLP ou redes neurais, o algoritmo proposto se mostrou competitivo, mantendo desempenho elevado com uma estrutura significativamente mais simples.

## Publicação

Este projeto resultou no artigo intitulado **"Application of a Degenerate RLS Algorithm for Epileptic Seizure Detection"**, **aprovado para apresentação no Workshop on Engineering Applications (WEA 2025)**.

🔗 \[Link para o artigo publicado – adicionar aqui quando disponível]

## Como Citar

Se você usar este projeto em sua pesquisa, cite da seguinte forma:

> Queiroz, K. L., Façanha, T. S., & Santos, L. S. M. (2025). *Application of a Degenerate RLS Algorithm for Epileptic Seizure Detection*. Workshop on Engineering Applications (WEA 2025).

## Contate-nos
[![Email - Tiago](https://img.shields.io/badge/email-tiago.facanha%40ifce.edu.br-blue)](mailto:tiago.facanha@ifce.edu.br) 

[![Email - Kauã](https://img.shields.io/badge/email-kaua.queiroz09%40aluno.ifce.edu.br-red)](mailto:kaua.queiroz09@aluno.ifce.edu.br)

[![Email - Luana](https://img.shields.io/badge/email-luana.stefany.moura07%40aluno.ifce.edu.br-violet)](mailto:luana.stefany.moura07@aluno.ifce.edu.br)
