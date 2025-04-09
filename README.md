# 📚 Sistema de Livraria em MySQL

Um banco de dados simples para gerenciar livros, autores, preços e estoque.

## 🛠 Como Usar
1. Execute o script no MySQL (Workbench, XAMPP, etc.).
2. Modifique conforme necessário (adicione mais tabelas, como `vendas` ou `clientes`).

## 🔍 Exemplo de Consultas
`sql
- Livros abaixo de R$30
SELECT titulo, autor FROM livros WHERE preco < 30.00;
