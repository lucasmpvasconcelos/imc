# 🧮 Calculadora de IMC

Uma aplicação web desenvolvida em **Python** utilizando o framework **Django**, que permite calcular o **Índice de Massa Corporal (IMC)** de forma rápida e intuitiva.

## 📋 Sobre o Projeto

A Calculadora de IMC foi criada com o objetivo de praticar conceitos de desenvolvimento web com Django, incluindo manipulação de formulários, processamento de dados enviados pelo usuário e renderização dinâmica de páginas HTML.

O usuário informa seu **peso** e **altura**, e o sistema calcula automaticamente o IMC, exibindo também sua classificação conforme os padrões da Organização Mundial da Saúde (OMS).

---

## 🚀 Funcionalidades

* Cálculo automático do IMC.
* Classificação do resultado.
* Interface simples e intuitiva.
* Processamento de formulários com Django.
* Exibição do resultado em tempo real.

---

## 📊 Classificação do IMC

| IMC                 | Classificação      |
| ------------------- | ------------------ |
| Menor que 18,5      | Abaixo do peso     |
| 18,5 – 24,9         | Peso normal        |
| 25,0 – 29,9         | Sobrepeso          |
| 30,0 – 34,9         | Obesidade Grau I   |
| 35,0 – 39,9         | Obesidade Grau II  |
| Maior ou igual a 40 | Obesidade Grau III |

---

## 🛠️ Tecnologias Utilizadas

* Python 3
* Django
* HTML5
* CSS3

---

## 📂 Estrutura do Projeto

```text
calculadora-imc/
│
├── app/
├── templates/
├── static/
├── manage.py
├── requirements.txt
└── README.md
```

---

## ⚙️ Como Executar o Projeto

### 1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
```

### 2. Entre na pasta

```bash
cd seu-repositorio
```

### 3. Crie um ambiente virtual

Windows

```bash
python -m venv venv
venv\Scripts\activate
```

Linux/Mac

```bash
python3 -m venv venv
source venv/bin/activate
```

### 4. Instale as dependências

```bash
pip install -r requirements.txt
```

### 5. Execute as migrações

```bash
python manage.py migrate
```

### 6. Inicie o servidor

```bash
python manage.py runserver
```

Acesse:

```text
http://127.0.0.1:8000/
```

---

## 🎯 Objetivo

Este projeto foi desenvolvido para colocar em prática conhecimentos em:

* Desenvolvimento Web com Django;
* Manipulação de formulários;
* Estruturas condicionais em Python;
* Templates do Django;
* Organização de aplicações web.

---

## 📸 Demonstração

Adicione aqui uma imagem ou GIF da aplicação em funcionamento.

```text
docs/imagens/calculadora-imc.png
```

---

## 👨‍💻 Autor

**Lucas Vasconcelos**

GitHub: https://github.com/lucasmpvasconcelos

---

## 📄 Licença

Este projeto está disponível para fins de estudo e aprendizado.
