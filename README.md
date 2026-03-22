# 📚 Estudos de Git e GitHub

---

# 📚 Estudos de Git e GitHub - Dia 21/03

---

## 🚀 Conteúdo estudado

Hoje aprofundei meus conhecimentos em Git e GitHub, entendendo o fluxo completo de trabalho com repositórios locais e remotos.

### 📌 Tópicos abordados:

* Criando e clonando repositórios
* Salvando alterações no repositório local
* Desfazendo alterações
* Enviando e baixando alterações (local ↔ remoto)
* Trabalhando com branches
* Comandos úteis no dia a dia

---

## 📦 Criando e clonando repositórios

### Criar repositório local

```bash
mkdir nome-do-projeto
cd nome-do-projeto
git init
```

> Inicializa um repositório Git na pasta

---

### Clonar repositório remoto

```bash
git clone URL_DO_REPOSITORIO
```

> Baixa um projeto do GitHub para sua máquina

---

## 💾 Salvando alterações no repositório local

### Verificar estado do projeto

```bash
git status
```

> Mostra arquivos modificados

---

### Adicionar arquivos (stage)

```bash
git add .
```

> Adiciona todos os arquivos para o commit

---

### Criar commit

```bash
git commit -m "mensagem do commit"
```

> Salva uma versão do projeto

---

## ↩️ Desfazendo alterações

### Desfazer mudanças em arquivo

```bash
git checkout -- nome-do-arquivo
```

---

### Remover arquivo do stage

```bash
git reset nome-do-arquivo
```

---

### Voltar último commit (mantendo arquivos)

```bash
git reset --soft HEAD~1
```

---

## ☁️ Trabalhando com repositório remoto

### Conectar repositório local ao remoto

```bash
git remote add origin URL_DO_REPOSITORIO
```

---

### Enviar código para o GitHub (primeiro envio)

```bash
git push -u origin main
```

---

### Enviar alterações

```bash
git push
```

---

### Baixar alterações

```bash
git pull
```

---

## 🔄 Fluxo completo (LOCAL → REMOTO)

1. Criar/editar arquivos
2. `git status`
3. `git add .`
4. `git commit -m "mensagem"`
5. `git push`

---

## 🌿 Trabalhando com branches

### Criar branch

```bash
git branch nome-da-branch
```

---

### Trocar de branch

```bash
git checkout nome-da-branch
```

---

### Criar e trocar

```bash
git checkout -b nome-da-branch
```

---

### Mesclar branch

```bash
git merge nome-da-branch
```

---

## 🧠 Comandos úteis no dia a dia

* `git status` → Estado do repositório
* `git log` → Histórico
* `git diff` → Diferenças
* `git branch` → Listar branches

---

## 🧠 O que eu entendi

Hoje aprendi o fluxo completo do Git, desde a criação de um repositório até o envio das alterações para o GitHub.

Entendi a diferença entre repositório local e remoto e como eles se sincronizam.

---

## 📌 Próximos passos

* Praticar conflitos de merge
* Criar projetos reais com Git
* Aprender Git avançado (rebase, stash)

---

# 📅 Dia 20/03

## 🚀 Conteúdo estudado

Hoje tive meu primeiro contato com Git e GitHub no bootcamp de Java.

Aprendi:

- O que é Git
- O que é GitHub
- Diferença entre Git e GitHub
- Instalação e configuração inicial
- Integração com VS Code

---

## 🧠 O que é Git?

Git é um sistema de controle de versão.

Ele serve para:

- Salvar versões do código
- Acompanhar mudanças
- Voltar para versões anteriores
- Trabalhar em equipe

---

## 🌐 O que é GitHub?

GitHub é uma plataforma online onde armazenamos repositórios Git.

Com ele, podemos:

- Salvar código na nuvem
- Compartilhar projetos
- Trabalhar em equipe
- Acessar projetos de qualquer lugar

---

## ⚖️ Diferença entre Git e GitHub

- Git → ferramenta (instalada no computador)
- GitHub → plataforma online

---

## ⚙️ Configuração inicial do Git

### Configurar nome de usuário

```bash
git config --global user.name "Seu Nome"

```
---
# 📚 Estudos de Java - Dia 19/03

<!-- 
Início da jornada no Java (base e fundamentos)
-->

## 🚀 Conteúdo estudado

Hoje reiniciei meus estudos em Java do zero, com foco em entender o ecossistema da linguagem e preparar o ambiente de desenvolvimento.

---

## ☕ Introdução ao Java

<!-- 
Contexto da linguagem
-->

Aprendi sobre a história da linguagem Java e sua importância no mercado.

### 📌 Onde o Java é utilizado:

- Backend
- Sistemas corporativos
- Aplicações Android

Também tive uma visão inicial da área de programação com Java.

---

## ⚙️ Configuração do ambiente

<!-- 
Primeiro passo de qualquer dev
-->

Instalei o JDK (Java Development Kit).

### 🧠 Entendimento:

O JDK é responsável por:

- Compilar o código (`javac`)
- Executar programas Java (JVM)

Agora já consigo rodar códigos Java localmente.

---

## 🏗️ Gerenciamento de Build

<!-- 
Conceito mais avançado (ótimo que você já viu isso cedo)
-->

Aprendi que **build** é o processo de transformar código fonte em algo executável.

### 🔄 Esse processo envolve:

- Compilação (`.java → .class`)
- Testes (em alguns casos)
- Empacotamento

Também entendi a importância da automação nesse processo.

### 🛠️ Ferramentas:

- Maven → mais padrão
- Gradle → mais flexível (**minha escolha inicial**)

---

## 🖥️ Configuração da IDE

<!-- 
Ambiente de desenvolvimento
-->

Conheci algumas das principais IDEs:

- IntelliJ
- Eclipse
- VS Code

Optei pelo **VS Code** por já ter familiaridade.

---

## 💻 Primeiros contatos práticos

<!-- 
Aqui começa a prática real
-->

- Escrevi meus primeiros códigos em Java
- Compilei arquivos manualmente
- Executei programas no terminal

### 🔁 Fluxo básico aprendido:

1. Escrever código
2. Compilar
3. Executar

---

## 🧠 O que eu entendi

<!-- 
Parte mais importante
-->

Antes de programar de fato, é essencial entender o ecossistema da linguagem.

Hoje foi um dia focado em base e preparação para evoluir com mais segurança nos próximos conteúdos.

---

## 📌 Próximos passos

<!-- 
Conexão com os próximos dias
-->

- Sintaxe básica (variáveis e tipos)
- Estruturas condicionais (if/else)
- Laços de repetição (for, while)
