# 🌩️  S I S T E M A   I N T E G R A D O  —  N O C
```
  ____  _      _   _  _____  _   _  ____   ____   ____ 
 / ___|| | ___| \ | || ____|| \ | |/ ___| / ___| / ___|
 \___ \| |/ _ \  \| ||  _|  |  \| |\___ \| |  _  \___ \
  ___) | |  __/ |\  || |___ | |\  | ___) | |_| | ___) |
 |____/|_|\___|_| \_||_____||_| \_||____/ \____||____/ 
```

> **Uma single-file app poderosa e elegante — pensada para quem resolve, não para quem só desenha telas.**

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE.md) [![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-ready-blue.svg)](#) [![No Back-end](https://img.shields.io/badge/Backend-None-lightgrey.svg)](#) [![Size: single-file](https://img.shields.io/badge/Bundle-single--file-orange.svg)](#)

---

## ✨ Impressão imediata (um TL;DR que convence)
- **Tudo em `index.html`**: abra, personalize, use. Sem deploy complicado.
- **Fluxo real de trabalho**: Prompts → KB → Comandos → Relatórios (feito pra produção).
- **Offline-first**: IndexedDB + localStorage = seus dados sempre com você.
- **Visual marcante**: tema escuro, fundo customizável e visual terminal para comandos.

> "Mostre o repositório — a primeira frase que eles vão ler será: *isso foi pensado por alguém que resolveu o problema.*"

---

## 🎯 Recursos que fazem parecer mágico
- **Gerenciador de Prompts**: salvar, versionar rápido, copiar com formatação pronta para IA.
- **KB avançada**: rich text, imagens embutidas, tags coloridas e busca rápida.
- **Comandos com look de terminal**: copiar comandos com preservação de formatação e snippets agrupados.
- **NOC / Relatórios automáticos**: cadastre clientes, configure rotinas e gere relatórios prontos.
- Export/Import em JSON para mover seu workspace entre máquinas.

---

## 🚀 Demonstração rápida (faça agora)
1. Clone o repo e abra `index.html` no navegador. Ou:
```bash
git clone <seu-repo>.git
cd <seu-repo>
python -m http.server 8080
# abra http://localhost:8080
```
2. Abra a aba **KB** e crie seu primeiro procedimento.
3. Salve um comando, vá na aba **Comandos** e copie com um clique.
4. Entre no **NOC** e gere um relatório diário — cole onde quiser.

---

## 🧩 Highlights técnicos (curto & preciso)
- **Armazenamento:** `IndexedDB` (KB), `localStorage` (Prompts/Comandos/Config)
- **APIs usadas:** Clipboard API, File API (import/export), ContentEditable para edição rica
- **Design:** Single-file, sem frameworks, fácil de auditar e forkear

---

## 🖌️ Visual & Branding (como impressionar quem abriu o repo)
- Coloque um **banner GIF** no topo do README (use um `docs/banner.gif`) com animação sutil de neon.
- Inclua um **screenshot** (dark mode) em `docs/screenshot-dark.png` e insira no README com `![dark mode demo](docs/screenshot-dark.png)`.
- Badges dinâmicas (stars, issues) e um **gif curto** mostrando a cópia de um comando → aumentam retenção dos visitantes.

---

## ⚙️ Configurações rápidas que dão poder
- `CONFIG.MAX_BG_SIZE_BYTES` — ajuste o limite de upload de fundos.
- `CONFIG.KEYBINDINGS` — adicione atalhos de teclado (ex.: `Ctrl+Shift+P` para prompts).
- `CONFIG.STORES` — nomes das chaves do `localStorage` e stores do `IndexedDB` para migração rápida.

---

## 🔒 Segurança & Privacidade
- Sem servidor: seus dados **não saem do navegador** por padrão.
- Exporte seus backups manualmente se quiser sincronizar com serviços externos (Gist, Drive).
- Para equipes: crie um workflow de CI que criptografe backups antes de persistir em repositórios privados.

---

## 📦 Deploy rápido (GitHub Pages)
1. Commit e push para `main`.
2. No GitHub → Settings → Pages, selecione branch `main` e root (`/`).  
O `index.html` será servido como site estático.

**Sugestão profissional:** adicione workflow de CI para validar `index.html` (linting e checks simples) antes de deploy automático.

---

## 🛠️ Contribuir (rápido e direto)
1. Abra uma *issue* descrevendo a motivação.  
2. Fork, edite `index.html` e faça PR.  
3. Mantenha PRs pequenos (uma feature por PR) e documente mudanças no topo do arquivo.

> Template de issue sugerida:  
> **Título:** `feature: exportar KB para markdown`  
> **Descrição:** motivo, passos para reproduzir, proposta de solução.

---

## 📣 Pitch curto para GitHub / Portfólio
> **Sistema Integrado — NOC**: velocidade, foco e autonomia no navegador. Ideal para times de suporte, SREs e profissionais que dependem de runbooks confiáveis — tudo em um arquivo, pronto para rodar.

---

## 📜 Licença
MIT — veja `LICENSE.md`.

---

## ✨ Extras que faço por você (se quiser que eu gere)
- Banner ASCII animado (topo)
- Badges prontas (stars, pages, license)
- `CONTRIBUTING.md`, `ISSUE_TEMPLATE.md`, `PULL_REQUEST_TEMPLATE.md`
- `docs/` com screenshots e GIFs curtos

---

> Se quiser, escrevo agora os arquivos extras (`CONTRIBUTING.md`, `LICENSE.md`) e adiciono um `docs/banner.gif` com instruções de como gerar um GIF direto do browser (screen capture). Quer que eu gere os arquivos agora? 