# 🧾 Sistema de Gestão de Funcionários - Startup de Tecnologia

Este projeto é parte de um estudo de caso acadêmico que simula um sistema simples de gerenciamento de funcionários para uma startup de tecnologia, desenvolvido com HTML, CSS, JavaScript e Docker.

---

## 🎯 Objetivo

Permitir o cadastro, listagem, edição, exclusão e geração de relatórios de funcionários, com armazenamento em memória via JavaScript e renderização dinâmica em HTML.

---

## 📌 Funcionalidades

### 🔹 Exercício 1: Cadastro e Listagem de Funcionários
- Formulário HTML com campos: Nome, Idade, Cargo, Salário
- Classe `Funcionario` com atributos, `get/set`, `toString()`
- Funcionários armazenados em array de objetos
- Exibição dinâmica em tabela HTML

### 🔹 Exercício 2: Edição e Exclusão
- Botão "Excluir" para remover funcionário
- Botão "Editar" para carregar dados no formulário
- Atualização dos dados com métodos da classe e DOM
- Eventos com funções anônimas

### 🔹 Exercício 3: Funções Anônimas e Arrow Functions
- Refatoração de eventos para arrow functions
- Manipulação de array com funções lambda
- Substituição de funções anônimas tradicionais

### 🔹 Exercício 4: Relatórios com Streams JS
- Listar funcionários com salário > R$ 5000
- Calcular média salarial
- Listar cargos únicos (sem repetição)
- Lista de nomes em maiúsculo
- Uso de `map`, `filter`, `reduce`, `Set()`

---

## 🐳 Docker

O sistema roda em um ambiente isolado com **Docker + Nginx**.

### ✅ Como executar:

```bash
# Build da imagem
docker build -t sistema-funcionarios .

# Rodar o container
docker run -d -p 8082:80 --name funcionarios-app sistema-funcionarios
```

Acesse via navegador: [http://localhost:8082](http://localhost:8082)

---

## 🗃️ Estrutura Esperada

```
/sistema-funcionarios/
├── index.html         # Página principal
├── script.js          # Código JS com classes, eventos e relatórios
├── style.css          # Estilização
├── Dockerfile         # Configuração do container
```

---

## 🌐 Tecnologias

- HTML5
- CSS3
- JavaScript (ES6+)
- Docker (Nginx)
- Git e GitHub

---

## 🧪 Como testar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/sistema-funcionarios.git
   cd sistema-funcionarios
   ```

2. Construa e execute com Docker:
   ```bash
   docker build -t sistema-funcionarios .
   docker run -d -p 8082:80 sistema-funcionarios
   ```

3. Acesse: `http://localhost:8082`
   
