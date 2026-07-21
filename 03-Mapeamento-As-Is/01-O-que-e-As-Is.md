# Capítulo 13 - Processo As Is

## Objetivo

Compreender o conceito de Processo As Is, sua importância em projetos de Business Process Management (BPM) e seu papel como base para a melhoria contínua.

---

# Introdução

Antes de propor qualquer melhoria, um consultor precisa entender exatamente como o processo funciona atualmente.

Essa etapa é conhecida como **As Is** ("Como Está") e representa o retrato fiel da operação.

Um dos maiores erros em projetos de melhoria é propor soluções sem compreender a realidade do processo.

O As Is elimina esse risco.

---

# O que significa As Is?

As Is é a documentação completa do processo em seu estado atual.

Ele representa:

- Como as atividades são executadas;
- Quem realiza cada atividade;
- Quais sistemas são utilizados;
- Quais documentos são gerados;
- Quais decisões são tomadas;
- Quais indicadores são acompanhados.

O objetivo não é corrigir o processo.

O objetivo é compreendê-lo.

---

# Por que o As Is é importante?

O mapeamento permite responder perguntas como:

- O processo está padronizado?
- Existem gargalos?
- Há retrabalho?
- Existem atividades sem valor agregado?
- Existem riscos?
- Existem etapas desnecessárias?
- Os SLAs são cumpridos?

Sem essas respostas, qualquer melhoria será baseada em hipóteses.

---

# Processo

Durante essa etapa, o consultor deve atuar como observador.

Ele evita sugerir melhorias antes de compreender completamente o funcionamento do processo.

Seu foco está em coletar evidências e validar informações.

---

# O que normalmente é identificado?

Durante o levantamento do As Is, são registrados:

- Entradas;
- Saídas;
- Responsáveis;
- Sistemas;
- Documentos;
- Aprovações;
- Regras de negócio;
- Exceções;
- Indicadores;
- SLAs;
- Tempo médio de execução;
- Pontos de controle.

Quanto mais completo o levantamento, melhor será a qualidade da análise.

---

# Exemplo

Imagine o processo de abertura de chamados.

```text
Cliente abre chamado

↓

Central recebe

↓

Analista analisa

↓

Supervisor aprova

↓

Equipe executa

↓

Chamado encerrado
```

Nesse momento não avaliamos se o fluxo está correto.

Apenas registramos como ele realmente acontece.

---

# Aplicação na minha experiência profissional

Durante minha atuação na Torre de Business Process Management (BPM) da TIVIT, compreender a operação era essencial antes da elaboração de planos de ação.

A análise dos indicadores, auditorias, reuniões de acompanhamento e observação dos processos permitia identificar como as atividades eram executadas na prática, servindo de base para iniciativas de melhoria contínua.

Na área de Qualidade de Software (QA), essa mesma abordagem era utilizada para entender fluxos de negócio antes da elaboração de cenários de testes, garantindo que as validações refletissem o comportamento esperado do sistema.

---

# Boas práticas

- Registrar fatos, não opiniões.
- Validar todas as informações.
- Conversar com quem executa o processo.
- Observar a operação.
- Documentar exceções.
- Utilizar indicadores sempre que possível.

---

# Exemplo Visual

```mermaid
flowchart LR

A[Cliente]

B[Abertura do Chamado]

C[Análise]

D[Aprovação]

E[Execução]

F[Encerramento]

A --> B
B --> C
C --> D
D --> E
E --> F
```

---

# Resumo

| Conceito | Descrição |
|-----------|-----------|
| As Is | Processo como ele acontece hoje |
| Objetivo | Compreender a situação atual |
| Resultado | Base para o Processo To Be |

---

# Referências

- ABPMP International. *BPM CBOK®.*
- OMG. *Business Process Model and Notation (BPMN) 2.0.*
- Hammer, Michael; Champy, James. *Reengineering the Corporation.*



