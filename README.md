# Sistema de Gestão de Estoque - Mini Mercado

Este projeto é uma releitura do sistema de gestão de estoque originalmente desenvolvido para a disciplina de Orientação a Objetos (OO):

- 🔗 [Projeto original - MiniProjetoUML](https://github.com/samarawwleticia/MiniProjetoUML)  
- 🔁 [Fork do projeto original](https://github.com/Carlos-kadu/MiniProjetoUML)

Agora, o sistema está sendo reconstruído e aprimorado utilizando **Python** e o framework **Django**, como parte da disciplina **Técnicas de Programação em Plataformas Emergentes (TPPE)**.

O objetivo é entregar uma solução simples, eficiente e organizada para facilitar a administração de estoques em múltiplas unidades comerciais.

---

## 🚀 Tecnologias Utilizadas

- Python 3.11+
- Django 5.x
- Django REST Framework
- PostgreSQL
- Docker e Docker Compose
- Pytest
- Flake8

---

## 🐳 Como Executar o Projeto

Todo o ambiente está dockerizado, basta ter o Docker e o Docker Compose instalados.

### 1. Navegue até a pasta `src` do projeto:

```bash
cd src
```

### 2. Suba o ambiente:

```bash
docker-compose up --build
```

O backend Django estará disponível em: [http://localhost:8000/](http://localhost:8000/)

A documentação da API estará disponível em: [http://localhost:8000/swagger/](http://localhost:8000/swagger/)

> Os testes e a análise de código com Flake8 são executados automaticamente junto com o backend e o banco de dados. Não é necessário rodá-los manualmente.

---

## 📚 Documentação

- [Kanban do Projeto](https://github.com/users/Carlos-kadu/projects/1)
- Documentação da API disponível em `/swagger/` após rodar o servidor.
- [Diagrama de Classes UML (PDF)](docs/DIAGRAMA%20DE%20CLASSES%20UML%20-%20Mini%20mercado.pdf)
- [Diagrama Físico do Banco (PNG)](docs/Diagrama%20de%20dados.png)


## 🔗 Frontend
- Repositório do frontend: [https://github.com/Carlos-kadu/Frontend-Mini-Mercado](https://github.com/Carlos-kadu/Frontend-Mini-Mercado)
- Deploy: [https://frontend-mini-mercado.vercel.app](https://frontend-mini-mercado.vercel.app)

## 🎨 Protótipo Figma
- [Protótipo no Figma](https://www.figma.com/design/P7Iw6NzhkGvnL3Vu72kfgO/Mini-Mercado---TPPE?node-id=0-1&t=sjhqkpkcfMfer1Qw-1)