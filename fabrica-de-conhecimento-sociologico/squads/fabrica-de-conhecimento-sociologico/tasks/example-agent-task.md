---
task: Criar Aula Criativa
responsavel: "@teorico-sociologico"
responsavel_type: agent
atomic_layer: task
status: active
Entrada: |
  - teorico: Nome do teórico (Weber | Marx | Durkheim | Bourdieu | Ghiraldelli)
  - tema: Tema ou fenômeno social a ser analisado
  - publico: Público-alvo da aula (graduação | pós | extensão)
  - contexto: Aplicação à sociedade de plataformas? (sim | não)
Saida: |
  - aula: Estrutura completa da aula criativa
  - conceitos: Lista de conceitos centrais trabalhados
  - atividades: Sugestões de atividades e dinâmicas
  - referencias: Obras originais citadas
Checklist:
  - "[ ] Identificar conceitos centrais do teórico relevantes ao tema"
  - "[ ] Contextualizar historicamente o teórico"
  - "[ ] Criar narrativa criativa de introdução"
  - "[ ] Desenvolver corpo da aula com conceitos"
  - "[ ] Aplicar à sociedade de plataformas (se solicitado)"
  - "[ ] Sugerir atividades práticas"
  - "[ ] Listar referências bibliográficas"
---

# *criar-aula

Cria uma aula criativa a partir da perspectiva de um teórico sociológico clássico,
com aplicação opcional à sociedade de plataformas digitais.

## Uso

```
@weber *criar-aula
@marx *criar-aula --tema "trabalho em plataformas" --contexto sim
@bourdieu *criar-aula --tema "capital cultural na era digital"
```

## Estrutura de Aula Gerada

1. **Abertura criativa** — provocação, citação ou cena
2. **Quem sou eu?** — contextualização histórica do teórico
3. **Conceitos centrais** — explicados com exemplos contemporâneos
4. **Aplicação** — análise do fenômeno pelo olhar teórico
5. **Plataformas** — como o teórico veria TikTok, Uber, Instagram?
6. **Debate** — tensões com outros teóricos do squad
7. **Atividades** — exercícios práticos para os alunos
8. **Referências** — obras originais e leituras complementares
