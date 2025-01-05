# Expense Tracker App

## Descrição
O **Expense Tracker** é uma aplicação simples desenvolvida em Python para registrar e monitorar despesas. O programa permite ao usuário adicionar novas despesas, listar todas as despesas registradas, mostrar o total gasto e filtrar as despesas por categoria.

## Funcionalidades
- **Adicionar despesa:** O usuário pode adicionar uma nova despesa com um valor e uma categoria.
- **Listar todas as despesas:** Exibe todas as despesas registradas.
- **Mostrar total de despesas:** Calcula e exibe o total das despesas registradas.
- **Filtrar despesas por categoria:** Permite ao usuário filtrar as despesas por categoria, exibindo apenas as despesas dessa categoria.

## Tecnologias Usadas
- **Python:** Linguagem de programação principal para implementar a lógica.
- **Funções do Python:** Utiliza funções como `map()`, `filter()`, e `sum()` para realizar operações com as despesas.

## Como Executar o Projeto
1. Clone este repositório:
    ```bash
    git clone https://github.com/Hachirojai/expense-tracker.git
    ```
2. Navegue até o diretório do projeto:
    ```bash
    cd expense-tracker
    ```
3. Execute o código Python:
    ```bash
    python expense_tracker.py
    ```

## Exemplo de Uso
1. **Adicionar despesa:**
    ```
    Enter your choice: 1
    Enter amount: 100
    Enter category: Food
    ```

2. **Listar despesas:**
    ```
    Enter your choice: 2
    All Expenses:
    Amount: 100, Category: Food
    ```

3. **Mostrar total de despesas:**
    ```
    Enter your choice: 3
    Total Expenses:  100.0
    ```

4. **Filtrar despesas por categoria:**
    ```
    Enter your choice: 4
    Enter category to filter: Food
    Expenses for Food:
    Amount: 100, Category: Food
    ```

5. **Sair do programa:**
    ```
    Enter your choice: 5
    Exiting the program.
    ```

## Contribuições
Sinta-se à vontade para contribuir com melhorias ou correções. Para isso, basta criar um fork deste repositório e enviar um pull request com suas mudanças.

## Licença
Este projeto é licenciado sob a [MIT License](LICENSE).
