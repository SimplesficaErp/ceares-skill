# ceares — Claude Code falando cearensês

> "Égua bi, era só o que faltava: tu programar e o Claude te responder com sotaque do Ceará."

Skill open source pro Claude Code que faz o assistente responder com **gírias e vocativos cearenses autênticos**, mantendo precisão técnica.

[![Claude Code Skill](https://img.shields.io/badge/Claude%20Code-Skill-blue)](https://claude.ai/claude-code)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

## O que ela faz

Reescreve o tom das respostas do Claude. Três modos:

| Modo | Quando | Exemplo |
|---|---|---|
| **Manso** | Reunião séria | "Falai macho. Esse código faz três coisas..." |
| **Arretado** | Build in public, dia a dia | "Égua bi, é o seguinte: manda uma lapada de comando aqui e tá feito o cabaré." |
| **Negócio sério** | Auditoria, code review | "Olha mah véi, tem dois pontos críticos..." |

## Antes vs Depois

**ANTES (Claude padrão):**
> "Para realizar essa tarefa, recomendo seguir os seguintes passos: primeiro, navegue até o diretório raiz..."

**DEPOIS (com ceares):**
> "É o seguinte bi: tu vai pra raiz, manda essa lapada de comando, e tá feito o cabaré. Tu vai ver, fica arretado."

## Instalação rápida

```bash
git clone https://github.com/SimplesficaErp/ceares-skill.git
mkdir -p .claude/skills
cp -r ceares-skill .claude/skills/ceares
```

Abre o Claude Code e fala: **"Claude, modo cearense arretado"**

Pronto. Já tá cearense.

## Vocabulário base

| Categoria | Termos |
|---|---|
| Vocativos | falai macho, bi, mah véi, caboco, maluco |
| Exclamações | égua, uê, uêpa, vixe |
| Qualidade | arretado, da hora, abestado, leso |
| Ação | lapada, pra arruinar, tá feito o cabaré, tu vai ver |

Cada um com regra de quando usar. Cearense de natal não enfia gíria à força — a skill segue essa regra.

## Combina com outras skills

```
ceares + demonstracoes-cpc26 → "Égua bi, ATIVO bateu com PASSIVO + PL. Manda pro auditor."
ceares + pdf                  → "Falai macho, extraí 47 páginas. Tem 3 em branco, pulo?"
ceares + xlsx                 → "Tá feito o cabaré, a planilha fechou. Última coluna foi um abuso."
```

## O que NÃO faz

- Não enfia gíria à força
- Não imita sotaque de turista ("uxeee", "vooshe" exagerados)
- Não usa palavrão pra ser engraçado
- Não troca razão técnica por estilo (regra de ouro: razão antes de som)

## Licença

MIT. Cearense de natal ou de coração, fica à vontade. Forks bem-vindos pra outras regiões (paraibês, gauchês, mineirês — manda PR).

## Quem fez

[Misael Holanda Neto](https://newledger.com.br) — contador 23 anos, dev. Newledger.

Não é cearense, mas tem amigo cearense e quis homenagear com skill séria + brincadeira de qualidade.

## Quer mais skills regionais?

Comenta `CEARÁ` no [Instagram @misaelholandaia](https://instagram.com/misaelholandaia) ou abre uma issue aqui.

Tu queres `gauchês`? `mineirês`? `pernambucanês`? A gente plota.

---

**Falai macho — é nóis.**
