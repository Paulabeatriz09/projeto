# Restaurante - App 

## Funcionalidades

- **Cadastro e Login**: Os usuários podem se cadastrar e fazer login para realizar reservas e compras.
- **Cardápio Digital**: Visualização do cardápio com informações detalhadas sobre cada produto (nome, descrição e preço), com a possibilidade de adicionar ao carrinho.
- **Reserva de Eventos**: Permite que os usuários façam reservas para eventos no restaurante, com controle de disponibilidade de data e limite de pessoas.

## Estrutura de Pastas

A estrutura de pastas do projeto é organizada para separar claramente as diferentes funcionalidades e componentes do aplicativo:

APP_BAR/ ├── api/
├── models/
│ ├── Compra.js │ ├── Produto.js │ ├── Reserva.js │ └── User.js ├── assets/
├── context/
│ └── CarrinhoContext.js ├── navigation/
│ └── StackNavigator.js ├── screens/
│ ├── CadastroProdutoScreen.js │ ├── CardapioScreen.js │ ├── CarrinhoScreen.js │ ├── HomeScreen.js │ ├── LoginScreen.js │ ├── PagamentoScreen.js │ ├── RegisterScreen.js │ └── ReservasScreen.js └── App.js

