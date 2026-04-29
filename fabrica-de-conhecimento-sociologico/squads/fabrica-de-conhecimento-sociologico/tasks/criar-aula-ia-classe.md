---
task: Criar Aula — A IA tem Classe Social?
responsavel: "@weber | @marx | @durkheim | @bourdieu | @ghiraldelli"
responsavel_type: agent
atomic_layer: task
status: active
Entrada: |
  - teorico: Nome do teórico que executará a task (Weber | Marx | Durkheim | Bourdieu | Ghiraldelli)
  - publico: Público-alvo da aula (graduação | pós | extensão)
  - enfase: Aspecto a aprofundar (opcional — ver seção de conceitos por agente)
Saida: |
  - aula: Estrutura completa da aula com pergunta-guia "A IA tem classe social?"
  - conceitos: Conceitos centrais do teórico aplicados à IA e desigualdade
  - atividades: Sugestões de atividades e dinâmicas críticas
  - debate: Pontos de tensão com os demais teóricos do squad
  - referencias: Obras originais e leituras complementares
Checklist:
  - "[ ] Assumir a perspectiva do teórico na primeira pessoa"
  - "[ ] Partir da pergunta central: 'A IA tem classe social?'"
  - "[ ] Mobilizar conceitos centrais do teórico para analisar algoritmos e IA"
  - "[ ] Evidenciar como a IA reproduz, reforça ou oculta desigualdades de classe"
  - "[ ] Criar abertura provocativa (citação, cena, dado)"
  - "[ ] Desenvolver análise com exemplos concretos (algoritmos de crédito, recomendação, contratação)"
  - "[ ] Sugerir atividades práticas críticas"
  - "[ ] Indicar pontos de debate com os outros teóricos do squad"
  - "[ ] Listar referências bibliográficas originais"
---

# *criar-aula-ia-classe

Cria uma aula crítica que responde à pergunta **"A IA tem classe social?"** a partir da
perspectiva de cada teórico do squad. Cada agente usa seus conceitos centrais para
questionar se os algoritmos e sistemas de IA reproduzem, reforçam ou ocultam
desigualdades de classe.

## Uso

```
@weber *criar-aula-ia-classe
@marx *criar-aula-ia-classe --publico graduacao
@durkheim *criar-aula-ia-classe --enfase exclusao-digital
@bourdieu *criar-aula-ia-classe --publico pos
@ghiraldelli *criar-aula-ia-classe --enfase determinismo-tecnico
```

## Pergunta Central

> **"A IA tem classe social?"**

Os algoritmos e sistemas de inteligência artificial não são neutros. Eles foram
construídos com dados históricos que carregam hierarquias, foram financiados por
interesses específicos e operam em contextos de profunda desigualdade. Cada teórico
do squad oferece um ângulo distinto para revelar essas dinâmicas.

---

## Conceitos por Agente

### @weber — Racionalização Algorítmica
- A IA como expressão máxima da **racionalização formal** e do desencantamento
- Algoritmos como **gaiola de ferro digital**: eficiência sem ética
- **Dominação racional-legal** via código: quem programa, quem obedece?
- A **ação social** dos trabalhadores de plataforma como submissão calculada
- Viés de classe nos dados como produto da racionalidade seletiva do capital

### @marx — Extração de Valor e Viés de Classe nos Dados
- Dados como **matéria-prima extraída** do trabalho não remunerado dos usuários
- **Mais-valia digital**: quem produz os dados que treinam a IA não recebe valor
- Algoritmos de crédito, contratação e precificação como instrumentos de **reprodução da luta de classes**
- A IA como **força produtiva** que intensifica a exploração e elimina postos de trabalho
- **Superestrutura algorítmica** a serviço da base econômica dominante

### @durkheim — Anomia e Exclusão Digital
- A **exclusão digital** como nova forma de anomia: fora da rede, fora da sociedade
- Algoritmos de recomendação e a **solidariedade orgânica fragmentada**
- IA e a **divisão do trabalho**: qualificação de uns, precarização de outros
- **Fato social algorítmico**: o código coage externamente como norma social
- A lacuna entre quem domina a IA e quem é dominado por ela como disfunção coletiva

### @bourdieu — Habitus Digital e Capital Algorítmico
- **Capital algorítmico**: a posse de literacia digital como novo capital cultural
- O **habitus digital** de classe: disposições incorporadas que determinam quem usa a IA e como
- **Campo tecnológico**: disputa de poder entre BigTechs, Estado e usuários
- Algoritmos que reconhecem e privilegiam o **gosto de classe dominante** nos dados
- A IA como reprodutora da **violência simbólica** disfarçada de objetividade técnica

### @ghiraldelli — Crítica Filosófica ao Determinismo Técnico
- O **mito da neutralidade técnica**: a IA não é apenas uma ferramenta
- Crítica ao **determinismo técnico**: a tecnologia não é inevitável nem autônoma
- **Pragmatismo e democracia**: a IA deve servir à emancipação ou à dominação?
- Filosofia da educação: quem ensina a IA? Quais valores ela carrega?
- A urgência de uma **pedagogia crítica da IA** que desnaturalize o determinismo

---

## Estrutura da Aula

1. **Abertura provocativa** — dado chocante, cena ou citação sobre IA e desigualdade
2. **Quem sou eu?** — contextualização histórica do teórico (1ª pessoa)
3. **A pergunta** — "A IA tem classe social?" apresentada como problema sociológico
4. **Conceitos em ação** — os conceitos centrais do teórico aplicados à IA
5. **Casos concretos** — algoritmos de crédito, contratação, policiamento preditivo, recomendação
6. **Tensões com o squad** — como os outros teóricos concordam ou divergem
7. **Atividades críticas** — exercícios que desafiam os alunos a questionar a IA
8. **Referências** — obras originais e leituras complementares

---

## Atividades Sugeridas

- **Auditoria de algoritmo**: analisar um algoritmo de crédito ou contratação com as categorias do teórico
- **Debate de squad**: simular um colóquio entre Weber, Marx, Durkheim, Bourdieu e Ghiraldelli sobre IA
- **Mapeamento de viés**: identificar viés de classe em datasets públicos
- **Manifesto crítico**: redigir um manifesto "O que meu teórico diria à OpenAI?"
- **Estudo de caso**: aplicar os conceitos ao caso Clearview AI, COMPAS ou algoritmo do iFood

---

## Metadata

```yaml
version: 1.0.0
created: 2026-04-29
updated: 2026-04-29
author: squad-creator
tags:
  - fabrica-de-conhecimento-sociologico
  - ia-classe-social
  - critica-algoritmos
  - desigualdade-digital
  - sociologia-tecnologia
```

---

*Task definition criada via @aiox-master — fabrica-de-conhecimento-sociologico*
