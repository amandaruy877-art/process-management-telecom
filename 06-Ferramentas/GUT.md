# Matriz GUT

## O que é?

A Matriz GUT é uma ferramenta de priorização utilizada para avaliar e ordenar problemas ou demandas com base em três critérios:

- **Gravidade (G):** Qual o impacto do problema?
- **Urgência (U):** Com que rapidez ele precisa ser resolvido?
- **Tendência (T):** O problema tende a piorar se nenhuma ação for tomada?

Cada critério recebe uma nota de **1 a 5**, sendo:

| Nota | Significado |
|------|-------------|
| 1 | Muito Baixo |
| 2 | Baixo |
| 3 | Médio |
| 4 | Alto |
| 5 | Muito Alto |

A prioridade é calculada pela fórmula:

```
G × U × T
```

Quanto maior o resultado, maior deve ser a prioridade da demanda.

---

# Quando utilizar?

A Matriz GUT pode ser aplicada para:

- Priorizar defeitos (bugs)
- Organizar backlog
- Definir ordem de correção
- Priorizar incidentes
- Avaliar riscos
- Planejar melhorias de processo

---

# Exemplo aplicado ao QA

Imagine que três defeitos foram encontrados durante uma Sprint.

| Problema | Gravidade | Urgência | Tendência | Resultado |
|----------|----------:|----------:|----------:|----------:|
| Login indisponível | 5 | 5 | 5 | **125** |
| Erro de layout em smartphone | 2 | 2 | 2 | **8** |
| Lentidão na geração de relatório | 4 | 3 | 4 | **48** |

### Ordem de prioridade

1. Login indisponível (125)
2. Lentidão no relatório (48)
3. Layout em smartphone (8)

---

# Aplicação em QA

Durante o processo de testes é comum encontrar diversos defeitos ao mesmo tempo.

Nem sempre é possível corrigir tudo antes da entrega, por isso a Matriz GUT auxilia Product Owners, Desenvolvedores e Analistas de QA na definição das prioridades.

Exemplos:

- Definir quais bugs serão corrigidos na Sprint atual.
- Priorizar incidentes críticos em produção.
- Apoiar reuniões de triagem (Bug Triage).
- Organizar o backlog técnico.

---

# Vantagens

- Fácil aplicação
- Objetividade na priorização
- Apoia tomada de decisão
- Reduz decisões baseadas apenas em opinião
- Facilita alinhamento entre áreas

---

# Limitações

- A avaliação das notas pode ser subjetiva.
- Deve ser utilizada em conjunto com o contexto do negócio.
- Não substitui análise de impacto técnico.

---

# Resumo

A Matriz GUT é uma ferramenta simples e eficiente para priorizar problemas de acordo com seu impacto, urgência e tendência de agravamento. No contexto de Qualidade de Software (QA), ela auxilia equipes na tomada de decisão sobre quais defeitos devem ser tratados primeiro, contribuindo para entregas mais seguras e alinhadas às prioridades do negócio.
