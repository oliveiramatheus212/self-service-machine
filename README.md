# 🍔 Self-Service Machine - Totem de Pedidos

Uma aplicação web interativa para um totem de auto-atendimento de fast food, permitindo que os clientes façam seus pedidos de forma rápida e intuitiva.

## 📋 Características

✨ **Catálogo Interativo**: Visualize produtos com imagens e preços

- Big Mac, Mc Chicken, Double Cheese Burger
- Acompanhamentos: Batata frita, Mc Nuggets, Salada
- Bebidas: Coca Cola, Ice Tea, Água

🛒 **Gerenciamento de Pedidos**:

- Clique nos produtos para adicioná-los ao pedido
- Ajuste a quantidade com os botões + e -
- Visualize o resumo em tempo real

💰 **Resumo Automático**:

- Cálculo instantâneo do total
- Tabela com detalhes de cada item selecionado

📱 **Interface Responsiva**:

- Design adaptável para diferentes tamanhos de tela
- Perfeito para totens touchscreen

## 🛠️ Tecnologias Utilizadas

- **Vue3** - Estrutura
- **HTML5** - Estrutura
- **CSS3** - Estilização responsiva
- **JavaScript Vanilla** - Lógica da aplicação

## 🚀 Como Executar

### Opção 1: Live Server (VS Code) - ⭐ Recomendado

1. **Instale a extensão Live Server no VS Code:**
   - Abra VS Code
   - Vá em `Extensions` (Ctrl+Shift+X)
   - Procure por "Live Server"
   - Clique em instalar (desenvolvida por Ritwick Dey)

2. **Execute o servidor:**
   - Clique com botão direito em `index.html`
   - Selecione "Open with Live Server"
   - Seu navegador abrirá automaticamente em `http://localhost:5500`

3. **Parando o servidor:**
   - Clique em "Port: 5500" na barra de status do VS Code

### Opção 2: Abrir Diretamente

Se não quiser usar servidor local:

- Clique duas vezes em `index.html` para abrir no navegador padrão
- ⚠️ Nota: Alguns recursos podem não funcionar corretamente sem um servidor local

## 📁 Estrutura do Projeto

```
self-service-machine/
├── index.html       # Estrutura HTML principal
├── scripts.js       # Lógica da aplicação com Vue.js
├── style.css        # Estilos e layout
├── img/             # Imagens dos produtos
│   ├── big-mac.png
│   ├── mc-chicken.png
│   ├── double-cb.png
│   ├── fries.png
│   ├── nuggets.png
│   ├── salad.png
│   ├── cola.png
│   ├── lipton.png
│   └── water.png
└── README.md        # Este arquivo
```

## 💻 Como Usar a Aplicação

1. **Selecionar Produtos**: Clique em qualquer produto para adicioná-lo ao pedido
2. **Ajustar Quantidade**: Use os botões `+` e `-` para aumentar ou diminuir a quantidade
3. **Ver Resumo**: Na lateral direita, acompanhe os itens selecionados e o total
4. **Remover Itens**: Clique novamente no produto para removê-lo do pedido

## 🎨 Personalização

Para adicionar novos produtos, edite o arquivo `scripts.js`:

```javascript
{
  photo: "img/seu-produto.png",
  name: "Nome do Produto",
  price: 9.99,
  active: false,
  quantity: 1,
}
```

Certifique-se de adicionar a imagem na pasta `img/`.

## 📝 Licença

Este projeto é um estudo de caso educacional.

---

<img width="895" height="682" alt="image" src="https://github.com/user-attachments/assets/eeead0aa-01de-47db-a991-39c15fb3e191" />

