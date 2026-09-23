# 📝 Lista de Tarefas (To-Do List) com Funções — Python
 
Evolução do meu primeiro projeto de to-do list em terminal, agora reorganizado com **funções**, como parte dos meus estudos de Python.
 
## 🎯 Funcionalidades
 
- **Adicionar tarefa**: inclui uma nova tarefa na lista
- **Ver tarefas**: exibe todas as tarefas numeradas
- **Remover tarefa**: remove uma tarefa específica pelo número
- **Sair**: encerra o programa
## 🚀 Como executar
 
```bash
python todo.py
```
 
## 🧠 Conceitos praticados
 
- Tudo do projeto anterior (listas, `while`, `if`/`elif`/`else`, `input`, f-strings, laços aninhados)
- **Funções** (`def`): organizar o código em blocos nomeados e reutilizáveis
- **Parâmetros**: como uma função recebe informação de fora (ex: a lista de tarefas)
- **Retorno (`return`)**: como uma função devolve um valor para ser usado fora dela
- Diferença entre `print()` (só exibe) e `return` (devolve o valor para reuso)
- Separar **definição** de função (uma vez, no topo do arquivo) de **chamada** de função (no momento certo, dentro do menu)
## 🔧 Estrutura do código
 
O programa tem 3 funções principais:
 
- `adicionar_tarefas(lista)` — pergunta uma nova tarefa e adiciona na lista
- `mostrar_tarefas(lista)` — exibe todas as tarefas numeradas
- `remover_tarefa(lista)` — mostra a lista, pergunta qual remover, e remove
O menu principal (`while True`) ficou mais limpo, só chamando cada função na opção certa, em vez de ter toda a lógica escrita diretamente ali.
 
## 📌 Status
 
Projeto de aprendizado — próximas melhorias possíveis incluem salvar as tarefas em um arquivo (para não perder ao fechar o programa) e validação de entradas inválidas.
