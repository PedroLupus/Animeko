<div align="center">

# 🐺 AnimêKo

### *Assista grátis, com anúncio a cada 3 segundos.*

Um site de streaming de anime **falso**, feito só de HTML, CSS e um pouquinho de JavaScript — e muita ironia sobre a experiência de "sites de anime piratas".

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](#)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](#)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](#)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)](#)

</div>

---

## ⚠️ Aviso

> **Isto não é um site real.** Nenhum episódio é hospedado aqui, nenhum vídeo é reproduzido de verdade e nenhum formulário envia dados a lugar nenhum. É **apenas um layout HTML/CSS**, feito somente para a finalização da disciplina de Desemvolvimento Front-End I.

---

## 🍥 Sobre o projeto

**AnimêKo** é uma paródia carinhosa daqueles sites de anime cheios de pop-up, "legendado por estagiário" e player que nunca carrega. O projeto simula uma plataforma completa de catálogo de animes — com página inicial, lista, categorias, calendário de lançamentos e fluxo de login/cadastro — tudo construído com HTML e CSS puros, sem frameworks de front-end pesados, usando a **API pública [Jikan](https://jikan.moe/)** para ilustrar os cards com dados reais de animes.

A identidade visual aposta em uma paleta escura e sofisticada (tons de carvão, madeira e âmbar), tipografia serifada em destaque (**Syne**) combinada com uma mono (**JetBrains Mono**), e microtextos irônicos espalhados por toda a interface.

---

## ✨ Funcionalidades

| Página | Descrição |
|---|---|
| 🏠 **`index.html`** | Página inicial com ticker de aviso, carrossel de lançamentos e vitrines de animes em destaque |
| 📚 **`animeko-lista.html`** | Lista completa de animes com barra de filtros |
| 🗂️ **`animeko-categorias.html`** | Grade de categorias/gêneros com contagem de títulos |
| 📅 **`animeko-calendario.html`** | Calendário de lançamentos organizado por dia da semana |
| 🔐 **`animeko-login.html`** | Tela de login (que não autentica ninguém, de propósito) |
| 📝 **`animeko-cadastro.html`** | Tela de cadastro com indicador de força de senha |

Outros detalhes:
- 🔎 Barra de busca no cabeçalho, presente em todas as páginas
- 🖼️ Busca dinâmica de capas de anime via **API Jikan** (MyAnimeList)
- 🎠 Carrossel de lançamentos animado com Bootstrap
- 💬 Textos de interface propositalmente exagerados e cômicos
- 📱 Layout responsivo

---

## 🛠️ Tecnologias

- **HTML5** — estrutura semântica das páginas
- **CSS3** — estilização unificada em `animeko.css` (variáveis CSS, gradientes, animações)
- **JavaScript** (vanilla) — consumo da API Jikan e interações simples
  > *só um tiquim🤏*
- **[Bootstrap 5.3](https://getbootstrap.com/)** — componentes de carrossel
- **[Jikan API](https://jikan.moe/)** — dados públicos do MyAnimeList
- Fontes **Syne** e **JetBrains Mono**, via Google Fonts

---

## 📁 Estrutura do projeto

```
Animeko-main/
├── index.html                  # Página inicial
├── animeko-lista.html          # Lista de animes
├── animeko-categorias.html     # Categorias
├── animeko-calendario.html     # Calendário de lançamentos
├── animeko-login.html          # Login
├── animeko-cadastro.html       # Cadastro
├── animeko.css                 # Estilos globais
└── .vscode/
    └── settings.json           # Configuração do Live Server
```

---

## 🚀 Como rodar localmente

Por ser um projeto 100% estático, não há build nem dependências para instalar.

```bash
# 1. Clone o repositório
git clone https://github.com/<seu-usuario>/Animeko.git

# 2. Entre na pasta
cd Animeko

# 3. Abra index.html no navegador
```

Ou, se preferir, use a extensão **[Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)** no VS Code (o projeto já vem com a porta configurada em `.vscode/settings.json`).

---

## 👤 Autoria

[![GitHub](https://img.shields.io/badge/GitHub-PedroLupus-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/PedroLupus)

---

<div align="center">

*"Legendado por estagiário. Dublado às pressas. 7 pop-ups grátis."*

</div>