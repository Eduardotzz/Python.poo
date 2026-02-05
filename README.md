# 🌎 World Guessing Game – Ranking Edition

Projeto educacional desenvolvido em **Python**, aplicando **Programação Orientada a Objetos (POO)** e conceitos de **arquitetura MVC**.  
O jogo utiliza a **API REST Countries** para desafiar o jogador a descobrir países a partir de dicas como **Capital** e **Região**, acumulando pontos e salvando os melhores resultados em um **ranking global**.



## 🎯 Objetivo do Jogo

O jogador deve adivinhar corretamente o país com base nas informações exibidas a cada rodada.  
A cada acerto, pontos são somados e, ao final do jogo, a pontuação é salva em um ranking **Top 5**.



## 🚀 Tecnologias Utilizadas

- **Linguagem:** Python 3.13+
- **Interface Gráfica:** Tkinter (nativo do Python)
- **Banco de Dados:** SQLite3
- **Integração com API:** Requests (REST Countries API)
- **Normalização de Texto:** Unicodedata
- **Lógica e Sorteio:** Random
- **Persistência de Dados:** Datetime + SQLite



## 🧠 Conceitos Aplicados

- Programação Orientada a Objetos (POO)
- Separação de responsabilidades (MVC)
- Consumo de API REST
- Interface gráfica com Tkinter
- Manipulação de banco de dados SQLite
- Normalização de strings (acentos e capitalização)
- Ranking persistente com data e hora



## 📋 Pré-requisitos

Antes de começar, você precisa ter instalado na sua máquina:

1. **Python 3.x**  
   ⚠️ Durante a instalação, marque a opção **"Add Python to PATH"**

2. **VS Code** (ou outro editor de sua preferência)

3. **Conexão com a Internet**  
   Necessária para buscar os países da API na primeira execução



## 🔧 Passo a Passo de Instalação

### 1️⃣ Clonar ou baixar o projeto

Abra o terminal na pasta onde deseja salvar o projeto e execute:

```bash
git clone https://github.com/lkaua-dev/World-Guessing-Game.git
```
## 2️⃣ Instalar dependências

A maioria das bibliotecas já vem com o Python.
Você só precisa instalar a biblioteca de requisições:
```bash
pip install requests
```
## ▶️ Como Executar o Projeto

1. Abra o terminal na pasta raiz do projeto

2. Acesse o diretório correto:
```bash
cd World-Guessing-Game
```

3. Execute o arquivo principal:
```bash
python main.py
```
