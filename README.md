# Análise de Segurança em Aplicações Web — SAST, SCA e DAST

Este repositório contém os artefatos produzidos para uma atividade prática de **Segurança em Aplicações Web**, envolvendo a aplicação de técnicas de análise estática, análise de dependências e análise dinâmica de segurança.

## Objetivo

A atividade teve como objetivo aplicar diferentes abordagens para identificação e análise de vulnerabilidades em aplicações web:

* **SAST (Static Application Security Testing)** com **Semgrep**;
* **SCA (Software Composition Analysis)** com **OSV-Scanner**;
* **DAST (Dynamic Application Security Testing)** com **Burp Suite**.

As vulnerabilidades identificadas foram analisadas considerando aspectos como **CWE**, **OWASP Top 10 2025**, **CVSS**, impacto, criticidade e possíveis medidas de remediação.

## Ferramentas utilizadas

* [Semgrep](https://semgrep.dev/)
* [OSV-Scanner](https://google.github.io/osv-scanner/)
* [Burp Suite](https://portswigger.net/burp)
* Git / GitHub
* Linux

## Estrutura da atividade

### 1. SAST — Semgrep

Foi realizada uma análise estática do código-fonte da aplicação **Broken Crystals**, utilizando o Semgrep.

O scan foi executado sobre:

```text
brokencrystals/src/
```

Os resultados foram exportados para análise e documentação das vulnerabilidades encontradas.

### 2. SCA — OSV-Scanner

Foi realizada uma análise das dependências e componentes utilizados pelo projeto **Broken Crystals** com o OSV-Scanner.

O objetivo foi identificar vulnerabilidades conhecidas associadas às dependências da aplicação e analisar CVEs selecionadas em maior detalhe.

### 3. DAST — Burp Suite

A etapa de análise dinâmica consistiu na resolução de um desafio da categoria **Web** da plataforma **Forge RSI**, utilizando o Burp Suite para interceptação e análise das requisições e respostas HTTP.

O procedimento completo, incluindo evidências e capturas de tela, está documentado no relatório da atividade.

## Conteúdo do repositório

Os arquivos deste repositório correspondem aos artefatos e evidências produzidos durante a execução da atividade, incluindo resultados das ferramentas utilizadas e o relatório final.

> Para a descrição detalhada da metodologia, análise das vulnerabilidades, classificações e procedimentos realizados, consulte o relatório disponibilizado neste repositório.

## Observação

Este repositório possui finalidade **exclusivamente acadêmica e educacional**. As análises e explorações descritas foram realizadas em ambientes destinados à prática de segurança da informação.

---



Feito com 💙 por Isis Lavor! Bons estudos.
