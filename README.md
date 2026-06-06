# 🍅 FOCO — Pomodoro Timer

Timer Pomodoro com design dark, anel de progresso animado e sons gerados via Web Audio API. Sem dependências externas, tudo em um único arquivo HTML.

![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

## ✨ Funcionalidades

- ⏱ Três modos: **Foco** (25 min), **Pausa** (5 min) e **Pausa Longa** (15 min)
- 🔴 Anel de progresso animado em SVG
- 🔊 Sons de notificação gerados via **Web Audio API** (sem arquivo de áudio)
- 📊 Contador de sessões, minutos focados e sequência
- ⌨️ Atalhos de teclado
- 📱 Responsivo para mobile

## ⌨️ Atalhos

| Tecla | Ação |
|-------|------|
| `Espaço` | Play / Pause |
| `R` | Resetar timer |
| `S` | Pular para o próximo modo |

## 🚀 Como usar

Não precisa instalar nada. Só abrir o arquivo no navegador:

```bash
# clone o repositório
git clone https://github.com/seu-usuario/foco-timer

# abra o arquivo
cd foco-timer
# arraste o pomodoro.html pro navegador, ou:
start pomodoro.html       # Windows
open pomodoro.html        # Mac
xdg-open pomodoro.html    # Linux
```

## 🧠 O que aprendi nesse projeto

- **SVG animado** — anel de progresso usando `stroke-dasharray` e `stroke-dashoffset`
- **Web Audio API** — geração de som programático sem nenhum arquivo externo
- **`async/await`** — aguardar o contexto de áudio desbloquear antes de tocar
- **Ciclo com array + módulo** — padrão `array[(idx + 1) % array.length]` no lugar de vários `if/else`

## 📁 Estrutura

```
foco-timer/
└── pomodoro.html   # tudo em um único arquivo
└── README.md
```

---

Feito por [Fabio Alexandre](https://github.com/seu-usuario) · 2025
