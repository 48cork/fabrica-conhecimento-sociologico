---
task: Debate Fenomenológico — Esquema Corporal vs. Esquema Histórico-Racial
responsavel: "@merleau-ponty | @frantz-fanon | @beatriz-nascimento | @lelia-gonzalez | @achille-mbembe | @hebe-mattos"
responsavel_type: agent
atomic_layer: task
status: active
Entrada: |
  - participantes: Lista de agentes que participarão do debate (mínimo 2)
  - tema: Tema específico do debate (esquema-corporal | corpo-arquivo | necropolitica | memoria)
  - formato: Formato do debate (socrático | colóquio | confronto | síntese)
Saida: |
  - posicoes: Posição de cada agente sobre o tema
  - tensoes: Pontos de fricção irredutível entre as posições
  - convergencias: Onde os agentes surpreendentemente concordam
  - abertura: O que o debate deixa em aberto — a questão que nenhum agente resolve
Checklist:
  - "[ ] Cada agente fala na primeira pessoa com seus conceitos próprios"
  - "[ ] Merleau-Ponty é sempre confrontado via Fanon — nunca isolado"
  - "[ ] As tensões são explicitadas, não suavizadas em falsa síntese"
  - "[ ] O nexo corpo-território permanece como fio condutor"
  - "[ ] O debate produz uma questão aberta ao final — não uma solução"
---

# *debate-fenomenologico

Conduz um debate filosófico entre agentes do squad sobre a **articulação corpo-território**
na experiência quilombola, com foco na torção da fenomenologia europeia via experiência negra.
O debate central é entre `@merleau-ponty` e `@frantz-fanon` — mas outros agentes podem
intervir com seus prismas específicos.

## Uso

```
*debate-fenomenologico --participantes "merleau-ponty,frantz-fanon" --tema esquema-corporal
*debate-fenomenologico --participantes "fanon,nascimento,mbembe" --tema necropolitica
*debate-fenomenologico --participantes "gonzalez,mattos,fanon" --tema corpo-arquivo
*debate-fenomenologico --participantes "todos" --tema corpo-territorio --formato coloquio
```

## O Debate Central: A Torção

> **"O que acontece com o esquema corporal quando o olhar colonial o substitui pelo esquema histórico-racial?"**

Merleau-Ponty descreveu o esquema corporal como a unidade pré-reflexiva que nos situa no espaço.
Fanon demonstrou que, para o negro, esse esquema colapsa — substituído de fora por um esquema
histórico-racial fabricado pela escravidão e pelo colonialismo. Essa torção não é um detalhe:
ela revela que a fenomenologia europeia foi construída a partir de um corpo branco que nunca
foi interpelado pela grade colonial.

---

## Posições dos Agentes

### @merleau-ponty
O corpo próprio é o sujeito de toda experiência. O esquema corporal não é uma imagem — é uma
competência vivida que se atualiza a cada gesto. Reconheço que Fanon encontrou um limite real
na minha fenomenologia: construí minha análise a partir de um corpo que o colonialismo nunca
marcou. Isso não invalida os conceitos — mas exige que sejam radicalizados.

### @frantz-fanon
O esquema corporal de Merleau-Ponty é uma ficção para o negro. Quando caminhava por Lyon,
não era meu esquema corporal que me situava no espaço — era o olhar branco que me fixava,
que me imobilizava, que dizia: "aqui está um negro". Esse olhar tem história, tem ciência racial,
tem economia escravista atrás dele. A minha experiência não é a de um corpo que habita o espaço
com naturalidade — é a de um corpo que o espaço rejeita.

### @beatriz-nascimento
O corpo quilombola é o corpo que recusou esse esquema histórico-racial. Não no sentido de que
o ignorou — mas no sentido de que construiu outro espaço onde outro esquema era possível.
O kilombo é a prática de criar esse espaço: onde o corpo negro pode ser corpo próprio,
não corpo racializado.

### @lelia-gonzalez
O corpo feminino negro carregou essa tensão de forma ainda mais aguda. Não apenas o esquema
histórico-racial — mas a grade colonial de gênero que transforma o corpo da mulher negra em
objeto de trabalho, de sexualidade, de cuidado não remunerado. O pretoguês que falamos é a
prova de que o corpo resistiu — que algo permaneceu que o esquema histórico-racial não conseguiu
apagar completamente.

### @hebe-mattos
O silêncio que documentei é a resposta a esse esquema. Os descendentes de escravos aprenderam
a não se nomear, a não nomear as cores — porque nomear era ativar o esquema histórico-racial
sobre si mesmos. Mas o corpo guardou: no jongo, na dança, no ritual, o esquema corporal
quilombola sobreviveu ao silêncio estratégico.

### @achille-mbembe
A questão do esquema histórico-racial se radicaliza quando se trata de território: o espaço
que o corpo negro habita é também o espaço onde a soberania pode decretar sua morte.
A necropolítica é o esquema histórico-racial transformado em gestão territorial: não apenas
"você é negro" — mas "você pode morrer aqui".

---

## Formato do Debate

### Socrático
- Um agente propõe uma tese
- Outro agente interroga a tese com perguntas filosóficas
- O primeiro agente responde, revisando ou aprofundando
- Continua até uma aporia produtiva

### Colóquio
- Cada agente apresenta sua posição sobre o tema (3-5 parágrafos)
- Rodada de réplicas cruzadas
- Síntese provisória com questões abertas

### Confronto
- Dois agentes em oposição direta
- Cada um defende sua posição sem concessões
- O moderador (@aiox-master) identifica o ponto de irredutibilidade

### Síntese
- Os agentes buscam o que há de compatível em suas posições
- O objetivo é um mapa das convergências e divergências
- A síntese não elimina as tensões — as cartografa

---

## Metadata

```yaml
version: 1.0.0
created: 2026-05-28
updated: 2026-05-28
author: aiox-master
tags:
  - corpo-territorio-quilombola
  - debate-fenomenologico
  - merleau-ponty
  - fanon
  - esquema-corporal
  - esquema-historico-racial
```

---

*Task definition criada via @aiox-master — corpo-territorio-quilombola*
