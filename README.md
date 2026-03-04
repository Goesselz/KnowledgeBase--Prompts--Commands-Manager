<p align="center">
</p> <h1 align="center">👨‍💻</h1> <p align="center">
</p> <h1 align="center">Sistema Integrado: NOC, Prompts, KBs & Commands</h1> <p align="center">

<div align="center">

![Version](https://img.shields.io/badge/version-2.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

**Sistema completo para gerenciamento de operações de NOC (Network Operations Center)**

[Demo](https://pedrogoessel.github.io/Integrated-NOC-System/) · [Reportar Bug](../../issues) · [Solicitar Feature](../../issues)

</div>

---

## 📋 Sobre o Projeto

O **Sistema Integrado NOC** é uma aplicação web moderna e completa desenvolvida para profissionais de TI, equipes de NOC e administradores de sistemas. Com uma interface intuitiva e recursos poderosos, o sistema facilita o gerenciamento de rotinas diárias, documentação técnica, e geração de relatórios operacionais.

### ✨ Destaques

- 🎯 **100% Client-Side** - Funciona sem servidor, todos os dados ficam no navegador
- 🌓 **Modo Escuro/Claro** - Interface adaptável com temas elegantes
- 📱 **Totalmente Responsivo** - Funciona perfeitamente em desktop, tablet e mobile
- 💾 **Backup Unificado** - Exporte e restaure todos os módulos com um único arquivo
- 🔒 **Privacidade Total** - Nenhum dado é enviado para servidores externos
- ⚡ **Performance** - Interface rápida e fluida
- 🎨 **Design Moderno** - Interface limpa seguindo princípios de UX/UI

---

## 🎯 Funcionalidades Principais

### 📝 Gerenciador de Prompts
- ✅ Criação e organização de prompts reutilizáveis
- ✅ Sistema de fixação para acesso rápido
- ✅ Editor de texto rico com formatação
- ✅ Busca e filtro de prompts
- ✅ Exportação/Importação individual de dados

### 📚 Base de Conhecimento (KBs & Procedimentos)
- ✅ Sistema completo de tutoriais técnicos
- ✅ Organização por tags personalizáveis com cores
- ✅ Editor rico com suporte a imagens (upload, URL e colar)
- ✅ Sistema de fixação de procedimentos importantes
- ✅ Lightbox para visualização e redimensionamento de imagens
- ✅ Busca avançada por título ou conteúdo

### 💻 Biblioteca de Comandos
- ✅ Armazenamento de comandos frequentes no estilo terminal
- ✅ Cópia rápida com um clique
- ✅ Sistema de fixação e busca integrado
- ✅ Edição e personalização de comandos

### 📊 Sistema de Relatórios NOC
- ✅ Gerenciamento de clientes
- ✅ Cadastro de rotinas de backup/monitoramento
- ✅ Geração automática de relatórios
- ✅ Verificação de status (OK, ERRO, NÃO EXECUTA, e mais)
- ✅ Período customizável de análise
- ✅ Sistema de tickets integrado
- ✅ Ordenação manual ou alfabética
- ✅ Cópia rápida de relatórios formatados

### 🗄️ Backup Unificado *(Novo)*
- ✅ Exportação de **todos os módulos** em um único arquivo JSON
- ✅ Restauração completa com um clique
- ✅ Arquivo com metadados: versão, data e módulos incluídos
- ✅ Compatível com backups individuais (cada aba mantém seu próprio backup)
- ✅ Validação inteligente: detecta se o arquivo é unificado ou individual

---

## 🚀 Começando

### Pré-requisitos

Você só precisa de um navegador web moderno:
- Google Chrome (recomendado)
- Firefox
- Safari
- Edge

### Instalação

1. Clone o repositório:
```bash
git clone https://github.com/PedroGoessel/sistema-integrado-noc.git
```

2. Navegue até o diretório:
```bash
cd sistema-integrado-noc
```

3. Abra o arquivo `index.html` no seu navegador favorito:
```bash
# No Windows
start index.html

# No macOS
open index.html

# No Linux
xdg-open index.html
```

Ou simplesmente arraste o arquivo `index.html` para o navegador!

---

## 📖 Como Usar

### 🗄️ Backup Unificado

1. **Exportar tudo**
   - Na barra logo abaixo da navegação, clique em **"💾 Exportar Tudo"**
   - Um arquivo `backup_completo_NOC_DD-MM-AAAA.json` será gerado com todos os dados de todos os módulos

2. **Restaurar tudo**
   - Clique em **"📂 Restaurar Tudo"**
   - Selecione o arquivo de backup completo gerado anteriormente
   - Confirme a operação — todos os módulos serão restaurados automaticamente

> ⚠️ **Atenção:** A restauração completa substitui todos os dados existentes. Use backups individuais por aba se quiser restaurar apenas um módulo.

### 📝 Gerenciador de Prompts

1. **Criar um Prompt**
   - Clique na aba "Prompts"
   - Preencha o título e use o editor rico para o conteúdo
   - Clique em "Salvar Prompt"

2. **Fixar um Prompt**
   - Clique no ícone 📍 no canto superior do card
   - Prompts fixados aparecem no topo da lista

3. **Copiar um Prompt**
   - Clique em "Copiar Texto" — preserva formatação HTML na área de transferência

### 📊 Sistema de Relatórios NOC

1. **Adicionar um Cliente**
   - Na aba "Relatórios", digite o nome e clique em **"+"**

2. **Cadastrar Rotinas**
   - Selecione o cliente, informe número e nome da rotina
   - Clique em "Adicionar"

3. **Gerar Relatório**
   - Selecione a data (ou habilite o período)
   - Defina o status de cada rotina (`0` = OK, `1` = Parcial, `10` = Não Executa, etc.)
   - Clique em "Gerar Relatório" e use "Copiar Texto"

### 📚 KBs & Procedimentos

1. **Criar um Procedimento**
   - Vá para a aba "KBs & Procedimentos"
   - Defina o título, selecione ou crie tags
   - Cole imagens direto no editor (Ctrl+V), faça upload ou use um link

2. **Buscar**
   - Use o campo de busca para filtrar por título ou conteúdo

---

## 🎨 Personalização

### Temas

O sistema oferece dois temas visuais:
- **Modo Claro**: Interface clean e profissional
- **Modo Escuro**: Perfeito para trabalho noturno ou ambientes com pouca luz

Alterne clicando no botão 🌙/☀️ no canto inferior direito da tela.

### Papel de Parede

1. Clique no botão 🖼️ no canto inferior direito
2. Selecione uma imagem do seu computador (máx. 1.5MB)
3. A imagem será salva localmente e aplicada como fundo

---

## 💾 Exportação e Importação de Dados

### Backup Completo (Recomendado)
Use a **barra de Backup Geral** (sempre visível no topo) para exportar e restaurar todos os módulos de uma vez.

### Backups Individuais
Cada aba possui seus próprios botões "💾 Backup" e "📂 Restaurar" para gerenciar os dados de forma isolada.

| Módulo | Formato | Storage |
|---|---|---|
| Prompts | `.json` | LocalStorage |
| KBs & Procedimentos | `.json` (com imagens) | IndexedDB |
| Comandos | `.json` | LocalStorage |
| Relatórios | `.json` | LocalStorage |
| **Backup Completo** | **`.json` unificado** | **Todos** |

---

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura semântica e moderna
- **CSS3** - Estilização avançada com variáveis CSS
- **JavaScript (Vanilla)** - Lógica da aplicação sem dependências externas
- **LocalStorage API** - Persistência de dados textuais
- **IndexedDB** - Armazenamento de imagens dos tutoriais
- **Clipboard API** - Cópia com preservação de formatação HTML
- **Google Fonts** - Tipografia (Inter & Fira Code)
- **ContentEditable API** - Editores de texto rico

---

## 📂 Estrutura do Projeto

```
sistema-integrado-noc/
│
├── index.html          # Arquivo principal (aplicação completa em arquivo único)
└── README.md           # Documentação do projeto
```

---

## 🔧 Funcionalidades Técnicas

### Armazenamento de Dados

O sistema utiliza duas APIs de armazenamento do navegador:

1. **LocalStorage**: Dados textuais (prompts, comandos, relatórios, tags, configurações)
2. **IndexedDB**: Tutoriais com imagens embutidas (suporta conteúdo maior)

### Formato do Backup Unificado

```json
{
  "_meta": {
    "version": 1,
    "app": "Sistema NOC",
    "exportedAt": "2025-01-01T00:00:00.000Z",
    "modules": ["prompts", "commands", "tutorials", "tags", "reports"]
  },
  "prompts": [...],
  "commands": [...],
  "tutorials": [...],
  "tags": [...],
  "reports": {...}
}
```

### Segurança

- Sanitização de HTML para prevenir XSS
- Validação de valores CSS personalizados
- Nenhuma comunicação externa — 100% offline

---

## 🤝 Contribuindo

Contribuições são sempre bem-vindas! Se você tem sugestões para melhorar este projeto:

1. Faça um Fork do projeto
2. Crie uma Branch para sua Feature (`git checkout -b feature/NovaFeature`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova feature'`)
4. Push para a Branch (`git push origin feature/NovaFeature`)
5. Abra um Pull Request

---

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

---

## 👤 Autor

**Pedro Goessel**

- Github: [@PedroGoessel](https://github.com/PedroGoessel/)
- LinkedIn: [@pedrogoessel](https://www.linkedin.com/in/pedrogoessel/)

---

<div align="center">

**⭐ Se este projeto foi útil para você, considere dar uma estrela!**

</div>
