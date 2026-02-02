# Sistema de Controle de Estoque em Python  
**Estudo de Caso – Desenvolvimento de Solução Computacional**

Este projeto consiste no desenvolvimento de um sistema simples de controle de estoque utilizando a linguagem Python. O trabalho foi elaborado como estudo de caso para a disciplina, com o objetivo de aplicar conceitos fundamentais de lógica de programação, estruturas de dados e interação com o usuário via terminal.

---

## 1. Objetivo do Projeto

O objetivo principal é implementar um sistema capaz de gerenciar produtos em estoque, permitindo operações essenciais como cadastro, atualização, exclusão e visualização de itens.  
O projeto busca demonstrar:

- Organização lógica do código  
- Manipulação de listas e dicionários  
- Estruturação de funções  
- Tratamento básico de erros  
- Interação com o usuário por meio de menus textuais  

---

## 2. Funcionalidades Implementadas

O sistema contempla quatro operações principais:

### **2.1 Adicionar Produto**
O usuário informa:
- Nome do produto  
- Preço  
- Quantidade disponível  

Caso o produto já exista, o sistema atualiza seus dados.

### **2.2 Atualizar Produto**
Permite modificar:
- Preço  
- Quantidade  

A seleção é feita com base no número do produto exibido na listagem.

### **2.3 Excluir Produto**
O sistema apresenta o estoque atual e solicita o número do produto a ser removido, incluindo confirmação antes da exclusão definitiva.

### **2.4 Visualizar Estoque**
Exibe todos os produtos cadastrados, apresentando:
- Nome  
- Preço  
- Quantidade  

---

## 3. Estrutura Lógica do Sistema

O sistema utiliza uma lista denominada `estoque`, onde cada produto é armazenado como um dicionário:

```python
{"Nome": nome, "Preço": preco, "Quantidade": quantidade}
```
A aplicação é organizada em funções, garantindo modularidade e clareza:
• 	 – apresenta as opções disponíveis
• 	 – insere ou atualiza itens
• 	 – lista os produtos cadastrados
O programa principal utiliza um loop contínuo para manter o menu ativo até que o usuário opte por encerrar.

## 4. Execução do Sistema

### Pré-requistos
- Python 3 instalado
  
### Como executar
python estoque.py

## 5. Estrutura do Projeto
```
estoque/
│── estoque.py        # Código-fonte principal
│── README.md         # Documentação do projeto
```

## 6. Considerações Técnicas
O projeto demonstra domínio de:
- Estruturas condicionais
- Estruturas de repetição
- Manipulação de listas e dicionários
- Funções e modularização
- Tratamento de exceções (ValueError, IndexError)
- Boas práticas de interação com o usuário
Esses elementos são fundamentais para o desenvolvimento de sistemas mais complexos e servem como base para aplicações futuras, como interfaces gráficas, persistência de dados e integração com bancos de dados.

## 7. Possíveis Melhorias Futuras
- Implementação de persistência de dados (JSON, CSV ou banco de dados)
- Criação de interface gráfica (Tkinter, PyQt ou web)
- Inclusão de filtros e ordenação de produtos
- Geração de relatórios automáticos
- Modularização avançada em múltiplos arquivos
- Desenvolvimento de API para integração com outros sistemas



