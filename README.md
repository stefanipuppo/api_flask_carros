# 🚗 Projeto Flask para Gerenciamento de Carros
Este projeto é uma aplicação Flask para gerenciar uma lista de carros.  
Ele oferece dois endpoints principais: um para obter a lista de carros disponíveis e outro para adicionar novos carros.

## 🛠️ Requisitos
- Python 3.7 ou superior  
- Flask (instale com pip install Flask)  
- Um arquivo bd.py contendo uma lista de carros

## 🚀 Como Executar
Clone ou faça o download deste repositório.  
Instale as dependências necessárias com pip install Flask.  
Execute a aplicação com python app.py.  
Acesse a aplicação pelo navegador ou por ferramentas como Postman no endereço http://127.0.0.1:5000.

## 🌐 Endpoints Disponíveis
### 📜 GET /carros
Este endpoint retorna a lista de todos os carros disponíveis no sistema.  
A resposta inclui uma mensagem e a lista de carros com seus detalhes.

### ✍️ POST /carros
Este endpoint permite adicionar um novo carro ao sistema.  
Para isso, envie os dados do carro no corpo da requisição como JSON.   
A resposta indicará se o carro foi adicionado com sucesso, com os detalhes do carro recém-adicionado.

## 📂 Estrutura do Projeto
- app.py: Contém o código principal da aplicação Flask.
- bd.py: Contém a lista inicial de carros, que é usada como um banco de dados em memória.
