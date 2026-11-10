# Ideias de monetização · Monetization ideas — Claude Skill

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
![Claude Skill](https://img.shields.io/badge/Claude-Skill-D97757)

📚 Faz parte da **[biblioteca de skills de mozuraa](https://github.com/mozuraa/claude-skills)** · Part of **[mozuraa's skills library](https://github.com/mozuraa/claude-skills)**

**[Português](#português) · [English](#english)**

---

## Português

Uma [skill](#o-que-é-uma-skill) para o **Claude** (Claude Code, app Claude e claude.ai).

### O que faz

Gera **2 a 3 estratégias de monetização bem desenvolvidas** para uma app ou jogo — compras dentro da app, compra única, subscrições, anúncios, pacotes, economia de moedas, paywalls. Sempre com preços concretos (escalões reais das lojas), o momento certo em que a oferta aparece e atenção às regras da App Store e do Google Play.

### Quando é ativada

O Claude usa-a sozinho quando pedes algo como:

- "Como ganho dinheiro com o meu jogo?"
- "Que preço ponho na versão completa?"
- "Devo pôr anúncios?"
- "Revê a loja da minha app"

Também a podes chamar diretamente com `/ideias-monetizacao`.

### O que recebes

Cada ideia vem sempre com:

- O que é
- Porquê nesta app
- Preços e números
- Onde aparece
- Riscos
- Esforço
- Como medir

No fim, o Claude diz qual recomenda e porquê, e oferece-se para aprofundar.

Vê um exemplo completo em [`examples/exemplo.md`](examples/exemplo.md).

### Detalhes

- Justo para o utilizador: nada de pagar-para-ganhar agressivo nem truques enganadores.
- Assinala quando uma ideia toca nas regras das lojas (caixas aleatórias, subscrições, compras de conteúdo digital).
- São ideias de produto, **não** aconselhamento financeiro.
- Responde na língua em que escreves — as instruções estão em português, mas funciona em qualquer língua.

### Instalação

**Claude Code (para todos os teus projetos)**

```bash
git clone https://github.com/mozuraa/claude-skill-ideias-monetizacao.git ~/.claude/skills/ideias-monetizacao
```

**Claude Code (só num projeto)** — dentro da pasta do projeto:

```bash
git clone https://github.com/mozuraa/claude-skill-ideias-monetizacao.git .claude/skills/ideias-monetizacao
```

Abre uma sessão nova para a skill ser carregada.

**App Claude / claude.ai**

1. Nesta página, carrega em **Code → Download ZIP**.
2. No Claude, abre as **Definições** e procura a secção **Skills** (em *Capacidades*).
3. Carrega o ZIP. A skill fica disponível nas tuas conversas.

> As skills personalizadas precisam de estar ativadas na tua conta/organização.

### Atualizar

```bash
cd ~/.claude/skills/ideias-monetizacao && git pull
```

### O que é uma skill?

Uma skill é uma pasta com um ficheiro `SKILL.md`: um nome, uma descrição de quando deve ser usada e instruções. O Claude lê só a descrição até ela ser útil; quando o pedido encaixa, carrega as instruções e segue-as. Não instala programas nem corre código — é só texto.

### Estrutura

```
claude-skill-ideias-monetizacao/
├── SKILL.md            # a skill (nome, descrição e instruções)
├── examples/
│   └── exemplo.md      # exemplo de pedido e resposta
├── README.md
├── CHANGELOG.md
└── LICENSE
```

### Família de skills de ideias

| Skill | Para quê |
|---|---|
| [`ideias-apps`](https://github.com/mozuraa/claude-skill-ideias-apps) | Ideias de apps e jogos |
| [`ideias-funcionalidades`](https://github.com/mozuraa/claude-skill-ideias-funcionalidades) | Ideias de funcionalidades |
| [`ideias-monetizacao`](https://github.com/mozuraa/claude-skill-ideias-monetizacao) *(esta)* | Ideias de monetização |
| [`brainstorming`](https://github.com/mozuraa/claude-skill-brainstorming) | Brainstorming |

### Contribuir

Sugestões e melhorias são bem-vindas: abre uma *issue* ou um *pull request*. Se a skill não se ativou quando devia (ou ativou quando não devia), diz qual foi o pedido — ajuda a afinar a descrição.

### Licença

[MIT](LICENSE) — podes usar, alterar e partilhar livremente, mantendo o aviso de licença.

---

## English

A [skill](#what-is-a-skill) for **Claude** (Claude Code, the Claude app and claude.ai).

### What it does

Generates **2–3 well-developed monetization strategies** for an app or game — in-app purchases, one-time unlocks, subscriptions, ads, bundles, coin economies, paywalls. Always with concrete prices (real store price tiers), the right moment for the offer to appear, and attention to App Store and Google Play rules.

### When it triggers

Claude uses it on its own when you ask things like:

- "How do I make money from my game?"
- "What should the full version cost?"
- "Should I add ads?"
- "Review my app's store screen"

You can also call it directly with `/ideias-monetizacao`.

### What you get

Every idea always includes:

- What it is
- Why it fits this app
- Prices and numbers
- Where it appears
- Risks
- Effort
- How to measure it

At the end, Claude says which one it recommends and why, and offers to go deeper.

See a full example in [`examples/exemplo.md`](examples/exemplo.md) (in Portuguese).

### Details

- Fair to users: no aggressive pay-to-win or dark patterns.
- Flags when an idea touches store rules (loot boxes, subscriptions, digital goods).
- These are product ideas, **not** financial advice.
- Replies in the language you write in — the instructions are in Portuguese, but it works in any language.

### Installation

**Claude Code (all your projects)**

```bash
git clone https://github.com/mozuraa/claude-skill-ideias-monetizacao.git ~/.claude/skills/ideias-monetizacao
```

**Claude Code (one project only)** — from the project folder:

```bash
git clone https://github.com/mozuraa/claude-skill-ideias-monetizacao.git .claude/skills/ideias-monetizacao
```

Start a new session so the skill is loaded.

**Claude app / claude.ai**

1. On this page, click **Code → Download ZIP**.
2. In Claude, open **Settings** and find the **Skills** section (under *Capabilities*).
3. Upload the ZIP. The skill becomes available in your chats.

> Custom skills must be enabled for your account/organization.

### Updating

```bash
cd ~/.claude/skills/ideias-monetizacao && git pull
```

### What is a skill?

A skill is a folder with a `SKILL.md` file: a name, a description of when it should be used, and instructions. Claude only reads the description until it becomes relevant; when a request matches, it loads the instructions and follows them. It installs no programs and runs no code — it's just text.

### Idea skills family

| Skill | What for |
|---|---|
| [`ideias-apps`](https://github.com/mozuraa/claude-skill-ideias-apps) | App & game ideas |
| [`ideias-funcionalidades`](https://github.com/mozuraa/claude-skill-ideias-funcionalidades) | Feature ideas |
| [`ideias-monetizacao`](https://github.com/mozuraa/claude-skill-ideias-monetizacao) *(this one)* | Monetization ideas |
| [`brainstorming`](https://github.com/mozuraa/claude-skill-brainstorming) | Brainstorming |

### Contributing

Suggestions and improvements are welcome: open an issue or a pull request. If the skill didn't trigger when it should have (or did when it shouldn't), share the prompt — it helps tune the description.

### License

[MIT](LICENSE) — free to use, modify and share, keeping the license notice.
