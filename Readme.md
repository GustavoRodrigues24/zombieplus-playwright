# Playwright Zombie Edition - Testes Automatizados 🧟‍♂️

![poster](https://raw.githubusercontent.com/qaxperience/thumbnails/main/playwright-zombie.png)

## 🤘 Sobre o Projeto

Este é o repositório oficial do projeto de testes automatizados para o sistema **Zombie Plus**, desenvolvido durante o curso **Playwright Zombie Edition** da QA Experience.

O Playwright é uma ferramenta de automação de testes web moderna e de código aberto, mantida pela Microsoft. Ele permite a criação de testes robustos e confiáveis, simulando interações de usuários em navegadores como Chromium, Firefox e WebKit.

---

## 💻 Tecnologias Utilizadas

Este projeto utiliza um conjunto de tecnologias modernas para automação e desenvolvimento:

* **Node.js**: Ambiente de execução para JavaScript.
* **Playwright**: Framework principal para automação de testes web.
* **JavaScript**: Linguagem de programação para a escrita dos testes.
* **Faker**: Biblioteca para geração de dados de teste dinâmicos.
* **PostgreSQL**: Banco de dados utilizado pela aplicação sob teste.

---

## 🚀 Como Executar o Projeto

Siga os passos abaixo para configurar e executar os testes em seu ambiente local.

### 1. Pré-requisitos

Antes de começar, certifique-se de que você tem o **Node.js** instalado.

### 2. Instalação

Clone o repositório e instale as dependências do projeto:

```bash
# Clone este repositório
git clone [https://SEU-REPOSITORIO-AQUI.git](https://SEU-REPOSITORIO-AQUI.git)

# Acesse a pasta do projeto
cd nome-da-pasta

# Instale as dependências
npm install
```

### 3. Executando os Testes

Você pode executar os testes de diferentes maneiras:

```bash
# Executar todos os testes em modo headless (sem interface gráfica)
npx playwright test

# Executar os testes com a interface gráfica do Playwright (UI Mode)
npx playwright test --ui

# Executar os testes em um navegador específico (ex: chrome)
npx playwright test --project=chromium
```

### 4. Visualizando os Relatórios

Após a execução, um relatório detalhado dos testes é gerado. Para visualizá-lo, execute o comando:

```bash
npx playwright show-report
```

---

<p align="center">
  Curso disponível na <a href="https://qaxperience.com">QA Experience</a>.
</p>
