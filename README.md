# 🌳 Árvores AVL - Estruturas de Dados (Java)

**Autora:** Beatriz Dornelles  
**Disciplina:** Estruturas de Dados II  
**Tema:** Árvores AVL  
**Linguagem:** Java

---

## 🎯 Objetivo
Explicar de forma clara e prática o funcionamento de uma **Árvore AVL**, uma estrutura de dados que mantém seu equilíbrio automaticamente, garantindo eficiência nas operações de **busca**, **inserção** e **remoção**.


## 💻 Código-Fonte

Arquivo principal: `AVLTree.java`

```bash
javac AVLTree.java
java AVLTree
```

Durante a execução, o programa insere os valores `10, 20, 30, 40, 50, 25` e mostra o resultado da **travessia pré-ordem** após cada inserção.

---

## 🧠 Conceitos Explicados

| Conceito | Descrição |
|-----------|------------|
| **Fator de Balanceamento** | Diferença entre as alturas das subárvores esquerda e direita. Deve ser -1, 0 ou 1. |
| **Rotação Simples** | Corrige desequilíbrio em linha (LL ou RR). |
| **Rotação Dupla** | Corrige desequilíbrio em zigue-zague (LR ou RL). |
| **Complexidade** | Inserção, remoção e busca em O(log n). |

---

## 🧾 Estrutura do Projeto

```
📁 avl-tree
 ┣ 📜 AVLTree.java
 ┣ 📜 README.md
```

> “Equilibrar a vida é tão importante quanto equilibrar uma árvore.” 🌱
