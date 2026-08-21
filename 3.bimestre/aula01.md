# Introdução
## O **Markdawn** é uma linguagem de marcação simples para formatar textos de maneira rápida e legivel. No github e amplamente usado para;
--- 
- arquivos "README.md"
- documentação de projetos
- anotações técnicas
- instruções de instalações
- registros de aulas
- issues e pull requets
---
A extensão padrão do arquivo **Markdawn** é **md**


# 1- O que é Markdown?
---

 Markdawn permite aplicar formatação simples em um texto usando caracteres simples;
 
 Exemplo:
   
        # Meu projeto

Este projeto foi desenvolvida durante a aula de **Versionamento de código**

---


## Tecnologias
- Git
- GitHub
- VScode
  
No Github, esse conteudo sera apresentado de forma formatada com titulo, texto em negrito e lista

---

# 2- Criando um arquivo Markdown
---

Na Visual Code Studio
- Abra a pasta do projeto
- Clique em "new file"
- Informe o nome do arquivo

Exemplo:

        README.md

Para registros de aulas, também podem ser utilizados nomes como;

- Semana-01.md
- Semana-02.md
- Aula-01.md
  
---


## Boas Práticas 
---
*Prefira nomes*:

- curtos
- descrivos
- escrito em letras minúsculas
- sem acentos
- sem espaços
- separados por hífen quando necessário

*Recomendado*

- resumo-git.md
- aula-01.md
- comandos-git.md
  
---

## Evite
---

- resumo git.md
- aula 01.md
- atividade prática github.md
- meu arquivo novo.md

# 3- Titulo e subtitulo
Markdawn utiliza a caracter # para criar titulo 
```markdown
# Titulo Principal
## Titulo Nivel 2
### Titulo Nivel 3
#### Titulo Nivel 4
##### Ttulo Nivel 5
###### Titulo Nivel 6
```
        # Titulo Principal
        ## Titulo Nivel 2
        ### Titulo Nivel 3
        #### Titulo Nivel 4
        ##### Ttulo Nivel 5
        ###### Titulo Nivel 6
---

# Boa Pratica
Utilize uma estrutura hierarquica

Exemplo: 

```markdown
# semana 08 - introdução
## objetivos da aula
## conceitos aprendidos
### repositorio
### commit
### breach
### atividade pratica
## conclusao
```

        # semana 08 - introdução
        ## objetivos da aula
        ## conceitos aprendidos
        ### repositorio
        ### commit
        ### breach
        ### atividade pratica
        ## conclusao

Evite pular niveis sem necesidade como;


# titulo
### subtitulo
´´´

# 4- Paragrafos
Para criar um paragrafo, deixe uma linha em branco entre os textos
    
Git é um sistema de controle distribuido

Ele permite registrar e acompanhar alterações realizadas nos arquivos de um projeto

---

# 5- Negrito
Utiliza 2 asteriscos (**)

**Texto em negrito**

O **GitHub** é um sistema de controle de versão 

---

# 6- Italico
utiliza 1 asteristico (*)

*texto em italico*

O comando *git status* permite o estado do repositorio

Entretando para representar comdandos, o ideial é us=tilizar a formatação de codigo

---

# 7- Negrito e Italico
***texto em negrito e italico***

***git add***

---

# 8- Lista não ordenadas
Utilize antes de cada item

- git 
- github
- visual code studio

Tambem é possivel criar niveis

- git
   - commit
   - breach
   - merge
 - Github
   - repositorio
   - pull request
   - issues
---
# Boa Pratica
Utilize para representar

- conceitos
- requisitos
- tecnologias
- etapas
- recursos

---

# 9- Listas Numeradas

- 1. criar o repositorio
- 2. adicione os arquivos
- 3. criar o commit
- 4. enviar para github
  
Ideal para procedimentos que precisam ser executadas em ordem

---

# 10- Listas de tarefas - checklists
O github permite criar caixas de seleção

- [x] criar o repositorio
- [x] criar o README
- [ ] realizar a atividade
- [ ] criar o commit
- [ ]  enviar para o github
  
Esse recurso é especialmente util para acompanhar atividades e projetos



