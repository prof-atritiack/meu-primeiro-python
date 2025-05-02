# Meu Primeiro Projeto com Python

Este repositório foi criado para um **bootcamp introdutório de Python** com duração de 2h30, voltado para iniciantes absolutos. Utiliza o ambiente Google Colab para execução de código e GitHub para versionamento.

---

## 🎓 Objetivo do Bootcamp

Ensinar os primeiros passos em programação com Python, com foco em:  
- Compreensão da lógica de programação  
- Execução no ambiente Google Colab  
- Registro e organização do projeto via GitHub  

---

## 🛠 Ferramentas utilizadas

- [Google Colab](https://colab.research.google.com/)
- [GitHub](https://github.com/)
- Python 3

---

## 📚 Roteiro da Aula (Sequência Sugerida)

| Etapa | Conteúdo                                     | Tipo     | Duração Estimada |
|-------|----------------------------------------------|----------|------------------|
| 1     | Apresentação + Como usar o Colab e GitHub    | Teórico  | 15 min           |
| 2     | `print()` e variáveis (`str`, `int`, `float`) | Prático  | 20 min           |
| 3     | Entrada com `input()` e conversão de tipos   | Prático  | 10 min           |
| 4     | Condicionais (`if`, `elif`, `else`)          | Prático  | 15 min           |
| 5     | Repetições: `for` e `while`                  | Prático  | 20 min           |
| 6     | Listas e iteração                            | Prático  | 10 min           |
| 7     | Funções simples (`def`)                      | Prático  | 10 min           |
| 8     | Mini Projeto: Jogo da Adivinhação            | Prático  | 30 min           |
| 9     | GitHub: salvar notebook + escrever README    | Final    | 20 min           |

---

## 📁 Arquivos disponíveis

- [`bootcamp_python_exercicios.ipynb`](bootcamp_python_exercicios.ipynb) – com os exercícios propostos
- [`bootcamp_python_colab.ipynb`](bootcamp_python_colab.ipynb) – com exemplos resolvidos

---

## 🚀 Executar no Google Colab

- [![Abrir Exercícios](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/prof-atritiack/meu-primeiro-python/blob/main/bootcamp_python_exercicios.ipynb)
- [![Abrir com Soluções](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/prof-atritiack/meu-primeiro-python/blob/main/bootcamp_python_colab.ipynb)

---

## 🧠 Comandos Git úteis

```bash
# Configuração inicial (uma única vez por máquina)
git config --global user.name "Seu Nome"
git config --global user.email "seu@email.com"

# Clonar o repositório do GitHub
git clone https://github.com/prof-atritiack/meu-primeiro-python.git
cd meu-primeiro-python

# Verificar status dos arquivos
git status

# Adicionar arquivos ao controle de versão
git add .

# Criar um commit com uma mensagem
git commit -m "mensagem do commit"

# Subir os arquivos para o GitHub
git push origin main

# Criar novo repositório local e conectar ao GitHub (se necessário)
git init
git remote add origin https://github.com/prof-atritiack/meu-primeiro-python.git
git branch -M main
git push -u origin main
```

---

## ✍️ Autoria

Criado por [André Tritiack](https://github.com/prof-atritiack) como parte de um projeto de ensino introdutório de programação com Python.

---

## 🧰 Apêndice: Principais Comandos Git

Este é um guia rápido para os comandos Git mais usados durante o bootcamp ou em projetos futuros:

| Comando                                 | Função                                               |
|-----------------------------------------|------------------------------------------------------|
| `git config --global user.name`         | Define seu nome de usuário                           |
| `git config --global user.email`        | Define seu e-mail usado no GitHub                    |
| `git clone URL`                         | Clona um repositório remoto                          |
| `git init`                              | Inicia um repositório Git em uma pasta local         |
| `git add .`                             | Adiciona todos os arquivos para serem versionados    |
| `git commit -m "mensagem"`              | Cria um snapshot (commit) com uma mensagem           |
| `git push origin main`                  | Envia as alterações para o GitHub                    |
| `git branch -M main`                    | Renomeia a branch atual para `main`                  |
| `git remote add origin URL`             | Conecta o repositório local ao repositório remoto    |
| `git status`                            | Mostra o status atual dos arquivos no projeto        |
| `git pull`                              | Atualiza seu repositório local com mudanças remotas  |

> ⚠️ Para push via HTTPS, utilize um token pessoal (PAT) no lugar da senha.

---

