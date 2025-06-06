# 🐍 Jornada Python - Canal Hashtag

Repositório contendo todos os projetos desenvolvidos durante a **Jornada Python** do Canal Hashtag. Uma imersão completa em Python aplicado ao mercado de trabalho, abordando desde automação até inteligência artificial.

## 📋 Sobre o Evento

A Jornada Python foi um evento de 4 dias focado em projetos práticos e aplicações reais de Python nas principais áreas da tecnologia atual.

## 🚀 Projetos Desenvolvidos

### 📁 Dia 1 - Automação com PyAutoGUI
**Objetivo:** Criar automações para simular interações humanas no sistema  
**Tecnologias:** Python, PyAutoGUI  
**Aplicação:** Otimização de processos repetitivos  

```python
# Exemplo de automação desenvolvida
import pyautogui
import time
```

### 📁 Dia 2 - Análise de Cancelamento de Clientes
**Objetivo:** Analisar dados de cancelamento para extrair insights de negócio  
**Tecnologias:** Python, Pandas, Plotly  
**Aplicação:** Business Intelligence e tomada de decisão baseada em dados  

```python
# Principais bibliotecas utilizadas
import pandas as pd
import plotly.express as px
import plotly.graph_objects as go
```

### 📁 Dia 3 - Score de Crédito com IA
**Objetivo:** Classificar 100.000 clientes bancários usando Machine Learning  
**Tecnologias:** Python, Pandas, Sklearn (KNN)  
**Aplicação:** Sistema de score de crédito para instituições financeiras  

```python
# Algoritmo de classificação
from sklearn.neighbors import KNeighborsClassifier
from sklearn.model_selection import train_test_split
import pandas as pd
```

### 📁 Dia 4 - HashZap (Chat ao Vivo)
**Objetivo:** Desenvolver um sistema de chat em tempo real  
**Tecnologias:** Python, Flask, SocketIO, Simple WebSocket  
**Aplicação:** Sistema de comunicação instantânea web  

```python
# Estrutura base do chat
from flask import Flask
from flask_socketio import SocketIO
```

## 🛠️ Tecnologias Utilizadas

- **Python 3.x**
- **PyAutoGUI** - Automação de interface
- **Pandas** - Manipulação e análise de dados
- **Plotly** - Visualização interativa de dados
- **Sklearn** - Machine Learning (algoritmo KNN)
- **Flask** - Framework web
- **SocketIO** - Comunicação em tempo real
- **Simple WebSocket** - Protocolo de comunicação

## 📊 Estrutura do Repositório

```
jornada-python/
├── dia-1-automacao/
│   ├── automacao.py
│   └── README.md
├── dia-2-analise-dados/
│   ├── analise_cancelamento.py
│   ├── dados/
│   └── README.md
├── dia-3-ia-score/
│   ├── score_credito.py
│   ├── modelo_knn.py
│   ├── dados/
│   └── README.md
├── dia-4-hashzap/
│   ├── app.py
│   ├── templates/
│   ├── static/
│   └── README.md
└── requirements.txt
```

## ⚙️ Como Executar

### Pré-requisitos
- Python 3.7 ou superior
- pip (gerenciador de pacotes Python)

### Instalação
1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/jornada-python.git
cd jornada-python
```

2. Instale as dependências:
```bash
pip install -r requirements.txt
```

3. Execute cada projeto individualmente seguindo as instruções em cada pasta.

## 📚 Principais Aprendizados

- **Automação:** Como Python pode otimizar tarefas repetitivas
- **Data Science:** Análise e visualização de dados para insights de negócio
- **Machine Learning:** Aplicação prática de algoritmos de classificação
- **Web Development:** Desenvolvimento de aplicações web em tempo real

## 🎯 Aplicações Práticas

Cada projeto foi desenvolvido pensando em cenários reais do mercado de trabalho:

- **Automação corporativa** para redução de tempo em tarefas manuais
- **Análise de churn** para retenção de clientes
- **Sistema de score** para aprovação de crédito
- **Chat corporativo** para comunicação interna

## 👨‍💻 Sobre o Desenvolvimento

Projetos desenvolvidos durante a **Jornada Python** do [Canal Hashtag](https://www.hashtagtreinamentos.com/), evento focado em aplicações práticas de Python no mercado de trabalho.

## 🤝 Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para:
- Reportar bugs
- Sugerir melhorias
- Adicionar novos recursos

## 📞 Contato

Desenvolvido por Yago Leme  
LinkedIn: https://www.linkedin.com/in/yago-leme-550845205/ 
Email: lemey592@gmail.com

---

⭐ Se este repositório foi útil para você, considere dar uma estrela!
