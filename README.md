# 🏫 Sistema de Gerenciamento Escolar

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python&logoColor=white)
![Status](https://img.shields.io/badge/Status-Conclu%C3%ADdo-brightgreen?style=for-the-badge)

Um sistema em linha de comando (CLI) desenvolvido em Python para automatizar o controle acadêmico de estudantes. O programa gerencia o cadastro do aluno, valida o lançamento de notas por critérios, calcula frequências e gera um boletim completo de forma inteligente.

---

## 🎯 Principais Funcionalidades

* **📋 Cadastro Inteligente:** Coleta dados básicos do estudante e configura a quantidade de bimestres letivos (1 a 4) dinamicamente.
* **🛡️ Validação de Notas Dinâmica:** O sistema impede a digitação de notas fora do padrão escolar estabelecido (Caderno, Trabalho e Prova).
* **📉 Controle de Assiduidade:** Monitoramento de faltas absoluto e percentual baseado na carga horária da disciplina.
* **📊 Boletim Consolidado:** Geração de um relatório final limpo e formatado com a situação acadêmica detalhada em 6 disciplinas base.

---

## 📐 Regras de Negócio & Distribuição de Pontos

O sistema segue uma estrutura rígida de avaliação por bimestre, onde a nota máxima de cada período é **10.0 pontos**, distribuídos da seguinte forma:

| Avaliação | Pontuação Máxima | Descrição |
| :--- | :---: | :--- |
| **📓 Caderno** | 2.5 | Visto e organização das atividades de sala |
| **💼 Trabalho** | 2.5 | Projetos, pesquisas e atividades em grupo |
| **📝 Prova** | 5.0 | Avaliação formal individual |

### 🚦 Critérios de Aprovação

O software aplica automaticamente a lógica de aprovação baseada nas regras institucionais após o processamento das notas e faltas:
