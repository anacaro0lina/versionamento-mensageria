# Semana 15 — Aula 01

## Tema da aula
Aprendendo a usar Git e GitHub no dia a dia

## Data
07/08/2026

## O que rolou hoje
Hoje a gente revisou como trazer um projeto do GitHub direto pro VS Code usando o `clone`. 
Depois organizamos melhor as pastas do projeto aqui no computador pra não virar bagunça. 
E pra finalizar, aprendi a registrar o que estudei criando um arquivo `.md` seguindo o modelo que o professor passou.

## O que ficou na cabeça
- Manter o projeto organizado em pastas ajuda muito na hora de achar as coisas
- Clonar repositório é basicamente "baixar" o projeto do GitHub pro meu PC
- Todo commit precisa ter uma mensagem clara do que eu fiz
- Depois de commitar, preciso dar `push` pra subir tudo pro GitHub

## Comandos que usei na prática
```bash
# 1. Baixar o projeto do GitHub
git clone <URL_DO_REPOSITORIO>

# 2. Ver o que mudou
git status

# 3. Adicionar meu arquivo de resumo
git add 3-bimestre/semana-15/aula-01.md

# 4. Salvar com uma mensagem explicando
git commit -m "docs: adiciona resumo da semana 15 aula 01"

# 5. Enviar pro GitHub
git push