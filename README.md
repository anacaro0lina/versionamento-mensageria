# 📦 Versionamento

> 🚀 Repositório dedicado ao estudo e aplicação de **controle de versão com Git e GitHub**, abordando desde conceitos básicos até boas práticas utilizadas no mercado.

---

## 📚 Sobre o Projeto

Este repositório foi criado com o objetivo de:

* 📖 Compreender os conceitos fundamentais de versionamento
* 🔄 Praticar o fluxo de trabalho com Git
* 🌿 Trabalhar com **branches**, **merges** e **pull requests**
* 🧠 Desenvolver pensamento organizado no controle de mudanças
* 🤝 Simular colaboração em equipe

---

## 🧰 Tecnologias & Ferramentas

* 🐙 Git
* 🌐 GitHub
* 💻 Terminal / CLI
* 📝 Markdown

---

## 🗂️ Estrutura do Repositório

```bash
📁 versionamento/
├── 📄 README.md
├── 📁 docs/          # Documentações e anotações
├── 📁 exemplos/      # Exemplos práticos
├── 📁 atividades/    # Exercícios propostos
└── 📁 projetos/      # Projetos aplicando versionamento
```

---

## ⚙️ Conceitos Abordados

* 🧾 Controle de versão
* 📌 Commits (histórico de mudanças)
* 🌿 Branches (ramificações)
* 🔀 Merge (junção de branches)
* 🔁 Rebase
* 📥 Pull Requests
* 🧩 Resolução de conflitos
* 🏷️ Tags e versionamento semântico

---

## 🚀 Como Começar

```bash
# Clonar o repositório
git clone https://github.com/prof-andrericardo/versionamento.git

# Acessar a pasta
cd versionamento
```

---

## 🔄 Fluxo de Trabalho Básico

```bash
# Verificar status
git status

# Adicionar alterações
git add .

# Criar um commit
git commit -m "feat: descrição da alteração"

# Enviar para o repositório remoto
git push origin main
```

---

## 🌿 Trabalhando com Branches

```bash
# Criar nova branch
git checkout -b minha-feature

# Alternar entre branches
git checkout main

# Mesclar branch
git merge minha-feature
```

---

## 🌳 Git Flow

O Git Flow é uma estratégia de organização de branches muito utilizada em equipes para manter o desenvolvimento estruturado.

### Principais branches

* `main` → versão estável do projeto
* `develop` → branch de desenvolvimento
* `feature/*` → novas funcionalidades
* `hotfix/*` → correções urgentes
* `release/*` → preparação para novas versões

### Exemplo de fluxo

```bash
# Criar branch de funcionalidade
git checkout -b feature/login

# Fazer alterações e commit
git add .
git commit -m "feat: adiciona tela de login"

# Voltar para develop
git checkout develop

# Mesclar funcionalidade
git merge feature/login
```

---

## 🧪 Boas Práticas

* ✔️ Faça commits pequenos e descritivos
* 🏷️ Utilize padrões como **Conventional Commits**
* 🌱 Sempre trabalhe em branches
* 🔍 Revise antes de subir (push)
* 📄 Documente suas alterações
* 🤝 Utilize Pull Requests para colaboração

---

## 🧠 Exemplo de Commits

```bash
feat: adiciona funcionalidade de login
fix: corrige erro de validação
docs: atualiza README
refactor: melhora estrutura do código
```

---

## 🎯 Objetivo Final

Capacitar o desenvolvedor a:

* 📈 Manter histórico organizado de código
* 🤝 Trabalhar em equipe de forma eficiente
* 🚀 Aplicar versionamento em projetos reais
* 🧩 Resolver conflitos de forma estratégica

---

## 📌 Contribuição

Sinta-se à vontade para contribuir! 💡

```bash
# Fork o projeto
# Crie uma branch
git checkout -b minha-contribuicao

# Commit suas alterações
git commit -m "feat: minha contribuição"

# Push
git push origin minha-contribuicao
```

---

## 📄 Licença

Este projeto está sob a licença MIT. 📜

---

## 👨‍🏫 Autor

Desenvolvido para fins educacionais 💙  
Professor & Desenvolvedor

---

> 💬 *"Versionar não é só salvar código, é contar a história do seu projeto."* 🚀