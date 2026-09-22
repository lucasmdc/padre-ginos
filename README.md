# Padre Gino's

![Status](https://img.shields.io/badge/status-in%20progress-gold)
![Type](https://img.shields.io/badge/portfolio-reference-blue)
![License](https://img.shields.io/badge/license-MIT-lightgrey)

> 🚀 **Status:** Projeto em progresso.

## 📌 Sobre o projeto

O **Padre Gino's** é um projeto desenvolvido a partir da plataforma de ensino **Master.dev** (anteriormente chamada **Frontend Masters**).

## 🎯 Objetivo

[...]

> Pendência: Gerar o contéudo!

## ⚙️ Pré-requisitos

Para executar o projeto, recomenda-se ter instalado:

- [`Node.js` **20.16.0**](https://nodejs.org/download/release/v20.16.0/)
- `npm` **10.8.1**
- [`nvm`](https://github.com/nvm-sh/nvm?tab=readme-ov-file#installing-and-updating) _(recomendado)_

> O `npm` acompanha a instalação padrão do `Node.js`.

Para verificar a versão instalada do `npm`:

```sh
npm -v
```

### ⌨️ Usando `nvm`

Instale a versão utilizada neste projeto:

```sh
nvm install 20.16.0
```

Em seguida, dentro do projeto, execute:

```sh
nvm use
```

> O comando `nvm use` utilizará a versão definida no arquivo `.nvmrc` presente no diretório atual.

## ▶️ Como executar

### 🔹 Aplicação

```bash
$ npm run dev
```

### 🔹 Api

```bash
$ cd api
$ npm run dev
```

### 📦 Sistema de módulos

Este projeto utiliza o padrão `ESModule`, definido no arquivo `package.json`:

```json
{
  "type": "module"
}
```
