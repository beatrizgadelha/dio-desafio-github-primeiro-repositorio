# Introdução ao Git e ao Github

## Navegação via command line interface e instalação

### Comandos básicos para um bom desempenho no terminal

- dir = listar pastas
- cd = possibilita navegar entre as pastas
- cd .. = voltar (retroceder 1 nível na navegação
- cls = limpar o terminal
- cd + letra inicial + TAB = completa atalho
- mkdir = criar uma pasta
- del + nome da pasta = deletar pasta
- rmdir + nome repositório + /s /q = remover repositório

### Tópicos fundamentais para entender o funcionamento do Git

A sigla SHA significa Secure Hash Algorithm (Algoritmo de Hash Seguro), é um conjunto de funções hash criptografadas projetadas pela NSA (agencia de segurança nacional dos EUA)

A encriptação gera um conjunto de characteres identificador d e40 dígitos

openssl sha1

### Objetos internos do Git

Blobs → estrutura básica

\0

![Untitled](C:\Users\beatr\Downloads\Untitled.png)

Trees → Armazena e aponta tipos de blobs diferentes monta a estrutura de onde estão os arquivos

![Untitled](C:\Users\beatr\Downloads\tree.png)

![Untitled](C:\Users\beatr\Downloads\tree2.png)

Commits →

![Untitled](C:\Users\beatr\Downloads\2.png)

### Chave SSH e Token

Chave SSH é uma forma de manter uma conexão segura e encriptada nas maquinas

## Primeiros comandos com Git

### Iniciando o Git e criando um commit

- Git init → iniciar repositório
- Gir add → mover arquivos
- Git commit → criar primeiro commit
- ls -a → lista pastas ocultas

## Ciclo de vida dos arquivos no Git

### Passo a passo no ciclo de vida

![Untitled](C:\Users\beatr\Downloads\vida.png) 

## Introdução ao Git e ao GitHub

### Trabalhando com o GitHub

git remote add origin + https = botar repositório no github

git push origin master
