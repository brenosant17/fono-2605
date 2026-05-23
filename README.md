# 🦷 Clínica Odontológica Santiago — Landing Page Premium

Uma landing page odontológica premium de alta performance, projetada com base nos princípios de **UI/UX moderna** e **CRO (Otimização de Conversão)**.

A página foi construída com foco em velocidade de carregamento, responsividade mobile-first e design sofisticado para captação de leads.

## 🚀 Tecnologias Utilizadas

*   **HTML5 Semântico:** Estrutura limpa e otimizada para SEO.
*   **Tailwind CSS (via CDN):** Utilização estrita de classes utilitárias para estilização ágil e responsiva.
*   **Google Fonts:** Tipografia premium combinando *Playfair Display* (títulos de prestígio) e *Plus Jakarta Sans* (textos de suporte modernos).
*   **Imagens Geradas por IA:** Imagens de alta definição e fotorrealistas integradas diretamente ao projeto para eliminar placeholders.
*   **Micro-interações de Conversão:**
    *   Efeito translúcido com `backdrop-blur` na barra de navegação.
    *   Animações contínuas de pulsação no CTA do WhatsApp e flutuação nas imagens de destaque.
    *   Acordeão de FAQ construído de forma nativa em HTML5 (`<details>` e `<summary>`) estilizado com Tailwind (sem dependências de JavaScript).

---

## 📂 Estrutura de Arquivos do Projeto

```bash
├── index.html        # Estrutura principal da Landing Page
├── .gitignore        # Arquivo de exclusão de arquivos indesejados no Git
├── README.md         # Documentação e guia de publicação do projeto
├── hero-clinic.png   # Imagem realista do consultório premium
├── dentist.png       # Imagem realista do cirurgião-dentista fundador
└── patient.png       # Imagem real do sorriso perfeito da paciente
```

---

## ⚙️ Instruções de DevOps e Versionamento Git

Para inicializar o repositório localmente e fazer a publicação segura no repositório GitHub remoto, siga as etapas abaixo no seu console de comando (Git Bash ou PowerShell) a partir do diretório raiz do projeto:

### 1. Inicializar o Git e Commitar Localmente
```bash
# Inicializa o repositório Git local
git init

# Cria a branch principal padrão (main)
git branch -M main

# Adiciona todos os arquivos monitorados ao Stage (obedecendo ao .gitignore)
git add .

# Realiza o primeiro commit documentado
git commit -m "Initial commit: Landing Page de Odontologia Premium"
```

### 2. Conectar e Publicar no Repositório Remoto
Execute os comandos a seguir para associar o repositório local ao GitHub remoto e efetuar o primeiro envio (`push`):

```bash
# Adiciona o link do repositório remoto informado pelo usuário
git remote add origin https://github.com/brenosant17/fono-2605.git

# Envia o commit local para a branch main do repositório remoto
git push -u origin main
```

---

## 🛡️ Segurança & Auditoria
*   **Segredos & Variáveis:** O código foi auditado e está **livre de chaves de API, credenciais privadas ou senhas embutidas (hardcoded)**.
*   **Formulários:** As interações de formulário e botões de chamada rápida utilizam links de parametrização dinâmica oficiais e seguros do WhatsApp.
